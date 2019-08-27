# hamonikr-apphamonia

## 화상회의 프로그램 hamonia

구성원 간 실시간 문서공유 및 화상회의 기능을 제공하는 프로그램으로 문서 소유자 정보를 기반으로 플러그인인 없는 웹브라우저기반 실시간 통신기술을 적용하여 별도의 서버 없이 영상통화 및 문서공유가 가능하도록 개발된 프로그램 입니다<br/>
<br/>
<br/>

![screensht samlpe](./img/image2019-7-9_18-14-16.png?raw=true)
별도의 서버를 구축하지 않고 피어간 웹브라우저를 기반으로 실시간 영상과 문서를 공유할 수 있는 WebRTC 기반 P2P 아키텍처
![screensht samlpe](./img/image2019-7-9_18-14-16.png?raw=true)
실시간 문서 공유 및 판서 기능
- 원문을 PDF로 변환하고, 변환된 PDF는 이미지로 추출하여 문서 공유
- Android, iOS 등 다양한 모바일 기기 및 데스크톱 PC 간 별도의 설치 없이 사용할 수 있는 호환성 제공
<br/>
<br/>

# 사용법

## 프로젝트 설정
```
yarn install
```

### 개발을 위한 컴파일 및 핫리로드
```
yarn run serve
```

### 빌드를 위한 컴파일
```
yarn run build
```

### 테스트 실행
```
yarn run test
```

### Lints 및 수정파일
```
yarn run lint
```

### 사용자 정의 구성
See [Configuration Reference](https://cli.vuejs.org/config/).

* 변수 초기화로 인해 접속이 안되던 부분 수정
