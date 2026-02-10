Модуль WayForPay для Wordpress WooCommerce
=======

Встановлення
----
>1. Вміст архіву помістити в папку плагінів Wordpress ( за замовчуванням - {корінь сайту}/wp-content/plugins/)
>2. Зайти в адмін розділ сайту (/wp-admin/) та активувати плагін "WooCommerce WayForPay Payments"
>3. Перейти до розділу "WooCommerce" -> "Settings" -> "Checkout"
>4. Внизу сторінки в пункті "WayForPay – Internet acquiring", натиснути кнопку "Settings" біля "Card payments, Apple Pay and Google Pay."
>5. Ввести дані вашого мерчанта.

У полі “Merchant Login” необхідно вставити MERCHANT LOGIN.
У полі “Merchant Secret key” – вставте, будь ласка, MERCHANT SECRET KEY.

![Settings](https://github.com/artgana/woocommerce-wayforpay-gateway/blob/master/settings.png)

## Відмінності від оригінального плагіну
1. Встановлено мінімальну версію PHP 7.4, WordPress 6.2 та WooCommerce 8.2 
2. Виправлено завантаження локалізації, відповідно до змін у WordPress 6.7
3. Додано поп-ап з повідомленням про переадресацію на сайт платіжної системи 

![Modal](https://github.com/artgana/woocommerce-wayforpay-gateway/blob/master/modal.png)

4. Додано опцію вибору часу, через який буде перенаправлено на сайт платіжної системи
5. Змінено повернення після платежу — тепер повертає завжди на сторінку підтвердження замовлення
