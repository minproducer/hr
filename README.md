# MinProducer HR Jobs Portal

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fhr.minproducer.com&style=for-the-badge&logo=firefox&logoColor=white)](https://hr.minproducer.com)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://minproducer.github.io/hr)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20Friendly-blue?style=for-the-badge&logo=mobile&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

🚀 **Trang web tuyển dụng hiện đại của MinProducer - Hiển thị các vị trí Infrastructure Full-stack Developer**

**🌐 Live Demo:** [hr.minproducer.com](https://hr.minproducer.com)

## 🎯 Tính năng chính

- ✅ **Job Display**: Hiển thị chi tiết Infrastructure Full-stack Developer position
- ✅ **Responsive Design**: Hoạt động mượt mà trên mọi thiết bị (desktop, tablet, mobile)
- ✅ **Direct Links**: Liên kết trực tiếp đến JD chi tiết và form ứng tuyển
- ✅ **Multi-Contact**: WhatsApp, Zalo, và các kênh liên hệ khác
- ✅ **Modern UI**: Giao diện hiện đại với animations và effects
- ✅ **Fast Loading**: Tối ưu tốc độ tải trang
- ✅ **SEO Friendly**: Chuẩn SEO cho tìm kiếm tốt hơn

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-339AF0?style=flat-square&logo=fontawesome&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-100000?style=flat-square&logo=github&logoColor=white)

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
    <p>MÔ TẢ NGẮN VỀ CÔNG VIỆC</p>
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

## 📁 Cấu trúc dự án

```
HR/
├── index.html      # File HTML chính
├── styles.css      # File CSS styling
├── CNAME          # Custom domain configuration
├── README.md      # Documentation
└── deploy-status.txt # Deploy status
```

## 🚀 Deployment

Trang web được deploy tự động lên GitHub Pages và có thể truy cập qua:

- **Production URL**: [hr.minproducer.com](https://hr.minproducer.com)
- **GitHub Pages URL**: [minproducer.github.io/hr](https://minproducer.github.io/hr)

### Deploy Process:

1. Push code lên `main` branch
2. GitHub Actions tự động build và deploy
3. Website được cập nhật trong vài phút

## 🎨 Customization

- **Colors**: Chỉnh sửa màu sắc trong `styles.css`
- **Content**: Cập nhật thông tin job trong `index.html`
- **Branding**: Thay đổi logo/tên công ty trong header
- **Layout**: Tùy chỉnh responsive breakpoints

## 🔧 Development

```bash
# Clone repository
git clone https://github.com/minproducer/hr.git

# Make changes
# Edit index.html or styles.css

# Deploy changes
git add .
git commit -m "Update job information"
git push origin main
```

## 📞 Contact & Support

- **Current Job**: Infrastructure Full-stack Developer
- **WhatsApp**: [+84 974 597 614](https://wa.me/84974597614)
- **Zalo**: 0974 597 614 (HM Travel)
- **JD Details**: [hr.minproducer.com/fullstackdevInfrastructure](https://hr.minproducer.com/fullstackdevInfrastructure)

---

⭐ **Nếu project này hữu ích, hãy cho một star nhé!** ⭐
