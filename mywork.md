# 이클립스 단축키
   1. 실행

      Ctrl + F11 : 바로 전에 실행했던 클래스 실행

      Al + Shift + X, J : ​Java 실행. (Run As > Java Application). Alt키와 Shift키와 X키를 동시에 눌렀다 뗀 다음 J키를 누른다. J키를 누를 때는 Alt키와 Shift키를 누르지 않는다. Alt + Shift + X를 누르면 상태바에 'Alt + Shift + X'가 눌렸음이 표시되고, 그 상태에서 조금 더 기다리면 워크벤치의 오른쪽 아랫부분에 팝업이 나타나 Alt + Shift + X 당므에 사용할 수 있는 키가 표시된다. 팝업에 있는 항목을 마우스나 화살표 키로 선택해도 되고, 그 상태에서 J키를 눌러도 된다.
   2. 소스 네비게이션

      Ctrl + 마우스커서(혹은 F3) : 자바소스에서 클래스나 메소드 혹은 멤버를 상세하게 검색하고자 할때
      Alt + ->, Alt + <- : 이후, 이전
      Ctrl + O : 해당 소스의 메소드 리스트를 확인하려 할때. 메소드나 필드 이동하기. Symbol List. 빠른 아웃라인.
      F4 : 클래스명을 block을 잡고 누르면 해당 클래스의 Hierarchy를 볼 수 있다.
   3. 문자열 찾기

      Ctrl + F : 기본적으로 찾기
      Ctrl + K : 찾고자 하는 문자열을 block을 잡은 후 키를 누른다.
      Ctrl + Shift + K : 역으로 찾고자 하는 문자열을 찾아감.
      Ctrl + J : Incremental Find. 이클립스 하단 상태 표시줄에 Incremental Find(증분 찾기)라고 표시되어 한 글자씩 누를 때마다 코드 내의 일치하는 문자열로 이동. 다시 Ctrl + J를 누르면 그 문자열과 일치하는 부분을 위/아래 방향키로 탐색이 가능하다.

      ​입력하면서 찾을 수 있음.
      Ctrl + Shift + J : 입력하면서 거꾸로 찾아갈 수 있음.

      ​Ctrl + Shift + R : Open Resource

      Ctrl + Shift + T : Open Type. 클래스 찾기(Goto Class).​ 유형 열기.
   4. 소스 편집

      Ctrl + Space : 입력 보조장치(Content Assistance) 강제 호출 => 입력하는 도중엔 언제라도 강제 호출 가능하다.
      F2 : 컴파일 에러의 빨간줄에 커서를 갖져다가 이 키를 누르면 에러의 원인에 대한 힌트를 제공한다.
      Ctrl + L : 원하는 소스 라인으로 이동
                  로컬 히스토리 기능을 이용하면 이전에 편집했던 내용으로 변환이 가능하다.
      Ctrl + Shift + Space : 메소드의 가로안에 커서를 놓고 이 키를 누르면 파라미터 타입 힌트를 볼 수 있다.
      Ctrl + D : 한줄 삭제.
      Ctrl + W : 파일 닫기.
      Ctrl + I : 들여쓰기 자동 수정. (3.0 NEW)
      Ctrl + Shift + / : Add Block Comment. 블록 주석(/*..*/) 추가.(3.0 NEW)
      Ctrl + /         : 여러줄이 한꺼번에 주석(//)처리됨. 주석 해제하려면 /을 한번 더 누르면 됨.
      Ctrl + Shift + \ : Remove Block Comment. 블록 주석 제거.

      Ctrl + Alt + Down : 한줄 복사후 아래에 복사 넣기. 커서가 위치한 라인을 복사해서 밑줄에 생성해 준다.

                                Copy & Paste 대체하는 단축키. 
      Alt + 방향키(UP↑/DOWN↓) : 줄바꿈. 해당 라인을 위(아래)줄과 바꾸기
      Alt + Shift + 방향키 : 블록 선택하기.

      Alt + Shift + Up : Escalating Selection. 블록 설정. 소스 코드를 블록 단위로 설정한다. 엔클로징 요소 선택.

              커서를 소스에 위치하고 단축키를 누르면, 커서가 위치한 코드 요소보다 문법 구조상 한 단계 높은 범위를 선택한다.(블록 잡기)​

              키를 반복 호출하면 선택 범위가 넓어진다.​

      Alt + ​Shift + Down : 블록 해제. 소스 코드를 블록 단위로 해제한다.

      Alt + Shift + J : 주석 생성. 해당 메서드/클래스에 대한 주석을 템플릿으로 생성한다.
      Ctrl + Shift + Space : method의 parameter 목록 보기.
      Ctrl + Shift + O : 자동으로 import 하기.
      Ctrl + Shift + F4 : 열린 파일 모두 닫기.
      Ctrl + M : 전체화면 토글.
      Ctrl + Alt + 방향키(UP/DOWN) : 한줄(블럭) 복사.
      Ctrl + , (혹은 .) : 다음 annotation(에러, 워닝, 북마크 가능)으로 점프.
      Ctrl + 1 : 퀵 픽스.
      F3 : 메소드 정의부로 이동.

      Ctrl + E : Recently edited files / Files open. 빠른 전환 편집기.​ 열린 버퍼 목록을 보여줌.
      Ctrl + T : Hierarchy 팝업창 띄우기.(인터페이스 구현 클래스간 이동시 편리)

      Ctrl + Shift + ​F : 코드 포맷팅. 코드 내용을 문법 템플릿에 맞게 포맷팅(들여쓰기) 해준다.

      Ctrl + Shift + X : 대문자로 변환.

      Ctrl + Shift + Y : 소문자로 변환.​​
   5. 에디터 변환

      Ctrl + F6 : ULTRAEDIT나 EDITPLUS의 CTRL+TAB과 같은 기능.

                    작업중인 여러 파일의 목록이 열리고 F6키를 누르면 아래로 커서가 움직인다.
      Ctrl + Shift + F6 : 작업중인 여러 파일의 목록이 open되고 F6키를 누르면 위로 커서가 움직인다.
      Ctrl + F7 : Views간 전환.
      Ctrl + F8 : Perspectives간 전환.
      F12 : 에디터 창으로 포커스 이동. (Debugging등 자동적으로 포커스가 이동됐을 경우 편리)
   6. 템플릿 사용

      sysout 입력한 후 Ctrl + Space 하면 System.out.println(); 으로 바뀐다.
      try 입력한 후 Ctrl + Space 하면 try-catch 문이 완성된다.
      for 입력한 후 Ctrl + Space 하면 여러가지 for 문을 완성할 수 있다.
      템플릿을 수정하거나 추가하려면 [Preferences > Java > Editor > Templates] 에서 할 수 있다.
   7. method 쉽게 생성하기

      클래스의 멤버를 일단 먼저 생성한다.
      override 메소드를 구현하려면 [Source > 메소드대체/구현]에서 해당 method를 체크한다.
      기타 클래스의 멤버가 클래스의 오브젝트라면 [Source > 위임메소드 생성]에서 method를 선택한다.
   8. organize import

      자바파일을 여러개 선택한 후 [Source > 가져오기 체계화] 해주면 모두 적용된다.
   9. 소스 코드 형식 및 공통 주석 설정

      환경설정 -> 자바 -> 코드 스타일 -> 코드 포멧터 -> 가져오기 -> 프로파일.xml 을 불러다가 쓰면 된다.
      또한 다수의 자바파일에 프로파일을 적용하려면 패키지 탐색기에서 패키지를 선택한 후 소스 -> 형식화를 선택하면 된다.
      환경설정 -> 자바 -> 코드 스타일 -> 코드 템플리트 -> 가져오기 -> 템플리트.xml 을 불러다가 쓰면 된다.

   10. 디버깅

      F11 : 디버깅 시작

      F8 : 디버깅 계속

      F6 : 디버깅 한줄씩 실행 (Step Over)

      F5 : 디버깅 한줄씩 실행 함수 내부로 들어감 (Step Into)

      Ctrl + Shift + B : 현재 커서 라인에 Break Point 설정.

   11. 기타
      Alt + Shift + L : Introduce variable. 로컬 변수 추출.​ 기술적으로는 리팩토링 기능.
      Ctrl + Shift + PgUp : 커서 이동 없이 스크롤 위로 이동.
      Ctrl + Shift + PgDn : 커서 이동 없이 스크롤 아래로 이동.​

