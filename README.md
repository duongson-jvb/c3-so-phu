# Sổ phụ cho C3

Danh sách chặn thứ hai (sổ phụ) của bộ chặn quảng cáo chạy trên ESP32-C3: tên miền quảng cáo, theo dõi
và đích banner cá cược hay gặp ở các web Việt Nam mà sổ chính chưa chặn.

Link nhập vào C3 (mục Sổ phụ, chu kỳ 168 giờ):

    https://github.com/duongson-jvb/c3-so-phu/releases/download/so-phu/blocklist2.bin

Tệp không phải văn bản: mỗi tên miền là 5 byte mã băm FNV-1a (40 bit, little-endian), xếp tăng dần.
Mỗi lần dựng lại, tệp trong release `so-phu` được thay, link giữ nguyên.
