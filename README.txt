
تعليمات إعداد Supabase:

1. أنشئ جدول patients يحتوي:
   - id (PK - auto increment)
   - full_name, birth_date, age, phone, notes, treatment, face_subtype, start_date, before_image_url

2. أنشئ جدول sessions يحتوي:
   - id, patient_id, session_date, doctor_notes, after_image_url

3. أنشئ bucket باسم: patients-images

4. لتشغيل الموقع:
   - افتح index.html باستخدام Python أو GitHub Pages
