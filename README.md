# Spring_DI
<br>
<ul>

  <li>Spring Framework란?</li><br>
  
  <ul>
    <li>엔터프라이즈 급 어플리케이션을 구축할 수 있는 가벼운 솔루션입니다.</li><br>
    <li>원하는 부분만 가져다 사용할 수 있도록 모듈화가 잘 되어 있습니다.</li><br>
    <li>IoC 컨테이너입니다.</li><br>
    <li>선언적으로 트랜잭션을 관리할 수 있습니다.</li><br>
    <li>완전한 기능을 갖춘 MVC Framework를 제공합니다.</li><br>
    <li>AOP를 지원합니다.</li><br>
  </ul>
 
  <br>
  <li>컨테이너(Container)란?</li><br>
  
  <ul>
    <li>컨테이너는 인스턴스의 생명주기를 관리한다.</li><br>
    <li>생성된 인스턴스들에게 추가적인 기능을 제공합니다.</li><br>
  </ul>
 
  <br>
  <li>IoC란?</li><br>
  
  <ul>
    <li>IoC란 Inversion of Control의 약어입니다.</li><br>
    <li>개발자는 프로그램의 흐름을 제어하는 코드를 작성합니다.<br><br> 그런데, 이 흐름의 제어를 개발자가 하는 것이 아니라, <strong>다른 프로그램이 그 흐름을 제어하는 것을 IoC라고 말합니다.</strong></li><br>
  </ul>
  
  <br>
  <li>DI란?</li><br>
  
  <ul>
    <li>DI는 Dependency Injection의 약자로, 의존성 주입이라는 뜻을 가지고 있습니다.</li><br>
    <li>DI는 클래스 사이의 의존 관계를 빈(Bean)설정 정보를 바탕으로 컨테이너가 자동으로 연결해 주는 것을 말합니다.</li><br>
  </ul>
  
  <br>
  <li>Spring에서 제공하는 IoC/DI 컨테이너</li><br>
  
  <ul>
    <li>BeanFactory<br><br>
    IoC/DI에 대한 기본 기능을 가지고 있습니다.</li><br>
    <li>ApplicationContext<br><br>
    BeanFactory의 모든 기능을 포함하며, 일반적으로 BeanFactory보다 추천됩니다.<br><br>
    트랜잭션 처리, AOP등에 대한 처리를 할 수 있습니다.<br><br>
    BeanPostProcessor, BeanFactoryPostProcessor등을 자동으로 등록하고, 국제화 처리, 어플리케이션 이벤트 등을 처리할 수 있습니다.
    </li><br>
  </ul>
 
</ul>
