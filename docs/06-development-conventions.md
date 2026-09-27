# Development Conventions

## Commit

형식:

`type: 변경 내용`

### Type

- `feat`: 기능 추가 또는 변경
- `fix`: 버그 수정
- `refactor`: 동작 변경 없는 구조 개선
- `test`: 테스트 추가 또는 수정
- `docs`: 문서 및 정책 변경
- `chore`: 빌드, 설정, 의존성 변경

### Examples

- `feat: 예약 생성 기능 추가`
- `fix: 중복 예약 허용 문제 수정`
- `docs: 예약 취소 정책 변경`
- `test: 동시 예약 통합 테스트 추가`

### Commit Principles

- 하나의 커밋에는 하나의 변경 의도를 담는다.
- 변경 내용을 알 수 없는 메시지는 사용하지 않는다.
- 정책 변경이 구현에 영향을 주면 문서와 구현을 함께 갱신한다.

## Branch

- `feat/{feature}`
- `fix/{issue}`
- `refactor/{target}`
- `docs/{topic}`

예:

- `feat/reservation-create`
- `docs/reservation-policy`

## Pull Request

의미 있는 기능이나 정책 변경부터 PR을 사용한다.

PR에서는 다음 흐름이 보이도록 작성한다.

문제 → 정책/요구사항 → 구현 → 검증

## Definition of Done

- [ ] Acceptance Criteria를 만족한다.
- [ ] 주요 정상/예외 시나리오를 테스트했다.
- [ ] 관련 정책 문서를 갱신했다.
- [ ] 코드와 문서의 정책이 일치한다.
- [ ] PR에 변경 이유와 검증 방법을 적었다.

## Documentation Review

주요 문서는 작성 후 한 번 다시 읽는다.

- 실제로 고민하거나 결정한 내용만 남긴다.
- 사실, 수치, 기술 용어와 정책의 의미를 임의로 바꾸지 않는다.
- 같은 내용을 반복하거나 필요 이상으로 설명하지 않는다.
- 번역투나 지나치게 형식적인 표현은 자연스럽게 고친다.
- 추상적인 설명보다 실제 조건, 판단 근거, 사례를 적는다.
- 없는 근거나 판단을 나중에 만들어 붙이지 않는다.
- AI를 사용했더라도 최종 내용은 직접 확인한다.
