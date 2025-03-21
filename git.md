- CÁC THÀNH PHẦN CỦA GIT:

-- GIT REPOSITORY: Là cơ sở dữ liệu của GIT. Chứa tất cả các phiên bản
đã tạo trong dự án. Có 2 cách để tạo ra GIT REPOSITORY(.git) tại local.

- Câu hỏi

1. Nhánh mặc định main || master
2. Git Bash ko cho phép tiếp tục khi kết quả hiển thị quá dài
3. git commit thay vì git commit -m "message...."

- HEAD

-- Là 1 con trỏ đặc biệt có thể trỏ đến nhánh (trỏ đến commit) hoặc commit.
: Khi HEAD trỏ đến commit trực tiếp hay gián tiếp thông qua nhánh
--> thư mục làm việc sẽ hiển thị code, tài liệu ở commit đó.
: HEAD có thể nhảy đến bất kỳ commit, branch nào.

- HEAD trỏ đến branch --> bình thường (khuyến khích)
- HEAD trỏ đến commit --> detached HEAD (ko khuyến khích)
  --> Vì khi đang ở detached head, nếu tạo commit mới thì HEAD nhảy lên nhưng quan
  trọng là commit đó ko được chứa/quản lý trong bất kỳ branch (nhánh) nào
  --> Nếu như mình gõ git log thậm chí với tham số -all nó cũng ko show ra

-- master: là 1 nhánh ( là 1 con trỏ trỏ đến commit ).

--> git log [--oneline] [--all]
++ xem lịch sử commit: gồm commit hiện tại và các commit cha của nó.
++ --all: hiển thị tất cả commit được quản lý bởi BRANCH.

--> git ls-tree commit_hash
++ xem danh sách blob của commit đó.
++ xem commit đó có những file nào thay đổi so với commit trước đó.

--> git checkout commit_hash
++ đưa con trỏ HEAD đến commit_hash.
++ thư mục làm việc(working directory) sẽ chứa code, tài liệu ở commit.

--> git commit ^^^ hiện notepad
--> git commit -m "message"
++ Kết quả: tạo commit mới

--> git commit --amend ^^^ hiện notepad
--> git commit --amend -m 'new message'
++ Kết quả: ghi đè commit hiện tại (đổi mã hash)
+) đè nội dung
+) đè message
-> nếu k muốn update message --> git commit --amend --no-edit

--> git reset --hard HEAD~1
++ xóa commit, xóa luôn nội dung commit

--> git reset --soft HEAD~1
++ xóa commit, giữ lại nội dung commit

--> git reflog
++ hiện lịch sử các commit mà HEAD từng đi qua (gián/trực tiếp)

--> git branch ten_nhanh_moi ten_nhanh_cu
--> git checkout new_branch

--> git checkout -b new_branch old_branch

--> git ls-tree commit_hash
++ xem ds các blob của commit đó
++ xem commit đó có những file nào thay đổi so với commit trước

-- GIT STATUS

+) untracked: mới tạo ra, chỉnh sửa ... chưa được git quản lý,
chưa commit lần nào.

+) unmodified: file vừa mới commit.

+) modified: chỉnh sửa 1 file đã từng được commit.
--> changes not staged got committed

+) staged: file được dùng để commit.
--> change for commit

- NHÁNH LÀ GÌ

+) Nhánh đơn thuần là một con trỏ, trỏ đến một commit và có khả năng di chuyến được

+) Nhánh thường đại diện cho 1 version của dự án, commit mà nhánh đang trỏ đến sẽ
là commit, chức năng mới nhất của dự án đó

+) GIT có nhánh mặc định là master | main, HEAD -> master | main

+) Cách tạo nhánh:

--> git branch ten_nhanh_moi commit_hash

--> git branch ten_nhanh_moi ten_nhanh_cu : tạo ten_nhanh_moi từ cái commit
mà ten_nhanh_cu đang trỏ đến
