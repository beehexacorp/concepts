# Đồng Bộ Dữ Liệu Là Gì?

## 1. Khái Niệm Đồng Bộ Dữ Liệu

    Đồng bộ dữ liệu là tiến trình làm cho dữ liệu xuất hiện trên các hệ thống khác nhau ở cùng thời điểm.

### 1.1 Cụ thể hơn về việc đồng bộ dữ liệu giữa hệ thống A và hệ thống B.

- Khi một sự kiện __X__ xảy ra ở hệ thống __A__ , sẽ dẫn tới có một tập dữ liệu __D__ được thêm mới, cập nhặt hoặc xóa (__THAY ĐỔI__) trên hệ thống __A__.
- Tiến trình đồng bộ dữ liệu sẽ tạo ra một sự kiện __X1__ xảy ra trên hệ thống B với tập dữ liệu __D1__ được thêm mới, cập nhật hoặc xóa (__THAY ĐỔI__) trên __B__.
- Sự kiện __X1__ nếu xảy ra ngay sau sự kiện __X__ thì được xem như là đồng bộ theo thời gian thực.
- Tập dữ liệu __D__ và __D1__ có thể tương tự nhau nhưng **cũng có thể có khác biệt** tùy theo yêu cầu nghiệp vụ cụ thể.

## 2. Làm Rõ Thuật Ngữ

    2.1 Bộ Là Gì?

    2.2 Đồng Bộ Là Gì?

    2.3 Dữ Liệu Là Gì?

    2.4 Hiểu Đúng Về Đồng Bộ Dữ Liệu?

## 3. Nhầm Lẫn Giữa Đồng Bộ Dữ Liệu và Di Dời Dữ Liệu