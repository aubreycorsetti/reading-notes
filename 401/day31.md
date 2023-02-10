# Day 31 Notes

## Django Forms

### What is it?

Django provides a convenient way to create and process web forms through its forms module. Here are the key points to remember about Django forms:

### Creating a Form

• You can create a form in Django by defining a class that inherits from django.forms.Form or django.forms.ModelForm.

• The class defines the fields of the form as class attributes, using various form field classes (e.g. CharField, EmailField, PasswordInput, etc.).

• You can specify additional attributes for each field, such as the label, required status, and widget.

### Using a Form in a View

• In a view, you can create an instance of the form and render it in a template using the form template variable.

• You can also process form submissions by checking if the request method is POST, validating the form data using form.is_valid(), and performing any necessary actions.

• If the form is not valid, you can render it again in the template along with error messages for the invalid fields.

### Customizing Form Rendering

• By default, Django will render form fields as HTML. You can change the way individual fields are rendered by specifying a widget.

• You can also specify a custom template for rendering the form, allowing you to control the exact HTML output.

### ModelForm

• If you want to create a form based on a database model, you can use a ModelForm.

• ModelForm is a subclass of Form that automatically generates form fields based on the fields in a model.

•You can override the default form fields by explicitly specifying them in the form class.

#### Things I want to know more about

> How to create Django forms!

#### Sources

https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms

Click to return [Home!](../README.md)
