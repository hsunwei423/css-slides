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
---
### CSS Reset?
### CSS Normalize?

[Reset CSS 與 Normalize.css 差異](https://israynotarray.com/css/20210807/3641451940/)  
[小事之 CSS Reset 與 CSS normalize](https://ithelp.ithome.com.tw/articles/10196528)
---
### CSS preprocessor - SCSS
[Sass/SCSS 基本語法介紹，搞懂CSS 預處理器](https://tw.alphacamp.co/blog/css-preprocessor-sass-scss)
[讓CSS不再難讀！SCSS](https://medium.com/andy-blog/day05-%E8%AE%93css%E4%B8%8D%E5%86%8D%E9%9B%A3%E8%AE%80-scss-6e46261a42b5)
[SASS](https://www.sassmeister.com/)

1. Nesting
2. Variables
3. Mixins
4. Import
5. Extend
6. Functions


---
### RWD
[如何利用 Sass 的 @mixin 功能，讓撰寫 RWD 網站變的輕而易舉](https://medium.com/@wywsmail/%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8-sass-%E7%9A%84-mixin-%E5%8A%9F%E8%83%BD-%E8%AE%93%E6%92%B0%E5%AF%AB-rwd-%E7%B6%B2%E7%AB%99%E8%AE%8A%E7%9A%84%E8%BC%95%E8%80%8C%E6%98%93%E8%88%89-d44912b01f3c)