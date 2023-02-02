# Day 28 Notes

## API Deployment

### Django Settings Best Practices

> Managing Django Settings: Issues

• Different environments: Typically, multiple environments exist such as local, dev, ci, qa, staging, production, etc. Each environment can have its own specific settings, like the value of DEBUG, verbose logging, additional apps, and mocked data, etc. It's essential to have an approach that can keep all these Django setting configurations organized.

• Sensitive data: SECRET_KEY is present in each Django project, and other sensitive data like DB passwords and API tokens also exist. This sensitive data can't be stored in VCS (version control system) for security reasons.

• Sharing settings between team members: There's a need for a general approach to eliminate human error while working with the settings. A developer might add a third-party app or some API integration and forget to add the corresponding settings, causing real issues on large or even mid-sized projects.

• Django settings are Python code: This can be both a blessing and a curse. It provides a lot of flexibility but can also create problems if the settings.py file contains tricky logic instead of simple key-value pairs.

> Setting Django Configurations: Different Approaches

• settings_local.py: This is the oldest method and still used by many. The basic idea is to extend all environment-specific settings in the settings_local.py file, which is ignored by VCS. The settings.py file contains the default configurations, and the settings_local.py file contains the environment-specific configurations.

  • Pros: Secrets not in VCS.
  
  • Cons: The settings_local.py file is not in VCS, so the environment settings can be lost, and the settings_local.py file can have non-obvious logic.

• Separate settings file for each environment: This approach extends the previous method. It allows keeping all configurations in VCS and sharing default settings between developers. A settings package is created with a file structure that includes base.py and separate files for each environment (ci.py, local.py, staging.py, production.py, etc.).

  • Pros: All environments are in VCS, easy to share settings between developers.
  
  • Cons: Handle secret passwords and tokens and inheritance of settings can be difficult to trace and maintain.

• Environment variables: This approach solves the issue of sensitive data by using environment variables in Django.
  
  • Pros: SECRET_KEY and other sensitive data are not stored in VCS.
  
  • Cons: Complex setup, need to be careful with access to the environment variables.

#### Things I want to know more about

> I want to know everything about Django- I really enjoy it and find it fascinating

#### Sources

[Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)

Click to return [Home!](../README.md)
