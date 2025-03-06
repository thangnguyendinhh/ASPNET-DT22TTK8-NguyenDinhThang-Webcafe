# Dự án website bán cafe giải khát bằng ASP.Net
## Cài đặt công cụ triển khai
1. Cài đặt SQL Server 2022 và SQL Server Management Studio (SSMS)
   - Truy cập trang chủ Microsoft download SQL Server 2022 phiên bản developer hoặc Express
   - Tiến hành cài đặt theo các bước
   - Download SSMS và tiến hàng cài đặt theo các bước
   - cấu hình SQL server login bằng tài khoản windows và tài khoản SQL (sa)
  2. Cài đặt visual studio 2022
     - Truy cập trang chủ Microsoft và download visual studio 2022
     - Tiến hàng cài đặt theo các bước.
  ## Triển khai dự án
  1. Tạo CSDL trên SQL server và tạo project trên visual studio 2022
  2. Phân tích các chức năng của website
     ### Trang người dùng
       - Giao diện website
       - danh sách sản phẩm
       - Chức năng tìm kiếm
       - Chức năng giỏ hàng
       - Chức năng đặt hàng
       - chức năng đăng ký/đăng nhập
     ### Trang quản trị
       - Quản lý sản phẩm: thêm/sửa/xóa sản phẩm
       - QUản lý danh mục: thêm/sửa/xóa danh mục
       - Quản ký đơn hàng
       - Quản lý người dùng
       - Quản lý phân quyền
       - Thống kê
     ### Demo giao diện
     1. Giao diện người dùng
       ![front_home](https://github.com/user-attachments/assets/15f14970-1d6f-476f-8714-abea7fbae555)

       - Danh sách sản phẩm
         ![front_list san pham](https://github.com/user-attachments/assets/a6f4749c-c997-4883-a239-1a2744401bc8)

         - giao diện chi tiết sản phẩm
           ![front_chi tiet_san_pham](https://github.com/user-attachments/assets/21e27420-cee7-4f8f-8c3c-e5214e037b10)

         - Chức năng giỏ hàng
           ![Gio hang](https://github.com/user-attachments/assets/282142e1-6191-46e5-a18b-a8f098e26c52)

           - Chức năng edit giỏ hàng
             ![edit_gio_hang](https://github.com/user-attachments/assets/f41396e2-e520-4bd5-9857-aae5be233b16)

            - Chức năng đặt hàng
              ![dat hang](https://github.com/user-attachments/assets/d4cdc8d7-e9be-45c5-92b3-5b1004cb1010)

            - Chức năng đăng ký người dùng
              ![front_dang ky tk](https://github.com/user-attachments/assets/da291c2e-4c99-4ae7-b641-1cfc8aca069e)

            - Chức năng đăng nhập tài khoản người dùng
              ![dang_nhap](https://github.com/user-attachments/assets/3e7dc278-003d-4c18-9136-1fc9f8df0e57)

              - Chức năng thông tin tài khoản
                ![front_chi tiết user](https://github.com/user-attachments/assets/f89783c9-b439-4345-99ce-34928311965b)

      2. Giao diện admin
         - Trang quản lý sản phẩm
           ![admin_home](https://github.com/user-attachments/assets/912dd30e-a3c5-460c-8b72-43fc4ed89e1e)

         - Trang danh mục sản phẩm
           ![danh muc san pham](https://github.com/user-attachments/assets/c18c7ece-ebb0-4630-9934-e9c37b4a8ebe)

         - Quản lý đơn hàng
            ![admin_quan ly don hang](https://github.com/user-attachments/assets/cff82524-26b8-4510-8b43-b53e2f3c4ed2)

         - Quản lý người dùng
           ![quan ly user](https://github.com/user-attachments/assets/c9177d4a-a154-408b-82b9-b80927e4bced)

         - Quản lý quyền
          ![quan ly quyen](https://github.com/user-attachments/assets/8f725ebf-3ed8-4ac3-982b-1f515aea7fa9)

         - Thống kê
           ![admin_thống kê](https://github.com/user-attachments/assets/b033af31-7531-4764-b961-1d932f9321af)

User đăng nhập

user khách khách: 
email: nguyendinhthang01@tvu.edu.vn
password: 12345678

User admin:
email: thangnd261000@tvu-onschool.edu.vn
password: 12345678

sau khi đăng nhập,để vào trang quản trị, truy cập link: /admin/Home





           

