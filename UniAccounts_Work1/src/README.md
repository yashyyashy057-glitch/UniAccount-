# UniAccounts - Work 1

هذا المشروع يمثل أول عمل تطبيقي لمقياس أنماط التصميم (Design Patterns).

## الأنماط المستخدمة (Patterns used)

1. البناء (Builder)
   - يُستخدم لبناء كائن حساب الطالب (StudentAccount).
   - الحقول الإلزامية: المعرف (id)، الاسم الكامل (fullName)، البريد الإلكتروني (email).
   - الحقول الاختيارية لها القيم الافتراضية المطلوبة.

2. النسخة الوحيدة (Singleton)
   - StudentRepository: مستودع مركزي واحد.
   - AuditLogger: سجل تدقيق واحد مشترَك.

3. النموذج الأولي (Prototype)
   - StudentAccount.copyWithNewIdentity(...) لإنشاء حساب جديد عن طريق نسخ حساب موجود وتغيير هوية الطالب.

## كيفية التشغيل (How to run)

افتح مجلد src في برنامج VS Code.

للترجمة (Compile):

`bash
javac src/*.java
للتشغيل (Run):
java -cp src Main
الملفات (Files)
StudentAccount.java
StudentRepository.java
AuditLogger.java
Main.java
يحتوي الكود على تعليقات توضح أنماط التصميم المستخدمة وأدوارها.
