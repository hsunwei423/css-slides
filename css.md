## CSS Tutorial
---
## outline
1. resources
2. box model
3. css selector
4. css reset, css normalize
5. css preprocessor - SASS, SCSS
6. css module
7. flexbox
---
## resouces
1. [學習 CSS 版面配置](https://zh-tw.learnlayout.com/)
2. [Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/)
3. [W3C CSS](https://www.w3schools.com/css/default.asp)
4. [CSS Trick](https://css-tricks.com/)

---
### Box Model
Every element on a page is a rectangular box.

![Image](/assets/imgs/box-model.PNG)

---
### Box Model

![Image](/assets/imgs/box-model-w3c.PNG)

---
### css selector
1. tag
2. class
3. id
4. properties
---
### css selector - tag

![img](/assets/imgs/css-selector-tag.PNG)
```
a {
  background-color: red;
}
```

![image](/assets/imgs/apple-link.PNG)
---
### css selector - class

![img](/assets/imgs/css-selector-class.PNG)
```
.a-link {
  background-color: yellow;
}
```

![img](/assets/imgs/apple-link-bg-yellow.PNG)

---
### css selector - id
![img](/assets/imgs/css-selector-id.PNG)

```
#a-link {
  background-color: pink;
}
.b-link {
  background: blue;
}
```

![img](/assets/imgs/apple-pink.PNG)
---
### css selector - properties

![img](/assets/imgs/css-selector-properties.PNG)
---
### css selector - properties

```
<a href="https://www.apple.com/"
  target="_blank">Apple 官網連結</a>
<a href="https://www.google.com/"
  target="_blank">Google</a>
<a target="_blank">連結缺少 href</a>
```
```
[href] {
  color: red;
}
```
![img](/assets/imgs/css-properties-style.PNG)