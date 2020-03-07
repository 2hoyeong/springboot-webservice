스프링 부트와 AWS로 혼자 구현하는 웹 서비스
=
# 1. 책을 구매하게 된 계기
## 1.1 왜 스프링 부트 책을 구매했나?
학교를 다니면서 프로젝트를 진행할 땐 프레임워크를 쓸 여유도 굳이 그럴 이유도 없어서 사용하지 않았다. 프레임워크를 공부하기엔 시간이 부족했기 때문이다. 또한  JAVA, Python 같은 언어만 사용할 줄 알면 될 거라고 생각했다.  
그런데 실제 회사에서는 생산성도 좋고 유지보수도 좋은 프레임워크들을 안쓸이유가 없더라 ~~(생각이 짧았다.)~~ 그래서 학교를 졸업한 지금 넘쳐나는 시간에 공부할 건 프레임워크 밖에 없다고 생각했다. 서버 개발자를 꿈꾸는 내가 알아야할 프레임워크가 무엇이 있을까 생각해봤다.  

* Spring (JAVA)
* Laravel (PHP)
* Django (Python)

더 많이 있을 거라고 생각하지만 새로운 언어보단 할줄아는 언어 기반의 프레임워크를 공부하는 것이 좋을거라고 생각했고 3개만 간추렸다. 그 중에 나는 왜 Spring을 선택했을까?  
> 나는 언어 중에 자바를 가장 잘 알고있다고 생각했는데, Spring 코드를 보니 나는 우물안의 개구리였단 생각이 들었다. 여러 장점이 있었지만 어노테이션을 이용한 직관적인 코딩, Maven(책에서는 Gradle)을 이용한 쉬운 확장이 가장 크게  나에게 와닿았다.  

그래서 Spring을 가장 먼저 공부해 보고 싶다고 느꼈다. 그런데 나는 스프링 책이 아니라 스프링 부트책을 골랐다.  
왜? 이는 **1.2** 마지막에 같이 설명하겠다.

## 1.2 스프링 부트 책 중에서 이 책을 고른이유
나는 우아한 형제들 블로그를 [Java Serialize 게시글]("https://woowabros.github.io/experience/2017/10/17/java-serialize.html")을 통해 우연히 알게 되었다. 호기심에 다른 게시글들을 봤는데 우아한 형제들에서 일하는 개발자들이 서비스를 안정적으로 운영하기 위해 겪은 일들과 어떻게 개발해 나가야 하는지 적은 것들을 이해도 못하는 코드를 보면서 시간가는줄 모르고 읽었었다. 책의 저자가 우아한 형제들의 개발자라서 산건 아니다. ~~(사고나서 알았다.)~~ 코드 짜면서 사소한 실수가 많은 나로써 테스트 코드 작성은 여러모로 새로운 충격이었다. (이 repo의 commit 로그만 봐도 shell script 오타 수정만 여러번이다...)   
> 그래서 책의 표지에 쓰인 JUnit 테스트, 블로그를 보면서 배운 무중단 배포까지 책을 몇일 째 고르던 내가 보자마자 구매하게 만들었다.

구매하고 나서 깨달은건 책의 저자가 우아한 형제들의 개발자 였다는 것 뿐만아니라 내가 면접 준비하면서 보게된 [개발자 블로그]("https://jojoldu.tistory.com/")까지 책의 저자가 운영하고 있었다는 것, **스프링 책이 아닌 스프링 부트 책이였단 것이다..**

# 2. 책을 읽고 느낀점
    !! 개인적으로 책을 읽고 느낀 점이므로 지극히 주관적임

이 책은 스프링(부트)의 입문서가 아니다. 그렇다고 처음 공부하기에 나쁘진 않다고 생각하는데 ~~(내가 공부해서)~~ 게시판과 OAuth를 이용한 로그인기능을 구현하며 코드를 짤 수 있는 경험을 제공하고 그에 준한 설명을 해주기 때문이다. 그럼에도 불구하고 왜 입문서라고 생각하지 않느냐면 동작이 눈에 보이지 않기 때문이다. 기본적으로 스프링과 MVC패턴이 익숙하다면 코드를 보고 쉽게? 이해할 수 있지만 그렇지 않다면 머릿속에 쉽게 떠오르지는 않기 때문이다. 이에 대한 설명이 부족한 느낌이다. **그렇다고 이 책의 스프링 부트에 관한 내용이 부실하다는 건 아니다!**  
다른 스프링을 공부했다면 그 다음 책으로는 이 책을 구매하길 적극 권장하고 싶다. 단순 스프링 부트 뿐만 아니라 그 뒤에 나오는 AWS에 CI/CD 환경을 구축하고 Nginx를 이용하여 무중단 배포까지 하는 과정을 설명한 내용은 정가 22,000원(인터넷에선 2만원) 그 이상의 가치를 하고도 남는다.

> **한줄요약 : 이 책에 적힌 내용은 정가 22,000원 그 이상이다. 필요한 내용이라면 당장 구매해라!**