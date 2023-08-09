# 깃 명령어 정리

`git init` : 파일에 Git 생성(로컬저장소)
`git config --global user.mail "~" ` : 깃과 깃허브의 메일 연동
`git config --global user.name "~" ` : 깃과 깃허브의 닉네임 연동
`git add README.md` : 버전 관리할 파일 추가
`git commit -m "커밋설명"` : 지금까지 한 것들 깃에 저장
`git log` : 각 커밋별 커밋 ID 확인
`git checkout 0000000` : 로그기록에서 커밋ID 앞 7자리 적어서 과거로 돌아가기
`git checkout -` : 최신 커밋으로 다시 돌아가기
`git remote add origin https://~` : 로컬저장소에 연결할 원격저장소 주소를 알려줌
`git branch -M main` : 지금까지 만든 커밋을 둘 장소
`git push origin main` : 로컬저장소를 원격저장소에 올림
`git clone http://~` : 해당 원격저장소에 있는 파일을 로컬저장소로 받기
`git pull origin main` : 다른 로컬저장소에 변경된 최신 커밋을 받아 갱신하기

>깃의 4가지 상태?
>   + 추적안됨(`untracked`) : 초기화하거나 파일을 폴더에 추가했을때
>   + 수정없음(`tracked`) : 현재 커밋에서 수정된거 없을 때
>   + 수정함(`tracked`) : 현재 커밋에서 수정된게 있을 때
>   + 스테이지됨(`tracked`) : `add`명령으로 스테이지에 올리면