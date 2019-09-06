# Product Development Guidelines

My personal & professional bookmarks, guidelines &amp; documentation for *modern product development*

---

# Engineering

## 🏗 DevOps

### Git

- [PRs (Pull Requests)](engineering/git/PRs.md)
- [Semantic Commits](engineering/git/commits.md)
- [Git Workflow (basic)](https://github.com/benoror/guides/blob/master/git/workflow.md)
- [Gitflow: A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Git Tools - Rewriting History](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)

#### Code Reviews

- [Why review code?](https://sophiebits.com/2018/12/25/why-review-code.html)
- [How to Do Code Reviews Like a Human (Part One)](https://mtlynch.io/human-code-reviews-1/)
  - [Part Two](https://mtlynch.io/human-code-reviews-2/)
- [How to do a code review](https://google.github.io/eng-practices/review/reviewer/)
- [More Effective Code Reviews](https://medium.com/make-better-software/more-effective-code-reviews-49e6998effe2)
- [The (written) unwritten guide to pull requests](https://www.atlassian.com/blog/git/written-unwritten-guide-pull-requests)
- [Pull requests and code review](https://confluence.atlassian.com/bitbucket/pull-requests-and-code-review-223220593.html)

### Heroku

- [CLI](engineering/heroku/cli.md)
- [Postgres](engineering/heroku/postgres.md)
- [Rollbacks](https://blog.heroku.com/releases-and-rollbacks#rollbacks)

## ⚙️ Backend

### Ruby (on Rails)

- [Ruby Styleguide](engineering/style.md)
  - [Rubocop Styleguide](https://github.com/rubocop-hq/ruby-style-guide)

#### Best Practices & Design Patterns

##### Service Objects

- [A simple explanation of Service Objects for Ruby on Rails](https://medium.freecodecamp.org/service-objects-explained-simply-for-ruby-on-rails-5-a8cc42a5441f)
- [Using Services to Keep Your Rails Controllers Clean and DRY](https://www.engineyard.com/blog/keeping-your-rails-controllers-dry-with-services)
- [Rails Service Objects: A Comprehensive Guide](https://www.toptal.com/ruby-on-rails/rails-service-objects-tutorial)

##### Controllers

- Memoizing
  - [Explaining the rationale behind using memoized helper methods for controller resources](https://gist.github.com/bloudermilk/8345597)
  - [The Basics of Ruby Memoization](http://gavinmiller.io/2013/basics-of-ruby-memoization/)
  - [Rails best practices: Use memoization](https://rails-bestpractices.com/posts/2010/11/22/use-memoization/)
  - [4 Simple Memoization Patterns in Ruby (And One Gem)](https://www.justinweiss.com/articles/4-simple-memoization-patterns-in-ruby-and-one-gem/)
  
##### Testing

  - [How to configure RSpec in Ruby on Rails](https://blog.eq8.eu/article/junior-developer-set-up-rails-with-rspec-factorybot-database-cleaner.html)

##### Migrations

- **_Data_** Migrations
  - [Data Migrations in Rails](https://thoughtbot.com/blog/data-migrations-in-rails)
  - [Migrating Data - Rails Migrations or a Rake Task?
](https://www.urbanbound.com/make/migrating-data-rails-migrations-or-a-rake-task)

### REST APIs

#### Specifications

- [JSON:API](https://jsonapi.org/)

## 🖼 Frontend

### Javascript
  
#### HTML & CSS

- [Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
  - [Grid by Example](https://gridbyexample.com/examples/)
  - [Learn CSS Grid](https://learncssgrid.com/)

#### React

- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Presentational and Container Components (Dan Abramov)](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
  - [Example Gist (Michael Chan)](https://gist.github.com/chantastic/fc9e3853464dffdb1e3c)
  - [Usage with Redux](https://redux.js.org/basics/usage-with-react#presentational-and-container-components)
- [React Cheat Sheet](https://reactcheatsheet.com/)
- [React Patterns](https://reactpatterns.com/)
- [How to fetch data in React](https://www.robinwieruch.de/react-fetching-data/#react-fetch-data-loading-error)

##### CSS-Modules

- [CSS Modules](https://github.com/css-modules/css-modules)
- [CRA: Adding CSS Modules](https://facebook.github.io/create-react-app/docs/adding-a-css-modules-stylesheet)
- [Getting started with CSS modules in React](https://blog.pusher.com/css-modules-react/)
- [What are CSS Modules and why do we need them?](https://css-tricks.com/css-modules-part-1-need/)
- [What are CSS Modules? A visual introduction](https://www.javascriptstuff.com/what-are-css-modules/)

##### State Management

- Hooks & Context API
  - [Application State Management with React](https://kentcdodds.com/blog/application-state-management-with-react)
  - [State Management with React Hooks and Context API in 10 lines of code!
](https://medium.com/simply/state-management-with-react-hooks-and-context-api-at-10-lines-of-code-baf6be8302c)
- [MobX](https://mobx.js.org/intro/overview.html)
  - [Ten minute introduction to MobX and React](https://mobx.js.org/getting-started.html)
  - [MobX: Concepts & Principles](https://mobx.js.org/intro/concepts.html)
  - [Video: Preethi Kasireddy - MobX vs Redux: Comparing the Opposing Paradigms - React Conf 2017](https://www.youtube.com/watch?v=76FRrbY18Bs)
  - [Building a JSON:API App with React and Reststate/Mobx](https://howtojsonapi.com/react-native.html)
[Redux](https://redux.js.org/introduction/motivation)
- [Redux (react-redux)](https://react-redux.js.org/introduction/why-use-react-redux)
  - [Leveling Up with React: Redux](https://css-tricks.com/learning-react-redux/)
  - [React Redux Tutorial for Beginners: The Definitive Guide (2019)](https://www.valentinog.com/blog/redux/)
  - [Redux and React: An Introduction](http://jakesidsmith.com/blog/post/2017-11-18-redux-and-react-an-introduction/)
  - [What Does Redux Do? (and when should you use it?)](https://daveceddia.com/what-does-redux-do/)
  - [How Redux Works: A Counter-Example](https://daveceddia.com/how-does-redux-work/)
  - [Redux Architecture and Best Practices](https://github.com/markerikson/react-redux-links/blob/master/redux-architecture.md)
  - [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links)
  - [JSON:API resources for React + Redux](https://gist.github.com/benoror/9988c235d5cb53acfcf57ea668bd95cb)
  
##### Testing

- [Write tests. Not too many. Mostly integration.](https://kentcdodds.com/blog/write-tests)
- [Jest](https://jestjs.io/)
  - [jest-dom](https://github.com/testing-library/jest-dom)
- [RTL (react-testing-library)](https://testing-library.com/docs/react-testing-library/intro)
  - [testing-library/react-testing-library](https://github.com/testing-library/react-testing-library)
  - [React Testing Examples: Jest + RTL](https://react-testing-examples.com/jest-rtl/)
  - [Course: Teting Javascript by Kent C. Dodds](https://testingjavascript.com)
- [Enzyme (AirBnB)](https://airbnb.io/enzyme/)

## ⭐️ Misc

- [DockYard Styleguides](https://github.com/DockYard/styleguides)
- [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- [Tractical Guides](https://github.com/benoror/guides)

## 📚 Books

### Technical

- [Refactoring (Martin Fowler)](https://refactoring.com/)
- [The Pragmatic Programmer](https://pragprog.com/book/tpp/the-pragmatic-programmer)
- [Domain-Driven Design (Eric Evans)](https://domainlanguage.com/ddd/)
- [Domain-Driven Design Distilled](https://www.oreilly.com/library/view/domain-driven-design-distilled/9780134434964/)
- [Patterns of Enterprise Application Architecture (Martin Fowler)](https://www.martinfowler.com/books/eaa.html)
- [JavaScript: The Good Parts (Douglas Crockford)](http://shop.oreilly.com/product/9780596517748.do)
- [You Don't Know JS (Kyle Simpson)](https://github.com/getify/You-Dont-Know-JS)

### Non-technical

- [The Lean Startup (Eric Ries)](https://www.goodreads.com/book/show/10127019-the-lean-startup)
- [Inspired: How to Create Tech Products Customers Love](https://svpg.com/inspired-how-to-create-products-customers-love/)
- [Zero to One: Notes on Startups, or How to Build the Future (Peter Thiel)](https://www.goodreads.com/book/show/18050143-zero-to-one)
- [High Output Management (Andrew S. Grove)](https://www.goodreads.com/book/show/324750.High_Output_Management)
- [Remote (J. Fried, D.H.H.)](https://www.goodreads.com/book/show/17316682-remote)
- [Rework (J. Fried, D.H.H.)](https://www.goodreads.com/book/show/6732019-rework)
- [Priming Kanban](https://www.infoq.com/minibooks/priming-kanban-jesper-boeg)
