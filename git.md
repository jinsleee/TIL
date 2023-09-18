# git

## 최소설정
커밋에 기록되는 사용자 정보
```bash
git config --global user.name 'lovelysangjin'
git config --global user.email 'sjsj9620@gmail.com'

git config --global user.email
```

## 명령어
- `git init`
    - `.git` repository를 생성 하는 명령어

- `git add <file name>.`
    - working directiory에서 staging area로 추가
    - 일반적으로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .`

- `git commit`
    - `staging area`에 올라간 파일들의 스냅샷을 찍어 `.git directiory`
    - 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가
    - `git commit -m "message"`

    
