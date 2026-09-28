# Job Hunt Agent

## 목적
채용 공고를 검색하고, 내 이력서와 비교해 적합도를 평가하고, 지원 현황을 관리하는 도구 사용 AI 에이전트.
GitHub 포트폴리오용 프로젝트이므로 코드 가독성과 문서화를 중요하게 여긴다.

## 기술 스택
- Python, uv로 의존성 관리
- Anthropic Python SDK (tool use)
- httpx로 Greenhouse 공개 Job Board API 호출
- SQLite로 지원 현황 저장
- pytest로 테스트

## 규칙
- API 키는 .env에만 두고 절대 커밋하지 않는다
- 에이전트 루프에는 최대 반복 횟수 제한을 둔다
- 새 기능마다 테스트를 함께 작성한다
- 나는 학습 중이므로 새로운 개념이 나오면 한국어로 짧게 설명해준다
- 한 번에 큰 변경을 하지 말고 단계별로 진행하며 매 단계 확인을 받는다
- 커밋 메시지는 영어로, 한 줄 요약 형식으로 작성한다

## 환경
- OSU ENGR flip 서버, 공용 서버라 sudo 권한 없음
- GitHub 원격 저장소는 github-personal SSH 별명으로 연결 (계정 Hwan4234)
