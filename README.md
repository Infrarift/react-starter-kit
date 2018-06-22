# React Starter Kit
I have created this starter kit mostly as a reference for myself as I learn how to create React Apps. Here I will write the basic setup instructions, useful commands, and other resources that will be helpful to getting a React app up and running, all in one place.

### Getting Started

##### [Udemy React Complete Guide](https://www.udemy.com/react-the-complete-guide-incl-redux/learn/v4/)

This was my entry point into learning React. This is an excellent Udemy course by a cool German dude. I already knew some Javascript going into this.

### Useful Snippets

```jsx
// Route some JSX to an exact path.
import {Route} from "react-router-dom";
<Route path="/" exact render={() => <h1>Hello World</h1>} />
<Route path="/" exact component={MyComponent} />
```

```jsx
// Creating a link as a MenuItem.
import {Menu} from "semantic-ui-react";
import {Link} from "react-router-dom";

<Menu.Item as={Link} to='profile'>
  My profile
</Menu.Item>
```

### Libraries and Shit

```bash
npm install --save react-router react-router-dom
```

### Styling

I like to use the [Semantic UI React](https://react.semantic-ui.com/introduction) library. It doesn't seem to have an npm installer, so I need to use yarn. However, npm seems to mess up the yarn packages after a new install.

```bash
yarn add semantic-ui-react
```

