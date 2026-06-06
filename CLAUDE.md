# EasyTech Teamwork — Claude Code 작업 원칙

## 핵심 원칙
코드 수정 작업 시 반드시 아래 순서를 지킨다:
1. 수정 대상 함수의 전체 코드를 먼저 읽는다 (view 또는 read 도구 사용)
2. 관련 함수와 DOM ID 연결을 확인한다
3. 확인된 실제 코드 기준으로 str_replace를 작성한다
4. 절대 기억이나 추측으로 old 텍스트를 작성하지 않는다

## 배포
- Netlify 수동 drag-and-drop (index.html 단일 파일)
- 사이트: easytechteamwork.netlify.app

## 스키마
- Supabase daily_logs 테이블
- 주요 컬럼: id, member_name, log_date, meetings, others, attachments, report, tasks(jsonb)
