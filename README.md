# 포도 주문 관리

택배 발송 명단을 입력하고 엑셀로 내보내는 한 페이지짜리 도구입니다.

- 주소검색: 카카오 우편번호 서비스
- 로그인: Google (Firebase Authentication) — Firestore 규칙에 등록된 이메일만 접근 가능
- 저장: Firestore (`grape/list` 문서 하나) — 기기 간 실시간 동기화
- 백업 저장/불러오기로 JSON 파일로도 보관 가능
