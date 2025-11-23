
```
asc-website/
├── backend/               # FastAPI API 서버 (고성능 비동기 서버 로직)
│   ├── app.py             # REST API 엔드포인트 정의 (Pydantic 모델 활용)
│   └── requirements.txt   # Python 의존성 관리 (fastapi, uvicorn, psycopg2 등)
├── frontend/              # Next.js 프론트엔드 애플리케이션 (TypeScript 기반 UI)
│   ├── src/
│   │   ├── app/           # Next.js App Router (5대 핵심 페이지 라우팅)
│   │   │   ├── 공통 구성 # layout.tsx, page.tsx 등 공통 레이아웃 파일
│   │   │   └── 핵심 페이지 라우팅 # /about, /board, /study, /rental 등 5대 기능 구현
│   │   └── components/    # 재사용 가능한 UI 컴포넌트
│   │       └── Navigation.tsx # 메인 네비게이션 바
│   ├── public/            # 이미지, 아이콘 등 정적 파일
│   ├── package.json       # Node.js/Next.js 의존성 관리
│   ├── next.config.ts     # Next.js 설정
│   ├── tsconfig.json      # TypeScript 컴파일러 설정 (타입 안정성 확보)
│   └── postcss.config.mjs # Tailwind CSS 설정 파일 (반응형 디자인 시스템)
├── Dockerfile             # Docker 컨테이너 빌드 정의 (Uvicorn 서버 실행)
├── docker-compose.yml     # 컨테이너 통합 실행 환경 설정 (DB: PostgreSQL 포함)
└── README.md              # 프로젝트 문서
```
