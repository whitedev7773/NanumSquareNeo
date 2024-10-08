# NanumSquareNeo
> 나눔스퀘어 고유의 직선적인 형태를 계승한 글꼴로 친근한 미감과 안정적인 글줄이 특징이며, 다양한 환경에서 메시지를 주목도 있게 전달하기 좋은 글꼴입니다.https://hangeul.naver.com/fonts/search?f=nanum

나눔스퀘어 Neo 폰트를 웹에서 사용할 수 있게 변환한 웹폰트입니다.

## 🧑‍💻 폰트 개발자
나눔스퀘어 Neo 폰트는 네이버 한글한글 아름답게 캠페인으로 개발한 폰트입니다.

## 🔍 미리보기
[Playground](https://htmlpreview.github.io/?https://github.com/whitedev7773/NanumSquareNeo/blob/master/index.html)

[![폰트 미리보기](https://raw.githubusercontent.com/whitedev7773/NanumSquareNeo/main/demo.png)](https://htmlpreview.github.io/?https://github.com/whitedev7773/NanumSquareNeo/blob/master/index.html)

## 🪚 폰트 굵기
나눔스퀘어 Neo 폰트는 총 5가지의 굵기를 지원합니다.  
CSS의 `font-weight: 200,300,700~900`을 사용할 수 있습니다.
| Weight Name | CSS Value | 설명          |
| :---        | :---      | ---:          |
| Light       | 200       | 가장 얇음     |
| Regular     | 300       |               |
| Bold        | 700       | 중간인 두께   |
| ExtraBold   | 800       |               |
| Heavy       | 900       | 가장 두꺼움   |

## ✏️ 사용 방법
### `<link>` 방식
> HTML 문서에 아래 link 태그를 추가하여 폰트를 불러올 수 있어요.  
> @import 방식 대신 쓰는 걸 추천해요.
> ```html
> <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/whitedev7773/NanumSquareNeo/NanumSquareNeo.css">
> ```
### `@import` 방식
> css 파일에서 @import를 추가해서 폰트를 불러올 수 있어요.  
> 이 방식 대신 link 방식을 쓰는 걸 추천해요.
> ```css
> @import url(https://cdn.jsdelivr.net/gh/whitedev7773/NanumSquareNeo/NanumSquareNeo.css);
> ```

## ✅ 적용
> css 적용 예시
> ```css
> body		{ font-family: 'NanumSquareNeo', sans-serif }
> .light		{ font-weight: 200 }
> .regular	{ font-weight: 300 }
> .bold		{ font-weight: 700 }
> .extrabold	{ font-weight: 800 }
> .heavy		{ font-weight: 900 }
> ```