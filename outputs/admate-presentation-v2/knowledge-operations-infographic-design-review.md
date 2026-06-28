# AdMate Knowledge Operations Infographic Design Review

작성일: 2026-06-28
대상 이미지: `판단_근거_보존_지식_플랫폼.png`
검토 역할: AdMate Design Director
목적: NotebookLM 생성 인포그래픽을 임원 보고용 1장 이미지로 사용하기 전, 오탈자, 용어, 메시지 정확도, 정보 밀도, 시각 위계를 정리한다.

## 1. 핵심 평가

현재 인포그래픽의 큰 구조는 유지 가능하다. `업무 신호 -> 판단 근거 -> 조치 후보 -> 사용자 반응 -> 승인된 지식`으로 이어지는 방향은 AdMate 발표자료 v2의 핵심 메시지와 맞다.

다만 임원 보고용으로 쓰기에는 한글 오탈자와 제품명 오류가 눈에 띄고, 일부 표현이 자동 판단, 자동 학습, 자동 집행처럼 오해될 수 있다. 또한 각 박스의 설명문이 길어 슬라이드나 작은 화면에서는 읽기 어렵다.

최종 이미지는 "예쁜 AI 흐름도"보다 "사람 승인 아래 판단 근거가 조직 지식으로 남는 운영 구조"로 보여야 한다.

## 2. 반드시 고칠 오탈자와 용어

아래 항목은 최종 이미지 반영 전 반드시 수정한다.

| 현재 표현 | 수정 표현 | 비고 |
|---|---|---|
| `Openciaw` | `Openclaw` | 제품명 오류 |
| `매일과 요청 등` | `메일과 요청 등` | 한글 오탈자 |
| `파편화원 업무 신호` 또는 유사 표현 | `파편화된 업무 신호` | 자연스러운 한국어로 수정 |
| `시적 증빙` | `시각적 증빙` | 의미 오류 |
| `승인 전 데이터는 'Candidate'로 달리` | `승인 전 데이터는 Candidate로 분류` | 문장 오류 및 용어 정리 |
| `Lens (필름)` | `Lens (증빙 캡처)` 또는 `Lens (시각 증빙)` | AdMate 제품 역할에 맞게 수정 |
| `Foresight (예측)` | `Foresight (예측·벤치마크)` | 제품 가치 보강 |
| `승인 지식` | `승인된 지식` 또는 `Approved Knowledge` 병기 | 전체 용어 통일 |

권장 용어:

- `Learning Candidate`: 승인 전 학습 후보
- `Approved Knowledge`: 승인된 지식
- `Human Approval Gate`: 사람 승인 게이트
- `Slack`: 알림/응답 채널
- `Openclaw`: 실행 요청과 사용자 반응 회수 흐름

## 3. 권장 제목과 상단 카피

제목:

```text
AdMate: 판단 근거를 보존하는 지식 운영 플랫폼
```

부제:

```text
AI가 판단을 대신하지 않고, 업무 신호 -> 판단 근거 -> 조치 후보 -> 사용자 반응 -> 승인된 지식의 흐름을 보존합니다.
```

부제는 2줄 이내로 유지한다. 더 긴 설명은 발표자 노트로 분리한다.

## 4. 메시지 정확도 수정 지시

1. AdMate가 자동 판단, 자동 학습, 자동 집행하는 것처럼 보이면 안 된다.
2. `조치 후보`, `사용자 반응`, `Learning Candidate`, `Approved Knowledge` 사이에 사람 승인 경계를 명확히 표시한다.
3. Slack은 판단 주체가 아니라 `알림/응답 채널`로만 표현한다.
4. Openclaw는 승인 없는 실행 엔진처럼 보이지 않게 하고, `조치 후보 전달 및 반응 회수` 역할로 제한한다.
5. Hermes는 자동으로 지식을 확정하는 주체가 아니라, `사람이 승인한 기준만 Approved Knowledge로 축적`하는 흐름으로 표현한다.
6. AI Venture Lab과 AI News Input은 메인 운영 루프가 아니라 `Future/Planned`, `장기 확장`, `Long-term extension`으로 표시한다.

권장 박스 카피:

| 영역 | 권장 카피 |
|---|---|
| Candidate 박스 | `승인 전 데이터는 Candidate로 분류` |
| Hermes 박스 | `사람이 승인한 기준만 Approved Knowledge로 축적` |
| Slack/Openclaw 박스 | `조치 후보를 알리고 사용자 반응을 회수` |
| AI Venture Lab 박스 | `축적된 지식과 AI 뉴스 신호를 신규 실험 후보로 연결` |

## 5. 정보 밀도 조정 지시

현재 박스별 설명문은 슬라이드 축소 상태에서 읽기 어렵다. 최종본은 다음 기준으로 줄인다.

- 각 박스 안 설명은 1~2줄만 사용한다.
- 박스 안에는 역할명과 핵심 기능만 둔다.
- 세부 설명, 배경, 예시는 발표자 노트로 이동한다.
- 상단 부제는 2줄 이내로 제한한다.
- 1단계/2단계 제목은 유지하되, 박스 내부 문장 수를 줄여 흐름이 먼저 보이게 한다.

권장 정보 구조:

```text
1단계: 파편화된 업무 신호를 판단 근거로 정리
메일과 요청 등 -> Compass / Sentinel / Lens / Foresight -> 조치 후보

2단계: 사용자 반응을 승인된 지식으로 축적
조치 후보 -> Slack/Openclaw -> 사용자 반응 -> Candidate -> Human Approval Gate -> Hermes -> Approved Knowledge

장기 확장:
Approved Knowledge + AI News Input -> AI Venture Lab -> 신규 실험 후보
```

## 6. 시각 위계와 레이아웃 수정 지시

### Human Approval Gate

- `Human Approval Gate`는 핵심이지만 너무 큰 독립 아이콘처럼 보이면 운영 흐름이 끊긴다.
- 중앙 연결점 또는 승인 단계 라벨로 정리한다.
- `Candidate -> Human Approval Gate -> Approved Knowledge`의 경계가 가장 선명하게 보이게 한다.

### Candidate와 Hermes 연결

2단계 하단 흐름은 아래 방향으로 명확히 표현한다.

```text
사용자 반응 -> Learning Candidate -> Human Approval Gate -> Hermes -> Approved Knowledge
```

화살표 방향이 양방향처럼 보이거나 자동 순환처럼 보이면 안 된다.

### Slack/Openclaw

- Slack은 `알림/응답 채널`로 표시한다.
- Openclaw는 `조치 후보 전달`, `응답 회수`, `승인 흐름 연결` 수준으로 표현한다.
- Slack/Openclaw가 최종 판단 또는 자동 집행 주체처럼 보이지 않게 한다.

### AI Venture Lab

- 메인 운영 루프와 색 또는 선 스타일을 구분한다.
- `장기 확장 루프`, `Future/Planned`, `Long-term extension` 같은 라벨을 붙인다.
- 메인 운영 루프와 같은 중요도로 보이면 안 된다.

### NotebookLM 워터마크

- NotebookLM 워터마크가 남는다면 최종 임원 보고용 이미지에서 제거 가능 여부를 확인한다.
- 제거가 불가하거나 라이선스/브랜드 리스크가 있으면 직접 제작본으로 대체한다.

## 7. NotebookLM 또는 제작자 재생성 프롬프트 초안

아래 프롬프트는 NotebookLM 또는 디자인 제작자에게 전달할 수 있는 초안이다.

```text
AdMate 인포그래픽을 임원 보고용 1장 이미지로 다시 정리해 주세요.

제목은 "AdMate: 판단 근거를 보존하는 지식 운영 플랫폼"으로 사용합니다.

부제는 "AI가 판단을 대신하지 않고, 업무 신호 -> 판단 근거 -> 조치 후보 -> 사용자 반응 -> 승인된 지식의 흐름을 보존합니다."로 사용하되 2줄 이내로 배치합니다.

전체 구조는 유지하되, 각 박스 설명은 1~2줄로 줄여 주세요. 슬라이드 축소 상태에서도 흐름이 먼저 보이게 해 주세요.

1단계는 "파편화된 업무 신호를 판단 근거로 정리"입니다. 메일과 요청 등에서 들어온 업무 신호가 Compass, Sentinel, Lens, Foresight를 통해 판단 근거와 조치 후보로 정리되는 흐름을 보여 주세요.

제품명은 다음처럼 표기해 주세요.
- Compass (정책·근거)
- Sentinel (위험 신호·검토 기준)
- Lens (증빙 캡처) 또는 Lens (시각 증빙)
- Foresight (예측·벤치마크)

2단계는 "사용자 반응을 승인된 지식으로 축적"입니다. 조치 후보가 Slack/Openclaw를 통해 알림과 응답으로 이어지고, 사용자 반응이 Learning Candidate로 분류된 뒤, Human Approval Gate를 거쳐 Hermes에서 Approved Knowledge로 축적되는 흐름을 보여 주세요.

중요한 메시지는 다음입니다.
- AdMate는 자동 판단하지 않습니다.
- AdMate는 자동 학습이나 승인 없는 자동 집행처럼 보이면 안 됩니다.
- Slack은 판단 주체가 아니라 알림/응답 채널입니다.
- 승인 전 데이터는 Candidate로 분류합니다.
- 사람이 승인한 기준만 Approved Knowledge로 축적합니다.

AI Venture Lab과 AI News Input은 메인 운영 루프가 아니라 Future/Planned 또는 장기 확장 영역으로 구분해 주세요. 색상이나 선 스타일을 메인 루프와 다르게 처리해 "장기 확장 루프"로 보이게 해 주세요.

반드시 아래 오탈자를 수정해 주세요.
- Openciaw -> Openclaw
- 매일과 요청 등 -> 메일과 요청 등
- 파편화원 업무 신호 -> 파편화된 업무 신호
- 시적 증빙 -> 시각적 증빙
- 승인 전 데이터는 'Candidate'로 달리 -> 승인 전 데이터는 Candidate로 분류
- Lens (필름) -> Lens (증빙 캡처) 또는 Lens (시각 증빙)
- Foresight (예측) -> Foresight (예측·벤치마크)
- 승인 지식 -> 승인된 지식 또는 Approved Knowledge

최종 이미지는 차분한 운영 콘솔 톤으로 구성하고, 과장된 AI 자동화 느낌보다 승인, 기록, 감사, 지식 축적의 흐름이 먼저 보이게 해 주세요.
```

## 8. 남은 리스크

- NotebookLM 생성 이미지에 워터마크가 남으면 임원 보고용 최종본으로 부적합할 수 있다.
- 박스 설명이 길게 유지되면 PPTX에 삽입했을 때 텍스트가 읽히지 않을 가능성이 높다.
- `AI Venture Lab`이 메인 루프와 같은 색/굵기로 표현되면 현재 운영 범위처럼 오해될 수 있다.
- `Approved Knowledge` 경계가 약하면 AdMate가 자동 학습하는 것처럼 보일 수 있다.
- Slack/Openclaw가 크게 강조되면 승인 없는 실행 또는 자동 조치처럼 오해될 수 있다.

## 9. COMMANDER_HANDOFF

- 핵심 평가: 구조는 유지 가능하지만, 임원 보고용으로는 오탈자, 용어 통일, 승인 경계, 정보 밀도 조정이 필요하다.
- 반드시 고칠 오탈자: `Openciaw`, `매일과 요청 등`, `파편화원 업무 신호`, `시적 증빙`, `승인 전 데이터는 'Candidate'로 달리`, `Lens (필름)`, `Foresight (예측)`, `승인 지식`.
- 메시지/레이아웃 수정 지시: 자동 판단/자동 학습/자동 집행처럼 보이지 않게 하고, `사용자 반응 -> Candidate -> Human Approval Gate -> Hermes -> Approved Knowledge` 흐름을 명확히 한다. AI Venture Lab은 장기 확장 루프로 분리한다.
- NotebookLM에 다시 넣을 프롬프트 초안: 본 문서 7장 문안을 사용한다.
- 남은 리스크: NotebookLM 워터마크, 긴 박스 설명, AI Venture Lab의 현재 범위 오해, Approved Knowledge 승인 경계 약화, Slack/Openclaw 자동 집행 오해.
