Bước 1: Tạo database bằng file QLBanHangVer1 trong file trên SQL
Bước 2: Kết nối database trong Visual Code bằng cách sau :
	2.1. Chọn Project trên thanh công cụ và chọn Properties
	2.2. Chọn Settings
	2.3. Đặt tên tùy ý (nhưng nhớ đổi trong phần code theo tên mình đã đặt: Dòng 20 trong class Functions)
	2.4. Chọn Type là Connection string, Chọn Scope là Application
	2.5. Chọn value 
		2.5.1. Chọn Data source là Micriosoft SQL Server (SqlClient)
		2.5.2. Server name thì tùy vào tên máy bạn sử dụng (Có thể vô SQL chọn properties để xem)
		2.5.3. Phần connect to a database chọn QLBanHangVer1, có thể ấn Test Connection để xem
		2.5.4. Ấn OK và vào code chạy thử
