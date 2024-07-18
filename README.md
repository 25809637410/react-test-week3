# react-test-week3

> [이노캠] 주특기 3주차 테스트(React)

✏️ 시험 문제

아래 시험문제를 다운받아 구현해야 하는 기능들을 구현하세요.
총 2개의 문제가 있습니다.

1. VS Code에 다운받은 파일을 불러와 엽니다.
2. npm 또는 yarn install로 프로젝트 종속성을 설치합니다.
3. npm 또는 yarn start 명령어로 프로젝트를 실행할 수 있습니다.

```
eg.)
yarn install
yarn start
```

💡 Redux toolkit의 “thunk”와 비동기 함수를 이용해서 프로젝트를 완성해봅니다.

⭐️ 지금까지 배운 내용을 바탕으로 추가하고 삭제하는데 각각 2초씩 걸리는 “느린” 투두 리스트를 만들어 보세요.

---

❗️ features : 구현해야 할 기능이에요.
과제와 비슷하지만, 요구사항이 훨씬 적습니다! 아래의 요구사항만 반영된 프로젝트를 제출해주세요.

<details>
  <summary markdown=1>구현해야 하는 UI 이미지 보기</summary>
  <div>
    ![구현해야 하는 UI 이미지 보기](https://file.notion.so/f/f/83c75a39-3aba-4ba4-a792-7aefe4b07895/15143d77-52cf-4f71-8fc2-bb80418803e4/과제_영상.mov?id=a3d54e06-0ffa-4442-b2ea-acaeb7fa6bac&table=block&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&expirationTimestamp=1721354400000&signature=19pcqvk73guh7X-3nEav0zatXDG2-KKH447lmg2O3JY)

  </div>
</details>

❗️ 비동기 작업인 2초 지연을 위해서는 미리 만들어둔 `“waitTwoSeconds”` 함수를 사용하세요.

```
// waitTwoSeconds 예시:

await waitTwoSeconds()
```

### 1. input에 제목을 쓰고, [추가하기] 버튼을 클릭하면 “2초 뒤” todo가 추가되어 화면에 렌더링 됩니다.

### 2. [삭제하기] 버튼을 클릭하면 “2초 뒤” todo가 삭제되어 화면에 렌더링 됩니다.
