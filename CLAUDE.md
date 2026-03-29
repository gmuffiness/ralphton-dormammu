# Project Instructions

## Environment Variables

작업 시작 시 반드시 `.env` 파일을 로드하여 환경변수를 셸에 적용할 것:

```bash
export $(grep -v '^#' .env | xargs)
```

이 프로젝트의 `.env`에는 `GOOGLE_API_KEY`, `OPENAI_API_KEY` 등 API 키가 포함되어 있으며, 이미지 생성 등 외부 API 호출 시 필요하다.
