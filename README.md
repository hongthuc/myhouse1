<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Nhà Thầu Xây Dựng My House | Thiết Kế & Thi Công Trọn Gói Tại Đà Nẵng - myhouse.com</title>
    <meta name="description" content="Nhà thầu xây dựng My House chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và xây nhà trọn gói uy tín tại TP Đà Nẵng. Hotline: 0965.700.668.">

    <!-- Cấu hình ảnh Thumbnail Logo khi chia sẻ link trang web lên Zalo, Facebook -->
    <!-- Lưu ý: Khi đưa lên hosting myhouse.com, hãy đặt ảnh logo PNG tại đường dẫn /assets/logo-myhouse-thumbnail.png -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Nhà Thầu Xây Dựng My House">
    <meta property="og:url" content="https://myhouse.com/">
    <meta property="og:title" content="Nhà Thầu Xây Dựng My House - Thiết Kế & Thi Công Uy Tín Tại Đà Nẵng">
    <meta property="og:description" content="Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện nhà phố, biệt thự, căn hộ, văn phòng tại TP Đà Nẵng. Hotline: 0965.700.668.">
    <meta property="og:image" content="https://myhouse.com/assets/logo-myhouse-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Nhà Thầu Xây Dựng My House">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nhà Thầu Xây Dựng My House - myhouse.com">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói chuyên nghiệp tại TP Đà Nẵng. Hotline: 0965.700.668.">
    <meta name="twitter:image" content="https://myhouse.com/assets/logo-myhouse-thumbnail.png">

    <!-- Favicon hiển thị biểu tượng Logo My House trên tab trình duyệt -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2942'/%3E%3Cpath d='M10 34L32 14L54 34' fill='none' stroke='%23D9822B' stroke-width='5' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M18 32V50H27V38H37V50H46V32' fill='none' stroke='%23FFFFFF' stroke-width='4.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter tối ưu hiển thị tiếng Việt sắc nét -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình bảng màu thương hiệu theo Logo My House -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2942',
                            navyDark: '#0A1D30',
                            navyLight: '#1A3E63',
                            gold: '#D9822B',
                            goldDark: '#B86A1E',
                            goldLight: '#F4E6D6',
                            surface: '#F6F8FA',
                            border: '#E2E8F0',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền ngang và chống lệch phải tuyệt đối trên mọi thiết bị */
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
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chuẩn Flatsome: Chiều ngang trên máy tính đúng 95% kích thước màn hình */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .flatsome-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Đảm bảo tên danh mục trên máy tính nằm liền mạch trên 1 hàng, không rớt dòng */
        .desktop-nav-link {
            white-space: nowrap;
            flex-shrink: 0;
        }

        /* Hiệu ứng Dropdown Flatsome mượt mà */
        .nav-dropdown-parent {
            position: relative;
        }
        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: opacity 0.2s ease, transform 0.2s ease, visibility 0.2s ease;
        }
        .nav-dropdown-parent:hover .nav-dropdown-menu,
        .nav-dropdown-parent:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner trượt kích thước bằng nhau chuẩn xác */
        .hero-slider-track {
            display: flex;
            width: 100%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .hero-slide-item {
            width: 100%;
            min-width: 100%;
            flex-shrink: 0;
        }

        /* Hiệu ứng hover ảnh nhẹ nhàng kiểu Flatsome */
        .flatsome-img-zoom {
            transition: transform 0.45s ease;
        }
        .group:hover .flatsome-img-zoom {
            transform: scale(1.04);
        }

        /* Hiệu ứng sóng lan tỏa cho nút liên hệ nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 130, 43, 0.55); }
            70% { box-shadow: 0 0 0 10px rgba(217, 130, 43, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 130, 43, 0); }
        }
        .pulse-hotline {
            animation: softPulse 2.2s infinite;
        }

        /* Ẩn thanh cuộn nhưng vẫn mượt cho nhóm tab nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Đảm bảo footer không bị che bởi thanh liên hệ nổi trên mobile */
        @media (max-width: 1023px) {
            body {
                padding-bottom: 64px;
            }
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ==================== TOP BAR THÔNG TIN (KHÔNG HIỂN THỊ TÙY CHỌN UX BUILDER) ==================== -->
    <div class="bg-brand-navy text-white text-xs border-b border-white/10">
        <div class="flatsome-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-4 text-slate-200">
                <span class="inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z"/>
                        <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                    </svg>
                    <span>TP Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/>
                    </svg>
                    <span>myhouse.com</span>
                </span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 text-slate-200">
                <a href="tel:0965700668" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition-colors font-medium">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                    </svg>
                    <span>0965.700.668</span>
                </a>
                <span class="hidden md:inline text-white/30">|</span>
                <a href="mailto:lienhe@myhouse.com" class="hidden md:inline-flex items-center gap-1.5 hover:text-brand-gold transition-colors">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                    </svg>
                    <span>lienhe@myhouse.com</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==================== HEADER CHÍNH (LOGO GỌN NHỎ, MENU 1 HÀNG, KHÔNG ĐỂ NÚT GỌI NGAY) ==================== -->
    <header id="mainHeader" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-brand-border shadow-sm">
        <div class="flatsome-container h-[60px] lg:h-[66px] flex items-center justify-between gap-3">
            <!-- Logo My House chuyên nghiệp, tinh gọn -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Nhà Thầu Xây Dựng My House">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="12" fill="#0F2942"/>
                    <!-- Khung mái kiến trúc màu vàng đồng -->
                    <path d="M11 33L32 13L53 33" stroke="#D9822B" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M19 25V17H24V21" stroke="#D9822B" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                    <!-- Trụ nhà chữ M-H hiện đại -->
                    <path d="M18 33V49H25V39L32 45L39 39V49H46V33" stroke="#FFFFFF" stroke-width="3.8" stroke-linecap="round" stroke-linejoin="round"/>
                    <!-- Đường nền vững chắc -->
                    <line x1="14" y1="53" x2="50" y2="53" stroke="#D9822B" stroke-width="2.5" stroke-linecap="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors">
                        MY <span class="text-brand-gold">HOUSE</span>
                    </div>
                    <div class="text-[9px] sm:text-[9.5px] font-semibold uppercase tracking-[0.12em] text-slate-500">
                        Nhà Thầu Xây Dựng
                    </div>
                </div>
            </a>

            <!-- Menu Danh Mục Máy Tính: Viết liền trên 1 hàng, chữ nhỏ gọn, không rớt dòng -->
            <nav class="hidden lg:flex items-center justify-end gap-3 xl:gap-5 2xl:gap-6 min-w-0" aria-label="Menu chính">
                <a href="#trang-chu" class="desktop-nav-link text-[12px] xl:text-[13px] font-semibold uppercase text-brand-navy hover:text-brand-gold transition-colors py-2">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="desktop-nav-link text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                    Giới thiệu
                </a>

                <!-- Dropdown: Công trình thực tế -->
                <div class="nav-dropdown-parent">
                    <a href="#du-an-da-nang" class="desktop-nav-link inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                        <span>Công trình thực tế</span>
                        <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-brand-border py-1.5 overflow-hidden">
                            <a href="#du-an-da-nang" onclick="filterProjects('khach-san-can-ho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Biệt thự</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Nhà phố</a>
                            <a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="nav-dropdown-parent">
                    <a href="#linh-vuc" class="desktop-nav-link inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                        <span>Lĩnh vực hoạt động</span>
                        <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-brand-border py-1.5 overflow-hidden">
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('thiet-ke')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Thi công phần thô</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Thi công hoàn thiện</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Mẫu thiết kế -->
                <div class="nav-dropdown-parent">
                    <a href="#thi-cong-thuc-te" class="desktop-nav-link inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                        <span>Mẫu thiết kế</span>
                        <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute left-0 top-full pt-1 w-52 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-brand-border py-1.5 overflow-hidden">
                            <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Mẫu thiết kế nhà phố</a>
                            <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Mẫu thiết kế nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Báo giá -->
                <div class="nav-dropdown-parent">
                    <a href="#bao-gia" class="desktop-nav-link inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                        <span>Báo giá</span>
                        <svg class="w-3 h-3 opacity-70" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown-menu absolute right-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-brand-border py-1.5 overflow-hidden">
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-surface hover:text-brand-gold transition-colors">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#tin-tuc" class="desktop-nav-link text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                    Tin tức
                </a>
                <a href="#lien-he" class="desktop-nav-link text-[12px] xl:text-[13px] font-semibold uppercase text-slate-700 hover:text-brand-gold transition-colors py-2">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút Mở Menu Mobile (Flatsome Drawer Trigger) -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-navy hover:bg-brand-surface border border-brand-border transition-colors" aria-label="Mở danh mục">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>
    </header>

    <!-- ==================== MENU TRƯỢT TRÊN ĐIỆN THOẠI (FLATSOME DRAWER) ==================== -->
    <div id="mobileMenuBackdrop" class="fixed inset-0 bg-slate-900/55 z-50 hidden opacity-0 transition-opacity duration-200"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="px-4 py-3.5 bg-brand-navy text-white flex items-center justify-between">
            <div class="font-bold text-sm tracking-wide">DANH MỤC MY HOUSE</div>
            <button id="closeMobileMenuBtn" type="button" class="p-1.5 rounded-lg hover:bg-white/10 transition-colors" aria-label="Đóng menu">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
                </svg>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-[13.5px]">
            <a href="#trang-chu" class="mobile-nav-item block px-4 py-3 font-semibold text-brand-navy hover:bg-brand-surface">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-item block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-surface">Giới thiệu</a>

            <!-- Nhóm Công trình thực tế -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full px-4 py-3 flex items-center justify-between font-semibold text-slate-700 hover:bg-brand-surface">
                    <span>Công trình thực tế</span>
                    <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-brand-surface/70 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#du-an-da-nang" onclick="filterProjects('khach-san-can-ho')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Khách sạn – Căn hộ – Phòng trọ</a>
                    <a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Biệt thự</a>
                    <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Nhà phố</a>
                    <a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Văn phòng</a>
                </div>
            </div>

            <!-- Nhóm Lĩnh vực hoạt động -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full px-4 py-3 flex items-center justify-between font-semibold text-slate-700 hover:bg-brand-surface">
                    <span>Lĩnh vực hoạt động</span>
                    <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-brand-surface/70 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('thiet-ke')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Thiết kế Kiến trúc – Nội thất</a>
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Thi công phần thô</a>
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Thi công hoàn thiện</a>
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Thi công nội thất</a>
                </div>
            </div>

            <!-- Nhóm Mẫu thiết kế -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full px-4 py-3 flex items-center justify-between font-semibold text-slate-700 hover:bg-brand-surface">
                    <span>Mẫu thiết kế</span>
                    <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-brand-surface/70 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Mẫu thiết kế nhà phố</a>
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Mẫu thiết kế nội thất</a>
                </div>
            </div>

            <!-- Nhóm Báo giá -->
            <div>
                <button type="button" class="mobile-accordion-btn w-full px-4 py-3 flex items-center justify-between font-semibold text-slate-700 hover:bg-brand-surface">
                    <span>Báo giá</span>
                    <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                </button>
                <div class="hidden bg-brand-surface/70 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#bao-gia" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Báo giá thiết kế kiến trúc</a>
                    <a href="#bao-gia" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Báo giá thi công phần thô</a>
                    <a href="#bao-gia" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Báo giá thi công hoàn thiện</a>
                    <a href="#bao-gia" class="mobile-nav-item block py-2 text-slate-600 hover:text-brand-gold">Báo giá thi công trọn gói</a>
                </div>
            </div>

            <a href="#doi-tac" class="mobile-nav-item block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-surface">Đối tác</a>
            <a href="#tin-tuc" class="mobile-nav-item block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-surface">Tin tức</a>
            <a href="#lien-he" class="mobile-nav-item block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-surface">Liên hệ & Bản đồ</a>
        </div>
        <div class="p-4 bg-brand-surface border-t border-brand-border text-xs text-slate-600 space-y-1">
            <div class="font-bold text-brand-navy">Nhà Thầu Xây Dựng My House</div>
            <div>Địa chỉ: TP Đà Nẵng</div>
            <div>Hotline: <a href="tel:0965700668" class="font-bold text-brand-gold">0965.700.668</a></div>
        </div>
    </aside>

    <!-- ==================== MAIN CONTENT ==================== -->
    <main id="trang-chu" class="w-full overflow-x-hidden">

        <!-- ==================== SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU ==================== -->
        <!-- Thiết kế hình ảnh và chữ nằm gọn hoàn toàn bên trong, chữ cách xa viền ảnh, không bị thiếu chữ trên điện thoại & máy tính -->
        <section class="w-full py-3 sm:py-4 bg-brand-surface">
            <div class="flatsome-container">
                <div id="heroSlider" class="relative w-full overflow-hidden rounded-xl shadow-md bg-brand-navy">
                    <div id="heroTrack" class="hero-slider-track">

                        <!-- BANNER 1: Kích thước chuẩn đồng nhất với Banner 2 -->
                        <div class="hero-slide-item relative min-h-[360px] sm:min-h-[430px] md:min-h-[480px] lg:min-h-[520px] flex items-center">
                            <img
                                src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                                data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                onerror="handleDriveImgError(this, 'Thiết Kế Thi Công My House Đà Nẵng')"
                                alt="Nhà thầu xây dựng My House - Thiết kế và thi công trọn gói tại Đà Nẵng"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <!-- Lớp phủ chuyển sắc hài hòa theo màu logo giúp chữ nổi bật hoàn hảo -->
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navy/40"></div>

                            <!-- Vùng nội dung chữ cách xa 4 viền banner an toàn trên cả mobile và desktop -->
                            <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-14 md:py-16">
                                <div class="max-w-2xl space-y-3 sm:space-y-4">
                                    <div class="w-12 h-1 bg-brand-gold rounded-full"></div>
                                    <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight">
                                        NHÀ THẦU XÂY DỰNG MY HOUSE
                                    </h1>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed max-w-xl">
                                        Thiết kế kiến trúc – Thi công phần thô – Xây nhà trọn gói Nhà phố, Biệt thự, Căn hộ, Khách sạn chuẩn kỹ thuật và đúng tiến độ tại TP Đà Nẵng.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition-colors shadow">
                                            Nhận Báo Giá Miễn Phí
                                        </a>
                                        <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold transition-colors">
                                            Xem Dự Án Đà Nẵng
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2: Kích thước bằng đúng 100% Banner 1 -->
                        <div class="hero-slide-item relative min-h-[360px] sm:min-h-[430px] md:min-h-[480px] lg:min-h-[520px] flex items-center">
                            <img
                                src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                                data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                onerror="handleDriveImgError(this, 'Thi Công Xây Dựng Thực Tế My House')"
                                alt="Thi công xây dựng thực tế chuẩn kỹ thuật tại TP Đà Nẵng - My House"
                                class="absolute inset-0 w-full h-full object-cover object-center"
                            >
                            <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navy/40"></div>

                            <!-- Vùng nội dung chữ cách xa 4 viền banner an toàn trên cả mobile và desktop -->
                            <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-14 md:py-16">
                                <div class="max-w-2xl space-y-3 sm:space-y-4">
                                    <div class="w-12 h-1 bg-brand-gold rounded-full"></div>
                                    <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug sm:leading-tight">
                                        THI CÔNG THỰC TẾ – CAM KẾT CHẤT LƯỢNG
                                    </h2>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed max-w-xl">
                                        Đội ngũ kỹ sư trực tiếp giám sát tại công trường, vật tư chính hãng minh bạch, bảo hành kết cấu dài hạn cho mọi công trình tại Đà Nẵng.
                                    </p>
                                    <div class="pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                                        <a href="#thi-cong-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition-colors shadow">
                                            Xem Hình Ảnh Thi Công
                                        </a>
                                        <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 text-xs sm:text-sm font-semibold transition-colors">
                                            Bảng Giá Tham Khảo
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút chuyển Banner Trái / Phải đặt sát mép gọn gàng, không đè chữ -->
                    <button id="prevSlideBtn" type="button" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-brand-navyDark/65 hover:bg-brand-gold text-white flex items-center justify-center transition-colors border border-white/20" aria-label="Banner trước">
                        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                    </button>
                    <button id="nextSlideBtn" type="button" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-brand-navyDark/65 hover:bg-brand-gold text-white flex items-center justify-center transition-colors border border-white/20" aria-label="Banner tiếp theo">
                        <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                    </button>

                    <!-- Chấm chỉ báo 2 Banner -->
                    <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" data-slide-dot="0" class="slide-dot w-7 h-2 rounded-full bg-brand-gold transition-all" aria-label="Chuyển tới banner 1"></button>
                        <button type="button" data-slide-dot="1" class="slide-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Chuyển tới banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 2: DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG (THEO WEB MẪU) ==================== -->
        <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <!-- Tiêu đề chuẩn Flatsome -->
                <div class="text-center mb-7 sm:mb-9">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Lĩnh Vực Hoạt Động Tiêu Biểu
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                        Giải pháp toàn diện từ thiết kế kiến trúc, thi công phần thô đến hoàn thiện và nội thất trọn gói tại TP Đà Nẵng.
                    </p>
                </div>

                <!-- 4 Hạng mục dịch vụ chính: 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Mục 1 -->
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('thiet-ke')" class="group bg-brand-surface hover:bg-white rounded-xl p-4 sm:p-6 border border-brand-border hover:border-brand-gold/60 hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5 group-hover:bg-brand-gold group-hover:text-white transition-colors">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/>
                            </svg>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug">
                            Thiết Kế Kiến Trúc – Nội Thất
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                            Hồ sơ thiết kế 3D, kết cấu, điện nước tối ưu công năng và phong thủy.
                        </p>
                    </a>

                    <!-- Mục 2 -->
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')" class="group bg-brand-surface hover:bg-white rounded-xl p-4 sm:p-6 border border-brand-border hover:border-brand-gold/60 hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5 group-hover:bg-brand-gold group-hover:text-white transition-colors">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/>
                            </svg>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug">
                            Thi Công Phần Thô
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                            Thi công móng, khung bê tông cốt thép, xây tô chuẩn kỹ thuật bền vững.
                        </p>
                    </a>

                    <!-- Mục 3 -->
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')" class="group bg-brand-surface hover:bg-white rounded-xl p-4 sm:p-6 border border-brand-border hover:border-brand-gold/60 hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5 group-hover:bg-brand-gold group-hover:text-white transition-colors">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/>
                            </svg>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug">
                            Thi Công Hoàn Thiện Trọn Gói
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                            Ốp lát, sơn nước, chống thấm, nhôm kính, điện nước hoàn thiện chìa khóa trao tay.
                        </p>
                    </a>

                    <!-- Mục 4 -->
                    <a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="group bg-brand-surface hover:bg-white rounded-xl p-4 sm:p-6 border border-brand-border hover:border-brand-gold/60 hover:shadow-md transition-all text-center flex flex-col items-center">
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center mb-3.5 group-hover:bg-brand-gold group-hover:text-white transition-colors">
                            <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zm10 0a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zm10 0a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"/>
                            </svg>
                        </div>
                        <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug">
                            Thi Công Nội Thất
                        </h3>
                        <p class="text-[11.5px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                            Sản xuất và lắp đặt nội thất gỗ tinh tế cho nhà phố, biệt thự, căn hộ, văn phòng.
                        </p>
                    </a>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 3: GIỚI THIỆU & THẾ MẠNH CỦA MY HOUSE ==================== -->
        <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-surface border-y border-brand-border">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center">
                    <!-- Cột Giới thiệu -->
                    <div class="lg:col-span-5 space-y-4">
                        <h2 class="text-lg sm:text-2xl font-bold uppercase text-brand-navy leading-snug">
                            Nhà Thầu Xây Dựng My House – Uy Tín Tại TP Đà Nẵng
                        </h2>
                        <div class="w-14 h-1 bg-brand-gold rounded-full"></div>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            <strong>My House (myhouse.com)</strong> chuyên Tư vấn Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực TP Đà Nẵng và lân cận.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Với phương châm đặt chữ <strong>Tâm</strong> và <strong>Chất lượng</strong> lên hàng đầu, mỗi công trình do My House thi công đều đảm bảo 4 tiêu chuẩn cốt lõi: <strong>An Toàn – Chất Lượng – Đúng Tiến Độ – Chi Phí Minh Bạch</strong>.
                        </p>
                        <div class="grid grid-cols-3 gap-3 pt-2">
                            <div class="bg-white rounded-xl p-3 border border-brand-border text-center">
                                <div class="text-lg sm:text-xl font-extrabold text-brand-gold">10+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-brand-border text-center">
                                <div class="text-lg sm:text-xl font-extrabold text-brand-navy">150+</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình bàn giao</div>
                            </div>
                            <div class="bg-white rounded-xl p-3 border border-brand-border text-center">
                                <div class="text-lg sm:text-xl font-extrabold text-brand-gold">5 Năm</div>
                                <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                            </div>
                        </div>
                    </div>

                    <!-- Cột 6 Thế mạnh (bố cục 2 cột gọn gàng) -->
                    <div class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Đội ngũ KTS & Kỹ sư chuyên nghiệp</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Kiến trúc sư sáng tạo cùng kỹ sư giám sát, đội thợ xây dựng tay nghề cao.</p>
                            </div>
                        </div>

                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Giám sát tiến độ chuẩn xác</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Báo cáo hình ảnh công trường hằng ngày giúp gia chủ theo dõi dễ dàng.</p>
                            </div>
                        </div>

                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Cập nhật xu hướng hiện đại</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Ứng dụng giải pháp vật liệu mới, tối ưu ánh sáng và thông gió tự nhiên.</p>
                            </div>
                        </div>

                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Bảo hành công trình lâu dài</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Hỗ trợ kỹ thuật nhanh chóng sau bàn giao, cam kết đồng hành cùng chủ nhà.</p>
                            </div>
                        </div>

                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Dự toán minh bạch, hợp lý</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Bóc tách khối lượng rõ ràng theo từng hạng mục, hạn chế tối đa phát sinh.</p>
                            </div>
                        </div>

                        <div class="bg-white rounded-xl p-4 border border-brand-border flex items-start gap-3">
                            <div class="w-9 h-9 rounded-lg bg-brand-goldLight text-brand-gold flex items-center justify-center shrink-0 mt-0.5">
                                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"/></svg>
                            </div>
                            <div>
                                <h3 class="text-[13.5px] font-bold text-brand-navy">Tư vấn & Xin phép xây dựng 24/7</h3>
                                <p class="text-xs text-slate-600 mt-1 leading-relaxed">Hỗ trợ khảo sát thực địa, tư vấn phương án thiết kế và thủ tục pháp lý.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 4: HÌNH ẢNH THI CÔNG XÂY DỰNG THỰC TẾ (9 ẢNH GOOGLE DRIVE) ==================== -->
        <!-- Không có nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên sản phẩm rõ ràng không bị cắt chữ -->
        <section id="thi-cong-thuc-te" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-5 sm:mb-7">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Hạng Mục Thi Công Xây Dựng Thực Tế
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                        Hình ảnh thực tế quá trình thi công phần thô, kết cấu, hoàn thiện và nội thất do đội ngũ My House trực tiếp triển khai.
                    </p>
                </div>

                <!-- Danh mục lọc chữ nhỏ gọn, canh giữa đẹp mắt trên cả điện thoại & máy tính -->
                <div id="constructionTabs" class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                    <button type="button" data-cat="all" onclick="filterConstruction('all')" class="cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-brand-navy text-white border border-brand-navy">
                        Tất cả hạng mục
                    </button>
                    <button type="button" data-cat="phan-tho" onclick="filterConstruction('phan-tho')" class="cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Thi công phần thô
                    </button>
                    <button type="button" data-cat="hoan-thien" onclick="filterConstruction('hoan-thien')" class="cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Thi công hoàn thiện
                    </button>
                    <button type="button" data-cat="thiet-ke" onclick="filterConstruction('thiet-ke')" class="cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Thiết kế Kiến trúc
                    </button>
                    <button type="button" data-cat="noi-that" onclick="filterConstruction('noi-that')" class="cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Thi công nội thất
                    </button>
                </div>

                <!-- Lưới 9 ảnh thi công thực tế: 2 cột trên điện thoại, 3 cột trên máy tính -->
                <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Nội dung được render tự động từ dữ liệu 9 ảnh Google Drive -->
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 5: DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE) ==================== -->
        <!-- Không nhãn dán, chia 2 cột trên điện thoại, 4-5 cột trên máy tính, tên dự án đầy đủ không tràn/thiếu chữ -->
        <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-surface border-y border-brand-border">
            <div class="flatsome-container">
                <div class="text-center mb-5 sm:mb-7">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Các Dự Án Tiêu Biểu Tại Đà Nẵng
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                        Tổng hợp các công trình Nhà phố, Biệt thự, Khách sạn – Căn hộ và Văn phòng thực tế tại TP Đà Nẵng.
                    </p>
                </div>

                <!-- Bộ lọc danh mục dự án Đà Nẵng (theo đúng danh mục web mẫu tintruongthinh.com) -->
                <div id="projectTabs" class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                    <button type="button" data-cat="all" onclick="filterProjects('all')" class="proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-brand-navy text-white border border-brand-navy">
                        Tất cả
                    </button>
                    <button type="button" data-cat="nha-pho" onclick="filterProjects('nha-pho')" class="proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Nhà phố
                    </button>
                    <button type="button" data-cat="biet-thu" onclick="filterProjects('biet-thu')" class="proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Biệt thự
                    </button>
                    <button type="button" data-cat="khach-san-can-ho" onclick="filterProjects('khach-san-can-ho')" class="proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Khách sạn – Căn hộ
                    </button>
                    <button type="button" data-cat="van-phong" onclick="filterProjects('van-phong')" class="proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold">
                        Văn phòng
                    </button>
                </div>

                <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại, 3 cột tablet, 5 cột desktop lớn (cân đối 2 hàng x 5 cột) -->
                <div id="projectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Nội dung được render tự động từ dữ liệu 10 ảnh Google Drive -->
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 6: DANH MỤC BÁO GIÁ XÂY DỰNG (THEO WEB MẪU) ==================== -->
        <section id="bao-gia" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-7 sm:mb-9">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Bảng Báo Giá Thiết Kế & Thi Công Tại Đà Nẵng
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                        Đơn giá tham khảo minh bạch, tối ưu theo quy mô diện tích và nhu cầu thực tế của từng chủ đầu tư.
                    </p>
                </div>

                <!-- 4 Gói báo giá: 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Gói 1 -->
                    <div class="bg-brand-surface rounded-xl p-4 sm:p-5 border border-brand-border flex flex-col justify-between hover:shadow-md transition-shadow">
                        <div>
                            <h3 class="text-[13.5px] sm:text-[15px] font-bold text-brand-navy leading-snug">
                                Báo Giá Thiết Kế Kiến Trúc
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">
                                Từ 150.000đ<span class="text-xs font-medium text-slate-500"> /m²</span>
                            </div>
                            <ul class="mt-3 space-y-1.5 text-[11.5px] sm:text-xs text-slate-600">
                                <li>• Phối cảnh 3D mặt tiền & công năng</li>
                                <li>• Hồ sơ kết cấu, điện nước MEP</li>
                                <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillQuoteType('Thiết kế kiến trúc')" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition-colors">
                            Yêu cầu báo giá
                        </a>
                    </div>

                    <!-- Gói 2 -->
                    <div class="bg-brand-surface rounded-xl p-4 sm:p-5 border border-brand-border flex flex-col justify-between hover:shadow-md transition-shadow">
                        <div>
                            <h3 class="text-[13.5px] sm:text-[15px] font-bold text-brand-navy leading-snug">
                                Báo Giá Thi Công Phần Thô
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">
                                Từ 3.550.000đ<span class="text-xs font-medium text-slate-500"> /m²</span>
                            </div>
                            <ul class="mt-3 space-y-1.5 text-[11.5px] sm:text-xs text-slate-600">
                                <li>• Cung cấp vật tư thô chính hãng</li>
                                <li>• Nhân công phần thô & hoàn thiện</li>
                                <li>• Kỹ sư giám sát toàn bộ công trình</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công phần thô')" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition-colors">
                            Yêu cầu báo giá
                        </a>
                    </div>

                    <!-- Gói 3 -->
                    <div class="bg-brand-surface rounded-xl p-4 sm:p-5 border border-brand-border flex flex-col justify-between hover:shadow-md transition-shadow">
                        <div>
                            <h3 class="text-[13.5px] sm:text-[15px] font-bold text-brand-navy leading-snug">
                                Báo Giá Thi Công Hoàn Thiện
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">
                                Từ 2.400.000đ<span class="text-xs font-medium text-slate-500"> /m²</span>
                            </div>
                            <ul class="mt-3 space-y-1.5 text-[11.5px] sm:text-xs text-slate-600">
                                <li>• Gạch ốp lát, đá cầu thang, sơn nước</li>
                                <li>• Hệ cửa nhôm kính, thiết bị vệ sinh</li>
                                <li>• Hệ thống chiếu sáng & trần thạch cao</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công hoàn thiện')" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition-colors">
                            Yêu cầu báo giá
                        </a>
                    </div>

                    <!-- Gói 4 -->
                    <div class="bg-brand-navy rounded-xl p-4 sm:p-5 border border-brand-navy text-white flex flex-col justify-between hover:shadow-md transition-shadow">
                        <div>
                            <h3 class="text-[13.5px] sm:text-[15px] font-bold text-white leading-snug">
                                Báo Giá Thi Công Trọn Gói
                            </h3>
                            <div class="text-base sm:text-xl font-extrabold text-brand-gold mt-2">
                                Từ 5.950.000đ<span class="text-xs font-medium text-slate-300"> /m²</span>
                            </div>
                            <ul class="mt-3 space-y-1.5 text-[11.5px] sm:text-xs text-slate-200">
                                <li>• Miễn phí hồ sơ thiết kế & giấy phép</li>
                                <li>• Chìa khóa trao tay không phát sinh</li>
                                <li>• Bảo hành kết cấu lên đến 5 năm</li>
                            </ul>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillQuoteType('Thi công trọn gói')" class="mt-4 block text-center py-2 px-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs font-semibold transition-colors">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
        <section id="form-bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                    <!-- Cột thông tin hỗ trợ -->
                    <div class="lg:col-span-5 space-y-4">
                        <h2 class="text-xl sm:text-2xl lg:text-3xl font-bold uppercase leading-snug">
                            Đăng Ký Tư Vấn & Nhận Báo Giá Miễn Phí
                        </h2>
                        <div class="w-16 h-1 bg-brand-gold rounded-full"></div>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Quý khách vui lòng để lại thông tin công trình dự kiến. Đội ngũ kỹ sư <strong>My House</strong> sẽ liên hệ khảo sát thực tế tại TP Đà Nẵng và gửi bảng dự toán chi tiết trong vòng 24 giờ.
                        </p>
                        <div class="space-y-2.5 pt-2 text-xs sm:text-sm text-slate-200">
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-gold flex items-center justify-center shrink-0">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                                </span>
                                <span>Hotline tư vấn trực tiếp: <a href="tel:0965700668" class="font-bold text-brand-gold hover:underline">0965.700.668</a></span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-gold flex items-center justify-center shrink-0">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                                </span>
                                <span>Khu vực phục vụ: Toàn TP Đà Nẵng & lân cận</span>
                            </div>
                            <div class="flex items-center gap-2.5">
                                <span class="w-8 h-8 rounded-lg bg-white/10 text-brand-gold flex items-center justify-center shrink-0">
                                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3"/></svg>
                                </span>
                                <span>Website chính thức: <strong>myhouse.com</strong></span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form nhập liệu -->
                    <div class="lg:col-span-7">
                        <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                    <input id="customerName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                    <input id="customerPhone" type="tel" required placeholder="Ví dụ: 0965.700.668" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="projectType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                    <select id="projectType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none bg-white">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn – Căn hộ – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Thiết kế kiến trúc">Thiết kế kiến trúc</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                                        <option value="Thi công trọn gói">Thi công trọn gói</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="budgetRange" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="budgetRange" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none bg-white">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label for="projectNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (Diện tích đất, số tầng, địa điểm tại Đà Nẵng...)</label>
                                <textarea id="projectNote" rows="3" placeholder="Ví dụ: Đất 5x20m tại Hòa Xuân, dự kiến xây nhà phố 3 tầng trọn gói..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none resize-none"></textarea>
                            </div>

                            <!-- Thông báo gửi form thành công/lỗi (thay thế hoàn toàn alert) -->
                            <div id="quoteFormMessage" class="hidden rounded-lg px-4 py-3 text-xs sm:text-sm font-medium"></div>

                            <button type="submit" class="w-full py-3 px-5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm uppercase tracking-wide transition-colors shadow">
                                Gửi Yêu Cầu Tư Vấn & Báo Giá
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 8: DANH MỤC CÁC ĐỐI TÁC VẬT TƯ & XÂY DỰNG ==================== -->
        <section id="doi-tac" class="py-10 sm:py-12 bg-brand-surface border-b border-brand-border">
            <div class="flatsome-container">
                <div class="text-center mb-6 sm:mb-8">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Đối Tác Cung Ứng Vật Tư Uy Tín
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
                        My House cam kết sử dụng vật liệu xây dựng chính hãng từ các thương hiệu hàng đầu.
                    </p>
                </div>

                <!-- 8 Đối tác: 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">HÒA PHÁT</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Thép xây dựng</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">VIỆT NHẬT</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Thép Vina Kyoei</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SÔNG GIANH</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Xi măng cao cấp</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">DULUX</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">JOTUN</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Sơn chống thấm</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XINGFA</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">TOTO</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                    </div>
                    <div class="bg-white rounded-xl border border-brand-border p-4 flex flex-col items-center justify-center text-center h-20 sm:h-24 hover:border-brand-gold/60 transition-colors">
                        <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">AN CƯỜNG</span>
                        <span class="text-[10px] sm:text-[11px] text-slate-500 mt-0.5">Gỗ nội thất công nghiệp</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 9: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== -->
        <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
            <div class="flatsome-container">
                <div class="text-center mb-7 sm:mb-9">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Tin Tức & Kinh Nghiệm Xây Nhà
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2.5 max-w-2xl mx-auto">
                        Chia sẻ kiến thức kỹ thuật thi công, xu hướng thiết kế kiến trúc và cẩm nang xây nhà tiết kiệm tại Đà Nẵng.
                    </p>
                </div>

                <!-- 4 Bài viết: 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <!-- Nội dung được render tự động qua JS -->
                </div>
            </div>
        </section>

        <!-- ==================== SECTION 10: GOOGLE MAP TP ĐÀ NẴNG & FANPAGE FACEBOOK NGOÀI TRANG CHỦ ==================== -->
        <section id="lien-he" class="py-10 sm:py-14 bg-brand-surface border-t border-brand-border">
            <div class="flatsome-container">
                <div class="text-center mb-7 sm:mb-9">
                    <h2 class="text-lg sm:text-2xl lg:text-[26px] font-bold uppercase text-brand-navy tracking-tight">
                        Bản Đồ Chỉ Đường & Kết Nối Fanpage My House
                    </h2>
                    <div class="w-16 h-1 bg-brand-gold mx-auto mt-2.5 rounded-full"></div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6">
                    <!-- Cột Google Map TP Đà Nẵng (7/12 cột trên desktop) -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col">
                        <div class="px-4 py-3 border-b border-brand-border flex items-center justify-between bg-white">
                            <div class="flex items-center gap-2">
                                <svg class="w-4 h-4 text-brand-gold shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z"/>
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                                </svg>
                                <span class="text-xs sm:text-sm font-bold text-brand-navy">Bản Đồ Google Map – TP Đà Nẵng</span>
                            </div>
                            <a href="https://maps.google.com/?q=Da+Nang,+Vietnam" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-gold hover:underline">
                                Mở Google Maps
                            </a>
                        </div>
                        <div class="w-full h-[290px] sm:h-[340px] relative bg-slate-100">
                            <iframe
                                title="Bản đồ Nhà Thầu Xây Dựng My House tại TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=Da%20Nang,%20Vietnam&t=&z=13&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>

                    <!-- Cột Fanpage Facebook ngoài trang chủ (5/12 cột trên desktop) -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col justify-between">
                        <div class="px-4 py-3 border-b border-brand-border flex items-center justify-between bg-white">
                            <div class="flex items-center gap-2">
                                <svg class="w-4 h-4 text-[#1877F2] shrink-0" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/>
                                </svg>
                                <span class="text-xs sm:text-sm font-bold text-brand-navy">Fanpage Facebook Chính Thức</span>
                            </div>
                            <span class="text-[11px] text-slate-500">Cập nhật công trình</span>
                        </div>

                        <!-- Khung hiển thị Fanpage My House trực quan (luôn hiển thị đẹp không bị lỗi chặn iframe) -->
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <!-- Ảnh bìa Fanpage -->
                                <div class="relative h-32 sm:h-36 rounded-lg overflow-hidden bg-brand-navy">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                                        data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                        onerror="handleDriveImgError(this, 'Fanpage My House Đà Nẵng')"
                                        alt="Ảnh bìa Fanpage Nhà Thầu Xây Dựng My House"
                                        class="w-full h-full object-cover opacity-80"
                                    >
                                    <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/90 via-brand-navy/35 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                            <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none">
                                                <path d="M11 33L32 13L53 33" stroke="#D9822B" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
                                                <path d="M18 33V49H25V39L32 45L39 39V49H46V33" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                        </div>
                                        <div class="min-w-0">
                                            <div class="text-sm font-bold text-white leading-tight">Nhà Thầu Xây Dựng My House</div>
                                            <div class="text-[11px] text-slate-200 mt-0.5">Thiết kế & Thi công trọn gói TP Đà Nẵng</div>
                                        </div>
                                    </div>
                                </div>

                                <!-- Thông tin Fanpage -->
                                <div class="mt-3.5 space-y-2 text-xs text-slate-600">
                                    <p class="leading-relaxed">
                                        Theo dõi Fanpage <strong>Nhà Thầu Xây Dựng My House</strong> để cập nhật hình ảnh thực tế tại công trường, mẫu nhà đẹp Đà Nẵng và chương trình ưu đãi thiết kế mới nhất.
                                    </p>
                                    <div class="flex flex-wrap items-center gap-4 pt-1 text-[11.5px] font-medium text-brand-navy">
                                        <span>TP Đà Nẵng</span>
                                        <span>•</span>
                                        <span>Hotline: 0965.700.668</span>
                                        <span>•</span>
                                        <span>myhouse.com</span>
                                    </div>
                                </div>
                            </div>

                            <div class="mt-4 grid grid-cols-2 gap-2.5">
                                <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs font-semibold transition-colors">
                                    <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
                                    <span>Theo dõi Fanpage</span>
                                </a>
                                <a href="https://zalo.me/0965700668" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 py-2.5 px-3 rounded-lg bg-[#0068FF] hover:bg-[#0055D4] text-white text-xs font-semibold transition-colors">
                                    <span>Nhắn Tin Zalo</span>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==================== FOOTER CHUYÊN NGHIỆP CHUẨN FLATSOME ==================== -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 sm:pt-12 pb-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thương hiệu & Liên hệ -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none">
                            <rect width="64" height="64" rx="12" fill="#0F2942"/>
                            <path d="M11 33L32 13L53 33" stroke="#D9822B" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M18 33V49H25V39L32 45L39 39V49H46V33" stroke="#FFFFFF" stroke-width="3.8" stroke-linecap="round" stroke-linejoin="round"/>
                            <line x1="14" y1="53" x2="50" y2="53" stroke="#D9822B" stroke-width="2.5" stroke-linecap="round"/>
                        </svg>
                        <div>
                            <div class="text-base font-extrabold text-white">MY <span class="text-brand-gold">HOUSE</span></div>
                            <div class="text-[10px] uppercase tracking-wider text-slate-400">Nhà Thầu Xây Dựng</div>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-slate-300">
                        Đơn vị thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói chuyên nghiệp tại TP Đà Nẵng.
                    </p>
                    <ul class="text-xs space-y-1.5 text-slate-300">
                        <li><strong>Địa chỉ:</strong> TP Đà Nẵng</li>
                        <li><strong>Hotline:</strong> <a href="tel:0965700668" class="text-brand-gold font-semibold hover:underline">0965.700.668</a></li>
                        <li><strong>Website:</strong> myhouse.com</li>
                        <li><strong>Email:</strong> lienhe@myhouse.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div>
                    <h3 class="text-sm font-bold uppercase text-white mb-3">Lĩnh Vực Hoạt Động</h3>
                    <div class="w-10 h-0.5 bg-brand-gold mb-3"></div>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#thi-cong-thuc-te" onclick="filterConstruction('thiet-ke')" class="hover:text-brand-gold transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#thi-cong-thuc-te" onclick="filterConstruction('phan-tho')" class="hover:text-brand-gold transition-colors">Thi công phần thô</a></li>
                        <li><a href="#thi-cong-thuc-te" onclick="filterConstruction('hoan-thien')" class="hover:text-brand-gold transition-colors">Thi công hoàn thiện</a></li>
                        <li><a href="#thi-cong-thuc-te" onclick="filterConstruction('noi-that')" class="hover:text-brand-gold transition-colors">Thi công nội thất</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Công trình thực tế -->
                <div>
                    <h3 class="text-sm font-bold uppercase text-white mb-3">Công Trình Đà Nẵng</h3>
                    <div class="w-10 h-0.5 bg-brand-gold mb-3"></div>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#du-an-da-nang" onclick="filterProjects('nha-pho')" class="hover:text-brand-gold transition-colors">Thi công Nhà phố Đà Nẵng</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('biet-thu')" class="hover:text-brand-gold transition-colors">Thi công Biệt thự cao cấp</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('khach-san-can-ho')" class="hover:text-brand-gold transition-colors">Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('van-phong')" class="hover:text-brand-gold transition-colors">Thiết kế & Thi công Văn phòng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Báo giá & Hỗ trợ -->
                <div>
                    <h3 class="text-sm font-bold uppercase text-white mb-3">Báo Giá & Hỗ Trợ</h3>
                    <div class="w-10 h-0.5 bg-brand-gold mb-3"></div>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Báo giá thiết kế kiến trúc</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Báo giá thi công phần thô</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Báo giá thi công hoàn thiện</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Báo giá thi công trọn gói</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-gold transition-colors">Gửi yêu cầu khảo sát miễn phí</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright © 2026 <strong>Nhà Thầu Xây Dựng My House</strong> (myhouse.com).</div>
                <div>Thiết kế tối ưu chuẩn Flatsome UX Builder – TP Đà Nẵng.</div>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE ==================== -->
    <!-- Phiên bản Máy tính (Desktop >= 1024px): Cụm nút nổi bên góc phải dưới -->
    <div class="hidden lg:flex fixed right-5 bottom-6 z-40 flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2.5 bg-[#1877F2] hover:bg-[#1465CC] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-x-1" aria-label="Fanpage Facebook My House">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24">
                <path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/>
            </svg>
            <span class="text-xs font-bold tracking-wide">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0965700668" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2.5 bg-[#0068FF] hover:bg-[#0055D4] text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-x-1" aria-label="Chat Zalo 0965.700.668">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold tracking-wide">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0965700668" class="pulse-hotline flex items-center gap-2.5 bg-brand-gold hover:bg-brand-goldDark text-white pl-3.5 pr-4 py-2.5 rounded-full shadow-lg transition-transform hover:-translate-x-1" aria-label="Gọi Hotline 0965.700.668">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
            </svg>
            <span class="text-xs font-bold tracking-wide">0965.700.668</span>
        </a>
    </div>

    <!-- Phiên bản Điện thoại & Tablet (< 1024px): Thanh liên hệ nổi cố định dưới màn hình, dễ chạm, không tràn viền -->
    <div class="lg:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-brand-border shadow-[0_-4px_15px_rgba(15,41,66,0.12)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a href="tel:0965700668" class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-lg bg-brand-gold text-white text-xs font-bold shadow-sm">
                <svg class="w-4 h-4 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                </svg>
                <span>Hotline</span>
            </a>
            <a href="https://zalo.me/0965700668" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-lg bg-[#0068FF] text-white text-xs font-bold shadow-sm">
                <span class="w-4 h-4 rounded-full bg-white text-[#0068FF] font-extrabold text-[8px] flex items-center justify-center shrink-0">Z</span>
                <span>Zalo</span>
            </a>
            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 py-2.5 px-2 rounded-lg bg-[#1877F2] text-white text-xs font-bold shadow-sm">
                <svg class="w-4 h-4 shrink-0" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/>
                </svg>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- ==================== MODAL XEM CHI TIẾT HÌNH ẢNH / DỰ ÁN / BÀI VIẾT ==================== -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-slate-900/75 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-brand-border relative">
            <button id="closeModalBtn" type="button" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-brand-navy/85 hover:bg-brand-gold text-white flex items-center justify-center transition-colors" aria-label="Đóng cửa sổ">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
            <div id="modalImageWrap" class="w-full bg-slate-100 aspect-[16/10] overflow-hidden">
                <img id="modalImage" src="" alt="" class="w-full h-full object-cover">
            </div>
            <div class="p-5 sm:p-6 space-y-3">
                <div id="modalCategory" class="text-xs font-bold uppercase text-brand-gold"></div>
                <h3 id="modalTitle" class="text-lg sm:text-xl font-bold text-brand-navy leading-snug"></h3>
                <div id="modalMeta" class="text-xs text-slate-500"></div>
                <p id="modalDesc" class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-pre-line"></p>
                <div class="pt-3 flex flex-wrap gap-2.5 border-t border-slate-100">
                    <a href="#form-bao-gia" onclick="closeDetailModal()" class="inline-flex items-center justify-center px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs font-semibold transition-colors">
                        Nhận Báo Giá Hạng Mục Này
                    </a>
                    <a href="tel:0965700668" class="inline-flex items-center justify-center px-4 py-2 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-semibold transition-colors">
                        Gọi Tư Vấn: 0965.700.668
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ DỮ LIỆU, SLIDER, BỘ LỌC & FORM ==================== -->
    <script>
        /**
         * Cơ chế tải ảnh Google Drive an toàn với 2 tầng dự phòng
         * Tầng 1: lh3.googleusercontent.com/d/{ID}=w1000
         * Tầng 2: drive.google.com/thumbnail?id={ID}&sz=w1000
         * Tầng 3: Ảnh giữ chỗ chuẩn màu thương hiệu My House
         */
        function getDriveImageUrl(fileId) {
            return 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
        }

        function handleDriveImgError(imgEl, fallbackLabel) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const stage = imgEl.getAttribute('data-fallback-stage') || '0';
            if (stage === '0' && driveId) {
                imgEl.setAttribute('data-fallback-stage', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
            } else if (stage !== '2') {
                imgEl.setAttribute('data-fallback-stage', '2');
                const safeText = encodeURIComponent(fallbackLabel || 'My House Da Nang');
                imgEl.src = 'https://placehold.co/800x600/0F2942/FFFFFF?text=' + safeText;
            }
        }

        /**
         * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (TỪ GOOGLE DRIVE NGƯỜI DÙNG CUNG CẤP)
         * Đã phân loại theo đúng danh mục dịch vụ chuẩn mẫu tintruongthinh.com
         */
        const constructionItems = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                title: 'Thi công kết cấu móng & cốt thép dầm sàn',
                location: 'TP Đà Nẵng',
                desc: 'Triển khai gia công lắp dựng cốt thép dầm móng, sàn bê tông đúng bản vẽ kết cấu. Kiểm tra nghiêm ngặt độ dày lớp bảo vệ và khoảng cách thép trước khi đổ bê tông.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                title: 'Đổ bê tông sàn & dựng hệ cột chịu lực',
                location: 'TP Đà Nẵng',
                desc: 'Thi công cốp pha, cây chống gia cố chắc chắn và đổ bê tông thương phẩm đúng mác thiết kế, kết hợp đầm dùi và bảo dưỡng ẩm đúng tiêu chuẩn kỹ thuật.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                title: 'Xây tường bao, tường ngăn & tô trát phẳng',
                location: 'TP Đà Nẵng',
                desc: 'Thi công xây gạch nung chuẩn mạch vữa, đóng lưới chống nứt tại các vị trí tiếp giáp cột tường và đường ống kỹ thuật âm tường.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                title: 'Thi công chống thấm sân thượng & khu vực ẩm',
                location: 'TP Đà Nẵng',
                desc: 'Xử lý chống thấm chuyên sâu khu vực sàn mái, ban công và nhà vệ sinh nhiều lớp, ngâm thử nước nghiệm thu trước khi cán nền ốp lát.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                title: 'Thi công hệ thống điện nước âm tường (MEP)',
                location: 'TP Đà Nẵng',
                desc: 'Lắp đặt đường ống cấp thoát nước, ống luồn dây điện âm tường khoa học, kiểm tra áp lực đường ống và nghiệm thu bản vẽ hoàn công.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                title: 'Hoàn thiện mặt tiền & lắp đặt hệ cửa nhôm kính',
                location: 'TP Đà Nẵng',
                desc: 'Bả matit, sơn lót chống kiềm, sơn phủ ngoại thất chịu thời tiết miền Trung và lắp đặt cửa nhôm kính cách âm, kín khít.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                category: 'thiet-ke',
                categoryLabel: 'Thiết kế Kiến trúc',
                title: 'Thi công hoàn thiện trần thạch cao & chiếu sáng',
                location: 'TP Đà Nẵng',
                desc: 'Triển khai hệ khung xương trần thạch cao giật cấp hiện đại, kết hợp bố trí đèn âm trần tạo chiều sâu sang trọng cho không gian sống.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                category: 'noi-that',
                categoryLabel: 'Thi công nội thất',
                title: 'Thi công ốp lát gạch men & đá tự nhiên cầu thang',
                location: 'TP Đà Nẵng',
                desc: 'Ốp lát gạch nền khổ lớn thẳng mạch, lắp đặt đá cầu thang, lan can kính tay vịn gỗ chuẩn xác từng chi tiết hoàn thiện.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                category: 'noi-that',
                categoryLabel: 'Thi công nội thất',
                title: 'Hoàn thiện nội thất phòng khách & khu bếp hiện đại',
                location: 'TP Đà Nẵng',
                desc: 'Lắp đặt đồng bộ hệ tủ bếp, vách trang trí phòng khách và nội thất gỗ hoàn thiện chìa khóa trao tay theo đúng thiết kế 3D đã duyệt.'
            }
        ];

        /**
         * DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (TỪ GOOGLE DRIVE NGƯỜI DÙNG CUNG CẤP)
         */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Nhà phố hiện đại 3 tầng – Khu đô thị Hòa Xuân',
                location: 'Cẩm Lệ, TP Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng thiết kế mặt tiền thoáng mát, tối ưu thông gió tự nhiên và ánh sáng giếng trời, thi công trọn gói bởi My House.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Nhà phố 2 mặt tiền – Khu Nam Việt Á',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thiết kế và thi công nhà phố 2 mặt tiền phong cách hiện đại kết hợp mảng xanh ban công, tận dụng tối đa lợi thế góc phố.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Biệt thự sân vườn hiện đại – Khu Đảo Xanh',
                location: 'Hải Châu, TP Đà Nẵng',
                desc: 'Biệt thự cao cấp với không gian mở liên thông phòng khách – sân vườn, vật liệu hoàn thiện sang trọng và kết cấu bền vững.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Tòa nhà căn hộ cho thuê cao cấp – Khu An Thượng',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Thi công trọn gói tòa nhà căn hộ dịch vụ gần biển Mỹ Khê, tối ưu số lượng phòng khai thác kinh doanh và hệ thống PCCC đạt chuẩn.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Nhà phố 4 tầng kết hợp kinh doanh – Đường Nguyễn Chánh',
                location: 'Liên Chiểu, TP Đà Nẵng',
                desc: 'Giải pháp thiết kế linh hoạt tầng trệt kinh doanh và các tầng trên sinh hoạt gia đình yên tĩnh, thi công đúng tiến độ cam kết.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Biệt thự phố tân cổ điển – Khu sinh thái Hòa Quý',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Công trình biệt thự đường nét kiến trúc tinh tế, phào chỉ sắc sảo, không gian nội thất tiện nghi cho gia đình nhiều thế hệ.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Khách sạn Boutique & Căn hộ biển – Sơn Trà',
                location: 'Sơn Trà, TP Đà Nẵng',
                desc: 'Thiết kế và thi công hoàn thiện khách sạn mini phong cách nhiệt đới, mặt tiền ấn tượng thu hút du khách tại Đà Nẵng.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                title: 'Tòa nhà văn phòng kết hợp Showroom – Hải Châu',
                location: 'Hải Châu, TP Đà Nẵng',
                desc: 'Thi công tòa nhà văn phòng hiện đại với hệ vách kính cường lực lớn, không gian làm việc mở năng động tại trung tâm thành phố.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Nhà phố lệch tầng tối ưu ánh sáng – Phước Lý',
                location: 'Cẩm Lệ, TP Đà Nẵng',
                desc: 'Thiết kế lệch tầng thông minh tạo cảm giác rộng rãi cho diện tích phố tiêu chuẩn, hoàn thiện nội thất đồng bộ gọn đẹp.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                title: 'Thi công cải tạo Văn phòng & Trụ sở – Thanh Khê',
                location: 'Thanh Khê, TP Đà Nẵng',
                desc: 'Cải tạo nâng cấp toàn diện không gian làm việc, phòng họp và sảnh tiếp khách chuyên nghiệp, bàn giao nhanh đúng kế hoạch.'
            }
        ];

        /**
         * DỮ LIỆU 4 BÀI VIẾT KINH NGHIỆM XÂY DỰNG TRANG CHỦ (THEO CHỦ ĐỀ WEB MẪU)
         */
        const articlesData = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '15/11/2026',
                title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật',
                summary: 'Bảo dưỡng bê tông đúng cách trong 7 ngày đầu quyết định trực tiếp đến cường độ chịu lực và khả năng chống nứt của ngôi nhà.',
                content: 'Trong thi công xây dựng dân dụng, bê tông móng và sàn cần được giữ ẩm liên tục sau khi đổ để quá trình thủy hóa xi măng diễn ra hoàn toàn.\n\n1. Sau khi đổ 3–4 giờ, che phủ bề mặt bằng bao bố ẩm hoặc bạt nilon tránh nắng gió làm mất nước đột ngột.\n2. Tưới nước phun sương nhẹ đều đặn mỗi 3–4 tiếng trong 7 ngày đầu tiên.\n3. Tuyệt đối không đặt tải trọng vật tư nặng lên sàn khi bê tông chưa đạt cường độ quy định.\n\nTại My House, kỹ sư công trường luôn lập nhật ký bảo dưỡng chi tiết cho từng đợt đổ bê tông.'
            },
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                date: '10/11/2026',
                title: '3 nỗi lo lớn nhất khi xây nhà trọn gói và cách phòng tránh',
                summary: 'Phát sinh chi phí, chậm tiến độ và vật tư không đúng cam kết là 3 vấn đề chủ đầu tư cần lưu ý trước khi ký hợp đồng.',
                content: 'Xây dựng tổ ấm là quyết định quan trọng của mỗi gia đình. Để tránh rủi ro phát sinh, gia chủ nên chuẩn bị kỹ 3 yếu tố:\n\n1. Có hồ sơ thiết kế kiến trúc, kết cấu và điện nước hoàn chỉnh trước khi khởi công.\n2. Ký hợp đồng ghi rõ chủng loại vật tư, thương hiệu thép, xi măng, dây điện và tiến độ thanh toán từng giai đoạn.\n3. Lựa chọn nhà thầu có công trình thực tế tại Đà Nẵng để tham quan và kiểm chứng chất lượng thi công.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                date: '04/11/2026',
                title: 'Kinh nghiệm thiết kế nhà phố Đà Nẵng mát mẻ quanh năm',
                summary: 'Giải pháp giếng trời, thông gió chéo và vật liệu cách nhiệt giúp nhà phố miền Trung giảm bức xạ nắng gió hiệu quả.',
                content: 'Đặc thù khí hậu Đà Nẵng có mùa hè nắng nóng và mùa mưa bão gió mạnh. Do đó, thiết kế nhà phố cần chú trọng:\n\n• Bố trí giếng trời kết hợp cầu thang giúp đối lưu không khí nóng thoát lên trên.\n• Sử dụng hệ lam chắn nắng mặt tiền hướng Tây và cửa nhôm kính cách nhiệt kín khít.\n• Chống thấm kỹ khu vực tường hướng mưa tạt, ban công và mái sân thượng.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                date: '28/10/2026',
                title: 'Cách tính chi phí xây dựng nhà phố, căn hộ năm 2026',
                summary: 'Nắm rõ phương pháp tính diện tích móng, các tầng và mái giúp gia chủ chủ động dự trù ngân sách xây dựng chính xác.',
                content: 'Đơn giá xây dựng thường được tính theo tổng diện tích sàn quy đổi (m²):\n\n• Phần móng đơn/móng băng: tính từ 30% – 50% diện tích sàn trệt.\n• Các tầng trệt, lầu: tính 100% diện tích xây dựng.\n• Phần mái tôn/mái bê tông cốt thép: tính từ 30% – 50% diện tích.\n\nLiên hệ Hotline My House 0965.700.668 để nhận bảng dự toán bóc tách chi tiết miễn phí theo đúng kích thước lô đất của bạn.'
            }
        ];

        /**
         * RENDER 9 HẠNG MỤC THI CÔNG THỰC TẾ (KHÔNG NHÃN DÁN, TÊN RÕ RÀNG KHÔNG CẮT CHỮ)
         */
        function renderConstruction(filterCat = 'all') {
            const grid = document.getElementById('constructionGrid');
            if (!grid) return;

            const items = filterCat === 'all'
                ? constructionItems
                : constructionItems.filter(item => item.category === filterCat);

            grid.innerHTML = items.map(item => `
                <article onclick="openItemModal('construction', '${item.id}')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-brand-border hover:border-brand-gold/70 hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(item.id)}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveImgError(this, '${item.title.replace(/'/g, '')}')"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover flatsome-img-zoom"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] font-semibold text-brand-gold mb-1">${item.categoryLabel}</div>
                            <h3 class="text-[13px] sm:text-[14.5px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                                ${item.title}
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] sm:text-xs text-slate-500">
                            ${item.location}
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(cat) {
            renderConstruction(cat);
            document.querySelectorAll('.cons-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === cat;
                btn.className = isActive
                    ? 'cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-brand-navy text-white border border-brand-navy'
                    : 'cons-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold';
            });
        }

        /**
         * RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE, ĐẦY ĐỦ TÊN DỰ ÁN)
         */
        function renderProjects(filterCat = 'all') {
            const grid = document.getElementById('projectsGrid');
            if (!grid) return;

            const items = filterCat === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.category === filterCat);

            grid.innerHTML = items.map(item => `
                <article onclick="openItemModal('project', '${item.id}')" class="group cursor-pointer bg-white rounded-xl overflow-hidden border border-brand-border hover:border-brand-gold/70 hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(item.id)}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveImgError(this, '${item.title.replace(/'/g, '')}')"
                            alt="${item.title}"
                            loading="lazy"
                            class="w-full h-full object-cover flatsome-img-zoom"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] sm:text-[11px] font-semibold text-brand-gold mb-1">${item.categoryLabel}</div>
                            <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                                ${item.title}
                            </h3>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[10.5px] sm:text-[11.5px] text-slate-500">
                            ${item.location}
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(cat) {
            renderProjects(cat);
            document.querySelectorAll('.proj-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === cat;
                btn.className = isActive
                    ? 'proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-brand-navy text-white border border-brand-navy'
                    : 'proj-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold transition-colors bg-white text-slate-700 border border-brand-border hover:border-brand-gold hover:text-brand-gold';
            });
        }

        /**
         * RENDER 4 BÀI VIẾT TRANG CHỦ
         */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            if (!grid) return;

            grid.innerHTML = articlesData.map((art, idx) => `
                <article onclick="openArticleModal(${idx})" class="group cursor-pointer bg-brand-surface hover:bg-white rounded-xl overflow-hidden border border-brand-border hover:border-brand-gold/60 hover:shadow-md transition-all flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImageUrl(art.id)}"
                            data-drive-id="${art.id}"
                            onerror="handleDriveImgError(this, 'Tin Tuc My House')"
                            alt="${art.title}"
                            loading="lazy"
                            class="w-full h-full object-cover flatsome-img-zoom"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] sm:text-[11px] text-slate-400 mb-1">${art.date}</div>
                            <h3 class="text-[13px] sm:text-[14px] font-bold text-brand-navy group-hover:text-brand-gold transition-colors leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                                ${art.summary}
                            </p>
                        </div>
                        <div class="mt-3 text-xs font-semibold text-brand-gold group-hover:underline">
                            Xem chi tiết →
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /**
         * ĐIỀU KHIỂN MODAL XEM CHI TIẾT
         */
        function openItemModal(type, fileId) {
            const list = type === 'construction' ? constructionItems : danangProjects;
            const item = list.find(x => x.id === fileId);
            if (!item) return;

            const modal = document.getElementById('detailModal');
            const modalImg = document.getElementById('modalImage');
            modalImg.setAttribute('data-drive-id', item.id);
            modalImg.setAttribute('data-fallback-stage', '0');
            modalImg.onerror = function() { handleDriveImgError(this, item.title); };
            modalImg.src = getDriveImageUrl(item.id);
            modalImg.alt = item.title;

            document.getElementById('modalCategory').textContent = item.categoryLabel;
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalMeta').textContent = 'Địa điểm: ' + item.location + ' • Nhà thầu: My House (myhouse.com)';
            document.getElementById('modalDesc').textContent = item.desc;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;

            const modal = document.getElementById('detailModal');
            const modalImg = document.getElementById('modalImage');
            modalImg.setAttribute('data-drive-id', art.id);
            modalImg.setAttribute('data-fallback-stage', '0');
            modalImg.onerror = function() { handleDriveImgError(this, art.title); };
            modalImg.src = getDriveImageUrl(art.id);
            modalImg.alt = art.title;

            document.getElementById('modalCategory').textContent = 'Kinh Nghiệm Xây Nhà';
            document.getElementById('modalTitle').textContent = art.title;
            document.getElementById('modalMeta').textContent = 'Ngày đăng: ' + art.date + ' • My House Đà Nẵng';
            document.getElementById('modalDesc').textContent = art.content;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        /**
         * ĐIỀN SẴN LOẠI CÔNG TRÌNH KHI BẤM YÊU CẦU BÁO GIÁ
         */
        function prefillQuoteType(typeName) {
            const selectEl = document.getElementById('projectType');
            if (selectEl) {
                selectEl.value = typeName;
            }
        }

        /**
         * SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
         */
        (function initHeroSlider() {
            const track = document.getElementById('heroTrack');
            const slider = document.getElementById('heroSlider');
            const prevBtn = document.getElementById('prevSlideBtn');
            const nextBtn = document.getElementById('nextSlideBtn');
            const dots = document.querySelectorAll('.slide-dot');
            if (!track || !slider) return;

            let currentSlide = 0;
            const totalSlides = 2;
            let autoTimer = null;
            let touchStartX = 0;

            function goToSlide(index) {
                currentSlide = (index + totalSlides) % totalSlides;
                track.style.transform = 'translateX(-' + (currentSlide * 100) + '%)';
                dots.forEach((dot, idx) => {
                    if (idx === currentSlide) {
                        dot.className = 'slide-dot w-7 h-2 rounded-full bg-brand-gold transition-all';
                    } else {
                        dot.className = 'slide-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                    }
                });
            }

            function startAutoPlay() {
                stopAutoPlay();
                autoTimer = setInterval(() => goToSlide(currentSlide + 1), 5500);
            }

            function stopAutoPlay() {
                if (autoTimer) {
                    clearInterval(autoTimer);
                    autoTimer = null;
                }
            }

            prevBtn.addEventListener('click', () => { goToSlide(currentSlide - 1); startAutoPlay(); });
            nextBtn.addEventListener('click', () => { goToSlide(currentSlide + 1); startAutoPlay(); });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.getAttribute('data-slide-dot'), 10));
                    startAutoPlay();
                });
            });

            slider.addEventListener('mouseenter', stopAutoPlay);
            slider.addEventListener('mouseleave', startAutoPlay);

            // Hỗ trợ vuốt ngang trên điện thoại
            slider.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
                stopAutoPlay();
            }, { passive: true });

            slider.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 45) {
                    goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAutoPlay();
            }, { passive: true });

            startAutoPlay();
        })();

        /**
         * ĐIỀU KHIỂN MENU MOBILE DRAWER & ACCORDION
         */
        (function initMobileMenu() {
            const btnOpen = document.getElementById('mobileMenuBtn');
            const btnClose = document.getElementById('closeMobileMenuBtn');
            const backdrop = document.getElementById('mobileMenuBackdrop');
            const drawer = document.getElementById('mobileMenuDrawer');

            function openMenu() {
                backdrop.classList.remove('hidden');
                requestAnimationFrame(() => {
                    backdrop.classList.remove('opacity-0');
                    drawer.classList.remove('-translate-x-full');
                });
                document.body.style.overflow = 'hidden';
            }

            function closeMenu() {
                backdrop.classList.add('opacity-0');
                drawer.classList.add('-translate-x-full');
                setTimeout(() => {
                    backdrop.classList.add('hidden');
                }, 250);
                document.body.style.overflow = '';
            }

            if (btnOpen) btnOpen.addEventListener('click', openMenu);
            if (btnClose) btnClose.addEventListener('click', closeMenu);
            if (backdrop) backdrop.addEventListener('click', closeMenu);

            document.querySelectorAll('.mobile-nav-item').forEach(link => {
                link.addEventListener('click', closeMenu);
            });

            document.querySelectorAll('.mobile-accordion-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    const panel = btn.nextElementSibling;
                    const icon = btn.querySelector('svg');
                    if (panel) panel.classList.toggle('hidden');
                    if (icon) icon.classList.toggle('rotate-180');
                });
            });
        })();

        /**
         * XỬ LÝ FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (KHÔNG DÙNG ALERT)
         */
        document.getElementById('quoteForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('customerName').value.trim();
            const phone = document.getElementById('customerPhone').value.trim();
            const projectType = document.getElementById('projectType').value;
            const msgBox = document.getElementById('quoteFormMessage');

            if (!name || !phone) {
                msgBox.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                msgBox.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư My House liên hệ tư vấn.';
                msgBox.classList.remove('hidden');
                return;
            }

            msgBox.className = 'rounded-lg px-4 py-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
            msgBox.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá hạng mục "' + projectType + '" đã được gửi thành công. Kỹ sư My House sẽ liên hệ số ' + phone + ' trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0965.700.668).';
            msgBox.classList.remove('hidden');
            this.reset();
        });

        // Đóng modal khi click nút đóng hoặc vùng nền mờ
        document.getElementById('closeModalBtn').addEventListener('click', closeDetailModal);
        document.getElementById('detailModal').addEventListener('click', function(e) {
            if (e.target === this) closeDetailModal();
        });
        document.addEventListener('keydown', function(e) {
            if (e.key === 'Escape') closeDetailModal();
        });

        // Khởi tạo toàn bộ danh sách ảnh thực tế, dự án Đà Nẵng và bài viết khi tải trang
        window.addEventListener('DOMContentLoaded', function() {
            renderConstruction('all');
            renderProjects('all');
            renderArticles();
        });
    </script>
</body>
</html>
