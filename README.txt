
[GITHUB YSIT24]

# 로컬 저장소 생성
git init

# 파일 생성(README.txt)
git add README.txt

# 커밋
git commit -m "[파일생성] README.txt"

# 원격 저장소 연결
git remote add origin https://github.com/kim-sung-pyo/Hello24.git

# 원격 저장소 연결 확인
git remote -v

# 원격 저장소에 저장소
git push -u origin main

###################################################################
원격 저장소 위치:
https://github.com/kim-sung-pyo/Hello24.git

…or create a new repository on the command line
echo "# Hello24" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kim-sung-pyo/Hello24.git
git push -u origin main