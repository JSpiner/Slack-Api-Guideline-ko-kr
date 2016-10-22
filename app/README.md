# Slack App Api 가이드라인 
이 페이지에선 [Event Api](./eventapi), [Web Api](./webapi), [RTM Api](./rtmapi), [Bot User](./botuser), [Slash Command](./slashcommand), [Publish](./publish)에 대한 간략한 설명과 절차가 설명 되어 있습니다.

## 사전 준비물 
- 슬랙 App([여기](https://api.slack.com/apps)서 만들 수 있습니다.)
- https 형태로 callback을 받을 수 있는 서버(`Slash Command`와 `EventApi`만 해당)
- websocket방식을 지원하는 언어(`RTM API`만 해당)

## App 사용 프로세스   
#### 앱 설치 요청   
웹페이지 혹은 프로그램에서 아래와 같은 링크를 통해 `App` 설치 요청이 필요합니다.
```
https://slack.com/oauth/authorize?client_id=<앱의 clientId>&scope=<필요한 권한들>
```




