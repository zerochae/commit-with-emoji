# commit-with-emoji

## What is this

- 더 나은 git 커밋 메시지를 작성하도록 도와주는 간단한 git 커맨드입니다.
- 이모지와 시멘틱 태그를 동시에 사용하여 직관적인 커밋 메시지 로그를 작성할 수 있습니다.

## Emoji

| emoji | Tag      | Description                                 |
| ----- | -------- | ------------------------------------------- |
| ✨    | Feat     | 기능 추가                                   |
| 🐛    | Fix      | 버그 픽스                                   |
| 💄    | Design   | CSS, UI 변경                                |
| ♻️    | Refactor | 프로덕션 코드 리팩토링                      |
| ⚙     | Test     | 테스트 코드 추가,수정(프로덕션 코드 변경 X) |
| 📦    | Chore    | 패키지 매니저 설정(프로덕션 코드 변경 X)    |
| 🚚    | Rename   | 파일,폴더명 수정                            |
| 🔥    | Remove   | 파일 삭제                                   |
| 📝    | Docs     | 문서 추가,수정                              |

## Install

1. 깃 설정 파일 열기

```
vim ~/.gitconfig
```

2. .gitconfig 파일 내용 추가하기
- 내용을 모두 복사 붙여넣기 합니다.

<img width="578" alt="스크린샷 2022-05-01 17 26 37" src="https://user-images.githubusercontent.com/84373490/166138142-ded84300-9918-4070-86cb-a85cb887acd6.png">

3. 변경사항 적용

```
source ~/.gitconfig
```


## Usage

- `git feat "커밋 메시지"` -> `git commit -m "✨ Feat: 커밋 메시지"`
- `git fix "커밋 메시지"` -> `git commit -m "🐛 Fix: 커밋 메시지"`
- `git docs "커밋 메시지"` -> `git commit -m "📝 Docs: 커밋 메시지"`


<img width="723" alt="스크린샷 2022-05-01 17 00 10" src="https://user-images.githubusercontent.com/84373490/166137529-cab51e33-96f5-4b5e-8cde-2d7a7777cb3f.png">


