# week08

## 오늘 한 일

    AVD 통일 - Pixel 2, 파일 이름 정리: main에서 연결하기 위함

### Feedback

    박승준 - (학교/두정역/터미널)의 버스 정보 담당
              도착정보 API 연동 성공함. 그러나 버스 정보, 노선 정보, 정류장 정보까지 모두 다 하기엔 무리일 것 같아 
              각 위치의 도착 정보를 불러오는 것을 우선으로 하여 개발을 이어가기로 함. 
    
    김다혜 - 셔틀 버스 정보 담당
             지난 시간 한 각 출발지에서의 셔틀 버스 정보를 보여주는 것에 이어 그 시간표에 맞게 실시간으로 몇분이 남았는지를 보여주는 것을 개발함.
             UI를 더 꾸미고 조금 더 보완 후에 택시 부분 개발을 이어가기로 함.
    
    마혜준 - 회원가입/ 로그인 담당
             지난 주에 AVD 오류로 보여주지 못한 부분을 해결하여 보여줌.
             Firebase 연동으로 User 정보를 관리하는 부분에 대해 개발을 이어가기로 함.
    
    박윤빈 - 시간표 담당
             시간표와 강의 목록 버튼을 생성하여 강의 목록에서 자신이 추가할 강의를 찾아 볼 수 있으며 그 강의를 추가하면 시간표에서 자신이 짠 시간표를 확인할 수 있음.
             시간표 부분 layout의 보완이 필요하며 이것을 보완한 후 더 효율적으로 활용할 수 있도록 연구하여 개발을 이어가기로 함.
    
    심우정 - 게시판/ 댓글 담당
             지난 시간에 해오기로 한 firebase 연동을 성공하였으며 게시물을 작성하였을 때 firebase에서 실시간으로 DB가 업데이트 되는 것을 확인 할 수 있음. 
             연동한 것을 토대로 작성한 게시물의 DB를 불러와서 목록에 대해 개발을 이어가기로 함.
    
    양하은 - 메인화면/ 채팅/ 졸업학점 담당
             firebase 연동을 성공하여 User의 id/학번/이름을 저장하고 불러와 recyclerView를 만들어옴.
             저장된 user 정보를 이용하여 채팅을 하는 부분에 대해 개발을 이어가기로 함.
             오늘 팀원들의 xml, java 파일 명을 정리하여 메인화면에서 각자 화면으로 넘어갈 수 있도록 해오기로 함.
             
### 파일 이름 정리

**박승준**

    -JAVA
    smc_bus_informationActivity.java // 버스정보조회 기능
    -Layout
    activity_main.xml // 버스정보조회 레이아웃

**김다혜**

    - JAVA
    SuttleBusActivity.class //셔틀버스 관련 기능
    - Layout.xml
    activity_main//셔틀버스 레이아웃

**마혜준**

    -JAVA
    LoginActivity.class //로그인 클래스 + 파이어베이스 DB연동(가져오기)
    RegisterActivity.class //회원가입 클래스 + 파이어베이스 DB연동(보내기)

    - Layout.xml
    login.xml //로그인 레이아웃
    register.xml //회원가입 레이아웃
    add_friends //친구추가 레이아웃
    
**박윤빈**

    -JAVA
    MainActivity.class
    CourseFragment.class // 강의 목록 DB
    ScheduleFragment.class // 시간표 클래스

    - Layout.xml
    activity_main.xml // 강의 목록, 시간표 버튼 누르면 넘어가는 화면
    fragment_course.xml // 강의 선택 화면 레이아웃
    fragment_schedule.xml // 시간표 테이블 레이아웃

**심우정**

    -JAVA
    BoardInfo.class
    BoardActivity.class // 글 목록 클래스 + 파이어베이스 DB연동 (가져오기)
    MyAdapter.class // 리사이클러뷰 뷰홀더 어댑터
    WriteActivity_b.class // 글 작성 클래스 + 파이어베이스 DB연동 (보내기)
    WriteActivity_c.class // 댓글 파이어베이스 DB 연동 (보내기+받아오기)

    - Layout.xml
    activity_main.xml // 글목록(리사이클러뷰 이용) 레이아웃
    activity_write.xml // 글작성 레이아웃
    item.xml // 글목록 리사이클러뷰에 넣을 카드뷰 레이아웃
    activity_comment.xml // 댓글 작성+목록 레이아웃
    
**양하은**
   
    - JAVA
    CustomAdapter.class // recyclerView holer
    MainActivity.class // 파이어베이스 DB 연동
    User.class // 유저 정보 
    
    - Layout.xml
    activity_main.xml // list 레이아웃 (채팅)
    list_item.xml // recyclerView 레이아웃
    activity_drawer.xml // 메인화면 drawer 레이아웃
    activity_main.xml // 메인 화면 구성 (메인)
