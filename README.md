# 🖼 로고 SVG 아카이브

브랜드들의 **SVG 형식 벡터 로고**를 모아두기 위해 제작한 저장소입니다.

개발자들이나 디자이너들이 로고를 가져다 쓰기 편하게 하는 것이 목적입니다.

## 파일 형식

기본적으로, 다음과 같은 로고 형식을 취급합니다.

벡터: 

- **`svg`**

공개 원본:

- `ai`
- `eps`

## 기타

- PR, 기여 환영
  - Squash merging을 사용하고 있습니다. 기여 규칙은 <a href="CONTRIBUTING.md">CONTRIBUTING</a>을 참고해주세요.
- **공개 원본**?
  - 브랜드를 소유하고 있는 회사에서 공식으로 공개한 파일의 원본을 저장합니다.
  - 회사 홈페이지에 공개된 경우에만 업로드하며, 원본이라도 파일 형식에 일치하지 않는 경우 업로드하지 않습니다.
  - 공개 원본은 각 로고 폴더 하위에 `original`이라는 이름으로 업로드합니다.
- SVG 최적화
  - 기본적으로 `svgo`를 통하여 처리 후 업로드합니다. [#svgomg](https://jakearchibald.github.io/svgomg/)
  - 추가적으로 저장소 메인테이너가 보기에 최적화가 가능하다고 생각되는 부분은 수정 후 커밋될 수 있습니다.

## 참고

- <https://github.com/gilbarbara/logos>
- <https://github.com/simple-icons/simple-icons>