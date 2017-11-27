---
title: First Post, no hero.
date: 2016-01-22
layout: Post
---

This is the 
<note content="first post">Notes are long, so they accept inner markdown to be more flexible.</note>

Code is highlighted by default.

```js
const StatelessComponent = (props) => {
  return (
    <div>
      I‘m a stateless component that accepts children
      { props.children }
    </div>
  )
}

// ...

  return (
    <StatelessComponent>
      Example of child
    </StatelessComponent>
  )
```
