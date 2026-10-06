**Bài 4 : Tối ưu tài nguyên máy tính và xây dựng hệ thống lưu trữ khoa học**

### ***Phần 1 (Phân tích):***

Sử dụng Task Manager để chẩn đoán xem tại sao máy bị lag (dựa trên **%CPU và %RAM**). Giải thích sự khác biệt về vai trò giữa **RAM (Bàn làm việc)** và **Storage (Ngăn tủ)** trong tình huống này.  
\+Hơn 90 %CPU  và khi RAM đầy thì máy giật lag  
\+RAM (Bàn làm việc) lưu trữ dữ liệu tạm thời, nếu máy đang giật là, tắt máy thì sẽ mất hết dữ liệu   
\+Storage (Ngăn tủ) Lưu trữ file lâu dài (code, tài liệu). Không trực tiếp xử lý công việc. 

***Phần 2 (Thiết kế):***

Vẽ lại sơ đồ Cây thư mục (File Tree) mới trên ổ D: theo đúng **quy tắc 4 trụ cột** và Naming Convention chuẩn **kebab-case**.  
D:\\ 

└── ptit-projects/   
       └── python-first-project/   
              ├── docs/   
              ├── src/   
              └── data/ 

