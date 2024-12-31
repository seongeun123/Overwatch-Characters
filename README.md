# Overwatch-Characters
![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)

패스트캠퍼스 강의를 듣고 작성했습니다.


## 오답노트
:star: reset.css cdn
```
 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.2/reset.min.css">
```

:star: 약식 표현
```
<div class="heroes">
  .hero*32>.image
</div>
```

:star: margin으로 가운데 정렬하기
```
margin: 0 auto
```
해당 요소가 블록이고, 가로 사이즈가 명시되어 있으면 margin 으로 가운데 정렬할 수 있다.

:star: skewX
```
.container .heroes .hero {
    transform: skewX(-14deg);
 }

.container .heroes .hero:hover{
    transform: skewX(-14deg));
}
```
부모 요소에서 skewX를 적용하면 자식 요소에도 적용되어서 자식요소에 반대로 다시 적용해줘야 한다.
