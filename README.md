### برطرف کردن مشکل تست‌ها 
همانطور که در تصویر زیر میبینیم در هنگامی که ورودی اول -1 و ورودی دوم 6 و خروجی 5 است به مشکل خورده ایم:
![Screenshot 2024-08-05 123339](https://github.com/user-attachments/assets/dd9dac2c-6dfe-40be-b836-fdf958a2baa7)

دلیل آن این است که در تابع twoInputValuesAnd در  MyStepdefs.java دو عدد مثبت را وروی گرفته است در حالی که تست ما یک ورودی منفی نیز دارد که باعث ارور و فیل شدن تست شده است.
![image](https://github.com/user-attachments/assets/9d1a8109-fa56-48aa-88e8-dff090e86197)


که (\\d+) یک regex برای اعداد مثبت است.

![image](https://github.com/user-attachments/assets/8a3efb76-734a-40ef-bd93-f422a1a975f7)
رجکس برای تشخیص هم اعداد مثبت و هم منفی به این صورت است.

![image](https://github.com/user-attachments/assets/e6a0058c-f9b4-4f82-b8c0-fb7d00e66c98)

تست ها هم به طور کامل و درست پاس شدند و تست مشکل دار هم اوکی شد.
