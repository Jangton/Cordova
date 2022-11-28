# 실행 화면 
<br>
<img src = "https://github.com/Jangton/Cordova/blob/main/img/cordova%EB%A9%94%EC%9D%B8.JPG" height="600" align="left">
<br>
<img src = "https://github.com/Jangton/Cordova/blob/main/img/cordova%EB%AA%A8%EB%B0%94%EC%9D%BC%20%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.JPG" height="600" align="center">
<br>

## 환경변수 설정를 설정해주었습니다.
<br>
<img src = "https://github.com/Jangton/Cordova/blob/main/img/%ED%99%98%EA%B2%BD%EB%B3%80%EC%88%98.JPG" height="600" align="left">
<br>
<img src = "https://github.com/Jangton/Cordova/blob/main/img/%ED%99%98%EA%B2%BD%EB%B3%80%EC%88%98%20%ED%99%88.JPG" height="200" align="center"><br>
<br>

## Node.js 다운로드(cmd창에서 실행)<br>
cmd 창에서 <br>
node -v (node 버전 확인) <br>
npm -v (npm 버전 확인) <br>
npm update -g (npm 업데이트) <br>

##phonegap 다운로드<br>
npm install -g phonegap <br>
npm install -g cordova <br>
cordova -v <br>
npm update -g phonegap <br>
npm update -g cordova <br>

## Andorid cordova 만들기<br>
cmd창을 켜고 <br>
mkdir \HybridProject <br>
프로젝트 파일 만들기 <br>
cd\HybridProject <br>
cordova create test com.example.test testApp -d  <br>
Cordova test 파일 만들기(test부분 수정해서 파일명 변경 가능) <br>
cd test <br>
dir <br>
dir platform <br>	
안되면 밑에 줄 해보고 하기 <br>
cordova platform add android <br>
android 플랫폼 추가하기 <br>
dir platform <br>
<br>
## 안드로이드에서 실행 시(USB와 갤럭시 기종의 스마트폰 필요)<br>
### 1. 삼성 usb드라이버를 설치한다<br>
### 2. 갤럭시 스마트폰 설정에 들어가서 개발자 옵션을 들어간 뒤 usb디버깅을 온한다.<br>
### 3. usb를 스마트폰에 연결해 컴퓨터와 스마트폰을 디버깅한다.<br>
### 4. cmd에 >cd\HybridProject -> cd/test를 입력 후 cordova run android을 입력해 준다.<br>
### 5. 실행이 완료된다.<br>
<br>
<image src = "https://github.com/Jangton/Cordova/blob/main/img/cmd%20%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C%20%EC%8B%A4%ED%96%891.JPG" height="600" align="left"><br>
  <br>
<image src = "https://github.com/Jangton/Cordova/blob/main/img/cmd%20%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C%20%EC%8B%A4%ED%96%892.JPG" height="600" align="center"><br>
