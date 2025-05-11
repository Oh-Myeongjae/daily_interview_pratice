HTTP 동작 순서 : TCP → HTTP

HTTPS 동작 순서 : TCP → SSL → HTTP

SSL(Secure Socket Layer)을 쓰냐 안쓰냐의 차이다. SSL 프로토콜은 정보를 암호화시키고 이때 공개키와 개인키 두가지를 이용한다.

HTTPS는 인터넷 상에서 정보를 암호화하기 위해 SSL 프로토콜을 이용해 데이터를 전송하고 있다는 것을 말한다. 즉, 문서 전송시 암호화 처리 유무에 따라 HTTP와 HTTPS로 나누어지는 것

모든 사이트가 HTTPS로 하지 않는 이유는, 암호화 과정으로 인한 속도 저하가 발생하기 때문이다.