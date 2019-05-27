# 190429_meeting
## 하고 있는 토이프로젝트
### 1.로그인
```
암호설정 및 인증과정
현재는 aws lambda에서 대조후 처리중


```
### 2.홈피드
```
구글드라이브에있는 사진들 불러옴
현재는 google apps script 이용
```
### 3.대화
```
저장한것 불러오려면 결국 db가필요...?
현재는 aws dynamodb + lambda 사용중
db에 변화가 생기면 업데이트 하고싶음
node + express 사용?
배포할 수 있나?
```

## 프론트엔드 신입이 가져야할 기술?
javascript 어디까지?
react? vue? node? express?
알고리즘? or 다른언어 or 컴퓨터 


////////

# 190527_meeting
## 클라이언트 빌드
yarn build 이제안함
yarn serve 로 :8080에서 :3000으로 proxy설정해줌
한가지, 새로고침하면 socket과 proxy 둘중하나가 1초마다 에러남(아마 socket)

## socket.id
socket연결함
궁금한점
express app.js에서 app.get('/') 과 app.use('/')의 차이...?
app.get('/')이 왜안되는지 모르겠음...
express().Router의 역할도..

## db연결
예전에 연결못한 db 연결함
no,id,msg,datetime 4row...

전반적으로 실시간채팅은 거의 마무리단계인것같음...
다음주에는 배포해볼예정

## 다음 하고싶은것
알고리즘연습?
js연습더하기... 예)숫자야구게임,같은그림찾기 같은것?
