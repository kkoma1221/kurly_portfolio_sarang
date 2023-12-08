### 브랜치(작업하기) 프로젝트 작업하기
- git branch
``````
 $ git branch
 * master
`````````
- git branch love (git branch 생성될 브랜치 이름)
``````
$ git branch
  love
* master
``````
- git checkout love (love라는 branch 사용하겠다.)
``````
$ git branch
* love (현재 사용하고 있는 branch)
  master
``````

### love 브랜치(Branch)에서 add, commit, push 하기
    - git add .
    - git commit -m 'love 브랜치(Branch)에서 add, commit, push'
    - git push origin love