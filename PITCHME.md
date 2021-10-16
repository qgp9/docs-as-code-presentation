---
marp: true
title: Marp CLI example
description: Hosting Marp slide deck on the web
theme: uncover
paginate: true
_paginate: false
class: invert
---
<!--
![bg](#123)![](#fff)
-->

# <!--fit--> Docs as Code

FinKoDev Core-Summit 2021
Beomsu Chang

---

## Docs as Code
문서를 코드처럼 관리하자

---

https://www.writethedocs.org/guide/docs-as-code
https://www.docslikecode.com
https://about.gitlab.com/handbook/handbook-usage/

---

## 문서를 코드처럼 관리하자.
* Issue Trackers
* Version Control (Git)
* Plain Text Markup (Markdown, reStructuredText, Asciidoc)
* Code Reviews
* Automated Tests

---

## 특히
1. 텍스트 문서 (Markdown, reStructuredText, Asciidoc)
2. 버젼 컨트롤 (Git)
3. 코드리뷰 (깃헙 머지 리퀘스트)

---

## 1. 텍스트 문서

---

### 장점
* 쉬운 버젼컨트롤 = 쉬운 비교
* 구조화된 내용
* 내용에 집중할 수 있음

---

### 단점
* 복잡한 문서는 어려움
* 러닝커브

---
### 마크다운 Markdown
구조가 단순하고 <br/> 개발자들이 가장 범용적으로 사용하는 형식
```
# 제목

내용

* 리스트1
* 리스트2
```
---

## 2. 버젼컨트롤

---
### Git
최근 가장 많이 사용되는 버젼 컨트롤 시스템
### GitHub
git 기반의 종합종합 서비스!
보너스: 웹기반 에디터, 이슈트레커, 위키, 코드리뷰 등등등.

---

### 히스토리와 비교

---
##### <!--fit--> [Marp CLI](https://github.com/marp-team/marp-cli) + [GitHub Pages](https://github.com/pages) | [Netlify](https://www.netlify.com/) | [Vercel](https://vercel.com/)

##### <!--fit--> 👉 The easiest way to host<br />your Marp deck on the web

---


---

![bg right 60%](https://icongr.am/octicons/mark-github.svg)

## **[GitHub Pages](https://github.com/pages)**

#### Ready to write & host your deck!

[![Use this as template h:1.5em](https://img.shields.io/badge/-Use%20this%20as%20template-brightgreen?style=for-the-badge&logo=github)](https://github.com/yhatt/marp-cli-example/generate)

---

## **[Netlify](https://www.netlify.com/)**
![bg right 60%](https://icongr.am/simple/netlify.svg?colored)

### abc

#### Ready to write & host your deck!

[![Deploy to Netlify h:1.5em](./assets/netlify-deploy-button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yhatt/marp-cli-example)

---

![bg right 60%](https://icongr.am/simple/zeit.svg)

## **[Vercel](https://vercel.com/)**

#### Ready to write & host your deck!

[![Deploy to Vercel h:1.5em](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/yhatt/marp-cli-example)

---

### <!--fit--> :ok_hand:

---

![bg 40% opacity blur](https://avatars1.githubusercontent.com/u/3993388?v=4)

### Created by Yuki Hattori ([@yhatt](https://github.com/yhatt))

https://github.com/yhatt/marp-cli-example
