#### [Home](https://joelmwatson.github.io) >> [Reading Notes](https://joelmwatson.github.io/reading-notes) >> [React Testing and Deployment](https://JoelMWatson.github.io/reading-notes/class-22-reading)

---

## Class 22 Reading: React Testing and Deployment

#### Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.

One case where snapsjot testing would be useful is when you are changing up the
back-end of an existing project and want to ensure the front end still rendered
the same way after you made your changes. A scenario where it would be ineffective
would be if you were updating the front end of the site. (This would change the
rendered html and the snapshot would not match)

#### What is the difference between full mount and shallow mount?

Full mount testing is where a component and all its children are rendered to be
tested. With shallow mount testing, only the current component is rendered and
all its required dependencies are left out to just test the function of the
current component.

#### What does npm run build do?

NPM build is a command that creates a production ready version of your code that
you can deploy to a website. The production ready code includes static files with
the compiled JS and CSS files as well as the rendered HTML pages.
