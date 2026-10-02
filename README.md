# Phiếu khảo sát dịch vụ ứng lương — 30Shine 2026

Trang phiếu để nhân sự salon điền trên điện thoại. Chỉ chứa phần giao diện.

> [!IMPORTANT]
> Repo này là **public** vì GitHub Pages cần vậy. Chỉ đặt ở đây trang phiếu và
> logo. Nguồn nội dung, tài liệu thiết kế, thông báo trình ký và phiếu Word nằm
> ở repo riêng **private** `30shine-khao-sat-ung-luong-2026`.
>
> **Không bao giờ** đưa câu trả lời của nhân sự vào repo này — câu trả lời nằm
> trong Google Sheet riêng, chia sẻ hạn chế.

## Sửa nội dung phiếu

Đừng sửa `index.html` ở đây. Sửa `noi-dung/noidung.py` trong repo private rồi
chạy `scripts/xuat.py` — file sẽ được sinh lại và đồng bộ sang đây.

## Deploy

Push nhánh `main`, workflow `.github/workflows/deploy.yml` tự đẩy lên GitHub Pages.
