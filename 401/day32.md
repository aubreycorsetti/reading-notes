# Day 32 Notes

## React 3

### NextJs

• Important details to consider:
  
  •Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.

  • You need to do production optimizations such as code splitting.

  • You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.

  • You might have to write some server-side code to connect your React app to your data store.

• Assets

  • Next.js can serve static assets, like images, under the top-level public directory. Files inside public can be referenced from the root of the application similar to pages.

### React Context for Beginners

• What is it?

  • React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.

• What problem does it solve?

  • React context helps us avoid the problem of props drilling.

• There are four steps to using React context:

  1. Create context using the createContext method.

  2. Take your created context and wrap the context provider around your component tree.

  3. Put any value you like on your context provider using the value prop.

  4. Read that value within any component by using the context consumer.

#### Things I want to know more about

> All of react! This stuff is really exciting and fun for me.

#### Sources

[NextJs](https://nextjs.org/learn/basics/getting-started)
[React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)

Click to return [Home!](../README.md)
