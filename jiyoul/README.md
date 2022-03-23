※ 1일차 ※

TCP :
- 연결지향 - TCP 3 way handshake (가상 연결)
  -> 1. 상대에게 접속 요청을 보냄.
  -> 2. 요청 수락 및 접속 요청을 나에게 보냄.
  -> 3. 요청 수락 및 데이터 전송가능.
- 데이터 전달 보증
  -> 데이터 전송하면 데이터 잘 받았다고 결과를 줌.
- 순서보장
  -> 패킷1, 패킷3, 패킷2 이렇게 들어올 경우 패킷2부터 다시 보내라고 함.

UDP :
- 하얀 도화지와 같다(기능이 거의 없음)
- TCP는 이미 기반으로 쓰고 있기 때문에 개인적으로 최적화 등 쓰고 바꿔 쓰고 싶을때 사용한다.

PORT
TCP/IP 패킷내에 출발지IP와 PORT가 있고 해당 정보를 꺼내서 찾는다.
아파트의 몇호 처럼 한IP가 아파트, 한 PC가 한 호라고 생각하면 된다.

DNS
DNS서버에 도메인을 돈주고 사면 IP대신 도메인 명으로 사용할 수 있다.


URI(Uniform Resource Identifier)
Uniform : 리소스를 식별하는 통일된 방식
Resource : 자원, URI로 식별할 수 있는 모든것(제한 없음)
- 실시간 교통정보라던가 구분할 수 있는 모든 정보.
  Identifier : 다른 항목과 구분하는데 필요한 정보
- 주문번호로 구분한다던가 하면 주문번호가 Identifier가 될 수 있음.

- URI 라는 가장 큰 개념이 있다.
- URI는 URL(로테이터 = locator), URN(이름 = name) 또는 둘다로 분류될 수 있다.

URL(Uniform Resourcec Locator)
- 리소스가 있는 위치를 지정한다.
- URL은 변할 수 있다.
  URN(Uninform Resource Name)
- 리소스에 이름을 부여한다.
- URN은 변하지 않는다.
- URN 이름만으로 실제 리소스를 찾는 방법이 보편화 되있지 않다.

http는 80포트, https는 443포트를 주로 사용한다.

![저장](https://user-images.githubusercontent.com/54700818/159712523-df3f42ea-dc87-4d6d-9f7f-6f7400bbb599.PNG)
