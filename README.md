# FDS 브라우저 측 JavaScript

---

## API

Application Programming Interface.

즉 어플리케이션을 프로그래밍할 수 있는 **접점**

---

## DOM API

- Document Object Model, 문서 객체 모델
- [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)
- [DOM 소개](https://developer.mozilla.org/ko/docs/Gecko_DOM_Reference/%EC%86%8C%EA%B0%9C)
- [트리](https://javascript-fds.netlify.com/pages/282-data-structures#트리-tree)
- [Event Reference](https://developer.mozilla.org/en-US/docs/Web/Events)
- [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)

---

## 엘리먼트 선택하기

- `document.querySelector`
- `document.querySelectorAll`
- `el.querySelector`
- `el.closest`
- `el.matches`

<!-- NodeList -->

---

## 엘리먼트 내용 조작하기

- `el.textContent`
- `el.innerHTML`

<!-- innerHTML과 XSS -->

---

## 엘리먼트 어트리뷰트 조작하기

- `el.hasAttribute`
- `el.getAttribute`
- `el.setAttribute`
- `el.removeAttribute`

---

## 엘리먼트 클래스 조작하기

- `el.classList.add`
- `el.classList.remove`
- `el.classList.contains`

---

## 인라인 스타일 조작하기

- `el.style`

---

## 이벤트 리스너

- `el.addEventListener`
- `el.removeEventListener`

---

## DOM 노드 생성하기

- `document.createElement`
- `document.createTextNode`
- `el.cloneNode`

---

## DOM 트리 조작하기

- `el.appendChild`
- `el.insertBefore`
- `el.replaceChild`
- `el.removeChild`

<!-- appendChild, insertBefore를 통한 위치의 이동 -->

---

## dataset

- `el.dataset`

---

## 노드 간 관계

- `el.childNodes`
- `el.firstChild`
- `el.lastChild`
- `el.previousSibling`
- `el.nextSibling`
- `el.parentNode`
- `el.offsetParent`

---

## 엘리먼트 크기 및 위치

- `el.getBoundingClientRect()`
- `el.offsetHeight` / `el.offsetWidth`
- `el.clientHeight` / `el.clientWidth`
- `el.scrollHeight` / `el.scrollWidth`
- `el.offsetTop` / `el.offsetLeft`
- `el.scrollTop` / `el.scrollLeft`
- `el.clientTop` / `el.clientLeft`

---

## 이벤트 전파

![inline](./images/eventphases.png)

- 버블링이 일어나는 이벤트도 있고, 일어나지 않는 이벤트도 있음 (submit, focus, blur, change 등)

<!--
참고 링크
- https://stackoverflow.com/questions/5574207/html-dom-which-events-do-not-bubble
- https://www.quirksmode.org/js/events_order.html
-->

---

## 이벤트 객체

- `e.target`
- `e.currentTarget`
- `e.stopPropagation()`
- `e.preventDefault()`

---

## 폼 이벤트

- change
- input
- focus
- blur
- submit

<!-- https://httpbin.org/ -->

---

## 마우스 이벤트

- click / dblclick
- mouseover / mouseout
- mousedown / mouseup
- mousemove

---

## 키보드 이벤트

- keydown
- keyup

---

## 스크롤 이벤트

- scroll
