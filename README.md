
```
asc-website/
├── backend/               # Flask API 서버
│   ├── app.py             # API 엔드포인트 (CORS 설정 포함)
│   └── requirements.txt   # Python 의존성 (flask, flask-cors, gunicorn)
├── frontend/              # Next.js 프론트엔드 애플리케이션
│   ├── src/
│   │   ├── app/           # Next.js App Router
│   │   │   ├── layout.tsx # 공통 레이아웃 (네비게이션 포함)
│   │   │   ├── page.tsx   # 홈페이지 (메인 네비게이션 카드)
│   │   │   ├── about/     # 동아리 소개 페이지
│   │   │   ├── board/     # 게시판 페이지
│   │   │   ├── study/     # 스터디 & 소모임 페이지
│   │   │   ├── rental/    # 물품 대여 페이지
│   │   │   └── globals.css # 글로벌 스타일
│   │   └── components/    # 재사용 가능한 컴포넌트
│   │       └── Navigation.tsx # 네비게이션 바
│   ├── public/            # 정적 파일 (이미지, 아이콘 등)
│   ├── package.json       # Node.js 의존성
│   ├── next.config.ts     # Next.js 설정
│   ├── tsconfig.json      # TypeScript 설정
│   └── postcss.config.mjs # PostCSS 설정 (Tailwind CSS)
├── Dockerfile             # Docker 컨테이너 빌드 설정
├── docker-compose.yml     # Docker Compose 설정
└── README.md              # 프로젝트 문서
```
