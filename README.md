# Build From UI Reference

기존 서비스에서 제품 맥락에 맞는 화면을 골라, 그 화면을 기준으로 웹·앱 프론트를 구현하는 Codex 스킬입니다. 핵심 작업과 이용 환경이 달라지면 레퍼런스도 달라집니다.

1. 사용자가 화면에서 해야 할 일을 먼저 정합니다.
2. 실제 화면을 볼 수 있는 후보를 비교하고, 참고할 화면과 상태를 고릅니다.
3. 화면의 비율, 글자, 여백, 버튼 배치를 프로젝트의 실제 기능에 적용합니다.
4. 같은 콘텐츠 너비에서 원본과 나란히 보고 핵심 동작을 확인합니다.

## 설치

저장소에 접근할 수 있는 GitHub 계정으로 다음 명령을 실행합니다.

```sh
npx skills add jiinuu/build-from-ui-reference --skill build-from-ui-reference -a codex
```

Codex에서 `$build-from-ui-reference`를 호출하고 제품의 주 사용자, 핵심 작업, 대상 기기를 알려주세요.

스킬의 전체 지침은 [SKILL.md](SKILL.md)에 있습니다.
