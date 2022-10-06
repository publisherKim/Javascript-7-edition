# Chapter 1. Introduction to JavaScript: 챕터 1. 자바스크립트 소개
- JavaScript is the programming language of the web.
    - 자바스크립트는 웹의 프로그래밍 언어이다.
- The overwhelming majority of websites use Javascript, and all modern web borwsers on desktops, tablets, and phones include JavaScript interpreters, making JavaScript the most deployed progamming language in history.
    - 전반적으로 중요한 웹사이트는 자바스크립트를 이용하고 현대의 웹들 데스크탑, 태플릿 그리고 휴대폰들은 자바스크립트 인터프리터를 포함하고 역사적으로 자바스크립트는 대다수 배포된 개발 언어이다.
- Over the last decade, Node.js has enabled JavaScript programing outside of web borwsers, and the dramatic success of Node means that JavaScript is now also the most used programming language among software developers.
    - 지난 십년간, Node.js 웹브라우저 바깥에서 자바스크립트 언어를 가능하게 했고, 극적인 성공을  Node는 의미한다. 자바스크립트는 이제 또한 소프트웨어 개발자들 사이에서 가장 유요한 프로그래밍 언어이다. 
- Whether you're starting from scratch or are already using JavaScript professionally, this book will help you master the languange.
    - 니가 스크래치부터 시작 했던지 이미 자바스크립트를 전문적으로 이용할지라도, 이 책은 니가 이 언어의 마스터가 되는데 도움이 될 것이다.
- If you are already familiar with other programming lancuages, it may help you to know that JavaSCript is a high level, dynamic, interpreted programming language that is well suited to object oriented and functional programming styles.
    - 만약 니가 이미 다른 프로그래밍 언어에 익숙하다면, 이것은 니가 자바스크립트는 하이레벨, 동적인, 해석된 프로그래밍언어 이며  매우 잘 입혀진 객체 지향 이고 함수형 프로그래밍 스타일을 알게 하는데 도움이 될 것이다.
- The name "JavaScript" is quite misleading.
    - 자바바스크립트라는 이름은 꽤 잘못된 방향으로 이끈다.
- Except for a superficial syntactic resemblance, JavaScript is completely different from the Java programming language.
    - 자바스크립트는 인공적인 구문 유사성을 제외하고 자바 프로그래밍 언어로 부터 완전히 다르다.
- And JavsScript has long since outgrown its scripting language roots to become a robust and efficeent general purpose language suitable for serious software engineering and projects with huge codebases. 
    - 그리고 자바스크립트는 스크립팅 언어에 뿌리를 둔 언어에서 벗어났고 효율적인 범용 목적의 언어에 적합하게 되어 심각한 소프트웨어 엔지니어링과 거대한 코드조각과 함께 프로젝트들을 할 수 있게 성장한지 오래 되었다.
<pre>
 <center>JAVASCRIPT: NAMES, VERSIONS, AND MODES
자바스크립트: 이름들, 버전들, 그리고 모드들
 </center>
- JavaScript was created at Netscape in the early days of the web, and technically, "JavaScript" is a trademark licensed from Sun Microsystems (now Oracle) used to describe Netscape's (now Mozilla's) implementation of the language.
    - 자바스킵트는 웹의 초창기 나날에 네스케이프에 의해서 창도 되었고 기술적으로, 자바스크립트는 썬 마이크로시스템즈(이제는 오라클) 네스케이프(이제는 모질라)로 언어를 구현시키는데 트레이드 마크로 사용되었다.
- Netscape submitted the language for standardization to ECMA the European Computer Manufacturer's Association and beacuse of trademark issues, the standrdized version of the language was stuck with the awkaward name "ECMAScript."
    - 네스케이프는 ECMA 유럽 컵퓨터 제조사들 협회의 표준화된 언러로 제출되었고 왜냐하면 트레이드 마크 문제로, 표준화된 버전의 언어의 이름은 어색한 ECMAScript로 되었다.
- In pratice, everyone just calls the language JavaScript. 
    - 실제로, 모든 사람들은 바로 이 언어를 자바스크립트로 불렀다.
- This book uses the name "ECMAScript" and the abbreviation "ES" to refer to the language standard and to versions of that standard. 
    - 이 책은 "ECMAScript"로 이름을 사용하고 약어로 "ES" 언어의 규격화를 나타 내고 해당 표준의 버전이다.

- For most of the 2010s, version 5 of the ECMAScript standard has been supported by web browsers.
    - 2010년대 대부분, 버전 5 ECMAScript의 표준 으로 웹 브라우저에서 지원 되어졌었다.
- This book treats ES5 as the compatibility baseline and no longer discusses eariler versions of the lanuage. 
    - 이책은 ES5를 호환성 기준으로써 다루고 더이상 언어의 초기 버전에 대해서 토론하지 않을 것이다.
- ES6 was released in 2015 and added major new features including class and module syntax that changed JavaScript from scripting language into a serious, general-purpose language suitable for large scale software engineering.
    - ES6는 2015년에 배포 되었고 중요한 새로운 특징들은 추가 되었어, 클래스와 모듈 syntax등을 포함하여 이러한 것들이 자바스크립트를 스크립팅 언어에서 진지하게 일반적인 목적의 언어에 적합한 소프트웨어 엔지니어를 위해 변화되었어.
- Since ES6, the ECMAScript specification has moved to a yearly release cadence, and versions of the language ES2016, ES2017, ES2018, ES2019, and ES2020 are now idetified by year of relaease.
    - ES6 이후로, ECMAScript는 사양은 해마다 배포 되고 언어의 버전들은 ES2016, ES2017, ES2018, ES2019, and ES2020 해마다 배포함으로써 식별되어졌어.
- As, JavaSCript evolved, the language designers attempted to correct flaws in the early (pre-ES5) versions.
    - 자바스크립트는 진화함으로써, 이 언어의 디자이너들은 초기 버전들을 올바른 방향으로 흐르게 시도 되어졌어.
- In order to maintain backward compatibility, it is not possible to remove legacy features, no matter how flawed.
    - 이전 버전과 호환성을 유지하기 위해서, 얼마나 결함이 있던지 이전 특징들을 지우지 않아도 가능하지 않았어.
- But in ES5 and later, programs can opt in to JavsScript's srict mode in which a number of early language mistakes have been corrected. 
    - 그러나 ES5와 이후로의 프로그램들은 자바스크립트의 strict mode 속에서는 초기 언어의 실수들은 수정되어졌어.
- The mechanism for opting in is the "use strict" directive described in 5.6.3 
    - 기계적으로 "use strict"를 고르는 것은 5.6.3에 직접적으로 설명 되어져 있어.
- That section also summarizes the differences between legacy JavaScript and strict JavaScript.
    - 저 섹션은 또한 요약하면, 이전 자바스크립트와 스트릭트 자바스크립트 사이의 차이들이야.
- In ES6 and later, the use of new language features often implicitly invokes strict mode.
    - ES6와 이후로는, 새로운 언어의 특징들로는 암시적으로 strict mode를 호출해서 사용해.
- For example, if you use the ES6 class keyword or create an ES6 module, then all the code within the class or module is automatically strict, and the old, flawed features are not avilable in those context.
    - 예를 들어 만약 니가 ES6 class 단어 또는 ES6 module을 만든다면, 모든 코드들은 class 또는 모듈 안에서 자동적으로 strict 되고 오래된, 결함이 있는 특징들은 이들의 문맥 안에서는 이용이 가능하지 않아.
- This book will cover the legacy features of JavaScript but is careful to point out that thet are not available in strict mode.
    - 이 책은 자바스크립트의 레가시 특징들로 덮여 있지만, strict mode에서는 이용이 가능하지 않다는 점을 주의해.
</pre>
- To be useful, every language must have a platform, or standard library, for performing things like basic input and output.
    - 유용하기 위해서, 모든 언어들은 플랫폼을 또는 표준화된 라이브러리 가지고 있어, 수행을 위한 것들 마치 기본적인 입력 과 출력 
- The core JavaScript language defines a minimal API for working with numbers, text, arrays, sets, maps, and so on, but does not include any input or output functionality.
    - 자바스크립트 언어 코어에는 최소한의 API들만 numbers, text, arrays, sets, maps, 기타등등이 함께 작동을 위해 정의 되어져 있지만 입력과 출력이라는 기능은 전현 포함 되어져 있지 않았다.
- Inpuit and output(as well as more sophisticated features, such as networking, storage, and graphics) are the responsibility of the "host environment" within which JavaScript is embedded.
    - 입력과 출력은(정교한 특징으로써 networking, storage, 그리고 graphics 등) 자바스크립트에 포함된 host environment의 책임이다.
- The original host environment for JavaScript was a web browser, and this is still the most common execution environment for JavaSCript code.
    - 자바스크립트의 근본적인 host environment은 웹 브라우져 였고 이것은 여전히 자바스크립트 코드를 위해 가장 흔한 실행 환경이다.
- The web browser environment allows JavaScript code to obtain input from the user's mouse and keyboard and by making HTTP requests.
    - 이 웹브라우져의 환경은 자바스크립트 코드가 입력을 얻기 위해 사용자의 마우스와 키보드 그리고 HTTP 요청을 만드는 것을 허용한다.
- And it allows JavsScript code to display output to the user with HTML and CSS.
    - 그리고 이것은 자바스크크립트 코드가 출력을 유저에게 HTML과 CSS를 함께 전시하는것을 허용한다.
- Since 2010, another host environment has been avaiable for JavaScript code.
    - 2010년 이후로, 또다른 host environment가 자바스크립트 코드를 위해 이용 가능해 졌다.
-  Insetead of constraining JavaScript to work with the APIs provided by web browser, Node gives JavsScript access to the entire operating system, allowing JavaSCript programs to read and write files, send and receive data over the network, and serve HTTP requests.
    -  자바스크립트를 구속하는 대신에 API들과 함꼐 작동하기 위해서 웹 브라우져는 제공 되어졌고, Node는 완벽한 작동 체계로 자바스크립트를 접근하게 해줬고, 자바스크립트 프로그램들에게 파일들을 일고 쓰게 해 주었고, 네트워크 위로 데이터를 주고 받고 HTTP 요청을 제곻 해 주었다.
- Node is a popular choice for implementing web servers and also a convenient tool for writing simple utility scripts as an alternative to shell scripts.
    - 노드는 웹서버들을 구현하기 위해 인기 있는 선택이고  또한  shell scripts를 대처할 간단하고 유용한 스크립트들을 쓰기 위한 편리한 도구 이다.

- Most of this book is focused on the JavsSCript language itself.
    - 이 책은 대부분은 자바스크립스 언어 스스로에 초점 되어져 있다.
- Chapter 11 documents the JavaScript standard library,
    - Chapter 11 문서들과 자바스크립트 표준 library,
- Chapter 15 introdouces the web browser hos environment, and
    - Chapter 15 소개 이 웹 브라우저 host environment, 그리고
- Chapter 16 introduces the Node host environment.
    - Chapter 16 the Node host environment 소개.

- This book covers low-level fundamentals frist, and then builds on those to more advanced and high-level abstractions.
    - 이 책은 처음에는 낮은 수준의 기능들로 덮여져 있고 그다음으로는 이런한 것들에서 더많이 발전하고 높은수중의 추상화를 세운다.
- The chapters are intended to be read more or less in order.
    - 챕터들은 더 많이 순서대로 읽거나 덜 읽는 경향이 있다.
- But learning a new programming language is never a linear process, and describing a language is not linear either: each language feature is related to other features, and this book is full of cross-references sometimes backward and sometiemes forward to related material.
    - 그러나 새로운 프로그래밍 언어를 배우는것은 결코 가벼운 과정은 아니고 언어를 설명하는 것 역시 결코 가볍지 않다.
    - 각 언어의 특징은 다른 특징과 연관성이 있고 이 책은 교차 레퍼런스들로 가득차서 때로는 뒤로 때로는 앞으로 가며 연광성을 파악해야 한다.
- This introductory chapter makes a quick first pass through the language, introducing key features that will make it easier to understand the in-depth treatment in the chapters that follow.
    - 이 소개 챕터는 이 언어를 빠르게 패스 하게 만들며, 주요 기능 소개는 챕터들에 따르는 깊이 있는 다룸을 이해하는데 좀더 쉽게 만들어 줄 것이다.
- If you are already a practiong JavaSCript prgrammer, you can probably skip this chapter.
    - 만약 니가 이마 자바스크립트 프로그래머로써 수행하고 있다면, 너는 아마도 이 챕터를 넘어가도 될수 있다..
- (Although you might enjoy reading Example 1-1 at the end of the chapter before you move on.)
    - 비록 니가 이 장의 끝 부분에 있는 예제 1-1 을 읽을 것을 즐겨 할 지 몰라도, 니가 이동하기 전에.

## 1.1 Exploring JavaScript: 자바스크립트 탐색
- When learning a new programming language, it's important to try the examples in the book, then modify then and try them again to test your understanding of the language.
    - 새로운 프로그래밍 언어를 배우는 중이라면, 책의 예제들을 시도하는 것은 중요하고, 다음으로 그것들에 관하여 테스트하고 시도하는 것이 너의 이 언어를 이해하는데 좋을거야.
- To do that, you need a JavsScript interpreter.
    - 그렇게 해라, 너는 자바스크립트 인터프리터가 필요하다.
- The easiest way to try out a few lines of JavaScript is to open up the web developer tools in your web browser (with F12, Ctrl-Shift-I, or Command-Oprion-I) and select the Console tab.
    - 가장 쉬운 방법은 웹 브라우저의(F12, Ctrl-Shift-I, or Command-Oprion-I와 함께, ) 개발자도구들을 열고 몇줄의 자바스크립트 줄을 시도해 보는거야 그리고 Console tab을 선택하는 것도.
- You can then type code at the prompt and see the results as you type.
    - 너는 그러면 프로프트에 코드를 쓰고  네가 쓴 결과를 볼수 있어.
- Browser developer tools often appear as panes at the bottom or right of the browser winodw, but you can usually detach them as separtat windows(as pictured in Figure 1-1), which is often quite convenient.
    - 브라우저 개발자 도구는 종종 판으로써 웹브라우저 창의 바닥 또는 오른쪽에 나타나지만, 너는 이것들을 창과 분리해서(사진 1-1 처럼) 떼어 낼 수 있어 이것은 종종 꽤 편리한 방법이야.
<center>- Figure 101. The JavaScript console in Firefox's Developer Tools</center>
- Another way to try out JavaScript code is to download and install Node from https://nodejs.org.
    - 또 다른 방법으로는 자바스립트 코드를 다운로드 받고 https://nodejs.org.로 부터 Node를 인스톨 하는 거야.
- Once Node is installed on your system, you can simply open a Terminal window and type node to begin an interactive JavaScript session like this one:
    - Node의 설치는 너의 시스템에 한 번 하게 되면, 간단히 윈도우 터미널에서 열 수 있고 node라고 쓰면 JavaSCript session 다음과 같이 시작 될거야.
<code>
$node
Welcome to Node.js v12.13.0.
Type ".help" for more information.
> .help
.break Sometimes you get stuck, this gets you out
.cleear Alias for .break
.editor Enter editor mode
.exit Exit the repl
.help Print this help message
.load Load JS from a file into the REPL session
.save Save all evaluated commands in this REPL session to a file

press ^C to abort current expression, ^D to exit the repl
> let x = 2, y = 3;
undefined
> x + y 
5
> (x === 2) && (y === 3)
true
> (x > 3) || (y < 3)
false
</code>
