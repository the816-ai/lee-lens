# Lee Lens

Ứng dụng quản lý bán hàng cho shop Lee Lens: tạo đơn, lưu khách hàng, lịch sử đơn hàng, doanh thu theo tháng, trạng thái thanh toán và hóa đơn dạng ảnh/in.

## Chức năng

- Tạo đơn Lens và phụ kiện
- Lưu độ cận, số lượng, đơn giá và giảm giá
- Quản lý tiền cọc/đã trả và công nợ
- Lịch sử đơn hàng theo tháng
- Doanh thu chỉ tính đơn Hoàn thành
- Sao chép hóa đơn thành ảnh và in hóa đơn
- Giao diện responsive cho máy tính và điện thoại
- Dữ liệu bền vững với Cloudflare D1

## Chạy dự án

Yêu cầu Node.js 22.13 trở lên.

```bash
pnpm install
pnpm dev
```

Sao chép `.openai/hosting.example.json` thành `.openai/hosting.json` khi triển khai bằng Sites. Dữ liệu đơn hàng thực tế không được lưu trong repository này.
