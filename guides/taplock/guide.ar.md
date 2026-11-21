---
title: قفل الشاشة بلمسة واحدة
name: TapLock
tagline: اقفل هاتفك بلمسة واحدة، مع بقاء فتح القفل ببصمة الإصبع أو الوجه.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## ماذا يفعل التطبيق

يضع TapLock زرًّا كبيرًا واحدًا باسم **Lock** على شاشتك. المسه فيُقفل هاتفك فورًا، تمامًا كما لو ضغطت زر التشغيل. وهو مفيد عندما يصعب الوصول إلى زر التشغيل أو يكون متآكلًا أو معطلًا.

- مع قفل Accessibility تفتح الهاتف كالمعتاد ببصمة الإصبع أو الوجه أو رمز PIN أو النمط.
- قفل Device Admin طريقة ثانية للقفل تعمل دون Accessibility.
- شاشة واحدة وزر واحد. بلا حساب وبلا تسجيل دخول.
- مجاني مع إعلانات.

## البدء

1. افتح TapLock. في أول مرة يظهر تحت الزر **Lock** السطر "One-time setup needed (about a minute)."
2. المس **Set up TapLock**. تفتح شاشة **Lock setup**.
3. اختر إحدى طريقتي القفل:
   - **Accessibility lock** (موصى بها، لنظام Android 9 أو أحدث): تقفل مثل زر التشغيل، ويبقى فتح القفل ببصمة الإصبع أو الوجه يعمل.
   - **Device Admin lock**: تعمل دون Accessibility. يطلب Android رمز PIN أو النمط أو كلمة المرور في المرة التالية التي تفتح فيها الهاتف.
4. اتبع الخطوات الخاصة باختيارك أدناه.

يمكنك فتح **Lock setup** مرة أخرى في أي وقت من أيقونة الإعدادات في أعلى يمين الشاشة الرئيسية.

## تفعيل قفل Accessibility

1. في **Lock setup**، من بطاقة **Accessibility lock**، المس **Turn on Accessibility lock**.
2. يظهر مربع حوار بعنوان **Allow TapLock to use Accessibility?** اقرأ كيف يستخدمها TapLock.
3. المس **Agree** للمتابعة. إذا المست **Decline** فلن يتغير شيء ويبقى قفل Accessibility متوقفًا.
4. تفتح إعدادات Accessibility في Android. ابحث عن TapLock، وغالبًا تجده ضمن "Downloaded apps".
5. فعّل "Use TapLock"، ثم المس **Allow**، ثم ارجع إلى TapLock.
6. تعرض البطاقة الآن **On**، وتظهر **You're all set** في الأعلى. المس **Back to Lock**.

![مربع الحوار "Allow TapLock to use Accessibility?" مع زرّي Decline وAgree](shots/04-accessibility-consent.png)

**لماذا يطلب TapLock إذن Accessibility؟** يستخدم TapLock واجهة Accessibility Service API لقفل شاشتك فقط عندما تلمس الزر **Lock**، كما لو ضغطت زر التشغيل. ولهذا يبقى فتح القفل ببصمة الإصبع أو الوجه يعمل. لا يقرأ TapLock شاشتك، ولا يرى ما تكتبه، ولا يجمع أي بيانات شخصية أو يخزنها أو يشاركها عبر هذا الإذن. أنت تختار **Agree** أو **Decline** قبل أن تفتح إعدادات Android، ويمكنك إيقافه في أي وقت.

إذا بقيت البطاقة تعرض **Starting** أكثر من بضع ثوانٍ، فأوقف TapLock ثم شغّله من جديد في إعدادات Accessibility. وإذا كان المفتاح في إعدادات Android باهتًا ولا يمكن تغييره، فالمس **Switch greyed out?** في **Lock setup** واتبع الإرشاد الظاهر هناك.

## استخدام قفل Device Admin بدلًا منه

1. في **Lock setup**، من بطاقة **Device Admin lock**، المس **Enable Device Admin**.
2. يطلب منك Android التأكيد. يستخدم TapLock هذا الإذن فقط لقفل الشاشة عندما تلمس الزر **Lock**.
3. تعرض البطاقة الآن **On**.

![شاشة Lock setup: بطاقة Accessibility lock تعرض On، وبطاقة Device Admin lock فيها الزر Enable Device Admin](shots/02-setup.png)

مع هذه الطريقة يطلب Android رمز PIN أو النمط أو كلمة المرور في المرة التالية التي تفتح فيها الهاتف، بدل البصمة أو الوجه. وإذا كانت الطريقتان مفعّلتين، يستخدم TapLock قفل Accessibility.

## قفل الشاشة

1. افتح TapLock. يبدأ السطر الذي تحت الزر بكلمة "Ready."
2. المس **Lock**. تُقفل الشاشة فورًا.
3. افتح هاتفك كما تفعل دائمًا.

![الشاشة الرئيسية مع الزر الدائري Lock والسطر "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## استخدام الوضع الداكن

1. فعّل المظهر الداكن من إعدادات Android في هاتفك.
2. افتح TapLock. يتبع التطبيق إعداد هاتفك ويتحول إلى الوضع الداكن تلقائيًا. لا يوجد إعداد منفصل داخل التطبيق.

![الشاشة الرئيسية في TapLock بالوضع الداكن](shots/03-dark-mode.png)

## تغيير اللغة

1. في الشاشة الرئيسية، المس أيقونة الإعدادات لفتح **Lock setup**.
2. افتح قائمة اختيار اللغة.
3. اختر لغة من 31 لغة، أو أبقِ الإعداد الافتراضي للنظام ليتبع TapLock لغة هاتفك.

![قائمة اختيار اللغة مع قائمة اللغات](shots/06-language.png)

تُعرض العربية والأردية والعبرية من اليمين إلى اليسار. وفي Android 13 أو أحدث يمكنك أيضًا تغيير لغة TapLock من إعدادات لغة التطبيقات في Android.

## إيقاف طريقة قفل أو إلغاء تثبيت التطبيق

1. في الشاشة الرئيسية، المس أيقونة الإعدادات لفتح **Lock setup**.
2. لإيقاف قفل Accessibility، المس **Manage in Accessibility settings** وأوقف TapLock هناك.
3. لإيقاف قفل Device Admin، المس **Turn off Device Admin**.
4. أوقف Device Admin قبل إلغاء تثبيت TapLock. لا يسمح Android بإلغاء تثبيت تطبيق ما دام مفعّلًا كمسؤول للجهاز.

![شاشة Lock setup مع بطاقة "You're all set" وزر إيقاف Device Admin](shots/05-device-admin-on.png)

## أسئلة شائعة

**لماذا يحتاج TapLock إلى إذن Accessibility؟**
لقفل الشاشة فقط عندما تلمس **Lock**، كما لو ضغطت زر التشغيل. فهو لا يقرأ شاشتك ولا يرى ما تكتبه. وإذا فضّلت ألا تمنحه هذا الإذن، فاستخدم قفل Device Admin.

**لا تعمل بصمتي بعد القفل عبر TapLock. لماذا؟**
أنت تستخدم قفل Device Admin، وهو يجعل Android يطلب رمز PIN أو النمط أو كلمة المرور مرة واحدة. فعّل قفل Accessibility ليبقى فتح القفل بالبصمة أو الوجه يعمل.

**لا أستطيع إلغاء تثبيت TapLock. ماذا أفعل؟**
افتح **Lock setup** والمس **Turn off Device Admin**، ثم ألغِ التثبيت.

**ما إصدار Android الذي أحتاج إليه؟**
يحتاج قفل Accessibility إلى Android 9 أو أحدث. في الإصدارات الأقدم استخدم قفل Device Admin.

**هل يمكنني استخدام TapLock بلغتي؟**
نعم. يتوفر TapLock بـ 31 لغة. اختر لغتك من **Lock setup**، أو أبقِ الإعداد الافتراضي للنظام.

## الخصوصية

يستخدم TapLock إذني Accessibility وDevice Admin لقفل شاشتك فقط، ولا يجمع أي بيانات شخصية عبرهما. يعرض التطبيق إعلانات من Google AdMob، ومتى كان ذلك مطلوبًا يمكنك تغيير خيارات الإعلانات من **Privacy settings** في **Lock setup**. اقرأ [سياسة الخصوصية](https://varian1.github.io/LockAppOnlyWeb/privacy.html) كاملة.
