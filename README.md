# Newbie-Guideline

해당 문서는 프로그래밍/개발에 입문하려는 모든 뉴비들(컴퓨터학과 신입생, 비전공 개발 입문자 등)을 위한 지침서입니다.

## Prerequisite

프로그래밍은 다른 분야와 비교하여 선수지식이 적은 편이라고 생각하지만, 그럼에도 불구하고 알아두면 좋은 선수지식들이 있습니다. 
특정 프로그래밍 분야들은 심도있는 선수지식이 필요한 경우도 있긴 하지만, 아래 내용 하나만큼은 일반적으로 도움이 되는 선수지식입니다:
* 영어 : 보통 선수지식으로 수학을 생각하는 분들이 많은데, 의외로 정말 필요한 선수지식은 영어입니다. 수학은 분야에 따라 많이 쓰이기도 하지만 전혀 쓰이지 않을 수도 있습니다. 반면에 영어는 공부를 하다보면 필수불가결한 스킬입니다. 책이나 문서 등 양질의 공부 자료들은 대부분 영어로 작성되어 있으며, 무엇보다 공부하는 과정에서 굉장히 많은 검색을 하게 될텐데 대부분의 원하는 결과는 Stack Overflow나 Quora라는 해외 사이트에서 찾을 수 있습니다. 영어 능력에서 오는 차이는 고급 개발자가 될수록 더욱 심화되므로, 본인의 영어 능력이 부족하다고 한국어로 되어있는 책이나 자료만 고집하지 말고 천천히 공부해서 영어 자료들에 친해지도록 합시다.
  * [IT 개발자의 영어 필살기](http://www.yes24.com/Product/Goods/85385648) : IT 업계에서 주로 사용하는 표현과 단어들을 접해볼 수 있습니다. 난이도는 굉장히 쉬운편이고 굉장히 얇아서 해당 책으로 새로운 공부를 한다는 느낌은 아니고, 해당 책을 통해서 앞으로 어떤 영어를 어떻게 공부할 지 길라잡이로 사용할 수 있습니다.
  * [English for Developers](http://www.yes24.com/Product/Goods/19992192) : IT 업계에서 주로 사용하는 표현과 단어들을 어느정도 익힐 수 있습니다. 난이도가 어렵진 않지만 위 책보다는 어려운 편이며, 어느정도 영어 표현들에 대한 학습을 할 수 있습니다.
  * [Grammar in use intermediate](http://www.yes24.com/Product/Goods/61953545) : 학창 시절 한번씩은 들어봤을 유명한 영어 문법서입니다. 해당 책을 두세번 정독하고 나면 영어를 읽고 쓰는데 확실히 도움되는 것이 체감됩니다.
  * [Computer Science and Technology Vocabulary](https://www.vocabulary.com/lists/1508153) : Computer Science(이후 CS)와 관련된 용어들 리스트와 간단한 뜻이 적혀 있습니다. 한번씩 눈에 익혀두면 좋습니다.
  * [Glossary of computer science](https://en.wikipedia.org/wiki/Glossary_of_computer_science) : 위와 마찬가지로 용어 리스트와 간단한 뜻들이 적혀 있습니다. 한번씩 익혀두면 좋습니다.
  * 위 자료들은 굉장히 빠르게 학습할 수 있는 내용들입니다. 가볍게 학습하고 나서, 주기적으로 원서를 읽고 Stack Overflow나 Quora 글들을 보며 영어에 친숙해지도록 합시다.

## Computer Language

개발 공부를 시작하면서 가장 처음 접하게 되는 것은 아무래도 컴퓨터 언어일 것입니다. (간혹가다가 컴퓨터구조같은 것들을 공부하며 입문하는 예외적인 케이스도 보긴 했습니다만..)  
컴퓨터 언어는 말 그대로 컴퓨터에서 동작하는 소프트웨어(프로그램)을 작성하기 위한 언어입니다.  
처음 공부하는 분들의 입장에서는 정말 수많은 컴퓨터 언어 중에 무엇을 공부하는 것이 가장 좋을지 막막할 수도 있습니다.  
또, 어떤 분은 대체 왜 이렇게 많은 컴퓨터 언어가 존재하는지 의아해할수도 있습니다. (이런 의문을 갖는 것은 매우 좋습니다.)  
컴퓨터 언어들은 저마다 고유한 특색을 가지고 있고, 장단점이 있습니다. 이러한 언어의 특성 때문에 특정 컴퓨터 분야에는 특정 언어가 어울리게 됩니다.  
예를 들어, 안드로이드 앱 개발을 할 때에는 Java와 Kotlin이라는 언어를 주로 쓰게 됩니다. (NDK개발을 한다면 C/C++도 많이 쓰게 됩니다.)  
웹 개발자라면 Javascript와 Java를 많이 다루게 될 것이고, 게임 개발자라면 C++이나 C#을 많이 사용할 것입니다.  
시스템 개발자라면 C와 C++를 주로 쓰게 될 것이며, 윈도우 응용 프로그램 개발자라면 C#과 일부 C++을 쓸 것입니다.  
혹은, 정말 어쩌면, 매니악한 분야를 좋아하여 로우 레벨 개발을 하게 된다면 C와 어셈블리를 사용하게 될 것입니다.  
이처럼 많은 분야와 많은 언어들이 있는데 이들을 모두 공부해야하는 것은 아닌가 걱정이 될 수 있습니다.  
하지만, 언어는 어디까지나 도구일 뿐이며 해당 언어를 사용하여 무언가를 만들어내는 능력이 중요합니다. (물론, 컴파일러나 언어론 자체를 전공하는 예외적인 케이스는 제외합니다.)  
그리고 보통 하나의 언어를 숙달하고 나면 다른 언어를 익히는 시간은 굉장히 줄어듭니다.  
제 경우 처음 공부한 언어가 C언어였는데, 언어를 처음 공부한 시점부터 해당 언어로 무언가 그럴싸한 프로그램을 만들어내기까지 거진 6개월이라는 시간이 걸렸던거 같습니다.  
반면, 자바를 공부하기 시작한지 1주일만에 정부 사업으로 진행한 앱을 만들었고, 파이썬을 공부한지 이틀만에 그럴싸한 프로그램을 만들어냈습니다.  
이러한 극단적인 시간 축소에는 언어의 특성적인 측면도 있긴 하지만 프로그래밍 자체에 대한 숙련도 증가로 인한 학습 속도 향상이 지대했습니다.  
즉, 여러분은 (취미로 여러 언어를 공부하는 경우를 제외하면) 여러 언어를 공부하는 데에 시간을 과투자할 필요가 없습니다.  
그렇다고 언어를 익히는 것이 중요하지 않다는 것은 아닙니다. 도구 자체의 사용법을 익히는 것 또한 필요합니다.  
개인적으로 주무기로 사용할 언어 두 개와, 보조 무기로 사용할 언어 하나 정도 익혀두는 것을 추천합니다.  
자신이 어떤 분야에서 일을 하게될지, 어떤 분야를 세부적으로 전공할지 미리 정할 수 있다면 그에 맞춰서 주무기를 구성하는게 베스트지만, 그렇지 않은 경우가 더 많을 것입니다.  
다음은 지극히 제 개인적인 성향에 따른 주언어 및 보조언어 구성 추천입니다: 주언어 / 보조언어 (참고로 Java와 Javascript는 전혀 다른 언어입니다.)  
* 나는 화려하고 눈에 보이는 것이 좋다 : Java and Javascript / Python
* 나는 복잡한 과정에 대해 논리적으로 접근하는 것이 좋다 : C++ and Java / Python
* 나는 요즘 유행하는 신기술에 관심이 간다 : Python / C++
* 나는 로봇이 좋다 : C and C++ / Python

다시 말하지만 위 추천은 지극히 개인적인 의견이며, 전혀 따라하지 않아도 좋습니다. (또한, 심심해서 이 글을 읽고 있는 시니어 개발자분들의 피드백도 매우 환영합니다.)  
오히려 자신이 필요하다고 생각되는 언어가 있다면 해당 언어를 공부하는 것이 더욱 좋습니다.  
자신의 비범함을 뽐내고 싶다면 Haskell을 공부할 수도 있고, 강력한 최신 언어를 공부하고 싶다면 Rust를 익힐 수도 있겠죠. (다만, 한국에서 일할 거면 웬만해서 Java는 공부해두도록 합시다.)  
그런데 위 추천에서 보다보면 Python이 하나씩 다 들어가 있습니다. Python은 굉장히 범용적으로 사용할 수 있으며 언어 자체가 굉장히 다양한 기능을 탑재하고 있어서 프로그램을 만들어내기 쉽습니다. 또한, 프로그래밍을 처음 공부하는 사람이 익히기도 쉬워서 입문용 언어로 정말 제격입니다.  
컴퓨터공학과 신입생이라면 학교 커리큘럼상 처음 배우는 언어가 있고, 비전공자분들 중 원하는 분야가 있다면 해당 분야에 적합한 언어가 있기에 해당 언어로 시작하면 되지만, 그렇지 않은 분이라면 Python으로 입문하는 것을 굉장히 추천합니다.

### Python

* [점프 투 파이썬](https://wikidocs.net/book/1)
* [Python Tutorial](https://docs.python.org/ko/3/tutorial/index.html)
* [전문가를 위한 파이썬](http://www.yes24.com/Product/Goods/30231768)

### C

* [C Programming : A Modern Approach](http://www.yes24.com/Product/Goods/573769)
* [The C Programming Language](http://www.yes24.com/Product/Goods/5928879)

### C++

* [C++ Primer](http://www.yes24.com/Product/Goods/6285665)
* [Programming : Principles and Practice Using C++](http://www.yes24.com/Product/Goods/23207535)
* [Effective C++](http://www.yes24.com/Product/Goods/17525589)
* [Effective Modern C++](http://www.yes24.com/Product/Goods/20288684)
* [The C++ Programming Language](http://www.yes24.com/Product/Goods/23441719)

### Java

* [Java의 정석](http://www.yes24.com/Product/Goods/24259565)
* [Effective Java](http://www.yes24.com/Product/Goods/65551284)

### Javascript

* [생활코딩! HTML+CSS+자바스크립트](http://www.yes24.com/Product/Goods/67883315)
* [인사이드 자바스크립트](http://www.yes24.com/Product/Goods/11781589)
* [자바스크립트는 왜 그 모양일까?](http://www.yes24.com/Product/Goods/90283410)
* [자바스크립트는 모든 곳에 존재한다](http://www.yes24.com/Product/Goods/97125368)

### C#

* [이것이 C#이다](http://www.yes24.com/Product/Goods/96674785)
* [C# 6.0 완벽 가이드](http://www.yes24.com/Product/Goods/33085047)
* [이펙티브 C#](http://www.yes24.com/Product/Goods/55864866)

### etc.

## Fundamental Technique

### Algorithm

#### Academic

* [Foundations of Algorithms](http://www.yes24.com/Product/Goods/11999564)
* [Introduction to Algorithms](http://www.yes24.com/Product/Goods/13776831)
* [The Art of Computer Programming](http://www.yes24.com/Product/Goods/13776831)
* [Project Euler](https://euler.synap.co.kr/)

#### Coding Interview (Coding Test)

* [파이썬 알고리즘 인터뷰](http://www.yes24.com/Product/Goods/91084402)
* [프로그래머스](https://programmers.co.kr/)
* [LeetCode](https://leetcode.com/)

#### Competition

* [알고리즘 문제 해결 전략 세트](http://www.yes24.com/Product/Goods/8006522)
* [백준 온라인 저지](https://www.acmicpc.net/)
* [CodeForces](https://codeforces.com/)
* [알고스팟](https://www.algospot.com/)

### Computer Architecture

### Operating System

### Network

### Database

## Projects
