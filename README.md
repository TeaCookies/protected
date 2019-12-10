# protected : 보호할개
유기견 입·분양사이트입니다.




# 사용기술
*Front-End : HTML5, CSS3, JS6, jQuery, Json, Ajax, Bootstrap

*Back-End : Apache, java, Servlet, MyBatis, spring

*Open API : FullCalendar, Google Vision API, Google Map API, Google Geocoding API, Sweet Alert, CKEditor 4

*Tool & DB : Oracle 11g, sqlDeveloper, starUML, OvenApp, eclipse, Git




# 주요기능설명

![목록1](https://user-images.githubusercontent.com/50124719/70513419-eb88f880-1b74-11ea-825f-57729a40f4fb.png)
![목록2](https://user-images.githubusercontent.com/50124719/70513420-eb88f880-1b74-11ea-9b76-fd8edb58cab4.png)

분양게시판입니다. 무한스크롤로 썸네일 리스트를 구현하였습니다. 지역, 제목, 내용, 견종으로 검색 가능하며 분양글 등록은 인증회원만 가능합니다.  분양이 완료된 글은 완료표시가 출력됩니다.


![검색결과](https://user-images.githubusercontent.com/50124719/70514118-4ff88780-1b76-11ea-9dc8-f9b47a3fb836.png)

검색결과가 없을시 나타나는 화면입니다.

![분양등록1](https://user-images.githubusercontent.com/50124719/70514291-b5e50f00-1b76-11ea-8bdb-5ca38f7cb157.png)

![비전](https://user-images.githubusercontent.com/50124719/70514847-b29e5300-1b77-11ea-8a27-9e487d6709e5.gif)

분양글 등록페이지입니다. 사진 등록 시 Google Vision API를 사용하여 견종과 크기를 출력합니다.

![분양등록2 ](https://user-images.githubusercontent.com/50124719/70515164-39ebc680-1b78-11ea-861d-6b217142cc54.png)

Google Map API, Geocoding API를 이용해 분양가능지역, 발견 위치에 마커와 팝업창, 간략 주소를 출력합니다.


![분양조회](https://user-images.githubusercontent.com/50124719/70516129-c945a980-1b79-11ea-8fe0-629025964da5.png)

분양글 조회페이지입니다. 신고, 관심목록 등록·해제, 입양신청, 쪽지 보내기가 가능합니다.

![입양신청](https://user-images.githubusercontent.com/50124719/70515781-3e64af00-1b79-11ea-9dd7-1aeb67a87e71.png)
![신청자확인](https://user-images.githubusercontent.com/50124719/70515783-3e64af00-1b79-11ea-8163-11637cf94a9a.png)

인증회원일 경우 입양신청 가능하며, 입양 신청 후에는 조회, 수정, 삭제가 불가능하기 때문에 신청 전 다시 modal을 통해 확인합니다.

![작성자확인](https://user-images.githubusercontent.com/50124719/70515780-3dcc1880-1b79-11ea-84a3-407a53c93720.png)

분양글 등록자는 신청서를 확인할 수 있습니다.


![실종](https://user-images.githubusercontent.com/50124719/70516126-c8ad1300-1b79-11ea-9502-52259771845c.png)

실종게시판은 FullCalendar를 이용하여 캘린더 형식으로 구현하였습니다.

![실종조회](https://user-images.githubusercontent.com/50124719/70516127-c8ad1300-1b79-11ea-8ba7-37734f3c8752.png)
 
 각 장소를 클릭하면 실종글을 조회할 수 있습니다.
 
![실종등록](https://user-images.githubusercontent.com/50124719/70516128-c8ad1300-1b79-11ea-9313-d20f5d808e7f.png)

실종글 등록 화면입니다. 분양글 등록과 마찬가지로 Google Vision API를 사용하여 견종과 크기를 출력하며 Google Map API, Geocoding API를 이용해 발견 지역에 마커와 팝업창, 간략 주소를 출력합니다.
