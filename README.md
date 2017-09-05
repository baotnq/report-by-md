
# Kĩ năng bắt buộc cho VinaAS Beginner 
## Sử dụng Markdown để ghi chú, report 
### Lưu ý 

- hình ảnh minh hoạ trong 1 thư mục, ví dụ `screenshot` 
   - hình ảnh này sẽ được lưu trữ github (hoặc gitlab)
   - đính kèm vào file markdown bằng đường dẫn tương đối, ví dụ [mdwithVSCode.png](/screenshot/mdwithVSCode.png)
   - thay thế bằng hình mới khi có thay đổi  sau này 

- ghi chú các bước thực hiện kèm theo hình minh hoạ 
   - cho hiện hình ảnh trực tiếp, dùng `![]()`, ví dụ 
   ![mdwithVSCode.png](/screenshot/mdwithVSCode.png)
   - rút gọn hình dưới dạng link, nguời xem mở ra khi cần thiết, ví dụ [mdwithVSCode.png](/screenshot/mdwithVSCode.png)

- chia files report thành cấu trúc rõ ràng
   - cho phép đánh chỉ mục sau này ,sử dụng `markdown toc`

## Sử dụng git
### quản  lý công việc của bản  thân
- sử dụng `commit` để kiểm soát thay đổi
- tổ chức công việc theo `commit`, hoặc `branch` với các việc độc lập 
- sử dụng `git history` để review lại công việc đã thực hiện 
- báo cho người khác bằng `Pull Request` hoặc `Merge Request` 
   - trao đổi, thảo luận vấn đề với người khác 
   - review công việc của mình, xác nhận kết quả 
### học hỏi, review công việc của người khác
- xem `commit history` để học tập, ví dụ, [commit](https://github.com/baotnq/report-by-md/commits/master)

- xem `code diff` để biết cách thực hiện, đã fix
  - ví dụ commit [link](https://github.com/baotnq/report-by-md/commit/02be7480e1d6cc0b0b1254ef19850d9644ac6fbc)
  
- comment, trao đổi để nhờ giải thích chi tiết hơn.
  - trên từng commit link hoặc trên từng dòng thay đổi 

### Kết hợp với VS Code
- hỗ trợ viết nhanh so với trên browser, viết thẳng trên github, gitlab
- Cho phép `Preview` file .md nhanh chóng 
- tích hợp Terminal trực tiếp vào VS Code, shortcut `Ctrl + `` 
- tích hợp tốt với git, sử dụng extenstion `GitLen`, `Git History`
   - git clone, commit, push, pull, ..., xem hình 
   ![vsCode Tips](/screenshot/vscode-tips.png)

#### Sử dụng GitLen, Git History
> Cập nhật sau 




