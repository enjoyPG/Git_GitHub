## 깃 초보의 깃 사용법입니다..



### 처음 만들 때
1. echo "# test" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"
5. git remote add origin https://github.com/enjoyPG/test.git
6. git push origin master

### 작업한거 올릴 때
1. git add .
2. git commit -m "~~~"
3. git push origin master

### 깃에서 가져올 때
1. git init
2. git remote add origin 링크
3. git pull origin master


### 이건 뭐지?
1. git에서 원격 저장소 만들기
2. git clone 주소  입력해서 저장소 내려받기
3. git add .
4. git commit -m "메시지"
5. git push orgin master 푸시하기
(git status는 변화 보는 것)

(git remote로 직접연결해도됨)
(새 컴퓨터에서 처음 push할 때 email이랑 name 설정해야함)
(push할 때 로그인도 해야할 수도 있음)
(깃헙에 있는 원본 받아올 때는 pull명령어 사용하면 됨)