# week08

## 팀 전체 진행상황

    중간고사 기간이어서 대부분의 팀원이 많은 진행을 하지 못함. 원래 있던 기능에서 하나의 기능을 추가하거나, 오류를 해결함.

### Feedback

    박승준 - (학교/두정역/터미널)의 버스 정보 담당
              데이터 API를 연동하여 정류소명 입력시 정류장 관련 id, 버스 번호 입력시 버스 id 가져오는 기능을 추가함.
              정류소ID와 노선번호를 기준으로하여 실시간 도착정보인 남은 도착시간, 남은 정류장 수를 알 수 있도록 하는 코드 작성하고 있음.
    
    김다혜 - 셔틀 버스 정보 및 택시 모집 게시글 담당
             택시 출발 장소를 Google API 지도를 통해서 설정하려고 했으나, 연동이 잘 되지 않아서 카카오맵 API를 이용하기로 함.
             택시 모집 게시글 board 레이아웃과 모집 게시글 작성 레이아웃을 설계함.
    
    마혜준 - 회원가입/ 로그인 담당
             Register 레이아웃의 위젯이 많아 한 레이아웃에 담지 못하는 오류가 있었음.
             ScrollView에 RelativeLayout을 추가하여 다양한 위젯을 한 레이아웃에 담을 수 있도록 설계함.
             다음주까지 문자메시지 발송하여 인증번호를 받는 과정을 구현할 예정임.
    
    박윤빈 - 시간표 담당
             Fragment를 사용하여 레이아웃을 설계하였는데, 이 과정에서 버튼을 누르면 다른 레이아웃으로 이동하는 부분이 오류가 남.
             그 이유는 Fragment 안에 Onclick 함수를 정의할 수 없기 때문인데 OnClick 함수를 Override해서 정의하여 오류를 해결함.
    
    심우정 - 게시판/ 댓글 담당
             게시글을 쓰면 fireBase를 통해 실시간으로 DB를 저장하고 불러오는 기능을 추가함.
             게시글 board 목록이 역순으로 올라오도록 함. (가장 최근의 것이 제일 위쪽에 올라오도록 함.)
             다음주까지 게시글 업로드한 시간도 함께 뜨도록 기능을 추가할 예정.
    
    양하은 - 메인화면/ 채팅/ 졸업학점 담당
             메인화면에 navigation menu 기능을 추가하여 앱 내의 기능 list가 뜨도록 애니메이션을 구현함.
             메인화면에 학교 홈페이지로 이동하는 아이콘을 추가하여 해당하는 URL로 이동하는 기능을 추가할 예정임.
            

