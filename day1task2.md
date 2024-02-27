                     Write a blog about objects and its internal representation in Javascript


*what is an object?
            An object is a fundamental data type that represents a collection of key-value pairs. It is a composite data type, meaning it can contain other data types such as
         strings, numbers, arrays, functions, and even other objects.

         for example:

             // Creating an object using object literal
const person = {
    name: "Josco",
    age: 24,
    city: "Nagercoil"
};

*objects and its internal representation in Javascript:
             
In JavaScript, objects serve as fundamental data structures, encapsulating collections of key-value pairs. Internally, each object is composed of properties and methods, 
with each property associated with a property descriptor containing metadata about its behavior. Objects are linked to a prototype object, forming a prototype chain for property and method lookups. 
Modern JavaScript engines optimize object access using techniques like hidden classes and inline caching, while memory management involves automatic garbage collection to deallocate unused objects. 


Conclusion:
         Understanding the internal representation of objects in JavaScript is essential for efficient development. Objects consist of properties and methods, linked to prototype objects forming a chain for lookups. 
Modern engines optimize access using techniques like hidden classes and inline caching, with memory management handled through automatic garbage collection. This knowledge empowers developers to write more efficient and performant JavaScript code.

    



                                         Day 2

     Understanding the Difference Between Document and Window Objects in JavaScript

                  In the world of web development, JavaScript reigns supreme as the language of the web browser. As developers dive into the intricacies of JavaScript, they often encounter two essential objects: the Document object and the Window object. 
While both are fundamental to web development, they serve distinct purposes and understanding their differences is crucial for mastering JavaScript. In this blog post, we'll explore the disparities between these two objects and shed light on their respective roles in the web development landscape.

### Document Object: Navigating the DOM

                 The Document object represents the web page loaded into the browser window. It serves as an entry point to the content of the web page, allowing developers to manipulate its structure, content, and styling through JavaScript. 
The Document object is part of the Document Object Model (DOM), which provides a structured representation of the HTML elements on a web page.

Here are some key characteristics of the Document object:

1. **Access to HTML Elements**: 
               The Document object provides methods and properties for accessing and interacting with HTML elements within the web page. Developers can use methods like `getElementById()`, `getElementsByClassName()`,
 or `querySelector()` to select specific elements and modify their attributes or content.

2. **Manipulating Content**:
             Through the Document object, developers can dynamically update the content of the web page. This includes tasks such as adding or removing elements, changing text or attributes, and altering the structure of the DOM.

3. **DOM Event Handling**: The Document object enables event handling within the DOM. Developers can attach event listeners to document-level events like `DOMContentLoaded` or `click`, allowing them to respond to user interactions or changes in the document structure.

### Window Object: Managing the Browser Window

In contrast to the Document object, the Window object represents the web browser window or tab. It serves as the global object in client-side JavaScript and provides access to various browser-related functionalities.

Here are some key characteristics of the Window object:

1. **Global Scope**: Variables and functions declared in the global scope of a JavaScript file are attached to the Window object. This means that they can be accessed from anywhere within the script.

2. **Browser Interaction**: The Window object provides methods for interacting with the browser window, including tasks such as opening new windows or tabs (`window.open()`), navigating to different URLs (`window.location`), and controlling the size and position of the window.

3. **Timers and Intervals**: JavaScript timers such as `setTimeout()` and `setInterval()` are functions of the Window object. These timers are used to execute code asynchronously after a specified delay or at regular intervals.

4. **Browser Information**: The Window object provides information about the browser environment, including properties like `window.innerHeight` and `window.innerWidth` for obtaining the dimensions of the viewport, as well as `window.navigator` for retrieving information about the user's browser and operating system.

### Key Differences

While both the Document and Window objects are integral parts of client-side JavaScript, they serve distinct purposes:

- **Scope**: The Document object operates within the scope of the web page's content, allowing manipulation of its structure and elements. In contrast, the Window object operates at the browser level, controlling aspects of the browser window and its interaction with the user.

- **Hierarchy**: The Document object is nested within the Window object, representing the content loaded within the browser window. This hierarchical relationship reflects the structure of the DOM, where the Document object serves as the root node.

- **Functionality**: The Document object focuses on manipulating the content and structure of the web page, while the Window object provides broader functionality related to browser interaction, navigation, and global scripting.

### Conclusion

In summary, the Document and Window objects play distinct yet complementary roles in client-side JavaScript development. While the Document object provides access to the content and structure of the web page through the DOM, the Window object manages browser-related functionalities and global scripting. 
Understanding the differences between these two objects is essential for mastering JavaScript and building dynamic and interactive web applications. Whether you're manipulating the DOM elements or controlling the behavior of the browser window, a solid grasp of both Document and Window objects will empower you to create rich and engaging web experiences.                                     