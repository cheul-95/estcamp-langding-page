
# 🐱 HODU 랜딩 페이지

> 귀여운 고양이 "호두"를 테마로 한 정적 랜딩 페이지입니다.  
> HTML과 CSS만으로 제작되었으며, GitHub Pages를 통해 배포됩니다.

## 🔗 데모 페이지

👉 [호두 랜딩 페이지 바로가기](https://cheul-95.github.io/estcamp-langding-page/)

---

## 🛠️ 사용 기술

- HTML5
- CSS3
- JavaScript (기본 DOM API)

---

## 📁 프로젝트 구조

```
estcamp-langding-page/
├── css/
│ ├── reset.css # 브라우저 스타일 초기화
│ └── style.css # 페이지 스타일 정의
├── img/ # 모든 이미지 리소스
├── file.pdf # 다운로드용 문서 파일
├── index.html # 메인 HTML 페이지
└── README.md # 프로젝트 설명 문서
```

---

## 💻 로컬에서 실행하기

1. 이 저장소를 클론하거나 zip으로 다운로드합니다.
2. `index.html` 파일을 브라우저에서 직접 열면 됩니다.

```
git clone https://github.com/cheul-95/estcamp-langding-page.git
cd estcamp-langding-page
start index.html
```

---

## 🖼️ 미리보기

<table align="center">
  <thead>
    <tr>
      <th align="center">💻 데스크탑 화면</th>
      <th align="center">📱 모바일 화면</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" valign="top">
        <img src="./img/landing-pc.png" alt="Desktop View" width="400">
      </td>
      <td align="center" valign="top">
        <img src="./img/landing-m.png" alt="Mobile View" width="250">
      </td>
    </tr>
  </tbody>
</table>

---

## 📌 주요 특징

✅ 순수 HTML + CSS + JS 기반의 정적 웹사이트

✅ 모바일 메뉴 토글 및 다이얼로그(모달) 기능

✅ 반응형 디자인
  - Desktop: max-width: 1320px
  - Tablet: max-width: 1023px
  - Mobile: max-width: 768px
  - picture , source 태그를 활용한 이미지 최적화
    
✅ 시맨틱 마크업
  - header, main, footer 레이아웃 구조 사용
  - 각 섹션 제목에 h2 태그 활용
  - sr-only

✅ 접근성 향상 요소
  - fieldset, legend, label, aria-label, alt,aria-hidden 등을 적절히 활용

✅ 검색엔진 최적화(SEO)
  - meta 태그: description, keywords, author 설정

✅ CSS 네이밍 방식
  - BEM(Block Element Modifier) 방식 적용
  - 유지보수성과 코드 가독성 개선 

---

## 🔧 향후 작업 목록 리스트

 - 모달 닫기 버튼에 이벤트 연결
 - 헤더 이후 섹션에서 자연스럽게 스크롤 시작되도록 개선
 - Open Graph 및 SNS 미리보기용 meta 태그 추가

---
## 🙋‍♀️ 제작자

- SC LEE  
- GitHub: [@cheul-95](https://github.com/cheul-95)
