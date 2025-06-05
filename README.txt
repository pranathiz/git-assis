 3  ls
    4   cd project-git
    5  mkdir git-project
    6  cd git-project/
    7  mkdir git-assis1
    8  cd git-assis1/
    9  touch code.txt log.txt output.txt
   10  echo "this is code" > code.txt
   11  echo "this is logs" > log.txt
   12  echo "this is output" > output.txt
   13  ls
   14  git init
   15  git add code.txt output.txt
   16  git status
   17  git commit -m "inital commit with code.txt and output.txt"
   18  git remote add origin https://github.com/pranathiz/git-assis.git
   19  git branch -m main
   20  git push -u origin main
   21  history no.
    history
