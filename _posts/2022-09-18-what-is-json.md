# '<JSON>'의 정의

---

### JSON이란?

* JSON은 JavaScript Object Notation의 줄임말이다.
* JavaScript 객체 문법으로 구조화된 데이터를 표현하기 위한 문자기반의 표준 포맷
* 일반적으로 웹 애플리케이션에서 데이터를 전송할 때 사용

---

### JSON의 탄생 배경

JSON 이전에 XML이 존재했다. XML은  HTML과 비슷한 문자 기반의 마크업 언어이다. 어떤 것을 실행하는 것이 아닌 데이터를 표현하는 형식에 가까웠다. 하지만 XML에는 불편한 점들이 존재했다. 이런 XML의 불편한 점들을 개선한 것이 JSON이다.

* XML -> JSON이 되면서 개선된 점
  * JSON은 종료 태그를 사용하지 않는다.
  * JSON은 XML보다 구문이 짧다.
  * XML보다 JSON의 데이터가 더 빨리 읽고 쓸 수 있다.
  * JSON은 배열을 사용할 수 있다.
  * XML은 XML 파서로 파싱이 되지만, JSON은 자바스크립트 표준 함수인 eval()함수로 파싱 된다.(파서 없이 함수만 가지고 파싱이 가능)
  * XML문서는 XML DOM을 이용하여 해당 문서에 접근하지만 JSON은 문자열을 전송받은 후에 해당 문자여을 바로 파싱하여 처리 속도가 더 빠르다.

---

### JSON이 쓰이는 곳

JSON은 빠르다는 특징을 가지고 있는 만큼, 빠른 응답이 필요한 환경에서 자주 사용되고 있다. 대표적이 예로는 챗봇 서비스가 있다.

![https://m.blog.naver.com/data_flow/221693093131?view=img_3]

![https://m.blog.naver.com/data_flow/221693093131?view=img_4]

출처 : <https://m.blog.naver.com/data_flow/221693093131>

### 
