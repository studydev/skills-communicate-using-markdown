## Step 4: 이미지 추가하기

상대 URL, 절대 URL, 크기 조절 및 기본 위치 지정을 사용하여 [마크다운에 이미지를 포함하는 방법](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)을 알아보겠습니다.

### 일반 마크다운

이미지는 저장소 내 파일의 상대 URL이나 절대 URL(인터넷 어디서든)을 제공하여 표시할 수 있습니다.

대괄호 안의 설명 텍스트는 이미지를 로드할 수 없을 때 표시되며, 스크린 리더를 사용하는 사람들에게 읽어집니다.

참고: 마크다운 문법에서는 이미지 크기를 변경하는 옵션을 제공하지 않습니다.

### 예시

저장소 내 이미지의 상대 URL:
```md
![Mona the Octocat](myrepo/original.png)

```

인터넷 상의 이미지의 절대 URL:
```md
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png" width="200">

### 간단한 HTML

이미지 크기를 줄이거나 텍스트 옆에 배치해야 하는 경우가 자주 있습니다. 일반 HTML 문법은 추가적인 유연성을 제공합니다.

- `alt` 필드는 대체 텍스트를 지정합니다.
- `src` 필드는 이미지의 소스 URL을 지정합니다.
- `width` 및/또는 `height` 필드를 사용하여 픽셀 단위로 크기를 지정할 수 있습니다.
- `align` 필드로 위치를 설정할 수 있습니다 (`left`, `right`)

```md
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```

### :keyboard: 실습: 장식 추가하기

우리의 블로그 게시물은 현재 꽤 단순합니다. 장식을 추가해 봅시다.

1. `start-blog` 브랜치에서 `day-1.md` 파일을 편집 모드로 여세요.

1. **Morning Planning** 레벨 2 헤딩 아래에 이미지를 삽입하세요.

   ```md
   ![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
   ```

1. **Preview** 탭을 사용하여 마크다운 서식을 확인하세요.

   - 이미지가 우리 목적에 비해 너무 큰 것을 확인하세요.

1. 간단한 마크다운 버전을 크기와 위치 정보가 포함된 HTML 버전으로 교체하세요. 훨씬 낫습니다!

   ```md
   <img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
   ```

1. 오른쪽 상단에서 **Commit changes** 버튼을 클릭하고 `start-blog` 브랜치에 직접 커밋하세요.

1. 이미지가 추가되고 커밋되면, Mona가 여러분의 작업을 검토하고 다음 단계를 준비할 것입니다.

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 올바른 파일과 브랜치를 편집하고 있는지 확인하세요.
- 문법을 다시 확인하세요. HTML 이미지 태그는 `img`로 시작하고 `src` 속성을 포함해야 합니다.

</details>
