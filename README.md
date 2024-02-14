http://real-my-account-be-env.eba-rhpanvt9.ap-northeast-2.elasticbeanstalk.com/
node.js의 express를 사용하여 간단한 회원가입 및 로그인 기능을 만들고 토큰을 발행하여 토큰으로 로그인을 유지할 수 있도록 하였다
mongoDB를 활요하여 유저정보와 가계부 내역이 저장된다.
회원가입과 로그인을 할 수 있으며 유저가 사용한 수입 지출내역이 저장되어 재로그인시 기존 정보를 가져올 수 있다.
mongoDB의 atlas를 활용하여 데이터를 저장하고 aws Ealstic Beanstalk를 활용하여 node.js 코드를 배포하였다
