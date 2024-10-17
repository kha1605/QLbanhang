# Hệ thống Quản lý Sản phẩm

## Mục lục
- [Giới thiệu](#giới-thiệu)
- [Chức năng của Hệ thống](#chức-năng-của-hệ-thống)
  - [Đối với Admin](#đối-với-admin)
  - [Đối với Khách vãng lai](#đối-với-khách-vãng-lai)
  - [Đối với Khách hàng](#đối-với-khách-hàng)
- [Cài đặt](#cài-đặt)
- [Liên hệ](#liên-hệ)

## Giới thiệu
Hệ thống Quản lý Sản phẩm là một ứng dụng cho phép người dùng quản lý và mua sản phẩm một cách dễ dàng và hiệu quả. Hệ thống bao gồm nhiều chức năng để phục vụ cho các đối tượng khác nhau như admin, khách vãng lai và khách hàng đã đăng ký.

## Chức năng của Hệ thống

### Đối với Admin
- **Quản lý kho**: Cập nhật, sửa, xóa thông tin kho hàng.
- **Quản lý sản phẩm**: Cập nhật, sửa, xóa thông tin sản phẩm.
- **Quản lý thông tin người dùng**: Cập nhật, sửa, xóa thông tin người dùng.

### Đối với Khách vãng lai (khách chưa đăng ký tài khoản)
- **Xem sản phẩm**: Duyệt và xem thông tin chi tiết về các sản phẩm.
- **Xem đánh giá sản phẩm**: Đọc các đánh giá từ người dùng khác về sản phẩm.

### Đối với Khách hàng
- **Xem sản phẩm**: Duyệt và xem thông tin chi tiết về các sản phẩm.
- **Đánh giá sản phẩm**: Để lại đánh giá cho các sản phẩm đã mua.
- **Xem đánh giá sản phẩm**: Đọc các đánh giá từ người dùng khác về sản phẩm.
- **Thêm giỏ hàng**: Thêm sản phẩm vào giỏ hàng của mình.
- **Xem giỏ hàng**: Kiểm tra các sản phẩm đã thêm vào giỏ hàng.
- **Đặt hàng**: Thực hiện đặt hàng cho các sản phẩm trong giỏ hàng.
- **Thanh toán**: Thực hiện thanh toán cho các đơn hàng.
- **Quản lý thông tin cá nhân**: Thêm, cập nhật, sửa, xóa thông tin cá nhân.
- **Xem hóa đơn**: Kiểm tra và xem các hóa đơn đã thanh toán.

# Hướng Dẫn Xây Dựng Dự Án C# Tại Local

## Mục Lục
- [Giới Thiệu](#giới-thiệu)
- [Bước 1: Cài Đặt Môi Trường Phát Triển](#bước-1-cài-đặt-môi-trường-phát-triển)
- [Bước 2: Tạo hoặc Clone Dự Án](#bước-2-tạo-hoặc-clone-dự-án)
- [Bước 3: Cài Đặt Các Thư Viện và Gói Cần Thiết](#bước-3-cài-đặt-các-thư-viện-và-gói-cần-thiết)
- [Bước 4: Build Dự Án](#bước-4-build-dự-án)
- [Bước 5: Chạy Ứng Dụng](#bước-5-chạy-ứng-dụng)
- [Bước 6: Kiểm Tra Kết Quả](#bước-6-kiểm-tra-kết-quả)
- [Kết Luận](#kết-luận)

## Giới Thiệu
Hướng dẫn này cung cấp các bước chi tiết để xây dựng và chạy một dự án C# ở local. Hướng dẫn áp dụng cho các dự án ASP.NET hoặc ứng dụng Console sử dụng .NET Framework hoặc .NET Core.

## Bước 1: Cài Đặt Môi Trường Phát Triển

1. **Cài đặt Visual Studio**:
   - Tải và cài đặt [Visual Studio](https://visualstudio.microsoft.com/). Chọn phiên bản Community nếu bạn muốn sử dụng miễn phí.

2. **Cài đặt .NET SDK** (nếu bạn phát triển với .NET Core):
   - Tải và cài đặt [.NET SDK](https://dotnet.microsoft.com/download).

## Bước 2: Tạo hoặc Clone Dự Án

1. **Tạo Dự Án Mới**:
   - Mở Visual Studio.
   - Chọn **Create a new project**.
   - Chọn loại dự án bạn muốn (ASP.NET Web Application, Console Application, v.v.) và nhấn **Next**.
   - Đặt tên cho dự án và chọn vị trí lưu trữ, sau đó nhấn **Create**.

2. **Clone Dự Án Từ GitHub**:
   - Mở Terminal hoặc Command Prompt.
   - Sử dụng lệnh sau để clone dự án:
     ```bash
     git clone https://github.com/kha1605/QLbanhang.git
     cd repository
     ```

## Bước 3: Cài Đặt Các Thư Viện và Gói Cần Thiết

Nếu dự án của bạn sử dụng NuGet để quản lý các gói thư viện:

- Mở **Package Manager Console** trong Visual Studio:
  - Đi tới **Tools** > **NuGet Package Manager** > **Package Manager Console**.

- Chạy lệnh sau để cài đặt các gói cần thiết:
  ```powershell
  Update-Package

