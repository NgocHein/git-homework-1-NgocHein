On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

nothing added to commit but untracked files present (use "git add" to track)
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   notes.txt
	new file:   todo.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	draft.md
	status_log.md

diff --git a/part1/notes.txt b/part1/notes.txt
index e69de29..0bd0ce1 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -0,0 +1,3 @@
+Dong 1
+Dong 2
+Dong 3
diff --git a/part1/notes.txt b/part1/notes.txt
index e69de29..0bd0ce1 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -0,0 +1,3 @@
+Dong 1
+Dong 2
+Dong 3
--- GIẢI THÍCH LỆNH GIT COMMIT -A ---
Lệnh 'git commit -a' chỉ tự động stage và commit đối với các file ĐÃ ĐƯỢC TRACK (tracked files - các file đã từng dùng 'git add' trước đây). Nó sẽ bỏ qua các file mới tạo lần đầu (untracked files, như draft.md).
--- SO SÁNH GIT FETCH VÀ GIT PULL ---
- git fetch: Tải các dữ liệu/commit mới nhất từ remote về máy local nhưng KHÔNG tự động gộp (merge) vào mã nguồn hiện tại của bạn.
- git pull: Là kết hợp của (git fetch + git merge). Nó vừa tải commit mới về vừa TỰ ĐỘNG GỘP trực tiếp vào branch local hiện tại.