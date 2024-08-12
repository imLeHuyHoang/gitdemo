Chào mừng bạn đến với tệp markdown này! Đây là nơi bạn có thể tạo và định dạng nội dung với Markdown. Markdown là một ngôn ngữ đơn giản và dễ hiểu để viết và định dạng văn bản. Bạn có thể sử dụng Markdown để tạo tiêu đề, đoạn văn, danh sách, liên kết và nhiều hơn nữa. Hãy bắt đầu viết và khám phá sức mạnh của Markdown!

cú pháp cơ bản với git 
# Cú pháp cơ bản với Git
## 1. Khởi tạo Git
Để bắt đầu sử dụng Git, bạn cần khởi tạo một repository. Để khởi tạo một repository, hãy sử dụng lệnh sau:
```
git init
```
## 2. Thêm và commit
Để thêm tất cả các tệp vào staging area, hãy sử dụng lệnh sau:
```
git add .
```
Sau khi đã thêm các tệp vào staging area, bạn có thể commit các thay đổi bằng cách sử dụng lệnh sau:
```
git commit -m "Message"
```
## 3. Kiểm tra trạng thái
Để kiểm tra trạng thái của repository, hãy sử dụng lệnh sau:
```
git status
```
## 4. Xem lịch sử commit
Để xem lịch sử commit, hãy sử dụng lệnh sau:
```
git log
```
## 5. Tạo nhánh mới
Để tạo một nhánh mới, hãy sử dụng lệnh sau:
```
git branch <branch_name>
```
## 6. Chuyển đổi giữa các nhánh
Để chuyển đổi giữa các nhánh, hãy sử dụng lệnh sau:
```
git checkout <branch_name>
```
## 7. Merge nhánh
Để merge một nhánh vào nhánh hiện tại, hãy sử dụng lệnh sau:
```
git merge <branch_name>
```
## 8. Xóa nhánh
Để xóa một nhánh, hãy sử dụng lệnh sau:
```
git branch -d <branch_name>
```
trong đó `-d` là viết tắt của `--delete`.
## 9. Đẩy lên repository từ xa
Để đẩy các thay đổi lên repository từ xa, hãy sử dụng lệnh sau:
```
git push origin <branch_name>
```
