# 부트캠프 3일차 - HTML 폼과 입력 요소 학습

## 📚 학습 목표
HTML의 다양한 입력 요소와 폼 구조를 이해하고 실제 웹 페이지에서 사용자 입력을 받는 방법을 학습합니다.

## 📁 프로젝트 구조
```
├── 13-입력을받자.html              # 기본 입력 요소 학습
├── 14-input외입력태그.html         # select, textarea 등 다양한 입력 태그
├── 15-양식만들고값전송하기.html     # form 태그와 데이터 전송
├── 17-문서정보관리.html            # meta 태그와 문서 정보 관리
├── form_Mini_project.html          # 설문조사 양식 미니 프로젝트
└── project_report/                 # 최종 프로젝트 결과물
    ├── 설문조사 양식.html
    └── 회원가입.html
```

## 🎯 학습 내용

### 1. 기본 입력 요소 (13-입력을받자.html)
- `<input>` 태그의 다양한 타입
  - `text`: 텍스트 입력
  - `password`: 비밀번호 입력
  - `color`: 색상 선택
  - `number`: 숫자 입력 (min, max 속성)
  - `range`: 범위 슬라이더
  - `checkbox`: 체크박스
- `<label>` 태그와 접근성
- `placeholder` 속성으로 힌트 제공

### 2. 다양한 입력 태그 (14-input외입력태그.html)
- `<fieldset>`과 `<legend>`: 관련 요소 그룹화
- `<select>`와 `<option>`: 드롭다운 선택
  - `multiple` 속성: 다중 선택
  - `size` 속성: 표시할 항목 수
  - `selected` 속성: 기본 선택 항목
- `<textarea>`: 여러 줄 텍스트 입력
- `<progress>`: 진행률 표시
- `<button>`: 클릭 가능한 버튼

### 3. 폼 데이터 전송 (15-양식만들고값전송하기.html)
- `<form>` 태그의 핵심 속성
  - `action`: 데이터를 보낼 URL
  - `method`: 전송 방식 (GET/POST)
- `name` 속성: 서버 전송 시 사용되는 키
- `<input type="submit">`: 폼 데이터 전송 버튼

### 4. 문서 정보 관리 (17-문서정보관리.html)
- `<meta>` 태그의 다양한 용도
  - `charset`: 문자 인코딩 설정
  - `viewport`: 반응형 웹 설정
  - `author`: 작성자 정보
  - `description`: 페이지 설명
  - `keywords`: 검색 키워드

### 5. 미니 프로젝트 (form_Mini_project.html)
종합적인 설문조사 양식 제작
- 개인정보 입력 섹션
- 라디오 버튼을 이용한 단일 선택 (연령대, 지역)
- 체크박스를 이용한 다중 선택 (학원 선택 기준)
- 자유 의견 입력 영역

## 🚀 주요 학습 포인트

### 접근성 (Accessibility)
- `<label>` 태그의 `for` 속성과 `<input>`의 `id` 연결
- 의미있는 HTML 구조 사용

### 폼 검증
- `required` 속성으로 필수 입력 설정
- `min`, `max` 속성으로 값 범위 제한
- `placeholder`로 사용자 가이드 제공

### 시맨틱 HTML
- `<fieldset>`과 `<legend>`로 관련 요소 그룹화
- `<header>`, `<main>`, `<footer>` 구조적 태그 사용

## 📋 실습 체크리스트
- [ ] 다양한 input 타입 사용해보기
- [ ] label과 input 올바르게 연결하기
- [ ] form 태그로 데이터 전송 구조 만들기
- [ ] meta 태그로 문서 정보 설정하기
- [ ] 접근성을 고려한 폼 구조 작성하기

## 🔗 관련 자료
- [MDN Web Docs - HTML Forms](https://developer.mozilla.org/ko/docs/Web/HTML/Element/form)
- [MDN Web Docs - Input Element](https://developer.mozilla.org/ko/docs/Web/HTML/Element/input)
- [웹 접근성 가이드라인](https://www.w3.org/WAI/WCAG21/quickref/)

---
*부트캠프 3일차 학습 완료! 다음 단계에서는 CSS 스타일링을 학습할 예정입니다.*