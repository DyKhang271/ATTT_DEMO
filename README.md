📘 ATTT_DEMO — Mô phỏng An toàn Thông tin (Interactive Demo)

🚀 ATTT_DEMO là một trang web tương tác mô phỏng lại các kỹ thuật cốt lõi trong An toàn thông tin, bao gồm:

Hàm băm (SHA-256)

Mã hóa đối xứng (AES-GCM)

Mã hóa bất đối xứng (RSA-OAEP)

Chữ ký số (RSA-PSS)

Chứng thực đa yếu tố (password + OTP + biometrics demo)

Blockchain mini (hash-linked blocks)

Website được xây dựng thuần HTML + CSS + JavaScript, không dùng thư viện ngoài, chạy trực tiếp trên GitHub Pages.

🌐 Demo Website

👉 Truy cập trang web tại:

🔗 https://dykhang271.github.io/ATTT_DEMO/
🎯 Tính năng chính
🔐 1. Hàm băm (SHA-256)

Người dùng nhập dữ liệu

Web tính toán giá trị hash và hiển thị dạng HEX

Minh họa tính một chiều và độ nhạy đầu vào

🔑 2. Mã hóa đối xứng (AES-256-GCM)

Sinh khóa bí mật 256-bit

Mã hóa → sinh IV → tạo ciphertext

Giải mã → trả về plaintext

Demo hoàn chỉnh quá trình encrypt/decrypt

🔑 3. Mã hóa bất đối xứng (RSA-2048 OAEP)

Sinh cặp private/public key

Mã hóa bằng khóa công khai

Giải mã bằng khóa riêng

Giải thích lý do RSA chỉ nên mã hóa dữ liệu nhỏ

✍️ 4. Chữ ký số (RSA-PSS)

Sinh cặp khóa ký số

Tạo digital signature từ nội dung

Kiểm tra tính hợp lệ của chữ ký

Minh họa tính toàn vẹn, xác thực nguồn gốc, chống chối bỏ

🧑‍💻 5. Chứng thực & Sinh trắc học

Đăng nhập 3 yếu tố (3FA):

Mật khẩu

OTP

Sinh trắc (fingerprint / face – mô phỏng)

Giải thích từng yếu tố trong Authentication

⛓️ 6. Blockchain mini-demo

Thêm block mới vào chuỗi

Tự động tính toán hash và prevHash

Cho phép giả mạo dữ liệu block #1 → chain bị gãy

Minh họa nguyên lý tamper-evident của blockchain

🏗️ Công nghệ sử dụng

HTML5

CSS3

JavaScript (Web Crypto API)

Không cần backend

Chạy trực tiếp trên GitHub Pages

📁 Cấu trúc dự án
ATTT_DEMO/
│
├── index.html        # File web chính
├── README.md         # Mô tả dự án
└── (các file assets nếu thêm sau)

🚀 Cách chạy trên GitHub Pages

Commit file index.html vào nhánh main

Vào: Settings → Pages

Chọn nguồn:

Source: Deploy from a branch

Branch: main

Folder: / (root)

Bấm Save

Website tự động hoạt động tại:

https://<username>.github.io/<repo-name>/

📸 Giao diện

(Bạn có thể thêm screenshot sau nếu muốn — mình có thể tạo ảnh mô phỏng giúp bạn.)

🤝 Đóng góp

Nếu bạn muốn:

Nâng cấp UI/UX

Tách code ra file JS/CSS riêng

Thêm phần mô phỏng tấn công ATTT (XSS, SQLi, brute-force…)

Thêm dark/light mode

Mình có thể hỗ trợ build thêm.

📄 Giấy phép

Dự án dành cho mục đích học tập và nghiên cứu, không khuyến khích sử dụng cho mục đích xấu.

💬 Liên hệ / Hỗ trợ

Nếu bạn muốn phát triển thêm tính năng hoặc tối ưu giao diện, cứ hỏi mình — mình hỗ trợ thêm miễn phí.
