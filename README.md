# Xây dựng Website bán tranh Thangka

Dự án này tập trung vào việc xây dựng một website thương mại điện tử để giới thiệu và bán các bức tranh Thangka - một loại hình nghệ thuật truyền thống của Tây Tạng, sử dụng nền tảng WordPress và các công cụ hỗ trợ như WooCommerce.

## Mục tiêu dự án

- Tạo một nền tảng trực tuyến chuyên nghiệp để kinh doanh các tác phẩm tranh Thangka.
- Giới thiệu và truyền tải giá trị văn hóa và nghệ thuật của Thangka đến cộng đồng.
- Đảm bảo trải nghiệm người dùng thân thiện và hiệu quả trong việc tìm kiếm, mua bán sản phẩm.

## Các tính năng chính

1. **Tìm kiếm và xem chi tiết sản phẩm**:
   - Tìm kiếm sản phẩm theo tên, danh mục, giá cả, màu sắc, kích thước.
   - Trang chi tiết sản phẩm cung cấp thông tin đầy đủ về tranh Thangka.

2. **Hệ thống giỏ hàng và thanh toán**:
   - Thêm sản phẩm vào giỏ, cập nhật số lượng, và thanh toán an toàn.

3. **Quản lý tài khoản**:
   - Người dùng có thể đăng ký, đăng nhập và theo dõi lịch sử mua hàng.

4. **Hỗ trợ đa ngôn ngữ**:
   - Website có khả năng tích hợp nhiều ngôn ngữ phục vụ khách hàng quốc tế.

5. **Tính năng nâng cao**:
   - So sánh sản phẩm.
   - Lưu sản phẩm yêu thích.
   - Xem phương vị nhà ở và tuổi xây dựng phong thủy khách hàng lựa chọn phương hướng treo Thangka thích hợp.

6. **Chức năng quản trị**:
   - Quản lý sản phẩm, đơn hàng, khách hàng, và các bài viết trên Blog.

## Công nghệ sử dụng

- **WordPress**: Nền tảng chính để xây dựng website.
- **WooCommerce**: Plugin hỗ trợ xây dựng cửa hàng trực tuyến.
- **Xampp**: Tạo môi trường máy chủ cục bộ bao gồm Apache để chạy máy chủ web, MySQL để quản lý cơ sở dữ liệu.

## Hướng dẫn cài đặt

1. Cài đặt môi trường phát triển:
   - Tải và cài đặt XAMPP.
   - Cài đặt WordPress từ [wordpress.org](https://wordpress.org).

2. Cài đặt cơ sở dữ liệu:
   - Tạo cơ sở dữ liệu MySQL thông qua phpMyAdmin.
   - Cấu hình `wp-config.php` để kết nối WordPress với cơ sở dữ liệu.

3. Cài đặt website:
   - Tải theme và các plugin cần thiết.
   - Kích hoạt WooCommerce và cấu hình cửa hàng.

4. Tùy chỉnh nội dung:
   - Thêm các danh mục sản phẩm, hình ảnh, và thông tin chi tiết.



### Tiến Độ Thực Hiện Website Bán Tranh Thangka Bằng WordPress  

---

#### **Tuần 1: Khởi động Dự án**  
##### **Nghiên cứu và Lên Kế Hoạch**  
- **Xác định mục tiêu dự án:**  
  - Xây dựng website bán tranh Thangka với giao diện trực quan, dễ sử dụng.  
  - Website gồm 6 trang chính:  
    - **Trang chủ**: Hiển thị bộ sưu tập tranh nổi bật và tổng quát về cửa hàng.  
    - **Trang giới thiệu**: Cung cấp thông tin về lịch sử, ý nghĩa văn hóa của tranh Thangka và cửa hàng.  
    - **Trang cửa hàng**: Hiển thị các sản phẩm Thangka kèm thông tin chi tiết và nút "Thêm vào giỏ hàng".  
    - **Trang phương vị**: Tích hợp tính năng xem hướng nhà và xem tuổi xây dựng.  
    - **Trang tin tức**: Cập nhật các bài viết, sự kiện, hoặc câu chuyện về tranh Thangka.  
    - **Trang liên hệ**: Cung cấp thông tin liên lạc và biểu mẫu liên hệ.  
- **Lập danh sách các tính năng cần thiết:**  
  - Hệ thống quản lý sản phẩm.  
  - Tích hợp giỏ hàng và thanh toán trực tuyến.  
  - Trang tìm kiếm và phân loại sản phẩm theo danh mục.  
  - Hệ thống quản lý tài khoản người dùng.  

##### **Cài đặt WordPress**  
- Cài đặt WordPress trên hosting hoặc localhost.  
- Cấu hình cơ bản:  
  - Cài đặt ngôn ngữ, giao diện mặc định.  
  - Thiết lập bảo mật cơ bản (sao lưu, plugin bảo mật).  

---

#### **Tuần 2: Thiết kế Giao Diện**  
##### **Thiết kế Giao Diện Người Dùng (UI)**  
- **Tạo mẫu thiết kế:**  
  - Sử dụng Canva để tạo mẫu thiết kế giao diện:  
    - **Trang chủ:** Trình bày các sản phẩm nổi bật, banner chuyển động và các liên kết nhanh.  
    - **Trang giới thiệu:** Tập trung vào hình ảnh tranh Thangka và nội dung giới thiệu giàu tính thẩm mỹ.  
    - **Trang cửa hàng:** Bố cục sản phẩm theo lưới, có tính năng lọc và tìm kiếm.  
    - **Trang phương vị:** Hiển thị lý do có trang phương vị và tính năng xem hướng nhà, xem tuổi xây dựng.  
    - **Trang tin tức:** Thiết kế phần bài viết dạng blog.  
    - **Trang liên hệ:** Đơn giản với form liên hệ và thông tin kết nối nhanh qua email, điện thoại và các kênh mạng xã hội nổi bật.  
- **Xây dựng các trang chính trong WordPress:**  
  - Sử dụng công cụ thiết kế Elementor.  

##### **Cài đặt Plugin**  
- **Quản lý sản phẩm, thanh toán và người dùng::**  
  - Cài đặt **WooCommerce** để quản lý sản phẩm, thanh toán trực tuyến và người dùng.  
- **Tối ưu hiệu suất trang web:**   
  - Thêm plugin tối ưu tốc độ tải trang (**WP Rocket**).  

---

#### **Tuần 3: Xây dựng chức năng và thiết kế poster**  
##### **Xây Dựng Các Trang Chính**  
- **Trang chủ:**  
  - Hiển thị banner chính, các sản phẩm nổi bật và bài viết mới từ trang tin tức.  
- **Trang giới thiệu:**  
  - Thêm nội dung về nguồn cảm hứng trong tranh Thangka, thông tin về cửa hàng và các họa sĩ nổi tiếng.  
- **Trang cửa hàng:**  
  - Tích hợp tính năng lọc sản phẩm theo giá, kích thước, màu sắc.  
- **Trang phương vị:**  
  - Tra cứu phương vị hiển thị vị trí phương hướng và tuổi thích hợp để đặt tranh Thangka.  
- **Trang tin tức:**  
  - Đăng các bài viết về nghệ thuật Thangka, các sự kiện văn hóa liên quan.  
- **Trang liên hệ:**  
  - Thêm biểu mẫu liên hệ (dùng plugin **Contact Form 7**) và thông tin cửa hàng.  

##### **Thiết Kế Poster**  
- Sử dụng Canva để thiết kế poster quảng bá website.  
  - Sử dụng hình ảnh tranh Thangka chất lượng cao.  
  - Thêm thông điệp quảng bá và cấu chi tiết của đồ án.  

---

#### **Tuần 4: Kiểm tra và Hoàn Thiện**  
##### **Kiểm tra và Chỉnh sửa**  
- **Kiểm tra chức năng:**  
  - Đảm bảo các tính năng như giỏ hàng, thanh toán, tìm kiếm và tra cứu phương vị hoạt động tốt.  
- **Kiểm tra giao diện:**  
  - Tối ưu hóa giao diện trên các thiết bị.  
  - Kiểm tra lại tốc độ tải trang và sửa lỗi.  

##### **Hoàn Thiện Poster và Bài Thuyết Trình**  
- **Poster:**  
  - Hoàn chỉnh thiết kế poster để in ấn hoặc quảng bá trực tuyến.  
- **Bài thuyết trình:**  
  - Sử dụng PowerPoint để tạo bài thuyết trình:  
    - Giới thiệu mục tiêu dự án và các tính năng chính của website.  
    - Trình bày quy trình thực hiện và các kết quả đạt được.  

---

## Kết quả đạt được
- Website bán tranh Thangka hoàn thiện với đầy đủ 6 trang chính, giao diện đẹp và chức năng tối ưu.  
- Website đã sẵn sàng hoạt động với giao diện thân thiện, tích hợp đầy đủ chức năng cần thiết cho một cửa hàng trực tuyến.
- Tăng khả năng tiếp cận của tranh Thangka đến cộng đồng khách hàng tiềm năng.
- Poster và bài thuyết trình hỗ trợ tốt cho việc quảng bá và giới thiệu dự án.  
## Hướng phát triển

- Tích hợp thêm các phương thức thanh toán như PayPal, Stripe.
- Phát triển ứng dụng di động để hỗ trợ trải nghiệm mua sắm tốt hơn.
- Tăng cường chiến lược SEO để thu hút lượng truy cập lớn hơn.

## Thông tin liên hệ:
**Email:** trantrungphuc98021@gmail.com

**MSSV:** 110122142

**Mã lớp:** DA22TTB

`GVHD: Nguyễn Hoàng Duy Thiện`
