### What is React?

React is a JavaScript library used for building user interfaces, particularly for single-page applications. It allows developers to create reusable UI components and manage their state efficiently.

- JavaScript kirjasto frontendiin, erityisesti single-page appeihin. Voi kayttaa samoja komponentteja uudestaan

### What are the key features of React?

React features include virtual DOM for efficient DOM manipulation, component-based architecture, JSX syntax for writing components, and uni-directional data flow.

- (DOM Document Object Model) on se minka ymparille koko sivu rakentuu. Eli Reactil on tehokasta manipuloida domii koska virtual dom

### Explain the concept of JSX.

JSX is a syntax extension for JavaScript that allows us to write HTML-like code within JavaScript. It simplifies the process of creating React elements and makes the code more readable.

- Voi kirjottaa html-like koodii javascriptis

### What is the significance of Virtual DOM in React?

The Virtual DOM is a lightweight copy of the actual DOM. React uses it to perform efficient updates to the real DOM, minimizing the number of DOM manipulations and improving performance.

- Virtual dom on kevytkopio ite DOMista ja reactil kayttomukavuus parantuu ja nopeentuu

### How does React handle state management?

React components can have state, which represents data that can change over time. State can be initialized in the constructor and updated using the setState method. When state changes, React automatically re-renders the component.

- Pitaa muuttujan tilaa ja sita voi vaihtaa

### What are props in React?

Props (short for properties) are used to pass data from parent components to child components in React. They are read-only and help create dynamic and reusable components.

- dataa mita voi passaa toisille komponenteille

### What is the role of the useState hook in React?

The useState hook is a function provided by React that allows functional components to have state. It takes an initial value and returns a state variable and a function to update that variable.

- Silla pidetaan tilaa reactis

### How does React Router work?

React Router is a library that enables navigation and routing in React applications. It uses a declarative approach, allowing developers to define routes and their corresponding components, which are rendered based on the URL.

- Maaritellaan reitit missa mennaan

### Explain the purpose of keys in React lists.

Keys are special attributes used by React to identify each child component in a list. They help React identify which items have changed, been added, or been removed, improving performance and reducing unnecessary re-renders.

- jokasella componentilla pitaa olla oma key et tietaa missa mennaan

### What are higher-order components (HOCs) in React?

Higher-order components are functions that take a component and return a new component with enhanced functionality. They are commonly used for code reuse, cross-cutting concerns like authentication, and adding additional props to components.

- kaytetaan koodin uudelleen kayttoon??

### What are controlled components in React?

Controlled components are React components whose state is controlled by React. Their value is controlled by state, and any changes to the input are handled by React, making them predictable and easier to manipulate.

- Minka tilaa hallitaan useStatel??

### How does TypeScript enhance JavaScript development?

TypeScript is a superset of JavaScript that adds static typing and other features like interfaces and enums. It helps catch errors during development, improves code readability and maintainability, and provides better tooling support.

- auttaa huomaa virheet koska tyyppi pitaa olla tiedossa

### What are the benefits of using TypeScript with React?

Using TypeScript with React provides benefits such as type checking, improved developer productivity, better code organization, enhanced tooling support, and easier collaboration in large teams.

### How do you define types in TypeScript?

Types in TypeScript can be defined using interfaces, type aliases, classes, enums, and primitives. They help specify the shape of data and provide compile-time checks to ensure type safety.

- Esim Username objektissa username: string, passsword: string, age: number

### Explain the difference between interface and type in TypeScript.

Interfaces and types are both used to define custom types in TypeScript. Interfaces are open to extension, while types are more flexible and can represent any kind of data structure, including primitives, unions, and intersections.

- Typet on joustavampia

### What are generics in TypeScript?

Generics allow us to create reusable components and functions that can work with any data type. They enable type-safe code without sacrificing flexibility, by allowing types to be parameterized.

- Uusiks kaytettavissa komponenteissa voi heittaa mita dataa haluu parametreissa

### How do you handle asynchronous operations in React?

Asynchronous operations in React can be handled using async/await, Promises, or third-party libraries like axios for HTTP requests. useEffect hook is often used to manage side effects like data fetching.

### Explain the concept of React context.

React context provides a way to pass data through the component tree without having to pass props manually at every level. It's useful for sharing global data such as themes, user authentication, or language preferences.

- Ei tartte pistaa propseja monen componentin lapi (EI PROP DRILLINGILLE)

### What are some common performance optimizations in React?

Performance optimizations in React include code splitting, memoization, virtualization, lazy loading, and using PureComponent or React.memo for preventing unnecessary renders.

- Lazy Loading ja useMemo esim

### How do you debug React applications?

React applications can be debugged using browser developer tools like Chrome DevTools, React DevTools extension, console.log statements, and debugging tools provided by IDEs like Visual Studio Code. Additionally, tools like React Error Boundaries can help catch errors in production builds.

- Developer consoles selaimella ja console.logeilla
