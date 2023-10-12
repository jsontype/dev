## 구동

1. 버전을 다음과 같이 맞춘다.
   node : v18.16.0
   npm : v9.5.1
2. 클론한 뒤, 프로젝트 디렉토리에서 패키지를 설치한다다.

```
npm i
```

3. 구동한다.

```
npm start // localhost:3000으로 연다.
```

## 스크립트

프로젝트 디렉토리에서 다음을 실행할 수 있다.

### npm start

개발 모드로 앱을 실행한다.<br>

### npm run deploy

제작용 앱을 'build' 폴더에 빌드한 뒤, 배포한다.<br>
프로덕션 모드에서 React를 올바르게 번들링하고 빌드를 최적화하여 최상의 성능을 제공한다.<br>
빌드는 최소화되고 파일 이름에는 해시가 포함된다.<br>

### npm lint

eslint를 통해 lint 오류가 있는지 테스트한다.

### npm lint:fix

eslint를 통해 lint 오류가 있는지 테스트하고, 있을 경우 자동 수정한다.

### npm run format

prettier를 통해 format 오류가 있는지 테스트한다.

### npm run format:fix

prettier를 통해 format 오류가 있는지 테스트하고, 있을 경우 자동 수정한다.
