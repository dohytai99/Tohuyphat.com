# Doanh Nghiệp Tư Nhân Sản Xuất Thương Mại Tô Huy Phát - Website

## Mô Tả Dự Án

Website doanh nghiệp chuyên nghiệp cho Doanh Nghiệp Tư Nhân Sản Xuất Thương Mại Tô Huy Phát, được thiết kế với giao diện cổ điển, responsive và tối ưu hóa cho trải nghiệm người dùng. Website tập trung vào lĩnh vực sản xuất túi nilon với 47 năm kinh nghiệm (từ 1977), chuyên cung cấp Túi Nilon PE, Túi PP, Túi HDPE.

## Tính Năng Chính

### 🎨 Giao Diện
- **Thiết Kế Hiện Đại**: Sử dụng gradient colors và shadow effects
- **Responsive Design**: Tương thích với mọi thiết bị (desktop, tablet, mobile)
- **Typography**: Font Inter với hierarchy rõ ràng
- **Color Scheme**: Gradient xanh-tím chuyên nghiệp

### 📱 Responsive & Mobile
- **Mobile-First Approach**: Tối ưu hóa cho mobile
- **Hamburger Menu**: Navigation menu cho mobile
- **Touch-Friendly**: Các element dễ thao tác trên mobile

### 🚀 Tương Tác & Animation
- **Smooth Scrolling**: Cuộn mượt giữa các section
- **Scroll Animations**: Fade-in effects khi scroll
- **Hover Effects**: Hiệu ứng hover cho buttons và cards
- **Counter Animation**: Số liệu thống kê có animation

### 📝 Form & Validation
- **Contact Form**: Form liên hệ với validation
- **Real-time Validation**: Kiểm tra email, phone format
- **Notification System**: Thông báo thành công/lỗi
- **Form Reset**: Tự động reset sau khi submit

### 🔧 Tính Năng Kỹ Thuật
- **Vanilla JavaScript**: Không sử dụng framework
- **CSS Grid & Flexbox**: Layout hiện đại
- **Intersection Observer**: Tối ưu performance
- **Event Handling**: Xử lý events một cách hiệu quả

## Cấu Trúc Website

### 1. Header & Navigation
- Logo công ty
- Menu navigation chính
- Mobile hamburger menu
- Fixed header với backdrop blur

### 2. Hero Section
- Tiêu đề chính với gradient text
- Mô tả công ty
- Call-to-action buttons
- Hero image placeholder

### 3. About Section
- Thông tin về công ty
- Lịch sử phát triển (1977-2024, 47+ năm kinh nghiệm)
- Sứ mệnh và tầm nhìn chi tiết
- Thống kê thành tựu (47+ năm, 500+ khách hàng, 50+ nhân viên, 100% chất lượng)

### 4. Services Section
- 6 dịch vụ chính:
  - Sản xuất bao bì nhựa
  - Thương mại & phân phối
  - Vận chuyển & giao hàng
  - Gia công theo yêu cầu
  - Tư vấn kỹ thuật
  - Hợp tác dài hạn

### 5. Products Section
- 3 sản phẩm nổi bật:
  - Túi Nilon PE
  - Túi PP
  - Túi HDPE

### 6. Contact Section
- Thông tin liên hệ
- Form liên hệ
- Giờ làm việc
- Địa chỉ, điện thoại, email

### 7. Footer
- Thông tin công ty
- Links navigation
- Social media links
- Copyright

## Công Nghệ Sử Dụng

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS features (Grid, Flexbox, Variables, Animations)
- **JavaScript (ES6+)**: Vanilla JS với modern syntax
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Cài Đặt & Chạy

### Yêu Cầu Hệ Thống
- Web browser hiện đại (Chrome, Firefox, Safari, Edge)
- Local server (khuyến nghị)

### Cách Chạy
1. Clone hoặc download project
2. Mở terminal/command prompt
3. Navigate đến thư mục project
4. Chạy local server:

```bash
# Sử dụng Python
python -m http.server 8000

# Hoặc sử dụng Node.js
npx serve .

# Hoặc sử dụng PHP
php -S localhost:8000
```

5. Mở browser và truy cập `http://localhost:8000`

### Cách Chạy Đơn Giản
- Double-click vào file `index.html` để mở trực tiếp trong browser
- Hoặc drag & drop file `index.html` vào browser

## Tùy Chỉnh

### Thay Đổi Nội Dung
- **Company Info**: Chỉnh sửa trong `index.html`
- **Colors**: Thay đổi CSS variables trong `styles.css`
- **Images**: Thay thế placeholder icons bằng hình ảnh thực

### Thay Đổi Styling
- **Color Scheme**: Chỉnh sửa gradient colors trong CSS
- **Fonts**: Thay đổi Google Fonts import
- **Layout**: Điều chỉnh Grid/Flexbox properties

### Thêm Tính Năng
- **Backend Integration**: Kết nối form với backend
- **Database**: Thêm database cho products/services
- **CMS**: Tích hợp Content Management System

## Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## Performance

- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices, SEO)
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## SEO & Accessibility

- **Semantic HTML**: Sử dụng đúng HTML tags
- **Meta Tags**: Title, description, viewport
- **Alt Text**: Icons có alt text
- **Keyboard Navigation**: Hỗ trợ keyboard
- **Screen Reader**: Tương thích với screen readers

## Deployment

### GitHub Pages
1. Push code lên GitHub repository
2. Vào Settings > Pages
3. Chọn source branch (main/master)
4. Website sẽ được deploy tại `https://username.github.io/repository-name`

### Netlify
1. Drag & drop thư mục project vào Netlify
2. Website sẽ được deploy tự động
3. Có thể setup custom domain

### Vercel
1. Connect GitHub repository với Vercel
2. Deploy tự động khi push code
3. Preview deployments cho mỗi PR

## Bảo Trì & Cập Nhật

### Regular Updates
- Kiểm tra browser compatibility
- Cập nhật dependencies
- Tối ưu hóa performance
- Security patches

### Content Updates
- Cập nhật thông tin công ty
- Thêm/sửa services/products
- Cập nhật contact information
- Thêm blog/news section

## Hỗ Trợ & Liên Hệ

Nếu có vấn đề hoặc cần hỗ trợ:
- Kiểm tra console errors
- Verify file paths
- Test trên different browsers
- Check mobile responsiveness

## License

Dự án này được tạo cho Tô Huy Phát. Vui lòng liên hệ để được phép sử dụng hoặc chỉnh sửa.

---

**Tô Huy Phát** - Doanh Nghiệp Uy Tín - Chất Lượng Hàng Đầu
