FINGER IQ FINAL v7.5 PDF REPORT FIX

이번 수정의 핵심:
- 기존 사이트 화면 자체를 window.print() 하는 방식을 중단
- PDF 버튼을 누르면 현재 결과지를 독립적인 인쇄 전용 문서(iframe)로 복사
- 앱의 모바일 화면 hidden/active CSS와 완전히 분리
- 현재 성향의 accent / accent-soft / accent-deep 컬러를 계산하여 PDF 문서에 직접 적용
- 결과 내용과 컬러가 PDF 미리보기에 함께 나오도록 수정
- 기존 모바일 분석 v7.4 수정 유지
- 비밀번호 finger1004 유지

모바일:
검사 완료 → A4 결과지 PDF로 저장 → 휴대폰 인쇄 화면에서 'PDF로 저장' 선택
