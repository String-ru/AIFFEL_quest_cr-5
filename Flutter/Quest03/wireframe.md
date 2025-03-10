# 플러터 앱 설계

## 앱 정보  
- Wedding Trivia  
- 결혼식 하객들이 즐길 수 있는 참여형 파티 게임  
- QR스캔을 통해 하객들의 핸드폰으로 실행하는 모바일 웹앱  
- 하객들의 질답을 통해 신랑 신부만의 유니크한 스토리텔링과 인간미 발산!  
   
## 앱 구조도  
![image](https://github.com/user-attachments/assets/8d17a31c-f85c-4fb1-be03-de57a5473329)  

## 앱 와이어프레임    
![image](https://github.com/user-attachments/assets/df557531-12cc-414e-b518-2a4eee47c623)  

## 프로토타입  
![wedding_trivia_proto](https://github.com/user-attachments/assets/5fecb6c7-68a4-4375-ac36-16d7bb55eef9)

## Flutter 구현    
- 와이어프레임에 맞추어 레이아웃 소폭 변경
![wedding_trivia_2](https://github.com/user-attachments/assets/1638de35-25c7-4ad1-84e0-90b9f121a5dd)

## 회고  
- 와이어프레임을 만드는 게 익숙하지 않아서 꼼꼼하게 레이아웃을 나누지 못한게 아쉽다.
- 일단 구동하는 것을 확인하고 조금씩 원하는 기능을 넣고 빼는 식으로 진행했는데, 실무에서는 설계를 잘 하고 넘겨야할 것 같다. 
- 전환 페이지들을 각각의 dart 파일로 저장해서 임포트 하는 식으로 정리했으면 좋았겠지만, 리뷰의 편의를 위해 한 파일에 작성했다.
- QR코드와 사진등의 이미지를 넣어 완성도를 높이지 않았다. 
