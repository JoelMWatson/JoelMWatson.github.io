#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [Next, Gatsby, and JS Frameworks](https://JoelMWatson.github.io/reading-notes/class-35-reading)

---

## Class 35 Reading: Next, Gatsby, and JS Frameworks

React is a fantastic javascript front-end library but there are some limitations
with the standard create-react-app. For one, with the create react app being entirely
client side rendering, these applications struggle with SEO. To solve this and
other issues, many toolkits like Next.js and Gatsby have been created to work with
React. There are also entirely different frameworks to choose from like Vue and Angular

### Next & Gatsby

Both Next.js and Gatsby solve the SEO problems react has but in slightly different
ways. They both create a single page application out of the box and generate very
performant websites. This can cause some difficulty when choosing between the two,
so I've covered some of differences below to help when choosing which to use.

Which to Use:

- You have lots of content or if you expect your content to grow. (Use Next)
- When you have thousands of pages (Use Next)
- When you have a high traffic e-commerce site with fewer than 1000 products and
  don't expect the product catalog to grow.(Use Gatsby)

#### Next

Next is a tool for server side rendering. This means it renders and serves the rendered
HTML files from the server to the client for each request (also supports static exports).
Next is also very flexible with how you handle your data leaving the decision of
using GraphQL, Redux, or pure React.

#### Gatsby

Gatsby is a tool for static site generating. This means all of the static HTML is
generated at build time, but no server is used to serve these files to the client.
Gatsby is rather restrictive with how you handle your data, requiring you to use
GraphQL.

### Angular & Vue

Angular and Vue are two major frameworks in the JavaScript world. They both, like
React, use components to build/rerender their content.

Which to Use:

- You are building a large scale enterprise application for a large company with
  a lot of resources (Use Angular)
- You are working with an existing code base not currently using either framework,
  or a very outdated version and need backwards compatibility (Use Vue)

#### Angular

Angular is the default commercial choice and is favored by back end developers. It is
a very opinionated front-end framework that is compatible with any back end language.

#### Vue

Vue is a much smaller framework made by an ex Google employee from the Angular team.
Vue is a developer favorite for its scalable implementation and familiar structure
to those already familiar with Angular.
