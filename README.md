# 될 때까지 안드로이드

<img src="https://raw.githubusercontent.com/junsuk5/android-first-book/master/resources/book_cover.png" width="240">

* [Yes24](http://www.yes24.com/24/goods/59298937?scode=032&OzSrank=1)
* [알라딘](http://www.aladin.co.kr/shop/wproduct.aspx?ItemId=137817656)
* [교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791186710289&orderClick=LAG&Kc=)
* [반디앤루니스](http://www.bandinlunis.com/front/product/detailProduct.do?prodId=4158780)
* [인터파크](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=281409749&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001)

## 예제 코드 실행 방법
하나의 프로젝트에 예제가 각각의 모듈로 되어있습니다. 안드로이드 스튜디오에서 프로젝트를 Open하고 실행하고 싶은 모듈을 선택하여 실행합니다.

## 예제 라이브 코딩 및 A/S
* [유튜브](https://www.youtube.com/playlist?list=PLxTmPHxRH3VWTd-8KB67Itegihkl4SVKe)
* [페이스북](https://www.facebook.com/untilandroid)

## 33장 미세먼지 앱 관련 중요 변경사항

책 출간 이후에 서비스 제공처가 변경되어 API요청주소는 http://apis.skplanetx.com/ 에서 http://api.weatherplanet.co.kr/ 로 변경되었습니다.
앱키는 6b200e091d1a4d7e83fb9b4732809b33를 사용합니다. (일일 500회 요청 제한)


## 오탈자 및 오류, 변경사항

* 오류 페이지 관련 공지
  - 책 초기 인쇄분에 인쇄 오류가 있습니다. 24~29쪽이고 출판사에서 해당 부분 PDF를 제공하며 문제가 있는 책은 교환해 드리니 링크를 참고해 주세요.
  - http://www.rubypaper.co.kr/notice/70

* 76쪽 스크린샷 수정
  - EditText가 가로로 꽉 차는 스크린샷이어야 함.
  
  
* 107쪽 실행결과 이미지 밑에 "숫자만 입력하는 소프트 키보드"라고 주제 외의 말이 적혀있습니다.
  - 삭제


* 120쪽 닥 -> 바닥
  - 텍스트뷰의 영역에서 '바'닥에 중력이 작용하는 것이지요.
  
  
* 183쪽 소스 두 번째 액티비티의 paretActivityName 수정
  - parentActivityName=".ChildActivity" -> parentActivityName=".parentActivity"


* 189쪽 하단 단락에 Select에 S 누락
  - elect Methods to ... -> Select Methods to
 
 
* 233쪽 하단 소스에 오타
  - mWeatherImagaMap -> mWeatherImageMap 으로 수정
  
 
* 266쪽 12.3.3. 제목
  - 깅제 종료 및 실행 => 강제 종료 및 실행
  

* 282쪽 액티비티에서 프래그먼트에 접근하는 예 코드에서
  - getFragmentManager() => getSupportFragmentManager() 로 수정
  
* 293쪽 // 종료처리 코드 누락
  - getActivity().finish();
  
* 310쪽 상단 스크린샷 패키지명이 다른게 들어가 있음

* 355쪽 중간에 오타
  - BroadcastReciever => BroadcastReceiver

* 369쪽 상단 소스 제목
  - [ContentResolver를 통해 데이터를 얻는 예]
  
* 379쪽 하단 path -> uri 로 수정
  - imageView.setImageURI(Uri.parse(uri));
  
* 537쪽 상단 문단
  - getBraodCast() => getBroadcast() 로 수정

 
* 554쪽 Google Play services와 연결하기 부분 삭제 
  - 과거에는 위치정보를 얻기 위해 GoogleApiClient가 필요했었는데 최근에는 FusedLocationProvider를 사용하게 되면서 필요없게 되었기 때문에 해당 절은 필요 없는 부분입니다. 관련된 코드 또한 작성하지 않아도 됩니다.
  
* 738쪽 3번째 줄 에제 -> 예제


* 774쪽 하단 표 '미세먼지 API 요청 기본 정보'의 Resource URI 수정 
  - http://api.weatherplanet.co.kr/~ 를 http://apis.skplanetx.com/~ 로 수정
  
  
* 776쪽 스크린샷에 API주소 수정
  - api.weatherplanet.co.kr 을 apis.skplanetx.com 으로 수정
  
  
* 794쪽 하단의 소스 경로 수정
  - finedust/FineDustFragment.java 를 MainActivity.java 로 수정
  
  
* 806쪽 상단 소스의 조건식 수정
  - mTabLayout.getSelectedTabPosition() - 1 < 0 을 mTabLayout.getSelectedTabPosition() == 0 으로 수정

