# 디자인 패턴
디자인 패턴 공부를 위한 페이지입니다.

공부하기 위해 사용한 정보들은 **Head First Design Patterns: 스토리가 있는 패턴 학습법<sup>(서환수 역 - 2005 초판)</sup>** 을 기준으로,  
위키백과, 위키피디아, 구글링을 통한 기타 페이지 등 **여러 출처를 바탕으로 최대한 오류를 범하지 않도록 작성**하였으나,

이 페이지를 작성하는 **저 또한 해당 학문을 공부하는 학생**입니다.  
**∴해당 페이지의 정보를 맹신하지 마시길 바랍니다.**

📝**현재 열씸히 공부중**📝


## 목차
- [상속과 구성](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%83%81%EC%86%8D%EA%B3%BC-%EA%B5%AC%EC%84%B1)
- SOLID 원칙<sup name="a1">[[1]](#f1)</sup>
  - [Single Responsiblity Principle (단일 책임 원칙)](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Single-Responsiblity-Principle-(%EB%8B%A8%EC%9D%BC-%EC%B1%85%EC%9E%84-%EC%9B%90%EC%B9%99))
  - [Open-Closed Principle (개방-패쇄 원칙)](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Open-Closed-Principle-(%EA%B0%9C%EB%B0%A9-%ED%8F%90%EC%87%84-%EC%9B%90%EC%B9%99))
  - [Liskov Substitution Principle (리스코프 치환 원칙)](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Liskov-substitution-principle-(%EB%A6%AC%EC%8A%A4%EC%BD%94%ED%94%84-%EC%B9%98%ED%99%98-%EC%9B%90%EC%B9%99))
  - [Interface Segregation Principle (인터페이스 분리 원칙)](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Interface-Segregation-Principle-(%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4-%EB%B6%84%EB%A6%AC-%EC%9B%90%EC%B9%99))
  - [Dependency Inversion Principle (의존 역전 원칙)](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Dependency-Inversion-Principle-(%EC%9D%98%EC%A1%B4-%EC%97%AD%EC%A0%84-%EC%9B%90%EC%B9%99))
    - [의존이란?](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Dependency-Inversion-Principle-(%EC%9D%98%EC%A1%B4-%EC%97%AD%EC%A0%84-%EC%9B%90%EC%B9%99)#f1)
    - [의존성 주입이란?](https://github.com/dhtpdud/DesignPatternStudy/wiki/SOLID:-Dependency-Inversion-Principle-(%EC%9D%98%EC%A1%B4-%EC%97%AD%EC%A0%84-%EC%9B%90%EC%B9%99)#f2)
- 생성 패턴
  - [팩토리 패턴 (Factory pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%ED%8C%A9%ED%86%A0%EB%A6%AC-%ED%8C%A8%ED%84%B4-(Factory-pattern))
    - [팩토리 메소드 패턴](https://github.com/dhtpdud/DesignPatternStudy/wiki/%ED%8C%A9%ED%86%A0%EB%A6%AC-%ED%8C%A8%ED%84%B4-(Factory-pattern)#팩토리-메소드-패턴-factory-method-pattern)
    - [추상 팩토리 패턴](https://github.com/dhtpdud/DesignPatternStudy/wiki/%ED%8C%A9%ED%86%A0%EB%A6%AC-%ED%8C%A8%ED%84%B4-(Factory-pattern)#추상-팩토리-패턴-abstract-factory-pattern)
    - [두 패턴의 차이점](https://github.com/dhtpdud/DesignPatternStudy/wiki/%ED%8C%A9%ED%86%A0%EB%A6%AC-%ED%8C%A8%ED%84%B4-(Factory-pattern)#두-패턴의-차이점)
  - [싱글턴 패턴 (Singleton pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%8B%B1%EA%B8%80%ED%84%B4-%ED%8C%A8%ED%84%B4-(Singleton-pattern))
    - [🛑SRP위반?](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%8B%B1%EA%B8%80%ED%84%B4-%ED%8C%A8%ED%84%B4-(Singleton-pattern)#srp%EC%9C%84%EB%B0%98)
- 구조 패턴
  - [데코레이터 패턴 (Decorator pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EB%8D%B0%EC%BD%94%EB%A0%88%EC%9D%B4%ED%84%B0-%ED%8C%A8%ED%84%B4-(Decorator-pattern))
  - 어댑터, 퍼사드 패턴 (Adapter, Facade pattern)
  - 프록시 패턴 (Proxy pattern)
  - 이터레이터, 컴포지트 패턴 (Iterator, Composite pattern)
- 동작 패턴
  - [옵저버 패턴 (Observer pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%98%B5%EC%A0%80%EB%B2%84-%ED%8C%A8%ED%84%B4-(Observer-pattern))
  - 템플릿 메소드 패턴 (Template pattern)
  - [커맨드 패턴 (Command pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%BB%A4%EB%A7%A8%EB%93%9C-%ED%8C%A8%ED%84%B4-(Command-pattern))
  - [스트래티지 패턴 (Strategy pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%8A%A4%ED%8A%B8%EB%9E%98%ED%8B%B0%EC%A7%80-%ED%8C%A8%ED%84%B4-(Strategy-pattern))
  - [스테이트 패턴 (State pattern)](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%8A%A4%ED%85%8C%EC%9D%B4%ED%8A%B8-%ED%8C%A8%ED%84%B4-(State-pattern))
    - [스트래티지 패턴과의 유사성](https://github.com/dhtpdud/DesignPatternStudy/wiki/%EC%8A%A4%ED%85%8C%EC%9D%B4%ED%8A%B8-%ED%8C%A8%ED%84%B4-(State-pattern)#%EC%8A%A4%ED%8A%B8%EB%9E%98%ED%8B%B0%EC%A7%80-%ED%8C%A8%ED%84%B4strategy-pattern%EA%B3%BC%EC%9D%98-%EC%9C%A0%EC%82%AC%EC%84%B1)

- 컴파운드 패턴 (Compound pattern)

***

### 각주
> <sup name="f1">[1]</sup> **객체 지향 프로그래밍 및 설계의 다섯 가지 기본 원칙.**<sup>[[↺]](#a1)</sup>  
프로그래머가 시간이 지나도 유지 보수와 확장이 쉬운 시스템을 만들고자 할 때 이 원칙들을 함께 적용할 수 있다.  
SOLID 원칙들은 소프트웨어 작업에서 프로그래머가 소스 코드가 읽기 쉽고 확장하기 쉽게 될 때까지 소프트웨어 소스 코드를 리팩터링하여 [코드 냄새](https://ko.wikipedia.org/wiki/%EC%BD%94%EB%93%9C_%EC%8A%A4%EB%A9%9C)를 제거하기 위해 적용할 수 있는 지침이다.<sup>출처: [위키백과](https://ko.wikipedia.org/wiki/SOLID_(%EA%B0%9D%EC%B2%B4_%EC%A7%80%ED%96%A5_%EC%84%A4%EA%B3%84))</sup>  
>
> **해당 원칙들은 항상 지켜야 하는 규칙이 아니라, 우리가 지향해야 할 바를 밝히고 있을 뿐입니다.**
디자인을 할 때 해당 원칙들을 염두해 둔다면, 원칙을 지키지 못하게 되더라도,불가피한 상황에서만 합리적인 이유를 바탕으로 그렇게 하게 될 것입니다.<sup>출처: Head First Design Patterns</sup>
