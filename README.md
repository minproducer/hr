# HR Jobs Portal

Trang web tuyển dụng đơn giản để hiển thị các vị trí công việc đang tuyển.

## Tính năng

- ✅ Hiển thị danh sách công việc với thông tin chi tiết
- ✅ Design responsive, hoạt động tốt trên mobile
- ✅ Liên kết đến JD chi tiết
- ✅ Thông tin liên hệ trực tiếp
- ✅ Giao diện đẹp mắt, chuyên nghiệp

## Cách sử dụng

### Thêm công việc mới

1. Mở file `index.html`
2. Tìm section `<div class="jobs-list">`
3. Copy một job card có sẵn và chỉnh sửa thông tin:

```html
<div class="job-card">
  <div class="job-header">
    <div>
      <h3 class="job-title">TÊN CÔNG VIỆC</h3>
      <p class="job-company">TÊN CÔNG TY</p>
    </div>
    <div class="job-badges">
      <span class="badge full-time">LOẠI HÌNH</span>
      <span class="badge junior">CẤP BẬC</span>
    </div>
  </div>

  <div class="job-meta">
    <span><i class="fas fa-map-marker-alt"></i> ĐỊA ĐIỂM</span>
    <span><i class="fas fa-dollar-sign"></i> LƯƠNG</span>
    <span><i class="fas fa-calendar"></i> THỜI GIAN ĐĂNG</span>
  </div>

  <div class="job-description">
    <p>MÔ TÃ NGẮN VỀ CÔNG VIỆC</p>
  </div>

  <div class="job-actions">
    <a href="LINK_TO_JD" class="btn-jd" target="_blank">
      <i class="fas fa-file-alt"></i> Xem JD Chi Tiết
    </a>
    <div class="job-contact">
      <i class="fas fa-envelope"></i>
      <a href="mailto:EMAIL_LIÊN_HỆ">EMAIL_LIÊN_HỆ</a>
    </div>
  </div>
</div>
```

### Các loại badge có sẵn

**Loại hình công việc:**

- `full-time` - Full-time (màu xanh)
- `part-time` - Part-time (màu tím)
- `contract` - Hợp đồng (màu xanh lá)
- `internship` - Thực tập (màu cam)

**Cấp bậc:**

- `intern` - Thực tập sinh
- `junior` - Junior
- `mid` - Middle
- `senior` - Senior

### Cập nhật số lượng job

Nhớ cập nhật số lượng job trong phần header:

```html
<span
  ><i class="fas fa-fire"></i> Đang có <strong>SỐ_LƯỢNG</strong> vị trí
  hot</span
>
```

## Cấu trúc files

```
HR/
├── index.html      # File HTML chính
├── styles.css      # File CSS styling
└── README.md       # File hướng dẫn này
```

## Chạy trang web

1. Mở file `index.html` bằng trình duyệt web
2. Hoặc host trên web server để có URL trực tuyến

## Tùy chỉnh

- Thay đổi màu sắc trong file `styles.css`
- Cập nhật logo/tên công ty trong header
- Thêm/bớt thông tin hiển thị cho mỗi job card
