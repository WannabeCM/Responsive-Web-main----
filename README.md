
##  반응형 웹

시연 영상
![]()


[사이트 바로가기](https://wannabecm.github.io/Responsive-Web-main----/)

## TIL
### 레이아웃은 width:100vw로 맞춰주기
테블릿과 모바일 부분에서 자꾸 가로 스크롤이 생겼다.
문제는 처음에 부모요소와 자식요소 모두에 width가 rem 등으로 지정되어 있어서 발생한 듯 하다.
부모요소에 width:100vw를 주고
자식요소에 width를 삭제 해주니 문제가 해결되었다.
### word-break:keep-all
한글은 단어별로 끊어주어야 하므로 위와같은 속성을 부여해주었다.

## 궁금한점

