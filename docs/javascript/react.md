---
description: My document description
---

# React

React es una biblioteca de JavaScript de código abierto diseñada para crear interfaces de usuario. Es mantenido por Facebook y una comunidad de desarrolladores individuales y empresas. React puede usarse como base en el desarrollo de aplicaciones de una sola página o móviles.

![docosaurus logo](./img/doco.png)

```jsx title="src/components/HelloDocusaurus.js"
function HelloDocusaurus() {
    return <h1>Hello, Docusaurus!</h1>;
}
```

export const Button = ({ children, ...props }) => (
<button {...props}>{children}</button>
);

<Button className="text-red-500">Click me</Button>
<Button className="text-blue-500">Click me blue</Button>
