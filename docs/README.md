# 해커그라운드 - 대구경북 개발자 커뮤니티

![해커그라운드 로고](images/1920x480-1.png)

## 🚀 프로젝트 소개

해커그라운드는 **대구경북 No.1 IT 실무 교육 및 네트워킹 플랫폼**입니다.

현업과 대학 교육의 간극을 메우는 실용적인 지식 공유의 장을 제공하여, 지역 청년들의 IT 역량을 강화하고 건강한 개발자 생태계를 조성합니다.

## 🎯 타겟 고객

- **대학생 (1~4학년)**: 실무 지식과 프로젝트 경험에 목마른 컴퓨터공학 및 유관 전공 학생
- **취업준비생**: 포트폴리오 강화와 네트워킹을 통해 취업 정보를 얻고 싶은 예비 개발자
- **주니어 개발자 (1~3년차)**: 새로운 기술 스택을 학습하고, 다른 개발자들과 교류하며 성장하고 싶은 현직자

## 📋 제공 서비스

### 핵심 서비스
- **핸즈온 실습**: 웹사이트 배포, Docker, ChatGPT API 활용 등 실질적인 결과물을 만드는 교육
- **세미나**: 현업 멘토의 성장 스토리, 채용 프로세스, 기술 스택 트렌드 등 인사이트 제공
- **지식콘서트**: 이직 vs 존버, 사이드 프로젝트 등 현실적인 고민을 나누는 토크쇼
- **네트워킹 파티**: 코드 리뷰 파티, 키노트 와치파티 등 가벼운 분위기의 교류 이벤트

### 대규모 이벤트 (연 1~2회)
- 지역 사회 문제 해결을 위한 미니 해커톤
- 모든 구성원이 참여하는 해커그라운드 컨퍼런스

## 🛠️ 기술 스택

이 프로토타입은 다음 기술들로 구축되었습니다:

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Design**: Noto Sans KR 폰트, 네온 그린 & 퍼플/블루 브랜드 컬러
- **배포**: GitHub Pages
- **반응형**: Mobile-First 디자인

## 🎨 브랜드 컬러

- **Primary Green**: #00FF41 (네온 그린)
- **Secondary Green**: #39FF14
- **Primary Purple**: #6B46C1
- **Secondary Purple**: #8B5CF6
- **Primary Blue**: #3B82F6
- **Background**: #000000 (다크 배경)

## 📁 프로젝트 구조

```
docs/
├── index.html              # 메인 페이지
├── css/
│   └── style.css          # 메인 스타일시트
├── js/
│   └── main.js            # JavaScript 인터랙션
├── images/                # 브랜드 이미지 및 캐릭터
│   ├── 1920x480-1.png    # 로고 이미지
│   ├── 1920x960-1.png    # 히어로 배너
│   └── [해커그라운드] 캐릭터-*.png  # 브랜드 캐릭터들
└── events/               # 이벤트 상세 페이지
    ├── docker-workshop.html
    ├── growth-story.html
    └── networking-party.html
```

## 🌟 주요 기능

### 메인 페이지
- 브랜드 캐릭터가 떠다니는 히어로 섹션
- 인터랙티브 월간 캘린더 (더미 이벤트 데이터 포함)
- 이벤트 카드 그리드 레이아웃
- 반응형 네비게이션

### 이벤트 상세 페이지
- **Docker 워크샵**: 핸즈온 실습 형태의 교육 프로그램
- **성장 스토리 세미나**: 현업 멘토의 경험 공유
- **코드 리뷰 파티**: 치맥과 함께하는 네트워킹 이벤트

### JavaScript 인터랙션
- 모바일 햄버거 메뉴
- 캐릭터 플로팅 애니메이션
- 스크롤 이벤트 기반 네비게이션 변화
- 인터랙티브 캘린더 (월 이동, 이벤트 표시)

## 🚀 GitHub Pages 배포

이 프로젝트는 GitHub Pages를 통해 자동 배포됩니다.

### 배포 설정
1. Repository Settings > Pages
2. Source: Deploy from a branch
3. Branch: `main` / `docs` folder
4. 커밋 후 자동 빌드 및 배포

### 로컬 개발
```bash
# 프로젝트 클론
git clone [repository-url]

# docs 폴더로 이동
cd docs

# 로컬 서버 실행 (Python 사용시)
python -m http.server 8000

# 브라우저에서 확인
open http://localhost:8000
```

## 📞 연락처

- **GitHub**: [hackersground-kr](https://github.com/hackersground-kr)
- **YouTube**: [@hackersground-kr](https://www.youtube.com/@hackersground-kr)
- **Email**: contact@hackersground.kr

## 📄 라이선스

© 2024 해커그라운드(HackerGround). All rights reserved.

---

**이 프로토타입은 동업자에게 비전과 서비스를 효과적으로 전달하기 위해 제작되었습니다.**