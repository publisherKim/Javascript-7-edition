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