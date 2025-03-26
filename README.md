<h1 align="center">2025-1 경기대학교 AI컴퓨터공학부 캡스톤 디자인</h1>
<h2 align="center">웹 기반 교통 시뮬레이션 게임 🚥🚐🚌=3</h3>

<hr>

<h2 align="left">프로젝트 개요</h3>
<h3><b>WHAT 🎮</b></h3>
<p>웹에서 작동하는 온라인 멀티플레이어 게임입니다.</p>
<p><b>게임 규칙</b></p>
<p>참여자1과 참여자2가 공격과 수비를 번갈아 가며 수행합니다.</p>
<p>공격은 자신이 설정한 자동차의 출발 위치와 출발 시간을 지정합니다.</p>
<p>수비는 신호등이나 장애물을 설치합니다.</p>
<p>게임이 끝나면 목표를 달성한 시간, 사고 유무와 같은 요소에 점수를 책정해 승리자를 정합니다.</p>
<h3><b>WHEN 🗓</b></h3>
<p>March 2025 -</p>
<h3><b>WHO 🧑‍🎓</b></h3>
<p>TEAM JAMES (J and Miracle Extreme students)</p>
<ul>
  <li><b>조해천</b> <a href="https://www.github.com/dasfaf4464"><img src="https://simpleicons.org/icons/github.svg" witdh="20" height="20"></a> (dasfaf4464) &nbsp&nbsp|| 웹서버, API서버를 제작했습니다.</li>
  <li><b>문준서</b> <a href="https://www.github.com/odpd09091"><img src="https://simpleicons.org/icons/github.svg" witdh="20" height="20"></a> (odpd09091) &nbsp&nbsp|| API서버를 제작했습니다.</li>
  <li><b>이상훈</b> <a href="https://www.github.com/KGU-LSH"><img src="https://simpleicons.org/icons/github.svg" witdh="20" height="20"></a> (KGU-LSH) &nbsp&nbsp|| 3D 오브젝트 및 게임 시스템을 제작했습니다.</li>
  <li><b>이지연</b> <a href="https://www.github.com/leejiyeoniya"><img src="https://simpleicons.org/icons/github.svg" witdh="20" height="20"></a> (leeeeejy) &nbsp&nbsp|| 웹페이지, DB를 제작했습니다.</li>
</ul>
<h3><b>HOW ⚙</b></h3>
<ul>
	<li>Client <p>HTML, CSS, JS</p></li>
	<li>Server</li> <p>C_[ Windows-(ws2_32.dll) ]</p>
</ul>

<hr>

<h2>설계도</h2>

<hr>

<h2>프로젝트 구조</h2>
<p>Project</p>

``` css
Project
├── src
│    ├── Client
│    │
│    │
│    │
│    ├── Server
│
│
└── Asset

```
<hr>

<h2>프로젝트 미리보기</h2>

<hr>

<h2>구현 로직 설명</h2>

<hr>

<h2>레퍼런스</h2>
<ol>
	<li>(http://www.robinpayot.com/) 3d 그래픽</li>
</ol>

<hr>

<h2>프로젝트 규칙</h2>
<details><summary><h3>Code Convention 🐫</h3></summary>
	<p>모든 변수와 함수는 Camel Case로 작성합니다. 소문자로 시작합니다. 변수는 담는 자료의 역할을 표현해야 합니다. ex)bool isTrue, int firstAdded</p>
	<p>들여쓰기는 tab으로 작성합니다.</p>
	<p>축약어는 전부 대문자로 작성합니다. ex) IP, TCP</p>
	<p>'(...)' 소괄호는 키워드와 바로 연결됩니다. ex) if(asd)</p>
	<p>'{...}' 중괄호의 시작은 한 칸 띄어 사용합니다. ex) while() {</p>
	<p>변수의 위치는 로직이 시작되기 전 맨 위에 선업합니다.</p>
	<p>각 변수나 함수들의 기능이 하나의 단위를 이루면 연결해서 작성합니다. 관계가 없거나 다른 단위이면 한칸 띄어 작성합니다.</p>
</details>
<details><summary><h3>Comment 💬</h3></summary>
	<p>모듈(클래스, C 소스) 위에 '/* ... */'(여러 줄)으로 작성합니다. 작성자, 해당 모듈이 제공하는 기능과 역할을 작성합니다.</p>
 	<p>함수 선언(인터페이스, 헤더) 위에 '/* ... */(여러 줄)으로 작성합니다.</p>

``` c
/*
* 함수 기능 설명, 사용되는 상황, 연결된 자료구조, 인수 조건 등을 적습니다.
*/
 function(arg);
```
``` java
/*
* 클래스가 제공하는 기능, 핵심 함수, 작성자 등을 적습니다.
*/
class Module1 {
```
	
  <p>기능을 종합해서 수행하는 함수 모음 위에 '//...'(한 줄)으로 작성합니다.</p>
	<p>작성자의 메모는 함수와 키워드와 같은 줄에 작성합니다.</p>
 
``` javascript
//화면을 출력하기 위한 함수
func1();
func2();
func3();
```
``` c++
func1(); //메모, 의문점, 수정할 사항 등
for() {//...
```
</details>
<details><summary><h3>Git 🐱‍💻</h3></summary>
	
</details>
<hr>

<h2>팀원 공간</h2>
<h3>할 일 ✅</h3>
<p>설계도 및 유즈케이스 시나리오 작성</p>
<p>논문 초록 작성 & 논문 작성</p>
<p>사업 계획서 작성</p>
<p>자문 전문가 선정</p>
<p>참여할 학회 선정</p>
<h3>진행 상황 🏃</h3>
<b>Front</b><p>html,css 생성</p>
<b>Server(Web & Hosting)</b><p>window TCP/IP socket 연결</p>
<b>Server(API)</b><p>...</p>
<b>DataBase</b><p>...</p>
<b>Game</b><p>...</p>
<h3>개발 과정 🗒</h3>
<details><summary>1주차 (2025.03.05 - 2025.03.11) [START]</summary>

> 팀원 선정
 
</details>
<details><summary>2주차 (2025.03.12 - 2025.03.18)</summary>
	
> 주제 선정

</details>
<details><summary>3주차 (2025.03.19 - 2025.03.25)</summary>
	
> 기본 설계 공유  
> 역할 분담  
> 협업 규칙 확정

</details>
<details><summary>4주차 (2025.03.26 - 2025.04.01)</summary>
	
> WEB server에서 TCP/IP 네트워크 관련 제작
> 게임 로직 작성

</details>
<details><summary>5주차 (2025.04.02 - 2025.04.08)</summary>
	
> ...  

</details>
<details><summary>6주차 (2025.04.09 - 2025.04.15)</summary>
	
> ...  

</details>
<details><summary>7주차 (2025.04.16 - 2025.04.22)</summary>
	
> ...  

</details>
<details><summary>8주차 (2025.04.23 - 2025.04.29)</summary>
	
> ...  

</details>
<details><summary>9주차 (2025.04.30 - 2025.05.06)</summary>
	
> ...  

</details>
<details><summary>10주차 (2025.05.07 - 2025.05.13)</summary>
	
> ...  

</details>
<details><summary>11주차 (2025.05.14 - 2025.05.20)</summary>
	
> ...  

</details>
<details><summary>12주차 (2025.05.21 - 2025.05.27)</summary>
	
> ...  

</details>
<details><summary>13주차 (2025.05.28 - 2025.06.03) [END]</summary>
	
> ...  

</details>
