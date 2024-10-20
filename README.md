# java-calculator-precourse

## 기능 목록

---

1. 입력 받은 문자열의 커스텀 구분자 유효성 검사
   1. 커스텀 구분자가 있는 경우 커스텀 구분자를 위한 입력이 유효한지 검사
   2. 커스텀 구분자가 없는 경우 기본 구분자 반환
2. 입력 받은 문자열 계산
   1. 구분자가 커스텀이면 문자열 다듬기
   2. 구분자를 기준으로 나누고 Double 형으로 바꿀때 구분자가 아닌 다른 문자가 있으면 오류 반환
   3. 없으면 모든 값을 더해서 반환