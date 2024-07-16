# نصب Rivalz CLI روی اوبونتو
**خیلی ساده Rivalz CLI نصب کنید . این بخش اپدیت شده و بر اساس اخرین تغییرات دایکیومنت Rivalz است**

![image](https://github.com/xONEIROS/Rivalz-CLI/assets/174752031/fa384f7d-3fcc-45a0-b940-c75ffa70c089)



## مرحله 1: آماده‌سازی سرور

اول از همه، سرورتون رو آپدیت کنین:

```bash
apt update && apt upgrade -y
```

حالا تابع curl رو نصب می‌کنیم:

```bash
apt install curl
```
![image](https://github.com/xONEIROS/Rivalz-CLI/assets/174752031/5156f5b3-e96d-417a-ae82-08e0346f9e9f)

رایوالز به نسخه 20 از Node.js نیاز داره، پس از مخزن نصبش می‌کنیم:

```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```

بعد بسته Node.js رو نصب می‌کنیم:

```bash
apt install -y nodejs
```

با این دستور می‌تونید نسخه Node.js نصب شده رو چک کنید:

```bash
nodejs -v
```

حالا وقتشه خود Rivalz رو نصب کنیم:

```bash
npm i -g rivalz-node-cli
```

## مرحله 2: اجرای Rivalz

برای نصب و اجرای Rivalz، اسکرین رو نصب می‌کنیم:

```bash
apt install screen
```

یه اسکرین جدید باز می‌کنیم:

```bash
screen -S rivalz
```

حالا به ترتیب دو دستور زیر رو اجرا می‌کنیم:
```
rivalz update-version
```
```bash
rivalz run
```
![image](https://github.com/xONEIROS/Rivalz-CLI/assets/174752031/c9de2510-ab6e-4e6f-81a5-0072cb788131)


در این مرحله، اطلاعات خواسته شده رو وارد کنید:
1. آدرس ولتتون
2. مقدار پردازشگر (CPU) که می‌خواین درگیر بشه
3. مقدار RAM
4. نوع هاردتون رو انتخاب کنید
5. سریال هارد رو فقط با زدن Enter انتخاب کنید
6. مقدار هاردی که می‌خواین اختصاص بدین

** اگر نصب براتون موفق باشه پیامی مثل پیام زیر میبینید**
![image](https://github.com/xONEIROS/Rivalz-CLI/assets/174752031/6475bd17-c4e3-415c-99bb-9e3f609029e3)


<div align="center">
    <p>
        <a href="Https://x.com/0xOneiros">
            <small>twitter</small>  
        </a>
        | 
        <a href="Https://t.me/xOneiros">
            <small>telegram</small>  
        </a>
    </p>
</div>
