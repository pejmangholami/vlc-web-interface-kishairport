<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GNU License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">رابط وب VLC برای IPTV فرودگاه کیش</h3>

  <p align="center">
    یک رابط وب سفارشی برای VLC که برای IPTV فرودگاه کیش بهینه‌سازی شده است.
    <br />
    <a href="https://github.com/pejmangholami/vlc-web-interface-kishairport/issues">گزارش خطا</a>
    ·
    <a href="https://github.com/pejmangholami/vlc-web-interface-kishairport/issues">درخواست ویژگی جدید</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## درباره پروژه

این پروژه یک رابط کاربری وب سفارشی برای نرم‌افزار VLC است که به طور خاص برای سیستم IPTV فرودگاه بین‌المللی کیش توسعه داده شده است.

### ساخته شده با

* [Bootswatch](https://bootswatch.com/)
* [JQuery](https://jquery.com)
* [Font Awesome](https://fontawesome.com/)
* [downupPopup.js](https://downuppopupjs.dincerali.com/)
* [Color Thief](https://lokeshdhakar.com/projects/color-thief/)

<!-- GETTING STARTED -->
## راهنمای نصب و راه‌اندازی

### مراحل نصب

1. پوشه رابط وب پیش‌فرض VLC را پیدا کنید (برای مثال در لینوکس: `/usr/share/vlc/lua/http/`)

2. از فایل‌های موجود در آن پوشه یک نسخه پشتیبان تهیه کرده و سپس محتویات این پروژه را جایگزین آن‌ها کنید (پوشه `requests/` را حذف نکنید).

3. رابط وب VLC را طبق توضیحات این لینک فعال کنید: [https://wiki.videolan.org/Documentation:Modules/http_intf](https://wiki.videolan.org/Documentation:Modules/http_intf)

4. VLC را اجرا کنید، چند فایل به لیست پخش اضافه کرده و به آدرس `http://localhost:[PORT]` بروید.

5. پس از وارد کردن رمز عبوری که انتخاب کرده‌اید، رابط کاربری جدید برای شما نمایش داده خواهد شد.

<!-- ROADMAP -->
## نقشه راه

برای مشاهده لیست ویژگی‌های پیشنهادی (و مشکلات شناخته شده) به بخش [مسائل باز (Issues)](https://github.com/pejmangholami/vlc-web-interface-kishairport/issues) مراجعه کنید.

<!-- CONTRIBUTING -->
## مشارکت در پروژه

مشارکت شما باعث می‌شود جامعه متن‌باز به مکانی شگفت‌انگیز برای یادگیری، الهام‌بخشی و خلق کردن تبدیل شود. هرگونه مشارکت شما **بسیار مورد قدردانی قرار خواهد گرفت**.

1. پروژه را Fork کنید.
2. شاخه ویژگی خود را ایجاد کنید (`git checkout -b feature/AmazingFeature`).
3. تغییرات خود را ثبت کنید (`git commit -m 'Add some AmazingFeature'`).
4. به شاخه خود Push کنید (`git push origin feature/AmazingFeature`).
5. یک Pull Request باز کنید.

<!-- LICENSE -->
## مجوز (License)

تحت مجوز GNU GPL 3.0 توزیع شده است. برای اطلاعات بیشتر فایل `LICENSE` را ببینید.

<!-- CONTACT -->
## تماس

پژمان غلامی - واحد فناوری اطلاعات فرودگاه کیش - pejman.gholami@gmail.com

لینک پروژه: [https://github.com/pejmangholami/vlc-web-interface-kishairport](https://github.com/pejmangholami/vlc-web-interface-kishairport)

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/pejmangholami/vlc-web-interface-kishairport?style=for-the-badge
[contributors-url]: https://github.com/pejmangholami/vlc-web-interface-kishairport/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pejmangholami/vlc-web-interface-kishairport?style=for-the-badge
[forks-url]: https://github.com/pejmangholami/vlc-web-interface-kishairport/network/members
[stars-shield]: https://img.shields.io/github/stars/pejmangholami/vlc-web-interface-kishairport?style=for-the-badge
[stars-url]: https://github.com/pejmangholami/vlc-web-interface-kishairport/stargazers
[issues-shield]: https://img.shields.io/github/issues/pejmangholami/vlc-web-interface-kishairport?style=for-the-badge
[issues-url]: https://github.com/pejmangholami/vlc-web-interface-kishairport/issues
[license-shield]: https://img.shields.io/github/license/pejmangholami/vlc-web-interface-kishairport?style=for-the-badge
[license-url]: https://github.com/pejmangholami/vlc-web-interface-kishairport/blob/main/LICENSE