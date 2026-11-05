## What's This?
HeadKasen은 [Orinrin Editor](https://github.com/SikigamiHNQ/OrinrinEditor) 등 아스키 아트 제작 환경에서 한글을 사용하기 위해 제작된 폰트입니다.  
Saitamaar와 DOSGothic 폰트를 결합 후 일부 글리프를 수정 및 추가하였습니다.  

기본 `HeadKasen.ttf` 파일은 16px 내장 비트맵이 포함된 PC 설치용 폰트이며, `HeadKasen-Web.ttf` 및 `HeadKasen-Web.woff2` 파일은 웹페이지의 비정수 배율에서도 폰트가 틀어지지 않도록 비트맵을 제거한 버전입니다.

```css
@font-face
{
  font-family: 'HeadKasen Web';
  src:
    url(https://da1eth.github.io/HeadKasen/fonts/web/HeadKasen-Web.woff2) format("woff2"),
    url(https://da1eth.github.io/HeadKasen/fonts/web/HeadKasen-Web.ttf) format("truetype");
  font-style: normal;
  font-weight: 400;
}
```

HeadKasen 웹폰트를 페이지에 포함하고 싶다면 위와 같은 css를 추가하면 됩니다.


## License
### HeadKasen
© Daleth  
본 폰트는 자유롭게 사용, 수정 및 출처 표기 후 재배포할 수 있으나 폰트 파일 자체를 유료로 판매할 수는 없습니다.

### Saitamaar
© YAMASINA Keage - http://keage.sakura.ne.jp / https://github.com/keage/Saitamaar  
Saitamaar is in the public domain.

### DOSGothic
Copyright (c) 2016-2022 Damheo Lee - https://github.com/hurss/fonts  
Licensed under the MIT license. - http://www.opensource.org/licenses/mit-license.php
