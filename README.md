# TRAINING

---

### Phrases 1.

Hướng xây dựng 1 framework MVC cơ bản để hiểu được MVC pattern rất hay dung trong
làm WEB, hiểu và nắm được các thành phần của web để khi tiếp cận các framework khác hay học framework
mới sẽ rễ hiểu và đơn giản hơn.

Code training có thể tham khảo ở đây.

[Simple PHP MVC Framework](https://github.com/nguyentrungtung/mvcphp)

Tài liêu Tham khảo về design pattern

1. [Source Making](https://sourcemaking.com/design_patterns)
2. [Original Design Pattern Book](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8)

---

Yêu cầu của framework build cần có.

* Cấu trúc project theo chuẩn PSR-4.
* Controller.
* Model.
* View.
* Database.
* Config.

**Example Structure**

```ini
├── app
│   ├── Config
│   ├── Controllers
│   ├── Core
│   ├── Models
│   ├── Services
│   ├── Utils
│   └── Views
├── bootstrap
│   └── app.php
├── composer.json
├── public
│   └── index.php
├── readme.md
└── vendor
    ├── autoload.php
    └── composer
```

Các yêu cầu thêm không bắt buộc.

* Encrypt cookie, session.
* Thử tích hợp các component/libraries khác vào framework vừa build (vd: tích hợp vender package laravel eloquent ORM, hay validator, ...)

Nếu còn thời gian sẽ cho xây dựng 1 blog CRUD đơn giản trên framework vừa xây dựng.

---

Từ tuần 2 sinh viên sẽ chuyển sang tìm hiểu về framework laravel. Yêu cầu là phải học qua và nắm được
các kiến thức cở bản trong phần training 1. Nếu bạn nào chưa nắm vững thì cho tự tìm hiểu lại và thời gian sẽ rút xuống 1/2 nghĩa là còn 1 tuần cho
việc review phần 1.

### Phrases 2:

Tài liệu training larvel cũng dựa vào các đề muc cần tìm hiểu và tìm hiểu ở các trang dứoi đây hay mentor có thể dùng các tài liệu khác phù hơp.

1. Web:

* [Larvel Official Documentation](https://laravel.com/docs/9.x)
* Có thể sử dụng phần extension dịch để đọc hiểu

#### Laravel basic. (2 buổi)

1. Cài đặt môi trường phát triển dùng docker nếu môi trường ở phần training 1 không chạy được
   laravel.
2. Các tạo 1 project laravel.
3. [Tìm hiểu về laravel lifecycle](https://laravel.com/docs/9.x/lifecycle#service-providers)
4. [Tìm hiểu về files/folders structure của 1 project laravel.](https://laravel.com/docs/9.x/structure)
5. Tìm hiểu về Architecture Concepts (Service Providers, Service Container)
6. Tìm hiểu về Routing. Controller, View
7. Request & Response.

#### Laravel Intermediate (2-3 buổi)

1. Tìm hiểu về config trong laravel, config môi trường, database,...,.
2. Validation.
3. Tìm hiểu về Database
4. Database migration.
5. Tim hiểu về ORM eloquent.
6. Kết hợp Model, View, Controller. Port lại blog ở phần training 1 sang dùng laravel.
7. Session & Cookie

#### Laravel Advanced. (Phần này sẽ cân nhắc để tự tìm hiểu rồi viết báo cáo hay sẽ training)

1. Tìm hiểu về Authentication & Authorization.
2. Cache.
3. Queue
4. Restful API and webservice.
5. Eloquent Relations and (N+1) problem in ORM relation.
6. Query Builder, Scope, ...
7. Middleware, Contract, Facade.
8. Event, Broadcasting
9. Task & Scheduling

### Phrases 3.

Từ tuần này vẫn tiếp tục học laravel và kết hợp làm project cuối. đự định cho làm 1 trang hoàn chỉnh có thể là trang hoàn chỉnh blog.

* Trang chủ admin list ra được các chức năng sau

   * Home
   * Category
   * Post
   * User
   * Login
