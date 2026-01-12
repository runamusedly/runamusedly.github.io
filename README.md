# 나의 블로그

## markdown에 대하여
- 안녕하세요.
- 여기는 제킬 블로그입니까?

### Grid 구조

```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}
```

→ column line은 1~5까지 존재

### 아이템 배치

```css
.item {
  grid-column-start: 2;
  grid-column-end: 5;
}
```

→ 2번 라인에서 시작해 5번 라인에서 끝남  
→ 즉, column 2~4를 가로로 모두 차지
  
