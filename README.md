# 2020_M4_Jibang :wink:
---
## Git & Github
---
### Git? - 깃이란 무엇인가
<img src="https://miro.medium.com/max/875/1*BCZkmZR1_YzDZy22Vn4uUw.png" width="400" height="170">

+ 파일에서 만든 모든 변경사항을 추적하는 시스템
+ 데스크탑에 저장하거나, 클라우드에 저장하거나
+ 팀원간의 공유 및 공동 작업에 용이
---
### Github? - 깃허브란 무엇인가
<img src="https://media.vlpt.us/images/ifyouseeksoomi/post/2ae4e377-1dc2-441c-8327-3f0a32959bfc/github.png" width="600" height="300">

+ 변경사항을 저장할 수 있는 클라우드 서비스
+ 협업개발플랫폼의 일종
  - 비트버킷(Bitbucket)
  - 요비(Yobi)
---
### Keyword! - 중요한 단어들
+ Repositories
  - 저장폴더
+ Commits
  - 파일 변경을 기록
+ Branches
  - 나무의 가지
+ Merge
  - 실험적인 작업을 하고 싶을 때, 중심 기둥이 되는 코드(master branches)에 하는 게 아니라 곁가지를 만들어서 작업하는 것
  - 적절하게 잘 완성되면 마스터 브랜치와 합친다.
---
### Internet Journey - 인터넷은 어떻게 동작하는가
  <img src="http://www.tcpschool.com/lectures/img_webbasic_10.png" width="400" height="300">
  
1. DNS를 통해 IP주소로 변환 = 사람이 이해할 수 있는 문자로 된 주소가 우편번호(IP주소)로 변환
2. IP라는 규칙에 따라 데이터를 패킷 형태로 나눔 = 편지지를 접어 봉투에 담음
3. 해당하는 웹서버가 있는 네트워크에 도달 : 받는 사람이 사는 지역의 우체국 지점에 도달함
4. 브로드캐스트를 통해 물리적 주소 이야기 : 어떤 우편물을 어디로 전달해야 하는지 정보 집계
5. 해당하는 랜카드가 있는 컴퓨터에 접근 : 받는 사람이 편지를 받음. 
6. 원하는 데이터를 다시 가져옴

#### 단어 설명
+ DNS(Domain Name System): 사람의 언어로 입력하면 컴퓨터의 언어로 바꿔주는 기능(ex - goole.com -> 172.217.25.238)
+ Internet Protocol(규약) Address: 인터넷에 연결되어 두 개의 디바이스가 있을 때, 한 쪽에서 다른 쪽으로 데이터를 전달하기 위해 사용하는 것
  - 표현하는 버전: IPV4 -> IPV6 (컴퓨터 수 증가로 주소가 부족해져서)
  - 받는이(웹브라우저)와 보내는이(웹서버)를 적는 규칙들
+ Packets: 요청하는 데이터를 규칙에 의해서 쪼개서 전달하는 것(편지지를 편지지에 담기 위해 크기를 줄이는 것과 유사)
+ TCP: 웹서버에 접근하기 위한 규칙
+ Port: 인터넷에서 영문이 아니라 개별 숫자를 사용하는 것
---
### 웹사이트 구성요소 3가지
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FxrmSd%2FbtqCAPnVCOj%2F5pleBWQ5k5G5otKCEooPCK%2Fimg.png" width="300" height="300">

+ HTML (Hyper Text Markup Language), CSS (Cascading Style Sheets), JS (Javascript)

<img src="https://html-css-js.com/images/og.jpg" width="370" height="200">

+ 세가지 프로그램이 담당하는 역할을 시각적으로 표현한 그림이다.

| 언어 | 역할 | 기능 |
| ------ | ----------- | -------------- |
| HTML   | 웹의 **구조**를 담당 | 제목, 이미지, 동영상, 문단, 표 |
| CSS | 웹의 **시각적인 표현**을 담당 | 색상, 레이아웃, 크기, 폰트 |
| JS    | 웹의 **동적 처리**를 담당 | 팝업창, 전화번호/이메일 체크 |

> 출처: https://junghn.tistory.com/entry/htmlcss-HTMLCSSJavascript-의-정의와-차이점 [코딩 시그널]
