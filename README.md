# blog-exam

## Công nghệ cần dùng
- Backend: `Laravel`
- Database: `MySQL`
- Frontend: `NextJS`, `ReactJS`, `TypeScript`, `SCSS`.
- Công cụ nên dùng: `HeidiSQL` (Quản lý Database), `IntellIj` (Code IDE).

## Tóm tắt yêu cầu
Tạo 1 trang báo online, có thể tương tác giữa tác và người đọc.

## Mô tả về người dùng
Có 3 vai trò người dùng bao gồm:
- Người đọc
- Nhà báo
- Quản trị viên của trang

Các tính năng chung của người dùng:
- Có thể đăng nhập, hoặc đăng xuất.
- Có thể thay ảnh đại diện.
- Có thể xem và sửa thông tin cá nhân.
- Có thể chọn đăng ký là nhà báo hoặc người đọc.

## Yêu cầu tính năng

### Nhà báo
#### Yêu cầu cơ bản
- Có thể xem và quản lý các bài viết của bản thân (thêm, sửa, xóa).
#### Yêu cầu nâng cao
- Có thể viết bài bằng cú pháp markdown.
- Có thể xem và trả lời các bình luận trong bài viết của bản thân.
- Có thể nhận được thông báo mỗi khi có người đọc bình luận vào bài viết.
### Người đọc
#### Yêu cầu cơ bản
- Có thể xem danh sách 25 bài báo mới nhất ở trang chủ, có thể cuộn xuống để xem thêm.
- Có thể xem danh sách TOP 10 bài báo được đọc nhiều nhất ở trang chủ.
- Có thể xem nội dung của từng bài báo.
- Có thể xem được tên tác giả và lần cập nhật cuối trong mỗi bài viết.
- Có thể viết bình luận trên các bài viết.
- Nếu chưa đăng nhập thì không thể bình luận vào các bài báo.
- Nếu phần bình luận có tác giả trả lời thì có thể biết được ai là tác giả thông qua nhận diện ui/ux.

#### Yêu cầu nâng cao
- Có thể like/dislike hoặc trả lời các bình luận của người đọc khác.
- Có thể thêm các người đọc khác làm bạn bè thông qua giao diện bình luận của bài viết.
- Có thể xem được danh sách bạn bè ở profile.
- Có thể bấm theo dõi các tác giả yêu thích thông qua giao diện của bài viết.
- Có thể tag bạn bè vào một bài viết hoặc bình luận.
- Có thể nhận được thông báo mỗi khi được bạn bè tag trong bình luận của bài viết hoặc mỗi khi tác giả yêu thích có bài đăng mới.
- Có thể xem số thông báo chưa đọc tại giao diện chính.
- Có thể xem danh sách 10 thông báo mới nhất, cuộn chuột xuống để xem thêm.
- Có thể gỡ bỏ 1 thông báo bất kỳ.
### Quản trị viên
#### Yêu cầu cơ bản
- Có thể đăng nhập, hoặc đăng xuất.
- Có thể quản lý các user khác, không bao gồm user có cùng quyền hạn.
#### Yêu cầu nâng cao
- Có thể cấm người đọc hoặc nhà báo khỏi trang.
- Khi người đọc hoặc nhà báo bị cấm thì không thể đăng nhập, đồng thời hiển thị lý do bị cấm.
- Có thể xem xếp hạng của các nhà báo theo thứ hạng được yêu thích nhiều nhất, có nhiều bài viết nhất và ngược lại.
- Có thể xem xếp hạng của các bài báo theo thứ hạng được yêu thích, nhiều người đọc nhất ngược lại.
