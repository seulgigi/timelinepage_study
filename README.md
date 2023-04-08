# 🗓️ timelinepage_study
gantt timeline drag&amp;drop study


**BaseURL**: `"${workspaceFolder}/examples/timeline/other/drag&drop.html”`


**Repository rule**
1. 기능을 추가할 때마다 issue를 생성한다.
    - `issue: {issue 내용}`
    
2. 작업시 branch를 생성하여 해당 branch에서 작업 후, pr하며 함께 코드 리뷰를 한다. 이상 없을 시 main에 merge한다! 
    - branch명 ⇒ `feature/issue-{issue 번호}`
        - ex) feature/issue-1
    
3. 기본적으로 [commit convention](https://velog.io/@archivvonjang/Git-Commit-Message-Convention)에 따라 커밋 메세지를 정한다.
    - `type : {수행 내용}`
        - ex) feat : block color change
