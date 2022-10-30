# MTProto

ابتدا یک سرور (vps) خارج از کشور تهیه کنید

پیشنهاد بنده <a href="https://my.onlineserver.ir/aff.php?aff=414" target="_blank">خرید سرور مجازی (VPS)</a>  از وب سایت آنلاین سرور هست.

البته الان خدماتی ارائه نمیدن و نمیتوانید سرور vps داخل یا خارج کشور از سایت میزبان داده پاسارگاد تهیه کنید،
به همین علت بهتر هست از وب سایتی که لینکش را در پایین قرار داده ام، با استفاده از ارز دیجیتال یک vps تهیه بکنید.

همچنین میتوانید از <a href="https://support.cloudzy.com/aff.php?aff=1557" target="_blank">اینجا سرور مجازی  (VPS) با ارز دیجیتال</a> بخرید. (با فیلتر شکن وارد لینک شوید)

 نرم افزار <a href="https://uploadb.me/direct/cjlbd3c6vuwm/CC_%208.0l.rar.html" target="_blank"> PUTTY </a> را دانلود کنید

با استفاده از کد زیر فایروال را بر روی سرور خود نصب میکنید:

<pre>yum install firewalld</pre>

در صورت روشن نبودن فایروال سرویس میتوانید از کد زیر استفاده بکنید:

<pre>service firewalld start</pre>

نصب اتوماتیک پروکسی MTPtoto:

<pre>curl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh -p [PORT] -s [SECRET] -t [TAG] -a dd -a tls -d [FAKE TLS]</pre>

بخش های [PORT]، [SECRET]، [TAG] و [FAKE TLS] را مطابق ویدیو یوتیب تکمیل کنید.

با استفاده از لینک زیر میتوانید کد SECRET مخصوص MTProto را دریافت کنید:

<a href="http://seriyps.ru/mtpgen.html" target="_blank">دریافت SECRET کد مخصوص پروکسی </a>

با استفاده از لینک زیر (بات تلگرام) میتوانید کد TAG مخصوص MTProto را دریافت کنید:

<a href="https://t.me/MTProxybot" target="_blank">دریافت کد TAG از بات تلگرام MTProto</a>

<h3>بهتر هست قبل از مشاهده ارور Node is not running کانفینگ های زیر را هم انجام دهید:</h3>

با استفاده از کد زیر اقدام به نصب nano کنید:

<pre>yum install nano -y</pre>

سپس کد زیر را وارد نمایید:

<pre>nano /root/mtproto_proxy/config/prod-vm.args</pre>

در انتها کد زیر را وارد نمایید:

<pre>cd /root/mtproto_proxy/;service mtproto-proxy stop;make && sudo make install;service mtproto-proxy restart;</pre>

# root
در تمامی مراحل برای برگشت به بخش root میتوانید از کد زیر استفاده کنید:

<pre>cd</pre>
