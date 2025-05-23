# 🌟 내 바이브 - 개인 브랜딩 사이트

> 아름다운 디지털 경험을 만드는 크리에이티브 개발자의 개인 브랜딩 웹사이트

![Website Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📖 프로젝트 소개

**내 바이브**는 개인의 감각과 분위기를 담은 미니멀하고 트렌디한 개인 브랜딩 웹사이트입니다. 바이브한 디자인과 부드러운 애니메이션으로 개성을 효과적으로 표현할 수 있는 싱글 페이지 웹사이트입니다.

### ✨ 주요 특징

- 🎨 **미니멀 & 모던 디자인**: 깔끔하고 세련된 UI/UX
- 🌈 **그라데이션 테마**: 보라-파랑 그라데이션으로 시각적 임팩트
- 📱 **완전 반응형**: 모든 디바이스에서 완벽한 경험
- ⚡ **부드러운 애니메이션**: 스크롤 기반 인터랙션과 트랜지션
- 🎯 **사용자 중심**: 직관적인 네비게이션과 UX
- 🚀 **빠른 로딩**: 최적화된 성능

## 🎬 데모

[Live Demo 보기](https://your-username.github.io/my-vibe-portfolio)

## 🛠️ 기술 스택

### Frontend
- **HTML5** - 시맨틱 마크업
- **CSS3** - Flexbox, Grid, 애니메이션
- **Vanilla JavaScript** - 인터랙션 및 동적 기능

### 라이브러리 & 도구
- **Google Fonts** (Outfit, Poppins)
- **Font Awesome** 6.4.0
- **Intersection Observer API** - 스크롤 애니메이션
- **CSS Variables** - 테마 시스템

### 배포
- **GitHub Pages** / **Netlify** 호환

## 🎯 주요 기능

### 📍 인트로 섹션 (Hero)
- 페이드인 애니메이션으로 시작
- 그라데이션 텍스트 효과
- 스크롤 유도 애니메이션 (바운스 효과)
- CTA 버튼

### 📍 자기소개 섹션
- 프로필 이미지/아이콘
- 자기소개 텍스트
- 개성있는 해시태그들
- 슬라이드인 애니메이션

### 📍 포트폴리오 섹션
- 반응형 그리드 레이아웃
- 호버 시 3D 리프트 효과
- 프로젝트 카테고리 태그
- 순차적 카드 등장 애니메이션

### 📍 연락처 섹션
- 이메일 클릭 시 자동 복사 기능
- 소셜 미디어 링크
- 다크 테마 디자인
- 글래스모피즘 효과

## 🚀 설치 및 실행 방법

### 1. 저장소 클론
```bash
git clone https://github.com/your-username/my-vibe-portfolio.git
cd my-vibe-portfolio
```

### 2. 로컬에서 실행
```bash
# 간단한 HTTP 서버 실행 (Python 3)
python -m http.server 8000

# 또는 Live Server Extension 사용 (VS Code)
# index.html 우클릭 → "Open with Live Server"
```

### 3. 브라우저에서 확인
```
http://localhost:8000
```

## 🎨 커스터마이징 가이드

### 개인 정보 수정

#### 기본 정보 변경
```html
<!-- index.html의 482-484행 -->
<h1 class="hero-title">안녕하세요, [당신의 이름]입니다</h1>
<p class="hero-subtitle">[당신의 역할/직업] 및 [관심사/전문분야]</p>
```

#### 연락처 정보 수정
```html
<!-- index.html의 685-691행 -->
<a href="mailto:[your-email]" class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>[your-email]</span>
</a>
<a href="tel:+82[your-phone]" class="contact-method">
    <i class="fas fa-phone"></i>
    <span>[your-phone]</span>
</a>
```

#### 소셜 링크 수정
```html
<!-- index.html의 695-715행 -->
<a href="[your-github-url]" class="social-link" title="깃허브">
    <i class="fab fa-github"></i>
</a>
<!-- 다른 소셜 링크들도 동일하게 수정 -->
```

### 색상 테마 변경

CSS 변수를 수정하여 전체 테마를 쉽게 변경할 수 있습니다:

```css
:root {
    --primary-color: #1a1a1a;      /* 기본 다크 컬러 */
    --secondary-color: #f5f5f5;    /* 배경 컬러 */
    --accent-color: #6366f1;       /* 액센트 컬러 */
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* 원하는 색상으로 변경 */
}
```

### 포트폴리오 항목 추가/수정

```html
<!-- 새로운 포트폴리오 아이템 추가 -->
<div class="portfolio-item">
    <div class="portfolio-image">
        <i class="fas fa-[icon-name]"></i>
    </div>
    <div class="portfolio-content">
        <h3 class="portfolio-title">🎯 [프로젝트 제목]</h3>
        <p class="portfolio-description">
            [프로젝트 설명]
        </p>
        <div class="portfolio-tags">
            <span class="portfolio-tag">[기술1]</span>
            <span class="portfolio-tag">[기술2]</span>
        </div>
    </div>
</div>
```

## 📁 프로젝트 구조

```
my-vibe-portfolio/
│
├── index.html          # 메인 HTML 파일
├── README.md          # 프로젝트 문서
└── assets/            # 에셋 폴더 (선택사항)
    ├── images/        # 이미지 파일들
    └── icons/         # 아이콘 파일들
```

## 🌐 배포 방법

### GitHub Pages로 배포

1. GitHub 저장소 생성
2. 코드 푸시
3. Settings → Pages → Source: Deploy from a branch
4. Branch: main 선택
5. `https://[username].github.io/[repository-name]`에서 확인

### Netlify로 배포

1. [Netlify](https://netlify.com) 회원가입
2. "New site from Git" 선택
3. GitHub 저장소 연결
4. Build command: 비워두기
5. Publish directory: `/` (루트)
6. Deploy 클릭

## 🎨 디자인 특징

### 컬러 팔레트
- **Primary**: `#1a1a1a` (다크 그레이)
- **Secondary**: `#f5f5f5` (라이트 그레이)
- **Accent**: `#6366f1` (인디고)
- **Gradient**: 보라-파랑 그라데이션

### 타이포그래피
- **Primary Font**: Outfit (Google Fonts)
- **Secondary Font**: Poppins (Google Fonts)
- **Responsive**: `clamp()` 함수로 반응형 텍스트

### 애니메이션
- **Fade In Up**: 요소들의 등장 애니메이션
- **Slide In**: 좌우 슬라이드 효과
- **Hover Effects**: 3D 변형 효과
- **Parallax**: 히어로 배경 패럴랙스

## 🔧 개발 팁

### 성능 최적화
- CSS 애니메이션 하드웨어 가속 사용
- Intersection Observer로 스크롤 최적화
- 이미지 lazy loading 적용 가능

### 접근성
- 시맨틱 HTML 구조
- ARIA 레이블 추가 권장
- 키보드 네비게이션 지원

### SEO 개선
```html
<!-- head 태그에 추가 -->
<meta name="description" content="[당신의 소개]">
<meta name="keywords" content="[관련 키워드들]">
<meta property="og:title" content="[당신의 이름] - 개인 브랜드">
<meta property="og:description" content="[간단한 소개]">
<meta property="og:image" content="[썸네일 이미지 URL]">
```

## 🤝 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

## 📞 연락처

- **이메일**: hello@myvibe.com
- **깃허브**: [@your-username](https://github.com/your-username)
- **링크드인**: [Your Name](https://linkedin.com/in/your-profile)

## 🙏 감사의 말

- [Google Fonts](https://fonts.google.com) - 아름다운 웹폰트 제공
- [Font Awesome](https://fontawesome.com) - 훌륭한 아이콘 라이브러리
- [CSS Gradient](https://cssgradient.io) - 그라데이션 생성 도구

---

⭐ 이 프로젝트가 마음에 드셨다면 별표를 눌러주세요!
