<h1>This is intended for learning how to use Github</h1>
<p>Steps to set up a Github by the first time:</p>
<ol>
  <li>
    git init 
  </li>
  <li>
    git add file.txt
  </li>
  <li>
    git commit -m "Fisrt commit"
  </li>
  <li>
    git add remote origin url-to-github-repository
  </li>
  <li>
    git push -u origin master
  </li>
</ol>
<p>Steps to create a Pull Request:</p>
<ol>
  <li>
    Fork the repository
  </li>
  <li>
    git clone url
  </li>
  <li>
    git add .
  </li>
  <li>
    git commit -m " "
  </li>
  <li>
    git push -u origin master
  </li>
  <li>
    New Pull Request
  </li>
</ol>
<p>To create a branch:</p>
<ol>
  <li>
    git checkout -b branchName
  </li>
  <li>
    git add .
  </li>
  <li>
    git commit -m " "
  </li>
  <li>
    git push --set-upstream origin design-features
  </li>
</ol>
<p>To merge a branch into another:</p>
<ol>
  <li>
    git checkout branch
  </li>
  <li>
    git merge desirebranch
  </li>
  <li>
    git push 
  </li>
</ol>
    