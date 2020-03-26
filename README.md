Microsoft Windows [Versión 10.0.18362.720]
(c) 2019 Microsoft Corporation. Todos los derechos reservados.

C:\Users\maria>cd Documents

C:\Users\maria\Documents>cd TEC

C:\Users\maria\Documents\TEC>cd "Semestre Feb-Jun 2020"

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020>cd "Web Development"

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development>cd First-Partial-Exam

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git init
Reinitialized existing Git repository in C:/Users/maria/Documents/TEC/Semestre Feb-Jun 2020/Web Development/First-Partial-Exam/.git/

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git commit -m "Exam"
[master (root-commit) a334f2b] Exam
 7 files changed, 425 insertions(+)
 create mode 100644 Coding-Challenge-1/indexch1.html
 create mode 100644 Coding-Challenge-2/css/index.css
 create mode 100644 Coding-Challenge-2/index.html
 create mode 100644 Coding-Challenge-3/css/index.css
 create mode 100644 Coding-Challenge-3/img/jammer_logo.png
 create mode 100644 Coding-Challenge-3/index.html
 create mode 100644 Coding-Challenge-3/js/index.js

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git remote add origin https://github.com/marianaevv/First-Partial-Exam

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master


C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git push --set-upstream origin master
To https://github.com/marianaevv/First-Partial-Exam
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/marianaevv/First-Partial-Exam'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git push --set-upstream origin mariana
error: src refspec mariana does not match any
error: failed to push some refs to 'https://github.com/marianaevv/First-Partial-Exam'

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git checkout mariana
error: pathspec 'mariana' did not match any file(s) known to git

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git branch
* master

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git branch marinaa

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git cheackoyt marinaa
git: 'cheackoyt' is not a git command. See 'git --help'.

The most similar command is
        checkout

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git cheackout marinaa
git: 'cheackout' is not a git command. See 'git --help'.

The most similar command is
        checkout

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git checkout marinaa
Switched to branch 'marinaa'

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>README.md
"README.md" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>echo >> README.md

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git add Coding-Challenge-1

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git add Coding-Challenge-2

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git add Coding-Challenge-3

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git commit "Exam"
error: pathspec 'Exam' did not match any file(s) known to git

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git commit -m "Exam"
On branch marinaa
Untracked files:
        README.md

nothing added to commit but untracked files present

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git add README.md

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git commit -m "Exam"
[marinaa 3d4ea46] Exam
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git push --set-upstream
fatal: The current branch marinaa has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin marinaa


C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>git push --set-upstream origin marinaa
Enumerating objects: 19, done.
Counting objects: 100% (19/19), done.
Delta compression using up to 4 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (19/19), 8.66 KiB | 2.89 MiB/s, done.
Total 19 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'marinaa' on GitHub by visiting:
remote:      https://github.com/marianaevv/First-Partial-Exam/pull/new/marinaa
remote:
To https://github.com/marianaevv/First-Partial-Exam
 * [new branch]      marinaa -> marinaa
Branch 'marinaa' set up to track remote branch 'marinaa' from 'origin'.

C:\Users\maria\Documents\TEC\Semestre Feb-Jun 2020\Web Development\First-Partial-Exam>
