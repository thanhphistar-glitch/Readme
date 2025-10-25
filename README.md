<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infographic: Chiến dịch 90 Ngày - Dữ liệu Đất đai</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        
        /* ----------------------------------------------------------------
        Cập nhật Style cho Dropcap (90 NGÀY) - FINAL
        ---------------------------------------------------------------- */
        .dropcap-wrapper {
            float: left;
            margin-right: 0.75rem; 
            margin-bottom: 0.25rem;
            position: relative;
            line-height: 1;
            border-radius: 0.5rem;
            padding: 0; 
            height: 6rem; 
            display: flex;
            align-items: center; 
            overflow: hidden; 
        }

        .text-90-special {
            font-size: 6rem; 
            line-height: 1;
            font-weight: 900;
            color: #1e40af; /* Xanh đậm cho 90 */
            display: block;
            position: relative; 
        }
        
        .text-ngay-special {
            /* Căn dưới đáy số 0 và căn giữa */
            position: absolute;
            bottom: 0.25rem; /* Đẩy xuống đáy 90 */
            left: 75%; /* Điều chỉnh thủ công để căn giữa số 0 */
            transform: translateX(-50%); /* Căn giữa theo trục X */
            font-size: 1.2rem; 
            font-weight: 900;
            color: white; 
            background-color: #d97706; /* Cam đậm cho NGÀY */
            padding: 0 0.3rem;
            border-radius: 0.2rem;
            z-index: 10;
            white-space: nowrap; 
            box-shadow: 0 1px 3px rgba(0,0,0,0.3);
            line-height: 1.2; 
        }

        /* Tiêu đề chính bên cạnh dropcap */
        .title-content-dropcap {
            font-size: 1.6rem; /* Kích thước chữ "LÀM GIÀU..." */
            font-weight: 900; 
            color: #1D4ED8;
            text-align: center;
            line-height: 1.3;
            display: block; 
            padding-top: 0.5rem; 
        }
        /* ---------------------------------------------------------------- */

        .section-card {
            background-color: white;
            border-radius: 0.75rem;
            padding: 0.5rem; 
            margin-bottom: 0.5rem; 
            box-shadow: 0 4px 8px -2px rgba(0, 0, 0, 0.1);
        }
        .section-title {
            font-size: 1.3rem; 
            font-weight: 800;
            color: #1D4ED8;
            margin-bottom: 0.5rem; 
            border-bottom: 2px solid #BFDBFE;
            padding-bottom: 0.3rem; 
            display: flex;
            align-items: center;
            gap: 0.4rem; 
        }
        /* Các điều chỉnh font cho tiêu đề và nội dung khác */
        header h2 {
            font-size: 1rem;
        }
        .bg-blue-50 p {
            font-size: 0.8rem;
        }
        main {
            padding: 0.5rem; 
        }
        footer h4 {
            font-size: 1.25rem;
        }

        /* Điều chỉnh cho các mục con */
        .section-card ul li div h4 {
            font-size: 0.9rem; 
        }
        .section-card ul li div p {
            font-size: 0.75rem; 
        }
        .section-card .bg-yellow-100 p {
            font-size: 0.75rem;
        }
        /* Style cho phần Thời gian & Địa điểm */
        .text-pink-700 { color: #be185d; }
        .text-pink-600 { color: #db2777; }
        .bg-pink-50 { background-color: #fdf2f8; }
        .text-pink-900 { color: #831843; }
        .border-pink-500 { border-color: #ec4899; }
        .border-pink-200 { border-color: #fbcfe8; }

    </style>
</head>
<body class="bg-gradient-to-br from-blue-100 to-indigo-200 p-2 md:p-4">

    
    <div class="max-w-xl mx-auto bg-white rounded-3xl shadow-2xl overflow-hidden transform hover-scale">
        
        <header class="bg-gradient-to-r from-blue-700 to-indigo-800 text-white p-2 text-center rounded-t-3xl"> 
            <div class="flex justify-center items-center mb-1">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/Emblem_of_Vietnam.svg/500px-Emblem_of_Vietnam.svg.png" alt="Quốc huy Việt Nam" class="h-10 w-auto"> 
            </div>
            <h2 class="font-extrabold uppercase tracking-wide">Ủy ban Nhân dân Phường Đông Gia Nghĩa</h2>
        </header>

        <div class="p-2 text-center bg-blue-50"> 
            
            <!-- ĐÃ CẬP NHẬT: Tăng cỡ chữ từ text-xl lên text-3xl -->
            <h1 class="font-extrabold text-red-600 uppercase leading-tight text-3xl mb-2">
                Triển khai Chiến dịch
            </h1>
            
            <div class="text-left relative">
                
                <div class="dropcap-wrapper">
                    <span class="text-90-special">90</span>
                    <span class="text-ngay-special">NGÀY</span> 
                </div>

                
                <div class="flow-root"> 
                    <h2 class="title-content-dropcap uppercase font-bold"> 
                        LÀM GIÀU, LÀM SẠCH CƠ SỞ DỮ LIỆU QUỐC GIA VỀ ĐẤT ĐAI
                    </h2>
                </div>
                
            </div>
            
            
            <p class="mt-1 font-medium text-gray-700 italic px-2 clear-both"> 
                "Dữ liệu Đúng - Đủ - Sạch - Sống - Thống nhất để Phục vụ tốt hơn"
            </p>
        </div>

        <main class="p-2"> 
            
            <div class="section-card hover-scale">
                <h3 class="section-title">
                    <svg class="w-5 h-5 flex-shrink-0 text-green-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <span>Mục tiêu & Lợi ích</span>
                </h3>
                <ul class="space-y-1"> 
                    <li class="flex items-start gap-1"> 
                        <svg class="w-4 h-4 text-green-500 flex-shrink-0 mt-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path fill-rule="evenodd" d="M2.25 12c0-5.385 4.365-9.75 9.75-9.75s9.75 4.365 9.75 9.75-4.365 9.75-9.75 9.75S2.25 17.385 2.25 12zm13.36-1.814a.75.75 0 10-1.22-.872l-3.236 4.53L9.53 12.22a.75.75 0 00-1.06 1.06l2.25 2.25a.75.75 0 001.14-.094l3.75-5.25z" clip-rule="evenodd" /></svg>
                        <div>
                            <h4 class="font-semibold text-gray-800">Lợi ích cho người dân</h4>
                            <p class="text-gray-600">Thực hiện các thủ tục đất đai trong tương lai <strong>nhanh chóng, chính xác và tiện lợi</strong> hơn.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-1"> 
                        <svg class="w-4 h-4 text-blue-500 flex-shrink-0 mt-1" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24"><path fill-rule="evenodd" d="M3.75 6.75a3 3 0 00-3 3v6a3 3 0 003 3h16.5a3 3 0 003-3v-6a3 3 0 00-3-3H3.75zm16.5 1.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm-3.75 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z" clip-rule="evenodd" /></svg>
                        <div>
                            <h4 class="font-semibold text-gray-800">Lợi ích cho chính quyền</h4>
                            <p class="text-gray-600">Xây dựng cơ sở dữ liệu đất đai quốc gia chính xác, phục vụ công tác quản lý và cải thiện dịch vụ công.</p>
                        </div>
                    </li>
                </ul>
            </div>

            <div class="section-card hover-scale">
                <h3 class="section-title">
                    <svg class="w-5 h-5 flex-shrink-0 text-purple-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M18 18.72a9.094 9.094 0 003.741-.479 3 3 0 00-4.682-2.72m.94 3.198l.001.001M18 18.72v-2.172a4.5 4.5 0 00-4.5-4.5H9.75a4.5 4.5 0 00-4.5 4.5v2.172m0 0a2.25 2.25 0 002.25 2.25h1.5m0 0a2.25 2.25 0 012.25-2.25h1.5m0 0a2.25 2.25 0 012.25 2.25h1.5m0 0a2.25 2.25 0 002.25-2.25h1.5M12 9.75A4.5 4.5 0 0116.5 12H18a9.094 9.094 0 00-3.741-.479M12 9.75A4.5 4.5 0 007.5 12H6a9.094 9.094 0 013.741-.479" /></svg>
                    <span>Đối tượng tham gia</span>
                </h3>
                <div class="flex items-center gap-2 p-2 bg-purple-50 rounded-lg transform hover-scale"> 
                    <svg class="w-8 h-8 text-purple-700 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"> 
                        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 21v-4.875c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125V21m0 0h4.5V3.545M12.75 21H8.25M8.25 21H3.375c-.621 0-1.125-.504-1.125-1.125V9.75c0-.621.504-1.125 1.125-1.125h17.25c.621 0 1.125.504 1.125 1.125v10.125c0 .621-.504 1.125-1.125 1.125h-4.5M16.5 18v-5.625c0-.621-.504-1.125-1.125-1.125h-2.25c-.621 0-1.125.504-1.125 1.125V18" />
                    </svg>
                    <p class="font-bold text-purple-900 text-sm"> 
                        Toàn bộ <strong>người sử dụng đất, chủ sở hữu nhà ở</strong> (cá nhân, hộ gia đình, tổ chức) trên địa bàn phường Đông Gia Nghĩa.
                    </p>
                </div>
            </div>

            <div class="section-card hover-scale">
                <h3 class="section-title">
                    <svg class="w-5 h-5 flex-shrink-0 text-orange-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25M9 16.5v.75m3-3v3M15 12v5.25m-4.5-15H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" /></svg>
                    <span>Công dân cần chuẩn bị</span>
                </h3>
                <ul class="space-y-2"> 
                    <li class="flex items-center gap-2 p-1 bg-orange-50 rounded-lg transform hover-scale"> 
                        <svg class="w-6 h-6 text-orange-500 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m.75 12l3 3m0 0l3-3m-3 3v-6m-1.5-9H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" /></svg>
                        <span class="text-sm text-gray-700"><strong>Giấy chứng nhận Quyền sử dụng đất</strong> (Sổ đỏ, Sổ hồng).</span> 
                    </li>
                    <li class="flex items-center gap-2 p-1 bg-orange-50 rounded-lg transform hover-scale"> 
                        <svg class="w-6 h-6 text-orange-500 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 8.25h19.5M2.25 9h19.5m-16.5 5.25h6m-6 2.25h6m3-3.75l-3 3m0 0l-3-3m3 3V1.5m9 5.25h-6m6 2.25h-6m6 3.75h-6m-3 3.75H3.75A1.125 1.125 0 012.625 21V5.25A1.125 1.125 0 013.75 4.125h16.5A1.125 1.125 0 0121.375 5.25V21a1.125 1.125 0 01-1.125 1.125H12m-3.75 0h-1.5m-1.5 0H6" /></svg>
                        <span class="text-sm text-gray-700"><strong>Căn cước công dân (CCCD)</strong> của tất cả người có tên trên sổ.</span> 
                    </li>
                </ul>
                <div class="mt-2 p-1 bg-yellow-100 border-l-4 border-yellow-500 rounded-r-lg shadow-inner"> 
                    <p class="font-bold text-yellow-800 text-xs">Lưu ý: Chỉ cần cung cấp <strong>bản sao hoặc bản chụp hình ảnh</strong>, không cần nộp bản gốc.</p> 
                </div>
            </div>
            
            
            <div class="section-card border-t-4 border-pink-500 shadow-lg"> 
                <h3 class="section-title text-pink-700 border-pink-200">
                    <svg class="w-5 h-5 flex-shrink-0 text-pink-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 9a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                    <span>Thời gian & Địa điểm tiếp nhận</span>
                </h3>
                <div class="p-1 space-y-1">
                    
                    <div class="flex items-start gap-2 p-1 bg-pink-50 rounded-lg">
                        <svg class="w-5 h-5 text-pink-600 flex-shrink-0 mt-0.5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 9a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                        <div>
                            <h4 class="font-bold text-pink-900">Thời gian</h4>
                            <p class="text-gray-700 text-sm">Từ ngày <strong>25/10/2025</strong> đến hết ngày <strong>15/11/2025</strong></p>
                        </div>
                    </div>
                    
                    <div class="flex items-start gap-2 p-1 bg-pink-50 rounded-lg">
                        <svg class="w-5 h-5 text-pink-600 flex-shrink-0 mt-0.5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 11-6 0 3 3 0 016 0z" /><path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1115 0z" /></svg>
                        <div>
                            <h4 class="font-bold text-pink-900">Địa điểm</h4>
                            <p class="text-gray-700 text-sm">Tại <strong>hội trường các tổ dân phố trên địa bàn phường</strong></p>
                        </div>
                    </div>
                </div>
            </div>

        </main>

        <footer class="bg-gradient-to-r from-green-600 to-emerald-700 text-white p-3 text-center rounded-b-3xl"> 
            <h4 class="font-extrabold leading-relaxed">
                "Vì quyền lợi của chính mình, hãy chuẩn bị và phối hợp để dữ liệu đất đai được chính xác!"
            </h4>
        </footer>

    </div>

</body>
</html>
