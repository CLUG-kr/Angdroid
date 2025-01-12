# 📢 (n주차) 스터디 일지

> #### 작성자 : 김성윤
>
> #### 작성 날짜 : 2021.10.20
>
> #### 참여자 : 신요한, 이지현

## ✅ 이번주 공부 내용 : 화면 여러 개 만들기

### ▶️ 화면 전환
       -어플리케이션 : 액티비티(화면), 서비스(기능), 브로드캐스트 수신자(외부데이터 처리), 내용 제공자(파일 내용 변환 및 제공)
       -방법 
        1) app(최상위 폴더) -> new -> Activity -> Empty Activity (새로운 액티비티 생성 -> manifests/AndroidManifest.xml파일에서 생성 확인)
        2) 위젯(버튼 등)과 Intent 객체를 생성하고 OnClick 메소드에서 연결하고자 하는 액티비티와 연결
        3) 요청코드와 함께 startActivityForResult 명령어로 액티비티를 실행 -> 화면 전환 
### ▶️ 인텐트
       -인텐트란?
        액티비티, 서비스, 브로드캐스트 수신자 등이 서로 간의 데이터 등을 교환할 때, 시스템 내에서는 '인텐트'라는 포맷의 형태로 교환이 진행된다.
       -인텐트의 대표적 속성
        1) 범주(Category) : 액션이 실행되는데 필요한 추가적인 정보를 제공
        2) 타입(Type) : 인텐트에 들어가는 데이터의 MIME 타입을 명시적으로 지정
        3) 컴포넌트(Component) : 인텐트에 사용될 컴포넌트 클래스 이름을 명시적으로 지정
        4) (중요)부가 데이터(Extra) : Bundle 객체를 통해 인텐트 안에 더 많은 정보를 넣어 전달 가능
### ▶️ 액티비티 수명(생명)주기
       -액티비티 상태가 변화하면서 cycle을 만듦
       - 액티비티 상태
         1) 실행 : 액티비티가 보이고 있음(스택 최상위)
         2) 일시 중지 : 사용자에게 보이고 있지만 포커스를 받지 못하는 상태 ex) 대화 상자
         3) 중지 : 다른 액티비티에 가려서 아예 보이지 않는 상태
       
### ▶️ 서비스
     - "화면"이 없는 상태에서 "백그라운드"로 실행 -> xml파일이 따로 없고, java파일만 있음(기능)
     - 서비스는 프로세스가 종료되어도 시스템에서 자동으로 재시작
     - 서비스 만드는 방법: app -> new -> service -> service
     
### ▶️ 브로드캐스트 수신자
    - 어플이 글로벌 이벤트를 받아서 처리할 때 데이터를 받아서 어플에서 사용할 수 있도록 처리
    - 수신자를 manifest파일에 등록하면 디폴트로 작동 가능
    - 서비스와 같이 ui(화면)가 없음
    - 컨텍스트의 클래스의 registerReceiver 메소드를 이용하면 런타임 시에도 수신자 등록 가능


## 👊 Git (공부한 소스코드 공유)

| 작성자 |           주소            |
| :----: | :-----------------------: |
|  예원  | https://github.com/yaeoni |
