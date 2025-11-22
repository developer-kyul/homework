# 📘 마크다운(Markdown) 문법 총정리

마크다운(Markdown)은 텍스트 기반의 문서 작성 문법으로, GitHub, Notion, VS Code, 블로그 등 다양한 환경에서 사용된다.  
아래는 가장 핵심적이고 실무에서 자주 활용되는 문법 전체를 정리한 문서이다.

---

# 1. 제목 (Headers)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

---

# 2. 강조 (Emphasis)

**굵게**  
_기울임_  
**_굵고 기울임_**  
~~취소선~~

---

# 3. 목록 (List)

- 항목 1
- 항목 2
  - 하위 항목

1. 첫 번째
2. 두 번째
   1. 하위 항목

---

# 4. 링크 (Links)

[링크 텍스트](https://example.com)  
[설명 있는 링크](https://example.com '툴팁 내용')

---

# 5. 이미지 (Image)

![이미지 설명](이미지_URL)

---

# 6. 인용문 (Blockquote)

> 인용문
>
> > 중첩 인용문

---

# 7. 코드 (Code)

인라인 코드: `print("hello")`

코드 블록:

```python
print("Hello")
```

# 8. 수평선 (Horizontal Line)

---

---

---

# 9. 표 (Table)

| 제목1 | 제목2  | 제목3 |
| ----- | :----: | ----: |
| 좌측  | 가운데 |  우측 |
| A     |   B    |     C |

표 안 줄바꿈 예시
줄1<br>줄2

# 10. 체크박스 (To-do List)

- [ ] 할 일
- [x] 완료된 일

# 11. 줄바꿈 (Line Break)

첫 번째 문장 끝에 공백 두 개  
여기서 줄이 바뀐다.

# 12. 각주 (Footnotes)

문구 A[^a], 문구 B[^b]

[^a]: 첫 번째 각주

[^b]: 두 번째 각주

# 13. 접기 (Details)

<details>
<summary>더보기</summary>

펼쳐지는 내용

</details>

# 14. 주석 (Comment)

<!-- 표시되지 않는 주석 -->

# 15. HTML 병행사용

<span style="color:red;">빨간 글씨</span>

<p align="center">가운데 정렬</p>
<div style="border:1px solid #ccc; padding:10px;">박스 스타일</div>
