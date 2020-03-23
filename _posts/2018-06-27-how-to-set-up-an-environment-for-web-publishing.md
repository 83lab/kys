---
layout: post
title:  "How to set up an environment for web publishing?"
date:   2018-06-27 14:51:45 +0900
categories: web publishing
---
사실 여타 다른 개발(develop)과는 다르게 일반적인 웹 퍼블리싱(Web Publishing)은 특별한 환경이 필요 없습니다. 
그냥 웹 브라우저에서 디자인된 화면만 잘 출력되면 되기 때문입니다. 
하지만 일에는 효율이라는 것이 있으므로, 웹 에디터를 설치하면 퍼블리싱에 도움이 됩니다. 
그리고 이렇게 작업된 웹 화면을 테스트할 브라우저가 필요할 겁니다. 

그래서 우선 필요한 프로그램들부터 설치해 보도록 하겠습니다.

Install web browser
---

웹 퍼블리싱을 위해서 주로 사용하는 브라우저는 Microsoft의 인터넷 익스플로어와 Google의 크롬입니다.   
사실상 이 두 브라우저가 거의 독식을 하고 있기 때문에, 가장 우선적으로 고려되는 웹 브라우저입니다.

인터넷 익스플로어를 설치하기 위해서는 아래의 링크와 연결된 페이지에서 설치 파일을 다운 받으시면 됩니다.   
사실 윈도우 컴퓨터의 경우에는 기본적으로 설치 되어 있습니다.
https://support.microsoft.com/ko-kr/help/17621/internet-explorer-downloads

구글 크롬을 설치하기 위해서는 아래의 링크와 연결된 페이지에서 설치 파일을 다운 받으시면 됩니다.   
저는 주로 크롬을 사용합니다.
https://www.google.co.kr/chrome/

Install code editor
---

웹 에디터라고도 하고 텍스트 에디터라고도 하는 에디터를 설치할 차례입니다.
사실 이 파트에서 가장 중요한 부분입니다. 

우리가 사용할 에디터는 Microsoft에서 배포하는 Visual Studio Code라는 에디터입니다. 
이 Visual Studio Code는 여러 프로그래밍 언어를 지원합니다. 
그중에서도 우리는 HTML, CSS, JS(javascript)를 사용할 것입니다. 
VS Code를 설치하기 위해서는 아래의 링크와 연결된 페이지에서 설치 파일을 다운 받으시면 됩니다.
https://code.visualstudio.com/

이제는 효율적으로 작업을 진행하기 위해서 몇 개의 플러그인을 설치하고자 합니다.
VS Code의 장점이 바로 이런 수 많은 플러그인을 설치할 수 있다는 것입니다.   
아래에는 제가 주로 사용하는 플러그인입니다.
- HTML Snippets
- Auto Close Tag
- Auto Rename Tag
- IntelliSense for CSS class names in HTML
- Beautify

Install plug-in
---

**VS Code 첫 화면**

VS Code의 첫 화면입니다.
Microsoft에서는 이런 간결한 디자인으로 전부 뽑으려나봅니다. 
메뉴들을 보면 파일을 불러오거나 git에 접근하거나, 디버깅을 위한 메뉴들이 있지만, 그런건 지금 중요하지 않습니다.    
![welcome page](/kys/assets/img/2018-06-27-post-01.png)   
우선은 이 화면에서 왼쪽의 네개의 아이콘 중에 맨 아래의 블럭 모양의 아이콘 extensions를 클릭하면 두번째 사진과 같은 ui로 바뀌는 것을 알 수 있습니다.

**플러그인 검색**

extensions에서는 플러그인을 검색할 수 있습니다. 
간단하게 CSS 관련 플러그인을 찾기위해서 검색어 'CSS'를 입력하면 관련 플러그인들이 나옵니다.    
![search plug-in](/kys/assets/img/2018-06-27-post-02.png)
많이도 나오지만, 우리는 IntelliSense for CSS class names in HTML만 찾으면 됩니다.   

**플러그인 설치**

원하는 플러그인을 찾으셨다면 "install" 버튼만 클릭해주면 됩니다. 
이제 우리가 찾은 "IntelliSense for CSS class names in HTML"이라는 플러그인이 설치되었습니다.
오른쪽은 위에 언급된 플러그인들이 모두 설치된 화면입니다.   
![installed plug-in](/kys/assets/img/2018-06-27-post-03.png)  
이 외에도 많은 플러그인들이 있으므로 필요에 맞춰서 플러그인을 설치 및 제거하여 더 쾌적하게 퍼블을 할 수 있을 것입니다.

***
<small>
위에서 언급한 VS code 이 외에도 무료로 사용할 수 있는 코드 에디터는 많습니다. 
그 중에 인기 있는 것으로는 서브라임 텍스트, 아톰, 브라켓등이 있습니다. 
이 중에서도 브라켓(Brackets)은 Adobe에서 만든 에디터로 UX, UI, Web designer를 위해 만들었다고 보시면 됩니다.
</small>