### نحوه اجرا در pycharm

#تنظیم  interupter
#PyCharm > Settings > Project > Python Interpreter
#یک Interpreter معتبر (Python 3.x) انتخاب/اضافه کنید.

##ساخت Run/Debug Configuration
#از بالا سمت راست روی Add Configuration کلیک کنید.
#Script path: مسیر فایل main.py پروژه‌ را بدهید.
#Parameters: این را وارد کنید:
examples\obfuscated.mc -o examples\roundtrip.mc
#Working directory: مسیر ریشه پروژه‌ (همان پوشه‌ای که main.py داخلش است).
#Python interpreter: همان Interpreter مرحله قبل.

##اجرا
#از منوی کشویی Run همان کانفیگ را انتخاب کنید و Run را بزنید.
#خروجی فایل در examples\roundtrip.mc تولید می‌شود.
