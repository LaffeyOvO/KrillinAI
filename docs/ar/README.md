<div align="center">
  <img src="/docs/images/logo.png" alt="KrillinAI" height="90">

  # أداة ترجمة الفيديو وتسجيل الصوت بالذكاء الاصطناعي

  <a href="https://trendshift.io/repositories/13360" target="_blank"><img src="https://trendshift.io/api/badge/repositories/13360" alt="krillinai%2FKrillinAI | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

  **[English](/README.md)｜[简体中文](/docs/zh/README.md)｜[日本語](/docs/jp/README.md)｜[한국어](/docs/kr/README.md)｜[Tiếng Việt](/docs/vi/README.md)｜[Français](/docs/fr/README.md)｜[Deutsch](/docs/de/README.md)｜[Español](/docs/es/README.md)｜[Português](/docs/pt/README.md)｜[Русский](/docs/rus/README.md)｜[اللغة العربية](/docs/ar/README.md)**

[![Twitter](https://img.shields.io/badge/Twitter-KrillinAI-orange?logo=twitter)](https://x.com/KrillinAI)
[![Discord](https://img.shields.io/discord/1333374141092331605?label=Discord&logo=discord&style=flat-square)](https://discord.gg/sKUAsHfy)
[![QQ 群](https://img.shields.io/badge/QQ%20群-754069680-green?logo=tencent-qq)](https://jq.qq.com/?_wv=1027&k=754069680)
[![Bilibili](https://img.shields.io/badge/dynamic/json?label=Bilibili&query=%24.data.follower&suffix=粉丝&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Frelation%2Fstat%3Fvmid%3D242124650&logo=bilibili&color=00A1D6&labelColor=FE7398&logoColor=FFFFFF)](https://space.bilibili.com/242124650)

</div>

### 📢 إصدار جديد لسطح المكتب لنظامي ويندوز وماك، مرحبًا بتجربتك وملاحظاتك [المستندات تحتاج إلى تحديث، جاري العمل عليها]

 ## مقدمة المشروع  

Krillin AI هو حل شامل لتوطين وتعزيز الصوت والفيديو. هذه الأداة البسيطة والقوية تجمع بين ترجمة الفيديو، تسجيل الصوت، واستنساخ الصوت، وتدعم إخراج بتنسيقات عمودية وأفقية، مما يضمن عرضًا مثاليًا على جميع المنصات الرئيسية (بلي بلي، شياوهونغشو، دوين، فيديوهات، كواي شou، يوتيوب، تيك توك، إلخ). من خلال سير العمل من البداية إلى النهاية، يمكن لـ Krillin AI تحويل المواد الأصلية إلى محتوى عبر المنصات جاهز للاستخدام بنقرات قليلة فقط.

## الميزات والوظائف الرئيسية:
🎯 **تشغيل بنقرة واحدة**: لا حاجة لتكوين بيئة معقدة، تثبيت تلقائي للاعتماديات، وبدء الاستخدام على الفور، مع إصدار سطح مكتب جديد لسهولة الاستخدام!

📥 **الحصول على الفيديو**: يدعم تنزيل yt-dlp أو رفع الملفات المحلية

📜 **التعرف الدقيق**: التعرف على الصوت بدقة عالية استنادًا إلى Whisper

🧠 **التقسيم الذكي**: استخدام LLM لتقسيم وتنسيق الترجمة

🔄 **استبدال المصطلحات**: استبدال مصطلحات المجال الاحترافية بنقرة واحدة 

🌍 **ترجمة احترافية**: استنادًا إلى LLM، تضمن الترجمة على مستوى الفقرات الحفاظ على تماسك المعنى

🎙️ **استنساخ الصوت**: تقديم أصوات مختارة من CosyVoice أو استنساخ صوت مخصص

🎬 **دمج الفيديو**: معالجة تلقائية للفيديوهات الأفقية والعمودية وتنسيق الترجمة


## عرض النتائج
الصورة أدناه توضح تأثير ملف الترجمة الناتج بعد استيراد فيديو محلي مدته 46 دقيقة وتنفيذه بنقرة واحدة، دون أي تعديلات يدوية. لا توجد أي فقدان أو تداخل، والفواصل طبيعية، وجودة الترجمة عالية جدًا.
![تأثير المحاذاة](/docs/images/alignment.png)

<table>
<tr>
<td width="33%">

### ترجمة الترجمة
---
https://github.com/user-attachments/assets/bba1ac0a-fe6b-4947-b58d-ba99306d0339

</td>
<td width="33%">



### تسجيل الصوت
---
https://github.com/user-attachments/assets/0b32fad3-c3ad-4b6a-abf0-0865f0dd2385

</td>

<td width="33%">

### عمودي
---
https://github.com/user-attachments/assets/c2c7b528-0ef8-4ba9-b8ac-f9f92f6d4e71

</td>

</tr>
</table>

## 🔍 دعم خدمات التعرف على الصوت
_**جميع النماذج المحلية في الجدول أدناه تدعم التثبيت التلقائي للملفات القابلة للتنفيذ + ملفات النموذج، كل ما عليك هو الاختيار، والباقي سيتولى KrillinAI.**_

| مصدر الخدمة        | المنصات المدعومة       | خيارات النموذج                               | محلي/سحابي | ملاحظات                |
| ------------------ | --------------------- | ---------------------------------------- | --------- | ---------------------- |
| **OpenAI Whisper** | جميع المنصات          | -                                        | سحابي      | سريع وفعال            |
| **FasterWhisper**  | ويندوز/لينكس         | `tiny`/`medium`/`large-v2` (موصى به medium+) | محلي      | أسرع، بدون تكاليف سحابية |
| **WhisperKit**     | ماك (لشرائح M فقط)   | `large-v2`                               | محلي      | تحسين أصلي لشرائح Apple |
| **علي بابا ASR**   | جميع المنصات          | -                                        | سحابي      | لتجنب مشاكل الشبكة في الصين |

## 🚀 دعم نماذج اللغة الكبيرة

✅ متوافق مع جميع خدمات نماذج اللغة الكبيرة السحابية/المحلية التي تتوافق مع **معايير OpenAI API**، بما في ذلك على سبيل المثال لا الحصر:
- OpenAI
- DeepSeek
- Tongyi Qianwen
- نماذج مفتوحة المصدر المثبتة محليًا
- خدمات API الأخرى المتوافقة مع تنسيق OpenAI

## دعم اللغات
اللغات المدخلة المدعومة: الصينية، الإنجليزية، اليابانية، الألمانية، التركية، الكورية، الروسية، الماليزية (يتم إضافة المزيد باستمرار)

اللغات المدعومة للترجمة: الإنجليزية، الصينية، الروسية، الإسبانية، الفرنسية، وغيرها من 101 لغة

## معاينة الواجهة
![معاينة الواجهة](/docs/images/ui_desktop.png)


## 🚀 البدء السريع
### الخطوات الأساسية
أولاً، قم بتنزيل [الإصدار](https://github.com/krillinai/KrillinAI/releases) الذي يتوافق مع نظام جهازك، ثم اختر ما إذا كنت تريد الإصدار المكتبي أو غير المكتبي، ثم ضع الملفات في مجلد فارغ، لأن البرنامج سيولد بعض الدلائل بعد التشغيل، وضعها في مجلد فارغ سيسهل إدارتها.  

【إذا كان الإصدار المكتبي، أي الملفات التي تحمل كلمة desktop، انظر هنا】  
_الإصدار المكتبي هو إصدار جديد، تم إصداره لحل مشكلة صعوبة تحرير ملفات التكوين بشكل صحيح من قبل المستخدمين الجدد، ولا يزال هناك العديد من الأخطاء، جاري التحديث._
1. انقر نقرًا مزدوجًا على الملف لبدء الاستخدام (الإصدار المكتبي يحتاج أيضًا إلى تكوين، يتم ذلك داخل البرنامج)

【إذا كان الإصدار غير المكتبي، أي الملفات التي لا تحمل كلمة desktop، انظر هنا】  
_الإصدار غير المكتبي هو الإصدار الأول، تكوينه معقد بعض الشيء، لكنه مستقر، ومناسب للنشر على الخوادم، حيث سيتم توفير واجهة المستخدم عبر الويب._
1. أنشئ مجلدًا باسم `config` داخل المجلد، ثم أنشئ ملفًا باسم `config.toml` داخل مجلد `config`، وانسخ محتوى ملف `config-example.toml` الموجود في دليل `config` إلى `config.toml`، واملأ معلومات التكوين الخاصة بك وفقًا لذلك.
2. انقر نقرًا مزدوجًا، أو نفذ الملف القابل للتنفيذ في الطرفية، لبدء الخدمة 
3. افتح المتصفح، وأدخل `http://127.0.0.1:8888`، وابدأ الاستخدام (استبدل 8888 بالمنفذ الذي أدخلته في ملف التكوين)

### إلى: مستخدمي macOS
【إذا كان الإصدار المكتبي، أي الملفات التي تحمل كلمة desktop، انظر هنا】  
حاليًا، بسبب مشاكل في التوقيع، لا يمكن حزم الإصدار المكتبي ليعمل بنقرة مزدوجة مباشرة أو تثبيته كملف dmg، تحتاج إلى الوثوق بالتطبيق يدويًا، والطريقة كالتالي:
1. افتح الطرفية في الدليل الذي يحتوي على الملف القابل للتنفيذ (افترض أن اسم الملف هو KrillinAI_1.0.0_desktop_macOS_arm64)
2. نفذ الأوامر التالية بالتتابع:
```
sudo xattr -cr ./KrillinAI_1.0.0_desktop_macOS_arm64
sudo chmod +x ./KrillinAI_1.0.0_desktop_macOS_arm64 
./KrillinAI_1.0.0_desktop_macOS_arm64
```

【إذا كان الإصدار غير المكتبي، أي الملفات التي لا تحمل كلمة desktop، انظر هنا】  
لم يتم توقيع هذا البرنامج، لذا عند تشغيله على macOS، بعد إكمال تكوين الملفات في "الخطوات الأساسية"، تحتاج أيضًا إلى الوثوق بالتطبيق يدويًا، والطريقة كالتالي:
1. افتح الطرفية في الدليل الذي يحتوي على الملف القابل للتنفيذ (افترض أن اسم الملف هو KrillinAI_1.0.0_macOS_arm64)
2. نفذ الأوامر التالية بالتتابع:
   ```
    sudo xattr -rd com.apple.quarantine ./KrillinAI_1.0.0_macOS_arm64
    sudo chmod +x ./KrillinAI_1.0.0_macOS_arm64
    ./KrillinAI_1.0.0_macOS_arm64
    ```
    لتشغيل الخدمة

### نشر Docker
يدعم هذا المشروع نشر Docker، يرجى الرجوع إلى [إرشادات نشر Docker](./docker.md)

### إرشادات تكوين الكوكيز (غير إلزامية)

إذا واجهت مشكلة في تنزيل الفيديو

يرجى الرجوع إلى [إرشادات تكوين الكوكيز](./get_cookies.md) لتكوين معلومات الكوكيز الخاصة بك.

### مساعدة التكوين (يجب قراءتها)
أسهل وأسرع طريقة للتكوين:
* اختر `transcription_provider` و`llm_provider` كـ `openai`، بحيث تحتاج فقط إلى ملء `openai.apikey` في الفئات الثلاث أدناه `openai` و`local_model` و`aliyun` لترجمة الترجمة. (يمكن ملء `app.proxy` و`model` و`openai.base_url` حسب الحاجة)

استخدام نموذج التعرف على اللغة المحلي (غير مدعوم حاليًا على macOS) (توازن بين التكلفة والسرعة والجودة)
* املأ `transcription_provider` بـ `fasterwhisper` و`llm_provider` بـ `openai`، بحيث تحتاج فقط إلى ملء `openai.apikey` و`local_model.faster_whisper` في الفئات الثلاث أدناه `openai` و`local_model` لترجمة الترجمة، وسيتم تنزيل النموذج المحلي تلقائيًا. (مثل `app.proxy` و`openai.base_url` كما هو مذكور أعلاه)

فيما يلي بعض الحالات التي تحتاج فيها إلى تكوين علي بابا:
* إذا تم ملء `llm_provider` بـ `aliyun`، تحتاج إلى استخدام خدمة النموذج الكبير من علي بابا، لذا تحتاج إلى تكوين `aliyun.bailian`.
* إذا تم ملء `transcription_provider` بـ `aliyun`، أو إذا قمت بتمكين وظيفة "تسجيل الصوت" عند بدء المهمة، تحتاج إلى استخدام خدمة الصوت من علي بابا، لذا تحتاج إلى ملء `aliyun.speech`.
* إذا قمت بتمكين وظيفة "تسجيل الصوت" وقمت بتحميل صوت محلي لاستنساخ الصوت، ستحتاج أيضًا إلى استخدام خدمة تخزين السحابة OSS من علي بابا، لذا تحتاج إلى ملء `aliyun.oss`.  
مساعدة تكوين علي بابا: [إرشادات تكوين علي بابا](./aliyun.md)

## الأسئلة الشائعة

يرجى الانتقال إلى [الأسئلة الشائعة](./faq.md)

## معايير المساهمة
1. لا تقدم ملفات غير مفيدة مثل .vscode و.idea، يرجى استخدام .gitignore لتصفية الملفات
2. لا تقدم config.toml، بل استخدم config-example.toml لتقديمها

## اتصل بنا
1. انضم إلى مجموعة QQ الخاصة بنا، للإجابة على الأسئلة: 754069680
2. تابع حساباتنا على وسائل التواصل الاجتماعي، [بلي بلي](https://space.bilibili.com/242124650)، حيث نشارك محتوى عالي الجودة في مجال تكنولوجيا الذكاء الاصطناعي يوميًا

## تاريخ النجوم

[![Star History Chart](https://api.star-history.com/svg?repos=krillinai/KrillinAI&type=Date)](https://star-history.com/#krillinai/KrillinAI&Date)