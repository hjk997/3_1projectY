# 3_1projectY

![image](https://user-images.githubusercontent.com/56015030/95088099-7a4aaf80-075d-11eb-8420-d4c28ce5e696.png)
![youtubePlayerUML](https://user-images.githubusercontent.com/56015030/95088878-74090300-075e-11eb-8975-588320ade096.gif)

# youtube 영상 추천 프로그램 
사용자가 입력한 검색어와 8가지 키워드를 통해 youtube 영상을 추천해주는 프로그램입니다. 
간단한 게시판 기능 또한 함께 제공합니다. 

[시연 영상 보기](https://youtu.be/xRQ2ePxqJCs)

##개발 기간
2019. 04.02 ~ 2019.06.05

##사용 도구 
java, eclipse, google youtube api

##구분 
팀 프로젝트 

##담당 부분
* google youtube api를 사용해서 youtube 검색 결과를 가져오는 기능을 구현하였습니다.
* client 프로그램에서 유튜브 검색 / 검색결과 리스트 출력 / 리스트에서 영상 선택시 썸네일 출력 기능을 구현하였습니다.
* 일부 중복 코드를 제거하였습니다.
* 프로젝트 전체 모듈을 병합한 후 충돌로 생기는 오류를 제거하였습니다.
* 강의 과제로 디자인 패턴 5가지를 필수적으로 사용하는 것이 조건이었습니다. Proxy 패턴과 Strategy 패턴을 구현하였습니다. 

proxy 패턴 클래스 다이어그램
![proxy](https://user-images.githubusercontent.com/56015030/95089434-1aed9f00-075f-11eb-9dd1-e9d587619d0f.gif)

strategy 패턴 클래스 다이어그램 
![strategy](https://user-images.githubusercontent.com/56015030/95089502-2e990580-075f-11eb-9f93-ce7f0e2808e6.gif)

