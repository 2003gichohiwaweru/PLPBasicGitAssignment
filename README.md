the following include the commands i used in doing the assignment
C:\Users\josan>CD /

C:\>mkdir PLPBasicGitAssignment

C:\>cd PLPBasicGitAssignment

C:\PLPBasicGitAssignment>git init
Initialized empty Git repository in C:/PLPBasicGitAssignment/.git/

C:\PLPBasicGitAssignment>git remote add origin https://github.com/2003gichohiwaweru/PLPBasicGitAssignment.git

C:\PLPBasicGitAssignment>dir
 Volume in drive C is New Volume
 Volume Serial Number is 5E1D-A9BC

 Directory of C:\PLPBasicGitAssignment

03/28/2024  10:02 AM    <DIR>          .
               0 File(s)              0 bytes
               1 Dir(s)  73,133,719,552 bytes free

C:\PLPBasicGitAssignment>git clone https://github.com/2003gichohiwaweru/PLPBasicGitAssignment.git
Cloning into 'PLPBasicGitAssignment'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

C:\PLPBasicGitAssignment>touch hello.txt
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\PLPBasicGitAssignment>type nul > hello.txt

C:\PLPBasicGitAssignment>dir
 Volume in drive C is New Volume
 Volume Serial Number is 5E1D-A9BC

 Directory of C:\PLPBasicGitAssignment

03/28/2024  10:06 AM    <DIR>          .
03/28/2024  10:06 AM                 0 hello.txt
03/28/2024  10:03 AM    <DIR>          PLPBasicGitAssignment
               1 File(s)              0 bytes
               2 Dir(s)  73,140,793,344 bytes free

C:\PLPBasicGitAssignment>echo heLlo World > hello.txt

C:\PLPBasicGitAssignment>dir
 Volume in drive C is New Volume
 Volume Serial Number is 5E1D-A9BC

 Directory of C:\PLPBasicGitAssignment

03/28/2024  10:06 AM    <DIR>          .
03/28/2024  10:06 AM                14 hello.txt
03/28/2024  10:03 AM    <DIR>          PLPBasicGitAssignment
               1 File(s)             14 bytes
               2 Dir(s)  73,138,667,520 bytes free

C:\PLPBasicGitAssignment>git add hello.txt

C:\PLPBasicGitAssignment>git commit -m "Add hello.txt with a greeting"
[master (root-commit) 3f683a3] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

C:\PLPBasicGitAssignment> git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/2003gichohiwaweru/PLPBasicGitAssignment.git'

C:\PLPBasicGitAssignment>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


C:\PLPBasicGitAssignment>git push --set-upstream origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 242 bytes | 242.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/2003gichohiwaweru/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/2003gichohiwaweru/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

C:\PLPBasicGitAssignment>
