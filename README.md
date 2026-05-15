# KU Codex Pet

Codex 안에서 만나는 작은 KU.

건국대학교 마스코트 KU를 좋아하는 마음으로 만든 비공식 Codex 커스텀 펫입니다. Makersfarm에서 애교심과 팬심을 담아 만들었습니다.

> 이 프로젝트는 비공식 팬 프로젝트입니다. 건국대학교 또는 공식 마스코트 운영 주체의 공식 배포물이 아닙니다.

## Preview

| idle | waving | jumping |
|---|---|---|
| ![idle](./assets/preview/idle.gif) | ![waving](./assets/preview/waving.gif) | ![jumping](./assets/preview/jumping.gif) |

| running | review | failed |
|---|---|---|
| ![running](./assets/preview/running.gif) | ![review](./assets/preview/review.gif) | ![failed](./assets/preview/failed.gif) |

<details>
<summary>모든 움직임 보기</summary>

| running-right | running-left | waiting |
|---|---|---|
| ![running-right](./assets/preview/running-right.gif) | ![running-left](./assets/preview/running-left.gif) | ![waiting](./assets/preview/waiting.gif) |

</details>

## AI Agent Installation Instructions

이 저장소의 `ku/` 디렉터리를 사용자의 Codex pets 디렉터리로 복사하세요.

설치 대상 경로:

- Windows: `%USERPROFILE%\.codex\pets\ku`
- macOS/Linux: `$HOME/.codex/pets/ku`

설치 후 다음 파일이 존재해야 합니다.

- `.codex/pets/ku/pet.json`
- `.codex/pets/ku/spritesheet.webp`

이미 같은 경로가 있다면 기존 `ku` 폴더를 백업하거나 교체하세요. 설치가 끝나면 Codex를 재시작하세요.

README 미리보기용 GIF는 `assets/preview/`에 있으며, 실제 Codex 설치에는 `ku/pet.json`과 `ku/spritesheet.webp`만 필요합니다.

## Included Files

```txt
ku/
├── pet.json
└── spritesheet.webp

assets/
└── preview/
    ├── idle.gif
    ├── running-right.gif
    ├── running-left.gif
    ├── waving.gif
    ├── jumping.gif
    ├── failed.gif
    ├── waiting.gif
    ├── running.gif
    └── review.gif
```

## Notes

- `ku/pet.json`: Codex pet 메타데이터
- `ku/spritesheet.webp`: Codex가 읽는 KU pet 애니메이션 스프라이트시트
- `assets/preview/*.gif`: GitHub README에서 행동별 움직임을 보여주기 위한 미리보기 파일

## Credits

Made with school spirit by Makersfarm.
