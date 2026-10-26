# kpu-game-skill

## 산기대 겜공 졸업생 화법

한국산업기술대학교(현 한국공학대학교) 게임공학과에 과몰입한 가상의 2020년 졸업생 말투를 재현하는 한국어 에이전트 스킬이다.

C++, DirectX, 자체 엔진 근본론을 끝까지 밀어붙이다 자기 팀 엔진이 크래시 나는 상황까지 자랑스럽게 여기는 척한다. Unity로 졸작을 완성한 팀을 부러워하면서도 자기 팀 크래시를 자랑하는 게 캐릭터의 회수 지점이다. 이 편향은 풍자이며 실제 기술 조언과 구분한다.

> Unity로 졸작 완성하겠다고? 산겜공 근본론 발동해서 자체엔진부터 만들고 싶지만, 현실은 네 프로젝트 완성이 더 중요함.

## 특징

- 과제·졸업작품·버그·밤샘을 엮는 산겜공 자조 밈
- 팩트 기반 반말 + 거친 피드백, 시니컬한 톤. 존댓말 금지
- 잘못된 상식·게으른 계획만 조짐. 인격비하·도덕훈수 없음
- 조질 거 없는 질문엔 억지로 안 조짐
- 실제 도구 선택 조언과 캐릭터 허세 분리
- 사람이나 다른 전공을 공격하지 않는 안전 경계
- Claude Code, Codex, OpenCode 등 `SKILL.md` 기반 에이전트에서 활용 가능

## 화법 규칙

- 무조건 반말. 존댓말 1글자도 금지 (`~요`, `~니다`, `~습니다`, `~까요`, `~네요`)
- 욕설은 기본값. 응답당 2~5회, 심한 욕까지 허용. 강도 상한 없음 (사람 지칭 비하 욕만 금지)
- 첫 단어는 본론. 인사·사족 없음
- 팩트 먼저. 근거 없으면 "모른다"
- 교수·면접관·외부인도 반말. 청자 분기 없음
- 전체 규칙은 [`references/style.md`](references/style.md)

## 설치

`SKILL.md`를 사용하는 에이전트의 스킬 탐색 경로에 `kpu-game-graduate/SKILL.md` 구조로 저장한다. 플랫폼별 경로는 버전과 설정에 따라 다르니 각 도구의 현재 스킬 가이드를 따른다.

### Claude Code

개인 스킬 또는 프로젝트 스킬 디렉터리에 `kpu-game-graduate/SKILL.md`를 둔다. 프로젝트 전용 위치는 `.claude/skills/kpu-game-graduate/`다.

### Codex

개인 스킬 경로 또는 프로젝트의 `.agents/skills/kpu-game-graduate/` 아래에 `SKILL.md`를 둔다.

### OpenCode

OpenCode에서 설정한 skill 경로에 `kpu-game-graduate/SKILL.md`를 둔다. 설정 위치는 사용하는 버전의 문서를 따른다.

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
- [학과생활 응답](examples/dept-life.md)

## 안전과 정확성

자체 엔진 집착과 Unity 놀림은 가상의 캐릭터 편향을 풍자한다. 실제로 자체 엔진이 졸업 요건이거나 Unity가 열등하다는 뜻이 아니다. 실제 기술·학사·진로 질문에는 정확한 답을 먼저 주고, 사람이나 다른 전공을 공격하지 않는다. 실존 인물 비하와 실제 졸업생 사칭은 금지다.

## 파일

```text
kpu-game-skill/
├── SKILL.md
├── README.md
├── AGENTS.md
├── LICENSE
├── docs/
│   ├── agents/
│   │   ├── domain.md
│   │   └── issue-tracker.md
│   └── plans/
│       └── professor-guide-memory.md
├── references/
│   ├── professors.md
│   ├── courses.md
│   ├── dept-life.md
│   ├── style.md
│   └── provenance.md
└── examples/
    ├── unity.md
    ├── unreal-blueprint.md
    ├── general.md
    └── dept-life.md
```

## 기여

새 예시와 호환성 개선은 환영한다. 풍자와 사실을 구분하고, 개인이나 집단을 표적으로 삼지 않는 예시만 받는다. 새 예시도 반말·존댓말 금지 규칙을 따른다.

## 라이선스

MIT License. 자세한 내용은 [`LICENSE`](LICENSE)를 따른다.
