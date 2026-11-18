<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH XD&TM PHẠM GIA - Thiết Kế & Thi Công Xây Dựng Trọn Gói Đà Nẵng | xaydungphamgia.com</title>
  <meta name="description" content="CÔNG TY TNHH XD&TM PHẠM GIA (xaydungphamgia.com) chuyên Thiết kế Kiến trúc - Nội thất, Thi công phần thô, Thi công hoàn thiện và Xây nhà trọn gói uy tín tại Đà Nẵng. Địa chỉ: 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0905.736.536" />
  <meta name="keywords" content="xaydungphamgia.com, Công ty TNHH XD&TM Phạm Gia, xây dựng Phạm Gia Đà Nẵng, xây nhà trọn gói Đà Nẵng, thi công phần thô Đà Nẵng, thiết kế kiến trúc nội thất Đà Nẵng" />
  <link rel="canonical" href="https://xaydungphamgia.com/" />

  <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://xaydungphamgia.com/" />
  <meta property="og:site_name" content="xaydungphamgia.com - CÔNG TY TNHH XD&TM PHẠM GIA" />
  <meta property="og:title" content="CÔNG TY TNHH XD&TM PHẠM GIA | Thiết Kế & Xây Dựng Trọn Gói Đà Nẵng" />
  <meta property="og:description" content="Chuyên Thiết kế - Thi công phần thô - Hoàn thiện - Nội thất các công trình Nhà phố, Biệt thự, Căn hộ, Khách sạn, Văn phòng tại Đà Nẵng. Hotline: 0905.736.536" />
  <meta property="og:image" content="https://placehold.co/1200x630/0b2e59/f59e0b.png?text=PHAM+GIA+CONSTRUCTION+%7C+xaydungphamgia.com" id="og-logo-thumb" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH XD&TM PHẠM GIA - xaydungphamgia.com" />
  <meta name="twitter:image" content="https://placehold.co/1200x630/0b2e59/f59e0b.png?text=PHAM+GIA+CONSTRUCTION+%7C+xaydungphamgia.com" />

  <!-- Google Fonts: Inter & Montserrat chuẩn giao diện Flatsome hiện đại -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            pgBlue: '#0B2E59',      /* Xanh Navy đậm chủ đạo của Logo Phạm Gia */
            pgBlueDark: '#071F3D',  /* Xanh Navy sâu */
            pgBlueLight: '#164B8A', /* Xanh trung gian */
            pgGold: '#D97706',      /* Vàng cam kiến trúc chủ đạo của Logo */
            pgGoldLight: '#F59E0B', /* Vàng sáng điểm nhấn */
            pgBg: '#F8FAFC'
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            heading: ['Montserrat', 'sans-serif']
          }
        }
      }
    };
  </script>

  <style>
    /* ==========================================================================
       CHUẨN HÓA KHUNG GIAO DIỆN FLATSOME (KHÔNG TRÀN VIỀN, KHÔNG LỆCH PHẢI)
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #F8FAFC;
      color: #1E293B;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95vw;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Thanh danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 2px 4px;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .desktop-nav-item {
      position: relative;
      white-space: nowrap; /* Tuyệt đối không xuống dòng tên danh mục */
    }

    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      padding: 7px 9px;
      font-size: 12.5px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.01em;
      color: #0B2E59;
      white-space: nowrap;
      border-radius: 6px;
      transition: all 0.2s ease;
    }

    @media (min-width: 1280px) {
      .desktop-nav-link {
        font-size: 13px;
        padding: 8px 11px;
      }
    }

    .desktop-nav-link:hover,
    .desktop-nav-link.active {
      color: #D97706;
      background-color: rgba(217, 119, 6, 0.08);
    }

    /* Dropdown menu chuẩn Flatsome */
    .flatsome-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 230px;
      background: #ffffff;
      border-top: 3px solid #D97706;
      box-shadow: 0 12px 28px rgba(11, 46, 89, 0.15);
      border-radius: 0 0 8px 8px;
      padding: 6px 0;
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 100;
    }

    .desktop-nav-item:hover .flatsome-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .flatsome-dropdown a {
      display: block;
      padding: 8px 16px;
      font-size: 12.5px;
      font-weight: 600;
      color: #1E293B;
      white-space: nowrap;
      transition: all 0.15s ease;
    }

    .flatsome-dropdown a:hover {
      background-color: #F1F5F9;
      color: #D97706;
      padding-left: 20px;
    }

    /* Nút lọc danh mục ở trang chủ: chữ nhỏ gọn, viết liền trên 1 hàng, không rớt chữ */
    .cat-filter-bar {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 6px;
    }

    .cat-pill-btn {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      padding: 6px 12px;
      border-radius: 6px;
      border: 1px solid #CBD5E1;
      background-color: #FFFFFF;
      color: #0B2E59;
      transition: all 0.2s ease;
      cursor: pointer;
    }

    .cat-pill-btn:hover,
    .cat-pill-btn.active {
      background-color: #0B2E59;
      border-color: #0B2E59;
      color: #FFFFFF;
    }

    /* 2 Ảnh Banner tự trượt kích thước bằng nhau tuyệt đối, chữ cách xa viền */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      height: 360px;
      overflow: hidden;
      border-radius: 12px;
      background-color: #071F3D;
    }

    @media (min-width: 640px) {
      .hero-slider-wrapper {
        height: 430px;
      }
    }

    @media (min-width: 1024px) {
      .hero-slider-wrapper {
        height: 500px;
      }
    }

    .hero-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.75s ease-in-out, visibility 0.75s ease-in-out;
    }

    .hero-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 10;
    }

    /* Đảm bảo chữ và hình nằm gọn bên trong và cách xa viền ảnh banner */
    .hero-safe-box {
      width: 100%;
      height: 100%;
      padding: 32px 36px;
      display: flex;
      align-items: center;
    }

    @media (min-width: 640px) {
      .hero-safe-box {
        padding: 48px 64px;
      }
    }

    @media (min-width: 1024px) {
      .hero-safe-box {
        padding: 60px 90px;
      }
    }

    /* Card Sản phẩm / Công trình chuẩn Flatsome: Tên sản phẩm đầy đủ, không cắt chữ, không tràn */
    .flatsome-col-box {
      background: #FFFFFF;
      border: 1px solid #E2E8F0;
      border-radius: 8px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      height: 100%;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .flatsome-col-box:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 24px rgba(11, 46, 89, 0.1);
    }

    .flatsome-box-image {
      position: relative;
      width: 100%;
      aspect-ratio: 4 / 3;
      background-color: #E2E8F0;
      overflow: hidden;
    }

    .flatsome-box-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.45s ease;
    }

    .flatsome-col-box:hover .flatsome-box-image img {
      transform: scale(1.05);
    }

    .flatsome-box-text {
      padding: 10px 10px 12px 10px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      flex-grow: 1;
    }

    @media (min-width: 768px) {
      .flatsome-box-text {
        padding: 12px 14px 14px 14px;
      }
    }

    /* Tên sản phẩm không bị tràn ra ngoài hoặc thiếu chữ */
    .product-full-title {
      font-size: 13px;
      line-height: 1.42;
      font-weight: 700;
      color: #0B2E59;
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      margin: 0 0 6px 0;
    }

    @media (min-width: 768px) {
      .product-full-title {
        font-size: 14.5px;
        line-height: 1.45;
      }
    }

    /* Tiêu đề Section kiểu Flatsome Title Center */
    .section-title-container {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 10px;
    }

    .section-title-line {
      flex: 1;
      max-width: 90px;
      height: 2px;
      background-color: #CBD5E1;
    }

    /* Nút liên hệ nổi bật cố định góc trái/phải */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
    }

    .floating-btn-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- ========================================================================
       TOP BAR (ĐỊA CHỈ, EMAIL, SĐT - GỌN GÀNG, KHÔNG TRÀN VIỀN)
       ======================================================================== -->
  <div class="bg-pgBlue text-white text-xs py-2 border-b border-pgBlueLight">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-pgGoldLight"></i>
          <span>25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-globe text-pgGoldLight"></i>
          <span>xaydungphamgia.com</span>
        </span>
      </div>
      <div class="flex items-center gap-4">
        <a href="tel:0905736536" class="inline-flex items-center gap-1.5 font-semibold text-pgGoldLight hover:underline">
          <i class="fa-solid fa-phone"></i>
          <span>0905.736.536</span>
        </a>
        <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1 hover:text-pgGoldLight transition">
          <i class="fa-brands fa-facebook"></i>
          <span class="hidden md:inline">Facebook Phạm Gia</span>
        </a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       HEADER CHÍNH (LOGO CHỈNH GỌN NHỎ LẠI, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN,
       DANH MỤC MÁY TÍNH VIẾT LIỀN TRÊN 1 HÀNG CHỮ NHỎ GỌN)
       ======================================================================== -->
  <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200">
    <div class="flatsome-container py-2">
      <div class="flex items-center justify-between gap-3">
        
        <!-- LOGO CÔNG TY CHUYÊN NGHIỆP (GỌN NHỎ LẠI, CÂN ĐỐI) -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" title="CÔNG TY TNHH XD&TM PHẠM GIA - xaydungphamgia.com">
          <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-pgBlue flex items-center justify-center shadow-sm border border-pgGold/40 shrink-0">
            <!-- SVG Logo Kiến Trúc & Xây Dựng Phạm Gia -->
            <svg class="w-7 h-7 sm:w-8 sm:h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <!-- Mái vòm & Khối nhà cao tầng -->
              <path d="M8 54H56" stroke="#F59E0B" stroke-width="3.5" stroke-linecap="round"/>
              <path d="M14 54V26L28 14V54" fill="#164B8A" stroke="#FFFFFF" stroke-width="2.2" stroke-linejoin="round"/>
              <path d="M28 54V20L46 10V54" fill="#D97706" stroke="#FFFFFF" stroke-width="2.2" stroke-linejoin="round"/>
              <!-- Cửa sổ kiến trúc -->
              <rect x="33" y="22" width="4" height="5" fill="#FFFFFF"/>
              <rect x="39" y="22" width="4" height="5" fill="#FFFFFF"/>
              <rect x="33" y="31" width="4" height="5" fill="#FFFFFF"/>
              <rect x="39" y="31" width="4" height="5" fill="#FFFFFF"/>
              <rect x="19" y="30" width="4" height="5" fill="#F59E0B"/>
              <rect x="19" y="39" width="4" height="5" fill="#F59E0B"/>
              <!-- Mái nhà chữ A phía trước -->
              <path d="M6 34L22 21L38 34" stroke="#F59E0B" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <div class="leading-tight">
            <div class="font-heading font-extrabold text-sm sm:text-base text-pgBlue tracking-tight">
              PHẠM GIA <span class="text-pgGold">XD&amp;TM</span>
            </div>
            <div class="text-[10px] sm:text-[11px] font-medium text-slate-500">
              xaydungphamgia.com
            </div>
          </div>
        </a>

        <!-- MENU DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG, KHÔNG ĐƯỢC XUỐNG DÒNG TÊN DANH MỤC) -->
        <nav class="hidden lg:block flex-1" aria-label="Danh mục chính">
          <ul class="desktop-nav-list">
            <li class="desktop-nav-item">
              <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                <span>Công trình thực tế</span>
                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
              </a>
              <div class="flatsome-dropdown">
                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'all')">Tất cả công trình thực tế</a>
                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'Thi công phần thô')">Thi công phần thô</a>
                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'Thi công hoàn thiện')">Thi công hoàn thiện</a>
                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'Thiết kế Kiến trúc – Nội thất')">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#cong-trinh-thuc-te" onclick="filterSection('thi-cong', 'Thi công nội thất')">Thi công nội thất</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#du-an-da-nang" class="desktop-nav-link">
                <span>Dự án Đà Nẵng</span>
                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
              </a>
              <div class="flatsome-dropdown">
                <a href="#du-an-da-nang" onclick="filterSection('du-an', 'all')">Tất cả dự án tại Đà Nẵng</a>
                <a href="#du-an-da-nang" onclick="filterSection('du-an', 'Khách sạn – Căn hộ – Phòng trọ')">Khách sạn – Căn hộ – Phòng trọ</a>
                <a href="#du-an-da-nang" onclick="filterSection('du-an', 'Biệt thự')">Biệt thự</a>
                <a href="#du-an-da-nang" onclick="filterSection('du-an', 'Nhà phố')">Nhà phố</a>
                <a href="#du-an-da-nang" onclick="filterSection('du-an', 'Văn phòng')">Văn phòng</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#linh-vuc-hoat-dong" class="desktop-nav-link">
                <span>Lĩnh vực hoạt động</span>
                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
              </a>
              <div class="flatsome-dropdown">
                <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#mau-thiet-ke" class="desktop-nav-link">
                <span>Mẫu thiết kế</span>
                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
              </a>
              <div class="flatsome-dropdown">
                <a href="#mau-thiet-ke" onclick="filterSection('mau-tk', 'Mẫu thiết kế nhà phố')">Mẫu thiết kế nhà phố</a>
                <a href="#mau-thiet-ke" onclick="filterSection('mau-tk', 'Mẫu thiết kế nội thất')">Mẫu thiết kế nội thất</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#bao-gia" class="desktop-nav-link">
                <span>Báo giá</span>
                <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
              </a>
              <div class="flatsome-dropdown">
                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                <a href="#bao-gia">Báo giá thi công phần thô</a>
                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                <a href="#bao-gia">Báo giá thi công trọn gói</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#doi-tac" class="desktop-nav-link">Đối tác</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
            </li>
          </ul>
        </nav>

        <!-- NÚT MỞ MENU TRÊN ĐIỆN THOẠI (KHÔNG ĐỂ NÚT GỌI NGAY TRÊN HEADER ĐỂ TRÁNH TRÀN VIỀN) -->
        <button id="mobile-menu-toggle" type="button" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 text-pgBlue hover:bg-slate-200 font-semibold text-xs shrink-0" aria-label="Mở danh mục">
          <i class="fa-solid fa-bars text-base"></i>
          <span>DANH MỤC</span>
        </button>

      </div>

      <!-- THANH DANH MỤC NHANH TRÊN ĐIỆN THOẠI (GỌN ĐẸP, KHÔNG TRÀN VIỀN) -->
      <div class="lg:hidden mt-2 pt-2 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
        <a href="#cong-trinh-thuc-te" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Dự án Đà Nẵng</a>
        <a href="#linh-vuc-hoat-dong" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Lĩnh vực hoạt động</a>
        <a href="#mau-thiet-ke" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Mẫu thiết kế</a>
        <a href="#bao-gia" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Báo giá</a>
        <a href="#doi-tac" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Đối tác</a>
        <a href="#tin-tuc" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Tin tức</a>
        <a href="#lien-he" class="shrink-0 text-[11px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-pgBlue">Liên hệ</a>
      </div>
    </div>

    <!-- DRAWER MENU ĐIỆN THOẠI -->
    <div id="mobile-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="flatsome-container py-3 grid grid-cols-2 sm:grid-cols-3 gap-2 text-xs font-semibold text-pgBlue">
        <a href="#trang-chu" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Giới thiệu</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Dự án Đà Nẵng</a>
        <a href="#linh-vuc-hoat-dong" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Lĩnh vực hoạt động</a>
        <a href="#mau-thiet-ke" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Mẫu thiết kế</a>
        <a href="#bao-gia" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Báo giá xây dựng</a>
        <a href="#form-bao-gia" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Yêu cầu tư vấn</a>
        <a href="#doi-tac" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Đối tác</a>
        <a href="#tin-tuc" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Tin tức</a>
        <a href="#lien-he" class="mobile-nav-close p-2 rounded bg-slate-50 hover:bg-amber-50">Bản đồ &amp; Liên hệ</a>
        <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="p-2 rounded bg-blue-50 text-blue-700">Facebook Phạm Gia</a>
      </div>
    </div>
  </header>

  <!-- ========================================================================
       2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       (HÌNH ẢNH VÀ CHỮ NẰM TRONG HẾT BANNER, CHỮ CÁCH XA VIỀN ẢNH BANNER)
       ======================================================================== -->
  <section id="trang-chu" class="py-3 sm:py-4">
    <div class="flatsome-container">
      <div class="hero-slider-wrapper shadow-md" id="pg-hero-slider">
        
        <!-- BANNER SLIDE 1 -->
        <div class="hero-slide active" data-slide="0">
          <img 
            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600" 
            onerror="handleDriveImageError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1600&q=80')"
            alt="Banner 1 - Công ty TNHH XD&TM Phạm Gia Đà Nẵng" 
            class="absolute inset-0 w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-pgBlueDark/95 via-pgBlue/85 to-pgBlueDark/60"></div>

          <!-- Vùng an toàn cách xa viền ảnh banner -->
          <div class="hero-safe-box relative z-10">
            <div class="w-full grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
              <div class="lg:col-span-8 text-white space-y-2.5 sm:space-y-3.5">
                <div class="inline-block bg-pgGold text-white text-[11px] sm:text-xs font-bold uppercase tracking-wider px-3 py-1 rounded">
                  CÔNG TY TNHH XD&amp;TM PHẠM GIA • XAYDUNGPHAMGIA.COM
                </div>
                <h1 class="font-heading font-extrabold text-lg sm:text-2xl lg:text-4xl leading-snug text-white">
                  THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI UY TÍN TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 max-w-2xl leading-relaxed">
                  Chuyên Thiết kế Kiến trúc – Nội thất, Thi công phần thô, Thi công hoàn thiện Nhà phố, Biệt thự, Căn hộ, Khách sạn &amp; Văn phòng. Cam kết An toàn – Chất lượng – Đúng tiến độ.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-xs sm:text-sm">
                  <a href="#form-bao-gia" class="bg-pgGold hover:bg-amber-500 text-white font-bold px-4 py-2.5 rounded-lg transition shadow">
                    ĐĂNG KÝ BÁO GIÁ MIỄN PHÍ
                  </a>
                  <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold px-4 py-2.5 rounded-lg transition">
                    XEM DỰ ÁN TẠI ĐÀ NẴNG
                  </a>
                </div>
              </div>
              <!-- Khung ảnh thực tế nằm gọn trong phải banner trên máy tính -->
              <div class="hidden lg:block lg:col-span-4">
                <div class="bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-lg">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800" 
                    onerror="handleDriveImageError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff', 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80')"
                    alt="Công trình tiêu biểu Phạm Gia" 
                    class="w-full h-48 object-cover rounded-lg"
                  />
                  <div class="pt-2 text-center text-white text-xs font-semibold">
                    25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng • 0905.736.536
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER SLIDE 2 (KÍCH THƯỚC BẰNG NHAU TUYỆT ĐỐI) -->
        <div class="hero-slide" data-slide="1">
          <img 
            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600" 
            onerror="handleDriveImageError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=1600&q=80')"
            alt="Banner 2 - Thi công phần thô và hoàn thiện Phạm Gia" 
            class="absolute inset-0 w-full h-full object-cover"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-pgBlueDark/95 via-pgBlue/85 to-pgBlueDark/60"></div>

          <!-- Vùng an toàn cách xa viền ảnh banner -->
          <div class="hero-safe-box relative z-10">
            <div class="w-full grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
              <div class="lg:col-span-8 text-white space-y-2.5 sm:space-y-3.5">
                <div class="inline-block bg-pgGold text-white text-[11px] sm:text-xs font-bold uppercase tracking-wider px-3 py-1 rounded">
                  CHẤT LƯỢNG TẠO NIỀM TIN • BẢO HÀNH DÀI HẠN
                </div>
                <h2 class="font-heading font-extrabold text-lg sm:text-2xl lg:text-4xl leading-snug text-white">
                  CHUẨN MỰC KỸ THUẬT TỪ PHẦN THÔ ĐẾN HOÀN THIỆN NỘI THẤT
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 max-w-2xl leading-relaxed">
                  Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm trực tiếp giám sát tại công trường. Vật tư chính hãng, minh bạch chi phí, không phát sinh.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-xs sm:text-sm">
                  <a href="#cong-trinh-thuc-te" class="bg-pgGold hover:bg-amber-500 text-white font-bold px-4 py-2.5 rounded-lg transition shadow">
                    HÌNH ẢNH THI CÔNG THỰC TẾ
                  </a>
                  <a href="#bao-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold px-4 py-2.5 rounded-lg transition">
                    XEM BẢNG BÁO GIÁ 2026
                  </a>
                </div>
              </div>
              <!-- Khung ảnh thực tế nằm gọn trong phải banner trên máy tính -->
              <div class="hidden lg:block lg:col-span-4">
                <div class="bg-white/10 backdrop-blur-sm p-2.5 rounded-xl border border-white/25 shadow-lg">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800" 
                    onerror="handleDriveImageError(this, '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_', 'https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80')"
                    alt="Thi công thực tế Phạm Gia" 
                    class="w-full h-48 object-cover rounded-lg"
                  />
                  <div class="pt-2 text-center text-white text-xs font-semibold">
                    Giám Sát Kỹ Thuật 24/7 • Cam Kết Đúng Vật Tư Hợp Đồng
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng trái/phải nằm gọn trong banner -->
        <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-pgGold text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp theo" class="absolute right-2.5 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-pgGold text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" id="slider-dot-0" class="w-6 h-2 rounded-full bg-pgGold transition-all" aria-label="Banner 1"></button>
          <button type="button" onclick="goToSlide(1)" id="slider-dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG (GIỐNG WEB MẪU TINTRUONGTHINH.COM)
       ======================================================================== -->
  <section id="linh-vuc-hoat-dong" class="py-6 sm:py-8 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-5">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            LĨNH VỰC HOẠT ĐỘNG CHÍNH
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Giải pháp khép kín từ Tư vấn Thiết kế Kiến trúc đến Thi công phần thô, Hoàn thiện và Nội thất trọn gói
        </p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        
        <div class="flatsome-col-box p-4 sm:p-5 text-center border-t-4 border-t-pgBlue">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-pgBlue/10 text-pgBlue flex items-center justify-center text-xl">
            <i class="fa-solid fa-compass-drafting"></i>
          </div>
          <h3 class="product-full-title text-center">Thiết kế Kiến trúc – Nội thất</h3>
          <p class="text-xs text-slate-600 leading-relaxed">
            Thiết kế hồ sơ bản vẽ kiến trúc, phối cảnh 3D mặt tiền, kết cấu M&amp;E và nội thất tối ưu công năng, chuẩn phong thủy.
          </p>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 text-center border-t-4 border-t-pgGold">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-pgGold/10 text-pgGold flex items-center justify-center text-xl">
            <i class="fa-solid fa-trowel-bricks"></i>
          </div>
          <h3 class="product-full-title text-center">Thi công phần thô</h3>
          <p class="text-xs text-slate-600 leading-relaxed">
            Thi công móng, cốp pha, cốt thép, đổ bê tông thương phẩm, xây tô tường bao đúng quy chuẩn kỹ thuật xây dựng.
          </p>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 text-center border-t-4 border-t-pgBlue">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-pgBlue/10 text-pgBlue flex items-center justify-center text-xl">
            <i class="fa-solid fa-paint-roller"></i>
          </div>
          <h3 class="product-full-title text-center">Thi công hoàn thiện</h3>
          <p class="text-xs text-slate-600 leading-relaxed">
            Ốp lát gạch, đóng trần thạch cao, sơn bả hoàn thiện, lắp đặt cửa nhôm kính, lan can, thiết bị điện nước đồng bộ.
          </p>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 text-center border-t-4 border-t-pgGold">
          <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-pgGold/10 text-pgGold flex items-center justify-center text-xl">
            <i class="fa-solid fa-couch"></i>
          </div>
          <h3 class="product-full-title text-center">Thi công nội thất</h3>
          <p class="text-xs text-slate-600 leading-relaxed">
            Sản xuất và lắp đặt nội thất phòng khách, bếp, phòng ngủ cho Nhà phố, Biệt thự, Căn hộ và Văn phòng.
          </p>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH CỦA CHÚNG TÔI (GIỐNG WEB MẪU)
       ======================================================================== -->
  <section id="gioi-thieu" class="py-7 sm:py-10 bg-slate-50 border-b border-slate-200">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center mb-8">
        <div class="lg:col-span-7 space-y-3">
          <div class="text-xs font-bold uppercase tracking-wider text-pgGold">
            VỀ CHÚNG TÔI • XAYDUNGPHAMGIA.COM
          </div>
          <h2 class="font-heading font-extrabold text-lg sm:text-2xl text-pgBlue">
            CÔNG TY TNHH XD&amp;TM PHẠM GIA
          </h2>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
            <strong>CÔNG TY TNHH XD&amp;TM PHẠM GIA</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại thành phố Đà Nẵng và khu vực miền Trung.
          </p>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
            Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình đều đạt trọn vẹn 4 giá trị cốt lõi: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
          </p>
          <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-2">
            <div class="bg-white p-3 rounded-lg border border-slate-200">
              <div class="font-heading font-extrabold text-lg text-pgBlue">0401953955</div>
              <div class="text-[11px] text-slate-500">Mã số doanh nghiệp</div>
            </div>
            <div class="bg-white p-3 rounded-lg border border-slate-200">
              <div class="font-heading font-extrabold text-lg text-pgGold">100%</div>
              <div class="text-[11px] text-slate-500">Vật tư đúng hợp đồng</div>
            </div>
            <div class="bg-white p-3 rounded-lg border border-slate-200 col-span-2 sm:col-span-1">
              <div class="font-heading font-extrabold text-lg text-pgBlue">5 - 10 Năm</div>
              <div class="text-[11px] text-slate-500">Bảo hành kết cấu bền vững</div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-5">
          <div class="bg-white p-3 rounded-xl border border-slate-200 shadow-sm">
            <img 
              src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w1000" 
              onerror="handleDriveImageError(this, '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_', 'https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1000&q=80')"
              alt="Công trình thực tế Công ty TNHH XD&TM Phạm Gia" 
              class="w-full h-56 sm:h-64 object-cover rounded-lg"
            />
            <div class="mt-2.5 flex items-center justify-between text-xs text-slate-600 px-1">
              <span><i class="fa-solid fa-building-shield text-pgGold mr-1"></i> Trụ sở: 25 Lỗ Giáng 19, P. Hòa Xuân, Đà Nẵng</span>
              <span class="font-bold text-pgBlue">0905.736.536</span>
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của chúng tôi -->
      <div class="text-center mb-4">
        <h3 class="font-heading font-bold text-sm sm:text-base text-pgBlue uppercase">
          THẾ MẠNH CỦA XÂY DỰNG PHẠM GIA
        </h3>
      </div>
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4">
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-user-helmet-safety text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Đội ngũ KTS, kỹ sư chuyên nghiệp</h4>
            <p class="text-xs text-slate-600">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư hiện trường và thợ lành nghề lâu năm tại Đà Nẵng.</p>
          </div>
        </div>
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-layer-group text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Cập nhật xu hướng mới hiện đại</h4>
            <p class="text-xs text-slate-600">Ứng dụng giải pháp không gian xanh, thông tầng lấy sáng tự nhiên và vật liệu bền đẹp.</p>
          </div>
        </div>
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-clipboard-check text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Giám sát tiến độ chuẩn xác</h4>
            <p class="text-xs text-slate-600">Báo cáo hình ảnh nhật ký công trình thường xuyên để Chủ đầu tư dễ dàng theo dõi từ xa.</p>
          </div>
        </div>
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-shield-halved text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Bảo hành công trình lâu dài</h4>
            <p class="text-xs text-slate-600">Chế độ hậu mãi tận tâm, bảo hành kết cấu dài hạn và hỗ trợ kiểm tra định kỳ nhanh chóng.</p>
          </div>
        </div>
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-hand-holding-dollar text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Giá cả hợp lý phải chăng</h4>
            <p class="text-xs text-slate-600">Dự toán bóc tách minh bạch từng hạng mục, cân đối ngân sách tối ưu nhất cho gia chủ.</p>
          </div>
        </div>
        <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 flex items-start gap-3">
          <i class="fa-solid fa-headset text-pgGold text-lg mt-0.5 shrink-0"></i>
          <div>
            <h4 class="product-full-title">Hỗ trợ tư vấn miễn phí 24/7</h4>
            <p class="text-xs text-slate-600">Khảo sát thực tế tận nơi tại Đà Nẵng, tư vấn phương án thiết kế và xin phép xây dựng.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       DANH MỤC 1: HÌNH ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (9 FILE GOOGLE DRIVE)
       - Chia 2 cột trên điện thoại
       - Không để các nhãn dán ở trang chủ
       - Tên sản phẩm đầy đủ không bị tràn hoặc thiếu chữ
       ======================================================================== -->
  <section id="cong-trinh-thuc-te" class="py-7 sm:py-10 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-4">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            CÔNG TRÌNH &amp; HÌNH ẢNH THI CÔNG THỰC TẾ
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Hình ảnh thực tế thi công phần thô, kết cấu, hoàn thiện và nội thất của Công ty TNHH XD&amp;TM Phạm Gia
        </p>
      </div>

      <!-- Thanh lọc danh mục nhỏ gọn, viết liền trên 1 hàng -->
      <div class="cat-filter-bar mb-5" id="thi-cong-filters">
        <button type="button" class="cat-pill-btn active" onclick="filterSection('thi-cong', 'all', this)">Tất cả (9)</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('thi-cong', 'Thi công phần thô', this)">Thi công phần thô</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('thi-cong', 'Thi công hoàn thiện', this)">Thi công hoàn thiện</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('thi-cong', 'Thiết kế Kiến trúc – Nội thất', this)">Thiết kế Kiến trúc – Nội thất</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('thi-cong', 'Thi công nội thất', this)">Thi công nội thất</button>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
      <div id="thi-cong-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Được render tự động bằng JavaScript từ 9 file Google Drive -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       DANH MỤC 2: CÁC DỰ ÁN Ở ĐÀ NẴNG (10 FILE GOOGLE DRIVE)
       - Chia 2 cột trên điện thoại, 5 cột trên máy tính
       - Không để các nhãn dán ở trang chủ
       - Tên sản phẩm hiển thị đầy đủ không tràn viền
       ======================================================================== -->
  <section id="du-an-da-nang" class="py-7 sm:py-10 bg-slate-50 border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-4">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Các dự án Nhà phố, Biệt thự, Khách sạn – Căn hộ và Văn phòng do Phạm Gia thiết kế &amp; thi công tại TP Đà Nẵng
        </p>
      </div>

      <!-- Thanh lọc danh mục dự án Đà Nẵng (giống web mẫu tintruongthinh.com) -->
      <div class="cat-filter-bar mb-5" id="du-an-filters">
        <button type="button" class="cat-pill-btn active" onclick="filterSection('du-an', 'all', this)">Tất cả dự án Đà Nẵng (10)</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('du-an', 'Khách sạn – Căn hộ – Phòng trọ', this)">Khách sạn – Căn hộ – Phòng trọ</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('du-an', 'Biệt thự', this)">Biệt thự</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('du-an', 'Nhà phố', this)">Nhà phố</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('du-an', 'Văn phòng', this)">Văn phòng</button>
      </div>

      <!-- Lưới dự án Đà Nẵng: 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính -->
      <div id="du-an-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
        <!-- Được render tự động bằng JavaScript từ 10 file Google Drive -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       MẪU THIẾT KẾ NHÀ PHỐ & NỘI THẤT (THEO DANH MỤC WEB MẪU)
       ======================================================================== -->
  <section id="mau-thiet-ke" class="py-7 sm:py-10 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-4">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            MẪU THIẾT KẾ NHÀ PHỐ &amp; NỘI THẤT ĐẸP
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Bộ sưu tập mẫu thiết kế kiến trúc nhà phố và mẫu thiết kế nội thất hiện đại được ưa chuộng tại Đà Nẵng
        </p>
      </div>

      <div class="cat-filter-bar mb-5" id="mau-tk-filters">
        <button type="button" class="cat-pill-btn active" onclick="filterSection('mau-tk', 'all', this)">Tất cả mẫu thiết kế</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('mau-tk', 'Mẫu thiết kế nhà phố', this)">Mẫu thiết kế nhà phố</button>
        <button type="button" class="cat-pill-btn" onclick="filterSection('mau-tk', 'Mẫu thiết kế nội thất', this)">Mẫu thiết kế nội thất</button>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="mau-tk-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render bằng JS -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       BẢNG BÁO GIÁ XÂY DỰNG (THEO 4 DANH MỤC BÁO GIÁ CỦA WEB MẪU)
       ======================================================================== -->
  <section id="bao-gia" class="py-7 sm:py-10 bg-slate-50 border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-5">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            BẢNG BÁO GIÁ THIẾT KẾ &amp; THI CÔNG XÂY DỰNG
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Đơn giá tham khảo minh bạch tại khu vực Đà Nẵng – Miễn phí 100% thiết kế khi ký hợp đồng thi công trọn gói
        </p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        
        <div class="flatsome-col-box p-4 sm:p-5 justify-between">
          <div>
            <h3 class="product-full-title">Báo giá thiết kế kiến trúc</h3>
            <div class="text-pgGold font-heading font-extrabold text-base sm:text-xl my-2">
              120.000đ – 180.000đ/m²
            </div>
            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li>• Bản vẽ kiến trúc &amp; phối cảnh 3D</li>
              <li>• Hồ sơ kết cấu &amp; điện nước M&amp;E</li>
              <li>• Hỗ trợ hồ sơ cấp phép xây dựng</li>
              <li>• Miễn phí khi thi công trọn gói</li>
            </ul>
          </div>
          <a href="#form-bao-gia" onclick="selectQuoteService('Báo giá thiết kế kiến trúc')" class="mt-4 block text-center text-xs font-bold py-2 px-3 rounded bg-pgBlue text-white hover:bg-pgGold transition">
            Nhận báo giá chi tiết
          </a>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 justify-between">
          <div>
            <h3 class="product-full-title">Báo giá thi công phần thô</h3>
            <div class="text-pgGold font-heading font-extrabold text-base sm:text-xl my-2">
              3.500.000đ – 3.900.000đ/m²
            </div>
            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li>• Vật tư phần thô chuẩn chính hãng</li>
              <li>• Nhân công phần thô &amp; hoàn thiện</li>
              <li>• Thi công hệ thống điện nước âm</li>
              <li>• Bảo hành kết cấu lên đến 10 năm</li>
            </ul>
          </div>
          <a href="#form-bao-gia" onclick="selectQuoteService('Thi công phần thô')" class="mt-4 block text-center text-xs font-bold py-2 px-3 rounded bg-pgBlue text-white hover:bg-pgGold transition">
            Nhận báo giá chi tiết
          </a>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 justify-between">
          <div>
            <h3 class="product-full-title">Báo giá thi công hoàn thiện</h3>
            <div class="text-pgGold font-heading font-extrabold text-base sm:text-xl my-2">
              2.200.000đ – 3.200.000đ/m²
            </div>
            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li>• Ốp lát gạch nền, gạch tường, đá</li>
              <li>• Trần thạch cao, sơn bả trong ngoài</li>
              <li>• Cửa nhôm Xingfa, cầu thang, lan can</li>
              <li>• Lắp đặt thiết bị vệ sinh &amp; chiếu sáng</li>
            </ul>
          </div>
          <a href="#form-bao-gia" onclick="selectQuoteService('Thi công hoàn thiện')" class="mt-4 block text-center text-xs font-bold py-2 px-3 rounded bg-pgBlue text-white hover:bg-pgGold transition">
            Nhận báo giá chi tiết
          </a>
        </div>

        <div class="flatsome-col-box p-4 sm:p-5 justify-between border-pgGold">
          <div>
            <h3 class="product-full-title">Báo giá thi công trọn gói</h3>
            <div class="text-pgGold font-heading font-extrabold text-base sm:text-xl my-2">
              5.600.000đ – 7.200.000đ/m²
            </div>
            <ul class="text-xs text-slate-600 space-y-1.5 mt-3">
              <li>• Chìa khóa trao tay từ A đến Z</li>
              <li>• Tặng 100% chi phí xin phép &amp; thiết kế</li>
              <li>• Cam kết không phát sinh chi phí</li>
              <li>• Giám sát kỹ sư chuyên trách 24/7</li>
            </ul>
          </div>
          <a href="#form-bao-gia" onclick="selectQuoteService('Xây nhà trọn gói')" class="mt-4 block text-center text-xs font-bold py-2 px-3 rounded bg-pgGold text-white hover:bg-pgBlue transition">
            Nhận báo giá trọn gói
          </a>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (GIỐNG WEB MẪU TINTRUONGTHINH.COM)
       ======================================================================== -->
  <section id="form-bao-gia" class="py-8 sm:py-10 bg-pgBlue text-white">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
        
        <div class="lg:col-span-5 space-y-3">
          <div class="text-xs font-bold uppercase tracking-wider text-pgGoldLight">
            ĐĂNG KÝ TƯ VẤN &amp; DỰ TOÁN CHI PHÍ XÂY DỰNG
          </div>
          <h2 class="font-heading font-extrabold text-lg sm:text-2xl leading-snug">
            MIỄN PHÍ TƯ VẤN &amp; BÁO GIÁ KHẢO SÁT TẬN NƠI TẠI ĐÀ NẴNG
          </h2>
          <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
            Quý khách hàng vui lòng để lại thông tin nhu cầu xây dựng. Kỹ sư trưởng của <strong>CÔNG TY TNHH XD&amp;TM PHẠM GIA</strong> sẽ liên hệ tư vấn trực tiếp và gửi bảng khái toán chi tiết trong vòng 15 phút.
          </p>
          <div class="pt-2 space-y-2 text-xs sm:text-sm text-slate-100">
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone-volume text-pgGoldLight w-5"></i>
              <span>Hotline / Zalo trực tiếp: <strong>0905.736.536</strong></span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-location-dot text-pgGoldLight w-5"></i>
              <span>Địa chỉ: <strong>25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng</strong></span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-pgGoldLight w-5"></i>
              <span>Facebook: <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="underline hover:text-pgGoldLight">facebook.com/phamtruy85</a></span>
            </div>
          </div>
        </div>

        <div class="lg:col-span-7">
          <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-xl shadow-lg">
            <h3 class="font-heading font-bold text-sm sm:text-base text-pgBlue uppercase mb-3 border-b border-slate-200 pb-2">
              FORM YÊU CẦU TƯ VẤN &amp; BÁO GIÁ XÂY DỰNG
            </h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input type="text" id="q-name" required placeholder="Nhập họ tên của Quý khách" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue" />
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="q-phone" required placeholder="Ví dụ: 0905736536" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue" />
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                <select id="q-type" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue bg-white">
                  <option value="Nhà phố">Nhà phố hiện đại / tân cổ điển</option>
                  <option value="Biệt thự">Biệt thự phố / Biệt thự sân vườn</option>
                  <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                  <option value="Văn phòng">Tòa nhà Văn phòng / Showroom</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa &amp; Hoàn thiện nội thất</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select id="q-budget" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue bg-white">
                  <option value="Từ 1 - 2 tỷ">Từ 1 - 2 tỷ</option>
                  <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  <option value=" từ 500 triệu - 1 tỷ">Từ 500 triệu - 1 tỷ</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                <select id="q-service" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue bg-white">
                  <option value="Xây nhà trọn gói">Xây nhà trọn gói (Chìa khóa trao tay)</option>
                  <option value="Thi công phần thô">Thi công phần thô &amp; nhân công hoàn thiện</option>
                  <option value="Thi công hoàn thiện">Thi công hoàn thiện &amp; nội thất</option>
                  <option value="Báo giá thiết kế kiến trúc">Thiết kế Kiến trúc – Nội thất</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất / Khu vực tại Đà Nẵng</label>
                <input type="text" id="q-area" placeholder="VD: 5x20m tại Hòa Xuân, Đà Nẵng" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue" />
              </div>
              <div class="sm:col-span-2">
                <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (Số tầng, công năng mong muốn)</label>
                <textarea id="q-note" rows="2" placeholder="Nhập thêm yêu cầu về số tầng, số phòng ngủ hoặc thời gian dự kiến khởi công..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-pgBlue"></textarea>
              </div>
            </div>
            <div class="mt-3 flex flex-wrap items-center justify-between gap-2">
              <span class="text-[11px] text-slate-500">
                <i class="fa-solid fa-lock text-pgGold mr-1"></i> Bảo mật thông tin khách hàng 100%
              </span>
              <button type="submit" class="bg-pgGold hover:bg-amber-600 text-white font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition shadow">
                GỬI YÊU CẦU BÁO GIÁ NGAY
              </button>
            </div>
            <div id="quote-feedback" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
          </form>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
       - Chia 2 cột trên điện thoại, 4 cột trên máy tính
       - Không để các nhãn dán
       ======================================================================== -->
  <section id="tin-tuc" class="py-7 sm:py-10 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-5">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            TIN TỨC &amp; KINH NGHIỆM XÂY DỰNG
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Cập nhật kiến thức kỹ thuật thi công, phong thủy nhà ở và cẩm nang xây nhà trọn gói tại Đà Nẵng
        </p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        
        <article class="flatsome-col-box cursor-pointer" onclick="openArticleModal(0)">
          <div class="flatsome-box-image">
            <img 
              src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w800" 
              onerror="handleDriveImageError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=800&q=80')"
              alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách"
            />
          </div>
          <div class="flatsome-box-text">
            <div>
              <h3 class="product-full-title">Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật xây dựng</h3>
              <p class="text-xs text-slate-600">
                Trong quá trình thi công phần thô, công tác giữ ẩm và bảo dưỡng bê tông móng đóng vai trò quyết định đến cường độ chịu lực...
              </p>
            </div>
            <span class="mt-2 inline-block text-xs font-semibold text-pgGold">Xem chi tiết →</span>
          </div>
        </article>

        <article class="flatsome-col-box cursor-pointer" onclick="openArticleModal(1)">
          <div class="flatsome-box-image">
            <img 
              src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w800" 
              onerror="handleDriveImageError(this, '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT', 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80')"
              alt="Tâm lý học không gian nội thất"
            />
          </div>
          <div class="flatsome-box-text">
            <div>
              <h3 class="product-full-title">Tâm lý học không gian: Thiết kế nội thất tác động đến gia đình như thế nào?</h3>
              <p class="text-xs text-slate-600">
                Bố cục ánh sáng tự nhiên, thông gió và màu sắc vật liệu nội thất mang lại sự thư thái và gắn kết các thành viên...
              </p>
            </div>
            <span class="mt-2 inline-block text-xs font-semibold text-pgGold">Xem chi tiết →</span>
          </div>
        </article>

        <article class="flatsome-col-box cursor-pointer" onclick="openArticleModal(2)">
          <div class="flatsome-box-image">
            <img 
              src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn=w800" 
              onerror="handleDriveImageError(this, '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80')"
              alt="03 Nỗi lo lớn nhất khi xây nhà"
            />
          </div>
          <div class="flatsome-box-text">
            <div>
              <h3 class="product-full-title">03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần biết để phòng tránh</h3>
              <p class="text-xs text-slate-600">
                Giải pháp kiểm soát dự toán không phát sinh chi phí, lựa chọn vật tư đúng chủng loại và đảm bảo tiến độ bàn giao...
              </p>
            </div>
            <span class="mt-2 inline-block text-xs font-semibold text-pgGold">Xem chi tiết →</span>
          </div>
        </article>

        <article class="flatsome-col-box cursor-pointer" onclick="openArticleModal(3)">
          <div class="flatsome-box-image">
            <img 
              src="https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k=w800" 
              onerror="handleDriveImageError(this, '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k', 'https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=800&q=80')"
              alt="Thủ tục xin giấy phép xây dựng tại Đà Nẵng"
            />
          </div>
          <div class="flatsome-box-text">
            <div>
              <h3 class="product-full-title">Kinh nghiệm xin giấy phép xây dựng và thiết kế nhà phố tại Đà Nẵng</h3>
              <p class="text-xs text-slate-600">
                Hướng dẫn đầy đủ hồ sơ pháp lý, mật độ xây dựng, khoảng lùi và chiều cao tầng theo quy hoạch tại Đà Nẵng...
              </p>
            </div>
            <span class="mt-2 inline-block text-xs font-semibold text-pgGold">Xem chi tiết →</span>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ & THIẾT BỊ CHÍNH HÃNG
       ======================================================================== -->
  <section id="doi-tac" class="py-7 sm:py-9 bg-slate-50 border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-5">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            ĐỐI TÁC VẬT TƯ &amp; THƯƠNG HIỆU ĐỒNG HÀNH
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          CÔNG TY TNHH XD&amp;TM PHẠM GIA cam kết sử dụng 100% vật tư chính hãng từ các nhà sản xuất uy tín hàng đầu
        </p>
      </div>

      <!-- Chia 2 cột trên điện thoại, 6 cột trên máy tính -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">THÉP HÒA PHÁT</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng tiêu chuẩn</div>
        </div>
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">XI MĂNG KIM ĐỈNH</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Bê tông &amp; kết cấu bền vững</div>
        </div>
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">SƠN DULUX &amp; JOTUN</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Sơn chống thấm cao cấp</div>
        </div>
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">NHÔM KÍNH XINGFA</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính nhập khẩu</div>
        </div>
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">GỖ AN CƯỜNG</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất hiện đại</div>
        </div>
        <div class="bg-white p-3.5 rounded-lg border border-slate-200 text-center flex flex-col items-center justify-center">
          <div class="font-heading font-extrabold text-sm text-pgBlue">INAX &amp; PANASONIC</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện &amp; vệ sinh</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       ĐƯA FACEBOOK & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
       (25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng - SĐT: 0905.736.536)
       ======================================================================== -->
  <section id="lien-he" class="py-7 sm:py-10 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="text-center mb-5">
        <div class="section-title-container">
          <span class="section-title-line"></span>
          <h2 class="font-heading font-extrabold text-base sm:text-xl text-pgBlue uppercase tracking-wide">
            BẢN ĐỒ GOOGLE MAPS &amp; KẾT NỐI FACEBOOK TRANG CHỦ
          </h2>
          <span class="section-title-line"></span>
        </div>
        <p class="text-xs sm:text-sm text-slate-600">
          Trụ sở: 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng • Hotline/Zalo: 0905.736.536
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        
        <!-- KHỐI FACEBOOK PHẠM GIA NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between border-b border-slate-200 pb-3 mb-3">
              <div class="flex items-center gap-2.5">
                <div class="w-10 h-10 rounded-full bg-blue-600 text-white flex items-center justify-center text-lg">
                  <i class="fa-brands fa-facebook-f"></i>
                </div>
                <div>
                  <h3 class="font-heading font-bold text-sm text-pgBlue">KẾT NỐI FACEBOOK CHÍNH THỨC</h3>
                  <p class="text-xs text-slate-500">Cập nhật tiến độ công trình hàng ngày</p>
                </div>
              </div>
            </div>

            <!-- Card hiển thị trang Facebook https://www.facebook.com/phamtruy85/ -->
            <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
              <div class="h-32 sm:h-36 relative">
                <img 
                  src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800" 
                  onerror="handleDriveImageError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80')"
                  alt="Facebook Xây dựng Phạm Gia" 
                  class="w-full h-full object-cover"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-pgBlueDark/90 via-pgBlueDark/40 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3 text-white">
                  <div class="w-12 h-12 rounded-lg bg-pgBlue border-2 border-white flex items-center justify-center font-heading font-extrabold text-pgGoldLight shrink-0">
                    PG
                  </div>
                  <div class="min-w-0">
                    <div class="font-bold text-sm truncate">Xây Dựng Phạm Gia Đà Nẵng</div>
                    <div class="text-[11px] text-slate-200 truncate">facebook.com/phamtruy85</div>
                  </div>
                </div>
              </div>
              <div class="p-3.5 space-y-2 text-xs text-slate-700">
                <p>
                  <i class="fa-solid fa-circle-check text-blue-600 mr-1"></i>
                  Chuyên tư vấn thiết kế, thi công xây dựng nhà phố, biệt thự, căn hộ trọn gói tại Đà Nẵng.
                </p>
                <p>
                  <i class="fa-solid fa-location-dot text-pgGold mr-1"></i>
                  Địa chỉ: 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng
                </p>
                <p>
                  <i class="fa-solid fa-phone text-pgGold mr-1"></i>
                  Điện thoại / Zalo: <strong>0905.736.536</strong>
                </p>
                <div class="pt-2 flex flex-wrap gap-2">
                  <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-3 rounded-lg transition">
                    <i class="fa-brands fa-facebook mr-1"></i> Truy cập Facebook
                  </a>
                  <a href="https://zalo.me/0905736536" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-sky-500 hover:bg-sky-600 text-white font-bold py-2 px-3 rounded-lg transition">
                    <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn tin Zalo
                  </a>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-slate-200 text-xs text-slate-600 flex items-center justify-between">
            <span>Website: <strong>xaydungphamgia.com</strong></span>
            <span>MST: <strong>0401953955</strong></span>
          </div>
        </div>

        <!-- KHỐI GOOGLE MAP TRỰC TIẾP NGOÀI TRANG CHỦ -->
        <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col">
          <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5 px-1">
            <div>
              <h3 class="font-heading font-bold text-sm text-pgBlue">
                <i class="fa-solid fa-map-location-dot text-pgGold mr-1.5"></i>
                VỊ TRÍ TRÊN GOOGLE MAPS: 25 LỖ GIÁNG 19, PHƯỜNG HÒA XUÂN, TP ĐÀ NẴNG
              </h3>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=25+L%E1%BB%97+Gi%C3%A1ng+19,+H%C3%B2a+Xu%C3%A2n,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-pgBlue hover:text-pgGold underline">
              Mở chỉ đường Google Maps ↗
            </a>
          </div>
          <div class="w-full flex-1 min-h-[300px] sm:min-h-[340px] rounded-lg overflow-hidden border border-slate-300 bg-slate-200">
            <iframe
              title="Bản đồ Công ty TNHH XD&TM Phạm Gia - 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng"
              src="https://maps.google.com/maps?q=25%20L%E1%BB%97%20Gi%C3%A1ng%2019,%20Ph%C6%B0%E1%BB%9Dng%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="100%"
              style="border:0; min-height: 320px;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ========================================================================
       FOOTER CHUẨN FLATSOME
       ======================================================================== -->
  <footer class="bg-pgBlueDark text-slate-200 pt-8 pb-20 sm:pb-8">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
        
        <div class="lg:col-span-5 space-y-2.5">
          <div class="font-heading font-extrabold text-base sm:text-lg text-white">
            CÔNG TY TNHH XD&amp;TM PHẠM GIA
          </div>
          <p class="text-xs text-slate-300 leading-relaxed">
            Đơn vị chuyên Thiết kế Kiến trúc – Nội thất, Thi công phần thô, Thi công hoàn thiện và Xây nhà trọn gói các công trình Nhà phố, Biệt thự, Căn hộ, Khách sạn, Văn phòng uy tín tại Đà Nẵng.
          </p>
          <ul class="text-xs space-y-1.5 text-slate-200 pt-1">
            <li><i class="fa-solid fa-location-dot text-pgGoldLight w-5"></i> <strong>Trụ sở:</strong> 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-pgGoldLight w-5"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0905736536" class="text-pgGoldLight font-bold">0905.736.536</a></li>
            <li><i class="fa-solid fa-globe text-pgGoldLight w-5"></i> <strong>Website:</strong> xaydungphamgia.com</li>
            <li><i class="fa-brands fa-facebook text-pgGoldLight w-5"></i> <strong>Facebook:</strong> <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="underline">facebook.com/phamtruy85</a></li>
            <li><i class="fa-solid fa-file-invoice text-pgGoldLight w-5"></i> <strong>Mã số thuế:</strong> 0401953955</li>
          </ul>
        </div>

        <div class="lg:col-span-3 space-y-2">
          <div class="font-heading font-bold text-sm text-white uppercase">Lĩnh vực hoạt động</div>
          <ul class="text-xs space-y-2 text-slate-300">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-pgGoldLight">• Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-pgGoldLight">• Thi công xây dựng phần thô</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-pgGoldLight">• Thi công hoàn thiện công trình</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-pgGoldLight">• Sản xuất &amp; Thi công nội thất</a></li>
            <li><a href="#bao-gia" class="hover:text-pgGoldLight">• Xây nhà trọn gói chìa khóa trao tay</a></li>
          </ul>
        </div>

        <div class="lg:col-span-4 space-y-2">
          <div class="font-heading font-bold text-sm text-white uppercase">Danh mục công trình</div>
          <div class="grid grid-cols-2 gap-2 text-xs text-slate-300">
            <a href="#du-an-da-nang" class="hover:text-pgGoldLight">• Dự án tại Đà Nẵng</a>
            <a href="#du-an-da-nang" class="hover:text-pgGoldLight">• Khách sạn – Căn hộ</a>
            <a href="#du-an-da-nang" class="hover:text-pgGoldLight">• Biệt thự hiện đại</a>
            <a href="#du-an-da-nang" class="hover:text-pgGoldLight">• Nhà phố Đà Nẵng</a>
            <a href="#du-an-da-nang" class="hover:text-pgGoldLight">• Tòa nhà Văn phòng</a>
            <a href="#mau-thiet-ke" class="hover:text-pgGoldLight">• Mẫu thiết kế đẹp</a>
            <a href="#bao-gia" class="hover:text-pgGoldLight">• Bảng báo giá 2026</a>
            <a href="#tin-tuc" class="hover:text-pgGoldLight">• Kinh nghiệm xây nhà</a>
          </div>
        </div>

      </div>

      <div class="pt-4 text-center text-xs text-slate-400">
        Copyright 2026 © <strong>CÔNG TY TNHH XD&amp;TM PHẠM GIA</strong> (xaydungphamgia.com) • Địa chỉ: 25 Lỗ Giáng 19, Phường Hòa Xuân, TP Đà Nẵng
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       TƯƠNG THÍCH TRÊN MÁY TÍNH VÀ ĐIỆN THOẠI, KHÔNG TRÀN VIỀN
       ======================================================================== -->
  <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo nổi bật -->
    <a href="https://zalo.me/0905736536" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition" title="Chat Zalo: 0905.736.536">
      <span class="w-7 h-7 rounded-full bg-white text-sky-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo</span>
    </a>

    <!-- Nút Facebook nổi bật -->
    <a href="https://www.facebook.com/phamtruy85/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition" title="Facebook Công ty Phạm Gia">
      <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0905736536" class="floating-btn-pulse flex items-center gap-2 bg-pgGold hover:bg-amber-600 text-white px-3.5 py-2 rounded-full shadow-xl transition" title="Gọi ngay 0905.736.536">
      <span class="w-7 h-7 rounded-full bg-white text-pgGold flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1">0905.736.536</span>
    </a>
  </div>

  <!-- ========================================================================
       MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT
       ======================================================================== -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden bg-black/75 p-3 sm:p-6 flex items-center justify-center">
    <div class="bg-white rounded-xl max-w-3xl w-full overflow-hidden shadow-2xl border border-slate-200 max-h-[90vh] flex flex-col">
      <div class="flex items-center justify-between px-4 py-3 bg-pgBlue text-white">
        <h3 id="modal-title" class="font-heading font-bold text-xs sm:text-sm pr-4">Chi tiết công trình</h3>
        <button type="button" onclick="closeModal()" class="w-7 h-7 rounded-full bg-white/15 hover:bg-white/30 flex items-center justify-center text-white shrink-0">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-5 overflow-y-auto space-y-3">
        <div id="modal-img-wrap" class="w-full rounded-lg overflow-hidden bg-slate-100">
          <img id="modal-img" src="" alt="" class="w-full max-h-[420px] object-contain mx-auto" />
        </div>
        <div id="modal-cat" class="text-xs font-bold text-pgGold uppercase"></div>
        <p id="modal-desc" class="text-xs sm:text-sm text-slate-700 leading-relaxed"></p>
        <div class="pt-2 flex flex-wrap items-center justify-between gap-2 border-t border-slate-200">
          <a id="modal-drive-link" href="#" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-pgBlue hover:underline">
            <i class="fa-brands fa-google-drive mr-1"></i> Mở ảnh gốc chất lượng cao trên Google Drive ↗
          </a>
          <a href="#form-bao-gia" onclick="closeModal()" class="bg-pgGold text-white text-xs font-bold px-4 py-2 rounded-lg">
            Đăng ký tư vấn mẫu này
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU 19 ẢNH GOOGLE DRIVE, BỘ LỌC & SLIDER
       ======================================================================== -->
  <script>
    // Hàm tự động chuyển đổi cơ chế tải ảnh Google Drive để luôn hiển thị mượt mà
    function handleDriveImageError(imgEl, fileId, backupUrl) {
      const stage = parseInt(imgEl.getAttribute('data-retry') || '0', 10);
      if (stage === 0) {
        imgEl.setAttribute('data-retry', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
      } else if (stage === 1) {
        imgEl.setAttribute('data-retry', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        imgEl.src = backupUrl;
      }
    }

    // 1. DANH SÁCH 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (ĐÚNG FILE GOOGLE DRIVE & PHÂN LOẠI CHUẨN)
    const realConstructionItems = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công phần thô và kết cấu móng băng nhà phố hiện đại tại Đà Nẵng',
        category: 'Thi công phần thô',
        location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
        desc: 'Hình ảnh thực tế công tác gia công lắp dựng cốt thép móng, cốp pha và đổ bê tông thương phẩm phần thô đảm bảo tiêu chuẩn chịu lực.',
        backup: 'https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Lắp dựng cốp pha, cốt thép dầm sàn và nghiệm thu trước khi đổ bê tông',
        category: 'Thi công phần thô',
        location: 'TP Đà Nẵng',
        desc: 'Kỹ sư Công ty TNHH XD&TM Phạm Gia trực tiếp kiểm tra khoảng cách thép sàn, con kê bê tông và độ kín khít cốp pha.',
        backup: 'https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công xây tường bao gạch tuynel và đi hệ thống ống điện nước âm tường',
        category: 'Thi công phần thô',
        location: 'Hòa Xuân, Đà Nẵng',
        desc: 'Xây tường thẳng đứng, mạch vữa no đều kết hợp lắp đặt ống luồn dây điện chống cháy và ống cấp thoát nước đúng bản vẽ M&E.',
        backup: 'https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công hoàn thiện mặt tiền nhà phố 3 tầng phong cách hiện đại',
        category: 'Thi công hoàn thiện',
        location: 'TP Đà Nẵng',
        desc: 'Công tác tô trát ngoại thất, sơn chống thấm, ốp gạch trang trí mặt tiền và lắp đặt hệ lam che nắng thẩm mỹ cao.',
        backup: 'https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi công đóng trần thạch cao, sơn bả matit và ốp lát gạch khổ lớn',
        category: 'Thi công hoàn thiện',
        location: 'Cẩm Lệ, Đà Nẵng',
        desc: 'Hoàn thiện không gian bên trong công trình với đường ron gạch sắc nét, trần thạch cao phẳng mịn và hệ đèn LED âm trần.',
        backup: 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Lắp đặt hệ cửa nhôm kính Xingfa, lan can kính cường lực và cầu thang đá',
        category: 'Thi công hoàn thiện',
        location: 'TP Đà Nẵng',
        desc: 'Thi công lắp đặt hệ cửa nhôm kính cách âm cách nhiệt, cầu thang ốp đá tự nhiên và lan can kính an toàn.',
        backup: 'https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thiết kế kiến trúc và thi công trọn gói biệt thự phố không gian xanh',
        category: 'Thiết kế Kiến trúc – Nội thất',
        location: 'Hòa Xuân, Đà Nẵng',
        desc: 'Phương án kiến trúc tối ưu thông gió và ánh sáng tự nhiên, kết hợp ban công cây xanh thoáng đãng cho gia chủ.',
        backup: 'https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công hoàn thiện nội thất phòng khách và tủ bếp gỗ công nghiệp cao cấp',
        category: 'Thi công nội thất',
        location: 'TP Đà Nẵng',
        desc: 'Lắp đặt trọn gói nội thất phòng khách liền bếp đồng bộ với bản vẽ thiết kế 3D, cốt gỗ chống ẩm bền bỉ.',
        backup: 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Nghiệm thu hoàn thiện và bàn giao công trình nhà ở trọn gói Phạm Gia',
        category: 'Thi công hoàn thiện',
        location: 'TP Đà Nẵng',
        desc: 'Công trình hoàn thiện sắc nét từng chi tiết, vệ sinh công nghiệp sạch sẽ trước khi bàn giao chìa khóa trao tay cho Chủ đầu tư.',
        backup: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=900&q=80'
      }
    ];

    // 2. DANH SÁCH 10 DỰ ÁN TẠI ĐÀ NẴNG (ĐÚNG 10 FILE GOOGLE DRIVE CỦA NGƯỜI DÙNG)
    const daNangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự án Nhà phố hiện đại 3 tầng – Khu đô thị Hòa Xuân, Cẩm Lệ, Đà Nẵng',
        category: 'Nhà phố',
        location: 'KĐT Hòa Xuân, Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói nhà phố 3 tầng diện tích 5x20m tại Khu đô thị sinh thái Hòa Xuân, TP Đà Nẵng.',
        backup: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự án Biệt thự phố 2 mặt tiền sang trọng – Khu Nam Hòa Xuân, Đà Nẵng',
        category: 'Biệt thự',
        location: 'Nam Hòa Xuân, Đà Nẵng',
        desc: 'Biệt thự 2 mặt tiền thiết kế kiến trúc mở, kết hợp hệ lam gỗ ngoài trời và sân vườn tiểu cảnh tại Đà Nẵng.',
        backup: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự án Căn hộ cho thuê & Apartment 5 tầng – Quận Sơn Trà, Đà Nẵng',
        category: 'Khách sạn – Căn hộ – Phòng trọ',
        location: 'Quận Sơn Trà, Đà Nẵng',
        desc: 'Tòa nhà căn hộ dịch vụ cho thuê tối ưu số lượng phòng, thang máy và hệ thống PCCC đạt chuẩn tại Đà Nẵng.',
        backup: 'https://images.unsplash.com/photo-1545324418-cc1a3fa10c00?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự án Nhà phố lệch tầng thông thoáng – Khu đô thị Nam Việt Á, Đà Nẵng',
        category: 'Nhà phố',
        location: 'KĐT Nam Việt Á, Đà Nẵng',
        desc: 'Giải pháp nhà phố có giếng trời trung tâm giúp đối lưu không khí mát mẻ quanh năm tại KĐT Nam Việt Á.',
        backup: 'https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự án Tòa nhà Văn phòng kết hợp kinh doanh – Quận Hải Châu, Đà Nẵng',
        category: 'Văn phòng',
        location: 'Quận Hải Châu, Đà Nẵng',
        desc: 'Thi công tòa nhà văn phòng mặt kính cường lực hiện đại, sàn vượt nhịp lớn tối ưu diện tích làm việc.',
        backup: 'https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự án Biệt thự nghỉ dưỡng sân vườn – Quận Ngũ Hành Sơn, Đà Nẵng',
        category: 'Biệt thự',
        location: 'Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Không gian biệt thự nghỉ dưỡng yên bình với hồ cá Koi, hiên thư giãn và nội thất gỗ tự nhiên sang trọng.',
        backup: 'https://images.unsplash.com/photo-1613977257363-707ba9348227?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự án Nhà phố 4 tầng kết hợp văn phòng gia đình – Hòa Cường, Đà Nẵng',
        category: 'Nhà phố',
        location: 'Hòa Cường, Đà Nẵng',
        desc: 'Công trình nhà phố 4 tầng bố trí tầng trệt làm văn phòng giao dịch và các tầng trên là không gian sinh hoạt tiện nghi.',
        backup: 'https://images.unsplash.com/photo-1600047509807-ba8f99d2cdde?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự án Khách sạn mini & Căn hộ lưu trú du lịch – Khu vực biển Mỹ Khê, Đà Nẵng',
        category: 'Khách sạn – Căn hộ – Phòng trọ',
        location: 'Mỹ Khê, Đà Nẵng',
        desc: 'Thiết kế và thi công hoàn thiện khách sạn - căn hộ du lịch ven biển với nội thất hiện đại, bền bỉ trước khí hậu biển.',
        backup: 'https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự án Nhà phố mái Nhật 3 tầng hiện đại – Khu đô thị FPT City, Đà Nẵng',
        category: 'Nhà phố',
        location: 'KĐT FPT, Đà Nẵng',
        desc: 'Mẫu nhà phố 3 tầng kiến trúc thanh lịch, ban công rộng và hệ cửa nhôm kính lớn đón nắng gió tự nhiên.',
        backup: 'https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự án Trụ sở Văn phòng & Showroom thương mại – Quận Thanh Khê, Đà Nẵng',
        category: 'Văn phòng',
        location: 'Quận Thanh Khê, Đà Nẵng',
        desc: 'Công trình thương mại dịch vụ kết hợp văn phòng đại diện được thi công trọn gói đảm bảo tiến độ và thẩm mỹ.',
        backup: 'https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=900&q=80'
      }
    ];

    // 3. DANH SÁCH MẪU THIẾT KẾ NHÀ PHỐ & NỘI THẤT
    const designTemplates = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Mẫu thiết kế nhà phố 3 tầng mặt tiền 5m hiện đại thoáng sáng',
        category: 'Mẫu thiết kế nhà phố',
        desc: 'Bố trí 4 phòng ngủ, phòng khách thông tầng, phòng thờ và sân thượng trồng cây xanh mát.',
        backup: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Mẫu thiết kế nhà phố 2 mặt tiền kết hợp kinh doanh tại Đà Nẵng',
        category: 'Mẫu thiết kế nhà phố',
        desc: 'Kiến trúc vát góc sang trọng giúp tối đa diện tích tiếp xúc mặt đường và đón sáng tự nhiên.',
        backup: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Mẫu thiết kế nội thất phòng khách liền bếp nhà phố hiện đại',
        category: 'Mẫu thiết kế nội thất',
        desc: 'Thiết kế nội thất gỗ An Cường phủ Acrylic bóng gương kết hợp hệ tủ kịch trần sang trọng.',
        backup: 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Mẫu thiết kế nội thất phòng ngủ Master và không gian thư giãn',
        category: 'Mẫu thiết kế nội thất',
        desc: 'Tông màu ấm cúng, bố trí tủ quần áo âm tường và bàn làm việc hướng ban công thoáng đãng.',
        backup: 'https://images.unsplash.com/photo-1616594039964-ae9021a400a0?auto=format&fit=crop&w=800&q=80'
      }
    ];

    // 4. DỮ LIỆU CHI TIẾT 4 BÀI VIẾT TIN TỨC
    const articlesData = [
      {
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật xây dựng',
        cat: 'Kỹ thuật thi công phần thô',
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        desc: 'Sau khi đổ bê tông móng hoặc dầm sàn, việc giữ ẩm liên tục trong 7 ngày đầu tiên giúp quá trình thủy hóa xi măng diễn ra hoàn toàn, ngăn ngừa nứt chân chim bề mặt và giúp bê tông đạt 100% mác thiết kế. Tại Công ty TNHH XD&TM Phạm Gia, đội ngũ kỹ thuật luôn tưới nước giữ ẩm định kỳ và che phủ bề mặt đúng quy chuẩn.'
      },
      {
        title: 'Tâm lý học không gian: Thiết kế nội thất tác động đến gia đình như thế nào?',
        cat: 'Tư vấn thiết kế nội thất',
        imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        desc: 'Không gian sống có giếng trời thông thoáng, ánh sáng tự nhiên hài hòa và bố trí nội thất gọn gàng giúp giảm căng thẳng, tái tạo năng lượng tích cực mỗi khi trở về nhà.'
      },
      {
        title: '03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư cần biết để phòng tránh',
        cat: 'Cẩm nang xây nhà trọn gói',
        imgId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        desc: 'Ba nỗi lo phổ biến nhất gồm: phát sinh chi phí ngoài dự kiến, vật tư không đúng cam kết và chậm trễ tiến độ. Khi ký hợp đồng tại Xây dựng Phạm Gia, toàn bộ bảng vật tư và tiến độ đều được quy định rõ ràng, minh bạch.'
      },
      {
        title: 'Kinh nghiệm xin giấy phép xây dựng và thiết kế nhà phố tại Đà Nẵng',
        cat: 'Pháp lý xây dựng Đà Nẵng',
        imgId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        desc: 'Trước khi khởi công xây dựng nhà phố tại Hòa Xuân, Cẩm Lệ hay các quận tại Đà Nẵng, Chủ đầu tư cần chuẩn bị giấy chứng nhận quyền sử dụng đất và bản vẽ thiết kế xin phép xây dựng đúng quy chuẩn chiều cao tầng và độ vươn ban công.'
      }
    ];

    // Hàm tạo HTML Card Sản phẩm / Dự án (Không có nhãn dán, tên đầy đủ không bị cắt chữ)
    function createCleanCardHTML(item) {
      const primaryUrl = 'https://lh3.googleusercontent.com/d/' + item.id + '=w900';
      const safeTitle = item.title.replace(/'/g, "\\'");
      const safeCat = item.category.replace(/'/g, "\\'");
      const safeDesc = (item.desc || '').replace(/'/g, "\\'");

      return `
        <div class="flatsome-col-box cursor-pointer" onclick="openProjectModal('${item.id}', '${safeTitle}', '${safeCat}', '${safeDesc}', '${item.backup}')">
          <div class="flatsome-box-image">
            <img 
              src="${primaryUrl}" 
              onerror="handleDriveImageError(this, '${item.id}', '${item.backup}')"
              alt="${item.title}"
              loading="lazy"
            />
          </div>
          <div class="flatsome-box-text">
            <div>
              <h3 class="product-full-title">${item.title}</h3>
              <p class="text-[11px] sm:text-xs text-slate-500">${item.category}</p>
            </div>
            <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] font-semibold text-pgBlue">
              <span>Xem thực tế</span>
              <span class="text-pgGold">Chi tiết →</span>
            </div>
          </div>
        </div>
      `;
    }

    function renderAllGrids() {
      document.getElementById('thi-cong-grid').innerHTML = realConstructionItems.map(createCleanCardHTML).join('');
      document.getElementById('du-an-grid').innerHTML = daNangProjects.map(createCleanCardHTML).join('');
      document.getElementById('mau-tk-grid').innerHTML = designTemplates.map(createCleanCardHTML).join('');
    }

    // Lọc danh mục
    function filterSection(type, category, btnEl) {
      let data = [];
      let gridId = '';
      let filterBarId = '';

      if (type === 'thi-cong') {
        data = realConstructionItems;
        gridId = 'thi-cong-grid';
        filterBarId = 'thi-cong-filters';
      } else if (type === 'du-an') {
        data = daNangProjects;
        gridId = 'du-an-grid';
        filterBarId = 'du-an-filters';
      } else if (type === 'mau-tk') {
        data = designTemplates;
        gridId = 'mau-tk-grid';
        filterBarId = 'mau-tk-filters';
      }

      const filtered = category === 'all' ? data : data.filter(item => item.category === category);
      document.getElementById(gridId).innerHTML = filtered.map(createCleanCardHTML).join('');

      const filterBar = document.getElementById(filterBarId);
      if (filterBar) {
        const buttons = filterBar.querySelectorAll('.cat-pill-btn');
        buttons.forEach(b => {
          b.classList.remove('active');
          if (!btnEl && b.textContent.includes(category)) {
            b.classList.add('active');
          }
        });
        if (btnEl) {
          btnEl.classList.add('active');
        }
      }
    }

    // Mở Modal xem ảnh thực tế
    function openProjectModal(id, title, cat, desc, backup) {
      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.setAttribute('data-retry', '0');
      img.onerror = function() {
        handleDriveImageError(this, id, backup);
      };
      img.src = 'https://lh3.googleusercontent.com/d/' + id + '=w1200';
      img.alt = title;

      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-cat').textContent = 'Danh mục: ' + cat;
      document.getElementById('modal-desc').textContent = desc;
      const driveLink = document.getElementById('modal-drive-link');
      driveLink.style.display = 'inline-block';
      driveLink.href = 'https://drive.google.com/file/d/' + id + '/view?usp=sharing';

      modal.classList.remove('hidden');
    }

    function openArticleModal(idx) {
      const art = articlesData[idx];
      if (!art) return;
      openProjectModal(art.imgId, art.title, art.cat, art.desc, 'https://images.unsplash.com/photo-1541888946425-d09bb18086f6?auto=format&fit=crop&w=900&q=80');
    }

    function closeModal() {
      document.getElementById('detail-modal').classList.add('hidden');
    }

    // Điều khiển 2 Banner tự trượt kích thước bằng nhau
    let currentSlideIdx = 0;
    const totalSlides = 2;
    let slideInterval = null;

    function showSlide(index) {
      currentSlideIdx = (index + totalSlides) % totalSlides;
      const slides = document.querySelectorAll('.hero-slide');
      slides.forEach((sl, i) => {
        if (i === currentSlideIdx) {
          sl.classList.add('active');
        } else {
          sl.classList.remove('active');
        }
      });

      const dot0 = document.getElementById('slider-dot-0');
      const dot1 = document.getElementById('slider-dot-1');
      if (dot0 && dot1) {
        dot0.className = currentSlideIdx === 0 ? 'w-6 h-2 rounded-full bg-pgGold transition-all' : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
        dot1.className = currentSlideIdx === 1 ? 'w-6 h-2 rounded-full bg-pgGold transition-all' : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
      }
    }

    function changeSlide(step) {
      showSlide(currentSlideIdx + step);
      resetSliderTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSliderTimer();
    }

    function resetSliderTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        showSlide(currentSlideIdx + 1);
      }, 5000);
    }

    // Chọn nhanh dịch vụ báo giá
    function selectQuoteService(serviceName) {
      const selectEl = document.getElementById('q-service');
      if (selectEl) {
        selectEl.value = serviceName;
      }
    }

    // Xử lý gửi form tư vấn & báo giá
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      const type = document.getElementById('q-type').value;
      const budget = document.getElementById('q-budget').value;
      const service = document.getElementById('q-service').value;
      const area = document.getElementById('q-area').value.trim();

      const feedback = document.getElementById('quote-feedback');
      feedback.classList.remove('hidden');
      feedback.innerHTML = `
        <strong>Cảm ơn Quý khách ${name}!</strong> Hệ thống <strong>xaydungphamgia.com</strong> đã ghi nhận yêu cầu <em>${service} (${type} - ${budget}${area ? ' - ' + area : ''})</em> qua SĐT <strong>${phone}</strong>. Kỹ sư Phạm Gia (Hotline/Zalo: <strong>0905.736.536</strong>) sẽ liên hệ tư vấn ngay!
      `;
      document.getElementById('quote-request-form').reset();
    }

    // Tạo Favicon đồng bộ với Logo Công ty
    function setupLogoFavicon() {
      const canvas = document.createElement('canvas');
      canvas.width = 128;
      canvas.height = 128;
      const ctx = canvas.getContext('2d');
      ctx.fillStyle = '#0B2E59';
      ctx.fillRect(0, 0, 128, 128);
      ctx.fillStyle = '#D97706';
      ctx.font = 'bold 54px Montserrat, sans-serif';
      ctx.textAlign = 'center';
      ctx.textBaseline = 'middle';
      ctx.fillText('PG', 64, 68);
      const link = document.createElement('link');
      link.rel = 'icon';
      link.href = canvas.toDataURL('image/png');
      document.head.appendChild(link);
    }

    // Khởi chạy khi trang tải xong
    window.addEventListener('DOMContentLoaded', () => {
      renderAllGrids();
      resetSliderTimer();
      setupLogoFavicon();

      // Menu điện thoại
      const toggleBtn = document.getElementById('mobile-menu-toggle');
      const drawer = document.getElementById('mobile-drawer');
      if (toggleBtn && drawer) {
        toggleBtn.addEventListener('click', () => {
          drawer.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-close').forEach(link => {
          link.addEventListener('click', () => {
            drawer.classList.add('hidden');
          });
        });
      }
    });
  </script>
</body>
</html>
