# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
One way to bind data in Vue.js is to use the v-model directive. When attached to an input, this model monitors the input and updates the given template once there is a change in the model. It also updates the data model if there is a change in the template. This is what we call two-way data binding. The most basic form of data binding is text interpolation using the “Mustache” syntax. The mustache tag will be replaced with the value of the msg property on the corresponding data object. It will also be updated whenever the data object’s msg property changes.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single page application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
You can build very snappy UIs that update fast. But SPAs also come with disadvantages such as long load times, and Google struggles with them because there’s no content initially on the page to crawl for SEO purposes.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
The mounted hook is the most commonly used lifecycle hook in Vue. Vue calls the mounted hook when your component is added to the DOM. It is most often used to send an HTTP request to fetch data that the component will then render.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
One way to bind data in Vue.js is to use the v-model directive. When attached to an input, this model monitors the input and updates the given template once there is a change in the model. It also updates the data model if there is a change in the template. This is what we call two-way data binding.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
A directive can have a single argument that always comes after the directive name. For v-on the argument is used to specify which event to listen on: keyup, click, to name a few. A directive can have multiple modifiers. Modifiers are like flags, boolean values, that your directive can react upon. So the at symbol can be used to say, hey you need ot listen to this, and when the event happens you need to complete the action associated with it.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
The v-if, v-else, and v-else-if directives allow you to create conditionally rendered HTML elements, and work similarly to JavaScript’s if, else if, else conditions. Instead of returning HTML or code like you would in JavaScript, Vue will conditionally render that block of code.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
`The key special attribute is used as a hint for Vue's virtual DOM algorithm to keep track of a node's identity. That way, Vue knows when it can reuse and patch existing nodes and when it needs to reorder or recreate them.``

```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The `<slot>` HTML element—part of the Web Components technology suite—is a placeholder inside a web component that you can fill with your own markup, which lets you create separate DOM trees and present them together. Attributes bound to a `<slot>` element are called slot props. Now, in the parent scope, we can use v-slot with a value to define a name for the slot props we’ve been provide
```