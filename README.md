# phase-0-gps-1-1  //github repository
 1092  ls //viewing file contents
 1093  git clone https://github.com/chrisswk/phase-0-gps-1-1.git  //cloning the github file
 1094  ls //viewing file contents
 1095  cd phase-0-gps-1-1  //changing directory into the file
 1096  touch awesome.md  //creating awesome.md, mistakenly
 1097  rm awesome.md  //deleting awesome.md
 1098  touch awesome_page.md  //creating new awesome_page.md
 1099  git add awesome_page.md  //adding awesome_page.md to stage
 1100  git commit -m "Adding awesome_page.md"  //Committed a snapshot of added awesome_page.md
 1101  git status  //checked status
 1102  git branch -v  //checked which branch we were in
 1103  git push origin/master  //tried to push to github, unsuccessfully
 1104  git push origin master //successfully pushed!
 1105  git checkout -b "add-command-log"  //Created a new branch
 1106  git checkout -help  //Checked the help commands as per the suggestion of the challenge
 1107  ls  //Lists file contents
 1108  cd ..  //changes into higher directory
 1109  ls //lists file contents
 1110  cd phase-0-gps-1-1  //changed back into directory
 1111  ls   //lists file contents
 1112  subl .  //opens contents in sublime
 1113  history 10  //viewed last 10 commands
 1114  history 10 | cat README.md  //attempted to append commands to README.md
 1115  cat README.md  //read README.md
 1116  history 25 >> README.md  //Shoveled last 25 commands into README.md
