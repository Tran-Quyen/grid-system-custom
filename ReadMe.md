Grid System?

1. Xuất hiện từ đầu thế kỷ XX trong phong trào (Constructivism) nghệ thuật/kiến trúc
2. Tạo nên các khung nền, hỗ trợ việc sắp xếp bố cục theo trật tự/thống nhất/cân bằng
3. Hệ thống lưới thường gặp

- Lưới nhiều cột (Mutilcolumn grid) (\*)
- Lưới một cột (Single column grid) (\*)
- Lưới module (Modular grid)
- Lưới đường cơ sở (Baseline grid)

4. Vai trò:

- Tổ chức: Có các đường căn gióng tiện lợi, dễ dàng sắp xếp các thành phần được ngăn nắp
- Cân bằng: Dù là đối xứng / bất đối xứng, mang lại cái nhìn trực quan, đảm bảo sự cân bằng
- Tách biệt thành phần: Phân chia nội dung, tạo khoảng cách các thành phần hiệu quả

5. Ứng dụng

- Lưới trong thiết kế UI UX: Vai trò đặc biệt quan trọng trong Responsive web desgin (\*)
- Lưới in ấn: Google "Grid system"

6. Responsive web desgin

- Grid <> CSS Grid
- Grid: Thành phần cha
- Row: Dòng
- Column: Cột
- Gutter: Khoảng cách giữa 2 Column

---

Grid System - part 2

I. Thành phần chính (lý thuyết)

1. Column - Cột
   Độ rộng sử dụng đơn vị % (tương đối) giúp linh động dễ dàng
   tương thích với độ rộng khác nhau của các thiết bị.Số lượng cột
   trong grid system được xác định trước (VD: PC 12|16 cột, tablet 8 cột, mobile 4 cột)

2.Gutter - Đường ngăn cách (rãnh ngăn)
Là khoảng cách 2 phía của 1 cột, tạo nên rãnh ngăn giữa các cột. Độ rộng rãnh ngăn có thể thay đổi cho phù hợp với thiết kế hoặc độ rộng màn hình (VD: PC/Tablet 24px, mobile 16px)

3. Margin - Phần lề
   Là khoảng cách 2 bên trái/phải của bố cục chính của website. Độ rộng phần lề thay đổi để phù hợp với các kích thước màn hình.VD: Phần lề lớn sẽ thích hợp với màn hình lớn như PC,phần lề nhỏ thích hợp cho màn hình nhỏ như Tablet,Mobile

II. Thành phần chính (làm việc với CSS)

    1. Grid - Lưới (Thường là phần cha chứa Row và Column)
    2. Row - Dòng (Dòng - chiều ngang, chưa Column)
    3. Column - Cột (Chứa content/component trên website)
