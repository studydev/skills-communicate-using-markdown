## Step 2: 목록 만들기

마크다운은 3가지 일반적인 목록 유형을 지원합니다:

- [비순서 목록](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 글머리 기호 목록
- [순서 목록](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 번호 목록
- [작업 목록](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) - 체크박스 목록

### 비순서 목록

비순서 목록은 간단하게 표시할 수 있습니다. 각 항목은 `-`, `*`, 또는 `+` 문자를 사용하여 각각의 줄에 배치합니다.

```md
- 항목 1
- 항목 2
- 항목 3
```

- 항목 1
- 항목 2
- 항목 3

### 순서 목록

목록 문자 대신 숫자를 사용하면 순서 목록으로 변경됩니다. 마크다운이 자동으로 번호 매기기를 처리하는 것을 확인하세요. 편리하죠!

```md
1. 단계 1
1. 단계 2
1. 단계 3
```

1. 단계 1
1. 단계 2
1. 단계 3

### 작업 목록

작업 목록은 비순서 목록에 체크박스를 추가한 것입니다.
완료된 작업에는 채워진 괄호 `[x]`를, 미완료 작업에는 빈 괄호 `[ ]`를 추가하세요. 참고: 빈 괄호에는 공백이 필수입니다.

```md
- [x] 이 작업은 완료됨
- [ ] 이 작업은 미완료
```

- [x] 이 작업은 완료됨
- [ ] 이 작업은 미완료

> [!TIP]
> 이슈와 풀 리퀘스트에서 작업 목록 문법을 사용하여 [진행 상황을 전달](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists)할 수 있습니다.

### :keyboard: 실습: 아침 계획에 아이디어와 목표 추가하기

1. `start-blog` 브랜치에서 `day-1.md` 파일을 편집 모드로 여세요.

1. **Morning Planning** 레벨 2 헤딩 아래에 다음 작업 목록을 추가하여 달성하고 싶은 목표를 추적하세요.

   ```md
   - [ ] Check out the [github blog](https://github.blog/) for topic ideas.
   - [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
   - [ ] Convert my first blog post into an actual webpage.
   ```

1. **Preview** 탭을 사용하여 마크다운 서식을 확인하세요.

1. 오른쪽 상단에서 **Commit changes** 버튼을 클릭하고 `start-blog` 브랜치에 직접 커밋하세요.

1. 코드 블록이 커밋되면, Mona가 여러분의 작업을 검토하고 다음 단계를 준비할 것입니다.

<details>
<summary>문제가 있나요? 🤷</summary><br/>

- 올바른 파일과 브랜치를 편집하고 있는지 확인하세요.
- 문법을 다시 확인하세요. 작업 목록의 `[ ]` 안에 공백이 있어야 합니다.

</details>
