# A.Storm

A.Storm 게임 개발 스튜디오 공식 웹사이트

> "We make games that delight people."

## 프로젝트 소개

A.Storm은 던전앤파이터 개발팀 A.Shock Studio 출신들이 설립한 게임 개발 스튜디오입니다. 현재 "Nightmare Breaker" (MORPG) 등의 액션 게임을 개발하고 있습니다.

**웹사이트**: https://www.astorm.com

## 기술 스택

| 분류 | 기술 |
|------|------|
| 마크업 | HTML5 |
| 스타일 | CSS3 |
| 클라이언트 | JavaScript (jQuery) |
| UI 컴포넌트 | Slick Carousel |
| 터치 핸들링 | Hammer.js |
| 기능 감지 | Modernizr |

## 디렉토리 구조

```
astorm/
├── index.html              # 메인 웹사이트 (SPA)
├── README.md
└── assets/
    ├── css/
    │   ├── style.min.css   # 압축된 스타일시트
    │   └── fonts/          # 웹 폰트 (Brandon Grotesque, NanumBarunGothic)
    ├── js/
    │   ├── app.js          # 메인 애플리케이션 로직
    │   ├── plugins.js      # 폴리필
    │   └── vendor/         # 외부 라이브러리
    ├── img/                # 이미지 리소스
    └── lib/slick/          # Slick 슬라이더 라이브러리
```

## 페이지 구성

| 섹션 | 설명 |
|------|------|
| `#home` | 메인 히어로 섹션 |
| `#about` | 회사 소개 |
| `#project` | 프로젝트 소개 (Nightmare Breaker) |
| `#career` | 채용 정보 |
| `#contact` | 연락처 및 위치 |

## 주요 기능

- **SPA 구조**: 단일 페이지 애플리케이션으로 해시 기반 라우팅 지원
- **반응형 디자인**: 모바일(740px 이하) 및 데스크톱 최적화
- **페이지 네비게이션**: 마우스휠/터치 기반 페이지 전환
- **모달 시스템**: 프로젝트, 채용, 오피스 사진, 지도 모달
- **이미지 슬라이더**: Slick Carousel 기반 오피스 갤러리

## 실행 방법

정적 웹사이트이므로 별도의 빌드 과정 없이 웹 서버에서 바로 서비스할 수 있습니다.

```bash
# 로컬 서버 실행 예시 (Python)
python -m http.server 8000

# 또는 Node.js (http-server)
npx http-server
```

브라우저에서 `http://localhost:8000` 접속

## 라이선스

All rights reserved. A.Storm Inc.
