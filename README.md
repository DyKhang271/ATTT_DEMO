# 📘 ATTT_DEMO – Mô phỏng An toàn Thông tin

Repo này là một **web demo tương tác** mô phỏng các kỹ thuật cơ bản trong An toàn thông tin:

- 🔁 Hàm băm: **SHA-256**
- 🔐 Mã hóa đối xứng: **AES-256-GCM**
- 🧬 Mã hóa bất đối xứng: **RSA-2048 (RSA-OAEP)**
- ✍️ Chữ ký số: **RSA-PSS / SHA-256**
- ✅ Chứng thực đa yếu tố: **mật khẩu + OTP + sinh trắc (demo)**
- ⛓️ Blockchain mini: **chuỗi khối linked bằng hash**

Website viết **thuần HTML + CSS + JavaScript**, dùng **Web Crypto API**, không cần backend.

---

## 🌐 Demo

👉 **Link chạy trực tiếp:**  
https://dykhang271.github.io/ATTT_DEMO/

---

## ⚙️ Cách dùng nhanh

1. Mở link demo ở trên.
2. Dùng thanh **menu trên cùng** để nhảy đến từng chức năng:
   - `Hàm băm`, `Mã đối xứng`, `Mã bất đối xứng`, `Chữ ký số`, `Chứng thực & Sinh trắc`, `Blockchain`.
3. Mỗi phần chỉ chạy khi bạn **bấm nút**:
   - Nhập dữ liệu 👉 bấm nút 👉 xem kết quả (hash, ciphertext, chữ ký, trạng thái chain,…).

---

## 🧩 Cấu trúc dự án

```bash
ATTT_DEMO/
├── index.html   # Toàn bộ giao diện + logic demo
└── README.md    # File mô tả này
