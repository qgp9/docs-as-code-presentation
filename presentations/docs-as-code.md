---
marp: true
title: Docs as Code
description: Docs as Code 슬라이드
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
Beomsu.Chang@gmail.com

---

## Docs as Code?
문서를 코드처럼 관리하자
* 현대 코드 관리는 그 복잡함 때문에
* 코드를 관리하고 협업하기 위한
다양한 방법이 발달되어 있음
* 그 방법들을 문서에도 적용하자.
---

## 참고
https://www.writethedocs.org/guide/docs-as-code  
https://www.docslikecode.com  
https://about.gitlab.com/handbook/handbook-usage/  

---

## Modern 코드 관리의 기본 요소
* Issue Trackers
* Version Control (Git)
* Plain Text Markup (Markdown, reStructuredText)
* Code Reviews
* Automated Tests

---

## 특히 Docs as Code 의 핵심은
1. 텍스트 문서 (Markdown, reStructurredText)
2. 버젼 컨트롤 (Git)
3. 코드리뷰 (깃헙 머지 리퀘스트)
### 그리고
Publish/Test

---

### 장점
코드를 관리의 현대적인 다양한
에코시스템을 적용할 수 있음

### 단점
배우고 관리하는데 러닝커브가 있음


---

## 1. 텍스트 문서
일단 문서를 텍스트로 만들면 코드를 관리하듯  
버젼컨트롤/코드리뷰 기능을 사용할 수 있음
HTML, Markdown, reStructurredText, Asciidoc, 그냥 TXT
Wikipedia 도 텍스트 문서
 

---

### 장점
* 쉬운 버젼컨트롤 = 쉬운 비교
* 구조화된 내용
* 내용에 집중할 수 있음

---

### 단점
* 복잡한 문서는 어려움 (장점이기도 함)
* 러닝커브

---
### 마크다운 Markdown
구조가 단순하고 <br/> 개발자들이 가장 많이 사용하는 문서 형식
```
# 제목

내용

* 리스트1
* 리스트2
```
---

### 예제) 1단계 : 마크다운 문서 작성
GitHub:
코드 관리 서비스 이지만
Doc as Code 를 위한 거의 모든 기능을 제공공
https://github.com/finko-dev/docs-as-code-example-1

~~어려운 커맨드~~
~~프로그램 설치~~
그냥 github 웹페이지로 다 합니다.

---

## 2. 버젼컨트롤

---

### Git
최근 가장 많이 사용되는 버젼 컨트롤 시스템
### GitHub
git 기반의 종합종합 서비스!
보너스: 웹기반 에디터, 이슈트레커, 위키, 코드리뷰 등등등.

---

### Git 의 장점
구글독스의 버젼 관리보다 진화되고
구조적인 버젼관리를 제공
GitHub / GitLab / Gitea 등의
어마무시하고 대단한 서비스가 있음

### 단점
어려움 ㅋㅋ

---

### 예제) 2단계: 문서 수정하고 히스토리 보기
https://github.com/finko-dev/docs-as-code-example-1

---

## 코드리뷰
* PR(Pull Request) 또는 MR(Merge Request)
* 문서의 추가/변경을 제안하고 함께 리뷰하는 협업시스템
* branch 또는 fork 를 이용하는 두가지 방법
### 장점: 세밀한 협업이 가능
### 단점: 어려움

---

### 예제) 코드리뷰: branch 를 이용한 PR
https://github.com/finko-dev/docs-as-code-example-1

---

### 예제) 코드리뷰: fork 를 이용한 PR
https://github.com/finko-dev/docs-as-code-example-1

---

## Publish / Test
작성한 문서를 웹페이지로 보기 좋게 publish 
##### <!--fit--> [GitHub Pages](https://github.com/pages) | [Netlify](https://www.netlify.com/) | [ReadTheDocs](https://readthedocs.io/) | ...

---

### readthedocs.io
테크니컬 문서를 위한 서비스
Docs as Code 와 잘 맞음
GitHub / GitLab 등의 서비스와 연동 가능
리뷰할 때 preview 기능을 지원(Test)

---

### 예제) readthedocs.io publish
https://github.com/qgp9/docs-as-code-example-readthedocs
https://docs-as-code-example-readthedocs.readthedocs.io/

---

### 예제) readthedocs.io 리뷰
https://github.com/qgp9/docs-as-code-example-readthedocs
https://docs-as-code-example-readthedocs.readthedocs.io/

---

## GitLab handbook
* https://about.gitlab.com/handbook/
* GitLab 은 GitHub 과 비슷한 서비스를 제공하는 회사
* All remote work 회사로 유명함
* GitLab handbook 이라는 문서를 모든 의사소통의 기반으로 사용
* GitLab handbook 은 Docs as Code 로 관리 

---

## GitLab Handbook Usage
https://about.gitlab.com/handbook/handbook-usage/#why-handbook-first


---

## GitLab Handbook Usage: 핵심
* 모든 의사소통/토론/질문은 가능한한 핸드북 링크를 이용한다. (link first)
* 의사소통에 필요한 내용이 핸드북에 없다면 추가한다. (PR) 
* 모든 제안은 가능한한 PR 을 기반으로 한다.

---

## PR 코드리뷰의 장점
* 실재 변경사항을 보여주고 토론할 수 있다
* 바로 문서에 반영되지 않기 때문에, 두려움 없이 제안을 할 수 있다
(Wiki 의 경우 바로 반영되기 때문에 심리적 장벽이 있음)
* 문서에 반영되지 않더라도 정보로 남는다.

---

## <!--fit--> 감사합니다.

---

## <!--fit--> Q&A

---

## <!--fit--> 보너스!

---

### 이 슬라이드도 Markdown 입니다
* https://github.com/qgp9/docs-as-code-presentation
* 이 문서에는 일부러 낸 오타들이 있씁니다.
* 오타나 다른 제안을 PR 해 주시는 분들께 맥주 샵니다.
* 필란드 돌아가면.
* 선착순 5명!
