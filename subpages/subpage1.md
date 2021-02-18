---
title: Second child page
parent: Main page
nav_order: 2
---

## A very wise title

To this page we shall link from other page.

Fun fact: this page resides in a different folder than its direct sibling, the [First child page](../page).

## Here we'll try out some code

This paragraph will showcase some `JavaScript` code.

```javascript
export class Blog {
  constructor() {
    this.getPosts = this.getPosts.bind(this);
    this.noop = () => {};
  }

  getPosts() {
    if (localStorage.getItem('cachedPosts') === true) {
      return Promise.resolve(localStorage.getItem('posts));
    }
    return fetch('/api/posts');
  }
}
```

Above code block should be rendered with `Fira Code` font.

Test image: [logo](/jekyll-docs-test/assets/images/site_logo.png)
