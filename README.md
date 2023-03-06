# appsdev-next

https://nextjs.org/learn/foundations/about-nextjs/what-is-nextjs

### FOUNDATIONS

### About Next.js
To effectively use Next.js, it helps to be familiar with JavaScript, React, and related web development concepts. But JavaScript and React are vast topics. How do you know when you're ready to learn Next.js?

Welcome to the Next.js Foundations course! This beginner-friendly, example-led course with guide you through the prerequisite knowledge for Next.js. You will build a simple project step-by-step; starting with a JavaScript application, then migrating it to React and Next.js.

Each section builds on the previous one, so you can choose where to start depending on what you already know.

Let's get started!

### What is Next.js?
Next.js is flexible **React framework** that gives you building blocks to create fast **web applications**.

But what exactly do we mean by this? Let's spend some time expanding on what React and Next.js are and how they can help.

### Building Blocks of a Web Application
There are a few things you need to consider when building modern application. Such as:
>
> - **User Interface** - how users will consume and interact with your application.
> - **Routing** - how users navigate between different parts of your application.
> - **Data Fetching** - where your data lives and how to get it.
> - **Rendering** - when and where you render static or dynamic content.
> - **Integrations** - what third-party services you use (CMS, auth, payments, etc) and how you connect to them.
> - **Infrastructure** - where you deploy, store, and run your application code (Serverless, CDN, Edge, etc).
> - **Performance** - how to optimize your application for end-users.
> - **Scalability** - how your application adapts as your team, data and traffic grow.
> - **Developer Experience** - your team's experience building and maintaining your application.
>
For each part of your application, you will need to decide whether you will build a solution yourself or use other tools such as libraries and frameworks.

### What is React?
React is a JavaScript **library** for building interactive **user interfaces**.

By user interfaces, we mean the elements that users see and interact with on-screen.

<img src="https://nextjs.org/static/images/learn/foundations/user-interface.png" width="80%" />

By library, we mean React provides helpful functions to build UI, but leaves it up to the developer where to use those functions in their application.

Part of React's success is that it is relatively unopinionated about the other aspect of building applications. This has resulted in a flourishing ecosystem of third-party tools and solutions.

It also means, however, that building a complete React application from the group up requires some effort. Developers need to spend time configuring tools and reinventing solutions for common application requirements.

**What is Next.js?**

Next.js is a React **framework** that gives you building blocks to create web applications.

By framework, we mean Next.js handles the tooling and configuration needed for React, and provides additional structure, features, and optimizations for your application.

<img src="https://nextjs.org/static/images/learn/foundations/next-app.png" width="80%" />

You can use React to build your UI, then incrementally adopt Next.js features to solve common application requirements such as routing, data fetching, integrations - all while improving the developer and end-user experience.

Whether you're an individual developer or part of a larger team, you can leverage React and Next.js to build fully interactive, highly dynamic, and performant web applications. 

In the next lessons, we will discuss how you can get started with React and Next.js.

**Rendering User Interfaces**

To understand how React works, we first need a basic understanding of how browsers interpret your code to create interactive user interfaces (UI).

When a user visits a web page, the server returns an HTML file to the browser that may look like this:

<img src="https://nextjs.org/static/images/learn/foundations/html-to-dom.png" width="80%" />

The browser then reads the HTML and constructs the Document Object Model (DOM).

......

**Create a Next.js App**

To build a complete web application with React from scratch, there are many important details you need to consider:

- Code has to be bundled using a bundler like webpack and transformed using a complier like Babel.
- You need to do production optimizations such as code splitting.
- You might want to statically pre-render some pages for performanceYour  and SEO. You might also want to use server-side rendering or client-side rendering.
- You might have to write some server-side code to connect your React app to your data store.


