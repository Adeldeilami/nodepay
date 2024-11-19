# Nodepay.ai
![Nodepay.ai](image.png)
پینگ خودکار ربات Nodepay.ai با استفاده از چندین پروکسی

ثبت نام در Nodepay.ai : [https://app.nodepay.ai/register](https://app.nodepay.ai/register?ref=8YKFpuUnwn1QiFe)

# Features
این اسکریپت برای اجرا بر روی سرور با استفاده از چندین پروکسی در نظر گرفته شده است.
## Update 
- هر حساب فقط می تواند 10 پروکسی را متصل کند
- بنابراین بهترین راه برای کشاورزی در حال حاضر ایجاد چندین حساب کاربری است
- اسکریپت از چندین حساب پشتیبانی می کند فقط رمز "np_tokens.txt" را برای هر خط برای 1 حساب جایگذاری کنید
- مطمئن شوید که حساب شما نشان **Proof of Humanhood** را دریافت کرده است
- Register here [https://app.nodepay.ai/](https://app.nodepay.ai/register?ref=8YKFpuUnwn1QiFe)
  
![image](https://github.com/user-attachments/assets/6b77e7e9-7fcc-4de0-b026-ca3d1a40146e)

## اطلاعات مورد نیاز را بدست آورید

1. لینک را باز کنید و وارد شوید [https://app.nodepay.ai/](https://app.nodepay.ai/register?ref=8YKFpuUnwn1QiFe)
2. F12 را فشار دهید تا کنسول باز شود و کد را وارد کنید (Ctrl + Shift + i for inspection)
3. In the console, enter ``localStorage.getItem('np_token');``
4. The text printed in the console is your NP_TOKEN copy and paste to `np_token.txt`
5. put your proxy in `proxy.txt` file ex: `http://username:pass@ip:port`

## 1. Steps to Run the Code
```bash
git clone https://github.com/Zlkcyber/nodepay.git
cd nodepay
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```
## 3. Run The Script
```bash
python3 main.py
```
## Expected Output
If running correctly, you will see logs like the following:
```bash
2024-07-30 04:37:18.263 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 88}}
2024-07-30 04:37:48.621 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 90}}
2024-07-30 04:38:18.968 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 94}}
2024-07-30 04:38:59.338 | Ping successful: {'success': True, 'code': 0, 'msg': 'Success', 'data': {'ip_score': 98}}

```
