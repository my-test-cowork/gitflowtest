# gitflowtest

## Fork and PR
1. Organization에서 생성된 repository에서 Fork를 받아온다. (나의 개인 Repository로)
2. 참고로 코드 수정 시 Fork된 Repository에서 `.`을 누르면 Web vscode가 실행된다.
3. PR보내기: Fork된 repo에서 코드 수정 후 Contribute > Open pull request를 누른다. (`organization명: repo명 <- 개인이름: repo명`과 branch가 맞는지 확인한 후 'Able to merge'초록색을 확인 후 'Create Pull request'버튼을 누른다.)
4. 중요한 setting: settings > Branches > Add branch protection rule > Protect matching branches > Require a pull request before merging 체크 > require approvals 체크 > lock branch (선택사항)
    - 보통 이 세팅은 release repo를 따로 만들고 거기에 세팅, 그리고 test repo를 따로 만들어서 그 repo에 있는 것을 release repo로 보낸다.

---
##### 참고 Links
- [GitHub으로 협업하기 1편 - 깃헙 프로젝트 생성, 이슈 생성, 충돌 해결까지](https://www.youtube.com/watch?v=6sBNPvxjyt0&t=50s)
- [GitHub으로 협업하기 2편 - mermaid로 WBS 작성, branch 전략에 고려할 점, fork와 PR](https://www.youtube.com/watch?v=DHnILM-tquI)
-   [docs](https://paullabworkspace.notion.site/GitHub-435ec8074bcf4353afb947f601a030df?pvs=4)
