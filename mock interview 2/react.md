JSX:

1. Adjacent JSX elements must be wrapped in an enclosing tag

2. Closing tag required

3. JSX properties are not similar to HTML attributes

4. Case Sensitiveness

5. Injecting Data using curly braces {}


Folder Structure:

Following are the basic points to note about some files that you see inside your application folder:


1 .gitignore file

    It is used by Git to determine which files and directories to ignore before a commit is made.

    It should be committed into the repository to share ignore rules with other users who clone the repository.

    The node_modules  folder is included inside the .gitignore file so that the user who clones the application is not required to clone this folder. The user simply needs to run the command 

npm install

    in the root folder of the project. This command creates the node_modules folder and installs all the dependencies (packages) needed for the application.

 

2. package.json file

    It consists of the name and version of the application, the combination of which should be unique in order to publish the package.

    It comprises of dependencies that list all the packages needed to be installed for the application.

    It also includes scripts that specify the commands to be run at various points in the application lifecycle.

     

3. package-lock.json file

    It is automatically generated for any operation where npm modifies either the node_modules  tree or the package.json  file.

    It locks the version of the full dependency tree of packages.

    It guarantees the generation of an identical dependency tree when the application is cloned by other developers.


4. node_modules folder

    Its contents are defined by the package.json file and it consists of all the packages required for running your application.

 

5. public folder

    Nothing inside this folder is processed by Webpack.

    It is used for keeping small files that are not required to be bundled.

    It can be used to contain images when there are thousands of them, and their paths need to be referenced dynamically.

    Any file inside this folder needs to be referenced at other places using the %PUBLIC_URL%/  keyword, which gets replaced with the path of the public folder during the application's build process.

 

6. index.html file

    It is the starting point of the application.

    It should always remain with the name index.html and inside the public folder; otherwise, the code will fail to run.

    It can only reference files that are inside the public  folder.

 

7. manifest.json file

    It is a simple JSON file telling the browser about the web application and how the application should behave when it is installed on the user’s mobile device or computer.

 

8. src folder

    It consists of the real application code.

    It consists of all the files that are needed to get bundled by Webpack.

 

9. index.js file

    It is the entry point for JavaScript.

    The filename should remain index.js and the location should be inside the src folder; otherwise, the code will not run.

 

10. index.css file

    It is the stylesheet for index.html.

 
11. App.js file

    It is the JavaScript file for the App component.

 

12. App.css file

    It is the stylesheet for the App component.

 

13. App.test.js file

    It is the test file for the App component.

    It contains unit tests for the application.

    It runs test cases for all the files that changed since the last commit of the application.

 

14. logo.svg file

    SVG is an acronym for Scalable Vector Graphics.

    An SVG file is an XML-based vector image format for 2D graphics with support for interactivity and animation.

    It is similar to raster-based image formats such as JPEG, PNG, BMP, GIF, etc.

    It offers a bandwidth-friendly way of rendering images; no matter how large a graphic gets, it transmits only the XML describing the graphic to the client.

    It helps to render resolution-independent and SEO-friendly images.

    It makes up the icon for your application and appears alongside the title in the browser tab.

    It gets saved along with the bookmark.


Component:

1. A Component's name must start with a capital letter
2. A class component must extend from a base/parent class named component
3. A component must always return something
4. export and import
5. A component can have a extension as .js or .JSX
6. In import statement, .jsx or .js extension is not required
7. Independant & re-use

Props:

1. Props help you to pass values from a parent component to child component 
so that they can be accessed within the child component.

Event handling:

1. An event is an action to be taken as a result of user interactions.
2. An event handler is a method to be called when an event occurs.

State:

1. State is something that is controlled within a component, unlike Props,
which are controlled by a parent component. Also, a change in state calls the
render() method again.

2. State can be maintained inside a calss component only.

3. State is always initialised inside the class constructor.

4. In case you define the constructor of a class, you need to call
the super() method in the first statement of the constructor definition.
This method calls the constructor of the parent class.

5. To set the state, you must always use the setState() method and never
directly manipulate the application's state. However, setState() should never be called
inside the constructor. 

Hooks:

1. Hooks allow functional components to use React features like state etc.
2. Hooks can be used only inside React function components.
3. Hooks cannot be used inside conditional(if, for loop) logics
4. Hooks can only be called at the top level of the components.

Routing:

1. Routing is the process that helps in loading partial content.
2. Based on the URL that a user visits, specific content is loaded on the page.
3. It helps in displaying different content to the user without any need for the page refresh.

useParams():

1. It is used when we need to access the parameters of the current route.

Switch/Routes:

1. Switch/Routes is used to render components only when the path will be matched.

Context API:

1. It allows data to be passed through a component tree without having to pass
   props manually at every level.

   --> Introduction
   --> Why use the context API?
   --> Creating a context API
   --> Creating a Context Provider
   --> Creating context provide components
   --> Drawbacks of Context API - When the context value changes, all the components
       that use the same context will re-render. This can cause performance issue
       in larger applications.

Redux:

1. Redux is a state management library.
2. It provides a predictable way to manage the state of your application
   by centralizing it in a single store.
3. Redux uses a unidirectional data flow - means that data flows in one direction
   only, from the store to the components.

Redux is based on three core principles:

--> Single soure of truth: The state of your whole application is stored
    in a single object tree within a single store.
--> State is read-only
--> Change are made with pure functions

Redux vs Context API:

1. Approach is different
2. Redux is centralized, whereas Context API decentralized
3. Another main difference between Redux and Context API is
   their PERFORMANCE. Redux can be more performant, especially
   when dealing with large and complex application because
   it minimizes the no of state updates.
4. On other hand Context API is simpler to use, we can use this 
   in smaller and medium sized application.

### what is usestate and useeffect in react
1) The useState hook is used for storing variables that are part of your application's state and will change as the user interacts with your website. 
2) The useEffect hook allows components to react to lifecycle events such as mounting to the DOM, re-rendering, and unmounting.