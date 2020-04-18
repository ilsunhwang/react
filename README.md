
git add .
git commit -m "전체추가 - 20200422"
git add README.md
git commit -m "README.md 파일추가 - 20200422"

git clone https://github.com/ilsunhwang/react.git .

echo "# react" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ilsunhwang/react.git
git push -u origin master

SYMC