<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Đá Mỹ Nghệ Sáu Thăng - Điêu Khắc Đá Non Nước Đà Nẵng | sauthang.com</title>
    <meta name="description" content="Cơ sở Điêu khắc Đá mỹ nghệ Sáu Thăng (sauthang.com) tại Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng. Chuyên Tượng Phật, Tượng Công Giáo, Linh Vật Phong Thủy, Đồ Thờ Đá nguyên khối. Hotline: 0765.574.380">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://sauthang.com/">
    <meta property="og:title" content="Đá Mỹ Nghệ Sáu Thăng - Tinh Hoa Đá Non Nước Đà Nẵng | sauthang.com">
    <meta property="og:description" content="Chuyên chế tác Tượng Phật, Tượng Công Giáo, Tượng Linh Vật, Đồ Thờ Đá & Kiến Trúc Đá Tự Nhiên Nguyên Khối. Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng. ĐT: 0765.574.380">
    <meta property="og:image" id="og-logo-thumb" content="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w800">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Đá Mỹ Nghệ Sáu Thăng - sauthang.com">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Cinzel/Playfair -->
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700;800&family=Playfair+Display:wght@700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#0f4c3a', /* Màu xanh ngọc lục bảo đậm theo logo */
                            dark: '#093326',
                            light: '#166951',
                            soft: '#eaf4f0',
                            gold: '#c89b3c',    /* Màu vàng đồng hoàng gia theo logo */
                            goldLight: '#e5c168',
                            sale: '#d9381e'     /* Màu đỏ cam giảm giá chuẩn Flatsome */
                        }
                    },
                    fontFamily: {
                        sans: ['"Be Vietnam Pro"', 'sans-serif'],
                        serif: ['"Playfair Display"', 'serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền, không lệch phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Be Vietnam Pro', sans-serif;
            background-color: #f8faf9;
            color: #1f2937;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tên danh mục viết liền trên 1 hàng, không bao giờ bị gãy dòng chữ bên trong */
        .cat-nowrap {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Chuẩn Tiêu đề Section Flatsome (Title Center Line) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e5e7eb;
            padding-bottom: 8px;
        }
        .section-title-main {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0f4c3a;
            letter-spacing: 0.02em;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #c89b3c;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            hyphens: none;
            line-height: 1.4;
        }

        /* Nhãn % Giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-onsale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d9381e;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.22);
            line-height: 1;
        }
        @media (max-width: 640px) {
            .flatsome-onsale-badge {
                width: 34px;
                height: 34px;
                font-size: 10px;
                top: 6px;
                left: 6px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(15, 76, 58, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(15, 76, 58, 0); }
            100% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(15, 76, 58, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }

        /* Dropdown menu trên máy tính */
        .nav-item-has-children:hover .sub-menu-dropdown {
            display: block;
        }
    </style>
</head>
<body class="bg-[#f7f9f8] text-gray-800 antialiased">

    <!-- ==================== HEADER CHUẨN FLATSOME ==================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40 border-b border-gray-200">
        <!-- Topbar nhỏ gọn -->
        <div class="bg-brand-dark text-white text-[11px] sm:text-xs py-1.5">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-brand-gold shrink-0"></i>
                    <span class="truncate">Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</span>
                </div>
                <div class="hidden md:flex items-center gap-4 shrink-0">
                    <span><i class="fa-solid fa-globe text-brand-gold mr-1"></i>Website: <strong>sauthang.com</strong></span>
                    <span><i class="fa-solid fa-phone-volume text-brand-gold mr-1"></i>Tư vấn 24/7: <strong>0765.574.380</strong></span>
                    <a href="https://www.facebook.com/sau.thang.351" target="_blank" rel="noopener" class="hover:text-brand-goldLight transition">
                        <i class="fa-brands fa-facebook mr-1"></i>Facebook Sáu Thăng
                    </a>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm (Không để nút gọi ngay trên header tránh tràn viền) -->
        <div class="py-2.5 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-3">
                
                <!-- Nút mở Menu trên Điện thoại -->
                <button id="mobile-menu-btn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md border border-gray-200 text-brand hover:bg-brand-soft shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-gradient-to-br from-brand to-brand-dark border border-brand-gold flex items-center justify-center shadow-sm shrink-0">
                        <!-- Biểu tượng Điêu khắc Đá & Hoa Sen Non Nước bằng SVG sắc nét -->
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <!-- Đỉnh núi Ngũ Hành & Hoa Sen -->
                            <path d="M32 8L43 26H21L32 8Z" fill="#e5c168"/>
                            <path d="M18 29L27 16L36 29H18Z" fill="#c89b3c" fill-opacity="0.85"/>
                            <path d="M28 29L37 16L46 29H28Z" fill="#c89b3c" fill-opacity="0.85"/>
                            <!-- Cánh sen nâng đỡ -->
                            <path d="M12 34C18 34 23 39 32 39C41 39 46 34 52 34C48 43 40 47 32 47C24 47 16 43 12 34Z" fill="#e5c168"/>
                            <!-- Bệ đá nguyên khối khắc chữ ST -->
                            <rect x="16" y="49" width="32" height="6" rx="2" fill="#c89b3c"/>
                            <text x="32" y="37" text-anchor="middle" fill="#093326" font-size="11" font-weight="900" font-family="serif">ST</text>
                        </svg>
                    </div>
                    <div class="leading-tight">
                        <span class="block text-[10px] font-semibold uppercase tracking-widest text-brand-gold">Đá Mỹ Nghệ Non Nước</span>
                        <span class="block text-sm sm:text-base font-extrabold text-brand tracking-tight uppercase">SÁU THĂNG</span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm (Giữa Header) -->
                <div class="hidden sm:flex flex-1 max-w-xl mx-auto">
                    <div class="relative w-full flex items-center">
                        <input id="search-input-desktop" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm tượng Phật, tượng Công Giáo, kỳ lân, lư hương đá..." class="w-full pl-3.5 pr-10 py-1.5 text-xs sm:text-sm bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand focus:bg-white transition">
                        <button onclick="filterProductsBySearch(document.getElementById('search-input-desktop').value)" class="absolute right-1 top-1 bottom-1 px-3 bg-brand text-white rounded-full text-xs hover:bg-brand-light transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cam kết ngắn trên máy tính (Không dùng nút gọi ngay để tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-4 text-xs text-gray-600 shrink-0">
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-gem text-brand-gold text-sm"></i>
                        <span>Đá tự nhiên 100%</span>
                    </div>
                    <div class="flex items-center gap-1.5">
                        <i class="fa-solid fa-truck-fast text-brand-gold text-sm"></i>
                        <span>Giao lắp toàn quốc</span>
                    </div>
                </div>
            </div>

            <!-- Ô tìm kiếm gọn trên điện thoại -->
            <div class="sm:hidden flatsome-container mt-2">
                <div class="relative w-full flex items-center">
                    <input id="search-input-mobile" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm sản phẩm đá mỹ nghệ Sáu Thăng..." class="w-full pl-3 pr-9 py-1.5 text-xs bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand">
                    <button onclick="filterProductsBySearch(document.getElementById('search-input-mobile').value)" class="absolute right-1 top-1 bottom-1 px-2.5 bg-brand text-white rounded-full text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Thanh Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, tuyệt đối không gãy dòng tên danh mục -->
        <nav class="hidden lg:block bg-brand text-white border-t border-brand-light">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 xl:gap-x-2 gap-y-1 py-1 text-[12px] xl:text-[12.5px] font-semibold">
                    <li>
                        <a href="#trang-chu" onclick="filterByCategory('all')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            <i class="fa-solid fa-house mr-1.5 text-[11px] text-brand-gold"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            TƯỢNG PHẬT <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <ul class="sub-menu-dropdown hidden absolute left-0 top-full w-52 bg-white text-gray-800 shadow-lg rounded-b-md border border-gray-200 py-1.5 z-50 text-xs font-medium">
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Phật Quan Âm</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Phật Di Lặc</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Phật Thích Ca</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Phật A Di Đà</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Địa Tạng Vương Bồ Tát</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Phúc Lộc Thọ</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Chú Tiểu</a></li>
                        </ul>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            TƯỢNG CÔNG GIÁO <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <ul class="sub-menu-dropdown hidden absolute left-0 top-full w-52 bg-white text-gray-800 shadow-lg rounded-b-md border border-gray-200 py-1.5 z-50 text-xs font-medium">
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Đức Mẹ Ban Ơn</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Chúa Giêsu</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Thánh Giuse</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Thiên Thần</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">14 Chặng Đàng Thánh Giá</a></li>
                        </ul>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            TƯỢNG ĐỘNG VẬT <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <ul class="sub-menu-dropdown hidden absolute left-0 top-full w-52 bg-white text-gray-800 shadow-lg rounded-b-md border border-gray-200 py-1.5 z-50 text-xs font-medium">
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Kỳ Lân Đá</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Sư Tử Đá</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Tỳ Hưu Phong Thủy</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Tượng Voi Đá - Rồng Đá</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Chó Đá - Ngựa Đá - Cá Chép</a></li>
                        </ul>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            ĐỒ THỜ ĐÁ <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <ul class="sub-menu-dropdown hidden absolute left-0 top-full w-52 bg-white text-gray-800 shadow-lg rounded-b-md border border-gray-200 py-1.5 z-50 text-xs font-medium">
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Bàn Thờ Đá - Bàn Lễ Đá</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Lư Hương Đá Tự Nhiên</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Cây Hương Đá Ngoài Trời</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Bát Hương - Bình Hoa - Búp Sen</a></li>
                        </ul>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            ĐÁ TRANG TRÍ KIẾN TRÚC <i class="fa-solid fa-chevron-down ml-1 text-[9px] opacity-80"></i>
                        </a>
                        <ul class="sub-menu-dropdown hidden absolute left-0 top-full w-56 bg-white text-gray-800 shadow-lg rounded-b-md border border-gray-200 py-1.5 z-50 text-xs font-medium">
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Bảng Hiệu Đá Tự Nhiên</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Đài Phun Nước Bằng Đá</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Đèn Đá Sân Vườn - Nhật Bản</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Đá Kê Chân Cột Nhà Gỗ</a></li>
                            <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="block px-3.5 py-1.5 hover:bg-brand-soft hover:text-brand">Bàn Ghế Đá - Lục Bình Đá</a></li>
                        </ul>
                    </li>
                    <li>
                        <a href="#san-pham-section" onclick="filterByCategory('SP Khác')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            SP KHÁC
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac-section" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            ĐỐI TÁC
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc-section" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            BÀI VIẾT
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia-section" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-brand-dark hover:text-brand-goldLight transition">
                            BÁO GIÁ & LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Ngang Nhỏ Gọn Trên Điện Thoại (Vuốt ngang mượt, chữ nhỏ gọn không tràn viền) -->
        <div class="lg:hidden bg-brand text-white border-t border-brand-light overflow-x-auto no-scrollbar">
            <div class="flex items-center gap-1 px-2 py-1.5 text-[11px] font-semibold">
                <button onclick="filterByCategory('all')" class="cat-nowrap px-2.5 py-1 rounded bg-brand-dark text-brand-goldLight">Tất cả</button>
                <button onclick="filterByCategory('Tượng Phật')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Tượng Phật</button>
                <button onclick="filterByCategory('Tượng Công Giáo')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Tượng Công Giáo</button>
                <button onclick="filterByCategory('Tượng Động Vật')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Tượng Động Vật</button>
                <button onclick="filterByCategory('Đồ Thờ Đá')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Đồ Thờ Đá</button>
                <button onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Đá Kiến Trúc</button>
                <button onclick="filterByCategory('SP Khác')" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">SP Khác</button>
                <a href="#bao-gia-section" class="cat-nowrap px-2.5 py-1 rounded hover:bg-brand-dark">Báo Giá</a>
            </div>
        </div>
    </header>

    <!-- Drawer Menu Điện Thoại -->
    <div id="mobile-drawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/60"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
            <div class="p-3.5 bg-brand text-white flex items-center justify-between">
                <span class="font-bold text-sm uppercase tracking-wide">Danh Mục Sáu Thăng</span>
                <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded bg-brand-dark flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <ul class="divide-y divide-gray-100 text-xs font-semibold text-gray-800">
                <li><a href="#trang-chu" onclick="filterByCategory('all'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">Trang chủ sauthang.com</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">1. Tượng Phật Đá Tự Nhiên</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">2. Tượng Công Giáo</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">3. Tượng Động Vật Phong Thủy</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">4. Đồ Thờ Đá Mỹ Nghệ</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">5. Đá Trang Trí & Kiến Trúc</a></li>
                <li><a href="#san-pham-section" onclick="filterByCategory('SP Khác'); toggleMobileMenu();" class="block px-4 py-3 hover:bg-brand-soft">6. Sản Phẩm Đá Nghệ Thuật Khác</a></li>
                <li><a href="#doi-tac-section" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-brand-soft">7. Danh Mục Đối Tác</a></li>
                <li><a href="#tin-tuc-section" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-brand-soft">8. Bài Viết Phong Thủy Hữu Ích</a></li>
                <li><a href="#bao-gia-section" onclick="toggleMobileMenu()" class="block px-4 py-3 hover:bg-brand-soft">9. Yêu Cầu Báo Giá & Bản Đồ</a></li>
            </ul>
            <div class="mt-auto p-4 bg-gray-50 border-t text-xs space-y-1.5">
                <p class="font-bold text-brand">ĐÁ MỸ NGHỆ SÁU THĂNG</p>
                <p class="text-gray-600">Làng đá mỹ nghệ, P. Ngũ Hành Sơn, Đà Nẵng</p>
                <p class="font-bold text-brand-sale">Hotline/Zalo: 0765.574.380</p>
            </div>
        </div>
    </div>

    <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT (THIẾT KẾ RIÊNG MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
    <section id="trang-chu" class="py-3">
        <div class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-brand/15 bg-brand-dark">

                <!-- SLIDE 1 -->
                <div id="banner-slide-0" class="banner-slide transition-opacity duration-500 opacity-100">
                    <!-- BANNER MÁY TÍNH 1 (Kích thước cố định 350px, chữ nhỏ gọn nằm hoàn toàn bên trong) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[340px] lg:h-[360px] w-full bg-gradient-to-r from-[#07291e] via-[#0f4c3a] to-[#135c46] px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-4 space-y-2.5">
                            <p class="inline-block text-[11px] uppercase tracking-widest text-brand-goldLight font-bold border border-brand-gold/40 px-2.5 py-0.5 rounded">
                                Làng Đá Mỹ Nghệ Non Nước - Đà Nẵng | sauthang.com
                            </p>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug uppercase">
                                CƠ SỞ ĐIÊU KHẮC ĐÁ MỸ NGHỆ <span class="text-brand-goldLight">SÁU THĂNG</span>
                            </h1>
                            <p class="text-xs lg:text-sm text-gray-200 leading-relaxed max-w-xl">
                                Chuyên chế tác Tượng Phật, Tượng Công Giáo, Linh Vật Phong Thủy, Đồ Thờ Đá và Kiến Trúc Đá Tự Nhiên Nguyên Khối 100%. Giao hàng và lắp đặt tận nơi toàn quốc.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <span class="px-3 py-1.5 rounded bg-brand-gold text-brand-dark font-bold">
                                    <i class="fa-solid fa-phone mr-1"></i>Hotline: 0765.574.380
                                </span>
                                <span class="px-3 py-1.5 rounded bg-white/10 text-white border border-white/20">
                                    <i class="fa-solid fa-location-dot text-brand-goldLight mr-1"></i>P. Ngũ Hành Sơn, Tp. Đà Nẵng
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center gap-3 z-10">
                            <div class="w-1/2 h-[250px] rounded-lg overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-white">
                                <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2=w800';"
                                     alt="Tượng Đá Mỹ Nghệ Sáu Thăng 1" class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[250px] rounded-lg overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-white">
                                <img src="https://drive.google.com/thumbnail?id=12EdHqcjosKt_y6AMLWuHwH3rRck5rxse&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/12EdHqcjosKt_y6AMLWuHwH3rRck5rxse=w800';"
                                     alt="Tượng Đá Mỹ Nghệ Sáu Thăng 2" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI 1 (Thiết kế riêng cho màn hình dọc, chữ thu nhỏ nằm gọn bên trong khung) -->
                    <div class="flex md:hidden flex-col justify-between h-[230px] sm:h-[245px] w-full bg-gradient-to-b from-[#082d21] via-[#0f4c3a] to-[#0b382a] px-5 py-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-3 h-full">
                            <div class="w-[58%] space-y-1.5 pr-1">
                                <span class="inline-block text-[9px] uppercase tracking-wider text-brand-goldLight font-bold bg-white/10 px-2 py-0.5 rounded">
                                    sauthang.com • Đà Nẵng
                                </span>
                                <h2 class="text-[13px] sm:text-sm font-extrabold text-white leading-tight uppercase">
                                    ĐÁ MỸ NGHỆ <span class="text-brand-goldLight">SÁU THĂNG</span>
                                </h2>
                                <p class="text-[10.5px] text-gray-200 leading-snug">
                                    Tượng Phật, Công Giáo, Linh Vật & Đồ Thờ Đá Nguyên Khối 100%.
                                </p>
                                <div class="pt-0.5">
                                    <span class="inline-block text-[10px] font-bold bg-brand-gold text-brand-dark px-2 py-0.5 rounded">
                                        ĐT: 0765.574.380
                                    </span>
                                </div>
                            </div>
                            <div class="w-[42%] h-[165px] rounded-lg overflow-hidden border border-brand-gold shadow bg-white shrink-0">
                                <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w600"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2=w600';"
                                     alt="Sản phẩm đá Sáu Thăng" class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="text-[9.5px] text-gray-300 text-center border-t border-white/15 pt-1 truncate">
                            Đ/c: Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng tuyệt đối với Slide 1) -->
                <div id="banner-slide-1" class="banner-slide hidden transition-opacity duration-500 opacity-100">
                    <!-- BANNER MÁY TÍNH 2 (Kích thước 340px/360px bằng Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[340px] lg:h-[360px] w-full bg-gradient-to-r from-[#0b382a] via-[#125843] to-[#082b20] px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-4 space-y-2.5">
                            <p class="inline-block text-[11px] uppercase tracking-widest text-brand-goldLight font-bold border border-brand-gold/40 px-2.5 py-0.5 rounded">
                                Tinh Hoa Nghệ Nhân Điêu Khắc Non Nước
                            </p>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug uppercase">
                                CHẾ TÁC THEO YÊU CẦU <span class="text-brand-goldLight">GIÁ GỐC TẠI XƯỞNG</span>
                            </h2>
                            <p class="text-xs lg:text-sm text-gray-200 leading-relaxed max-w-xl">
                                Cam kết đá cẩm thạch, đá trắng, đá xanh Ấn Độ, đá ngọc tự nhiên nguyên khối. Bảo hành trọn đời, vận chuyển và lắp đặt an toàn trên toàn quốc & quốc tế.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <span class="px-3 py-1.5 rounded bg-brand-gold text-brand-dark font-bold">
                                    <i class="fa-solid fa-award mr-1"></i>Bảo hành trọn đời
                                </span>
                                <span class="px-3 py-1.5 rounded bg-white/10 text-white border border-white/20">
                                    <i class="fa-solid fa-phone-volume text-brand-goldLight mr-1"></i>Tư vấn miễn phí: 0765.574.380
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center gap-3 z-10">
                            <div class="w-1/2 h-[250px] rounded-lg overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-white">
                                <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX=w800';"
                                     alt="Tác phẩm điêu khắc đá Sáu Thăng 3" class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[250px] rounded-lg overflow-hidden border-2 border-brand-gold/60 shadow-lg bg-white">
                                <img src="https://drive.google.com/thumbnail?id=1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-&sz=w800"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-=w800';"
                                     alt="Tác phẩm điêu khắc đá Sáu Thăng 4" class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI 2 (Kích thước 230px/245px bằng Slide 1, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[230px] sm:h-[245px] w-full bg-gradient-to-b from-[#0b382a] via-[#135c46] to-[#08291e] px-5 py-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-3 h-full">
                            <div class="w-[58%] space-y-1.5 pr-1">
                                <span class="inline-block text-[9px] uppercase tracking-wider text-brand-goldLight font-bold bg-white/10 px-2 py-0.5 rounded">
                                    Giá gốc tại xưởng
                                </span>
                                <h2 class="text-[13px] sm:text-sm font-extrabold text-white leading-tight uppercase">
                                    ĐIÊU KHẮC ĐÁ <span class="text-brand-goldLight">THEO YÊU CẦU</span>
                                </h2>
                                <p class="text-[10.5px] text-gray-200 leading-snug">
                                    Đá tự nhiên nguyên khối, đường nét tinh xảo, giao lắp toàn quốc.
                                </p>
                                <div class="pt-0.5">
                                    <span class="inline-block text-[10px] font-bold bg-brand-gold text-brand-dark px-2 py-0.5 rounded">
                                        Zalo: 0765.574.380
                                    </span>
                                </div>
                            </div>
                            <div class="w-[42%] h-[165px] rounded-lg overflow-hidden border border-brand-gold shadow bg-white shrink-0">
                                <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w600"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX=w600';"
                                     alt="Chế tác đá Sáu Thăng" class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="text-[9.5px] text-gray-300 text-center border-t border-white/15 pt-1 truncate">
                            Bảo hành trọn đời • Nghệ nhân Làng đá Non Nước Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Nút chuyển Banner Trái/Phải & Chấm tròn -->
                <button onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 text-white hover:bg-brand-gold hover:text-brand-dark flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Banner tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 text-white hover:bg-brand-gold hover:text-brand-dark flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button id="dot-0" onclick="goToSlide(0)" class="w-5 h-1.5 rounded-full bg-brand-gold transition-all"></button>
                    <button id="dot-1" onclick="goToSlide(1)" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU & 4 CAM KẾT (GIỐNG MẪU DANGUYENCONG.COM) ==================== -->
    <section class="py-5">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl p-4 sm:p-6 shadow-sm border border-gray-200">
                <div class="text-center max-w-4xl mx-auto space-y-2 mb-5">
                    <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase">
                        Điêu Khắc Đá Mỹ Nghệ Sáu Thăng - sauthang.com
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                        Cảm ơn quý khách hàng đã đến với <strong>Đá Mỹ Nghệ Sáu Thăng</strong>! Chúng tôi chuyên cung cấp và chế tác các sản phẩm tượng đá mỹ nghệ, tượng đá Non Nước, đồ thờ đá, linh vật phong thủy và đá trang trí nội ngoại thất, kiến trúc tại <strong>Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</strong>. Quý khách cần tư vấn mẫu mã, kích thước hoặc báo giá tại xưởng xin liên hệ Hotline/Zalo: <strong class="text-brand-sale">0765.574.380</strong>.
                    </p>
                </div>

                <!-- 4 Ô Cam Kết chuẩn Icon Box Flatsome -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                    <div class="p-3 sm:p-4 rounded-lg bg-brand-soft/60 border border-brand/10 flex flex-col items-center text-center">
                        <div class="w-10 h-10 rounded-full bg-brand text-brand-goldLight flex items-center justify-center mb-2 text-base">
                            <i class="fa-solid fa-gem"></i>
                        </div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand mb-1">Sản phẩm chất lượng</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 leading-normal">Chế tác từ đá tự nhiên nguyên khối 100%, kiểm định nghiêm ngặt từng đường nét.</p>
                    </div>
                    <div class="p-3 sm:p-4 rounded-lg bg-brand-soft/60 border border-brand/10 flex flex-col items-center text-center">
                        <div class="w-10 h-10 rounded-full bg-brand text-brand-goldLight flex items-center justify-center mb-2 text-base">
                            <i class="fa-solid fa-layer-group"></i>
                        </div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand mb-1">Mẫu mã đa dạng</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 leading-normal">Đầy đủ các mẫu tượng tâm linh, phong thủy và nhận điêu khắc theo yêu cầu riêng.</p>
                    </div>
                    <div class="p-3 sm:p-4 rounded-lg bg-brand-soft/60 border border-brand/10 flex flex-col items-center text-center">
                        <div class="w-10 h-10 rounded-full bg-brand text-brand-goldLight flex items-center justify-center mb-2 text-base">
                            <i class="fa-solid fa-hammer"></i>
                        </div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand mb-1">Nghệ nhân lâu năm</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 leading-normal">Đội ngũ nghệ nhân Làng đá Non Nước giàu kinh nghiệm, thổi hồn vào từng khối đá.</p>
                    </div>
                    <div class="p-3 sm:p-4 rounded-lg bg-brand-soft/60 border border-brand/10 flex flex-col items-center text-center">
                        <div class="w-10 h-10 rounded-full bg-brand text-brand-goldLight flex items-center justify-center mb-2 text-base">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand mb-1">Tư vấn tận tâm 24/7</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 leading-normal">Hỗ trợ chọn kích thước Lỗ Ban, hướng đặt chuẩn phong thủy, giao lắp toàn quốc.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, VIẾT LIỀN 1 HÀNG, ĐẸP TRÊN PC & MOBILE) ==================== -->
    <section class="py-3">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">DANH MỤC SẢN PHẨM</h2>
                    <span class="text-[11px] sm:text-xs text-gray-500">Chọn danh mục để lọc nhanh</span>
                </div>
            </div>

            <!-- Grid Danh Mục: 2 cột trên điện thoại nhỏ, 3 cột trên tablet, 6 cột trên máy tính. Chữ danh mục nhỏ gọn viết liền trên 1 hàng -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
                <button onclick="filterByCategory('Tượng Phật')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2=w200';"
                         alt="Tượng Phật" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">Tượng Phật</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Quan Âm, Di Lặc...</div>
                    </div>
                </button>

                <button onclick="filterByCategory('Tượng Công Giáo')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=1hSmK3rXsUikb8MqBd4haZ6bgUMHO8_Pc&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1hSmK3rXsUikb8MqBd4haZ6bgUMHO8_Pc=w200';"
                         alt="Tượng Công Giáo" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">Tượng Công Giáo</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Đức Mẹ, Chúa...</div>
                    </div>
                </button>

                <button onclick="filterByCategory('Tượng Động Vật')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=1FjkJWoKEGTKrEolABBL8b3P62PREo-4h&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FjkJWoKEGTKrEolABBL8b3P62PREo-4h=w200';"
                         alt="Tượng Động Vật" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">Tượng Động Vật</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Kỳ Lân, Sư Tử...</div>
                    </div>
                </button>

                <button onclick="filterByCategory('Đồ Thờ Đá')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=104LxoMllxAVN9KbtmEHDQTfutfTvxqER&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/104LxoMllxAVN9KbtmEHDQTfutfTvxqER=w200';"
                         alt="Đồ Thờ Đá" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">Đồ Thờ Đá</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Lư hương, Bàn lễ</div>
                    </div>
                </button>

                <button onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw=w200';"
                         alt="Đá Kiến Trúc" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">Đá Kiến Trúc</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Đài nước, Đèn đá</div>
                    </div>
                </button>

                <button onclick="filterByCategory('SP Khác')" class="cat-card group bg-white hover:bg-brand hover:text-white p-2.5 sm:p-3 rounded-lg border border-gray-200 shadow-sm transition flex items-center gap-2.5 text-left">
                    <img src="https://drive.google.com/thumbnail?id=1Z8dA5CIIW54MhsZx2OZlhnrAp303nXiK&sz=w200"
                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Z8dA5CIIW54MhsZx2OZlhnrAp303nXiK=w200';"
                         alt="SP Khác" class="w-10 h-10 rounded object-cover shrink-0 border border-brand-gold/40">
                    <div class="min-w-0">
                        <div class="cat-nowrap text-[11.5px] sm:text-xs font-bold text-brand group-hover:text-white">SP Khác</div>
                        <div class="text-[10px] text-gray-500 group-hover:text-brand-goldLight">Tượng nghệ thuật</div>
                    </div>
                </button>
            </div>
        </div>
    </section>

    <!-- ==================== DANH SÁCH 16 SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, CÓ % GIẢM GIÁ GÓC TRÊN BÊN TRÁI) ==================== -->
    <section id="san-pham-section" class="py-5">
        <div class="flatsome-container">
            <!-- Thanh lọc hiển thị tất cả hoặc từng danh mục -->
            <div class="flex flex-wrap items-center justify-between gap-2 mb-4 border-b border-gray-200 pb-2">
                <div>
                    <h2 id="active-category-heading" class="text-sm sm:text-lg font-extrabold text-brand uppercase">
                        TẤT CẢ SẢN PHẨM THỰC TẾ TẠI XƯỞNG SÁU THĂNG
                    </h2>
                    <p class="text-[11px] sm:text-xs text-gray-500">Hình ảnh thực tế chế tác tại Làng đá mỹ nghệ Non Nước - Đà Nẵng</p>
                </div>
                <div class="flex flex-wrap items-center gap-1.5">
                    <button onclick="filterByCategory('all')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-brand text-white">Tất cả (16)</button>
                    <button onclick="filterByCategory('Tượng Phật')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-white border border-gray-300 text-gray-700 hover:border-brand">Tượng Phật</button>
                    <button onclick="filterByCategory('Tượng Công Giáo')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-white border border-gray-300 text-gray-700 hover:border-brand">Tượng Công Giáo</button>
                    <button onclick="filterByCategory('Tượng Động Vật')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-white border border-gray-300 text-gray-700 hover:border-brand">Tượng Động Vật</button>
                    <button onclick="filterByCategory('Đồ Thờ Đá')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-white border border-gray-300 text-gray-700 hover:border-brand">Đồ Thờ Đá</button>
                    <button onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="filter-pill cat-nowrap px-2.5 py-1 rounded text-xs font-semibold bg-white border border-gray-300 text-gray-700 hover:border-brand">Đá Kiến Trúc</button>
                </div>
            </div>

            <!-- Lưới sản phẩm: Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 4 cột (lg:grid-cols-4) chuẩn Flatsome -->
            <div id="products-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Đổ dữ liệu 16 ảnh thực tế Google Drive bằng JS bên dưới -->
            </div>

            <!-- CÁC KHỐI DANH MỤC THEO MẪU DANGUYENCONG.COM TRÊN TRANG CHỦ -->
            <div id="categorized-sections-container" class="mt-8 space-y-8">
                <!-- Được khởi tạo tự động từ dữ liệu 16 sản phẩm thực tế để dễ dàng thiết kế lại trên UX Builder -->
            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="bao-gia-section" class="py-6 bg-brand-soft/70 border-y border-brand/15">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl shadow-sm border border-gray-200 overflow-hidden">
                <div class="grid grid-cols-1 lg:grid-cols-12">
                    <!-- Cột thông tin xưởng -->
                    <div class="lg:col-span-5 bg-brand text-white p-5 sm:p-7 flex flex-col justify-between">
                        <div class="space-y-3">
                            <span class="inline-block text-[11px] uppercase tracking-widest text-brand-goldLight font-bold">
                                Báo Giá Trực Tiếp Tại Xưởng
                            </span>
                            <h2 class="text-base sm:text-xl font-extrabold uppercase leading-snug">
                                ĐĂNG KÝ NHẬN BÁO GIÁ & TƯ VẤN PHONG THỦY MIỄN PHÍ
                            </h2>
                            <p class="text-xs sm:text-sm text-gray-200 leading-relaxed">
                                Quý khách vui lòng để lại thông tin hoặc gửi mẫu yêu cầu. Nghệ nhân <strong>Đá Mỹ Nghệ Sáu Thăng</strong> sẽ liên hệ tư vấn loại đá, kích thước Lỗ Ban và báo giá chi tiết tại xưởng trong vòng 5 phút.
                            </p>
                            <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
                                <div class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-brand-goldLight mt-1 shrink-0"></i>
                                    <span><strong>Địa chỉ xưởng:</strong> Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-brand-goldLight shrink-0"></i>
                                    <span><strong>Hotline / Zalo:</strong> <a href="tel:0765574380" class="text-brand-goldLight font-bold underline">0765.574.380</a></span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-globe text-brand-goldLight shrink-0"></i>
                                    <span><strong>Website chính thức:</strong> sauthang.com</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-brands fa-facebook text-brand-goldLight shrink-0"></i>
                                    <span><strong>Facebook:</strong> <a href="https://www.facebook.com/sau.thang.351" target="_blank" rel="noopener" class="underline hover:text-brand-goldLight">facebook.com/sau.thang.351</a></span>
                                </div>
                            </div>
                        </div>
                        <div class="mt-5 pt-4 border-t border-white/15 text-[11px] text-gray-300">
                            Cam kết đá tự nhiên nguyên khối 100% - Hoàn tiền nếu phát hiện đá bột, đá ghép.
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá (Chuẩn Contact Form 7 Flatsome) -->
                    <div class="lg:col-span-7 p-5 sm:p-7">
                        <h3 class="text-sm sm:text-base font-bold text-brand uppercase mb-4">
                            FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH
                        </h3>
                        <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3.5 text-xs sm:text-sm">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block font-semibold text-gray-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="q-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block font-semibold text-gray-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="q-phone" required placeholder="Ví dụ: 0912.xxx.xxx" class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block font-semibold text-gray-700 mb-1">Danh mục sản phẩm quan tâm</label>
                                    <select id="q-category" class="w-full px-3 py-2 rounded border border-gray-300 bg-white focus:outline-none focus:border-brand">
                                        <option value="Tượng Phật Đá Tự Nhiên">Tượng Phật (Quan Âm, Di Lặc, Thích Ca...)</option>
                                        <option value="Tượng Công Giáo">Tượng Công Giáo (Đức Mẹ, Chúa Giêsu...)</option>
                                        <option value="Tượng Động Vật Phong Thủy">Tượng Động Vật (Kỳ Lân, Sư Tử, Tỳ Hưu, Rồng...)</option>
                                        <option value="Đồ Thờ Đá Mỹ Nghệ">Đồ Thờ Đá (Lư Hương, Bàn Lễ, Cây Hương...)</option>
                                        <option value="Đá Trang Trí & Kiến Trúc">Đá Trang Trí Kiến Trúc (Đài Phun Nước, Bảng Hiệu...)</option>
                                        <option value="Chế Tác Theo Bản Vẽ Riêng">Chế tác theo mẫu / kích thước yêu cầu riêng</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block font-semibold text-gray-700 mb-1">Kích thước & chất liệu dự kiến</label>
                                    <input type="text" id="q-size" placeholder="VD: Cao 1m6, đá cẩm thạch trắng..." class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Nội dung yêu cầu chi tiết</label>
                                <textarea id="q-note" rows="3" placeholder="Nhập yêu cầu về mẫu mã, địa chỉ nhận hàng để xưởng báo giá chính xác nhất..." class="w-full px-3 py-2 rounded border border-gray-300 focus:outline-none focus:border-brand"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="px-6 py-2.5 rounded bg-brand hover:bg-brand-dark text-white font-bold uppercase tracking-wide transition shadow-sm">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                                </button>
                                <span class="text-xs text-gray-500">
                                    Hoặc kết nối Zalo nhanh: <a href="https://zalo.me/0765574380" target="_blank" rel="noopener" class="font-bold text-brand underline">0765.574.380</a>
                                </span>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quote-success-msg" class="hidden p-3 rounded bg-green-50 border border-green-300 text-green-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC TIÊU BIỂU ==================== -->
    <section id="doi-tac-section" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU</h2>
                    <span class="text-[11px] sm:text-xs text-gray-500">Đồng hành cùng các công trình tâm linh & kiến trúc toàn quốc</span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3">
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">SUN</div>
                    <p class="text-xs font-bold text-gray-800">Khu Du Lịch & Resort</p>
                    <span class="text-[10px] text-gray-500">Đà Nẵng - Quảng Nam</span>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">CHÙA</div>
                    <p class="text-xs font-bold text-gray-800">Hệ Thống Tự Viện</p>
                    <span class="text-[10px] text-gray-500">Chùa & Thiền Viện</span>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">GX</div>
                    <p class="text-xs font-bold text-gray-800">Các Giáo Xứ</p>
                    <span class="text-[10px] text-gray-500">Tượng Đài Công Giáo</span>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">BĐS</div>
                    <p class="text-xs font-bold text-gray-800">Khu Đô Thị Sinh Thái</p>
                    <span class="text-[10px] text-gray-500">Cảnh quan sân vườn</span>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">LN</div>
                    <p class="text-xs font-bold text-gray-800">Làng Nghề Non Nước</p>
                    <span class="text-[10px] text-gray-500">Hiệp hội Điêu khắc Đá</span>
                </div>
                <div class="bg-white p-3.5 rounded-lg border border-gray-200 shadow-sm flex flex-col items-center text-center justify-center">
                    <div class="w-10 h-10 rounded-full bg-brand-soft text-brand flex items-center justify-center mb-1.5 font-extrabold text-xs">QT</div>
                    <p class="text-xs font-bold text-gray-800">Đối Tác Xuất Khẩu</p>
                    <span class="text-[10px] text-gray-500">Mỹ, Úc & Châu Âu</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT HỮU ÍCH TRANG CHỦ ==================== -->
    <section id="tin-tuc-section" class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">TIN TỨC - BÀI VIẾT HỮU ÍCH</h2>
                    <span class="text-[11px] sm:text-xs text-gray-500">Kiến thức phong thủy & điêu khắc đá Non Nước</span>
                </div>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-36 sm:h-44 overflow-hidden bg-gray-100">
                        <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w600"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2=w600';"
                             alt="Hướng dẫn khai quang tượng Phật" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand mb-1.5">
                                Hướng dẫn chi tiết cách thỉnh và khai quang tượng Phật đá tại gia chuẩn tâm linh
                            </h3>
                            <p class="text-[11px] text-gray-600 line-clamp-2">
                                Những lưu ý quan trọng khi lựa chọn vị trí an vị tượng Phật Quan Âm, Phật Di Lặc bằng đá tự nhiên nguyên khối mang lại bình an.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-2 inline-block text-[11px] font-bold text-brand hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-36 sm:h-44 overflow-hidden bg-gray-100">
                        <img src="https://drive.google.com/thumbnail?id=1FjkJWoKEGTKrEolABBL8b3P62PREo-4h&sz=w600"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FjkJWoKEGTKrEolABBL8b3P62PREo-4h=w600';"
                             alt="Tượng kỳ lân đá phong thủy" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand mb-1.5">
                                Tượng Kỳ Lân, Sư Tử và Tỳ Hưu đá phong thủy – Ý nghĩa trấn trạch và cách đặt
                            </h3>
                            <p class="text-[11px] text-gray-600 line-clamp-2">
                                Cách đặt cặp linh vật đá tự nhiên trước cổng cơ quan, biệt thự và nhà thờ họ giúp chiêu tài lộc và hóa giải sát khí.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-2 inline-block text-[11px] font-bold text-brand hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-36 sm:h-44 overflow-hidden bg-gray-100">
                        <img src="https://drive.google.com/thumbnail?id=104LxoMllxAVN9KbtmEHDQTfutfTvxqER&sz=w600"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/104LxoMllxAVN9KbtmEHDQTfutfTvxqER=w600';"
                             alt="Lư hương đá ngoài trời" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand mb-1.5">
                                Lư hương đá, bàn lễ đá và cây hương đá ngoài trời – Báo giá tại xưởng Sáu Thăng
                            </h3>
                            <p class="text-[11px] text-gray-600 line-clamp-2">
                                So sánh độ bền vượt trội của đồ thờ đá cẩm thạch tự nhiên Non Nước trước nắng mưa so với các vật liệu thông thường.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-2 inline-block text-[11px] font-bold text-brand hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <article class="bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="h-36 sm:h-44 overflow-hidden bg-gray-100">
                        <img src="https://drive.google.com/thumbnail?id=19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw&sz=w600"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw=w600';"
                             alt="Đài phun nước bằng đá" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-gray-800 hover:text-brand mb-1.5">
                                Đài phun nước bằng đá và đèn đá sân vườn – Điểm nhấn tinh tế cho không gian sống
                            </h3>
                            <p class="text-[11px] text-gray-600 line-clamp-2">
                                Tổng hợp các mẫu kiến trúc đá tự nhiên nguyên khối được ưa chuộng cho biệt thự sân vườn và công trình tâm linh.
                            </p>
                        </div>
                        <a href="#bao-gia-section" class="mt-2 inline-block text-[11px] font-bold text-brand hover:underline">Xem chi tiết →</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA FACEBOOK & ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section class="py-5">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main text-sm sm:text-base">KẾT NỐI FACEBOOK & BẢN ĐỒ GOOGLE MAPS</h2>
                    <span class="text-[11px] sm:text-xs text-gray-500">Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                <!-- Khối Facebook Chính Thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-gray-200 shadow-sm p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-3 pb-3 border-b border-gray-100">
                            <div class="w-12 h-12 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-2xl shrink-0">
                                <i class="fa-brands fa-facebook-f"></i>
                            </div>
                            <div class="min-w-0">
                                <h3 class="text-sm sm:text-base font-extrabold text-gray-900 truncate">Đá Mỹ Nghệ Sáu Thăng</h3>
                                <p class="text-xs text-gray-500 truncate">facebook.com/sau.thang.351</p>
                            </div>
                        </div>

                        <p class="text-xs sm:text-sm text-gray-600 my-3 leading-relaxed">
                            Theo dõi trang Facebook chính thức của <strong>Đá Mỹ Nghệ Sáu Thăng</strong> để xem video và hình ảnh hoàn thiện tượng đá thực tế mỗi ngày tại xưởng Non Nước Đà Nẵng.
                        </p>

                        <!-- Lưới 4 ảnh thực tế trên khung Facebook -->
                        <div class="grid grid-cols-4 gap-1.5 mb-3">
                            <img src="https://drive.google.com/thumbnail?id=1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2=w300';"
                                 alt="FB 1" class="w-full h-16 object-cover rounded border">
                            <img src="https://drive.google.com/thumbnail?id=12EdHqcjosKt_y6AMLWuHwH3rRck5rxse&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/12EdHqcjosKt_y6AMLWuHwH3rRck5rxse=w300';"
                                 alt="FB 2" class="w-full h-16 object-cover rounded border">
                            <img src="https://drive.google.com/thumbnail?id=1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX=w300';"
                                 alt="FB 3" class="w-full h-16 object-cover rounded border">
                            <img src="https://drive.google.com/thumbnail?id=1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-&sz=w300"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-=w300';"
                                 alt="FB 4" class="w-full h-16 object-cover rounded border">
                        </div>
                    </div>

                    <div class="flex flex-wrap items-center gap-2 pt-2 border-t border-gray-100">
                        <a href="https://www.facebook.com/sau.thang.351" target="_blank" rel="noopener" class="flex-1 text-center py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs transition">
                            <i class="fa-brands fa-facebook mr-1.5"></i>Truy Cập Facebook Sáu Thăng
                        </a>
                        <a href="https://zalo.me/0765574380" target="_blank" rel="noopener" class="py-2 px-3 rounded bg-brand text-white font-bold text-xs hover:bg-brand-dark transition">
                            Nhắn Zalo
                        </a>
                    </div>
                </div>

                <!-- Khối Bản Đồ Google Map Ngoài Trang Chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-gray-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="p-3.5 bg-gray-50 border-b border-gray-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="text-xs sm:text-sm font-bold text-brand">
                            <i class="fa-solid fa-map-location-dot text-brand-sale mr-1.5"></i>
                            Bản đồ: Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=L%C3%A0ng+%C4%91%C3%A1+m%E1%BB%B9+ngh%E1%BB%87+Non+N%C6%B0%E1%BB%9Bc+Ph%C6%B0%E1%BB%9Dng+Ng%C5%A9+H%C3%A0nh+S%C6%A1n+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-xs font-bold text-brand underline">
                            Mở chỉ đường Google Maps →
                        </a>
                    </div>
                    <div class="relative w-full h-64 sm:h-72 bg-gray-100">
                        <iframe
                            title="Bản đồ Đá Mỹ Nghệ Sáu Thăng - Làng đá mỹ nghệ Ngũ Hành Sơn Đà Nẵng"
                            src="https://maps.google.com/maps?q=L%C3%A0ng%20%C4%91%C3%A1%20m%E1%BB%B9%20ngh%E1%BB%87%20Non%20N%C6%B0%E1%BB%9Bc,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== CÂU HỎI THƯỜNG GẶP (GIỐNG MẪU DANGUYENCONG.COM) ==================== -->
    <section class="py-5">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-gray-200 p-4 sm:p-6 shadow-sm">
                <h2 class="text-sm sm:text-base font-extrabold text-brand uppercase mb-3">
                    NHỮNG CÂU HỎI VỀ ĐIÊU KHẮC ĐÁ MỸ NGHỆ SÁU THĂNG BẠN SẼ QUAN TÂM
                </h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-xs sm:text-sm">
                    <div class="p-3.5 rounded-lg bg-gray-50 border border-gray-200">
                        <h3 class="font-bold text-brand mb-1">1. Vì sao khách hàng tin tưởng chọn Đá mỹ nghệ Sáu Thăng?</h3>
                        <p class="text-gray-600 leading-relaxed">
                            Cơ sở Đá mỹ nghệ Sáu Thăng (`sauthang.com`) tọa lạc tại Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng. Mọi sản phẩm đều được điêu khắc từ đá tự nhiên nguyên khối 100%, giá gốc tại xưởng và bảo hành trọn đời.
                        </p>
                    </div>
                    <div class="p-3.5 rounded-lg bg-gray-50 border border-gray-200">
                        <h3 class="font-bold text-brand mb-1">2. Đá mỹ nghệ Sáu Thăng có nhận chế tác theo yêu cầu không?</h3>
                        <p class="text-gray-600 leading-relaxed">
                            Có. Chúng tôi nhận điêu khắc tượng Phật, tượng Công Giáo, tượng chân dung, linh vật phong thủy và đồ thờ đá theo đúng kích thước Lỗ Ban và mẫu ảnh quý khách yêu cầu. Liên hệ: <strong>0765.574.380</strong>.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="bg-brand-dark text-gray-200 pt-8 pb-6 mt-4 border-t-4 border-brand-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/10 text-xs sm:text-sm">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-2.5">
                    <h3 class="text-brand-goldLight font-extrabold uppercase text-sm tracking-wide">
                        ĐÁ MỸ NGHỆ SÁU THĂNG
                    </h3>
                    <p class="text-gray-300 leading-relaxed text-xs">
                        Chuyên điêu khắc và cung cấp tượng đá mỹ nghệ Non Nước, tượng Phật, tượng Công Giáo, linh vật đá phong thủy, đồ thờ đá nguyên khối 100%.
                    </p>
                    <ul class="space-y-1.5 text-xs">
                        <li><i class="fa-solid fa-location-dot text-brand-gold mr-2"></i><strong>Địa chỉ:</strong> Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-brand-gold mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0765574380" class="text-brand-goldLight font-bold">0765.574.380</a></li>
                        <li><i class="fa-solid fa-globe text-brand-gold mr-2"></i><strong>Website:</strong> sauthang.com</li>
                        <li><i class="fa-brands fa-facebook text-brand-gold mr-2"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/sau.thang.351" target="_blank" rel="noopener" class="underline">fb.com/sau.thang.351</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục Tượng Phật & Công Giáo -->
                <div>
                    <h3 class="text-brand-goldLight font-extrabold uppercase text-sm tracking-wide mb-2.5">
                        TƯỢNG TÂM LINH
                    </h3>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="hover:text-brand-goldLight">• Tượng Phật Quan Âm Bằng Đá</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="hover:text-brand-goldLight">• Tượng Phật Di Lặc Đá Tự Nhiên</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Phật')" class="hover:text-brand-goldLight">• Tượng Phật Thích Ca - A Di Đà</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="hover:text-brand-goldLight">• Tượng Đức Mẹ Ban Ơn Đá Cẩm Thạch</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="hover:text-brand-goldLight">• Tượng Chúa Giêsu - Thánh Giuse</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Công Giáo')" class="hover:text-brand-goldLight">• Tượng Thiên Thần Bằng Đá</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục Linh Vật & Đồ Thờ Đá -->
                <div>
                    <h3 class="text-brand-goldLight font-extrabold uppercase text-sm tracking-wide mb-2.5">
                        LINH VẬT & ĐỒ THỜ ĐÁ
                    </h3>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="hover:text-brand-goldLight">• Tượng Kỳ Lân Đá - Nghê Đá</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="hover:text-brand-goldLight">• Tượng Sư Tử - Tỳ Hưu Phong Thủy</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Tượng Động Vật')" class="hover:text-brand-goldLight">• Tượng Voi Đá - Rồng Đá - Cá Chép</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="hover:text-brand-goldLight">• Lư Hương Đá - Cây Hương Đá</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Đồ Thờ Đá')" class="hover:text-brand-goldLight">• Bàn Thờ Đá - Bàn Lễ Đá Tự Nhiên</a></li>
                        <li><a href="#san-pham-section" onclick="filterByCategory('Đá Trang Trí Kiến Trúc')" class="hover:text-brand-goldLight">• Đài Phun Nước - Bảng Hiệu Đá</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Cam kết & Hỗ trợ -->
                <div>
                    <h3 class="text-brand-goldLight font-extrabold uppercase text-sm tracking-wide mb-2.5">
                        CAM KẾT KHÁCH HÀNG
                    </h3>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li>✓ Đá tự nhiên nguyên khối 100%</li>
                        <li>✓ Chế tác tỉ mỉ bởi nghệ nhân lâu năm</li>
                        <li>✓ Giá gốc tận xưởng không qua trung gian</li>
                        <li>✓ Giao hàng và lắp đặt toàn quốc</li>
                        <li>✓ Bảo hành chất lượng đá trọn đời</li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-gray-400 text-center sm:text-left">
                <p>Copyright © 2026 <strong>Đá Mỹ Nghệ Sáu Thăng (sauthang.com)</strong>. Làng đá mỹ nghệ, Phường Ngũ Hành Sơn, Tp. Đà Nẵng.</p>
                <p>Hotline/Zalo: <strong class="text-brand-goldLight">0765.574.380</strong></p>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH PC & MOBILE ==================== -->
    <div class="fixed bottom-4 left-3 z-40 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0765574380" target="_blank" rel="noopener" aria-label="Chat Zalo 0765.574.380"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-1.5 pr-3 shadow-lg border border-white/80 transition">
            <span class="w-8 h-8 rounded-full bg-white text-[#0068ff] font-black text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-[11px] sm:text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/sau.thang.351" target="_blank" rel="noopener" aria-label="Facebook Sáu Thăng"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-1.5 pr-3 shadow-lg border border-white/80 transition">
            <span class="w-8 h-8 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-[11px] sm:text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0765574380" aria-label="Gọi 0765.574.380"
           class="pulse-btn flex items-center gap-2 bg-brand-sale hover:bg-red-700 text-white rounded-full p-1.5 pr-3.5 shadow-lg border border-white/80 transition">
            <span class="w-8 h-8 rounded-full bg-white text-brand-sale flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <span class="text-[11px] sm:text-xs font-extrabold whitespace-nowrap">0765.574.380</span>
        </a>
    </div>

    <!-- ==================== MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG ==================== -->
    <div id="product-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/70">
        <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-gray-200 relative">
            <button onclick="closeProductModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-gray-100 hover:bg-red-100 text-gray-700 hover:text-red-600 flex items-center justify-center z-10">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="grid grid-cols-1 sm:grid-cols-12">
                <div class="sm:col-span-6 bg-gray-100 h-64 sm:h-auto relative">
                    <span id="modal-badge" class="flatsome-onsale-badge">-15%</span>
                    <img id="modal-img" src="" alt="Chi tiết sản phẩm" class="w-full h-full object-cover">
                </div>
                <div class="sm:col-span-6 p-5 flex flex-col justify-between space-y-3">
                    <div class="space-y-2">
                        <span id="modal-cat" class="inline-block text-[11px] font-bold uppercase text-brand bg-brand-soft px-2.5 py-0.5 rounded"></span>
                        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-gray-900 leading-snug"></h3>
                        <div class="flex items-baseline gap-2 pt-1">
                            <del id="modal-old-price" class="text-xs text-gray-400"></del>
                            <span id="modal-new-price" class="text-base font-extrabold text-brand-sale"></span>
                        </div>
                        <ul class="text-xs text-gray-600 space-y-1 pt-2 border-t border-gray-100">
                            <li><strong>Chất liệu:</strong> Đá tự nhiên nguyên khối 100%</li>
                            <li><strong>Xuất xứ:</strong> Xưởng Đá Mỹ Nghệ Sáu Thăng - Đà Nẵng</li>
                            <li><strong>Bảo hành:</strong> Trọn đời chất lượng đá</li>
                            <li><strong>Giao hàng:</strong> Vận chuyển & lắp đặt toàn quốc</li>
                        </ul>
                    </div>
                    <div class="space-y-2 pt-2">
                        <a href="tel:0765574380" class="block w-full text-center py-2 rounded bg-brand-sale text-white font-bold text-xs uppercase hover:bg-red-700 transition">
                            <i class="fa-solid fa-phone mr-1.5"></i>Gọi Đặt Hàng: 0765.574.380
                        </a>
                        <a href="https://zalo.me/0765574380" target="_blank" rel="noopener" class="block w-full text-center py-2 rounded bg-brand text-white font-bold text-xs uppercase hover:bg-brand-dark transition">
                            Nhắn Zalo Nhận Báo Giá Chi Tiết
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ DỮ LIỆU 16 ẢNH THỰC TẾ & TƯƠNG TÁC ==================== -->
    <script>
        // Danh sách 16 ảnh sản phẩm thực tế từ 16 link Google Drive của khách hàng,
        // phân bổ chuẩn vào các danh mục của mẫu danguyencong.com kèm giá giảm & % giảm giá góc trên bên trái
        const REAL_PRODUCTS = [
            {
                id: 1,
                driveId: '1N-y5XXiHtBRzJlG5_-3BjvNmrdquT9p2',
                name: 'Tượng Phật Quan Âm Bồ Tát đứng đài sen đá cẩm thạch trắng tự nhiên nguyên khối',
                category: 'Tượng Phật',
                discount: '-15%',
                oldPrice: '20.000.000₫',
                newPrice: '17.000.000₫'
            },
            {
                id: 2,
                driveId: '12EdHqcjosKt_y6AMLWuHwH3rRck5rxse',
                name: 'Tượng Phật Di Lặc chúc phúc đá tự nhiên nguyên khối điêu khắc tinh xảo',
                category: 'Tượng Phật',
                discount: '-18%',
                oldPrice: '18.500.000₫',
                newPrice: '15.170.000₫'
            },
            {
                id: 3,
                driveId: '1_enlCf1hPn-9vF0mqmgzwsE4E35lcHIX',
                name: 'Tượng Phật Thích Ca Mâu Ni tọa đài sen đá tự nhiên Non Nước Đà Nẵng',
                category: 'Tượng Phật',
                discount: '-15%',
                oldPrice: '22.000.000₫',
                newPrice: '18.700.000₫'
            },
            {
                id: 4,
                driveId: '1Etj-_9HDOdkysFJNKetZ52YNAyEX1eu-',
                name: 'Tượng Phật A Di Đà bằng đá cẩm thạch nguyên khối chế tác tại xưởng Sáu Thăng',
                category: 'Tượng Phật',
                discount: '-20%',
                oldPrice: '24.000.000₫',
                newPrice: '19.200.000₫'
            },
            {
                id: 5,
                driveId: '1hSmK3rXsUikb8MqBd4haZ6bgUMHO8_Pc',
                name: 'Tượng Đức Mẹ Ban Ơn bằng đá cẩm thạch trắng tự nhiên nguyên khối đẹp',
                category: 'Tượng Công Giáo',
                discount: '-15%',
                oldPrice: '19.000.000₫',
                newPrice: '16.150.000₫'
            },
            {
                id: 6,
                driveId: '1wx0-xXrwEa0azmS9vzUEPLt_y8yFFnOF',
                name: 'Tượng Chúa Kito Vua dang tay đá tự nhiên nguyên khối điêu khắc sắc nét',
                category: 'Tượng Công Giáo',
                discount: '-16%',
                oldPrice: '21.500.000₫',
                newPrice: '18.060.000₫'
            },
            {
                id: 7,
                driveId: '1ISDjvu4NO6WtUm4r-MHlt7yC1RVqTx4a',
                name: 'Tượng Thánh Giuse và Thiên Thần đá cẩm thạch tự nhiên Non Nước',
                category: 'Tượng Công Giáo',
                discount: '-15%',
                oldPrice: '17.000.000₫',
                newPrice: '14.450.000₫'
            },
            {
                id: 8,
                driveId: '1FjkJWoKEGTKrEolABBL8b3P62PREo-4h',
                name: 'Cặp Tượng Kỳ Lân Nghê Việt đá phong thủy tự nhiên nguyên khối trấn trạch',
                category: 'Tượng Động Vật',
                discount: '-20%',
                oldPrice: '28.000.000₫',
                newPrice: '22.400.000₫'
            },
            {
                id: 9,
                driveId: '1A44FOPRsylr8qTPu3Nl_T3UPMYQ7oY9R',
                name: 'Cặp Tượng Sư Tử đá cẩm thạch tự nhiên nguyên khối canh cổng uy nghi',
                category: 'Tượng Động Vật',
                discount: '-15%',
                oldPrice: '30.000.000₫',
                newPrice: '25.500.000₫'
            },
            {
                id: 10,
                driveId: '1JBkClNq1t_XIu7xMUy_akyzscUyw-1Vo',
                name: 'Cặp Tượng Tỳ Hưu đá phong thủy chiêu tài lộc chạm khắc nguyên khối',
                category: 'Tượng Động Vật',
                discount: '-18%',
                oldPrice: '25.000.000₫',
                newPrice: '20.500.000₫'
            },
            {
                id: 11,
                driveId: '1Jw3kfSZSnIjn9hvejPcV3DozSAwuhoWW',
                name: 'Tượng Voi đá và Rồng đá phong thủy tự nhiên nguyên khối Non Nước',
                category: 'Tượng Động Vật',
                discount: '-15%',
                oldPrice: '26.000.000₫',
                newPrice: '22.100.000₫'
            },
            {
                id: 12,
                driveId: '104LxoMllxAVN9KbtmEHDQTfutfTvxqER',
                name: 'Lư hương đá cẩm thạch tự nhiên chạm rồng chầu mặt nguyệt nguyên khối',
                category: 'Đồ Thờ Đá',
                discount: '-15%',
                oldPrice: '16.000.000₫',
                newPrice: '13.600.000₫'
            },
            {
                id: 13,
                driveId: '1Ng1N8t7-6-O2zlMZ6KPOTo8RMBlE7PDR',
                name: 'Cây hương đá bàn thờ thiên ngoài trời đá tự nhiên nguyên khối cao cấp',
                category: 'Đồ Thờ Đá',
                discount: '-17%',
                oldPrice: '14.500.000₫',
                newPrice: '12.035.000₫'
            },
            {
                id: 14,
                driveId: '19jbWQf33X14CXxuaC3ivGwPxGW9Yldhw',
                name: 'Đài phun nước bằng đá tự nhiên nguyên khối trang trí sân vườn biệt thự',
                category: 'Đá Trang Trí Kiến Trúc',
                discount: '-20%',
                oldPrice: '35.000.000₫',
                newPrice: '28.000.000₫'
            },
            {
                id: 15,
                driveId: '1ayS6Qj6yH5YovdU7MBHBdmUpgrN0R6nE',
                name: 'Bảng hiệu đá tự nhiên và đèn đá sân vườn chạm khắc theo yêu cầu',
                category: 'Đá Trang Trí Kiến Trúc',
                discount: '-15%',
                oldPrice: '27.000.000₫',
                newPrice: '22.950.000₫'
            },
            {
                id: 16,
                driveId: '1Z8dA5CIIW54MhsZx2OZlhnrAp303nXiK',
                name: 'Tượng đá nghệ thuật điêu khắc nguyên khối tinh xảo tại xưởng Sáu Thăng',
                category: 'SP Khác',
                discount: '-15%',
                oldPrice: '19.500.000₫',
                newPrice: '16.575.000₫'
            }
        ];

        // Hàm tạo URL ảnh thực tế từ Google Drive kèm cơ chế dự phòng đa tầng
        function getDriveThumbUrl(driveId) {
            return `https://drive.google.com/thumbnail?id=${driveId}&sz=w800`;
        }
        function getDriveFallbackUrl(driveId) {
            return `https://lh3.googleusercontent.com/d/${driveId}=w800`;
        }

        // Tạo HTML cho 1 thẻ sản phẩm chuẩn Flatsome:
        // - Có % giảm giá ở góc trên bên trái
        // - Tên sản phẩm hiển thị đầy đủ (product-title-full), không cắt chữ, không tràn viền
        function createProductCardHTML(product) {
            const primaryUrl = getDriveThumbUrl(product.driveId);
            const fallbackUrl = getDriveFallbackUrl(product.driveId);

            return `
                <div class="product-small box bg-white rounded-lg border border-gray-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div class="box-image relative w-full pt-[100%] bg-gray-100 overflow-hidden cursor-pointer" onclick="openProductModal(${product.id})">
                        <!-- Badge % Giảm giá góc trên bên trái chuẩn Flatsome -->
                        <div class="flatsome-onsale-badge">${product.discount}</div>
                        <img src="${primaryUrl}"
                             onerror="this.onerror=null;this.src='${fallbackUrl}';"
                             alt="${product.name}"
                             loading="lazy"
                             class="absolute inset-0 w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between text-center">
                        <div>
                            <p class="text-[10px] uppercase tracking-wider text-gray-400 font-semibold mb-1">${product.category}</p>
                            <h3 onclick="openProductModal(${product.id})" class="product-title-full text-[12.5px] sm:text-[13.5px] font-bold text-gray-800 hover:text-brand cursor-pointer mb-2">
                                ${product.name}
                            </h3>
                        </div>
                        <div class="pt-1.5 border-t border-gray-100">
                            <div class="price-wrapper flex flex-wrap items-center justify-center gap-1.5 mb-2">
                                <del class="text-[11px] text-gray-400">${product.oldPrice}</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-brand-sale no-underline">${product.newPrice}</ins>
                            </div>
                            <button onclick="openProductModal(${product.id})" class="w-full py-1.5 px-2 rounded bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold transition">
                                Liên hệ: 0765.574.380
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        // Hiển thị danh sách sản phẩm chính
        function renderProductsGrid(list) {
            const grid = document.getElementById('products-grid');
            if (!list.length) {
                grid.innerHTML = `<div class="col-span-full bg-white p-6 rounded-lg text-center text-xs sm:text-sm text-gray-500 border">Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi <strong>0765.574.380</strong> để được gửi mẫu trực tiếp.</div>`;
                return;
            }
            grid.innerHTML = list.map(createProductCardHTML).join('');
        }

        // Hiển thị các Section từng Danh Mục giống trang chủ danguyencong.com
        function renderCategorizedSections() {
            const categoriesOrder = [
                { key: 'Tượng Phật', title: 'TƯỢNG PHẬT ĐÁ' },
                { key: 'Tượng Công Giáo', title: 'TƯỢNG CÔNG GIÁO' },
                { key: 'Tượng Động Vật', title: 'TƯỢNG ĐỘNG VẬT PHONG THỦY' },
                { key: 'Đồ Thờ Đá', title: 'ĐỒ THỜ ĐÁ MỸ NGHỆ' },
                { key: 'Đá Trang Trí Kiến Trúc', title: 'ĐÁ TRANG TRÍ & KIẾN TRÚC' }
            ];
            const container = document.getElementById('categorized-sections-container');
            container.innerHTML = categoriesOrder.map(cat => {
                const items = REAL_PRODUCTS.filter(p => p.category === cat.key);
                return `
                    <div class="pt-2">
                        <div class="section-title-container">
                            <div class="section-title-normal">
                                <h2 class="section-title-main text-sm sm:text-base">${cat.title}</h2>
                                <button onclick="filterByCategory('${cat.key}')" class="text-xs font-bold text-brand hover:underline cat-nowrap">
                                    Xem tất cả →
                                </button>
                            </div>
                        </div>
                        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                            ${items.map(createProductCardHTML).join('')}
                        </div>
                    </div>
                `;
            }).join('');
        }

        // Lọc theo danh mục
        function filterByCategory(categoryName) {
            const heading = document.getElementById('active-category-heading');
            if (categoryName === 'all') {
                heading.textContent = 'TẤT CẢ SẢN PHẨM THỰC TẾ TẠI XƯỞNG SÁU THĂNG';
                renderProductsGrid(REAL_PRODUCTS);
            } else {
                heading.textContent = 'DANH MỤC: ' + categoryName.toUpperCase();
                const filtered = REAL_PRODUCTS.filter(p => p.category === categoryName);
                renderProductsGrid(filtered);
            }
            const section = document.getElementById('san-pham-section');
            if (section) {
                section.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        // Tìm kiếm sản phẩm theo từ khóa
        function filterProductsBySearch(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            if (!q) {
                renderProductsGrid(REAL_PRODUCTS);
                return;
            }
            const filtered = REAL_PRODUCTS.filter(p =>
                p.name.toLowerCase().includes(q) || p.category.toLowerCase().includes(q)
            );
            renderProductsGrid(filtered);
        }

        // Modal xem chi tiết sản phẩm
        function openProductModal(id) {
            const product = REAL_PRODUCTS.find(p => p.id === id);
            if (!product) return;
            const modal = document.getElementById('product-modal');
            const img = document.getElementById('modal-img');
            img.src = getDriveThumbUrl(product.driveId);
            img.onerror = function() {
                this.onerror = null;
                this.src = getDriveFallbackUrl(product.driveId);
            };
            document.getElementById('modal-badge').textContent = product.discount;
            document.getElementById('modal-cat').textContent = product.category;
            document.getElementById('modal-title').textContent = product.name;
            document.getElementById('modal-old-price').textContent = product.oldPrice;
            document.getElementById('modal-new-price').textContent = product.newPrice;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('product-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Bật/tắt menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-drawer');
            drawer.classList.toggle('hidden');
        }

        // Xử lý 2 Banner tự trượt chuyên nghiệp
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function showSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            for (let i = 0; i < totalSlides; i++) {
                const el = document.getElementById(`banner-slide-${i}`);
                const dot = document.getElementById(`dot-${i}`);
                if (i === currentSlide) {
                    el.classList.remove('hidden');
                    dot.className = 'w-5 h-1.5 rounded-full bg-brand-gold transition-all';
                } else {
                    el.classList.add('hidden');
                    dot.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 4500);
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const cat = document.getElementById('q-category').value;
            const msgBox = document.getElementById('quote-success-msg');

            msgBox.innerHTML = `Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá danh mục <strong>${cat}</strong> đã được ghi nhận. Xưởng Đá Mỹ Nghệ Sáu Thăng sẽ liên hệ lại ngay qua SĐT/Zalo <strong>0765.574.380</strong>.`;
            msgBox.classList.remove('hidden');
            document.getElementById('quote-form').reset();
        }

        // Tự động tạo ảnh Thumbnail OpenGraph từ Logo của trang web khi chia sẻ link
        function generateLogoOgThumbnail() {
            try {
                const canvas = document.createElement('canvas');
                canvas.width = 600;
                canvas.height = 315;
                const ctx = canvas.getContext('2d');
                ctx.fillStyle = '#093326';
                ctx.fillRect(0, 0, 600, 315);
                ctx.strokeStyle = '#c89b3c';
                ctx.lineWidth = 6;
                ctx.strokeRect(18, 18, 564, 279);
                ctx.fillStyle = '#e5c168';
                ctx.font = 'bold 34px sans-serif';
                ctx.textAlign = 'center';
                ctx.fillText('ĐÁ MỸ NGHỆ SÁU THĂNG', 300, 135);
                ctx.fillStyle = '#ffffff';
                ctx.font = '20px sans-serif';
                ctx.fillText('Làng đá mỹ nghệ, P. Ngũ Hành Sơn, Tp. Đà Nẵng', 300, 185);
                ctx.fillStyle = '#e5c168';
                ctx.font = 'bold 22px sans-serif';
                ctx.fillText('Website: sauthang.com | ĐT: 0765.574.380', 300, 230);
                const ogMeta = document.getElementById('og-logo-thumb');
                if (ogMeta) ogMeta.setAttribute('content', canvas.toDataURL('image/png'));
            } catch (err) {}
        }

        window.onload = function() {
            renderProductsGrid(REAL_PRODUCTS);
            renderCategorizedSections();
            resetSlideTimer();
            generateLogoOgThumbnail();
        };
    </script>
</body>
</html>
