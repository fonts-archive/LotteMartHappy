# 롯데마트 행복체

[배포처 바로가기](http://company.lottemart.com/bc/service/htmlView.do?menuCd=BM0307&SITELOC=DB005)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Lotte Mart Happy`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Lotte Mart Happy';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'Lotte Mart Happy';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'Lotte Mart Happy';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/LotteMartHappy-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/subsets/LotteMartHappy-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/LotteMartHappy/subsets/LotteMartHappy-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Lotte Mart Happy", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
개인 및 기업 사용자를 포함한 모든 사용자에게 무료 제공되며, 누구나 자유롭게 사용하실 수 있습니다. 
 
참고사항 통큰서체의 지적재산권은 롯데마트에 있습니다. 
 
참고사항 개인, 기업사용자 모두 상업적인 용도로 무료 사용이 가능합니다. 
 
참고사항 어떤 이유로도 지적 재산권자 이외의 사용자가 수정, 판매할 수 없으며, 배포되는 형태 그대로 사용해야 합니다. 
 
참고사항 CI, BI 제작은 불가합니다. 개인 및 기업 사용자를 포함한 모든 사용자에게 무료 제공되며, 누구나 자유롭게 사용하실 수 있습니다.
```
