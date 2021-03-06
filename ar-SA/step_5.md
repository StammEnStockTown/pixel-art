## تلوين وحدات البكسل

يستخدم هذا المشروع ثلاث لغات مختلفة:
- لغة HTML المستخدمة لتنظيم المحتوى
- لغة CSS التي تحدد الأنماط التي سيظهر بها المحتوى
- لغة البرمجة JavaScript التي يمكنك استخدامها لتجعل صفحة الويب تستجيب عندما تتفاعل معها

لنضِف بعض تعليمات JavaScript البرمجية لتلوين وحدة البكسل تلقائيًا عند النقر عليها.

سنُنشئ دالة **function**. تُسمى الدول بكل التعليمات البرمجية التي تنفذ مهمة محددة. ويمكننا **استدعاء** الدالة باسْمِها لتنفيذ التعليمات البرمجية الموضوعة داخلها.

+ داخل الملف `script.js`، أنشئ دالة اسمها `setPixelColour`. ويجب أن تأخذ الدالة `setPixelColour` وحدة بكسل `pixel` كقيمة **إدخال** حتى يمكنها تغيير لون وحدة البكسل هذه.

![Create function](images/create-function.png)

+ أضف هذه التعليمة البرمجية داخل الدالة لتعيين لون الخلفية لوحدة البكسل هذه:

![screenshot](images/pixel-art-set-pixel-colour.png)

لاحظ أن القيمة `backgroundColor` تستخدم التهجِّي الأمريكي للكلمة 'colour'.

في الوقت الحالي، لا يوجد أي تأثير لهذه التعليمة البرمجية.

+ انتقل إلى الملف `index.html` وأضف التعليمة البرمجية الموضحة أدناه إلى وحدة البكسل الأولى بحيث يتم استدعاء الدالة `setPixelColour` عندما تنقر فوق وحدة البكسل هذه:

![screenshot](images/pixel-art-onclick.png)

تمثل الكلمة `this` الموضوعة بين قوسين قيمةَ الإدخال للدالة `setPixelColour`، حيث تحدد لها وحدة البكسل المطلوب تعيين اللون لها — حيث معنى`this` هو (هذه)، أيْ وحدة البكسل هذه!

+ اختبر التعليمة البرمجية بالنقر فوق وحدة البكسل الأولى. سيتحول لونها إلى الأسود.

![screenshot](images/pixel-art-black.png)

لقد أضفتَ التعليمة البرمجية `onclick` إلى وحدة البكسل **الأولى** فقط، لذا عند النقر فوق وحدات البكسل الأخرى، لن تكون هناك أي نتيجة.
