## Step 3: 코드 예제 추가하기

언어에 따른 [코드 블록](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code)과 [구문 강조](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)에 대해 알아보겠습니다.

> [!TIP]
> 많은 프로그래밍 언어가 지원됩니다. 다른 파일 확장자 유형도 테스트해 보세요!

### 예시: 터미널 명령어

````md
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

```bash
git clone https://github.com/skills/communicate-using-markdown
```

### 예시: JavaScript 코드

````md
```js
var myVar = "Hello, world!";
```
````

```js
var myVar = "Hello, world!";
```

### :keyboard: 실습: 코드 예제 추가하기

1. `start-blog` 브랜치에서 `day-1.md` 파일을 편집 모드로 여세요.

1. **Review** 레벨 2 헤딩 아래에 GitHub 블로그에서 방금 배운 멋진 코드 스니펫을 기록하는 다음 항목을 추가하세요.

   ````md
   Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

   ```bash
   ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
   ```
   ````

1. **Preview** 탭을 사용하여 마크다운 서식을 확인하세요.

1. 오른쪽 상단에서 **Commit changes** 버튼을 클릭하고 `start-blog` 브랜치에 직접 커밋하세요.

1. 코드 블록이 커밋되면, Mona가 여러분의 작업을 검토하고 다음 단계를 준비할 것입니다.

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 올바른 파일과 브랜치를 편집하고 있는지 확인하세요.
- 문법을 다시 확인하세요. 코드 블록은 세 개의 백틱 ` ``` `이지, 세 개의 아포스트로피 `'''`가 아닙니다.

</details>
