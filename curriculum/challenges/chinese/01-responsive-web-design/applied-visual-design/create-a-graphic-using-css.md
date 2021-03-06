---
id: 587d78a6367417b2b2512add
title: 使用 CSS 创建一个图形
challengeType: 0
videoUrl: 'https://scrimba.com/c/cEDWPs6'
forumTopicId: 301048
---

# --description--

术语表：blur-radius => 模糊半径，spread-radius => 辐射半径，transparent => 透明的，border-radius => 圆角边框。

通过使用选择器选择不同的元素并改变其属性，你可以创造一些有趣的形状。比如新月。你可以使用 `box-shadow` 属性来设置元素的阴影，`border-radius` 属性控制元素的圆角边框。

首先你将会创建一个圆的、透明的对象，它具有模糊阴影并略微向两边递减。如你所见，这个阴影其实就是新月形狀。

为了创建一个圆形的对象，`border-radius` 应该被设置成 50%。

你应该还记得之前关卡的 `box-shadow` 属性以及它的依次取值 `offset-x`、`offset-y`、`blur-radius`、`spread-radius` 和颜色值。其中`blur-radius` 和 `spread-radius` 是可选的。

# --instructions--

把编辑器里的正方形元素变成新月形状。首先，把 `background-color` 改为 transparent，接着把 `border-radius` 属性设置成 50%，以创建一个圆形。最后，更改 `box-shadow` 属性，使其 `offset-x` 为 25px，`offset-y` 为 10px，`blur-radius` 为 0，`spread-radius` 为 0，`color` 为 blue。

# --hints--

`background-color` 属性应该取值 `transparent`。

```js
assert(code.match(/background-color:\s*?transparent;/gi));
```

`border-radius` 属性应该取值 `50%`。

```js
assert(code.match(/border-radius:\s*?50%;/gi));
```

`box-shadow` 属性的 `offset-x`、`offset-y`、`blur-radius`、`spread-radius` 和 `color` 应该依次取值`25px`、`10px`、`0`、`0` 和 `blue`。

```js
assert(
  code.match(/box-shadow:\s*?25px\s+?10px\s+?0(px)?\s+?0(px)?\s+?blue\s*?;/gi)
);
```

# --solutions--

