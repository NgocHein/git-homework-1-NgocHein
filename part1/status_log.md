1. ##### **Part B-1**

On branch master

Untracked files:

&#x20; (use "git add <file>..." to include in what will be committed)

&#x20;       ./



nothing added to commit but untracked files present (use "git add" to track)

##### 

##### **2. Part B-2**

On branch master

Changes to be committed:

&#x20; (use "git restore --staged <file>..." to unstage)

&#x20;       new file:   notes.txt

&#x20;       new file:   todo.txt



Untracked files:

&#x20; (use "git add <file>..." to include in what will be committed)

&#x20;       draft.md

&#x20;       status\_log.md



##### **3. Unstaged diff (git diff)**

diff --git a/part1/notes.txt b/part1/notes.txt

index e69de29..c0b40ff 100644

\--- a/part1/notes.txt

+++ b/part1/notes.txt

@@ -0,0 +1,3 @@

+Nguyen Ngoc Hien

+B25DCTN039

+D25CTTN01-B

\\ No newline at end of file



##### **4. Staged diff (git diff --staged)**

diff --git a/part1/notes.txt b/part1/notes.txt

index e69de29..c0b40ff 100644

\--- a/part1/notes.txt

+++ b/part1/notes.txt

@@ -0,0 +1,3 @@

+Nguyen Ngoc Hien

+B25DCTN039

+D25CTTN01-B

\\ No newline at end of file



##### **5. Explanation: Why git commit -a only works for tracked files**

* để tránh lưu file rác vào Git
* Git tuân theo nguyên tắc chỉ quản lí những gì người dùng chủ động yêu cầu( hoạt động với file đã được git add trước đó)

##### 

##### **6. Difference between git fetch and git pull:**

* git fetch: Tải các thông tin và commit mới nhất từ remote repository về máy local nhưng chưa tự động gộp(merge) vào thư mục làm việc.
* git pull: Tải dữ liệu mới về và tự động gộp ngay vào nhánh làm việc ở máy local (tương đương với git fetch + git merge).

