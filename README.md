# 사망보험금 유동화 계산기

정적 HTML 한 파일로 실행되는 6단계 참고용 계산기입니다.

## 기능
1. 제도 설명
2. 리서치 요약
3. 가입 계약 대상 여부 확인
4. 예상 수령액 계산 및 사망 시점별 비교
5. 결과 보고서
6. 신청 전 참고 조언

## GitHub Pages에서 배포
이 저장소의 Settings → Pages → Build and deployment에서 Source를 **Deploy from a branch**로 설정하고,
Branch **main**, Folder **/(root)**를 선택한 다음 Save합니다.

예상 사이트 주소:
https://kimjindol2025.github.io/insurance-liquidity-calculator/

배포 완료 후 실제 접속 가능한지 별도 확인해야 합니다.

## 주의
이 계산기 출력은 상품별 해약환급금과 보험사 비교안내표를 대신하지 않는 **참고용 추정**입니다.
대상 여부, 지급액, 사망보험금 감액, 과세 여부 등은 가입 보험사의 약관과 공식 안내로 반드시 확인하세요.
개인정보를 별도로 수집·저장하도록 구현하지 않았습니다.

## 배포 구조
- `index.html`: CSS와 JavaScript가 내장된 계산기
- `.nojekyll`: GitHub Pages Jekyll 처리 비활성화

GitHub Pages는 GitHub에서 제공하는 호스팅이며 사용자 소유 191 서버로 배포하는 것은 아닙니다.
