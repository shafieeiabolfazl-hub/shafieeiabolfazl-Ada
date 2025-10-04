# shafieeiabolfazl-Ada
# Ada Learning Repository | ریپازیتوری یادگیری آدا

Welcome to my Ada programming repository. I'm Abolfazl Shafiei, and this space is dedicated to my journey of learning the Ada language. Here you'll find my practice codes, experiments, and step-by-step progress as I explore this powerful and precise language.

به ریپازیتوری برنامه‌نویسی آدا خوش آمدید. من ابوالفضل شفیعی هستم و این بخش به مسیر یادگیری من در زبان آدا اختصاص دارد. در اینجا کدهای تمرینی، آزمایش‌ها و پیشرفت مرحله‌به‌مرحله من را خواهید دید در حین کشف این زبان قدرتمند و دقیق.

---

## 📌 Contents | محتوای ریپازیتوری

- `hello_world.adb`: First steps with Ada syntax  
- `variables.adb`: Declaring and using variables  
- `loops.adb`: Loop structures and iteration  
- `procedures.adb`: Writing and calling procedures  
- `records.adb`: Structuring data with records  

- `hello_world.adb`: اولین قدم‌ها با نحو آدا  
- `variables.adb`: تعریف و استفاده از متغیرها  
- `loops.adb`: ساختارهای حلقه و تکرار  
- `procedures.adb`: نوشتن و فراخوانی پروسیجرها  
- `records.adb`: ساختاردهی داده‌ها با رکوردها  

---

## 🎯 Purpose | هدف

- Learn Ada through hands-on coding  
- Document my progress and share insights  
- Build a foundation for future embedded or secure systems

- یادگیری آدا با کدنویسی عملی  
- مستندسازی پیشرفت و اشتراک‌گذاری نکات  
- ساخت پایه‌ای برای پروژه‌های نهفته یا امنیتی آینده  

---

## 🛠️ Setup | تنظیمات

- Compiler: GNAT (AdaCore)  
- IDE: VS Code with Ada extension  
- OS: Windows 11

- کامپایلر: GNAT (از AdaCore)  
- محیط توسعه: VS Code با افزونه آدا  
- سیستم‌عامل: ویندوز ۱۱  

---

## 📚 License | مجوز

🧠 Code Explanation: Greeting_With_If.adb
✍️ توضیح کد: Greeting_With_If.adb
<img width="1461" height="712" alt="1" src="https://github.com/user-attachments/assets/07d152ae-2e7f-493b-9deb-59792bb5b16c" />
<img width="652" height="662" alt="2" src="https://github.com/user-attachments/assets/8d351f00-d94b-4c77-bf69-0c96f2ab548d" />

### 🇬🇧 English Description

This Ada program demonstrates basic input/output and conditional logic. It starts by greeting the user and asking for their name and age. Based on the age entered, it responds with a personalized message:

- If the user is under 18 → "You are very young for my test"
- If the user is between 18 and 21 → "You are good for my test"
- Otherwise → "You are old for my test"

The code uses:
- `Put_Line` and `Put` for output
- `Get_Line` and `Get` for input
- `if`, `elsif`, and `else` for conditional branching

This is a great first step in mastering Ada’s control structures and user interaction.

---

### 🇮🇷 توضیح فارسی

این برنامه‌ی آدا، نمونه‌ای ساده از ورودی/خروجی و شرط‌گذاری است. ابتدا کاربر را خوش‌آمد می‌گوید، سپس نام و سن او را دریافت می‌کند. بر اساس سن وارد شده، پیام شخصی‌سازی‌شده‌ای نمایش می‌دهد:

- اگر سن کمتر از ۱۸ باشد → "برای آزمون من خیلی جوانی"
- اگر سن بین ۱۸ تا ۲۱ باشد → "برای آزمون من مناسبی"
- در غیر این صورت → "برای آزمون من مسنی"

در این کد از موارد زیر استفاده شده:
- `Put_Line` و `Put` برای چاپ خروجی  
- `Get_Line` و `Get` برای دریافت ورودی  
- ساختارهای شرطی `if`, `elsif`, و `else` برای تصمیم‌گیری  

این کد قدمی عالی برای یادگیری ساختارهای کنترلی و تعامل با کاربر در زبان آداست.

_________________________________________________________________________________________________________________________________________

📝 گزارش امروز – Example_Variables (فارسی / انگلیسی)
1️⃣ تاریخ و موضوع

تاریخ: 4 مهر 1404 (مطابق با تاریخ سیستم)
موضوع: تمرین برنامه‌نویسی Ada – مفاهیم پایه (Put, Put_Line, Get, Get_Line, شرط‌ها، حلقه‌ها، متغیرها، مدیریت رشته‌ها)

2️⃣ کاری که انجام شد
فارسی:

نوشتن برنامه‌ای برای گرفتن اسم و سن کاربر

تعیین سطح کاربر بر اساس سن (Child, Teenager, Adult)

پرسش از کاربر برای شرکت در مسابقه

چاپ پیام خوشامد در حلقه ۳ بار

تمرین استفاده از متغیرها و رشته‌ها و رفع خطای Constraint_Error

مرور و تثبیت مفاهیم پایه Ada مثل Put, Put_Line, New_Line, Get, Get_Line, if / elsif / else, for loop

English:

Developed a program to get user’s name and age

Determined user level based on age (Child, Teenager, Adult)

Asked user if they want to participate in a contest

Printed a welcome message 3 times in a loop

Practiced variables and string handling and resolved Constraint_Error

Reviewed and reinforced basic Ada concepts: Put, Put_Line, New_Line, Get, Get_Line, if / elsif / else, for loop

3️⃣ کد اجرا شده
with Ada.Text_IO; use Ada.Text_IO;
with Ada.Integer_Text_IO; use Ada.Integer_Text_IO;

procedure Example_Variables is
   Name : String(1..20);
   Last : Natural;
   Age : Integer;
   Answer : String(1..20);
   Ans_Last : Natural;
   Level : String(1..12);
begin
   Put_Line("Welcome to my contest");
   New_Line;

   Put("What's your name baby? ");
   Get_Line(Name, Last);

   Put("How old Are you? ");
   Get(Age);

   if Age < 12 then
      Level := (others => ' ');
      Level(1..5) := "Child";
   elsif (Age >= 12) and (Age < 23) then
      Level := (others => ' ');
      Level(1..8) := "Teenager";
   else
      Level := (others => ' ');
      Level(1..5) := "Adult";
   end if;

   New_Line;
   Put_Line("Hello, " & Name(1..Last) & "!");
   Put_Line("You are " & Integer'Image(Age) & " years old");
   Put_Line("Your Level: " & Level);
   New_Line;

   Put("Do you want to join the contest? (yes/no): ");
   Get_Line(Answer, Ans_Last);

   if Answer(1..Ans_Last) = "yes" then
      Put_Line("Great! Let's start");
      New_Line;
      for I in 1..3 loop
         Put_Line("Welcome " & Name(1..Last) & " to round " & Integer'Image(I));
      end loop;
   else
      Put_Line("Maybe next time!");
   end if;

   New_Line;
   Put_Line("Thanks for using my program. Goodbye!");
end Example_Variables;

4️⃣ نمونه خروجی
Welcome to my contest

What's your name baby? Abolfazl
How old Are you? 12

Hello, Abolfazl!
You are 12 years old
Your Level: Teenager

Do you want to join the contest? (yes/no): yes
Great! Let's start

Welcome Abolfazl to round 1
Welcome Abolfazl to round 2
Welcome Abolfazl to round 3

Thanks for using my program. Goodbye!

5️⃣ یادگیری‌ها
فارسی:

مدیریت ورودی/خروجی با Get و Get_Line

چاپ با Put, Put_Line, New_Line

شرط‌ها (if/elsif/else)

حلقه‌ها (for loop)

رفع خطای طول رشته (Constraint_Error) با روش (others => ' ') و بخش‌بندی رشته

تسلط بیشتر روی مفاهیم پایه Ada

English:

Handling input/output using Get and Get_Line

Printing with Put, Put_Line, New_Line

Conditional statements (if/elsif/else)

Loops (for loop)

Resolved string length issues (Constraint_Error) using (others => ' ') and substring assignment

Strengthened understanding of core Ada concepts
<img width="751" height="682" alt="1" src="https://github.com/user-attachments/assets/d426d100-2bbe-4a05-a5bf-1e850c267215" />
<img width="1020" height="456" alt="2" src="https://github.com/user-attachments/assets/351b9d3a-eb2c-4b69-9415-d1759b02aac6" />
