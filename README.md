# 당신의 귀가 되어드립니다. 실내 소음 탐지 시스템 hearO✨
<img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/hearo.png"/><br />

## 서비스 소개
* 농인 및 청력의 불편함을 겪는 대상에게 서비스 제공
* 주변 소음 및 음성을 탐지, 분석하여 상황 알림
* 위급 상황 발생 시 사용자에게 알림
* 알림은 대상자를 고려하여 진동으로 진행
<br/>

## 개발 환경
Front End - react native / Firebase <br />
Back End - Spring boot / Firebase / redis / MongoDB <br />
AI - tensorflow / OpenAI / FastAPI <br />
이슈 및 유지보수 - Docker / Github action <br />
Design - figma <br />
tools - notion / github / discord <br/>
<br/>

## 프론트 개발 화면
| 푸시알람 | 
|----------|
|<img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%ED%91%B8%EC%8B%9C%EC%95%8C%EB%9E%8C.png?raw=true" width=300px />|
* 앱을 사용하지 않을 때 사용자에게 알람을 주어야하기 때문에 푸시알림 제공


| 메인 화면 | 각 알림 세부 내용 |
|----------| ------------ |
|<img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%EC%95%8C%E3%84%B9%EB%9E%8C%EC%97%AC%EB%9F%AC%EA%B0%9C.png" />| <img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%EB%AF%B8%ED%99%95%EC%9D%B8%EC%95%8C%EB%9E%8C%EC%84%B8%EB%B6%80%EB%82%B4%EC%9A%A9.png"/> |
* 소음 및 음성 탐지 후 사용자에게 상황별 알림 제공
* 음성이 탐지 된 경우에는 stt를 통해 텍스트 제공
* 확인 시 알림 삭제

| 캘린더 | 
| ---------------- |
|<img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%EC%BA%98%EB%A6%B0%EB%8D%94%EA%B8%B0%EB%B3%B8%ED%99%A4%EB%85%80.png" /> |
* 캘린더 기능을 통해 최근 1주일 간 발생한 소리 별 알람 상황 확인 가능

| 캘린더 알람 세부 | stt 내용 확인 |
| ------------ | ----------- |
|<img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%EC%95%88%EB%82%B4%EB%B0%A9%EC%86%A1%EC%9E%87%EC%96%B4%EC%9A%94.png" /> | <img src="https://github.com/baezzzi/hearo/blob/main/hearo%20ui/%EC%95%88%EB%82%B4%EB%B0%A9%EC%86%A1STT.png" /> |
* 캘린더에서 미확인/확인 알람 전부 확인 가능
* 음성 탐지 경우, stt 제공, 이전 알림 확인 가능


