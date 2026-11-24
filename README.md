<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW - Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW chuyên thiết kế, sản xuất và thi công Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng.">

    <!-- Ảnh thumbnail logo khi chia sẻ link trang web (Facebook, Zalo, Messenger) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://giadatphatwindow.com/">
    <meta property="og:title" content="CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW - Cửa Nhôm Xingfa Đà Nẵng">
    <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa chính hãng, Cửa kính cường lực, Phòng tắm kính, Cầu thang kính tại Đà Nẵng. Hotline: 0937 543 988 - 0773 841 136.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w1000">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w1000">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w1000">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w256">

    <!-- Fonts & Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#0A4DA2',
                            dark: '#073675',
                            light: '#EBF3FC',
                            accent: '#E02424',
                            gold: '#D97706'
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS chuẩn Flatsome & chống tràn viền tuyệt đối -->
    <style>
        :root {
            --gdp-primary: #0A4DA2;      /* Màu chủ đạo theo logo (có thể chỉnh 1 dòng trong Flatsome) */
            --gdp-primary-dark: #073675; /* Màu xanh đậm nhấn */
            --gdp-primary-soft: #EBF3FC; /* Nền xanh nhạt */
            --gdp-accent: #DC2626;       /* Màu đỏ cho giá & giảm giá % */
            --gdp-gold: #D97706;         /* Màu vàng kim phụ trợ */
            --gdp-text: #1E293B;
            --gdp-muted: #64748B;
            --gdp-bg-alt: #F6F8FB;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            max-width: 100%;
            overflow-x: hidden;
        }

        body {
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: var(--gdp-text);
            background-color: #FFFFFF;
            margin: 0;
            padding: 0;
            max-width: 100%;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
        }

        /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
        .gdp-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .gdp-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Header Navigation - Không bao giờ xuống dòng tên danh mục */
        .nav-link-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            color: #1E293B;
            padding: 8px 8px;
            border-radius: 6px;
            transition: color 0.2s ease, background-color 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }

        @media (min-width: 1280px) {
            .nav-link-item {
                font-size: 13px;
                padding: 8px 10px;
            }
        }

        @media (min-width: 1440px) {
            .nav-link-item {
                font-size: 13.5px;
                padding: 9px 12px;
            }
        }

        .nav-link-item:hover,
        .nav-link-item.active {
            color: var(--gdp-primary);
            background-color: var(--gdp-primary-soft);
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            position: relative;
        }

        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #FFFFFF;
            border: 1px solid #E2E8F0;
            border-top: 2px solid var(--gdp-primary);
            border-radius: 0 0 10px 10px;
            box-shadow: 0 12px 28px rgba(15, 23, 42, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
            padding: 6px;
        }

        .nav-dropdown:hover .nav-dropdown-menu,
        .nav-dropdown:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .nav-dropdown-link {
            display: block;
            white-space: nowrap;
            padding: 8px 12px;
            font-size: 13px;
            font-weight: 500;
            color: #334155;
            border-radius: 6px;
            transition: all 0.15s ease;
        }

        .nav-dropdown-link:hover {
            background-color: var(--gdp-primary-soft);
            color: var(--gdp-primary);
            padding-left: 16px;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Divider) */
        .flatsome-section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 24px;
            text-align: center;
        }

        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            height: 2px;
            background: #E2E8F0;
            max-width: 120px;
        }

        .flatsome-section-title h2 {
            margin: 0 16px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--gdp-primary);
            letter-spacing: 0.02em;
        }

        /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối, không cắt chữ */
        .hero-slider-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 14px;
            box-shadow: 0 10px 30px rgba(10, 77, 162, 0.12);
        }

        .hero-slider-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
            align-items: stretch;
        }

        .hero-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
            display: flex;
            align-items: center;
        }

        /* Product Card chuẩn Flatsome WooCommerce */
        .product-card {
            background: #FFFFFF;
            border: 1px solid #E5E9F0;
            border-radius: 12px;
            overflow: hidden;
            transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }

        .product-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px rgba(10, 77, 162, 0.1);
            border-color: #BFDBFE;
        }

        /* Badge giảm giá % góc trên bên trái sản phẩm */
        .sale-badge-tl {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: var(--gdp-accent);
            color: #FFFFFF;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 5px 8px;
            border-radius: 6px;
            box-shadow: 0 2px 8px rgba(220, 38, 38, 0.35);
        }

        @media (min-width: 640px) {
            .sale-badge-tl {
                top: 10px;
                left: 10px;
                font-size: 12px;
                padding: 6px 9px;
            }
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        .floating-contact-bar {
            position: fixed;
            right: 12px;
            bottom: 18px;
            z-index: 50;
            display: flex;
            flex-direction: column;
            gap: 10px;
            align-items: flex-end;
        }

        @media (min-width: 768px) {
            .floating-contact-bar {
                right: 18px;
                bottom: 24px;
                gap: 12px;
            }
        }

        .float-btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            border-radius: 9999px;
            color: #FFFFFF;
            font-weight: 700;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            text-decoration: none;
            cursor: pointer;
            border: 2px solid rgba(255, 255, 255, 0.9);
        }

        .float-btn:hover {
            transform: scale(1.06);
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.28);
        }

        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }

        .pulse-hotline {
            animation: pulseRing 2s infinite;
        }

        /* Custom subtle scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #F1F5F9;
        }
        ::-webkit-scrollbar-thumb {
            background: #94A3B8;
            border-radius: 9999px;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ==================== HEADER (CHUẨN FLATSOME, KHÔNG CÓ NÚT GỌI NGAY) ==================== -->
    <header id="site-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm w-full">
        <!-- Top Info Bar (Hiển thị gọn gàng trên máy tính) -->
        <div class="hidden md:block bg-[#0A4DA2] text-white text-xs py-1.5 w-full">
            <div class="gdp-container flex items-center justify-between gap-4">
                <div class="flex items-center gap-5 truncate">
                    <span class="inline-flex items-center gap-1.5">
                        <i class="fa-solid fa-location-dot text-amber-300"></i>
                        114 - 116 Mai Đăng Chơn, Phường Ngũ Hành Sơn, Tp.Đà Nẵng
                    </span>
                    <span class="inline-flex items-center gap-1.5">
                        <i class="fa-regular fa-clock text-amber-300"></i>
                        Làm việc: 07:30 - 18:00 (Thứ 2 - Chủ Nhật)
                    </span>
                </div>
                <div class="flex items-center gap-4 shrink-0">
                    <span class="font-medium">Hotline: 0937 543 988 - 0773 841 136</span>
                    <a href="https://www.facebook.com/profile.php?id=61594081134064" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition" aria-label="Fanpage Facebook">
                        <i class="fa-brands fa-facebook-f"></i>
                    </a>
                </div>
            </div>
        </div>

        <!-- Main Header Row: Logo gọn nhỏ + Danh mục 1 hàng (KHÔNG có nút Gọi ngay) -->
        <div class="gdp-container py-2.5 lg:py-3">
            <div class="flex items-center justify-between gap-2 lg:gap-4 w-full">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" title="CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW">
                    <img
                        src="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w400"
                        data-drive-id="1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut"
                        alt="Logo CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW"
                        class="h-10 sm:h-11 lg:h-11 w-auto max-w-[135px] sm:max-w-[155px] object-contain rounded"
                        onerror="handleDriveImgError(this, 'GIA DAT PHAT')"
                    >
                    <div class="flex flex-col leading-tight sm:hidden">
                        <span class="text-[13px] font-extrabold text-[#0A4DA2] tracking-tight">GIA ĐẠT PHÁT</span>
                        <span class="text-[10px] font-semibold text-slate-500">WINDOW ĐÀ NẴNG</span>
                    </div>
                </a>

                <!-- Danh mục máy tính: Viết liền trên 1 hàng, không bao giờ xuống dòng tên danh mục -->
                <nav class="hidden lg:flex items-center justify-end flex-wrap xl:flex-nowrap gap-y-1 gap-x-0.5 xl:gap-x-1 min-w-0" aria-label="Menu chính">
                    <a href="#trang-chu" class="nav-link-item active">Trang chủ</a>
                    <a href="#gioi-thieu" class="nav-link-item">Giới thiệu</a>

                    <!-- Dropdown: Cửa nhôm xingfa -->
                    <div class="nav-dropdown">
                        <a href="#san-pham-xingfa" class="nav-link-item" onclick="filterProducts('all')">
                            Cửa nhôm xingfa
                            <i class="fa-solid fa-chevron-down text-[10px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="nav-dropdown-link">Cửa nhôm xingfa 1 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="nav-dropdown-link">Cửa nhôm xingfa 2 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="nav-dropdown-link">Cửa nhôm xingfa 3 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="nav-dropdown-link">Cửa nhôm xingfa 4 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="nav-dropdown-link">Cửa nhôm xingfa 5 cánh</a>
                        </div>
                    </div>

                    <a href="#danh-muc-san-pham" class="nav-link-item">Cửa kính cường lực</a>

                    <!-- Dropdown: Sản phẩm -->
                    <div class="nav-dropdown">
                        <a href="#danh-muc-san-pham" class="nav-link-item">
                            Sản phẩm
                            <i class="fa-solid fa-chevron-down text-[10px] opacity-70"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="nav-dropdown-link">Cửa nhôm xingfa</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-nhua-loi-thep')" class="nav-dropdown-link">Cửa nhựa lõi thép</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-kinh-tu-dong')" class="nav-dropdown-link">Cửa kính tự động</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cau-thang-kinh')" class="nav-dropdown-link">Cầu thang kính</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryInfo('kinh-op-bep')" class="nav-dropdown-link">Kính ốp bếp</a>
                            <a href="#danh-muc-san-pham" onclick="openCategoryInfo('phong-tam-kinh')" class="nav-dropdown-link">Phòng tắm kính</a>
                        </div>
                    </div>

                    <a href="#cong-trinh" class="nav-link-item">Công trình</a>
                    <a href="#bao-gia" class="nav-link-item">Báo giá</a>
                    <a href="#tin-tuc" class="nav-link-item">Tin tức</a>
                    <a href="#lien-he" class="nav-link-item">Liên hệ</a>
                </nav>

                <!-- Nút mở menu trên điện thoại & máy tính bảng -->
                <button
                    id="mobile-menu-open"
                    type="button"
                    class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-[#0A4DA2] hover:bg-blue-50 transition shrink-0"
                    aria-label="Mở danh mục"
                >
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- ==================== MOBILE OFF-CANVAS MENU (FLATSOME STYLE) ==================== -->
    <div id="mobile-drawer-overlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden opacity-0 transition-opacity duration-200"></div>
    <aside id="mobile-drawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 bg-[#0A4DA2] text-white">
            <span class="font-bold text-sm uppercase tracking-wide">Danh mục sản phẩm</span>
            <button id="mobile-menu-close" type="button" class="w-8 h-8 flex items-center justify-center rounded-lg hover:bg-white/15" aria-label="Đóng menu">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>

        <nav class="flex-1 overflow-y-auto p-3 space-y-1 text-sm font-medium text-slate-700">
            <a href="#trang-chu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Giới thiệu</a>

            <!-- Accordion: Cửa nhôm xingfa -->
            <div class="border-y border-slate-100 py-1">
                <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2] font-semibold">
                    <span>Cửa nhôm xingfa</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform duration-200"></i>
                </button>
                <div class="mobile-accordion-content hidden pl-4 pr-2 pb-1 space-y-1 text-[13px] text-slate-600">
                    <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-san-pham" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Cửa kính cường lực</a>

            <!-- Accordion: Sản phẩm -->
            <div class="border-b border-slate-100 pb-1">
                <button type="button" class="mobile-accordion-btn w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2] font-semibold">
                    <span>Sản phẩm</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform duration-200"></i>
                </button>
                <div class="mobile-accordion-content hidden pl-4 pr-2 pb-1 space-y-1 text-[13px] text-slate-600">
                    <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhôm xingfa</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-nhua-loi-thep')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa nhựa lõi thép</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-kinh-tu-dong')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cửa kính tự động</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryInfo('cau-thang-kinh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Cầu thang kính</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryInfo('kinh-op-bep')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Kính ốp bếp</a>
                    <a href="#danh-muc-san-pham" onclick="openCategoryInfo('phong-tam-kinh')" class="mobile-nav-link block py-2 px-3 rounded-md hover:bg-blue-50 hover:text-[#0A4DA2]">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Công trình</a>
            <a href="#bao-gia" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Báo giá</a>
            <a href="#tin-tuc" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Tin tức</a>
            <a href="#lien-he" class="mobile-nav-link block px-3 py-2.5 rounded-lg hover:bg-blue-50 hover:text-[#0A4DA2]">Liên hệ</a>
        </nav>

        <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1.5">
            <p class="font-bold text-[#0A4DA2]">CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</p>
            <p><i class="fa-solid fa-location-dot text-[#0A4DA2] mr-1"></i> 114 - 116 Mai Đăng Chơn, Ngũ Hành Sơn, Đà Nẵng</p>
            <p><i class="fa-solid fa-phone text-[#0A4DA2] mr-1"></i> 0937 543 988 - 0773 841 136</p>
        </div>
    </aside>

    <!-- ==================== MAIN CONTENT ==================== -->
    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM TRỌN & CÁCH XA VIỀN) -->
        <section class="py-3 sm:py-4 lg:py-5 bg-white w-full">
            <div class="gdp-container">
                <div class="hero-slider-viewport" id="hero-slider">
                    <div class="hero-slider-track" id="hero-slider-track">

                        <!-- BANNER 1 -->
                        <div class="hero-slide bg-gradient-to-br from-[#073675] via-[#0A4DA2] to-[#1366C9] text-white">
                            <div class="w-full px-7 py-8 sm:px-12 sm:py-10 lg:px-16 lg:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <!-- Nội dung chữ: Cách xa viền, không tràn chữ trên mọi màn hình -->
                                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                                    <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                                        CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW
                                    </p>
                                    <h1 class="text-xl sm:text-2xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                        THI CÔNG CỬA NHÔM XINGFA CHÍNH HÃNG TẠI ĐÀ NẴNG
                                    </h1>
                                    <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-2xl">
                                        Chuyên sản xuất &amp; lắp đặt cửa nhôm Xingfa nhập khẩu tem đỏ, phụ kiện Kinlong đồng bộ. Độ bền vượt trội, cách âm cách nhiệt chuẩn công trình nhà phố, biệt thự và khách sạn.
                                    </p>
                                    <div class="pt-1 flex flex-wrap gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center gap-2 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg shadow transition">
                                            <i class="fa-solid fa-file-invoice"></i>
                                            Nhận báo giá ngay
                                        </a>
                                        <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition">
                                            Xem mẫu cửa
                                        </a>
                                    </div>
                                </div>
                                <!-- Hình ảnh nằm gọn trong khung banner -->
                                <div class="md:col-span-5 flex justify-center">
                                    <div class="w-full max-w-[380px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w1000"
                                            data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                            alt="Cửa nhôm Xingfa Gia Đạt Phát Window Đà Nẵng"
                                            class="w-full h-full object-cover"
                                            onerror="handleDriveImgError(this, 'Cua Nhom Xingfa')"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 (Cấu trúc đối xứng đảm bảo kích thước bằng y hệt Banner 1) -->
                        <div class="hero-slide bg-gradient-to-br from-[#0F294A] via-[#0A4DA2] to-[#0E5AA7] text-white">
                            <div class="w-full px-7 py-8 sm:px-12 sm:py-10 lg:px-16 lg:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="md:col-span-7 space-y-3 sm:space-y-4">
                                    <p class="text-xs sm:text-sm font-semibold uppercase tracking-widest text-amber-300">
                                        GIẢI PHÁP NHÔM KÍNH TRỌN GÓI MIỀN TRUNG
                                    </p>
                                    <h2 class="text-xl sm:text-2xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                        CỬA KÍNH CƯỜNG LỰC &amp; PHÒNG TẮM KÍNH HIỆN ĐẠI
                                    </h2>
                                    <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-2xl">
                                        Thiết kế sang trọng, an toàn tuyệt đối cho phòng tắm kính, cầu thang kính, kính ốp bếp và cửa kính tự động. Khảo sát tận nơi miễn phí — Bảo hành dài hạn tại Đà Nẵng.
                                    </p>
                                    <div class="pt-1 flex flex-wrap gap-3">
                                        <a href="#cong-trinh" class="inline-flex items-center gap-2 bg-amber-500 hover:bg-amber-400 text-slate-950 font-bold text-xs sm:text-sm px-5 py-2.5 rounded-lg shadow transition">
                                            <i class="fa-solid fa-building"></i>
                                            Xem công trình thực tế
                                        </a>
                                        <a href="#danh-muc-san-pham" class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm px-5 py-2.5 rounded-lg transition">
                                            Danh mục sản phẩm
                                        </a>
                                    </div>
                                </div>
                                <div class="md:col-span-5 flex justify-center">
                                    <div class="w-full max-w-[380px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1000"
                                            data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                            alt="Thi công công trình nhôm kính Đà Nẵng"
                                            class="w-full h-full object-cover"
                                            onerror="handleDriveImgError(this, 'Du An Da Nang')"
                                        >
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút điều hướng Banner gọn gàng -->
                    <button id="hero-prev" type="button" aria-label="Banner trước" class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition z-10">
                        <i class="fa-solid fa-chevron-left text-sm"></i>
                    </button>
                    <button id="hero-next" type="button" aria-label="Banner tiếp theo" class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition z-10">
                        <i class="fa-solid fa-chevron-right text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo Slide -->
                    <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                        <button type="button" data-slide="0" class="hero-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
                        <button type="button" data-slide="1" class="hero-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Slide 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: GIỚI THIỆU CÔNG TY (THEO BỐ CỤC MẪU NGOCHANWINDOW.COM) -->
        <section id="gioi-thieu" class="py-8 lg:py-12 bg-[#F6F8FB] w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</h2>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">
                    <!-- Cột giới thiệu -->
                    <div class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-6 border border-slate-200 shadow-sm space-y-3.5 text-sm sm:text-[15px] leading-relaxed text-slate-600">
                        <p>
                            <strong class="text-[#0A4DA2]">CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</strong> là đơn vị uy tín chuyên thiết kế, gia công và thi công lắp đặt các hạng mục nhôm kính cao cấp tại <strong>Đà Nẵng và khu vực Miền Trung</strong>.
                        </p>
                        <p>
                            Các dòng sản phẩm chủ lực của Gia Đạt Phát Window gồm: <strong>Cửa nhôm Xingfa nhập khẩu chính hãng</strong>, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính hiện đại.
                        </p>
                        <p>
                            Với phương châm <em>“Chất lượng tạo niềm tin – Cửa đẹp cho mọi công trình”</em>, chúng tôi cam kết vật tư chuẩn nguồn gốc, thi công đúng tiến độ, thẩm mỹ tinh tế và chính sách bảo hành dài hạn, chu đáo.
                        </p>

                        <!-- Thông số năng lực (4 ô gọn chuẩn Flatsome) -->
                        <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-3 border-t border-slate-100">
                            <div class="text-center p-2.5 rounded-lg bg-[#EBF3FC]">
                                <div class="text-xl sm:text-2xl font-extrabold text-[#0A4DA2]">150+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Dự án hoàn thành</div>
                            </div>
                            <div class="text-center p-2.5 rounded-lg bg-[#EBF3FC]">
                                <div class="text-xl sm:text-2xl font-extrabold text-[#0A4DA2]">50+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Nhân sự lành nghề</div>
                            </div>
                            <div class="text-center p-2.5 rounded-lg bg-[#EBF3FC]">
                                <div class="text-xl sm:text-2xl font-extrabold text-[#0A4DA2]">100+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Mẫu cửa chất lượng</div>
                            </div>
                            <div class="text-center p-2.5 rounded-lg bg-[#EBF3FC]">
                                <div class="text-xl sm:text-2xl font-extrabold text-[#0A4DA2]">100%</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 font-medium mt-0.5">Khách hàng hài lòng</div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột cam kết dịch vụ (tương tự bảng ưu đãi mẫu ngochanwindow.com) -->
                    <div class="lg:col-span-5 bg-white rounded-xl p-5 sm:p-6 border border-slate-200 shadow-sm">
                        <h3 class="text-sm sm:text-base font-bold text-[#0A4DA2] uppercase pb-3 mb-3 border-b border-slate-100 flex items-center gap-2">
                            <i class="fa-solid fa-shield-halved text-amber-500"></i>
                            Cam kết từ Gia Đạt Phát Window
                        </h3>
                        <ul class="space-y-3 text-sm text-slate-700">
                            <li class="flex items-start gap-3">
                                <span class="w-6 h-6 rounded-full bg-blue-100 text-[#0A4DA2] flex items-center justify-center shrink-0 mt-0.5 text-xs">
                                    <i class="fa-solid fa-phone"></i>
                                </span>
                                <div>
                                    <span class="font-semibold text-slate-900">Tư vấn &amp; Hotline:</span>
                                    <span class="text-[#DC2626] font-bold"> 0937 543 988 - 0773 841 136</span>
                                </div>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-6 h-6 rounded-full bg-blue-100 text-[#0A4DA2] flex items-center justify-center shrink-0 mt-0.5 text-xs">
                                    <i class="fa-solid fa-ruler-combined"></i>
                                </span>
                                <div>
                                    <span class="font-semibold text-slate-900">Dịch vụ ưu đãi:</span> Khảo sát, đo đạc và lắp đặt tận nơi miễn phí tại Đà Nẵng.
                                </div>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-6 h-6 rounded-full bg-blue-100 text-[#0A4DA2] flex items-center justify-center shrink-0 mt-0.5 text-xs">
                                    <i class="fa-solid fa-tags"></i>
                                </span>
                                <div>
                                    <span class="font-semibold text-slate-900">Giá xưởng cạnh tranh:</span> Ưu đãi trực tiếp đến 20% cho công trình trọn gói.
                                </div>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-6 h-6 rounded-full bg-blue-100 text-[#0A4DA2] flex items-center justify-center shrink-0 mt-0.5 text-xs">
                                    <i class="fa-solid fa-award"></i>
                                </span>
                                <div>
                                    <span class="font-semibold text-slate-900">Vật tư chính hãng:</span> Thanh nhôm Xingfa tem đỏ Quảng Đông &amp; phụ kiện đồng bộ.
                                </div>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-6 h-6 rounded-full bg-blue-100 text-[#0A4DA2] flex items-center justify-center shrink-0 mt-0.5 text-xs">
                                    <i class="fa-solid fa-screwdriver-wrench"></i>
                                </span>
                                <div>
                                    <span class="font-semibold text-slate-900">Bảo hành chuẩn mực:</span> Bảo hành màu sơn &amp; kết cấu nhôm 5 năm, phụ kiện 24 tháng.
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT TRÊN MOBILE, GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI) -->
        <section id="san-pham-xingfa" class="py-8 lg:py-12 bg-white w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG</h2>
                </div>

                <!-- Bộ lọc gọn nhẹ theo số cánh -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="product-filter-bar">
                    <button type="button" onclick="filterProducts('all')" data-filter="all" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-[#0A4DA2] text-white transition">Tất cả</button>
                    <button type="button" onclick="filterProducts('1-canh')" data-filter="1-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 hover:text-[#0A4DA2] transition">1 cánh</button>
                    <button type="button" onclick="filterProducts('2-canh')" data-filter="2-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 hover:text-[#0A4DA2] transition">2 cánh</button>
                    <button type="button" onclick="filterProducts('3-canh')" data-filter="3-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 hover:text-[#0A4DA2] transition">3 cánh</button>
                    <button type="button" onclick="filterProducts('4-canh')" data-filter="4-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 hover:text-[#0A4DA2] transition">4 cánh</button>
                    <button type="button" onclick="filterProducts('5-canh')" data-filter="5-canh" class="filter-btn px-3 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 hover:text-[#0A4DA2] transition">Xếp trượt / 5 cánh</button>
                </div>

                <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính bảng & PC -->
                <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                    <!-- Sản phẩm được render tự động từ JS để dễ quản lý & tương tác chi tiết -->
                </div>
            </div>
        </section>

        <!-- SECTION 4: DANH MỤC SẢN PHẨM NỔI BẬT (6 DANH MỤC CHUẨN WEB MẪU, CHỮ NHỎ GỌN) -->
        <section id="danh-muc-san-pham" class="py-8 lg:py-12 bg-[#F6F8FB] w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">DANH MỤC SẢN PHẨM NỔI BẬT</h2>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 lg:gap-5" id="categories-grid">
                    <!-- Danh mục 1: Cửa nhôm xingfa -->
                    <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w800"
                                data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                alt="Cửa nhôm Xingfa"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Cua Nhom Xingfa')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                CỬA NHÔM XINGFA
                            </h3>
                        </div>
                    </a>

                    <!-- Danh mục 2: Cửa nhựa lõi thép -->
                    <button type="button" onclick="openCategoryInfo('cua-nhua-loi-thep')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w800"
                                data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                alt="Cửa nhựa lõi thép"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Cua Nhua Loi Thep')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center w-full flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                CỬA NHỰA LÕI THÉP
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 3: Cửa tự động -->
                    <button type="button" onclick="openCategoryInfo('cua-kinh-tu-dong')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w800"
                                data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                                alt="Cửa kính tự động"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Cua Tu Dong')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center w-full flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                CỬA KÍNH TỰ ĐỘNG
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 4: Cầu thang kính -->
                    <button type="button" onclick="openCategoryInfo('cau-thang-kinh')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w800"
                                data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                                alt="Cầu thang kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Cau Thang Kinh')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center w-full flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                CẦU THANG KÍNH
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 5: Kính ốp bếp -->
                    <button type="button" onclick="openCategoryInfo('kinh-op-bep')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w800"
                                data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                                alt="Kính ốp bếp"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Kinh Op Bep')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center w-full flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                KÍNH ỐP BẾP
                            </h3>
                        </div>
                    </button>

                    <!-- Danh mục 6: Phòng tắm kính -->
                    <button type="button" onclick="openCategoryInfo('phong-tam-kinh')" class="group bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col text-left">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img
                                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w800"
                                data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                alt="Phòng tắm kính"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                onerror="handleDriveImgError(this, 'Phong Tam Kinh')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3 text-center w-full flex-1 flex items-center justify-center">
                            <h3 class="text-[12px] sm:text-[13px] font-bold uppercase text-slate-800 group-hover:text-[#0A4DA2] leading-snug">
                                PHÒNG TẮM KÍNH
                            </h3>
                        </div>
                    </button>
                </div>
            </div>
        </section>

        <!-- SECTION 5: BẢNG BÁO GIÁ THAM KHẢO NHANH -->
        <section id="bao-gia" class="py-8 lg:py-12 bg-white w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">BẢNG BÁO GIÁ THAM KHẢO TẠI ĐÀ NẴNG</h2>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
                    <div class="overflow-x-auto w-full">
                        <table class="w-full text-left border-collapse text-xs sm:text-sm">
                            <thead>
                                <tr class="bg-[#0A4DA2] text-white">
                                    <th class="py-3 px-3 sm:px-4 font-semibold w-12 text-center">STT</th>
                                    <th class="py-3 px-3 sm:px-4 font-semibold">Hạng mục cửa nhôm kính</th>
                                    <th class="py-3 px-3 sm:px-4 font-semibold hidden md:table-cell">Quy cách nhôm &amp; kính</th>
                                    <th class="py-3 px-3 sm:px-4 font-semibold text-right whitespace-nowrap">Đơn giá (VNĐ/m²)</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-slate-200">
                                <tr class="hover:bg-blue-50/50 transition">
                                    <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-500">01</td>
                                    <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa sổ mở quay / mở hất nhôm Xingfa hệ 55</td>
                                    <td class="py-3 px-3 sm:px-4 text-slate-600 hidden md:table-cell">Nhôm Xingfa tem đỏ dày 1.4mm, kính cường lực 8mm</td>
                                    <td class="py-3 px-3 sm:px-4 text-right font-bold text-[#DC2626] whitespace-nowrap">1.650.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-blue-50/50 transition">
                                    <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-500">02</td>
                                    <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi mở quay 1 cánh nhôm Xingfa hệ 55</td>
                                    <td class="py-3 px-3 sm:px-4 text-slate-600 hidden md:table-cell">Nhôm Xingfa tem đỏ dày 2.0mm, kính an toàn 8mm</td>
                                    <td class="py-3 px-3 sm:px-4 text-right font-bold text-[#DC2626] whitespace-nowrap">1.750.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-blue-50/50 transition">
                                    <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-500">03</td>
                                    <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi mở quay 2 cánh / 4 cánh nhôm Xingfa</td>
                                    <td class="py-3 px-3 sm:px-4 text-slate-600 hidden md:table-cell">Nhôm Xingfa tem đỏ dày 2.0mm, gioăng EPDM kín khít</td>
                                    <td class="py-3 px-3 sm:px-4 text-right font-bold text-[#DC2626] whitespace-nowrap">1.800.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-blue-50/50 transition">
                                    <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-500">04</td>
                                    <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa đi xếp trượt nhôm Xingfa hệ 63</td>
                                    <td class="py-3 px-3 sm:px-4 text-slate-600 hidden md:table-cell">Nhôm Xingfa dày 1.8 - 2.5mm, ray trượt chịu lực</td>
                                    <td class="py-3 px-3 sm:px-4 text-right font-bold text-[#DC2626] whitespace-nowrap">2.150.000 ₫</td>
                                </tr>
                                <tr class="hover:bg-blue-50/50 transition">
                                    <td class="py-3 px-3 sm:px-4 text-center font-semibold text-slate-500">05</td>
                                    <td class="py-3 px-3 sm:px-4 font-semibold text-slate-800">Cửa kính cường lực / Phòng tắm kính / Cầu thang kính</td>
                                    <td class="py-3 px-3 sm:px-4 text-slate-600 hidden md:table-cell">Kính cường lực 10mm - 12mm phôi Việt Nhật, phụ kiện Inox 304</td>
                                    <td class="py-3 px-3 sm:px-4 text-right font-bold text-[#DC2626] whitespace-nowrap">Từ 750.000 ₫</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <div class="bg-slate-50 px-4 py-3 flex flex-col sm:flex-row sm:items-center justify-between gap-2 text-xs text-slate-600 border-t border-slate-200">
                        <span>* Giá trên mang tính tham khảo, báo giá chính xác theo bản vẽ &amp; diện tích thực tế.</span>
                        <a href="#form-bao-gia" class="font-bold text-[#0A4DA2] hover:underline whitespace-nowrap">
                            Đăng ký nhận báo giá chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 6: CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG -->
        <section id="cong-trinh" class="py-8 lg:py-12 bg-[#F6F8FB] w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5 lg:gap-6" id="projects-grid">
                    <!-- 6 dự án Đà Nẵng được render từ JS với ảnh Google Drive chuẩn xác -->
                </div>
            </div>
        </section>

        <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ -->
        <section id="tin-tuc" class="py-8 lg:py-12 bg-white w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">TIN TỨC &amp; KINH NGHIỆM NHÔM KÍNH</h2>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5" id="articles-grid">
                    <!-- Danh mục các bài viết trang chủ được render từ JS -->
                </div>
            </div>
        </section>

        <!-- SECTION 8: FORM YÊU CẦU BÁO GIÁ + GOOGLE MAP + FANPAGE FACEBOOK TRANG CHỦ -->
        <section id="lien-he" class="py-8 lg:py-12 bg-[#F6F8FB] w-full">
            <div class="gdp-container space-y-8">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">YÊU CẦU BÁO GIÁ &amp; KẾT NỐI VỚI CHÚNG TÔI</h2>
                </div>

                <!-- Hàng 1: Form Yêu Cầu & Báo Giá + Fanpage Facebook -->
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Form Yêu cầu và Báo giá trang chủ -->
                    <div id="form-bao-gia" class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-7 border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-[#0A4DA2] uppercase mb-1.5">
                                ĐĂNG KÝ NHẬN TƯ VẤN &amp; BÁO GIÁ MIỄN PHÍ
                            </h3>
                            <p class="text-xs sm:text-sm text-slate-500 mb-5">
                                Quý khách vui lòng để lại thông tin, đội ngũ kỹ thuật Gia Đạt Phát Window sẽ liên hệ khảo sát và gửi báo giá chi tiết trong 15 phút.
                            </p>

                            <form id="quote-form" class="space-y-4">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                        <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn"
                                            class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-[#0A4DA2] focus:ring-2 focus:ring-blue-100 outline-none transition">
                                    </div>
                                    <div>
                                        <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                        <input id="q-phone" name="phone" type="tel" required placeholder="Ví dụ: 0937 543 988"
                                            class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-[#0A4DA2] focus:ring-2 focus:ring-blue-100 outline-none transition">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="q-product" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                                        <select id="q-product" name="product"
                                            class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-[#0A4DA2] focus:ring-2 focus:ring-blue-100 outline-none transition">
                                            <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1 - 5 cánh)</option>
                                            <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                            <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                            <option value="Cửa kính tự động">Cửa kính tự động</option>
                                            <option value="Cầu thang kính">Cầu thang kính</option>
                                            <option value="Kính ốp bếp">Kính ốp bếp</option>
                                            <option value="Phòng tắm kính">Phòng tắm kính</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label for="q-address" class="block text-xs font-semibold text-slate-700 mb-1">Khu vực công trình</label>
                                        <input id="q-address" name="address" type="text" placeholder="Quận/Huyện tại Đà Nẵng..."
                                            class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-[#0A4DA2] focus:ring-2 focus:ring-blue-100 outline-none transition">
                                    </div>
                                </div>

                                <div>
                                    <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu (kích thước, số lượng dự kiến)</label>
                                    <textarea id="q-note" name="note" rows="3" placeholder="Mô tả sơ bộ nhu cầu lắp đặt của quý khách..."
                                        class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-[#0A4DA2] focus:ring-2 focus:ring-blue-100 outline-none transition resize-none"></textarea>
                                </div>

                                <button type="submit"
                                    class="w-full sm:w-auto px-7 py-3 bg-[#0A4DA2] hover:bg-[#073675] text-white font-bold text-sm rounded-lg shadow transition inline-flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    Gửi yêu cầu báo giá ngay
                                </button>
                            </form>
                        </div>
                    </div>

                    <!-- Fanpage Facebook đưa trực tiếp ra ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl p-5 sm:p-6 border border-slate-200 shadow-sm flex flex-col">
                        <div class="flex items-center justify-between mb-3 pb-3 border-b border-slate-100">
                            <h3 class="text-sm sm:text-base font-extrabold text-[#0A4DA2] uppercase flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-xl"></i>
                                FANPAGE FACEBOOK CHÍNH THỨC
                            </h3>
                            <a href="https://www.facebook.com/profile.php?id=61594081134064" target="_blank" rel="noopener noreferrer"
                                class="text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap">
                                Mở Facebook <i class="fa-solid fa-up-right-from-square ml-0.5"></i>
                            </a>
                        </div>

                        <!-- Thẻ nhận diện Fanpage luôn hiển thị đẹp kể cả khi trình duyệt chặn cookie Facebook -->
                        <div class="rounded-xl border border-slate-200 bg-gradient-to-r from-[#0A4DA2] to-[#1877F2] p-4 text-white mb-3">
                            <div class="flex items-center gap-3">
                                <div class="w-12 h-12 rounded-full bg-white p-1 shrink-0 shadow overflow-hidden flex items-center justify-center">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w256"
                                        data-drive-id="1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut"
                                        alt="Fanpage Gia Đạt Phát Window"
                                        class="w-full h-full object-contain"
                                        onerror="handleDriveImgError(this, 'GDP')"
                                    >
                                </div>
                                <div class="min-w-0">
                                    <p class="font-bold text-sm leading-snug">CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</p>
                                    <p class="text-[11px] text-blue-100">Cửa nhôm Xingfa • Kính cường lực Đà Nẵng</p>
                                </div>
                            </div>
                            <div class="mt-3 flex flex-wrap gap-2">
                                <a href="https://www.facebook.com/profile.php?id=61594081134064" target="_blank" rel="noopener noreferrer"
                                    class="inline-flex items-center gap-1.5 bg-white text-[#1877F2] hover:bg-blue-50 font-bold text-xs px-3.5 py-2 rounded-lg transition">
                                    <i class="fa-solid fa-thumbs-up"></i>
                                    Theo dõi Fanpage
                                </a>
                                <a href="https://www.facebook.com/profile.php?id=61594081134064" target="_blank" rel="noopener noreferrer"
                                    class="inline-flex items-center gap-1.5 bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs px-3.5 py-2 rounded-lg transition">
                                    <i class="fa-brands fa-facebook-messenger"></i>
                                    Nhắn tin tư vấn
                                </a>
                            </div>
                        </div>

                        <!-- Nhúng Facebook Page Plugin trực tiếp -->
                        <div class="flex-1 w-full rounded-xl overflow-hidden border border-slate-200 bg-slate-50 min-h-[215px]">
                            <iframe
                                title="Fanpage CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61594081134064&tabs=timeline&width=500&height=230&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                class="w-full h-[230px] border-0"
                                scrolling="no"
                                frameborder="0"
                                allowfullscreen="true"
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                loading="lazy">
                            </iframe>
                        </div>
                    </div>
                </div>

                <!-- Hàng 2: Bản đồ Google Map đưa ra ngoài trang chủ -->
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-[#0A4DA2] uppercase flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-[#DC2626]"></i>
                                BẢN ĐỒ CHỈ ĐƯỜNG — XƯỞNG &amp; SHOWROOM GIA ĐẠT PHÁT WINDOW
                            </h3>
                            <p class="text-xs sm:text-sm text-slate-600 mt-0.5">
                                Địa chỉ: <strong>114 - 116 Mai Đăng Chơn, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</strong>
                            </p>
                        </div>
                        <a
                            href="https://www.google.com/maps/search/?api=1&query=114+Mai+%C4%90%C4%83ng+Ch%C6%A1n,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng"
                            target="_blank"
                            rel="noopener noreferrer"
                            class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-[#0A4DA2] hover:text-[#073675] bg-blue-50 px-3.5 py-2 rounded-lg transition self-start sm:self-auto"
                        >
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            Mở Google Maps
                        </a>
                    </div>
                    <div class="w-full h-[280px] sm:h-[340px] lg:h-[380px] rounded-xl overflow-hidden border border-slate-200">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW - 114 - 116 Mai Đăng Chơn, Đà Nẵng"
                            src="https://maps.google.com/maps?q=114+Mai+%C4%90%C4%83ng+Ch%C6%A1n,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 9: ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC TỪ GOOGLE DRIVE) -->
        <section class="py-8 lg:py-10 bg-white border-t border-slate-200 w-full">
            <div class="gdp-container">
                <div class="flatsome-section-title">
                    <h2 class="text-base sm:text-xl lg:text-2xl">ĐỐI TÁC CỦA CHÚNG TÔI</h2>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w500" data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác 1" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 1')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w500" data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác 2" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 2')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w500" data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác 3" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 3')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w500" data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác 4" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 4')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w500" data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác 5" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 5')">
                    </div>
                    <div class="bg-white border border-slate-200 rounded-xl p-3 flex items-center justify-center h-20 sm:h-24 hover:border-[#0A4DA2] hover:shadow-sm transition">
                        <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w500" data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác 6" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, 'Doi Tac 6')">
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- ==================== FOOTER (CHUẨN FLATSOME) ==================== -->
    <footer class="bg-[#072B5E] text-blue-100 w-full">
        <div class="gdp-container py-10 lg:py-12">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="inline-block bg-white p-2 rounded-lg">
                        <img
                            src="https://lh3.googleusercontent.com/d/1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut=w400"
                            data-drive-id="1GxeIgxv1V6TTWrsInWBgjMBSW-kxO5ut"
                            alt="Logo CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW"
                            class="h-10 w-auto max-w-[150px] object-contain"
                            onerror="handleDriveImgError(this, 'GIA DAT PHAT')"
                        >
                    </div>
                    <h4 class="text-white font-bold text-sm uppercase">CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px] leading-relaxed">
                        <li><i class="fa-solid fa-building text-amber-400 mr-2"></i>MST: 0402267476</li>
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i>114 - 116 Mai Đăng Chơn, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</li>
                        <li>
                            <i class="fa-solid fa-phone text-amber-400 mr-2"></i>
                            <a href="tel:0937543988" class="hover:text-white font-semibold">0937 543 988</a> -
                            <a href="tel:0773841136" class="hover:text-white font-semibold">0773 841 136</a>
                        </li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i>Website: giadatphatwindow.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase pb-2 mb-3 border-b border-white/15">Cửa nhôm Xingfa</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('5-canh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhôm xingfa 5 cánh / Xếp trượt</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase pb-2 mb-3 border-b border-white/15">Danh mục dịch vụ</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-nhua-loi-thep')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa nhựa lõi thép Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryInfo('cua-kinh-tu-dong')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa kính tự động Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cửa kính cường lực Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryInfo('cau-thang-kinh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Cầu thang kính cường lực</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryInfo('kinh-op-bep')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Kính ốp bếp đẹp Đà Nẵng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="openCategoryInfo('phong-tam-kinh')" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Phòng tắm kính hiện đại</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase pb-2 mb-3 border-b border-white/15">Liên kết nhanh</h4>
                    <ul class="space-y-2 text-xs sm:text-[13px] mb-4">
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Giới thiệu công ty</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Công trình tiêu biểu</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Bảng báo giá mới nhất</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Tin tức &amp; Tư vấn</a></li>
                    </ul>
                    <div class="flex items-center gap-2.5">
                        <a href="https://www.facebook.com/profile.php?id=61594081134064" target="_blank" rel="noopener noreferrer" aria-label="Facebook"
                            class="w-9 h-9 rounded-lg bg-[#1877F2] hover:opacity-90 text-white flex items-center justify-center transition">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://zalo.me/0937543988" target="_blank" rel="noopener noreferrer" aria-label="Zalo"
                            class="w-9 h-9 rounded-lg bg-[#0068FF] hover:opacity-90 text-white flex items-center justify-center font-extrabold text-[11px] transition">
                            Zalo
                        </a>
                        <a href="tel:0937543988" aria-label="Hotline"
                            class="w-9 h-9 rounded-lg bg-[#DC2626] hover:opacity-90 text-white flex items-center justify-center transition">
                            <i class="fa-solid fa-phone"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <div class="bg-[#051E43] py-3.5 border-t border-white/10">
            <div class="gdp-container flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-blue-200 text-center">
                <p>Copyright 2026 © <strong>CÔNG TY TNHH GIA ĐẠT PHÁT WINDOW</strong>. All rights reserved.</p>
                <p>Tên miền: <strong class="text-white">giadatphatwindow.com</strong></p>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) ==================== -->
    <div class="floating-contact-bar" aria-label="Liên hệ nhanh">
        <!-- Nút Facebook -->
        <a
            href="https://www.facebook.com/profile.php?id=61594081134064"
            target="_blank"
            rel="noopener noreferrer"
            class="float-btn bg-[#1877F2] h-11 px-3 sm:px-4"
            title="Nhắn tin Facebook Gia Đạt Phát Window"
        >
            <i class="fa-brands fa-facebook-messenger text-lg"></i>
            <span class="hidden md:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a
            href="https://zalo.me/0937543988"
            target="_blank"
            rel="noopener noreferrer"
            class="float-btn bg-[#0068FF] h-11 px-3 sm:px-4"
            title="Chat Zalo: 0937 543 988"
        >
            <span class="font-extrabold text-xs tracking-tight bg-white text-[#0068FF] px-1.5 py-0.5 rounded">Zalo</span>
            <span class="hidden md:inline text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <button
            type="button"
            onclick="openHotlineModal()"
            class="float-btn pulse-hotline bg-[#DC2626] h-11 px-3.5 sm:px-4"
            title="Gọi Hotline: 0937 543 988 - 0773 841 136"
        >
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="text-xs font-bold whitespace-nowrap">0937 543 988</span>
        </button>
    </div>

    <!-- ==================== MODAL CHI TIẾT (SẢN PHẨM / DỰ ÁN / BÀI VIẾT / HOTLINE) ==================== -->
    <div id="info-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-3 sm:p-5">
        <div class="bg-white rounded-2xl max-w-xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200 animate-fade">
            <div class="sticky top-0 bg-white border-b border-slate-200 px-5 py-3.5 flex items-center justify-between gap-3 z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-[#0A4DA2] leading-snug">Chi tiết</h3>
                <button type="button" onclick="closeInfoModal()" class="w-8 h-8 rounded-lg hover:bg-slate-100 text-slate-500 flex items-center justify-center shrink-0" aria-label="Đóng">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div id="modal-body" class="p-5 text-sm text-slate-700 space-y-4"></div>
        </div>
    </div>

    <!-- Toast Thông báo (Không dùng alert) -->
    <div id="toast-box" class="fixed top-20 right-4 z-50 max-w-xs sm:max-w-sm bg-emerald-600 text-white px-4 py-3 rounded-xl shadow-xl hidden items-start gap-3 text-xs sm:text-sm">
        <i class="fa-solid fa-circle-check text-lg mt-0.5"></i>
        <div id="toast-message" class="leading-relaxed"></div>
    </div>

    <!-- ==================== JAVASCRIPT LOGIC ==================== -->
    <script>
        /**
         * Xử lý dự phòng nhiều tầng cho ảnh Google Drive để luôn hiển thị ổn định
         */
        function handleDriveImgError(imgEl, label) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);

            if (driveId && step === 0) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
            } else {
                imgEl.onerror = null;
                const text = encodeURIComponent(label || 'Gia Dat Phat Window');
                imgEl.src = `https://placehold.co/600x450/0A4DA2/FFFFFF?text=${text}`;
            }
        }

        /* ==================== DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA ==================== */
        const PRODUCTS = [
            {
                id: 1,
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: '1-canh',
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                oldPrice: '2.150.000 ₫',
                price: '1.750.000 ₫',
                discount: '-19%',
                unit: '/m²',
                specs: 'Thanh nhôm Xingfa hệ 55 tem đỏ Quảng Đông dày 2.0mm, kính cường lực 8mm, phụ kiện Kinlong chính hãng đồng bộ, bảo hành 5 năm.'
            },
            {
                id: 2,
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: '2-canh',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                oldPrice: '2.200.000 ₫',
                price: '1.800.000 ₫',
                discount: '-18%',
                unit: '/m²',
                specs: 'Thiết kế mở quay 2 cánh sang trọng cho mặt tiền, ban công. Nhôm Xingfa dày 2.0mm sơn tĩnh điện cao cấp chống muối biển Đà Nẵng.'
            },
            {
                id: 3,
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: '3-canh',
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                oldPrice: '2.300.000 ₫',
                price: '1.890.000 ₫',
                discount: '-18%',
                unit: '/m²',
                specs: 'Kết cấu khung bao cứng vững, gioăng kép EPDM kín nước cách âm tối đa, khóa đa điểm Kinlong an toàn vượt trội.'
            },
            {
                id: 4,
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: '4-canh',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                oldPrice: '2.350.000 ₫',
                price: '1.950.000 ₫',
                discount: '-17%',
                unit: '/m²',
                specs: 'Mẫu cửa chính 4 cánh được ưa chuộng nhất cho nhà phố, biệt thự tại Đà Nẵng. Mở rộng tối đa không gian đón sáng và thông gió.'
            },
            {
                id: 5,
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: '5-canh',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                oldPrice: '2.650.000 ₫',
                price: '2.150.000 ₫',
                discount: '-19%',
                unit: '/m²',
                specs: 'Nhôm Xingfa hệ 63 xếp gấp gọn gàng (từ 4 - 5 - 6 cánh), ray trượt êm ái, tối ưu tầm nhìn sân vườn, hồ bơi và khách sạn.'
            },
            {
                id: 6,
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: '2-canh',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                oldPrice: '1.950.000 ₫',
                price: '1.650.000 ₫',
                discount: '-15%',
                unit: '/m²',
                specs: 'Thanh nhôm hệ 55 dày 1.4mm, bản lề chữ A Inox 304 chống gió giật mạnh, mở hất lấy gió ngay cả khi trời mưa.'
            }
        ];

        /* ==================== DỮ LIỆU 6 DỰ ÁN TẠI ĐÀ NẴNG ==================== */
        const PROJECTS = [
            {
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                location: 'Đà Nẵng – Quảng Nam',
                scope: 'Thi công hạng mục cửa nhôm Xingfa cao cấp, vách kính cường lực mặt dựng và phòng tắm kính cho khu nghỉ dưỡng 4 sao.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                location: 'Tp. Đà Nẵng',
                scope: 'Cung cấp và lắp đặt đồng bộ hệ cửa nhôm kính cách âm, cửa đi ban công chống gió bão và cabin tắm kính.'
            },
            {
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                location: 'Tp. Đà Nẵng',
                scope: 'Hoàn thiện hệ mặt dựng kính, cửa tự động sảnh chính và toàn bộ cửa nhôm Xingfa phòng lưu trú.'
            },
            {
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                location: 'Biển Mỹ Khê, Tp. Đà Nẵng',
                scope: 'Thi công cửa nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển, vách kính an toàn hướng biển.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                location: 'Tp. Đà Nẵng',
                scope: 'Gia công lắp đặt trọn gói cửa sổ mở hất, cửa đi mở quay nhôm Xingfa và lan can cầu thang kính cường lực.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                location: 'Tp. Đà Nẵng',
                scope: 'Cung cấp và lắp đặt hoàn thiện hạng mục nhôm kính nội ngoại thất đạt chuẩn thẩm mỹ khách sạn boutique.'
            }
        ];

        /* ==================== DỮ LIỆU DANH MỤC CHI TIẾT ==================== */
        const CATEGORY_DETAILS = {
            'cua-nhua-loi-thep': {
                title: 'Cửa nhựa lõi thép uPVC Gia Đạt Phát Window',
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                desc: 'Thanh nhựa uPVC gia cường lõi thép mạ kẽm chịu lực tốt, khả năng cách âm, cách nhiệt vượt trội, không cong vênh mối mọt, chi phí tiết kiệm cho nhà phố và văn phòng tại Đà Nẵng.'
            },
            'cua-kinh-tu-dong': {
                title: 'Cửa kính tự động chính hãng tại Đà Nẵng',
                driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                desc: 'Hệ thống mắt thần cảm biến nhạy bén, motor vận hành êm ái, kính cường lực 10mm - 12mm an toàn tuyệt đối. Phù hợp sảnh khách sạn, showroom, siêu thị và văn phòng.'
            },
            'cau-thang-kinh': {
                title: 'Cầu thang kính cường lực hiện đại',
                driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                desc: 'Sử dụng kính cường lực 10mm - 12mm kết hợp trụ Inox 304 và tay vịn gỗ căm xe/sồi sang trọng, giúp không gian ngôi nhà luôn rộng rãi và tràn ngập ánh sáng.'
            },
            'kinh-op-bep': {
                title: 'Kính màu ốp bếp cường lực Đà Nẵng',
                driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                desc: 'Kính cường lực 8mm sơn hấp nhiệt đa dạng màu sắc phong thủy, chịu nhiệt cao, bề mặt phẳng mịn không mạch vữa giúp lau chùi dầu mỡ dễ dàng.'
            },
            'phong-tam-kinh': {
                title: 'Phòng tắm kính cường lực (Cabin tắm kính)',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                desc: 'Thiết kế vách kính mở quay 90°/135°/180° hoặc cửa lùa tiết kiệm diện tích, phụ kiện Inox 304 chống gỉ sét, ngăn nước tuyệt đối giúp phòng tắm luôn khô ráo, sạch sẽ.'
            }
        };

        /* ==================== DỮ LIỆU DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== */
        const ARTICLES = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
                date: '15/11/2026',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                excerpt: 'Khí hậu ven biển Đà Nẵng có độ ẩm và hơi muối cao. Thanh nhôm Xingfa sơn tĩnh điện ngoài trời cao cấp giúp chống oxy hóa, bền màu trên 15 năm...',
                content: 'Đà Nẵng là thành phố biển có mùa nắng nóng và mùa mưa bão mạnh. Nhôm Xingfa nhập khẩu tem đỏ được xử lý bề mặt và sơn tĩnh điện tiêu chuẩn quốc tế giúp chống ăn mòn muối biển cực tốt. Kết hợp hệ gioăng EPDM kép và phụ kiện Kinlong đồng bộ, cửa kín nước tuyệt đối khi mưa bão lớn.'
            },
            {
                title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu chính hãng tem đỏ',
                date: '10/11/2026',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                excerpt: 'Hướng dẫn khách hàng kiểm tra độ dày thanh nhôm 1.4mm - 2.0mm, mã QR trên tem đỏ Quảng Đông và ánh kim sắc nét bên trong khoang nhôm...',
                content: 'Để chọn đúng nhôm Xingfa chính hãng: (1) Kiểm tra tem đỏ chữ sắc nét, có mã QR xác thực; (2) Độ dày chuẩn 2.0mm với cửa đi và 1.4mm với cửa sổ; (3) Bên trong khoang nhôm có lớp xi mạ ánh đồng chống oxy hóa; (4) Góc cửa được ép bằng máy ép góc thủy lực kín khít, không bắt vít thủ công.'
            },
            {
                title: 'Cửa nhôm Xingfa có chống trộm và cách âm hiệu quả không?',
                date: '04/11/2026',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                excerpt: 'Cấu trúc khoang rỗng kết hợp 2 đường gân gia cường và khóa đa điểm giúp cửa nhôm Xingfa tăng cường độ an toàn và giảm ồn rõ rệt...',
                content: 'Nhờ cấu tạo khoang rỗng có các đường gân so le chịu lực cùng kính cường lực 8mm - 10mm hoặc kính hộp cách âm, cửa nhôm Xingfa giảm tiếng ồn đường phố hiệu quả. Hệ khóa đa điểm và chốt âm chống cạy giúp gia chủ hoàn toàn an tâm về an ninh.'
            },
            {
                title: 'Kinh nghiệm chọn phòng tắm kính & kính ốp bếp bền đẹp cho nhà mới',
                date: '28/10/2026',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                excerpt: 'Nên chọn độ dày kính bao nhiêu ly, dùng phụ kiện Inox 304 loại nào để phòng tắm kính và kính bếp sử dụng bền bỉ theo thời gian...',
                content: 'Với phòng tắm kính, Gia Đạt Phát Window khuyến nghị dùng kính cường lực 10mm đi kèm phụ kiện Inox 304 chuẩn để tránh rỉ sét trong môi trường ẩm ướt. Với kính ốp bếp, nên chọn kính 8mm cường lực phun sơn nhiệt để chịu sốc nhiệt tốt quanh khu vực bếp nấu.'
            }
        ];

        /* ==================== RENDER SẢN PHẨM ==================== */
        function renderProducts(filterKey = 'all') {
            const grid = document.getElementById('products-grid');
            const items = filterKey === 'all' ? PRODUCTS : PRODUCTS.filter(p => p.category === filterKey);

            grid.innerHTML = items.map(p => `
                <article class="product-card">
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <span class="sale-badge-tl">${p.discount}</span>
                        <img
                            src="https://lh3.googleusercontent.com/d/${p.driveId}=w800"
                            data-drive-id="${p.driveId}"
                            alt="${p.name}"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300 cursor-pointer"
                            onclick="openProductModal(${p.id})"
                            onerror="handleDriveImgError(this, '${p.name.replace(/'/g, '')}')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2.5">
                        <div>
                            <h3 class="text-[13px] sm:text-sm md:text-[15px] font-bold text-slate-800 hover:text-[#0A4DA2] leading-snug break-words cursor-pointer" onclick="openProductModal(${p.id})">
                                ${p.name}
                            </h3>
                        </div>
                        <div class="space-y-2.5">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-sm sm:text-base font-extrabold text-[#DC2626]">${p.price}<span class="text-[11px] font-medium text-slate-500">${p.unit}</span></span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
                            </div>
                            <div class="grid grid-cols-2 gap-1.5 sm:gap-2">
                                <button type="button" onclick="openProductModal(${p.id})"
                                    class="py-2 px-2 rounded-lg border border-[#0A4DA2] text-[#0A4DA2] hover:bg-blue-50 text-[11px] sm:text-xs font-bold transition text-center">
                                    Chi tiết
                                </button>
                                <button type="button" onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}')"
                                    class="py-2 px-2 rounded-lg bg-[#0A4DA2] hover:bg-[#073675] text-white text-[11px] sm:text-xs font-bold transition text-center">
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProducts(categoryKey) {
            renderProducts(categoryKey);
            document.querySelectorAll('.filter-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-filter') === categoryKey;
                btn.classList.toggle('bg-[#0A4DA2]', isActive);
                btn.classList.toggle('text-white', isActive);
                btn.classList.toggle('bg-slate-100', !isActive);
                btn.classList.toggle('text-slate-700', !isActive);
            });
        }

        /* ==================== RENDER DỰ ÁN ĐÀ NẴNG ==================== */
        function renderProjects() {
            const grid = document.getElementById('projects-grid');
            grid.innerHTML = PROJECTS.map((proj, idx) => `
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col cursor-pointer" onclick="openProjectModal(${idx})">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/${proj.driveId}=w900"
                            data-drive-id="${proj.driveId}"
                            alt="${proj.title}"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            onerror="handleDriveImgError(this, 'Du An Da Nang')"
                        >
                    </div>
                    <div class="p-4 flex flex-col flex-1 justify-between gap-2">
                        <h3 class="text-[13px] sm:text-sm font-bold text-slate-800 hover:text-[#0A4DA2] leading-snug">
                            ${proj.title}
                        </h3>
                        <p class="text-xs text-slate-500 flex items-center gap-1.5">
                            <i class="fa-solid fa-location-dot text-[#0A4DA2]"></i>
                            ${proj.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== RENDER BÀI VIẾT TRANG CHỦ ==================== */
        function renderArticles() {
            const grid = document.getElementById('articles-grid');
            grid.innerHTML = ARTICLES.map((art, idx) => `
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md hover:border-[#0A4DA2] transition flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openArticleModal(${idx})">
                        <img
                            src="https://lh3.googleusercontent.com/d/${art.driveId}=w700"
                            data-drive-id="${art.driveId}"
                            alt="${art.title}"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            onerror="handleDriveImgError(this, 'Tin Tuc')"
                        >
                    </div>
                    <div class="p-4 flex flex-col flex-1 justify-between gap-2.5">
                        <div class="space-y-1.5">
                            <span class="text-[11px] text-slate-400 font-medium"><i class="fa-regular fa-calendar mr-1"></i>${art.date}</span>
                            <h3 class="text-sm font-bold text-slate-800 hover:text-[#0A4DA2] leading-snug cursor-pointer" onclick="openArticleModal(${idx})">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">${art.excerpt}</p>
                        </div>
                        <button type="button" onclick="openArticleModal(${idx})" class="text-xs font-bold text-[#0A4DA2] hover:underline self-start inline-flex items-center gap-1">
                            Xem thêm <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== BANNER SLIDER (2 ẢNH TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU) ==================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function syncBannerEqualHeight() {
            const slides = document.querySelectorAll('.hero-slide');
            slides.forEach(s => s.style.minHeight = 'auto');
            let maxH = 0;
            slides.forEach(s => {
                if (s.offsetHeight > maxH) maxH = s.offsetHeight;
            });
            if (maxH > 0) {
                slides.forEach(s => s.style.minHeight = maxH + 'px');
            }
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            const track = document.getElementById('hero-slider-track');
            if (track) {
                track.style.transform = `translateX(-${currentSlide * 100}%)`;
            }
            document.querySelectorAll('.hero-dot').forEach((dot, i) => {
                if (i === currentSlide) {
                    dot.classList.add('w-6', 'bg-amber-400');
                    dot.classList.remove('w-2.5', 'bg-white/50');
                } else {
                    dot.classList.remove('w-6', 'bg-amber-400');
                    dot.classList.add('w-2.5', 'bg-white/50');
                }
            });
        }

        function startAutoSlide() {
            stopAutoSlide();
            sliderTimer = setInterval(() => goToSlide(currentSlide + 1), 5000);
        }

        function stopAutoSlide() {
            if (sliderTimer) clearInterval(sliderTimer);
        }

        /* ==================== MODAL & TƯƠNG TÁC ==================== */
        function openInfoModal(title, htmlContent) {
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-body').innerHTML = htmlContent;
            const modal = document.getElementById('info-modal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeInfoModal() {
            const modal = document.getElementById('info-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        function openProductModal(id) {
            const p = PRODUCTS.find(item => item.id === id);
            if (!p) return;
            openInfoModal(p.name, `
                <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <span class="sale-badge-tl">${p.discount}</span>
                    <img src="https://lh3.googleusercontent.com/d/${p.driveId}=w1000" data-drive-id="${p.driveId}" alt="${p.name}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${p.name.replace(/'/g, '')}')">
                </div>
                <div class="flex flex-wrap items-baseline gap-3">
                    <span class="text-xl font-extrabold text-[#DC2626]">${p.price}<span class="text-xs font-medium text-slate-500">${p.unit}</span></span>
                    <span class="text-sm text-slate-400 line-through">${p.oldPrice}</span>
                </div>
                <p class="leading-relaxed text-slate-600">${p.specs}</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-2">
                    <a href="tel:0937543988" class="py-2.5 px-4 rounded-lg bg-[#DC2626] hover:bg-red-700 text-white font-bold text-center transition">
                        <i class="fa-solid fa-phone mr-1.5"></i>Gọi 0937 543 988
                    </a>
                    <button type="button" onclick="closeInfoModal(); selectProductForQuote('${p.name.replace(/'/g, "\\'")}')" class="py-2.5 px-4 rounded-lg bg-[#0A4DA2] hover:bg-[#073675] text-white font-bold transition">
                        <i class="fa-solid fa-file-invoice mr-1.5"></i>Nhận báo giá mẫu này
                    </button>
                </div>
            `);
        }

        function openCategoryInfo(key) {
            const c = CATEGORY_DETAILS[key];
            if (!c) return;
            openInfoModal(c.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="https://lh3.googleusercontent.com/d/${c.driveId}=w1000" data-drive-id="${c.driveId}" alt="${c.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'San Pham')">
                </div>
                <p class="leading-relaxed text-slate-600">${c.desc}</p>
                <div class="flex flex-wrap gap-2.5 pt-2">
                    <a href="https://zalo.me/0937543988" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 px-4 rounded-lg bg-[#0068FF] text-white font-bold text-center text-xs sm:text-sm">
                        Tư vấn qua Zalo
                    </a>
                    <button type="button" onclick="closeInfoModal(); selectProductForQuote('${c.title.replace(/'/g, "\\'")}')" class="flex-1 py-2.5 px-4 rounded-lg bg-[#0A4DA2] text-white font-bold text-xs sm:text-sm">
                        Đăng ký báo giá
                    </button>
                </div>
            `);
        }

        function openProjectModal(idx) {
            const proj = PROJECTS[idx];
            if (!proj) return;
            openInfoModal(proj.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="https://lh3.googleusercontent.com/d/${proj.driveId}=w1000" data-drive-id="${proj.driveId}" alt="${proj.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Du An')">
                </div>
                <p class="text-xs font-semibold text-[#0A4DA2]"><i class="fa-solid fa-location-dot mr-1"></i>Địa điểm: ${proj.location}</p>
                <p class="leading-relaxed text-slate-600">${proj.scope}</p>
                <div class="pt-2">
                    <a href="tel:0937543988" class="inline-flex items-center gap-2 py-2.5 px-5 rounded-lg bg-[#0A4DA2] text-white font-bold text-xs sm:text-sm">
                        <i class="fa-solid fa-phone"></i>Liên hệ tư vấn dự án: 0937 543 988
                    </a>
                </div>
            `);
        }

        function openArticleModal(idx) {
            const art = ARTICLES[idx];
            if (!art) return;
            openInfoModal(art.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="https://lh3.googleusercontent.com/d/${art.driveId}=w900" data-drive-id="${art.driveId}" alt="${art.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Tin Tuc')">
                </div>
                <p class="text-xs text-slate-400">Đăng ngày: ${art.date} — Gia Đạt Phát Window</p>
                <p class="leading-relaxed text-slate-700">${art.content}</p>
                <div class="bg-blue-50 rounded-lg p-3.5 text-xs text-slate-700 border border-blue-100">
                    Cần tư vấn kỹ thuật miễn phí tại công trình Đà Nẵng? Gọi ngay <strong>0937 543 988</strong> hoặc <strong>0773 841 136</strong>.
                </div>
            `);
        }

        function openHotlineModal() {
            openInfoModal('LIÊN HỆ HOTLINE GIA ĐẠT PHÁT WINDOW', `
                <p class="text-slate-600">Chọn số Hotline để kết nối trực tiếp với kỹ thuật viên tư vấn &amp; báo giá:</p>
                <div class="space-y-2.5">
                    <a href="tel:0937543988" class="flex items-center justify-between p-3.5 rounded-xl bg-red-50 border border-red-200 hover:bg-red-100 transition">
                        <span class="font-bold text-slate-800"><i class="fa-solid fa-phone-volume text-[#DC2626] mr-2"></i>Hotline 1 (Kinh doanh &amp; Zalo)</span>
                        <span class="font-extrabold text-[#DC2626]">0937 543 988</span>
                    </a>
                    <a href="tel:0773841136" class="flex items-center justify-between p-3.5 rounded-xl bg-blue-50 border border-blue-200 hover:bg-blue-100 transition">
                        <span class="font-bold text-slate-800"><i class="fa-solid fa-phone text-[#0A4DA2] mr-2"></i>Hotline 2 (Kỹ thuật &amp; Bảo hành)</span>
                        <span class="font-extrabold text-[#0A4DA2]">0773 841 136</span>
                    </a>
                </div>
                <p class="text-xs text-slate-500 pt-1">Địa chỉ: 114 - 116 Mai Đăng Chơn, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</p>
            `);
        }

        function selectProductForQuote(productName) {
            const noteInput = document.getElementById('q-note');
            if (noteInput) {
                noteInput.value = `Tôi muốn nhận báo giá chi tiết cho: ${productName}`;
            }
            const formEl = document.getElementById('form-bao-gia');
            if (formEl) {
                formEl.scrollIntoView({ behavior: 'smooth', block: 'center' });
                document.getElementById('q-name').focus();
            }
        }

        function showToast(message) {
            const box = document.getElementById('toast-box');
            const msg = document.getElementById('toast-message');
            msg.textContent = message;
            box.classList.remove('hidden');
            box.classList.add('flex');
            setTimeout(() => {
                box.classList.add('hidden');
                box.classList.remove('flex');
            }, 4500);
        }

        /* ==================== MOBILE DRAWER & INIT ==================== */
        document.addEventListener('DOMContentLoaded', () => {
            renderProducts('all');
            renderProjects();
            renderArticles();

            // Khởi tạo banner trượt đều 2 kích thước bằng nhau
            syncBannerEqualHeight();
            window.addEventListener('resize', syncBannerEqualHeight);
            startAutoSlide();

            document.getElementById('hero-prev').addEventListener('click', () => {
                goToSlide(currentSlide - 1);
                startAutoSlide();
            });
            document.getElementById('hero-next').addEventListener('click', () => {
                goToSlide(currentSlide + 1);
                startAutoSlide();
            });
            document.querySelectorAll('.hero-dot').forEach(dot => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
                    startAutoSlide();
                });
            });

            // Hỗ trợ vuốt cảm ứng (swipe) cho banner trên điện thoại
            const sliderEl = document.getElementById('hero-slider');
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', e => {
                touchStartX = e.changedTouches[0].screenX;
                stopAutoSlide();
            }, { passive: true });
            sliderEl.addEventListener('touchend', e => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAutoSlide();
            }, { passive: true });

            // Mobile Menu Drawer
            const drawer = document.getElementById('mobile-drawer');
            const overlay = document.getElementById('mobile-drawer-overlay');
            const openDrawer = () => {
                overlay.classList.remove('hidden');
                requestAnimationFrame(() => {
                    overlay.classList.remove('opacity-0');
                    drawer.classList.remove('-translate-x-full');
                });
                document.body.style.overflow = 'hidden';
            };
            const closeDrawer = () => {
                overlay.classList.add('opacity-0');
                drawer.classList.add('-translate-x-full');
                setTimeout(() => overlay.classList.add('hidden'), 250);
                document.body.style.overflow = '';
            };

            document.getElementById('mobile-menu-open').addEventListener('click', openDrawer);
            document.getElementById('mobile-menu-close').addEventListener('click', closeDrawer);
            overlay.addEventListener('click', closeDrawer);
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', closeDrawer);
            });

            // Mobile Accordion cho danh mục con
            document.querySelectorAll('.mobile-accordion-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const content = btn.nextElementSibling;
                    const icon = btn.querySelector('i');
                    content.classList.toggle('hidden');
                    icon.classList.toggle('rotate-180');
                });
            });

            // Đóng modal khi click nền tối
            document.getElementById('info-modal').addEventListener('click', (e) => {
                if (e.target.id === 'info-modal') closeInfoModal();
            });

            // Xử lý Form Yêu cầu & Báo giá
            document.getElementById('quote-form').addEventListener('submit', (e) => {
                e.preventDefault();
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                if (!name || !phone) return;
                showToast(`Cảm ơn ${name}! Yêu cầu báo giá của bạn đã được gửi. Gia Đạt Phát Window sẽ gọi lại qua số ${phone} trong ít phút.`);
                e.target.reset();
            });
        });

        window.addEventListener('load', syncBannerEqualHeight);
    </script>
</body>
</html>
