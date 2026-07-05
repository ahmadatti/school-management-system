School Management System - (MIS Department Project)

وصف المشروع (Project Description)
نظام إدارة مدرسة متكامل يعتمد على تقنيات الويب (PHP & MySQL)، يهدف إلى أتمتة العمليات الإدارية المتعلقة بالطلاب، المعلمين، والمواد الدراسية. يوفر النظام لوحة تحكم للمسؤول لإدارة قاعدة البيانات وضمان سير العمل الأكاديمي بكفاءة.

فكرة المشروع (Project Concept)
فكرة المشروع تقوم على حل المشاكل الإدارية التقليدية في المدارس من خلال التحول الرقمي. يتيح النظام إضافة، عرض، تعديل، وحذف بيانات الطلاب والمعلمين (CRUD Operations)، مما يقلل من الأخطاء البشرية ويسهل الوصول إلى البيانات بشكل فوري وآمن.

المتطلبات التقنية (Tech Stack)
• Backend: PHP
• Database: MySQL (phpMyAdmin)
• Frontend: HTML/CSS (Bootstrap)
• Server: XAMPP

الجداول المستخدمة (Database Structure)
يتكون النظام من 5 جداول رئيسية لضمان تنظيم البيانات:
1. users: لتخزين بيانات المستخدمين وصلاحياتهم.
2. students: لتخزين بيانات الطلاب.
3. teachers: لتخزين بيانات المعلمين.
4. subjects: لتخزين المواد الدراسية.
5. classes: لتخزين بيانات الفصول.

طريقة التشغيل (How to Run)
1. تأكد من تثبيت وتشغيل XAMPP (Apache & MySQL).
انشأ ملف داخل htdocs وقم بتسميته school-management
2. قم بنقل مجلد المشروع إلى المسار: C:\xampp\htdocs\school-management
3. افتح phpMyAdmin وأنشئ قاعدة بيانات باسم (school_db).
4. قم باستيراد ملف قاعدة البياناتC:\xampp\htdocs\school-management\database.sql\database.sql الموجود داخل مجلد المشروع.
5. افتح المتصفح وتوجه إلى الرابط: http://localhost/school-management/login.php

بيانات تسجيل الدخول (Login Credentials)
• اسم المستخدم (Username): admin
• كلمة المرور (Password): 123456

ملاحظات الأمان
• تم استخدام تقنيات (Prepared Statements) لمنع هجمات SQL Injection.
• تم تفعيل جلسات العمل (Sessions) لضمان حماية الصفحات.
• تم تشفير كلمات المرور لزيادة مستوى أمان النظام.

───

إعداد الطالب: [أاحمد عوض عبد العاطي1320226637]


تخصص: نظم معلومات إدارية (Management Information Systems)
