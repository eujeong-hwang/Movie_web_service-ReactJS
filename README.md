# Movie Web Service using ReactJS

https://nomadcoders.co/react-for-beginners/lectures/3261

# I used...
#### JSX

```
const element = <h1>Hello, world!</h1>;
```
    - This funny tag syntax is neither a string nor HTML.
    - JSX is a syntax extension to Javascript. Recommend using it with React to describe 
    what the UI should look like.
    - JSX may remind you of a template language, but it comes with the full power of JavaScript.
    - JSX produces React "elements".
    - https://reactjs.org/docs/introducing-jsx.html

#### State
    - Where our data exists
    - Onclick vs. Onchange ??

#### Props

```
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

function App() {
  return (
    <div>
      <Welcome name="Sara" />
      <Welcome name="Cahal" />
      <Welcome name="Edite" />
    </div>
  );
}

ReactDOM.render(
  <App />,
  document.getElementById('root')
);
```

#### Class Components
    - Conceptually, components are like JavaScript functions. 
    They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.
    - Component is a function that returns some jsx.
    - https://reactjs.org/docs/components-and-props.html

#### Data Fetching
#### Routing

# In JSX, not Javascript

- We should use "htmlFor" instead of "for"
- We should use "className" instead of "class"

# Python lecture
https://www.youtube.com/watch?v=kWiCuklohdY
