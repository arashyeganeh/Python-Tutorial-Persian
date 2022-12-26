# فصل 3. سلام دنیای ...

اجرای دستورات، به 2 روش امکان پذیر می باشد :

<ul dir="rtl">
	<li>
	Interactive Mode
	</li>
	<li>
	Script Mode
	</li>
</ul>

## تعاملی ( Interactive Mode )

در این روش، دستورات خط به خط مستقیم درون مفسر ( interpreter ) تایپ می کنیم. این قابلیت به کمک ابزاری به نام Integrated Development and  Learning Environment یا به اختصار **IDLE** امکان پذیر می شود. برای دسترسی به محیط IDLE در سیستم عامل های مختلف مراحل ذیل انجام می دهیم :

> این روش، باتوجه به دشواری و محدودیت هایی که دارد به جزء موارد خاصی، توصیه نمی شود. ( بیشتر برای اجرای دستورات بدون نصب IDE در محیط هایی که از نظر امنیتی دارای حساسیت می باشند مثل سرورها، کاربرد دارد. )

### ویندوز

#### محیط ترمینال - بدون رابط گرافیکی

<ol dir="rtl">
<li>
	<p>
	پنجره ترمینال باز می کنیم :
	</p>
	<ul dir="rtl">
		<li>
			<p>
				روش اول : در جستجوی ویندوز عبارت Terminal جستجو می کنیم.
			</p>
		</li>
		<li>
			<p>
				روش دوم : با کلیدهای ترکیبی <kbd>Windows Key</kbd> + <kbd>R</kbd> پنجره Run باز می شود سپس عبارت cmd تایپ، سپس اجرا می کنیم.
			</p>
		</li>
	</ul>
</li>
<li>
	<p>
		عبارت "python" در محیط ترمینال اجرا می کنیم.
	</p>
	<div dir="ltr" align="left">
		<pre><code>python</code></pre>
	</div>
	<p>
		<<< این علامت محل ورود دستورات نمایش می دهد.این دستورات بصورت مستقیم درون مفسر اجرا می شود. برای مثال می خواهیم عبارت "Hello" در خروجی نمایش دهیم :
	</p>
	<div dir="ltr" align="left">
		<pre><code>print("Hello")</code></pre>
	</div>
</li>
</ol> 

![win_terminal_hello](img/win_terminal_hello.PNG)

#### برنامه IDLE Shell - محیط گرافیکی

این برنامه در زمان نصب پایتون به صورت خودکار نصب می شود. فقط کافیست عبارت IDLE در جستجوی ویندوز وارد کنید.

![windows-idle-gui](img/win_idle_gui.PNG)

به کمک برنامه IDLE در محیط گرافیکی امکاناتی از جمله دیباگ کردن، اضافه کردن فایل های خارجی، ذخیره کردن دستورات و ... نسبت به محیط ترمینال دارید.

### لینوکس

#### محیط ترمینال - بدون رابط گرافیکی

<ol dir="rtl">
<li>
	<p>
	پنجره ترمینال باز می کنیم.
	</p>
</li>
<li>
	<p>
	عبارت "python" در محیط ترمینال اجرا می کنیم.
	</p>
	<div dir="ltr" align="left">
		<pre><code>python</code></pre>
	</div>
	<p>
	<<< این علامت محل ورود دستورات نمایش می دهد.این دستورات بصورت مستقیم درون مفسر اجرا می شود. برای مثال می خواهیم عبارت "Hello" در خروجی نمایش دهیم :
	</p>
	<div dir="ltr" align="left">
		<pre><code>print("Hello")</code></pre>
	</div>
</li>
</ol>


![ubuntu_python_hello](img/ubuntu_python_hello.PNG)

#### برنامه IDLE Shell - محیط گرافیکی

<ol dir="rtl">
	<li>
		<p>
		پنجره ترمینال باز می کنیم.
		</p>
	</li>
	<li>
		<p>
		برنامه "idle" نصب می کنیم.
		</p>
		<ul dir="rtl">
			<li>
				<p>
					در صورتیکه سیستم عامل اوبونتو / دبیان باشد :
				</p>
				<div dir="ltr" align="left">
					<pre><code>sudo apt-get install idle</code></pre>
				</div>
			</li>
			<li>
				<p>
					در صورتیکه سیستم عامل فدورا / سنت او اس باشد :
				</p>
				<div dir="ltr" align="left">
					<pre><code>sudo dnf install idle</code></pre>
				</div>
			</li>
		</ul>
	</li>
	<li>
		<p>
            با توجه به نسخه ای که نصب می کنید، شماره نسخه ای که باید در انتهای "idle" بنویسیم متفاوت می باشد.عبارت "idle" تایپ می کنیم، سپس 2 بار کلید tab فشار می دهیم. با اینکار دستورات پیشنهادی که با عبارت "idle" شروع می شوند نمایش می دهد سپس عدد نسخه موردنظر وارد می کنیم.
        </p>
		<div dir="ltr" align="left">
			<pre><code>idle3.11</code></pre>
		</div>
	</li>
</ol>


![ubuntu_idle_terminal](img/ubuntu_idle_terminal.PNG)

![ubuntu_idle_window](img/ubuntu_idle_window.PNG)

### خروج از محیط IDLE بدون بستن پنجره ترمینال

![windows-idle-terminal](img/win_idle_terminal.PNG)

برای خروج از محیط IDLE بدون بستن پنجره ترمینال، 3 روش ذیل قابل اجرا می باشد. دستورات ذیل مقابل <<< وارد کنید : 

<ul dir="rtl">
	<li>
		<p>
		روش اول : تابع quit صدا بزنیم.
		</p>
		<div dir="ltr" align="left">
			<pre><code>quit()</code></pre>
		</div>
	</li>
	<li>
		<p>
		روش دوم : تابع exit صدا بزنیم.
		</p>
		<div dir="ltr" align="left">
			<pre><code>exit()</code></pre>
		</div>
	</li>
	<li>
		<p>
		روش سوم : کلید ترکیبی <kbd>Ctrl</kbd>+<kbd>z</kbd> فشار میدیم، سپس enter وارد کنیم.
		</p>
		<div dir="ltr" align="left">
			<pre><code>^Z</code></pre>
		</div>
	</li>
</ul>


## اسکریپت ( Script Mode )

این روش برخلاف روش تعاملی ( Interactive Mode )، دستورات درون یک فایل با پسوند py ذخیره می کنیم، سپس فایل در محیط ترمینال اجرا می کنیم.

### ویرایشگر فایل

می خواهیم عبارت "hello" در خروجی نمایش داده شود :

<ol dir="rtl">
	<li>
		<p>
		برنامه ویرایشگر متن باز می کنیم
		</p>
	</li>
	<li>
		<p>
		دستور ذیل تایپ می کنیم.
		</p>
		<div dir="ltr" align="left">
			<pre><code>print("Hello")</code></pre>
		</div>
	</li>
	<li>
		<p>
		فایل به نام hello.py ذخیره می کنیم. ( پسوند py ذخیره بشه )
		</p>
	</li>
	<li>
		<p>
		وارد محیط ترمینال می شویم. آدرس جاری ترمینال به محل ذخیره شده فایل hello.py جا به جا می کنیم.
		</p>
	</li>
	<li>
		<p>
		با دستور ذیل فایل hello.py اجرا می کنیم.
		</p>
		<div dir="ltr" align="left">
			<pre><code>python hello.py</code></pre>
		</div>
	</li>
</ol>

![windows-hello.py](img/win_python_hello.PNG)

### استفاده از برنامه های IDE - ( بهترین روش )

بهترین روش برای برنامه نویسی استفاده از برنامه های  IDE ( Integrated development environment )می باشد. این دسته از برنامه ها قابلیت هایی بسیار فراتر از روش IDLE و برنامه های ویرایشگر متن به شما می دهند. از جمله قابلیت های IDE می توان به موارد ذیل اشاره کرد : 

* رعایت عمق ها و مرتب کردن دستورات و دادن استایل رنگی ( در خوانایی کد بسیار موثر هست )
* ابزار های دیباگ ( عیب یابی )
* اتصال به سایر برنامه ها ( مثل گیت )
* و ....



------

👋 Hi, I’m Arash Yeganeh.

How can you best ❤️ **Support me** ❤️  :

- Give me  [GitHub Stars ⭐](https://github.com/arashyeganeh) 
- Share my content to someone else 👀
- Follow me on [linkedin](https://www.linkedin.com/in/arash-yeganeh)
- Subscribe my [YouTube](https://www.youtube.com/channel/UCUuojnAmPiklBpAeBmHE4Aw) channel
