# sc2_scv_kr — 건설로봇 (StarCraft II, 한국어)

테란 SCV 한국어 음성을 [CESP v1.0](https://openpeon.com) 이벤트 카테고리에 맞춰 묶은 사운드 팩입니다.

## 설치

```bash
peon-ping install sc2_scv_kr
```

## 카테고리별 음성

### `session.start` (별칭: `greeting`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVReady1_KR.wav` | 건설로봇 준비 완료! |
| `sounds/SCVReady2_KR.wav` | 건설로봇 준비 완료! (v2) |
| `sounds/SCVWhat5_KR.wav` | SCV 대기 중 |

### `task.acknowledge` (별칭: `acknowledge`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVYes1_KR.wav` | 시키면 해야죠. |
| `sounds/SCVYes2_KR.wav` | 이야~ 야근이다! |
| `sounds/SCVYes3_KR.wav` | 알겠습니다! |
| `sounds/SCVYes4_KR.wav` | 마음대로 하세요! |
| `sounds/SCVYes5_KR.wav` | 예, 대장! |
| `sounds/SCVYes6_KR.wav` | 그렇게 하죠! |
| `sounds/SCVYes7_KR.wav` | 갑니다! |
| `sounds/SCVYes8_KR.wav` | Roger! |

### `task.complete` (별칭: `complete`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVComplete1_KR.wav` | 작업 끝! |
| `sounds/SCVComplete2_KR.wav` | 예, 알겠다고요! |
| `sounds/SCVYes3_KR.wav` | 알겠습니다! *(수락 클립과 동일)* |

### `task.error` (별칭: `error`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVDeath1_KR.wav` | 으아! |
| `sounds/SCVDeath2_KR.wav` | 으아악! |

### `input.required` (별칭: `permission`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVWhat1_KR.wav` | 무슨 일이죠? |
| `sounds/SCVWhat4_KR.wav` | 뭔 일 있어요? |
| `sounds/SCVSurprise_KR.wav` | 으아잇! 깜짝이야! |

### `resource.limit` (별칭: `resource_limit`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVBlocked_KR.wav` | 막혔어요! |
| `sounds/SCVCantDo_KR.wav` | 안 되겠는데요? |
| `sounds/SCVPissed4_KR.wav` | 아주 훌륭하군요! |

### `user.spam` (별칭: `annoyed`)

| 파일 | 라벨 |
|------|------|
| `sounds/SCVSurprise_KR.wav` | 으아잇! 깜짝이야! |
| `sounds/SCVWhat1_KR.wav` | 무슨 일이죠? |
| `sounds/SCVWhat4_KR.wav` | 뭔 일 있어요? |
| `sounds/SCVPissed1_KR.wav` | 여긴 뭐 찍겠는데요? |
| `sounds/SCVPissed2_KR.wav` | 미친 거 아니야? |
| `sounds/SCVPissed5_KR.wav` | 이건 아니라고 봐! |
| `sounds/SCVPissed6_KR.wav` | 나 집에 갈래! |
| `sounds/SCVHelp_KR.wav` | 사람 살려! |
| `sounds/SCVPissed7_KR.wav` | 당신 마우스 정말 마음에 드는데? |

## 참고

- **고유 WAV 클립**: 27개
- `SCVYes3`는 `task.acknowledge`와 `task.complete`에서 공유
- `SCVSurprise`, `SCVWhat1`, `SCVWhat4`는 `input.required`와 `user.spam`에서 공유
- 별칭 정의는 `openpeon.json`의 `category_aliases` 참고

## 라이선스

CC-BY-NC-4.0
