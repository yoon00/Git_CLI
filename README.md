# Git CLI

---

`Git`_도구_, `Github` _클라우드_

- 버전 관리
- Git은 인터넷 연결 없이 관리 가능
- 로컬(Git)에서 삭제되어도 원격(Github)에서 복구 가능
- 여러 명이 작업 후 병합 가능

`CLI`: Command Line Interface
`GUI`: Graphic User Interface

---

#### CLI 환경에서 git 사용

```bash
git init
git add .
git commit -m "first commit"

git remote add origin https://github.com/yoon00/Git_CLI.git
git push -u origin main
```

#### git 명령어

```
- git init: 초기화
- git status: 상태 확인
- git add .: 모든 파일 add
- git commit -m 'commit message' : commit
- git commit -am 'commit message': add와 commit
- git checkout - b 브랜치명: 브랜치 생성 후 전환
- git checkout 브랜치명: 브랜치 전환
- git branch -D 브랜치명: 브랜치 삭제
- git push origin main: 브랜치 동기화
```

###### .gitignore: git에서 무시할 파일 작성
