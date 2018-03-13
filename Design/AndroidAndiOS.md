# 안드로이드와 iOS 디자인 차이점

- iOS 
    - Human Interface
    - 크기 단위 : pixel based
    - 축적 계수 : 1~3배수 (img.png, img@2x.png, img@3x.png)
    - 가변 리소스(ex : 카드가 다를 때) : vertical 의 경우, 상단 하단의 부분만 나누고 가운데를 납품
    - 
    -
    
- Android
    - Material Design
    - 크기 단위 : dp, dpi based (Dots Per Inch)
    - 축적 계수 : ldpi > xxxdpi 까지 6개
    - 가변 리소스 : 나인패치
    - mdpi를 기준으로 아트보드를 만듬
    -
    
- 공통
    - 작업시 1배수의 화면을 가지고 아트보드를 만들고 export시 배수설정
    
### 참고 사이즈

> 