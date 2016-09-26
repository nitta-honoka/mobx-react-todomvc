mobx-react-todomvc
=====================

A light todomvc demo with [MobX](https://mobxjs.github.io/mobx) & [React](https://facebook.github.io/react), Supports ES6 and JSX compilation through babel.

* Reference: [mobx-react-todomvc](https://github.com/mobxjs/mobx-react-todomvc).

### Run the example

```
npm install
npm start
open http://localhost:3000
```

### Redux is good enough, why we also need MobX?

- On the one hand, sometimes you [might not need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367#.ekst8i9x1).
- On the other hand, if you need manage a SPA by Redux, you should design your own action & reducer. It's Redux's core, but sometimes become more complicate than a pure React. you may also need a library or framework can help you with application's state, so you can consider to use MobX. It's lighter than Redux & comfortable enough to develop a React app.
- Yeah! There's no solution which is more better between Redux & MobX, you're wroth trying them all.
