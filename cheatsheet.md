# CHEATSHEET GIT CƠ BẢN
## (Dành cho người mới bắt đầu)

### LỆNH KIỂM TRA
- `git --version` - Kiểm tra Git đã cài chưa
- `git status` - Xem trạng thái file đang thay đổi
- `git log --oneline` - Xem lịch sử commit (dạng ngắn)

### LỆNH THAY ĐỔI
- `git add <tên_file>` - Thêm 1 file vào staging
- `git add .` - Thêm TẤT CẢ file vào staging
- `git commit -m "tin nhắn"` - Lưu lại trạng thái
- `git push` - Đẩy code lên GitHub

### LỆNH NHÁNH (BRANCH)
- `git branch` - Xem danh sách nhánh
- `git checkout -b <tên>` - Tạo và chuyển sang nhánh mới
- `git merge <tên>` - Hợp nhất nhánh

### LỆNH QUAY LẠI
- `git reset --hard HEAD~1` - Xóa commit gần nhất
- `git stash` - Cất công việc tạm thời

---
*File này sẽ được cập nhật thêm trong quá trình học*