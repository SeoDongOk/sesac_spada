# sesac_spada

금융데이터 분석과정 6기 Spada팀!

### **깃허브 브랜치 사용법!**

참고용 강의: https://www.youtube.com/watch?v=sly2u8BIi9E

참고: https://eehoeskrap.tistory.com/666

1. Local 브랜치를 생성한다.(이름 자유)

```bash
git checkout -b dev_sdo_local
```

2. 개인 Remote 브랜치를 생성한다.(이름: dev\_초성 ex: dev_sdo)
3. 변경사항을 Local 브랜치에 commit 한다.

```bash
git add .
git commit -m "message"
```

4. 개인 Remote 브랜치로 commit한 Local 브랜치의 내용을 push한다.(로컬 브랜치와 동일하게)

```bash
git push origin dev_sdo_local
```

5. commit된 Remote 브랜치를 Remote 브랜치 중 dev에 Pull Request 한다.
6. 검수 후 merge 완료.

### 주의 사항

- ${\textsf{\color{red} 변경내용을 commit하기 전에 fetch를 통해서 최신변경 내용을 반영한다}}$
- Pull Request는 요청만 하고 건드리지 않는다. (merge를 누르면 안됨)
- 에러가 발생한 코드는 commit 하지 않는다.
- ${\textsf{\color{pink}GUI를 적극 사용한다.(ex: SourceTree, GitHub Desktop, Fork)}}$
