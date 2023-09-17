<p align="left"><img src="https://rahulvijayam.com/wp-content/uploads/2021/11/1-2-1024x576.jpg" alt="Laravel Ecommerce Project " width="500"></p>


## Features
- User Dashboard
- Admin Dashboard
- Mobile-Friendly Website
- 3 Step Booking Process
- Order Tracking
- Email Notifications
- Subscriber Form
- A product search form
- Payment Gateway(PayU) Integrated
- Shopping Cart in a Responsive Layout
- Pre-Defined Content with High-Resolution Photos
- Search engine optimization (SEO) for Products
- Recommendations and related products in our categories

## Requirements 
-   Laravel <=5.8
-   PHP <= 7.1.3
-   Composer Version 2 
## Installation Steps 

1.  <code> composer create-project</code>
2. Create database for  your project with the name as <code>gainaloe</code>
3. Now Run <code>php artisan migrate</code> command for creating all the tables 
4. Add your email credentials in <code>.env</code> file
5. Add PayuMoney <code>merchant key and salt</code> on <code> config/indipay.php</code> file at line number 30 and 31
6. Start yor project using <code>php artisan serve</code>

## Generate Sample Data ( Optional)
1. Remove tables(products, users) from the  database.
2. Run two files present in this link https://github.com/loyalperson/Ecommerce-Laravel-First.git/tree/master/public/sql on your database
3. Finished, Now Check it in your browser using http://127.0.0.1:8000

### Watch Video
 [![Everything Is AWESOME](https://user-images.githubusercontent.com/36434065/141663839-bb06d652-1be7-4124-b3ba-76e6354bf456.png)](https://www.youtube.com/watch?v=TRr5OQ3YVIE "Watch Video")

## Security Vulnerabilities

If you discover a security vulnerability within project, please send an e-mail to me via [loyalman00715@outlook.com](mailto:loyalman00715@outlook.com). All security vulnerabilities will be promptly addressed.

## License

The project developed using laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
