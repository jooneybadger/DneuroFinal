# Latte & Iced Americano

# Introduction
<a href="https://www.youtube.com/watch?v=TFihk6oYf8o"><img src="https://i.ibb.co/NYdSskq/dneurologo.png"  width="400" height="370"></a>

<div>👆클릭해서 영상으로 이동(Main Page && Detail Page)</div>

## What did we use

- Language: JavaScript
- Library: React
- Third-party: React-Router, Styled-components, React-Slick, Redux, Hooks, Chart.js

## Who we are
### Team Members : Front-End

```javascript
  const member = 
        [{id : 0,
          'name': '공주민'},
         {id : 1,
          'name': '박영준'}]
```

### Team Members : Back-End

```javascript
  const member = 
        [{id : 0,
          'name': '백승진',},
         {id : 1,
          'name': '정현석',}]
```

# What we did

### 완성한 미션

#### Main page
- [x] Function : 토큰이 없을 시, survey를 진행하지 못하도록 구현
- [x] Function : 동적 routing 이용하여, survey 페이지로 넘어가도록 구현

#### Login page
- [x] Function : 카카오 API 이용하여 소셜 로그인 구현
- [x] Function : 서버와 통신하여 토큰을 이용한 일반 로그인 구현

#### SignUp Page
- [x] Function : 문자인증을 통하여 본인인증을 할 수 있도록 구현
- [x] Function : 서버에 사용자 정보를 넘겨줄 수 있도록 구현

#### Survey Page
- [x] Function : 사용자가 답변 클릭시, 서버로 데이터가 넘어가고 새로운 질문지를 받아오도록 구현
- [x] Function : 설문을 응답하는 시간을 계산하도록 구현
- [x] Function : 다시하기 버튼을 누르면 설문이 초기화 되도록 구현
- [x] Function : slice 메소드를 이용하여 받은 데이터를 원하는만큼 잘라서 사용
- [x] Function : Progress bar를 이용하여 설문 진행 상태 구현

#### Result Page
- [x] Function : Chart.js를 이용하여 결과값을 데이터 시각화

#### ShowResult
- [x] Function : 사용자가 로그아웃 했다가 다시 로그인을 했을시, 이전에 진행한 설문 결과를 보여주도록 구현

#### 배포
- [x] Function : AWS.ec2를 이용하여 페이지 배포
