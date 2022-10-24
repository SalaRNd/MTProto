# MTProto

ابتدا یک سرور (vps) خارج از کشور تهیه کنید

پیشنهاد بنده خرید سرور از وب سایت آنلاین سرور هست

https://my.onlineserver.ir/aff.php?aff=414

<p><a href="https://my.onlineserver.ir/aff.php?aff=414">
<img src="https://onlineserver.ir/my/banner/Onlineservers-234.gif"></a></p>

 نرم افزار putty را دانلود کنید

https://uploadb.me/direct/cjlbd3c6vuwm/CC_%208.0l.rar.html

با استفاده از کد زیر فایروال را بر روی سرور خود نصب میکنید:

<pre>yum install firewalld</pre>

در صورت روشن نبودن فایروال سرویس میتوانید از کد زیر استفاده بکنید:

<pre>service firewalld start</pre>

نصب اتوماتیک پروکسی MTPtoto:

<pre>ccurl -L -o mtp_install.sh https://git.io/fj5ru && bash mtp_install.sh -p [PORT] -s [SECRET] -t [TAG] -a dd -a tls -d [FAKE TLS]</pre>

بخش های [PORT]، [SECRET]، [TAG] و [FAKE TLS] را مطابق ویدیو یوتیب تکمیل کنید.

با استفاده از لینک زیر میتوانید کد SECRET مخصوص MTProto را دریافت کنید:

http://seriyps.ru/mtpgen.html

با استفاده از لینک زیر (بات تلگرام) میتوانید کد TAG مخصوص MTProto را دریافت کنید:

<a href="MTProxybot">https://t.me/MTProxybot</a>

<h2>بهتر هست قبل از مشاهده ارور Node is not running کانفینگ های زیر را هم انجام دهید:</h2>

با استفاده از کد زیر اقدام به نصب nano کنید:

<pre>yum install nano -y</pre>

سپس کد زیر را وارد نمایید:

<pre>nano /root/mtproto_proxy/config/prod-vm.args</pre>

در انتها کد زیر را وارد نمایید:

<pre>cd /root/mtproto_proxy/;service mtproto-proxy stop;make && sudo make install;service mtproto-proxy restart;</pre>

# root
در تمامی مراحل برای برگشت به بخش root میتوانید از کد زیر استفاده کنید:

<pre>cd</pre>
