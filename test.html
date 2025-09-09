<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ระบบจองห้องพัก</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Sarabun', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #e0f2fe 0%, #e8f5e8 100%); }
        .room-available { background: linear-gradient(135deg, #4ade80, #22c55e); }
        .room-booked { background: linear-gradient(135deg, #ef4444, #dc2626); }
        .btn-primary { background: linear-gradient(135deg, #06b6d4, #0891b2); }
        .btn-primary:hover { background: linear-gradient(135deg, #0891b2, #0e7490); }
        .admin-bg { background: linear-gradient(135deg, #1e293b, #334155); }
    </style>
</head>
<body class="gradient-bg min-h-screen">
    <!-- Admin Login Modal -->
    <div id="adminLoginModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-xl shadow-2xl max-w-md w-full">
            <div class="p-6">
                <div class="flex justify-between items-center mb-6">
                    <h3 class="text-xl font-semibold text-gray-800">เข้าสู่ระบบแอดมิน</h3>
                    <button onclick="closeAdminLogin()" class="text-gray-500 hover:text-gray-700">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
                <form id="adminLoginForm" class="space-y-4">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">ชื่อผู้ใช้</label>
                        <input type="text" id="adminUsername" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="admin">
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">รหัสผ่าน</label>
                        <input type="password" id="adminPassword" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="password">
                    </div>
                    <button type="submit" class="w-full px-6 py-3 btn-primary text-white rounded-lg transition-colors">
                        เข้าสู่ระบบ
                    </button>
                </form>
            </div>
        </div>
    </div>

    <div class="container mx-auto px-4 py-8">
        <!-- Header -->
        <div class="text-center mb-8">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">
                ระบบการจองห้องพักพิธีพระราชทานปริญญาบัตรแก่ผู้สำเร็จการศึกษา
            </h1>
            <h2 class="text-xl md:text-2xl font-semibold text-teal-700">
                ประจำปีการศึกษา 2567 ระหว่างวันที่ 29 พฤศจิกายน พ.ศ. 2567
            </h2>
        </div>

        <!-- Navigation -->
        <div class="flex justify-center mb-8">
            <div class="bg-white rounded-lg shadow-lg p-2 flex flex-wrap space-x-2">
                <button onclick="showPage('booking')" id="bookingTab" class="px-6 py-3 rounded-lg btn-primary text-white font-medium transition-all">
                    จองห้องพัก
                </button>
                <button onclick="showPage('myBookings')" id="myBookingsTab" class="px-6 py-3 rounded-lg bg-gray-200 text-gray-700 font-medium transition-all hover:bg-gray-300">
                    รายการจองของฉัน
                </button>
                <button onclick="openAdminLogin()" id="adminTab" class="px-6 py-3 rounded-lg bg-slate-600 text-white font-medium transition-all hover:bg-slate-700">
                    🔐 แอดมิน
                </button>
            </div>
        </div>

        <!-- Booking Page -->
        <div id="bookingPage" class="space-y-8">
            <!-- Room Rates Image -->
            <div class="flex justify-center mb-6">
                <img src="rmutto.jpg" alt="อัตราห้องพัดลม" width="600" class="rounded-xl shadow-lg max-w-full h-auto" 
                     onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
                <div class="bg-gradient-to-r from-teal-100 to-blue-100 p-8 rounded-xl shadow-lg max-w-2xl text-center" style="display: none;">
                    <div class="text-4xl mb-4">🏨</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-4">อัตราค่าห้องพัก</h3>
                    <div class="space-y-3 text-left">
                        <div style="text-align: center;">
                        <img src="rmutto.eec.jpg" alt="อัตราห้องพัดลม" width="600">
                        </div>
                        <div class="flex justify-between items-center bg-white p-3 rounded-lg">
                            <span class="font-medium">ห้องพัดลม (1ห้องเข้าพักได้ไม่เกิน 4 ท่าน)</span>
                            <span class="text-teal-600 font-bold">600 บาท/คืน</span>
                        </div>
                        <div class="flex justify-between items-center bg-white p-3 rounded-lg">
                            <span class="font-medium">ค่ามัดจำกุญแจดอกละ 100 บาท</span>
                            <span class="text-teal-600 font-bold">ชำระเงินสดวันที่เข้าพัก </span>
                        </div>
                         <div class="flex justify-between items-center bg-white p-3 rounded-lg">
                            <span class="font-medium">บัณฑิตแสดงบัตรประจำตัวประชาชนติดต่อรับกุญแจห้องพักได้ตั้งแต่เวลา</span>
                            <span class="text-teal-600 font-bold"> 08.30-18.00 น. </span>
                        </div>

                        <div class="text-sm text-gray-600 mt-4 bg-yellow-50 p-3 rounded-lg">
                            <strong>หมายเหตุ:</strong> สอบถามข้อมูลเพิ่มเติม โทร 065-461-5354 นางสาวปุณณภา เหลื่อมล้ำ  
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Calendar Selection -->
            <div class="bg-white rounded-xl shadow-lg p-6">
                <h3 class="text-xl font-semibold text-gray-800 mb-4">เลือกวันที่เข้าพัก</h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="calendar-day p-4 border-2 border-teal-200 rounded-lg cursor-pointer hover:border-teal-400 transition-all" onclick="selectDate('2024-11-03')">
                        <div class="text-center">
                            <div class="text-lg font-semibold text-gray-800">3 พ.ย. 68</div>
                            <div class="text-sm text-gray-600">วันอาทิตย์</div>
                        </div>
                    </div>
                    <div class="calendar-day p-4 border-2 border-teal-200 rounded-lg cursor-pointer hover:border-teal-400 transition-all" onclick="selectDate('2024-11-04')">
                        <div class="text-center">
                            <div class="text-lg font-semibold text-gray-800">4 พ.ย. 68</div>
                            <div class="text-sm text-gray-600">วันจันทร์</div>
                        </div>
                    </div>
                    <div class="calendar-day p-4 border-2 border-teal-200 rounded-lg cursor-pointer hover:border-teal-400 transition-all" onclick="selectDate('2024-11-05')">
                        <div class="text-center">
                            <div class="text-lg font-semibold text-gray-800">5 พ.ย. 68</div>
                            <div class="text-sm text-gray-600">วันอังคาร</div>
                        </div>
                    </div>
                </div>
                <div class="mt-4">
                    <label class="flex items-center space-x-2">
                        <input type="checkbox" id="allDaysCheckbox" class="w-4 h-4 text-teal-600">
                        <span class="text-gray-700">จองทั้ง 3 วัน (3-5 พ.ย. 68)</span>
                    </label>
                </div>
            </div>

            <!-- Room Grid -->
            <div class="bg-white rounded-xl shadow-lg p-6">
                <h3 class="text-xl font-semibold text-gray-800 mb-4">เลือกห้องพัก</h3>
                <div id="roomGrid" class="grid grid-cols-2 md:grid-cols-5 lg:grid-cols-6 gap-3">
                    <!-- Rooms will be generated by JavaScript -->
                </div>
                <div class="mt-4 flex items-center space-x-6">
                    <div class="flex items-center space-x-2">
                        <div class="w-4 h-4 room-available rounded"></div>
                        <span class="text-sm text-gray-600">ว่าง</span>
                    </div>
                    <div class="flex items-center space-x-2">
                        <div class="w-4 h-4 room-booked rounded"></div>
                        <span class="text-sm text-gray-600">จองแล้ว</span>
                    </div>
                </div>
            </div>

            <!-- System Closed Message -->
            <div id="systemClosed" class="bg-red-100 border border-red-400 text-red-700 px-4 py-3 rounded-lg hidden">
                <strong>ขออภัย!</strong> ห้องพักมีการจองเต็มแล้ว ไม่สามารถจองเพิ่มเติมได้
            </div>
        </div>

        <!-- My Bookings Page -->
        <div id="myBookingsPage" class="hidden">
            <div class="bg-white rounded-xl shadow-lg p-6">
                <h3 class="text-xl font-semibold text-gray-800 mb-4">รายการจองของฉัน</h3>
                <div id="bookingsList" class="space-y-4">
                    <!-- Bookings will be displayed here -->
                </div>
            </div>
        </div>

        <!-- Admin Page -->
        <div id="adminPage" class="hidden">
            <div class="admin-bg rounded-xl shadow-lg p-6 text-white mb-6">
                <div class="flex justify-between items-center">
                    <h3 class="text-2xl font-semibold">🛠️ ระบบจัดการแอดมิน</h3>
                    <button onclick="logoutAdmin()" class="px-4 py-2 bg-red-500 text-white rounded-lg hover:bg-red-600 transition-colors">
                        ออกจากระบบ
                    </button>
                </div>
            </div>

            <!-- Admin Stats -->
            <div class="grid grid-cols-1 md:grid-cols-4 gap-6 mb-8">
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-3xl font-bold text-teal-600" id="totalBookings">0</div>
                    <div class="text-gray-600">การจองทั้งหมด</div>
                </div>
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-3xl font-bold text-green-600" id="totalGuests">0</div>
                    <div class="text-gray-600">ผู้เข้าพักทั้งหมด</div>
                </div>
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-3xl font-bold text-blue-600" id="bookedRooms">0</div>
                    <div class="text-gray-600">ห้องที่จองแล้ว</div>
                </div>
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-3xl font-bold text-orange-600" id="availableRooms">30</div>
                    <div class="text-gray-600">ห้องที่ว่าง</div>
                </div>
            </div>

            <!-- Admin Controls -->
            <div class="bg-white rounded-xl shadow-lg p-6 mb-6">
                <h4 class="text-lg font-semibold text-gray-800 mb-4">เครื่องมือจัดการ</h4>
                <div class="flex flex-wrap gap-4">
                    <button onclick="exportBookings()" class="px-4 py-2 bg-green-500 text-white rounded-lg hover:bg-green-600 transition-colors">
                        📊 ส่งออกข้อมูล
                    </button>
                    <button onclick="clearAllBookings()" class="px-4 py-2 bg-red-500 text-white rounded-lg hover:bg-red-600 transition-colors">
                        🗑️ ล้างข้อมูลทั้งหมด
                    </button>
                    <button onclick="showRoomStatus()" class="px-4 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600 transition-colors">
                        🏠 สถานะห้องพัก
                    </button>
                </div>
            </div>

            <!-- Bookings Management -->
            <div class="bg-white rounded-xl shadow-lg p-6">
                <div class="flex justify-between items-center mb-4">
                    <h4 class="text-lg font-semibold text-gray-800">จัดการการจอง</h4>
                    <div class="flex space-x-2">
                        <select id="filterDate" class="px-3 py-2 border border-gray-300 rounded-lg" onchange="filterBookings()">
                            <option value="">ทุกวันที่</option>
                            <option value="2024-11-03">3 พ.ย. 68</option>
                            <option value="2024-11-04">4 พ.ย. 68</option>
                            <option value="2024-11-05">5 พ.ย. 68</option>
                        </select>
                        <select id="filterFaculty" class="px-3 py-2 border border-gray-300 rounded-lg" onchange="filterBookings()">
                            <option value="">ทุกคณะ</option>
                            <option value="คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ">คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ</option>
                            <option value="คณะมนุษยศาสตร์และสังคมศาสตร์">คณะมนุษยศาสตร์และสังคมศาสตร์</option>
                            <option value="คณะวิทยาศาสตร์และเทคโนโลยี">คณะวิทยาศาสตร์และเทคโนโลยี</option>
                        </select>
                    </div>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full table-auto">
                        <thead class="bg-gray-50">
                            <tr>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">ห้อง</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">ผู้จอง</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">วันที่</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">คณะ</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">จำนวนคน</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">เบอร์โทร</th>
                                <th class="px-4 py-3 text-left text-sm font-medium text-gray-700">สถานะ & การจัดการ</th>
                            </tr>
                        </thead>
                        <tbody id="adminBookingsTable" class="divide-y divide-gray-200">
                            <!-- Admin bookings will be displayed here -->
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>

    <!-- Booking Modal -->
    <div id="bookingModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-xl shadow-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-center mb-6">
                    <h3 class="text-xl font-semibold text-gray-800">จองห้องพัก</h3>
                    <button onclick="closeModal()" class="text-gray-500 hover:text-gray-700">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>

                <form id="bookingForm" class="space-y-6">
                    <div id="selectedRoomInfo" class="bg-teal-50 p-4 rounded-lg mb-6"></div>

                    <!-- Number of Guests -->
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">จำนวนผู้เข้าพัก (ไม่เกิน 4 ท่าน)</label>
                        <select id="guestCount" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" onchange="updateGuestForms()">
                            <option value="1">1 ท่าน</option>
                            <option value="2">2 ท่าน</option>
                            <option value="3">3 ท่าน</option>
                            <option value="4">4 ท่าน</option>
                        </select>
                    </div>

                    <!-- Guest Forms Container -->
                    <div id="guestFormsContainer"></div>

                    <!-- Booker Information -->
                    <div class="border-t pt-6">
                        <h4 class="text-lg font-semibold text-gray-800 mb-4">ข้อมูลผู้จอง</h4>
                        
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">เขตพื้นที่/วิทยาเขต</label>
                                <select id="campus" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500">
                                    <option value="">เลือกเขตพื้นที่/วิทยาเขต</option>
                                    <option value="เขตพื้นที่บางพระ">เขตพื้นที่บางพระ</option>
                                    <option value="เขตพื้นที่จักรพงษภูวนารถ">เขตพื้นที่จักรพงษภูวนารถ</option>
                                    <option value="เขตพื้นที่อุเทน">เขตพื้นที่อุเทน</option>
                                    <option value="วิทยาเขตจันทบุรี">วิทยาเขตจันทบุรี</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">คณะ</label>
                                <select id="faculty" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500">
                                    <option value="">เลือกคณะ</option>
                                    <option value="คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ">คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ</option>
                                    <option value="คณะมนุษยศาสตร์และสังคมศาสตร์">คณะมนุษยศาสตร์และสังคมศาสตร์</option>
                                    <option value="คณะวิทยาศาสตร์และเทคโนโลยี">คณะวิทยาศาสตร์และเทคโนโลยี</option>
                                    <option value="คณะสัตวแพทยศาสตร์">คณะสัตวแพทยศาสตร์</option>
                                    <option value="สถาบันเทคโนโลยีการบินและอวกาศ">สถาบันเทคโนโลยีการบินและอวกาศ</option>
                                    <option value="สำนักวิชาวิศวกรรมศาสตร์และนวัตกรรม">สำนักวิชาวิศวกรรมศาสตร์และนวัตกรรม</option>
                                    <option value="สถาบันนวัตกรรมการศึกษาและการเรียนรู้ตลอดชีวิต">สถาบันนวัตกรรมการศึกษาและการเรียนรู้ตลอดชีวิต</option>
                                    <option value="คณะบริหารธุรกิจและเทคโนโลยีสารสนเทศ">คณะบริหารธุรกิจและเทคโนโลยีสารสนเทศ</option>
                                    <option value="คณะวิศวกรรมศาสตร์และสถาปัตยกรรมศาสตร์">คณะวิศวกรรมศาสตร์และสถาปัตยกรรมศาสตร์</option>
                                    <option value="คณะเทคโนโลยีอุตสาหกรรมการเกษตร">คณะเทคโนโลยีอุตสาหกรรมการเกษตร</option>
                                    <option value="คณะเทคโนโลยีสังคม">คณะเทคโนโลยีสังคม</option>
                                    <option value="คณะศิลปศาสตร์">คณะศิลปศาสตร์</option>
                                </select>
                            </div>
                        </div>

                        <div class="mt-4">
                            <label class="block text-sm font-medium text-gray-700 mb-2">เบอร์โทรศัพท์</label>
                            <input type="tel" id="phone" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="เบอร์โทรศัพท์">
                        </div>
                    </div>

                    <!-- Payment Information -->
                    <div class="border-t pt-6">
                        <h4 class="text-lg font-semibold text-gray-800 mb-4">ข้อมูลการชำระเงิน</h4>
                        <div id="paymentAmountInfo" class="bg-orange-50 p-4 rounded-lg mb-4 border border-orange-200">
                            <h5 class="font-semibold text-orange-800 mb-2">💰 ยอดเงินที่ต้องชำระ</h5>
                            <div class="text-orange-700">
                                <p>ห้อง <span id="paymentRoomNumber"></span> × <span id="paymentNights"></span> คืน × 600 บาท</p>
                                <div class="text-xl font-bold text-orange-800 mt-2">
                                    รวมทั้งหมด: <span id="paymentTotalAmount"></span> บาท
                                </div>
                            </div>
                        </div>
                        <div class="bg-blue-50 p-4 rounded-lg mb-4">
                            <h5 class="font-semibold text-blue-800 mb-2">เลขบัญชีการชำระเงินค่าห้อง</h5>
                            <p class="text-blue-700">
                                <strong>ธนาคารกรุงไทย:</strong> 208-0-55482-4<br>
                                <strong>ชื่อบัญชี:</strong> เงินผลประโยชน์(สมทบกลาง)<br>
                                มหาวิทยาลัยเทคโนโลยีราชมงคลตะวันออก
                            </p>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">แนบสลิปหลักฐานการชำระเงิน</label>
                            <input type="file" id="paymentSlip" accept="image/*" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" onchange="previewPaymentSlip(this)">
                            <div id="paymentPreview" class="mt-2 hidden">
                                <img id="previewImage" class="max-w-xs max-h-48 rounded-lg border" alt="ตัวอย่างสลิป">
                            </div>
                        </div>
                    </div>

                    <div class="flex space-x-4 pt-6">
                        <button type="button" onclick="closeModal()" class="flex-1 px-6 py-3 bg-gray-300 text-gray-700 rounded-lg hover:bg-gray-400 transition-colors">
                            ยกเลิก
                        </button>
                        <button type="submit" class="flex-1 px-6 py-3 btn-primary text-white rounded-lg transition-colors">
                            ยืนยันการจอง
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </div>

    <!-- Booking Detail Modal -->
    <div id="detailModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-xl shadow-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-center mb-6">
                    <h3 class="text-xl font-semibold text-gray-800">รายละเอียดการจอง</h3>
                    <button onclick="closeDetailModal()" class="text-gray-500 hover:text-gray-700">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
                <div id="detailContent"></div>
            </div>
        </div>
    </div>

    <!-- Room Status Modal -->
    <div id="roomStatusModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-xl shadow-2xl max-w-4xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-center mb-6">
                    <h3 class="text-xl font-semibold text-gray-800">สถานะห้องพัก</h3>
                    <button onclick="closeRoomStatusModal()" class="text-gray-500 hover:text-gray-700">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>
                <div id="roomStatusContent"></div>
            </div>
        </div>
    </div>

    <!-- Edit Booking Modal -->
    <div id="editBookingModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50 p-4">
        <div class="bg-white rounded-xl shadow-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-6">
                <div class="flex justify-between items-center mb-6">
                    <h3 class="text-xl font-semibold text-gray-800">แก้ไขการจอง</h3>
                    <button onclick="closeEditModal()" class="text-gray-500 hover:text-gray-700">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </button>
                </div>

                <form id="editBookingForm" class="space-y-6">
                    <input type="hidden" id="editBookingId">
                    
                    <div id="editSelectedRoomInfo" class="bg-teal-50 p-4 rounded-lg mb-6"></div>

                    <!-- Number of Guests -->
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">จำนวนผู้เข้าพัก (ไม่เกิน 4 ท่าน)</label>
                        <select id="editGuestCount" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" onchange="updateEditGuestForms()">
                            <option value="1">1 ท่าน</option>
                            <option value="2">2 ท่าน</option>
                            <option value="3">3 ท่าน</option>
                            <option value="4">4 ท่าน</option>
                        </select>
                    </div>

                    <!-- Guest Forms Container -->
                    <div id="editGuestFormsContainer"></div>

                    <!-- Booker Information -->
                    <div class="border-t pt-6">
                        <h4 class="text-lg font-semibold text-gray-800 mb-4">ข้อมูลผู้จอง</h4>
                        
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">เขตพื้นที่/วิทยาเขต</label>
                                <select id="editCampus" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500">
                                    <option value="">เลือกเขตพื้นที่/วิทยาเขต</option>
                                    <option value="เขตพื้นที่บางพระ">เขตพื้นที่บางพระ</option>
                                    <option value="เขตพื้นที่จักรพงษภูวนารถ">เขตพื้นที่จักรพงษภูวนารถ</option>
                                    <option value="เขตพื้นที่อุเทน">เขตพื้นที่อุเทน</option>
                                    <option value="วิทยาเขตจันทบุรี">วิทยาเขตจันทบุรี</option>
                                </select>
                            </div>

                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">คณะ</label>
                                <select id="editFaculty" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500">
                                    <option value="">เลือกคณะ</option>
                                    <option value="คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ">คณะเกษตรศาสตร์และทรัพยากรธรรมชาติ</option>
                                    <option value="คณะมนุษยศาสตร์และสังคมศาสตร์">คณะมนุษยศาสตร์และสังคมศาสตร์</option>
                                    <option value="คณะวิทยาศาสตร์และเทคโนโลยี">คณะวิทยาศาสตร์และเทคโนโลยี</option>
                                    <option value="คณะสัตวแพทยศาสตร์">คณะสัตวแพทยศาสตร์</option>
                                    <option value="สถาบันเทคโนโลยีการบินและอวกาศ">สถาบันเทคโนโลยีการบินและอวกาศ</option>
                                    <option value="สำนักวิชาวิศวกรรมศาสตร์และนวัตกรรม">สำนักวิชาวิศวกรรมศาสตร์และนวัตกรรม</option>
                                    <option value="สถาบันนวัตกรรมการศึกษาและการเรียนรู้ตลอดชีวิต">สถาบันนวัตกรรมการศึกษาและการเรียนรู้ตลอดชีวิต</option>
                                    <option value="คณะบริหารธุรกิจและเทคโนโลยีสารสนเทศ">คณะบริหารธุรกิจและเทคโนโลยีสารสนเทศ</option>
                                    <option value="คณะวิศวกรรมศาสตร์และสถาปัตยกรรมศาสตร์">คณะวิศวกรรมศาสตร์และสถาปัตยกรรมศาสตร์</option>
                                    <option value="คณะเทคโนโลยีอุตสาหกรรมการเกษตร">คณะเทคโนโลยีอุตสาหกรรมการเกษตร</option>
                                    <option value="คณะเทคโนโลยีสังคม">คณะเทคโนโลยีสังคม</option>
                                    <option value="คณะศิลปศาสตร์">คณะศิลปศาสตร์</option>
                                </select>
                            </div>
                        </div>

                        <div class="mt-4">
                            <label class="block text-sm font-medium text-gray-700 mb-2">เบอร์โทรศัพท์</label>
                            <input type="tel" id="editPhone" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="เบอร์โทรศัพท์">
                        </div>

                        <div class="mt-4">
                            <label class="block text-sm font-medium text-gray-700 mb-2">สถานะการจอง</label>
                            <select id="editStatus" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500">
                                <option value="รอยืนยันการจอง">รอยืนยันการจอง</option>
                                <option value="ยืนยันการจอง">ยืนยันการจอง</option>
                            </select>
                        </div>
                    </div>

                    <div class="flex space-x-4 pt-6">
                        <button type="button" onclick="closeEditModal()" class="flex-1 px-6 py-3 bg-gray-300 text-gray-700 rounded-lg hover:bg-gray-400 transition-colors">
                            ยกเลิก
                        </button>
                        <button type="submit" class="flex-1 px-6 py-3 btn-primary text-white rounded-lg transition-colors">
                            บันทึกการแก้ไข
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </div>

    <!-- Image Preview Modal -->
    <div id="imageModal" class="fixed inset-0 bg-black bg-opacity-75 hidden items-center justify-center z-50 p-4">
        <div class="relative max-w-4xl max-h-[90vh]">
            <button onclick="closeImageModal()" class="absolute top-4 right-4 text-white bg-black bg-opacity-50 rounded-full p-2 hover:bg-opacity-75">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                </svg>
            </button>
            <img id="fullImage" class="max-w-full max-h-full rounded-lg" alt="สลิปการชำระเงิน">
        </div>
    </div>

    <script>
        // Global variables
        let selectedDates = [];
        let selectedRoom = null;
        let bookings = JSON.parse(localStorage.getItem('dormBookings')) || [];
        let roomStatus = JSON.parse(localStorage.getItem('roomStatus')) || {};
        let isAdminLoggedIn = false;

        // Initialize room status for all dates if not exists
        const availableDates = ['2024-11-03', '2024-11-04', '2024-11-05'];
        availableDates.forEach(date => {
            if (!roomStatus[date]) {
                roomStatus[date] = {};
                for (let i = 1; i <= 30; i++) {
                    roomStatus[date][i] = 'available';
                }
            }
        });

        // Initialize the application
        document.addEventListener('DOMContentLoaded', function() {
            generateRoomGrid();
            updateMyBookings();
            
            // Handle all days checkbox
            document.getElementById('allDaysCheckbox').addEventListener('change', function() {
                if (this.checked) {
                    selectedDates = [...availableDates];
                    updateCalendarSelection();
                } else {
                    selectedDates = [];
                    updateCalendarSelection();
                }
                generateRoomGrid();
            });

            // Admin login form
            const adminLoginForm = document.getElementById('adminLoginForm');
            if (adminLoginForm) {
                adminLoginForm.addEventListener('submit', function(e) {
                    e.preventDefault();
                    const username = document.getElementById('adminUsername').value.trim();
                    const password = document.getElementById('adminPassword').value.trim();
                    
                    console.log('Login attempt:', username, password); // Debug log
                    
                    if (username === 'admin' && password === 'admin123') {
                        isAdminLoggedIn = true;
                        closeAdminLogin();
                        showPage('admin');
                        updateAdminStats();
                        updateAdminBookingsTable();
                        alert('เข้าสู่ระบบแอดมินสำเร็จ!');
                    } else {
                        alert('ชื่อผู้ใช้หรือรหัสผ่านไม่ถูกต้อง');
                    }
                });
            }
        });

        function showPage(page) {
            const bookingPage = document.getElementById('bookingPage');
            const myBookingsPage = document.getElementById('myBookingsPage');
            const adminPage = document.getElementById('adminPage');
            const bookingTab = document.getElementById('bookingTab');
            const myBookingsTab = document.getElementById('myBookingsTab');

            // Hide all pages
            bookingPage.classList.add('hidden');
            myBookingsPage.classList.add('hidden');
            adminPage.classList.add('hidden');

            // Reset tab styles
            bookingTab.className = 'px-6 py-3 rounded-lg bg-gray-200 text-gray-700 font-medium transition-all hover:bg-gray-300';
            myBookingsTab.className = 'px-6 py-3 rounded-lg bg-gray-200 text-gray-700 font-medium transition-all hover:bg-gray-300';

            if (page === 'booking') {
                bookingPage.classList.remove('hidden');
                bookingTab.className = 'px-6 py-3 rounded-lg btn-primary text-white font-medium transition-all';
            } else if (page === 'myBookings') {
                myBookingsPage.classList.remove('hidden');
                myBookingsTab.className = 'px-6 py-3 rounded-lg btn-primary text-white font-medium transition-all';
                updateMyBookings();
            } else if (page === 'admin' && isAdminLoggedIn) {
                adminPage.classList.remove('hidden');
                updateAdminStats();
                updateAdminBookingsTable();
            }
        }

        // Admin functions
        function openAdminLogin() {
            if (isAdminLoggedIn) {
                showPage('admin');
                return;
            }
            const modal = document.getElementById('adminLoginModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeAdminLogin() {
            const modal = document.getElementById('adminLoginModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function logoutAdmin() {
            isAdminLoggedIn = false;
            showPage('booking');
        }

        function updateAdminStats() {
            const totalBookings = bookings.length;
            const totalGuests = bookings.reduce((sum, booking) => sum + booking.guests.length, 0);
            
            let bookedRoomsCount = 0;
            availableDates.forEach(date => {
                if (roomStatus[date]) {
                    for (let i = 1; i <= 30; i++) {
                        if (roomStatus[date][i] === 'booked') {
                            bookedRoomsCount++;
                            break; // Count each room only once even if booked multiple days
                        }
                    }
                }
            });

            document.getElementById('totalBookings').textContent = totalBookings;
            document.getElementById('totalGuests').textContent = totalGuests;
            document.getElementById('bookedRooms').textContent = bookedRoomsCount;
            document.getElementById('availableRooms').textContent = 30 - bookedRoomsCount;
        }

        function updateAdminBookingsTable() {
            const tbody = document.getElementById('adminBookingsTable');
            tbody.innerHTML = '';

            let filteredBookings = [...bookings];
            
            // Apply filters
            const filterDate = document.getElementById('filterDate').value;
            const filterFaculty = document.getElementById('filterFaculty').value;

            if (filterDate) {
                filteredBookings = filteredBookings.filter(booking => 
                    booking.dates.includes(filterDate)
                );
            }

            if (filterFaculty) {
                filteredBookings = filteredBookings.filter(booking => 
                    booking.faculty === filterFaculty
                );
            }

            filteredBookings.forEach(booking => {
                const row = document.createElement('tr');
                row.className = 'hover:bg-gray-50';
                
                const dateText = booking.dates.map(date => {
                    const d = new Date(date);
                    return d.toLocaleDateString('th-TH', { 
                        day: 'numeric', 
                        month: 'short'
                    });
                }).join(', ');

                const statusColor = booking.status === 'รอยืนยันการจอง' ? 'text-orange-600' : 'text-green-600';
                
                row.innerHTML = `
                    <td class="px-4 py-3 text-sm text-gray-900">${booking.room}</td>
                    <td class="px-4 py-3 text-sm text-gray-900">${booking.guests[0].name}</td>
                    <td class="px-4 py-3 text-sm text-gray-900">${dateText}</td>
                    <td class="px-4 py-3 text-sm text-gray-900">${booking.faculty}</td>
                    <td class="px-4 py-3 text-sm text-gray-900">${booking.guests.length}</td>
                    <td class="px-4 py-3 text-sm text-gray-900">${booking.phone}</td>
                    <td class="px-4 py-3 text-sm">
                        <div class="mb-2">
                            <span class="px-2 py-1 text-xs rounded-full ${statusColor} bg-opacity-20">${booking.status}</span>
                        </div>
                        <div class="flex space-x-2">
                            <button onclick="showBookingDetail(${booking.id})" class="px-3 py-1 bg-blue-500 text-white text-xs rounded hover:bg-blue-600">
                                ดู
                            </button>
                            <button onclick="editBooking(${booking.id})" class="px-3 py-1 bg-yellow-500 text-white text-xs rounded hover:bg-yellow-600">
                                แก้ไข
                            </button>
                            ${booking.status === 'รอยืนยันการจอง' ? 
                                `<button onclick="confirmBooking(${booking.id})" class="px-3 py-1 bg-green-500 text-white text-xs rounded hover:bg-green-600">
                                    ยืนยัน
                                </button>` : ''
                            }
                            <button onclick="deleteBooking(${booking.id})" class="px-3 py-1 bg-red-500 text-white text-xs rounded hover:bg-red-600">
                                ลบ
                            </button>
                        </div>
                    </td>
                `;
                tbody.appendChild(row);
            });

            if (filteredBookings.length === 0) {
                tbody.innerHTML = '<tr><td colspan="7" class="px-4 py-8 text-center text-gray-500">ไม่มีข้อมูลการจอง</td></tr>';
            }
        }

        function filterBookings() {
            updateAdminBookingsTable();
        }

        function deleteBooking(bookingId) {
            if (!confirm('คุณแน่ใจหรือไม่ที่จะลบการจองนี้?')) return;

            const bookingIndex = bookings.findIndex(b => b.id === bookingId);
            if (bookingIndex === -1) return;

            const booking = bookings[bookingIndex];
            
            // Free up the room
            booking.dates.forEach(date => {
                if (roomStatus[date]) {
                    roomStatus[date][booking.room] = 'available';
                }
            });

            // Remove booking
            bookings.splice(bookingIndex, 1);
            
            // Save to localStorage
            localStorage.setItem('dormBookings', JSON.stringify(bookings));
            localStorage.setItem('roomStatus', JSON.stringify(roomStatus));

            // Update displays
            updateAdminStats();
            updateAdminBookingsTable();
            generateRoomGrid();
            
            alert('ลบการจองเรียบร้อยแล้ว');
        }

        function exportBookings() {
            if (bookings.length === 0) {
                alert('ไม่มีข้อมูลการจองให้ส่งออก');
                return;
            }

            let csvContent = 'ห้อง,ผู้จอง,รหัสนักศึกษา,วันที่,คณะ,เขตพื้นที่,จำนวนคน,เบอร์โทร,วันที่จอง\n';
            
            bookings.forEach(booking => {
                const dateText = booking.dates.join(' | ');
                csvContent += `${booking.room},"${booking.guests[0].name}","${booking.guests[0].studentId}","${dateText}","${booking.faculty}","${booking.campus}",${booking.guests.length},"${booking.phone}","${booking.bookingDate}"\n`;
            });

            const blob = new Blob([csvContent], { type: 'text/csv;charset=utf-8;' });
            const link = document.createElement('a');
            const url = URL.createObjectURL(blob);
            link.setAttribute('href', url);
            link.setAttribute('download', 'booking_data.csv');
            link.style.visibility = 'hidden';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        }

        function clearAllBookings() {
            if (!confirm('คุณแน่ใจหรือไม่ที่จะล้างข้อมูลทั้งหมด? การกระทำนี้ไม่สามารถย้อนกลับได้')) return;
            
            bookings = [];
            roomStatus = {};
            
            // Reset room status
            availableDates.forEach(date => {
                roomStatus[date] = {};
                for (let i = 1; i <= 30; i++) {
                    roomStatus[date][i] = 'available';
                }
            });

            localStorage.setItem('dormBookings', JSON.stringify(bookings));
            localStorage.setItem('roomStatus', JSON.stringify(roomStatus));

            updateAdminStats();
            updateAdminBookingsTable();
            generateRoomGrid();
            updateMyBookings();
            
            alert('ล้างข้อมูลทั้งหมดเรียบร้อยแล้ว');
        }

        function showRoomStatus() {
            const modal = document.getElementById('roomStatusModal');
            const content = document.getElementById('roomStatusContent');
            
            let html = '';
            availableDates.forEach(date => {
                const d = new Date(date);
                const dateText = d.toLocaleDateString('th-TH', { 
                    day: 'numeric', 
                    month: 'long', 
                    year: 'numeric' 
                });
                
                html += `<div class="mb-6">
                    <h4 class="text-lg font-semibold text-gray-800 mb-3">${dateText}</h4>
                    <div class="grid grid-cols-6 gap-2">`;
                
                for (let i = 1; i <= 30; i++) {
                    const status = roomStatus[date] && roomStatus[date][i] === 'booked' ? 'booked' : 'available';
                    const statusClass = status === 'available' ? 'room-available' : 'room-booked';
                    const statusText = status === 'available' ? '✅ ว่าง' : '❌ จองแล้ว';
                    
                    html += `<div class="${statusClass} text-white p-2 rounded text-center text-sm">
                        <div>ห้อง ${i}</div>
                        <div class="text-xs">${statusText}</div>
                    </div>`;
                }
                
                html += '</div></div>';
            });
            
            content.innerHTML = html;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeRoomStatusModal() {
            const modal = document.getElementById('roomStatusModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function previewPaymentSlip(input) {
            const preview = document.getElementById('paymentPreview');
            const previewImage = document.getElementById('previewImage');
            
            if (input.files && input.files[0]) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    previewImage.src = e.target.result;
                    preview.classList.remove('hidden');
                };
                reader.readAsDataURL(input.files[0]);
            } else {
                preview.classList.add('hidden');
            }
        }

        function showFullImage(imageSrc) {
            const modal = document.getElementById('imageModal');
            const fullImage = document.getElementById('fullImage');
            
            fullImage.src = imageSrc;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeImageModal() {
            const modal = document.getElementById('imageModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function confirmBooking(bookingId) {
            if (!confirm('คุณแน่ใจหรือไม่ที่จะยืนยันการจองนี้?')) return;

            const bookingIndex = bookings.findIndex(b => b.id === bookingId);
            if (bookingIndex === -1) return;

            bookings[bookingIndex].status = 'ยืนยันการจอง';
            localStorage.setItem('dormBookings', JSON.stringify(bookings));

            updateAdminStats();
            updateAdminBookingsTable();
            updateMyBookings();
            
            alert('ยืนยันการจองเรียบร้อยแล้ว');
        }

        function editBooking(bookingId) {
            const booking = bookings.find(b => b.id === bookingId);
            if (!booking) return;

            const modal = document.getElementById('editBookingModal');
            const roomInfo = document.getElementById('editSelectedRoomInfo');
            
            const dateText = booking.dates.map(date => {
                const d = new Date(date);
                return d.toLocaleDateString('th-TH', { 
                    day: 'numeric', 
                    month: 'short', 
                    year: '2-digit' 
                });
            }).join(', ');
            
            roomInfo.innerHTML = `
                <h4 class="font-semibold text-teal-800">ห้องที่เลือก: ${booking.room}</h4>
                <p class="text-teal-700">วันที่: ${dateText}</p>
            `;

            // Fill form with existing data
            document.getElementById('editBookingId').value = booking.id;
            document.getElementById('editGuestCount').value = booking.guests.length;
            document.getElementById('editCampus').value = booking.campus;
            document.getElementById('editFaculty').value = booking.faculty;
            document.getElementById('editPhone').value = booking.phone;
            document.getElementById('editStatus').value = booking.status;

            updateEditGuestForms();
            
            // Fill guest data
            booking.guests.forEach((guest, index) => {
                const guestIndex = index + 1;
                document.querySelector(`input[name="editGuestName${guestIndex}"]`).value = guest.name;
                document.querySelector(`input[name="editStudentId${guestIndex}"]`).value = guest.studentId;
                document.querySelector(`select[name="editGender${guestIndex}"]`).value = guest.gender;
            });

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeEditModal() {
            const modal = document.getElementById('editBookingModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function updateEditGuestForms() {
            const guestCount = parseInt(document.getElementById('editGuestCount').value);
            const container = document.getElementById('editGuestFormsContainer');
            
            container.innerHTML = '';
            
            for (let i = 1; i <= guestCount; i++) {
                const guestForm = document.createElement('div');
                guestForm.className = 'border border-gray-200 rounded-lg p-4 space-y-4';
                guestForm.innerHTML = `
                    <h5 class="font-semibold text-gray-800">ผู้เข้าพักท่านที่ ${i}</h5>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">ชื่อผู้เข้าพัก</label>
                            <input type="text" name="editGuestName${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="ชื่อ-นามสกุล" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">รหัสนักศึกษา</label>
                            <input type="text" name="editStudentId${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="รหัสนักศึกษา" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">เพศ</label>
                            <select name="editGender${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required>
                                <option value="">เลือกเพศ</option>
                                <option value="ชาย">ชาย</option>
                                <option value="หญิง">หญิง</option>
                            </select>
                        </div>
                    </div>
                `;
                container.appendChild(guestForm);
            }
        }

        // Handle edit booking form submission
        document.addEventListener('DOMContentLoaded', function() {
            const editBookingForm = document.getElementById('editBookingForm');
            if (editBookingForm) {
                editBookingForm.addEventListener('submit', function(e) {
                    e.preventDefault();
                    
                    const bookingId = parseInt(document.getElementById('editBookingId').value);
                    const bookingIndex = bookings.findIndex(b => b.id === bookingId);
                    
                    if (bookingIndex === -1) {
                        alert('ไม่พบข้อมูลการจอง');
                        return;
                    }

                    const formData = new FormData(this);
                    const guestCount = parseInt(document.getElementById('editGuestCount').value);
                    
                    const guests = [];
                    for (let i = 1; i <= guestCount; i++) {
                        guests.push({
                            name: formData.get(`editGuestName${i}`),
                            studentId: formData.get(`editStudentId${i}`),
                            gender: formData.get(`editGender${i}`)
                        });
                    }
                    
                    // Update booking data
                    bookings[bookingIndex].guests = guests;
                    bookings[bookingIndex].campus = document.getElementById('editCampus').value;
                    bookings[bookingIndex].faculty = document.getElementById('editFaculty').value;
                    bookings[bookingIndex].phone = document.getElementById('editPhone').value;
                    bookings[bookingIndex].status = document.getElementById('editStatus').value;
                    
                    localStorage.setItem('dormBookings', JSON.stringify(bookings));
                    
                    closeEditModal();
                    updateAdminStats();
                    updateAdminBookingsTable();
                    updateMyBookings();
                    
                    alert('แก้ไขข้อมูลการจองเรียบร้อยแล้ว!');
                });
            }
        });

        // Rest of the existing functions remain the same...
        function selectDate(date) {
            const allDaysCheckbox = document.getElementById('allDaysCheckbox');
            
            if (allDaysCheckbox.checked) {
                return;
            }

            const index = selectedDates.indexOf(date);
            if (index > -1) {
                selectedDates.splice(index, 1);
            } else {
                selectedDates.push(date);
            }
            
            updateCalendarSelection();
            generateRoomGrid();
        }

        function updateCalendarSelection() {
            const calendarDays = document.querySelectorAll('.calendar-day');
            const dates = ['2024-11-03', '2024-11-04', '2024-11-05'];
            
            calendarDays.forEach((day, index) => {
                if (selectedDates.includes(dates[index])) {
                    day.classList.add('bg-teal-100', 'border-teal-500');
                } else {
                    day.classList.remove('bg-teal-100', 'border-teal-500');
                }
            });
        }

        function generateRoomGrid() {
            const roomGrid = document.getElementById('roomGrid');
            const systemClosed = document.getElementById('systemClosed');
            
            if (selectedDates.length === 0) {
                roomGrid.innerHTML = '<div class="col-span-full text-center text-gray-500 py-8">กรุณาเลือกวันที่เข้าพักก่อน</div>';
                return;
            }

            let availableRooms = 0;
            for (let i = 1; i <= 30; i++) {
                let isAvailable = true;
                for (const date of selectedDates) {
                    if (roomStatus[date] && roomStatus[date][i] === 'booked') {
                        isAvailable = false;
                        break;
                    }
                }
                if (isAvailable) availableRooms++;
            }

            if (availableRooms === 0) {
                systemClosed.classList.remove('hidden');
                roomGrid.innerHTML = '<div class="col-span-full text-center text-red-500 py-8">ห้องพักเต็มแล้ว</div>';
                return;
            } else {
                systemClosed.classList.add('hidden');
            }

            roomGrid.innerHTML = '';
            
            for (let i = 1; i <= 30; i++) {
                const roomDiv = document.createElement('div');
                
                let isAvailable = true;
                for (const date of selectedDates) {
                    if (roomStatus[date] && roomStatus[date][i] === 'booked') {
                        isAvailable = false;
                        break;
                    }
                }
                
                if (isAvailable) {
                    roomDiv.className = 'room-available text-white p-4 rounded-lg cursor-pointer hover:opacity-80 transition-all text-center font-medium';
                    roomDiv.innerHTML = `<div>ห้อง ${i}</div><div class="text-sm">✅ ว่าง</div>`;
                    roomDiv.onclick = () => openBookingModal(i);
                } else {
                    roomDiv.className = 'room-booked text-white p-4 rounded-lg text-center font-medium opacity-75';
                    roomDiv.innerHTML = `<div>ห้อง ${i}</div><div class="text-sm">❌ จองแล้ว</div>`;
                }
                
                roomGrid.appendChild(roomDiv);
            }
        }

        function openBookingModal(roomNumber) {
            selectedRoom = roomNumber;
            const modal = document.getElementById('bookingModal');
            const roomInfo = document.getElementById('selectedRoomInfo');
            
            const dateText = selectedDates.map(date => {
                const d = new Date(date);
                return d.toLocaleDateString('th-TH', { 
                    day: 'numeric', 
                    month: 'short', 
                    year: '2-digit' 
                });
            }).join(', ');
            
            const totalAmount = selectedDates.length * 600;
            
            roomInfo.innerHTML = `
                <h4 class="font-semibold text-teal-800">ห้องที่เลือก: ${roomNumber}</h4>
                <p class="text-teal-700">วันที่: ${dateText}</p>
                <p class="text-teal-700">ราคาห้องละ: 600 บาท/คืน</p>
                <p class="text-teal-700">จำนวนคืน: ${selectedDates.length} คืน</p>
                <div class="bg-teal-100 p-2 rounded mt-2">
                    <p class="font-bold text-teal-800">ยอดรวมทั้งหมด: ${totalAmount.toLocaleString()} บาท</p>
                </div>
            `;
            
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            
            // Update payment information
            document.getElementById('paymentRoomNumber').textContent = roomNumber;
            document.getElementById('paymentNights').textContent = selectedDates.length;
            document.getElementById('paymentTotalAmount').textContent = totalAmount.toLocaleString();
            
            document.getElementById('bookingForm').reset();
            document.getElementById('guestCount').value = '1';
            updateGuestForms();
        }

        function closeModal() {
            const modal = document.getElementById('bookingModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function updateGuestForms() {
            const guestCount = parseInt(document.getElementById('guestCount').value);
            const container = document.getElementById('guestFormsContainer');
            
            container.innerHTML = '';
            
            for (let i = 1; i <= guestCount; i++) {
                const guestForm = document.createElement('div');
                guestForm.className = 'border border-gray-200 rounded-lg p-4 space-y-4';
                guestForm.innerHTML = `
                    <h5 class="font-semibold text-gray-800">ผู้เข้าพักท่านที่ ${i}</h5>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">ชื่อผู้เข้าพัก</label>
                            <input type="text" name="guestName${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="ชื่อ-นามสกุล" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">รหัสนักศึกษา</label>
                            <input type="text" name="studentId${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" placeholder="รหัสนักศึกษา" required>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">เพศ</label>
                            <select name="gender${i}" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-teal-500 focus:border-teal-500" required>
                                <option value="">เลือกเพศ</option>
                                <option value="ชาย">ชาย</option>
                                <option value="หญิง">หญิง</option>
                            </select>
                        </div>
                    </div>
                `;
                container.appendChild(guestForm);
            }
        }

        document.getElementById('bookingForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const formData = new FormData(this);
            const guestCount = parseInt(document.getElementById('guestCount').value);
            
            const guests = [];
            for (let i = 1; i <= guestCount; i++) {
                guests.push({
                    name: formData.get(`guestName${i}`),
                    studentId: formData.get(`studentId${i}`),
                    gender: formData.get(`gender${i}`)
                });
            }
            
            const totalAmount = selectedDates.length * 600;
            
            const booking = {
                id: Date.now(),
                room: selectedRoom,
                dates: [...selectedDates],
                guests: guests,
                campus: document.getElementById('campus').value,
                faculty: document.getElementById('faculty').value,
                phone: document.getElementById('phone').value,
                paymentSlip: document.getElementById('paymentSlip').files[0] ? URL.createObjectURL(document.getElementById('paymentSlip').files[0]) : null,
                paymentSlipName: document.getElementById('paymentSlip').files[0]?.name || 'ไม่มีไฟล์',
                totalAmount: totalAmount,
                status: 'รอยืนยันการจอง',
                bookingDate: new Date().toLocaleDateString('th-TH')
            };
            
            bookings.push(booking);
            localStorage.setItem('dormBookings', JSON.stringify(bookings));
            
            selectedDates.forEach(date => {
                if (!roomStatus[date]) roomStatus[date] = {};
                roomStatus[date][selectedRoom] = 'booked';
            });
            localStorage.setItem('roomStatus', JSON.stringify(roomStatus));
            
            closeModal();
            generateRoomGrid();
            
            if (isAdminLoggedIn) {
                updateAdminStats();
                updateAdminBookingsTable();
            }
            
            alert('จองห้องพักเรียบร้อยแล้ว!');
        });

        function updateMyBookings() {
            const bookingsList = document.getElementById('bookingsList');
            
            if (bookings.length === 0) {
                bookingsList.innerHTML = '<div class="text-center text-gray-500 py-8">ไม่มีรายการจอง</div>';
                return;
            }
            
            bookingsList.innerHTML = '';
            
            bookings.forEach(booking => {
                const bookingDiv = document.createElement('div');
                bookingDiv.className = 'bg-gray-50 p-4 rounded-lg border border-gray-200';
                
                const dateText = booking.dates.map(date => {
                    const d = new Date(date);
                    return d.toLocaleDateString('th-TH', { 
                        day: 'numeric', 
                        month: 'short', 
                        year: '2-digit' 
                    });
                }).join(', ');
                
                const bookingAmount = booking.totalAmount || (booking.dates.length * 600);
                
                bookingDiv.innerHTML = `
                    <div class="flex justify-between items-start">
                        <div>
                            <h4 class="font-semibold text-gray-800">ห้อง ${booking.room}</h4>
                            <p class="text-gray-600">ผู้จอง: ${booking.guests[0].name}</p>
                            <p class="text-gray-600">วันที่: ${dateText}</p>
                            <p class="text-gray-600">ยอดเงิน: <span class="font-semibold text-orange-600">${bookingAmount.toLocaleString()} บาท</span></p>
                            <p class="text-gray-600">สถานะ: <span class="${booking.status === 'รอยืนยันการจอง' ? 'text-orange-600' : 'text-green-600'} font-medium">${booking.status}</span></p>
                        </div>
                        <button onclick="showBookingDetail(${booking.id})" class="px-4 py-2 bg-teal-500 text-white rounded-lg hover:bg-teal-600 transition-colors">
                            ดูรายละเอียด
                        </button>
                    </div>
                `;
                
                bookingsList.appendChild(bookingDiv);
            });
        }

        function showBookingDetail(bookingId) {
            const booking = bookings.find(b => b.id === bookingId);
            if (!booking) return;
            
            const modal = document.getElementById('detailModal');
            const content = document.getElementById('detailContent');
            
            const dateText = booking.dates.map(date => {
                const d = new Date(date);
                return d.toLocaleDateString('th-TH', { 
                    day: 'numeric', 
                    month: 'long', 
                    year: 'numeric' 
                });
            }).join(', ');
            
            let guestList = '';
            booking.guests.forEach((guest, index) => {
                guestList += `
                    <div class="bg-gray-50 p-3 rounded-lg">
                        <h6 class="font-medium">ผู้เข้าพักท่านที่ ${index + 1}</h6>
                        <p>ชื่อ: ${guest.name}</p>
                        <p>รหัสนักศึกษา: ${guest.studentId}</p>
                        <p>เพศ: ${guest.gender}</p>
                    </div>
                `;
            });
            
            const bookingAmount = booking.totalAmount || (booking.dates.length * 600);
            
            content.innerHTML = `
                <div class="space-y-4">
                    <div class="bg-teal-50 p-4 rounded-lg">
                        <h4 class="font-semibold text-teal-800 text-lg">ข้อมูลการจอง</h4>
                        <p><strong>ห้อง:</strong> ${booking.room}</p>
                        <p><strong>วันที่เข้าพัก:</strong> ${dateText}</p>
                        <p><strong>จำนวนคืน:</strong> ${booking.dates.length} คืน</p>
                        <p><strong>ราคาห้องละ:</strong> 600 บาท/คืน</p>
                        <p><strong>ยอดเงินรวม:</strong> <span class="text-orange-600 font-bold text-lg">${bookingAmount.toLocaleString()} บาท</span></p>
                        <p><strong>จำนวนผู้เข้าพัก:</strong> ${booking.guests.length} ท่าน</p>
                        <p><strong>สถานะ:</strong> <span class="text-green-600">${booking.status}</span></p>
                        <p><strong>วันที่จอง:</strong> ${booking.bookingDate}</p>
                    </div>
                    
                    <div>
                        <h5 class="font-semibold text-gray-800 mb-3">รายชื่อผู้เข้าพัก</h5>
                        <div class="space-y-2">
                            ${guestList}
                        </div>
                    </div>
                    
                    <div>
                        <h5 class="font-semibold text-gray-800 mb-3">ข้อมูลผู้จอง</h5>
                        <div class="bg-gray-50 p-3 rounded-lg">
                            <p><strong>เขตพื้นที่/วิทยาเขต:</strong> ${booking.campus}</p>
                            <p><strong>คณะ:</strong> ${booking.faculty}</p>
                            <p><strong>เบอร์โทรศัพท์:</strong> ${booking.phone}</p>
                            <p><strong>สลิปการชำระเงิน:</strong> ${booking.paymentSlipName}</p>
                            ${booking.paymentSlip ? `
                                <div class="mt-3">
                                    <p class="text-sm text-gray-600 mb-2">ตัวอย่างสลิป:</p>
                                    <img src="${booking.paymentSlip}" alt="สลิปการชำระเงิน" class="max-w-xs max-h-64 rounded-lg border cursor-pointer" onclick="showFullImage('${booking.paymentSlip}')">
                                </div>
                            ` : ''}
                        </div>
                    </div>
                </div>
            `;
            
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97c5197bc2bca1c3',t:'MTc1NzQwNDI3Ny4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
