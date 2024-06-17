# 부크크 고딕

[배포처 바로가기](https://bookk.co.kr/bookkFonts#gd)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Bookk Gothic`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Bookk Gothic';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Light.ttr') format('truetype');
}
@font-face {
    font-family: 'Bookk Gothic';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/BookkGothic-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/subsets/BookkGothic-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/BookkGothic/subsets/BookkGothic-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Bookk Gothic", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
제공되는 서체의 지적 재산권을 포함한 모든 권리는 (주)부크크에 있습니다. 
서체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공됩니다. 
상업적인 용도로 사용이 가능합니다. 
단, 임의로 수정 및 편집 등을 할 수 없으며, 배포되는 형태 그대로 사용되어야 합니다. 
제공되는 글꼴을 유료로 판매하는 것은 금지됩니다. 
글꼴 출처 표기를 권장합니다. 
부크크체가 사용된 인쇄물, 광고물(온라인 포함)은 (주)부크크의 홍보를 위해 활용될 수 있습니다.
```
