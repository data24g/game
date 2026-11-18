# 🚀 Word Shooter

Mini game gõ từ tiếng Anh đang rơi để bắn hạ, giống Parroto nhưng bạn tự nhập danh sách từ cần học.

## Tính năng
- Nhập danh sách từ tuỳ ý, mỗi dòng một từ, có thể kèm nghĩa: `apple - quả táo`
- 3 chế độ: gõ từ tiếng Anh / thấy nghĩa tiếng Việt rồi gõ từ tiếng Anh / hỗn hợp (tỉ lệ tiếng Việt tăng dần từ 10% đến 80%)
- Chế độ **Nối thẻ** kiểu Pikachu: thẻ tiếng Anh và nghĩa tiếng Việt đan xen trên cùng một bảng. Chọn 2 thẻ tương ứng, nối được bằng đường tối đa 2 góc (không xuyên qua thẻ khác) thì cả hai biến mất và được cộng điểm. Có nút Gợi ý, Xáo, tự xáo khi hết nước đi; hết thẻ thì qua màn mới (tự động hoặc bấm nút)
- Tự lưu danh sách từ trong trình duyệt (localStorage)
- Cuối ván hiện danh sách từ cần ôn lại

## Chạy thử trên máy
Mở file `index.html` bằng trình duyệt, không cần cài đặt hay build.

## Deploy lên GitHub Pages
1. Tạo repository mới trên GitHub, upload 3 file: `index.html`, `README.md`, `.nojekyll`
   (hoặc `git init`, `git add .`, `git commit`, `git push` lên nhánh `main`).
2. Vào **Settings → Pages**.
3. Ở mục **Build and deployment**, chọn **Source: Deploy from a branch**, **Branch: main**, thư mục **/ (root)**, rồi bấm **Save**.
4. Đợi 1 đến 2 phút, trang sẽ chạy tại `https://<username>.github.io/<tên-repo>/`.
