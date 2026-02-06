# 🎓 SmartSchool - Hệ thống Quản lý Giáo dục Thông minh

## Tổng quan

Một hệ thống quản lý giáo dục hiện đại, toàn diện được xây dựng với HTML, CSS, JavaScript và Firebase. Hệ thống giúp nhà trường số hóa toàn bộ quy trình từ quản lý hồ sơ học sinh đến tài chính.

## ✨ Tính năng chính

### 1. Dashboard (Bảng điều khiển)
- **Thống kê tổng quan**: Tổng số học sinh, học sinh mới, học sinh vắng, nợ học phí
- **Biểu đồ trực quan**: 
  - Phân bố học lực (Giỏi, Khá, Trung bình, Yếu)
  - Tỷ lệ Nam/Nữ  
  - Xu hướng theo thời gian
- **Thông báo & Sự kiện**: Hiển thị các sự kiện sắp tới, hạn nộp điểm
- **Chỉ số quan trọng**: Xu hướng tăng/giảm so với năm trước

### 2. Quản lý Hồ sơ Học sinh
- **Danh sách học sinh**: Hiển thị dạng bảng với đầy đủ thông tin
- **Tìm kiếm & Lọc**: 
  - Tìm kiếm theo tên, mã học sinh
  - Lọc theo lớp, khối
  - Lọc theo trạng thái (Đang học, Bảo lưu, Nghỉ học)
- **CRUD Operations**:
  - Thêm học sinh mới
  - Xem chi tiết hồ sơ
  - Chỉnh sửa thông tin
  - Xóa/Chuyển trạng thái
- **Import/Export**:
  - Nhập hàng loạt từ file Excel
  - Xuất danh sách ra Excel
- **Thông tin chi tiết**:
  - Ảnh thẻ, họ tên, giới tính, ngày sinh
  - Dân tộc, tôn giáo
  - Địa chỉ, số điện thoại
  - Thông tin gia đình (Cha/Mẹ, nghề nghiệp, SĐT khẩn cấp)

### 3. Quản lý Lớp học
- **Danh sách lớp**: Hiển thị tất cả lớp đang hoạt động
- **Thông tin lớp**:
  - Sĩ số (Nam/Nữ)
  - Giáo viên chủ nhiệm
  - Phòng học
  - Thời khóa biểu
- **Phân lớp**: Xếp học sinh vào lớp đầu năm hoặc chuyển lớp
- **Thống kê**: Sĩ số trung bình, tỷ lệ đầy lớp

### 4. Quản lý Học vụ & Điểm số
- **Sổ điểm điện tử**:
  - Nhập điểm theo môn, theo lớp
  - Các loại điểm: Miệng, 15 phút, 1 tiết, Thi học kỳ
  - Tự động tính điểm trung bình
- **Xếp loại học lực**: 
  - Tự động phân loại (Giỏi, Khá, Trung bình, Yếu)
  - Dựa theo quy chế tính điểm
- **Quản lý hạnh kiểm**: Đánh giá rèn luyện theo kỳ/năm
- **Lịch sử học tập**: Lưu trữ kết quả các năm trước (Học bạ điện tử)

### 5. Điểm danh
- **Điểm danh theo ngày**: Chấm công hàng ngày
- **Điểm danh theo tiết**: Theo dõi chi tiết từng tiết học
- **Lý do vắng**: 
  - Có phép/Không phép
  - Ghi chú chi tiết
- **Thống kê chuyên cần**:
  - Tỷ lệ đi học
  - Học sinh vắng nhiều
  - Báo cáo theo tháng/học kỳ

### 6. Quản lý Tài chính & Học phí
- **Theo dõi công nợ**:
  - Học phí phải đóng
  - Đã đóng
  - Còn nợ
- **Các khoản thu**:
  - Học phí
  - Tiền ăn, bán trú
  - Bảo hiểm y tế
  - Đồng phục
- **Xuất hóa đơn/Biên lai**: In phiếu thu hoặc gửi qua email/SMS
- **Nhắc nợ tự động**: Gửi thông báo nhắc nợ cho phụ huynh
- **Báo cáo tài chính**: Thống kê thu chi theo tháng/năm

### 7. Báo cáo & Thống kê
- **Xuất báo cáo**:
  - Danh sách học sinh (Excel/PDF)
  - Bảng điểm tổng hợp
  - Sổ gọi tên
  - Báo cáo chuyên cần
  - Báo cáo tài chính
- **Mẫu chuẩn**: Theo quy định của Bộ Giáo dục
- **Tùy chỉnh**: Chọn lọc thông tin cần xuất

## 🎨 Thiết kế UI/UX

### Màu sắc & Thương hiệu
- **Primary**: Indigo (#6366f1) - Chuyên nghiệp, tin cậy
- **Success**: Emerald (#10b981) - Tích cực, hoàn thành
- **Warning**: Amber (#f59e0b) - Cảnh báo, chú ý
- **Danger**: Red (#ef4444) - Khẩn cấp, lỗi
- **Dark**: Slate (#0f172a) - Sidebar, header

### Typography
- **Font**: Plus Jakarta Sans - Hiện đại, dễ đọc
- **Weight**: 300-800 - Linh hoạt cho nhiều mục đích

### Components
- **Stats Cards**: Thẻ thống kê với icon, giá trị, xu hướng
- **Charts**: Biểu đồ cột, tròn với Chart.js
- **Tables**: Bảng dữ liệu với hover, sort, filter
- **Modal**: Form nhập liệu overlay
- **Buttons**: Primary, Success, Outline, Danger
- **Badges**: Trạng thái màu sắc

### Responsive
- **Desktop**: Full features
- **Tablet**: Sidebar thu gọn
- **Mobile**: Navigation dạng hamburger menu

## 🔧 Công nghệ sử dụng

### Frontend
- **HTML5**: Cấu trúc semantic
- **CSS3**: Variables, Grid, Flexbox, Animations
- **JavaScript ES6+**: Modules, Async/Await, Arrow Functions

### Backend & Database
- **Firebase**:
  - Authentication: Đăng nhập/Đăng xuất
  - Realtime Database: Lưu trữ dữ liệu học sinh, điểm, điểm danh
  - Hosting: Deploy lên Firebase Hosting

### Libraries
- **Chart.js**: Vẽ biểu đồ
- **SweetAlert2**: Thông báo đẹp
- **SheetJS (XLSX)**: Import/Export Excel
- **Font Awesome**: Icons

## 🚀 Hướng dẫn cài đặt

### 1. Cấu hình Firebase

```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    databaseURL: "https://YOUR_PROJECT.firebaseio.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
};
```

### 2. Tạo tài khoản Admin đầu tiên

- Mở trang web
- Click "Tạo tài khoản demo"
- Email: `admin@school.com`
- Mật khẩu: `123456`

### 3. Import dữ liệu học sinh từ Excel

**Format Excel yêu cầu**:

| Họ Tên | Lớp | Giới tính | Ngày sinh | Mã HS | SĐT | Phụ huynh | Địa chỉ |
|--------|-----|-----------|-----------|-------|-----|-----------|---------|
| Nguyễn Văn A | 1A | Nam | 2015-01-01 | HS001 | 0901234567 | Nguyễn Văn B | 123 ABC |

## 📱 Tính năng nâng cao (Roadmap)

### Phase 2
- [ ] Phân quyền người dùng (Admin, Giáo viên, Phụ huynh)
- [ ] Gửi tin nhắn/Email cho phụ huynh
- [ ] Quản lý thư viện
- [ ] Quản lý y tế
- [ ] Lịch sử khen thưởng/kỷ luật

### Phase 3
- [ ] Mobile App (React Native)
- [ ] Tích hợp thanh toán online
- [ ] AI phân tích học lực
- [ ] Chatbot hỗ trợ

## 🎯 Người dùng mục tiêu

1. **Quản trị viên**: Toàn quyền quản lý hệ thống
2. **Giáo viên**: Xem lớp mình dạy, nhập điểm, điểm danh
3. **Phụ huynh**: Xem thông tin con em (tính năng tương lai)

## 📊 Database Structure

```
/students
  /{studentId}
    - name: string
    - code: string
    - class: string
    - gender: string
    - dob: string
    - parent: string
    - phone: string
    - address: string
    - ethnic: string
    - status: string
    - createdAt: timestamp

/grades
  /{studentId}
    /{subject}
      - midterm: number
      - final: number
      - average: number
      - rank: string

/attendance
  /{date}
    /{studentId}
      - status: string (present/absent)
      - reason: string
      - note: string

/finance
  /{studentId}
    - totalFee: number
    - paid: number
    - debt: number
    - history: array
```

## 🔐 Bảo mật

- ✅ Firebase Authentication
- ✅ Realtime Database Rules
- ✅ HTTPS only
- ✅ Input validation
- ⏳ Role-based access control (đang phát triển)

## 📝 License

MIT License - Free to use for educational purposes

## 👥 Đóng góp

Mọi đóng góp đều được chào đón! Hãy tạo Pull Request hoặc Issue nếu bạn phát hiện lỗi hoặc có ý tưởng mới.

## 📞 Hỗ trợ

- Email: support@smartschool.com
- Documentation: [Link to docs]
- Demo: [Link to live demo]

---

**Developed with ❤️ for Vietnamese Schools**
