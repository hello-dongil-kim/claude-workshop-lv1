# Changelog

이 워크샵의 주요 변경 이력. 형식은 [Keep a Changelog](https://keepachangelog.com/) 기반. 시리즈 공통 표준은 제작자 내부 문서 `workshop-series-standard`를 따른다.

## [2026-06-14] — 9+ 품질 개선

### Added (추가)

- 모든 파트 EXECUTE에 `✅ 이렇게 되면 성공` 성공 기준(P1)
- 각 파트 QUIZ에 적용형(시나리오) 문항 + 오답 이유 해설(P3)
- 모델·설치 등 버전 의존 정보용 변동 정보 박스(P2, Part 2·9)
- 세션 내 진도 추적·적응형 건너뛰기·오답 remediation 규칙(P4, 앱 환경에 맞게 적응)
- README 제작자 푸터, `LICENSE`(All rights reserved, 개인 학습 이용 허용), `.markdownlint.jsonc`

### Changed (변경)

- 매체 일관성: Claude Code 전용 기능(슬래시 명령·Plan Mode·패널)에 "Lv.2에서 실습" 라벨 부착
- Part 2 중복 설득 표를 핵심으로 통합(정보 손실 없이 슬림화)
- macOS/Windows 경로·단축키 병기 보강
- 무출처 정량 주장에 "사례 기준" 라벨, 사내 표현을 "조직의 IT 정책에 따라"로 중립화

### Fixed (수정)

- 모델 컨텍스트표 갱신(Opus 4.8/Sonnet 4.6 1M, Haiku 4.5 200K) + 가격 "약 5배"
- 데이터 정책 단정을 "공식 정책 확인" 완충으로
- npm 설치를 "Deprecated" → "정상 지원이나 네이티브 권장"으로 정정
- 앱에서 작동하지 않던 Part 3·4 EXECUTE를 앱에서 되는 과업으로 재정의
