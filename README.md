# Hi! School (고등학교 입시를 위한 선후배 매칭 서비스)
|<img src="https://user-images.githubusercontent.com/56965398/104407081-2c3b1880-55a4-11eb-8df1-60d831e22af2.png"  width="100%">|<img src="https://user-images.githubusercontent.com/56965398/104407113-3fe67f00-55a4-11eb-9587-2681240126a1.png"  width="100%">|
|---|---|

------------

## [👩‍👨‍팀원]
- 양준혁 : PM(팀장), 안드로이드 앱 개발, ppt제작, 디자인
- 이문영 : 안드로이드 앱 개발
- 곽준환 : 로고 디자인
- 양세연 : 안드로이드 앱 개발
- 조현지 : 안드로이드 앱 개발
- 이규락 : 서버 개발
- 김영재 : 채팅 서버 개발   

------------

## [👨‍💻개발 언어/프레임워크]   

|Kotlin|<img src="https://user-images.githubusercontent.com/56965398/104442284-30812900-55d8-11eb-9a62-6e0a3662ee78.png"  width="40%">|
|---|---|
Python|<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104442484-776f1e80-55d8-11eb-9235-60caee092883.png"  width="40%"><p/>|
Django|<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104448292-4eeb2280-55e0-11eb-849c-0a54be09044b.png"  width="30%"><p/>||
NodeJs|<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104442609-a7b6bd00-55d8-11eb-9789-9dbca9e8d3ae.png"  width="30%"><p/>|| 

------------    

## [🛠개발/디자인 툴]   

|Android Studio|<img src="https://user-images.githubusercontent.com/56965398/104442860-0419dc80-55d9-11eb-9e18-37877e1c49e1.png"  width="40%">|
|---|---|
|VsCode|<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104442943-1d228d80-55d9-11eb-9808-112595d5913d.png"  width="40%"><p/>
|Figma|<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104545589-c4510480-566d-11eb-996f-6daec08e4917.png" width="40%"><p/>|
 

------------ 

## [✍ 개발 목표]
- 저희가 대구소프트웨어고등학교 입시를 준비할 당시 인터넷에 정보를 찾아보면 컨설턴트들의 광고성 답변이나, 제대로 된 정보를 찾아보기가 어려웠습니다. 그리고 학교에 입학하여 ***학생 전문가 특강***이라는 선배가 후배에게 자신의 지식을 전달하는 프로그램이 있는 것을 알게되었습니다.    

- 학생 전문가 특강은 학생 대 학생으로 수업이 진행되기 때문에 일반 정규 수업들 보다 가볍고 모르는 것을 쉽게 물어볼 수 있는 장점이 있습니다. 그래서 저희는 이 장점들을 적용하여 ***해당 고등학교에 있는 선배에게 후배가 물어보는 형식***으로 서비스를 만들면 어떨까 하는 생각을 하게 되었습니다.     

- 그렇게 저희는 고등학교 입시를 위한 선후배 매칭 서비스 ***Hi! School***을 만들게 되었습니다.   

![image](https://user-images.githubusercontent.com/56965398/104444169-c4ec8b00-55da-11eb-915f-d31a1a2d0147.png)   

------------
   
## [⛏ 프로젝트 설계 및 구현 내용]   
|UI/UX|![image](https://user-images.githubusercontent.com/56965398/104445149-206b4880-55dc-11eb-8e4e-ec8912934d97.png)![image](https://user-images.githubusercontent.com/56965398/104445548-940d5580-55dc-11eb-9dd8-3dfbebaf2347.png)|
|---|---|
|ClientDataBase|Room|
TestServer|heroku|
ServerLanguage|python/JS|
ServerFrameWork|Django/NodeJs|

- **구현 내용**
  1. **학교 선택**  
    선배의 경우 재학중인 학교를 선택, 후배는 원하는 고등학교를 선택하여 해당하는 게시물을 볼 수 있음  
    
  2. **질문/답변**  
    후배가 질문을 올리면 선배에게 알림이 가고, 선배가 답변을 해줌  
    
  3. **채팅**  
    후배가 묻고 싶은 선배의 계정으로 채팅을 보내면 선배가 1:1 상담  
    
  4. **학교와 관련한 행사, 대회 홍보**  
    프로필 탭에서 학교 교내 대회나 행사를 홍보하고, 입학설명회도 홍보가   
    
------------   
    
## [🖥기능]  
   |<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104541915-e3e42f00-5665-11eb-8bf4-fd6191fdda15.png"  width="40%"></p>|후배가 해당 고등학교에 궁굼한 점이 있으면 질문 게시판에 올리고 선배가 답변을 해주는 기능
   |---|---|
   |<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104542907-bd26f800-5667-11eb-82b6-8eb1076c7522.png" width="40%"></p>|후배가 궁금한 점을 질문으로 작성할 수 있는 기능
   |<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104543093-1d1d9e80-5668-11eb-80f8-c7c7653b7f79.png" width="40%"></p>|후배가 게시글을 업로드 하면 선배에게 알림이 가고, 후배의 경우 답변을 받았을 때 알림이 간다
   |<p align="center"><img src="https://user-images.githubusercontent.com/56965398/104543513-ed22cb00-5668-11eb-927c-44eab0139d64.png" width="70%"></p>|선 후배 간 1:1 상담 채팅 기능|   
    
------------   
    
## [👍기대효과]  
~~~
중학생 친구들이 자신이 가고 싶은 고등학교에 대해서 직접 선배들 한테 정보를 얻고, 
학교에 오기전에 갖춰야 할 것들을 알게됨으로써 자신의 고등학교 생활에 대해서 미리 
준비 할 수 있습니다.   
~~~   
    
------------   
    
## [🚴‍♂️ 발전 가능성(앞으로 수정할 부분)]
- 디자인 리펙토링
- MVVM 아키텍처 적용
- 서버 리뉴얼(학생증 인중 시스템)
위의 부분들을 수정/적용 하여 서비스를 출시하는 것이 저희 서비스의 최종 목표입니다.   
    
------------   
    
## [📖참고 문헌]  
Android Developers JetPack
