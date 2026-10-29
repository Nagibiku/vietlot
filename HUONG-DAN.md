# Đưa trang Thống kê Vietlott lên mạng (miễn phí, GitHub Pages)

Trang là một file tĩnh duy nhất: `index.html`. Mỗi lần mở trang, trình duyệt tự tải kết quả mới nhất
từ kho dữ liệu công khai vietvudanh/vietlott-data (kho này tự cập nhật mỗi ngày).
Nếu tải lỗi (mất mạng, GitHub bận), trang dùng bản dữ liệu đã nhúng sẵn đến ngày 28/10/2026.
Góc trên bên phải của trang cho biết đang dùng dữ liệu nào.

## Các bước

1. Đăng ký tài khoản miễn phí tại https://github.com (nếu chưa có).
2. Bấm **New repository**, đặt tên ví dụ `vietlott`, chọn **Public**, bấm **Create repository**.
3. Bấm **uploading an existing file**, kéo file `index.html` vào, bấm **Commit changes**.
4. Vào **Settings > Pages**. Ở mục **Branch** chọn `main` và thư mục `/ (root)`, bấm **Save**.
5. Sau 1 đến 2 phút, trang có địa chỉ dạng `https://TEN-CUA-BAN.github.io/vietlott/`.

Có thể thay GitHub Pages bằng Netlify hoặc Cloudflare Pages: kéo thả file `index.html` là xong.

## Lưu ý

- Dữ liệu mới có độ trễ vì kho nguồn cập nhật theo lịch của họ (thường sau mỗi kỳ quay) và GitHub lưu đệm khoảng 5 phút.
- Nếu kho nguồn đổi tên, đổi nhánh hoặc ngừng cập nhật, trang sẽ quay về bản nhúng sẵn. Khi đó sửa hai địa chỉ trong biến `SRC` ở đầu đoạn script.
- Kết quả chính thức luôn lấy theo vietlott.vn. Trang chỉ mang tính tham khảo và giải trí.
