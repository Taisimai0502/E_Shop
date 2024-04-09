# Complete E-SHOP website in laravel
## Describe
Trong thế giới nhanh chóng của thương mại trực tuyến, hiệu quả và tính linh hoạt là chìa khóa. Đó là lý do tại sao chúng tôi rất vui mừng khi trình bày giải pháp thương mại điện tử bespoke của chúng tôi được cung cấp bởi Laravel, khung PHP nổi tiếng được biết đến với sự thanh lịch và mạnh mẽ của nó. Với nền tảng của chúng tôi, các doanh nghiệp có thể dễ dàng tạo ra một cửa hàng trực tuyến năng động vừa thân thiện với người dùng và công nghệ tiên tiến.
Từ danh sách sản phẩm phức tạp đến một hệ thống quản lý đơn hàng toàn diện, nền tảng của chúng tôi được thiết kế để cung cấp trải nghiệm mua sắm liền mạch. Mỗi tính năng được phát triển tỉ mỉ để đảm bảo điều hướng trực quan, giao dịch an toàn và thiết kế đáp ứng trên tất cả các thiết bị.
Bằng cách tận dụng kiến trúc MVC tinh vi của Laravel, chúng tôi cung cấp cho các thương nhân một mức độ kiểm soát và tùy chỉnh cao đối với các cửa hàng trực tuyến của họ. Điều này cho phép triển khai nhanh chóng các tính năng mới và đảm bảo rằng các doanh nghiệp có thể đáp ứng nhanh chóng các nhu cầu phát triển của thị trường.
Nắm bắt sức mạnh của thương mại điện tử hiện đại với giải pháp dựa trên Laravel của chúng tôi, nơi hiệu suất, bảo mật và khả năng mở rộng hội tụ để thúc đẩy doanh nghiệp của bạn tiến lên trong thời đại kỹ thuật số.

## The First

### Dependencies
+ dependencies chứa:

1/ laravel-echo: Dùng để làm việc với Laravel Echo, một thư viện phát thanh sự kiện trong Laravel.
2/ pusher-js: Thư viện client để tương tác với Pusher, dùng để xây dựng các ứng dụng realtime.

+ devDependencies chứa nhiều gói liên quan đến phát triển web như:

1/ axios, bootstrap, jquery, vue: Thư viện phổ biến cho việc xây dựng giao diện người dùng và gọi API.
2/ laravel-mix, sass, sass-loader: Công cụ và thư viện liên quan đến biên dịch CSS từ SASS/SCSS.
3/ cross-env, popper.js, resolve-url-loader, vue-template-compiler: Các công cụ và thư viện hỗ trợ phát triển ứng dụng Vue.js và web.

Set up :
Clone the repo and cd into it
In your terminal composer install
Rename or copy .env.example file to .env
php artisan key:generate
Set your database credentials in your .env file
Set your Braintree credentials in your .env file if you want to use PayPal
Import db file(database/e-shop.sql) into your database (mysql,sql)
npm install
npm run watch
run command[laravel file manager]:- php artisan storage:link
Edit .env file :- remove APP_URL
php artisan serve or use virtual host
Visit localhost:8000 in your browser
Visit /admin if you want to access the admin panel. Admin Email/Password: admin@gmail.com/1111. User Email/Password: user@gmail.com/1111
