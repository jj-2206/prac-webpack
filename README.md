# webpack

웹팩 설치 및 환경구축 연습 저장소입니다.

- Autoprefixer  
  구형 브라우저에서도 최신의 CSS기술이 동작할 수 있도록 해주는 패키지.  
   ```
  "browserslist": [
    "> 1%",
    "last 2 versions"
  ]
  ```
전 세계에서 점유율이 1% 이상인 모든 브라우저의 `Vender Prefix`를 최신 버전의 두 단계 전까지의 버전까지를 지원한다는 의미입니다.

  </br>
  <b>What are the CSS vendor prefixes</b>  
   CSS vendor prefixes allow the makers of web browsers to add support for the latest CSS features, for experimentation or a testing period.

  So they allow you to run all your CSS rules across all browsers.

  <b>Autoprefixer</b>  
   The autoprefixer is a PostCSS plugin to parse CSS and add vendor prefixes to CSS rules using values from Can I Use.

  It allows you to write your CSS rules without vendor prefixes, it takes care of doing that based on current browser popularity and property support.

  If you want to see how it works here you can find an interactive demo to check it out.

  <b>Why should you use Autoprefixer?</b>  
   Autoprefixer makes the life of frontend developers much easier because as I said they don’t need to think anymore which prefix to add for different browsers and to do research, Autoprefixer takes care of that and obviously it saves a lot of time.

  Also Google recommends to use it (read here) and it is used in companies as Twitter and Alibaba.  
  [How to Add CSS Vendor Prefixes Automatically /medium](https://medium.com/notonlycss/how-to-add-css-vendor-prefixes-automatically-84b6f78e4d2e)  
