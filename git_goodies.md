**EDITOR**  [https://stackedit.io/app#](https://stackedit.io/app#)
 - git difference in commits ahead/behind
>    git rev-list --left-right --count master...test-branch
>    result 1	     7  - compared to master test-branch is 1 commit behind, 7 ahead 


**Find most recent ancestor**
> git merge-base branch2 branch3

**Git rebase upto commit b6fc9dad86d2843063cd69f346762c052459f162 from common ancestor**
 > git rebase b6fc9dad86d2843063cd69f346762c052459f162
