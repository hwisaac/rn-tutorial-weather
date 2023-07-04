# React Native tutorial

## 설치
> [docs.expo.dev](https://docs.expo.dev/)


- 프로젝트 설치
```
npx create-expo-app --template
```

- 종속성도 설치해줘야 한다. (for WEB)
```
npx expo install react-native-web@~0.18.10 react-dom@18.2.0 @expo/webpack-config@^18.0.1
```

- expo 도 핸드폰에 설치한다.

터미널에 다음 입력하고 로그인: 
```
npx expo login
```

개발 시작:
```
npm start
```

## 특징

- `RN` 은 브라우저에서 실행되는 것이 아니므로 `div` 같은 것을 쓰지 않는다. -> `<View />` 컴포넌트를 컨테이너로 사용합니다.
- 마찬가지로 p, span 같은 태그가 없다. 문자는 모두 `<Text />` 컴포넌트 안에 들어가야 합니다. 
- Style.sheet 로 스타일 객체를 만들어서 스타일을 적용할 수 있다.
  - 자동완성 기능을 제공해준다.
  - 코드를 분리하고 가독성을 좋게 만들어준다.
- 특정 style 은 적용할 수가 없다. -> 예: `border: "1px solid black"` 

## React Native Packages

> https://reactnative.dev/
> https://reactnative.dev/docs/components-and-apis
> https://reactnative.directory/

초기에 RN 팀은 최대한 많은 컴포넌트들을 사람들에게 제공하려 했으나, 지금은 노선을 바꿔 최소한의 컴포넌트만을 제공합니다. 필요한 컴포넌트가 있다면 [커뮤니티 packages](https://reactnative.directory/) 를 이용하도록 권장하고 있습니다.