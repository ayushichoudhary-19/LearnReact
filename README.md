
# 🚀 Complete Guide to Crack React Developer Interview  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="40" height="40" alt="React Logo"> 

### This is a **React Learning Journey and Interview Preparation Repository**

### **Description**


Welcome to my React learning adventure! 📚 This repository is your comprehensive resource for mastering React, preparing for interviews, and clearing common doubts for new learners. 🌟

**What's Inside:**

📖 **Step-by-Step Documentation:** Follow my journey through the React Documentation and Roadmap.sh website. I've documented each step I've taken, making it easy for you to follow along.

❓ **Doubt Solving:** Learning can be challenging, and doubts are natural. I've recorded all the questions and confusions I've encountered while reading the documentation and provided clear solutions.

🔍 **Interview Preparation:** Are you aspiring to be a React developer? I've compiled a collection of interview questions topic-wise that you may encounter when applying for React developer roles in firms. Ace your interviews with confidence!

🔎 **Learning Beyond Documentation:** Sometimes, the official documentation might not cover everything. When that happens, I turn to Google and AI for answers. You'll find additional insights and explanations here.

🧑‍🎓 **New Learner's Perspective:** I put myself in the shoes of a beginner, so you'll benefit from explanations that address the common doubts and questions that new learners often face.

📚 **Structured Content:** Everything is neatly organized, making it easy for you to find the specific topics you're interested in. No more searching endlessly for answers!

Join me on this React learning journey, prepare for your React developer interviews, and let's conquer React together. Whether you're a new learner or an aspiring developer, this repository is your one-stop resource for mastering React! 🚀💡


## Step 1: Learn JavaScript <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" width="30" height="30" alt="JavaScript Logo">

Here are some of the JavaScript concepts that you should be familiar with before you start learning React:
- Variables, Data types, Operators
- Control flow statements
- Functions
- Objects
- Arrays
- DOM manipulation

<br>

## Step 2: CLI Tools
1. Vite <img src="https://vitejs.dev/logo.svg" width="20" height="20" alt="Vite Logo">
2. CRA  <img src="https://create-react-app.dev/img/logo.svg" width="20" height="20" alt="CRA Logo">

### Interview Questions

📝 **What is a CLI tool?**

A CLI tool (command-line interface tool) is a program that is operated by typing commands into a text-based interface. CLI tools are often used by developers to automate tasks and perform complex operations.

📝 **What are the benefits of using CLI tools?**

There are many benefits to using CLI tools, including:

    * They can be used to automate tasks, which can save time and improve efficiency.
    * They can be used to perform complex operations that would be difficult or impossible to do using a GUI tool.
    * They can be used to access and control system resources, such as files and directories.
    * They can be used to troubleshoot problems.

📝 **What are some common CLI tools used by front-end developers?**

Some common CLI tools used by front-end developers include:

    * `npm` - A package manager for JavaScript.
    * `yarn` - Another package manager for JavaScript.
    * `webpack` - A module bundler for JavaScript.
    * `gulp` - A task runner for JavaScript.
    * `grunt` - Another task runner for JavaScript.
    * `git` - A version control system.

📝 **Can you explain the difference between a CLI tool and a GUI tool?**

A CLI tool is a text-based interface, while a GUI tool is a graphical user interface. CLI tools are typically used by developers, while GUI tools are typically used by non-technical users.

📝 **What are the advantages and disadvantages of using Vite?**

Some of the advantages of using Vite include:

    * It is very fast.
    * It is easy to use.
    * It is highly customizable.
    * It supports TypeScript.
    * It is compatible with many popular frontend frameworks.

Some of the disadvantages of using Vite include:

    * It is still under development, so there may be some bugs.
    * It is not as widely used as some other frontend frameworks.

📝 **What are some of the features of Vite?**

Some of the features of Vite include:

    * Hot reload: This means that changes to your code are reflected in the browser immediately.
    * Automatic code splitting: This means that only the code that is needed for the current page is loaded, which can improve performance.
    * Pre-bundling: This means that the code is bundled before the browser loads it, which can also improve performance.
    * TypeScript support: Vite supports TypeScript out of the box.
    * Compatibility with many popular frontend frameworks: Vite is compatible with many popular frontend frameworks, such as React, Vue, and Angular.

📝 **How does Vite work?**

Vite uses a number of technologies to achieve its fast performance, including:

    * **ESBuild:** ESBuild is a JavaScript compiler that is very fast.
    * **Rollup:** Rollup is a module bundler that is also very fast.
    * **Webpack:** Webpack is a module bundler that is widely used and supports many features.

Vite also uses a number of other technologies to improve performance, such as code splitting and pre-bundling.

📝 **How does Vite compare to other frontend development frameworks?**

Vite is a relatively new frontend development framework, so it is not yet as widely used as some other frameworks, such as React and Vue. However, Vite has a number of advantages over these frameworks, including its speed, ease of use, and customizability.

📝 **What are some of the best practices for using Vite?**

Some of the best practices for using Vite include:

    * Use TypeScript: TypeScript can help to improve the quality of your code and prevent errors.
    * Split your code into smaller files: This can help to improve performance.
    * Use pre-bundling: This can also help to improve performance.
    * Use the latest version of Vite: The latest version of Vite will have the latest features and bug fixes.

📝 **Can you give me an example of a project you've worked on that used Vite?**

Sure, I worked on a project that used Vite to build a single-page application. The application was built using React and TypeScript. Vite helped to improve the performance of the application by making it very fast to load and by reducing the amount of code that needed to be loaded.

📝 **What are some of the challenges you've faced using Vite?**

Some of the challenges I've faced using Vite include:

    * It is still under development, so there may be some bugs

<br> 

## Step 3: Components
Components are the building blocks of React applications. They let us split the UI into independent, reusable pieces.

Basically Components in react are JavaScript functions only.
As every function returns something, these components also return markup(piece of HTML code).
```
function MyButton() {
  return (
    <button>I'm a button</button>
  );
}
```

Now, we can use this component within other components also. This concept is called **nested components**
```
function MyButton() {
  return (
    <button>I'm a button</button>
  );
}
```
```
💡 React component names must always start with a capital letter, while HTML tags must be lowercase.
```

### Questions
* **What is a React component?**
  
React apps are made out of components. A component is a piece of the UI (user interface) that has its own logic and appearance. A component can be as small as a button, or as large as an entire page.

* **What are the benefits of using React components?**

There are many benefits to using React components, including:

    * Reusability: Components can be reused throughout an application, which can save time and code duplication.
    * Modularity: Components can be broken down into smaller, more manageable units, which can make code easier to understand and maintain.
    * Testability: Components can be easily tested in isolation, which can help to improve the quality of code.
    * Flexibility: Components can be easily customized to meet the specific needs of an application.

### JSX

The markup syntax we’ve seen above is called JSX. **JSX is stricter than HTML.**
Like in HTML we can place a `<br>` anywhere without a need to close it, in JSX every tag needs a closing. So, You have to close tags like `<br />`. 
Also note that your component also can’t return multiple JSX tags. Each component/function (untill you're used to the term let's also call it a ' JS function'), can return only 1 JSX-tag/markup.

```
function AboutPage() {
  return (

      <h1>About</h1>
      <p>Hello there.<br />How do you do?</p>

  );
}
```
This is invalid!
However, if you want to return multiple tags, there's a way!
You can simply enclose all the markup in a partent tag. In this way that parent tag will be returned taking all the childs with it.

```
function AboutPage() {
  return (
    <div>
      <h1>About</h1>
      <p>Hello there.<br />How do you do?</p>
    </div>
  );
}
```

or we can wrap them is emply tags also.
```
function AboutPage() {
  return (
    <>
      <h1>About</h1>
      <p>Hello there.<br />How do you do?</p>
    </>
  );
}
```

### Adding Styles
In html we use `class` attribute of any element to style it in external css file. Similarly we can also style a component but the attribute for a component's markup in react is `className`.
Thus, in React, we specify a CSS class with `className`. It works the same way as the HTML `class` attribute:

```
<img className="avatar" />
```
Then you write the CSS rules for it in a separate CSS file:

```
/* In external CSS */
.avatar {
  border-radius: 50%;
}
```
### Displaying Data
We need certain user data to be displayed on the page. Like "Hi User_Name!".
Do to this through react, we use JSX.
JSX lets you put markup into JavaScript. **Curly braces** let you “_escape back_” into JavaScript so that you can embed some variable from your code and display it to the user. For example, this will display user.name:
```
return (
  <h1>
    {user.name}
  </h1>
);
```

You can also “escape into JavaScript” from JSX attributes, but you have to use curly braces instead of quotes. For example, className="avatar" passes the "avatar" string as the CSS class, but src={user.imageUrl} reads the JavaScript user.imageUrl variable value, and then passes that value as the src attribute:
```
return (
  <img
    className="avatar"
    src={user.imageUrl}
  />
);
```
### Conditional Rendering
This is already well explained in the React Documentation.
Refer: 
<a href="https://react.dev/learn#conditional-rendering">Conditional Rendering </a>

### Rendering Lists
Now, what is list rendering firstly?
List rendering is the process of displaying a list of items on a web page. So assume there is a list in which elements keep on getting added and removed and you want to display all the present elements on the web page. In this case what do you do? Ofcouse we use the tradiotional `for` loop to traverse the list/array and display it's elements one by one. 

Let me give you some examples of where list rendering can be useful on a website:

**- A to-do list:** A to-do list is a great example of a list that can be rendered using React. The list can be dynamically updated as the user adds or removes items.

**- A shopping cart:** A shopping cart is another example of a list that can be rendered using React. The list can be dynamically updated as the user adds or removes items from their cart.

### Questions: 

* **What are the different types of React components?**

There are two main types of React components: class components and functional components.

    * Class components are the traditional type of React component. They are defined using classes and have access to lifecycle methods, such as `componentDidMount` and `componentDidUpdate`.
    * Functional components are a newer type of React component. They are defined using functions and do not have access to lifecycle methods.

* **How do you create a React component?**

To create a React component, you can use the `React.Component` class or the `React.functionComponent` function.

* **What are the different lifecycle methods of a React component?**

React components have a number of lifecycle methods that are called at different stages in the component's life. These methods include:

    * `componentWillMount`: This method is called before the component is mounted.
    * `componentDidMount`: This method is called after the component is mounted.
    * `componentWillReceiveProps`: This method is called before the component's props are updated.
    * `componentDidUpdate`: This method is called after the component's props are updated.
    * `componentWillUnmount`: This method is called before the component is unmounted.

* **What are props and state in React?**

Props and state are two important concepts in React.

    * Props are the data that is passed to a component from its parent component.
    * State is the data that is managed by a component itself.

* **How do you pass props to a React component?**

To pass props to a React component, you can use the `props` prop.

* **How do you manage state in a React component?**

To manage state in a React component, you can use the `state` property.

* **What are the different ways to render a React component?**

There are two main ways to render a React component:

    * Using the `render` method: The `render` method is a required method in all React components. It is used to return the markup for the component.
    * Using the `JSX` syntax: JSX is a syntax extension that allows you to write React components in a more concise and readable way.

* **What are the advantages of using functional components over class components?**

Functional components have a number of advantages over class components, including:

    * They are easier to read and write.
    * They are more performant.
    * They are more testable.

* **What are the disadvantages of using functional components over class components?**

Functional components have a few disadvantages, including:

    * They do not have access to lifecycle methods.
    * They can be more difficult to debug.

* **What are the best practices for writing React components?**

Here are some best practices for writing React components:

    * Keep components small and focused.
    * Use props to pass data to components.
    * Use state to manage data that changes within a component.
    * Use the `render` method to return the markup for a component.
    * Use JSX to write React components in a more concise and readable way.

* **What are some common mistakes to avoid when writing React components?**

Here are some common mistakes to avoid when writing React components:

    * Using global state.
    * Using too many nested components.
    * Not using props correctly.
    * Not using state correctly.
    * Not using the `render` method correctly.
    * Not using JSX correctly.



