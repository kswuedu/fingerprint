FINGER IQ FINAL v7.4 MOBILE ANALYSIS FIX

모바일 분석 오류 수정:
- 결과지에서 이미 삭제한 과거 DOM(TOP3/손가락별/중복 점수)에 접근하던 렌더링 로직 완전 제거
- 현재 존재하는 상세 리포트만 렌더링하도록 renderResult 단순화
- ranking, learningStyle, 관계 상세 데이터가 일부 누락되어도 전체 결과 생성이 중단되지 않도록 방어
- 기존 v7.3 PDF 모바일 저장 수정 유지
- 비밀번호 finger1004 유지
