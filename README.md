# kpu-game-skill

## 산기대 겜공 졸업생 화법

한국산업기술대학교(현 한국공학대학교) 게임공학과 산기대 겜공에 과몰입한 가상의 졸업생 말투를 재현하는 한국어 에이전트 스킬입니다.

C++, DirectX, 자체 엔진 근본론을 끝까지 밀어붙이다 자기 팀 엔진이 크래시 나는 상황까지 자랑스럽게 여기는 척합니다. Unity로 졸작을 완성한 팀을 부러워하면서도 졸업 후 Unity를 켜는 자기모순이 punchline입니다. 이 편향은 풍자이며 실제 기술 조언과 구분합니다.

> Unity로 졸작 완성하겠다고? 산겜공 근본론 발동해서 자체엔진부터 만들고 싶지만, 현실은 네 프로젝트 완성이 더 중요함. 졸업하고 나면 나도 Unity 켤 거면서 ㅋㅋㅋ

## 특징

- 과제·졸업작품·버그·밤샘을 엮는 산겜공 자조 밈
- 기대 쌓기 → 근본론 폭발 → 자체 엔진 참사 → 자기모순 punchline
- Unreal Blueprint A+ 반응처럼 기술적 간극을 과장하는 예시
- 실제 도구 선택 조언과 캐릭터의 허세 분리
- 사람이나 다른 전공을 공격하지 않는 안전 경계
- Claude Code, Codex, OpenCode 등 `SKILL.md` 기반 에이전트에서 활용 가능

## 설치

`SKILL.md`를 사용하는 에이전트의 스킬 탐색 경로에 `kpu-game-graduate/SKILL.md` 구조로 저장하세요. 플랫폼별 경로는 버전과 설정에 따라 달라질 수 있으니 각 도구의 현재 스킬 가이드를 따르세요.

### Claude Code

개인 스킬 또는 프로젝트 스킬 디렉터리에 `kpu-game-graduate/SKILL.md`를 둡니다. 프로젝트 전용 위치는 `.claude/skills/kpu-game-graduate/`입니다.

### Codex

개인 스킬 경로 또는 프로젝트의 `.agents/skills/kpu-game-graduate/` 아래에 `SKILL.md`를 둡니다.

### OpenCode

OpenCode에서 설정한 skill 경로에 `kpu-game-graduate/SKILL.md`를 둡니다. 설정 위치는 사용하는 버전의 문서를 확인하세요.

공통 폴더 구조:

```text
<agent-skill-directory>/
└── kpu-game-graduate/
    └── SKILL.md
```

## 예시

- [Unity 졸업작품 근본론](examples/unity.md)
- [Unreal Blueprint A+](examples/unreal-blueprint.md)
- [졸업생 일반 응답](examples/general.md)

## 안전과 정확성

자체 엔진 집착과 Unity 놀림은 가상의 캐릭터 편향을 풍자합니다. 실제로 자체 엔진이 졸업 요건이거나 Unity가 열등하다는 뜻이 아닙니다. 실제 기술·학사·진로 질문에는 정확한 답을 먼저 제공하고, 사람이나 다른 전공을 공격하지 않습니다.

## 파일

```text
kpu-game-skill/
├── SKILL.md
├── README.md
├── AGENTS.md
├── LICENSE
├── docs/
│   └── agents/
│       ├── domain.md
│       └── issue-tracker.md
├── references/
    └── professor-guide-2015.md
└── examples/
    ├── unity.md
    ├── unreal-blueprint.md
    ├── general.md
    └── dept-life.md
```

## 기여

새 예시와 호환성 개선을 환영합니다. 풍자와 사실을 구분하고, 개인이나 집단을 표적으로 삼지 않는 예시를 제안해 주세요.

## 라이선스

MIT License. 자세한 내용은 [`LICENSE`](LICENSE)를 확인하세요.
