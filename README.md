# k8s-cert-tips
Tips and tricks for your CKA and CKAD exams.

The CKA and CKAD exams can be a pretty difficult challenge if you do not have enough practice with kubectl and Kubernetes yamls files. Generally speaking all questions can be simply and quickly resolved if you know where to look and how to use the resources.
And a key part of knowing where to look and how to use/modify the resources comes with practice (a lot of practice!).

If you spend quality time with kubectl and with k8s yamls, it will show on your speed and accuracy.
A good way to get this quality time is to have your own k8s cluster, ideally one with multiple nodes and installed by you using kubeadm or similar deployment tools.

If you have some spare hardware resources here is some tools you can use to set up a k8s sandbox with vms on your linux box:
[kvm build with cloud images](https://github.com/sturrent/kvm-build-with-cloud-image)

Some tips that you might already know that helped me a lot:

- Vim rc file to highlight yaml syntax and set tab to 2 spaces
```
~$ cat .vimrc
set number
syntax on
colorscheme zellner
autocmd FileType yaml setlocal ts=2 sts=2 sw=2 expandtab
```
  > I had to memorized this one and set it on the exam. Be careful with exam terminal copy and paste shortcuts (Ctrl + Insert = copy Ctrl + Shift = paste)

- Hands-on basic kubernetes examples:
[kubernetes by example](http://kubernetesbyexample.com/)

- Get familiar with the k8s docs layout and search tool (task and tutorials sections are real handy to copy, paste and modify yamls)
[kubernetes docs taks](https://kubernetes.io/docs/tasks/)
[kubernetes docs tutorials](https://kubernetes.io/docs/tutorials/)

- Learn the commands to quickly generate yamls with dry run option:
[kubectl generators](https://kubernetes.io/docs/reference/kubectl/conventions/#generators)

- Time management is key, if you feel a question is not all that clear to you move along to the next. 

- Here is some extra exercises to practice (contents are from CKAD but it’s also useful for CKA)
[Task samples](https://github.com/dgkanatsios/CKAD-exercises#contents)
