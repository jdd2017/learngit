Git is a version control system.
Git is free software.

使用git add txt/readme.txt 命令将readme.txt添加到git  可以添加多个文件
使用git commit -m "...本次提交的说明..."
------------------------------------------------------------------------------
[master (root-commit) 77c5a14] ...本次提交的说明...                                                                                                                mmit -m 进行提交
 1 file changed, 2 insertions(+)   一个文件改变 有2行文字
 create mode 100644 txt/readme.txt
------------------------------------------------------------------------------

使用 git status 查看哪些文件被改动
 
$ git status
------------------------------------------------------------------------------
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   txt/readme.txt

no changes added to commit (use "git add" and/or "git commit -a")
------------------------------------------------------------------------------


