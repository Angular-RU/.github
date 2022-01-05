<img  align='right' src="https://raw.githubusercontent.com/Angular-RU/.github/main/profile/angular.png" />

**Angular** is a development platform, built on TypeScript. As a platform, Angular includes:

- A component-based framework for building scalable web applications
- A collection of well-integrated libraries that cover a wide variety of features, including routing, forms management, client-server communication, and more
- A suite of developer tools to help you develop, build, test, and update your code

With Angular, you're taking advantage of a platform that can scale from single-developer projects to enterprise-level applications. 

<details>
<summary>The following is a minimal Angular component.</summary>
<div>
  
  
```ts
import { Component } from '@angular/core';

@Component({
  selector: 'hello-world',
  template: `
    <h2>Hello World</h2>
    <p>This is my first component!</p>
  `
})
export class HelloWorldComponent {
  // The code in this class drives the component's behavior.
}
```

To use this component, you write the following in a template:
  
```html
<hello-world></hello-world>
```

When Angular renders this component, the resulting DOM looks like this:
  
```html
<hello-world>
  <h2>Hello World</h2>
  <p>This is my first component!</p>
</hello-world>
```


</div>
</details>
