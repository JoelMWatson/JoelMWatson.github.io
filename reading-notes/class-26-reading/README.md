#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [React Hooks API](https://JoelMWatson.github.io/reading-notes/class-26-reading)

---

## Class 26 Reading: React Hooks API

#### What does a component’s lifecycle refer to?

The component lifecycle is refering to the the different points in the process of
rendering and unrendering the component like componentDidMount or componentDidUpdate

#### Why are functional components preferred over class components?

Functional components are preferred over class components

#### What is wrong with the following code?

The issue with the code below is that it is using the useEffect hook inside of a
for-loop.

`import React, {useState, useEffect} from 'react';

function MyComponent(props) {
const [count, setCount] = useState(0);

function changeCount(e) {
setCount(e.target.value);
}

let renderedItems = []

for (let i = 0; i < count; i++) {
useEffect( () => {
console.log('component mount/update');
}, [count]);

renderedItems.push(<div key={i}>Item</div>);
}

return (\<div>
\<input type='number' value={count} onChange={changeCount}/>
{renderedItems}
\</div>);
}`
