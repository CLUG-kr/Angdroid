# 📢 (2주차) 스터디 일지

> #### 작성자 : 신요한
>
> #### 작성 날짜 : 2021.10.06
>
> #### 참여자 : 신요한

## ✅ 이번주 공부 내용 :  이벤트와 리스트뷰

### ▶️  테이블 레이아웃 만들기

- 뜻: 격자 모양으로 배치할 때 쓰는 레이아웃
-테이블 레이아웃에서 각각의 행은 <TableRow> 태그를 이용해 추가
-행 안에  몇 개의 뷰를 추가하는가에 따라 열의 개수가 결정됨
-<TableLayout .. android:stretchColumns="0,1,2">을 쓰면 원하는 열을 지정할 수 있고 총 3개의 열이 생성된다.
-실습:
### ▶️ 스크롤뷰 
-뜻: 스크롤 기능을 넣고 싶을 때 사용되는 뷰
-이미지뷰나 텍스트뷰등의 뷰를 스크롤뷰로 감싸주는 방식
 화면에 보이는 공간을 넘어갔을 때 자동으로 스크롤이 만들어짐
-스크롤 방향은 그 안에 Linearlayout의 orientation에 관계없이 항상 위아래 방향임 
-실습: 

### ▶️ 이벤트
-뜻: 화면에 터치하거나 단말의 방향을 돌리는 등 뷰에 어떠한 행위를 했을 때 동작되는 기능 ex_ onclicklister,onkeylistener
-대표적인 이벤트: 터치이벤트 , 키 이벤트, 제스처 이벤트, 포커스 , 화면 방향 변경
-실습: 터치이벤트
-trouble:detector 객체 생성이 안됌, selecter background에 넣으면 오류 발생

-실습: 

### ▶️ 토스트
-뜻: 잠깐 알림메시지 창이 뜨는 것과 같이 간단한 메시지를 보여주었다가 없어지는 뷰
-trouble: 스낵바 안됌, 
-실습: 알림대화상자 못함

### ▶️ 나인패치
-뜻: 이미지가 늘어나거나 줄어들 때 생기는 이미지 왜곡을 해결하는 방법을 정의한 것
-:이미지파일 이름에 .9를 붙여주면 자동으로 나인패치가 된다(?)
실습: 

### ▶️ 비트맵 버튼

-뜻: 나인패치 이미지를 적용하는 대표적인 경우가 버튼인데, 배경부분을 이미지로 지정한 버튼은 눌러도 이미지의 변화가 없다
이때 비트맵 이미지를 이용하여 버튼의 상태를 이벤트로 구분해 표시할 수 있다.
-:

### ▶️ 인플레이션
-뜻: XML 레이아웃 파일 안에 들어있는 뷰 태그들을 이용해 뷰 객체를 메모리에 만드는 과정
-:자바소스코드파일과 xml파일을 연결시켜 사용할 수 있게 하는 기능
-최상위화면은 setContentView()메소드로 레이아웃 인플레이션가능
-그렇지 않은 경우엔 직접 인플레이션을 해야 한다.
-실습: 직접 인플레이션
### ▶️ 선택위젯
-뜻: 여러개의 아이템이 관리가 되면서 그중을 선택하는 위젯
- 원본데이터->데이터 어댑터*->선택 위젯(껍데기역할)
#### ▶️ 리스트뷰
-전화번호부과 모양이 비슷하게 생겼다
-중요사항: 1)아이템을 위한 레이아웃 정의 2) 아이템을 위한 뷰 정의3) 어댑터 정의 4) 리스트뷰 정의
-실습:
          



#### ▶️ 스피너



#### ▶️ 그리드뷰





```

```

## 👊 Git (공부한 소스코드 공유)

| 작성자 |           주소            |
| :----: | :-----------------------: |
|  신요한  | https://github.com/hanyohan |
