# RxPocketMonCardEffect
* RxPocketMonCardEffect
* CSS + JAVASCRIPT Card Effect

Support By [ Cloud Rx (<a href='https://rxapis.com'>https://rxapis.com</a>) ].
* Testing is available until 2025/12/31 23:59.

<img width="1677" alt="스크린샷 2024-11-17 오후 6 21 56" src="https://github.com/user-attachments/assets/cd1e3356-727c-4a79-b916-4300858544aa">
<img width="1677" alt="스크린샷 2024-11-17 오후 6 22 00" src="https://github.com/user-attachments/assets/a27c8044-5892-435c-82d1-dcab6590a735">


```javascript
new PocketMonCardEffect({
    ele : document.getElementById('card'),
    
    perspective : 2000,
    angle : 30,
    bgImage : `./banner1.jpeg`,
    bgPosition : 'center',
    bgSize : 'contain',

    effectHolo : `./effImg/holo.webp`,
    effectHoloMixBlendMode : 'color-dodge',
    effectHoloScale : 1,
    effectHoloOpacity : .5,

    effectSparkles : `./effImg/sparkles.webp`,
    effectSparklesMixBlendMode : 'color-dodge',
    effectSparklesScale : 1,
    effectSparklesOpacity : .5,

    shadow : true,
    shadowColor : `rgba(0, 0, 0, 0.5)`,
    shadowBlur : 20,

    holography : true,
    holographyDistance : 50,
    holographyImage : `./ch1.png`,
    holographyScale : 1.2,

});
```




## Document
* ele : Html Element
* perspective : Number, default : 2000  - rotate perspective
* angle : Number, default : 30  - rotate
* bgImage : String              - CSS background-image image Url
* bgPosition : String           - CSS background-position
* bgSize : String               - CSS background-size

    
* effectHolo : String           - Effect Image Url
* effectHoloMixBlendMode : String   - CSS mix-blend-mode
* effectHoloScale : Number      - Effect Image Scale, default : 1
* effectHoloOpacity : Number    - Effect Image Opacity, default : 0.5

* effectSparkles : String
* effectSparklesMixBlendMode : String   - CSS mix-blend-mode
* effectSparklesScale : Number  - Effect Image Scale, default : 1
* effectSparklesOpacity : Number - Effect Image Opacity, default : 0.5

* shadow : Boolean              - default : false
* shadowColor : String          - CSS
* shadowBlur : Number           - CSS

* holography : Boolean          - default : false
* holographyImage : String
* holographyScale : Number      - default : 1.2

