# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](./qrCode.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

justify-content와 align-items는 자기 자신을 움직이는 속성이 아니라, 자식 요소들을 정렬하는 속성이다.

```html
<div class="container">
  <div class="card"></div>
</div>
```

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 98vh;
}
.card {
  background-color: white;
  width: 320px;
  height: 499px;
  border-radius: 20px;
}
```

### Useful resources

- [MDN사이트](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/justify-content) - 헷갈리는 개념 및 필요한 CSS 속성 검색에 활용했습니다.

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)? chatGPT를 사용
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)? 질의응답
- What worked well? What didn't? It worked well

## Author

- Website - [Jeong Sua](https://github.com/SuaJeong-winter)
- Frontend Mentor - [@SuaJeong-winter](https://www.frontendmentor.io/profile/SuaJeong-winter)
