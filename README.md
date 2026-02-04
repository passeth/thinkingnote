# 생각도구 (Thinking Tool)

> "생각의 외주화를 막는 생각 도구"

## 데모
<img width="1040" height="608" alt="image" src="https://github.com/user-attachments/assets/f14ed65f-a3fe-483f-a13f-c6531e66aa15" />


▶️ **[데모 영상 보기](https://www.youtube.com/watch?v=kO6PZCTbyo0)**

## 개요

생각도구는 노트에서 소재를 수집하고, 자신만의 생각을 덧붙인 후, AI의 도움으로 글을 작성하는 Obsidian 플러그인입니다. Smart Connections와 연동하여 연관 노트를 보여줍니다.

## 철학

AI가 대신 생각하는 것이 아니라, **당신이 먼저 생각**합니다:

1. **당신이** 노트를 탐색하고 읽습니다
2. **당신이** 의미 있는 문장을 선택합니다
3. **당신이** 자신만의 생각을 덧붙입니다
4. **AI는** 마지막에 정리만 도와줍니다

## 주요 기능

- **3분할 레이아웃**: 원본 노트 | 연결 노트 | 소재 노트
- **Smart Connections 연동**: 의미적으로 연관된 노트 표시
- **소재 수집**: 텍스트 선택 → 생각 추가 → Callout 형식 저장
- **AI 글 생성**: 주제 제안 → 페르소나 선택 → 글 생성
- **다양한 페르소나**: 에세이, 블로그, 학술, 트위터 스레드 스타일

## 설치 방법

### BRAT 사용 (추천)

1. [BRAT](https://github.com/TfTHacker/obsidian42-brat) 플러그인 설치
2. BRAT 설정 → "Add Beta plugin" 클릭
3. `passeth/thinkingnote` 입력
4. 설치 후 플러그인 활성화

### 수동 설치

1. [Releases](https://github.com/passeth/thinkingnote/releases)에서 `main.js`, `manifest.json`, `styles.css` 다운로드
2. `.obsidian/plugins/thinking-tool/` 폴더 생성
3. 다운로드한 파일 복사
4. Obsidian 재시작 후 플러그인 활성화

## 요구 사항

- Obsidian v1.4.0+
- [Smart Connections](https://github.com/brianpetro/obsidian-smart-connections) 플러그인 (필수)
- OpenAI 또는 Anthropic API 키 (글 생성용)

## 사용법

1. 아무 노트나 열기
2. 리본의 🧠 아이콘 클릭 (또는 명령 팔레트: "Start Thinking Session")
3. 노트를 탐색하며 수집할 텍스트 선택
4. 플로팅 버튼 "📝 소재로 추가" 클릭 → 생각 입력
5. 중앙 패널의 연결 노트 클릭하여 탐색
6. 준비되면 "Generate" 클릭하여 글 생성

## 소재 형식

소재는 Obsidian Callout 형식으로 저장됩니다:

```markdown
> [!quote] [[원본노트]]
> 선택한 텍스트
>
> **My Thought**: 이 소재에 대한 나의 생각
```

## 설정

- **AI Provider**: OpenAI 또는 Anthropic (Claude)
- **API Keys**: 글 생성을 위한 API 키
- **Material Notes Folder**: 소재 노트 저장 폴더
- **Connections Limit**: 표시할 연결 노트 수
- **Output Language**: 출력 언어 (한국어 기본)

## 명령어

- `Start Thinking Session`: 현재 노트에서 세션 시작
- `End Thinking Session`: 현재 세션 종료
- `Generate Article from Materials`: 글 생성 모달 열기

## 라이선스

MIT
