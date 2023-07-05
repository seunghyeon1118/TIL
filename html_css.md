## HTML

- `<h> </h>` - 제목을 표시하는 태그

- `<strong> </strong>` - 강조하여 진하게 표시
- `<a href=" "> </a>` - 링크 태크(href 속성)
  - `target="_blank"` 속성 : 링크 클릭 시 새 탭에서 열리도록 함
- `<ol> </ol>` - 순서가 있는 리스트
- `<ul> </ul>` - 순서가 없는 리스트

  - `<li> </li>` - 리스트 태그

- `<p> </p>` - 단락을 구분하는 태그
- `<br>` - 줄바꿈
- `<img src="파일명">` - 이미지 태그(src 속성)

  - alt 속성 : 이미지가 없을 때 대안

  - width, height 속성 : 사진 크기 변경
  - title 속성 : 사진 도움말(설명)

- `<nav> </nav>` - 문서의 네비게이션 항목을 정의
- `<article> </article>` - 본문 내용

## CSS

- `<style> </style>` - style 태그 다음에는 css(html 문법)

- id 선택자는 한 번만 사용하고 중복 시에는 class 사용
- flex 사용 시 부모 요소에 `display:flex;` 입력
  - container 속성
    - `flex-direction: row;` : 기본값
    - `flex-direction: column` : 수직방향으로 정렬
  - item 속성
    - `flex-basis` - 크기 지정
    - `flex-grow: 1;` - 여백을 채움
    - `flex-shrink: 0` - 자신의 크기를 유지
