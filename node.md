 # Terms:
 ...Danh từ
 Repository (Repo) : Thư mục, dự án (Folder)
 Branch: Cành, nhánh. mặc định là master
 Conflict: Xung đột
 Local:
 Remote:


 # Commands:
 ...Lệnh

 - git init: Làm cho dự án or Repo trở thành Git Repo 
 => Dự án sử dụng dc Git sau khi dùng lệnh này

- git status: Cho thấy dc trạng thái dự án
=> Sẽ thấy được dự án đã thay đổi gì 

- git add: Cho phép chuẩn bị lưu lại thời điểm hiện tại của dự án 
    - git add {file name}: chuẩn bị lưu lại file đó
    - git add . : chuẩn bị lưu lại tất cả file trên 1 lượt

- git reset: Lấy lại file cbi lưu, không còn file nào cbi lưu nữa

- git commit: chính thức lưu, phải ghi chú 1 chi tiết trc khi lưu, để biết dc quá trình hay feature: phần nào đó
    -m initial commit: cam kết ban đầu, thời điểm ban đầu

- git log: Coi những thời điểm đã lưu
    -git log --oneline: ngắn gọn hơn

- git checkout {Commit ID}: quay lại thời điểm nào đó
    - git checkout {branch name}: quay về thời điểm hiện tại

- git branch: 
    - git checkout -b {branch name}: tạo ra 1 branch mới
    - git branch: lấy ra branch, branch hiện tại (*)
    - git merge {branch name}: 
    tổng hợp branch hiện tại + {branch name} đó
    - git branch -d {branch name}: xóa đi 1 branch

- git push: đẩy lên local repo trên remote repo 