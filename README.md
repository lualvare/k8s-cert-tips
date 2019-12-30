# k8s-cert-tips
Tips and tricks for your cka and ckad exam

Some tips that you might already know that helped me a lot:

- Vim rc file to highlight yaml syntax and set tab to 2 spaces
```
~$ cat .vimrc
set number
syntax on
colorscheme zellner
autocmd FileType yaml setlocal ts=2 sts=2 sw=2 expandtab
```
  I had to memorized this one and set it on the exam. 
  Be careful with exam terminal copy and paste shortcuts (Ctrl + Insert = copy Ctrl + Shift = paste)

- Get familiar with the k8s docs layout and search tool (task and tutorials sections are real handy to copy, paste and modify yamls)
[kubernetes docs taks] (https://kubernetes.io/docs/tasks/)
[kubernetes docs tutorials] (https://kubernetes.io/docs/tutorials/)

- Get familiar with the commands to quickly generate yamls with dry run option:
[kubectl generators] (https://kubernetes.io/docs/reference/kubectl/conventions/#generators)

- Time management is key, if you feel a question is not all that clear to you move a long to the next

- Here is some extra exercises to practice (contents are from CKAD but it’s also useful for CKA)
[Task samples] (https://github.com/dgkanatsios/CKAD-exercises#contents)

