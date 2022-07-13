test---------22222222222-----------# hamonikr-apphamonia

화상회의 프로그램 hamonia

node 8.16.0 이상


npm install node 로 설치하는  경우 8.10 버전이 설치됩니다.
아래의 n 모듈을 이용하여 설치 진행하시기 바랍니다.


## npm 을 이용한 node 설치 관리
```
# 버전확인
node -v

# 강제로 캐시 삭제
sudo npm cache clean -f

# n모듈 설치
sudo npm install -g n

# n모듈을 사용하여 Nodejs 설치
sudo n stable

# 설치확인 - 버전확인
node -v
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn electron:serve
```

### Compiles and minifies for production
```
yarn electron:build
```


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

* 변수 초기화로 인해 접속이 안되던 부분 수정
