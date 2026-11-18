# 김은열

**데이터·AI 소프트웨어 엔지니어**

데이터를 모으고 다듬어 서비스에 연결하는 일을 해왔습니다. 공공·제조 분야에서 데이터 파이프라인과 AI 운영 백엔드를 만들고, 운영 중 생기는 지연과 오류를 살피며 일했습니다. 지금은 파이프라인의 실행 결과와 데이터 품질을 함께 확인하는 사내 플랫폼을 만들고 있습니다.

[포트폴리오](https://kimeunyeol.github.io/) · [이력서](https://kimeunyeol.github.io/resume.html) · [한 페이지 요약](https://kimeunyeol.github.io/portfolio/) · [업무 기록](https://kimeunyeol.github.io/work/)

## 다루는 기술

| 분야 | 기술 |
| --- | --- |
| 데이터 파이프라인 | Airflow · NiFi · Hive · S3 · Glue · PySpark · Parquet · Athena |
| AI 운영 백엔드 | Python · Kafka · Redis · Docker · SOAP 연계 |
| 플랫폼 개발 | FastAPI · Pydantic · SQLite · PostgreSQL · Flask |
| 웹 | TypeScript · React · Vue · Vite · Supabase |
| 인프라·운영 | Docker · GitLab CI/CD · GitLab Runner · AWS (EC2·S3) |
| 분석·시뮬레이션 | OR-Tools · SQL · 데이터 정제 |

## 대표 프로젝트

**[데이터 생산 통제 플랫폼](https://kimeunyeol.github.io/projects/data-production-platform/)** · 진행 중 · 아키텍처 설계·개발  
파이프라인 명세, 실행 결과, 품질 검사와 증거 이력을 연결하는 사내 플랫폼입니다. FastAPI·SQLite로 로컬 MVP를 만들고 정상·품질 실패·증거 누락 시나리오를 검증했습니다.

**[제조 물류 운송 최적화 시뮬레이션](https://kimeunyeol.github.io/projects/transport-optimization/)** · 2026.07 · 현장대리인, 분석·개발  
운송 실적을 정제하고 OR-Tools로 차량·시간·거리 제약을 반영한 시뮬레이션을 개발했습니다. AS-IS와 TO-BE의 차량 수·운행 횟수·물동량을 비교했습니다.

**[데이터레이크 개발환경·운영 지원](https://kimeunyeol.github.io/projects/data-lake-environment-support/)** · 2025.12–2026.01 · 구축안 작성, CI/CD 장애 대응  
운영 구성을 축소한 Airflow 개발환경 구축안을 작성하고, GitLab CI/CD·Runner 장애를 조치해 개발·배포를 복구했습니다.

**[분석 인프라 전환 검토](https://kimeunyeol.github.io/projects/infrastructure-transition/)** · 2025.01–2025.07 · 응용 소프트웨어 개발  
Cloud의 S3 적재 흐름을 Private IDC 공유 스토리지로 옮길 때의 파일 경로, Airflow 메타데이터·로그 저장 위치, ETL 작업 분할 항목을 검토했습니다.

**[제조 데이터 레이크 고도화](https://kimeunyeol.github.io/projects/data-lake-upgrade/)** · 2024.03–2024.10 · 데이터 레이크 고도화  
Airflow 수집 → S3 적재 → Glue·PySpark Parquet 변환 → Athena 조회 흐름에 참여했습니다. 테이블별 전체·파티션·병합 갱신 방식을 구분하고 원천과 조회 건수를 대조했습니다.

**[제조 AI 운영 백엔드 구축·확장](https://kimeunyeol.github.io/projects/manufacturing-ai-backend/)** · 2021–2023 · 백엔드 개발, 외부 데이터 연계  
SOAP 원천 수집 → Kafka 전달 → Redis 추론 데이터 → S3 이력 저장 흐름을 개발하고, 모델별 전처리·추론 컨테이너 확장에 참여했습니다.

## 개인 프로젝트

**[음악동아리 홈페이지](https://gain-music-club.vercel.app)** — 소개·공지·일정·공연·활동 기록을 보여주는 공개 홈페이지와 운영자용 관리 화면. `React` `Vue` `TypeScript` `Vite` · [코드](https://github.com/KimEunYeol/gain)

**[랩타일링크](https://reptilelink.netlify.app/)** — 파충류 개체 정보와 사진, 날짜별 체중·성장 기록, 피딩 일정을 관리하고 공개 프로필로 공유하는 웹 서비스. `React` `TypeScript` `Vite` `Supabase` `Netlify`

## 경력·자격

- 응용 소프트웨어 개발 2020.06–재직 중
- 참여 분야: 공공 빅데이터·재정 데이터 분석 플랫폼, 제조 AI 운영 백엔드, 제조 데이터 레이크, 분석 인프라 전환, 물류 운송 최적화
- 컴퓨터공학 학사 · 정보처리기사 · SQL 개발자(SQLD)

---

프로젝트마다 맡은 일과 사용한 기술, 작업하며 고민한 내용을 [포트폴리오](https://kimeunyeol.github.io/)에 정리해 두었습니다.
