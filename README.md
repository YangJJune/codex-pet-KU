# 🐮 Codex Pet - 쿠 (KU)

Codex 안에서 만나는 작은 쿠!!

건국대학교 마스코트 KU를 좋아하는 마음으로 만든 비공식 Codex 커스텀 펫입니다.

|  |
|---|
| **TIP**<br>이 페이지 URL을 Codex에게 붙여넣고 “이 펫 설치해줘”라고 말하면 됩니다. |


[건국대학교 Makersfarm](https://makersfarm.notion.site/1a94cff385048074b049f0bde400abed?v=1a94cff3850481688d50000ceadaf1d8&pvs=74)에서 **애교심**과 **팬심**을 담아 만들었습니다. (쿠 너무 귀여워 ㅜㅜ)

> [!tip]
> Made by Codex 'hatch-pet' skil <br> Further info : [hatch-pet 스킬로 코덱스 펫 만들기](https://contents.premium.naver.com/brandmite/brandmiteplus/contents/260504110416618ip)

> [!NOTE]
> 이 프로젝트는 비공식 팬 프로젝트입니다. <br> 건국대학교 또는 공식 마스코트 운영 주체의 공식 배포물이 아닙니다. <br>

<br>
<br>

## 🖼️ Preview

![Codex에게 이 펫 설치를 요청하는 팁](./assets/readme/install-tip.svg)

- 상세한 설치 방법은 아래의 `AI Agent 설치 지시` 섹션에 따로 모아두었습니다.

<br>

| 대기 | 🏃‍♂️‍➡️ 달리기 | 🏃‍♂️ 달리기 | 안녕~ | 짬푸- |
|:---:|:---:|:---:|:---:|:---:|
| ![대기](./assets/preview/idle.gif) | ![🏃‍♂️‍➡️ 달리기](./assets/preview/running-right.gif) | ![🏃‍♂️ 달리기](./assets/preview/running-left.gif) | ![안녕~](./assets/preview/waving.gif) | ![짬푸-](./assets/preview/jumping.gif) |

| 실패 | 건덕이 쓰담 | 작업 중 | Hmm... |  |
|:---:|:---:|:---:|:---:|
| ![실패](./assets/preview/failed.gif) | ![기다리는 중](./assets/preview/waiting.gif) | ![작업 중](./assets/preview/running.gif) | ![검토 중](./assets/preview/review.gif) | 

<br>
<br>

## 💻 Playground

Codex Pets 사이트의 KU 상세 페이지에서 `Playground` 버튼을 누르면 KU를 직접 움직여볼 수 있습니다.

[Codex Pets에서 KU 체험하기](https://codex-pets.net/#/pets/ku)

<br>
<br>

## 🤖 Instruction for AI Agent 

<details>
<summary>Installation instructions for AI agents</summary>

Copy this repository's `ku/` directory into the user's Codex pets directory.

Target install paths:

- Windows: `%USERPROFILE%\.codex\pets\ku`
- macOS/Linux: `$HOME/.codex/pets/ku`

After installation, these files must exist:

- `.codex/pets/ku/pet.json`
- `.codex/pets/ku/spritesheet.webp`

If the target `ku` directory already exists, back it up or replace it. Restart Codex after installation.

The GIF files in `assets/preview/` are only for the README preview. The actual Codex pet installation only needs `ku/pet.json` and `ku/spritesheet.webp`.

</details>

<br>
<br>

## 📂 File Structure

```txt
ku/
├── pet.json          # Codex pet metadata
└── spritesheet.webp  # Sprite sheet used by Codex

assets/
└── preview/
    ├── idle.gif           # README preview
    ├── running-right.gif  # README preview
    ├── running-left.gif   # README preview
    ├── waving.gif         # README preview
    ├── jumping.gif        # README preview
    ├── failed.gif         # README preview
    ├── waiting.gif        # README preview
    ├── running.gif        # README preview
    └── review.gif         # README preview
```

<br>
<br>

## ℹ️ Credits

- Made with school spirit by [@ArticPenguin](https://github.com/ArticPenguin) in [Makersfarm](https://www.instagram.com/makersfarm_konkuk/).

- Special Thanks to my coworkers '취업토크쇼', '돈벌자!'


### 메이커스팜의 다른 프로젝트도 궁금하시지 않나요?
- [LinKU](https://github.com/Turtle-Hwan/LinKU): 건대생 필수 크롬 확장프로그램!
- [Makers-Skills](https://github.com/makersfarm/Makers-Skills): 메이커들을 위한 Agent 스킬 모음
