## إنشاء شبكة من وحدات البكسل

لننشئ شبكة من وحدات البكسل التي يمكنك استخدامها لإنشاء فن البكسل.

ستأخذ الشبكة شكل جدول من صفوف وأعمدة مكونة من خلايا تمثل وحدات البكسل.

+ افتح [مشروع البدء على trinket](http://jumpto.cc/web-pixel).

سيكون المشروع بالشكل التالي:

![screenshot](images/pixel-starter.png)

لنكتب أولًا بعض التعليمات البرمجية لإنشاء جدول ذي خلفية سوداء ثم نضع فيه وحدات بكسل بيضاء.

+ أضف هذه التعليمة البرمجية داخل وسم `<body>` في الملف `index.html` لإنشاء وسم `<div>`:

![screenshot](images/pixel-art-art.png)

يكون الوسم `<div>` مربعًا غير مرئي ويمكنك أن تحدِّد **نمطًا** له. ويتضمن هذا الوسمُ `<div>` المعرِّفَ `art` الذي ستحتاج إليه لتضيف أنماطًا إلى المربع.

+ انتقل الآن إلى الملف `style.css` وأضف نمط الجدول إلى الوسم `<div>` الذي يُسمى `art`.

![screenshot](images/pixel-art-style.png)

سيؤدي ذلك إلى إنشاء جدول ذي حد وتعيين التباعد داخل الشبكة.

لكن لا يبدو الجدول مشوِّقًا حتى الآن، لذا فإنك تحتاج إلى وضع صفوف من وحدات البكسل داخله.

+ انتقل إلى ملف `index.html` وأضف صفًا مكونًا من ثلاث وحدات بكسل **داخل** المربع `art`. وإذا كنتَ تريد توفير الوقت، يمكنك إدخال الصف الأول ثم نسخه ولصقه لإنشاء صفوف أخرى.

![screenshot](images/pixel-art-row.png)

لاحظ أنك تستخدم **class** بدلًا من ID لتحديد نمط أوسمة div. وهذا لأنه سيكون لديك الكثير من هذه الأوسمة، لذا سيكون استخدام الفئة أكثر فائدة هنا.

+ انتقل إلى الملف `style.css` وأضف الأنماط التالية إلى الصفوف ووحدات البكسل داخل كل صف:

![screenshot](images/pixel-art-row-style.png)

ستظهر الآن وحدات البكسل منظمة في شكل صف داخل شبكة تحيط بها خطوط سوداء.

+ في الملف `index.html`، أضف صفين آخرين من وحدات البكسل لإنشاء شبكة 3×3. ويمكنك استخدام النسخ واللصق مرة أخرى لتوفير الوقت.

--- hints ---
--- hint ---
ابحث عن الوسم `<div>` الذي يتضمن الفئة `row` وانسخه كاملًا، بما في ذلك الصفوف الثلاثة المسماة `pixel` الموجودة بداخله بما في ذلك وسم `</div>` المطابق له.

ألصق هذه التعليمات البرمجية أسفل الوسم الذي نسخته مباشرة لإنشاء صف آخر. ثم كرِّر اللصق مرة أخرى أسفل الوسم الثاني مباشرة حتى يكون لديك ثلاثة صفوف يحتوي كل منها على ثلاث وحدات من البكسل.

انظر إلى المساحة الموجودة على اليمين لترى النتيجة وتتأكد من أن الجدول يظهر بالشكل المطلوب.
--- /hint ---
--- hint ---
يجب أن تكون التعليمة البرمجية التي تُدخلها كما يلي:

![screenshot](images/pixel-art-grid-3.png)
--- /hint ---
--- /hints ---