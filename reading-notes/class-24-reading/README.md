#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Routing and Component Composition](https://JoelMWatson.github.io/reading-notes/class-24-reading)

---

## Class 23 Reading: Routing and Component Composition

#### Why do we not need more .html pages in a multi-page React app?

React apps do not need more .html pages because react-router-dom allows you to show
different sections of jsx based on the url given. This loads much faster because
it doesnt need to communicate with the server at all.

#### If we wanted a component to show up on every page, where would we put it and why?

- Outside the <BrowserRouter/>

If it were placed outside of the BrowserRouter it would not be shown on every page.

- Inside the <BrowserRouter />, outside a <Route />

If it were placed inside the BrowserRouter but outside of the Route components it
would show on every page.

- Inside a <Route />

If it were placed inside one of the Route componenets it would only show when that
route was rendered.

#### What does props.children contain?

The props.children variable contains a reference to everything contained between
the opening and closing tags of the component. It is used when you dont know what
children are going to be contained in a component.
