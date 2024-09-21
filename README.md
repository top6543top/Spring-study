# Spring-study

## 1. 프로젝트 생성

1. spring.io

빌드 툴은 최근에 Gradle을 사용 -> 버전 결정하고 어떤 라이브러리를 끌고오는지 결정

dependencies는 어떤 라이브러리를 끌어다 쓸것이냐를 결정한다. 

web프로젝트를 진행하니깐 Spring web 선택

html과 같은 프론트를 하는 데 필요한 templete engine으로 thymeleaf를 선택한다

---

2. intellij

java 파일을 제외한 모든 파일은 resources 파일에 저장

Spring은 tomcat이라는 웹서버를 내장하고 있다.

gradld은 의존 관계의 library도 다 땡겨온다.

ex) start-web에 필요한 모든 라이브러리를 당겨옴.

---

3. welcome page

welcome page 는 index.html에서 시작, 그게 없다면 index 템플릿을 찾는다.
