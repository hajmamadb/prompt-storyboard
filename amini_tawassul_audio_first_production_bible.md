# پرونده تولید انیمیشن سه‌بعدی «نجاتم بده»

> **سند اجرایی ایجنت — نسخه 1.0 | صوت‌محور | مدت هدف: حدود ۲ دقیقه | زبان نریشن: فارسی**
>
> **وضعیت:** سند آماده اجرای مرحله پیش‌تولید است؛ فایل صوتی اصلی هنوز به این سند پیوست نشده، بنابراین زمان‌های شات‌ها فقط **پیش‌طرح ۱۲۰ثانیه‌ای** هستند، نه تایم‌کدهای استخراج‌شده از صوت.

## ۰. دستور اصلی به ایجنت تولید

**مأموریت:** بر اساس فایل صوتی واقعی که کارفرما تحویل می‌دهد، انیمیشنی سینمایی، سه‌بعدی و واقع‌گرایانه درباره نقلِ منتسب به علامه عبدالحسین امینی در نجف تولید کن. **صوت اصلی مرجع نهایی روایت، زمان‌بندی، ریتم، سکوت و نقاط تأکید است.** استوری‌بورد پایین تنها قالب اولیه است: اگر صوت اصلی با ۱۲۰ ثانیه یا متنِ نقل‌شده اختلاف داشت، **صحنه‌ها را با صوت تطبیق بده، نه صوت را با صحنه‌ها**.

1. اول فایل صوتی را بگیر، صحت و مدت آن را بسنج، رونویسی کن و واژه‌به‌واژه زمان‌بندی کن.
2. متن صوت را با متن مرجع داستان تطبیق بده؛ تغییرات روایت را مشخص کن؛ هیچ دیالوگ یا جمله‌ای به صوت اضافه نکن.
3. عکس‌های مستند شخصیت اصلی و شیت‌های چهره را گردآوری/بساز؛ سپس شیت چهار شیطان، رئیس، همسر، دوست و دو شاگرد را تولید کن.
4. محیط‌های نجف، حرم، اتاق خانه و پشت‌بام خواب را یک‌بار طراحی و قفل کن.
5. برای شات‌های این سند، مطابق جمله‌های زمان‌بندی‌شده **فریم آغاز/پایان** بساز و سپس تصویر‌به‌ویدئو را اجرا کن.
6. تصاویر را طبق تایم‌کدهای واقعی روی صدای اصلی مونتاژ کن؛ افکت و موسیقی فقط زیر صدای اصلی باشند.
7. کنترل کیفیت دقیقِ هویت چهره، شمارش دقیق پنج موجود، تداوم معماری، لباس، نسبت تصویر، و هماهنگی صوت و تصویر انجام بده.
8. خروجی نهایی به‌علاوه فایل‌های پروژه، استوری‌بورد، شیت‌ها، تایم‌لاین و گزارش مشکلات را تحویل بده.

**قانون توقف:** اگر فایل صوتی وجود ندارد، فقط تا پایان پیش‌تولید و تهیه پیش‌نمایش فریم‌های تأییدی جلو برو؛ تولید نهایی شات‌های دارای تایم‌کد قطعی ممنوع است. اگر تصویر معتبر علامه در دسترس نیست، چهره فرضی را به نام چهره واقعی علامه تأیید نکن.

## ۱. مشخصات فنی و قواعد قفل‌شده

| آیتم | مقدار |
|---|---|
| نام تولید | `amini-tawassul` |
| نوع اثر | بازآفرینی هنری یک نقل مذهبی در قالب خواب، نه مستندِ اثبات وقوع واقعه |
| تصویر اصلی | 16:9، حداقل 1920×1080، ترجیحاً مستر 4K در صورت کیفیت واقعی خروجی |
| فریم‌ریت | 24fps، همه کلیپ‌ها یکسان |
| زمان هدف | 120s **فقط اگر صوت واقعی 120s باشد** |
| مرجع زمان | `audio/master_original.*`؛ تغییر مدت، سرعت و زیر‌وبمی ممنوع مگر با اجازه صریح |
| روایت | تنها فایل صوتی کارفرما؛ بدون صداپیشگی جدید یا تقلید صدای گوینده |
| سبک | photoreal cinematic 3D animation, historical Najaf, grounded fantasy dream |
| نورپردازی | حرم: طلایی طبیعی و امیدبخش؛ خانه: کهربایی ملایم؛ خواب: خاکستری/سبز دودی کنترل‌شده |
| زیرنویس | SRT مستقل و قابل خاموش‌کردن، استخراج‌شده از صوت واقعی |
| موسیقی و افکت | بی‌کلام، فاقد گفتار افزوده؛ زیر میکس صدای موجود |
| خروجی | `final_16x9.mp4`, `final_clean.mp4`, `subtitles.fa.srt`, `edit_project`, `shot_manifest.json` |

**دقت تاریخی:** علامه عبدالحسین امینی پژوهشگر شیعه و صاحب اثر «الغدیر» بوده است. ظاهر وی (از جمله شکل و رنگ عمامه، محاسن، صورت، پوشش) باید از **عکس تأییدشده خود ایشان** استخراج شود، نه براساس یک کلیشه عمومی از روحانیان. بازسازی جزئیات ساختمان‌های نجف در دوره دقیق روایت، در صورت نامشخص بودن تاریخ رخداد، باید با عنوان «بازسازی تقریبی» ثبت شود. منبع تصویری اولیه جهت جست‌وجو: https://commons.wikimedia.org/wiki/File:Allame_Amini.jpg و نمای حرم: https://commons.wikimedia.org/wiki/File:InsideImamAliMosqueNajafIraq.JPG . شرایط مجوز هر تصویر پیش از استفاده نهایی بررسی شود.

**امانت‌داری روایی:** انتساب تاریخیِ جزئیات این خواب صرفاً بر اساس روایت صوتی ارائه‌شده است؛ تا زمانی که مأخذ مکتوب مستقل به دست نیامده، متن پایانی را طوری تنظیم نکن که سندیت تاریخی این نقل را قطعی ادعا کند. پیشنهاد تیتراژ: «بازآفرینی هنری بر اساس روایت نقل‌شده درباره علامه امینی».

## ۲. اول صوت: الگوریتم همگام‌سازی ویدئو با گوینده

### ۲.۱ دریافت و اعتبارسنجی

- منبع: **فایل واقعی کارفرما** با نام `audio/master_original.wav` یا `mp3`/`m4a`.
- با ابزار تحلیل صدا مانند `ffprobe` مدت حقیقی، نرخ نمونه‌برداری، تعداد کانال، سطح صدای اوج و سکوت‌ها را بخوان.
- فایل منبع read-only نگه‌داری شود؛ از آن هش SHA-256 و کپی کاری تهیه کن.
- با ASR فارسی (مثلاً Whisper/WhisperX یا معادل در دسترس) متن خام را استخراج کن؛ سپس بازبینی انسانی/متنی روی عبارت‌هایی مانند «مخ‌مخه‌ست»، «گنده شده»، «احسنت» و «نجف» انجام بده. **دقت رونویسی مدل را فرض نگیر.**
- با forced alignment یا زمان‌بندی دقیق دستی، مرز آغاز و پایانِ هر جمله مهم و ترجیحاً واژه را پیدا کن؛ خطاهای محاوره‌ای و مکث‌های واقعی حفظ شوند.
- فایل‌های `audio/transcript_verified.fa.txt`, `audio/word_timestamps.json`, `audio/phrase_timestamps.json`, `audio/subtitles.fa.srt` بساز.

### ۲.۲ قاعده تدوین تابع صوت

- هر شات پایین یک **لنگر متنی** دارد؛ آن لنگر را در رونویسی صوت پیدا و بازه واقعی‌اش را استخراج کن.
- شات ممکن است زودتر از جمله مرتبط شروع شود، اما باید در نقطه تأکید گوینده تصویر اصلی آن حاضر باشد.
- اگر بازه گفتار طولانی‌تر بود، پوشش بصری با نمای واکنشی، نمای جزئیات، فلاش‌بک مکمل یا J-cut / L-cut ادامه یابد؛ تصویر را با کشیدن فریم یا حرکت آهسته غیرطبیعی طولانی نکن.
- اگر کوتاه‌تر بود، شات‌های فرعی را حذف یا ترکیب کن؛ هیچ جمله صوتی را حذف نکن.
- **نباید** با عددهای ثابت پیشنهادی زیر، صدا را هم‌زمان‌سازی صوری کرد. ساخت `final_timeline.csv` پس از تحلیل صوت الزامی است.
- اگر طول صوت مثلاً ۱۶۵ ثانیه شد، نسخه وفادار به صوت **۱۶۵ ثانیه** خواهد بود؛ ساخت نسخه دقیقاً ۱۲۰ثانیه‌ای فقط با دریافت مجوز برای تدوین و کوتاه‌سازی صوت.
- متن گوینده شامل گفتار مستقیم رئیس شیاطین است اما چون یک گوینده آن را تعریف می‌کند، انیمیشن لب‌خوانی در شات‌های گفت‌وگو ضروری نیست. در صورت تصمیم به لب‌خوانی، تنها بخش گفتار مستقیم و با آزمون کوتاه هماهنگ شود؛ هیچ صدای ساختگی دیگری اضافه نشود.

### ۲.۳ الگوریتم اجرایی نمونه

```python
# pseudo-code — نمایانگر ترتیب کار، نه اجرای آماده بدون ابزار و فایل
original = probe_audio("audio/master_original.wav")
words = transcribe_and_force_align_persian(original)
verified = manually_verify_against_audio(words)
anchors = locate_story_anchors(verified, storyboard_shots)
segments = allocate_shots_to_real_phrases(anchors, preserve_pauses=True)
assert no_original_audio_removed(segments)
write_json("audio/word_timestamps.json", verified)
write_csv("edit/final_timeline.csv", segments)
render_video_to_original_audio(segments, audio="audio/master_original.wav")
```

## ۳. کتابچه ظاهر و قواعد تصویری

**موتور تصویر مشترک برای همه پرامپت‌ها:**

```text
Prestige historical drama, photorealistic cinematic 3D animation, physically-based materials, believable anatomy, subtle performance, richly layered but restrained lighting, controlled natural film grain, historical mid-20th-century Najaf Iraq, period-correct garments and props, professional 35mm-cinema sensibility, 16:9 composition, no subtitles or text burned into generated frames, continuity with approved character and environment reference sheets.
```

**پرامپت منفی سراسری، برای مدل‌هایی که negative prompt می‌پذیرند:**

```text
face drift, identity change, invented faces for the historical protagonist, modern cars, modern billboards, incorrect era props, extra demons, missing demons, swapped demon faces, extreme horror, gore, flames, cartoon anatomy, fantasy armor, excessive horns, distorted hands, extra fingers, rubber motion, melting faces, changing clothing, low-res image, unstable architecture, hallucinated Arabic calligraphy, random subtitles, logos, watermark, camera teleportation, extreme lens warping, flashy magical beams, extra voices.
```

**حرم:** جلوه حقیقی کاشی‌کاری، نقوش آینه‌کاری و ضریح براساس عکس مرجع، نه معماری تلفیقیِ بی‌ریشه. **خواب:** عبور بصری تدریجی از جهان عادی به جهان ذهنی؛ عناصر وهم‌آلود صرفاً بخشی از خواب هستند. **شیاطین:** پنج موجود انسان‌نمای غیرمتعارف، با روان‌شناسی و حرکت باورپذیر، بدون خون‌ریزی و ترس‌افکنی افراطی. **همسر و شاگردان:** به‌شکل انسانی، باوقار و غیرمتهم نمایش داده شوند.

## ۴. شیت شخصیت‌ها — مرحله اجباری پیش از ساخت شات

هر شخصیت باید یک **Character ID** مستقل، یک مدل چهره تأییدشده و شیت چرخش ۳۶۰ درجه داشته باشد. خروجی شیت‌ها حداقل شامل نماهای رو‌به‌رو، نیم‌رخ راست و چپ، سه‌ربع و پشت، نمای نزدیک، تمام‌قد، یک حالت نشسته و ۶ حالت چهره است. تمامی لباس‌ها، تناسب اندام، طرح چهره و رنگ‌ها به عنوان `LOCKED` در یک `character_bible.json` ذخیره شوند.

### `REF_CHAR_AMINI` — علامه عبدالحسین امینی

- **اولویت مطلق:** استفاده از یک یا چند عکس مستندِ تأییدشده از خود علامه. رنگ و شکل عمامه یا جزئیات سنِ مقطع روایت را حدسی قفل نکن.
- **نقش:** دعا در حرم، ناهار و استراحت، بیداری؛ حضور تصویریِ واکنشی در خواب محدود.
- **حالات:** تأمل، خستگی ملایم، توسل، آرامش، خواب، شگفتی کنترل‌شده، بیداری.

```text
Using the user-approved authentic historical portrait(s) of Allameh Abdolhossein Amini as the single identity reference, construct a photorealistic 3D period-film character turnaround sheet. Faithfully preserve his actual face geometry, beard, forehead, eyes, nose, turban style and color, and era-appropriate clerical clothing exactly as visible in approved photographs. Front, left/right profile, three-quarter, back, full body, seated posture and six subtle emotional expressions. Neutral 18% gray studio background with consistent softbox illumination and fixed focal length. Never substitute a generic cleric face. No typography inside the images.
```

### `REF_CHAR_LEADER` — رئیسِ شیاطین

```text
Create one original cinematic 3D character turnaround of a frightening but credible humanoid dream-demon leader, older-looking, tall seated silhouette, angular but anatomically stable facial structure, charcoal-brown worn garment, restrained pale-gray eyes, emotionally commanding presence. Distinctive asymmetric brow, weathered skin, no giant horns or cartoon grotesqueness. Front, both profiles, three-quarter, back, full body, seated pose, neutral, approval, suspicion, controlled anger, sudden realization. Neutral studio background and physically-based texture fidelity. LOCK appearance.
```

### `REF_CHAR_D1` — مأمور حسادت

```text
Create an original photoreal 3D subordinate dream-demon character sheet: lean narrow shoulders, nimble hands, crafty half-smile, medium-gray rough skin, short dark worn robe with a distinctive tied waist cord, slightly bent forward posture. Exactly one unique face, visually distinct from the leader and other demons. Full turnaround plus reporting, sly, startled, fearful expressions. Neutral studio background. LOCK identity.
```

### `REF_CHAR_D2` — مأمور شبهه

```text
Create a distinct photoreal 3D dream-demon subordinate sheet: compact build, quietly calculating narrow gaze, long slim fingers, charcoal layered vest over ash-colored tunic, controlled whispering manner, a small vertical scar by the eyebrow. No duplication of D1 or leader facial anatomy. Front/profile/back/three-quarter, seated and reporting poses, cold satisfaction, surprise and concern. LOCK identity.
```

### `REF_CHAR_D3` — مأمور اثرگذاری بر همسر

```text
Distinct original cinematic 3D humanoid dream-demon sheet, calmer and more manipulative body language rather than physically threatening, slender angular face, gray-olive skin, dusty long shawl and uneven shoulder line, soft deceptive expression. Multiple full-body angles, close-ups and reporting pose. Distinct from all others, believable human-adjacent anatomy, no exaggerated sexual characteristics. LOCK identity.
```

### `REF_CHAR_D4` — مأمور القای خروج به علامه

```text
Distinct original 3D humanoid dream-demon subordinate, shorter hesitant posture, heavy brows, dark muted indigo-brown garment with distinct narrow cuffs, anxious small gestures, unusually round observant eyes but no cartoon look. Full turnaround, seated, reporting, flinching, tense silence. Keep this face and wardrobe exactly consistent thereafter. LOCK identity.
```

### `REF_CHAR_WIFE` — همسر علامه (بازسازی غیرمستند)

```text
An original respectful middle-aged Iranian Shia scholar's wife for a period historical drama in Najaf, modest full traditional home covering, believable warm facial features, natural age lines, dignified reserved body language, historically grounded unornamented clothing. Character turnaround, standing by a window, quiet family concern, neutral and reflective expressions. Fictional visual reconstruction, not a claim of exact historical likeness. No caricature.
```

### `REF_CHAR_FRIEND` — دوست علامه (بازسازی غیرمستند)

```text
An original period-accurate scholarly acquaintance in old Najaf, middle-aged man with subdued practical garment and simple beard, credible realistic Iranian/Iraqi regional appearance, quiet thoughtful manner. Full character turnaround and micro-expressions of respect, insecurity, troubled envy and embarrassment, nuanced not villainous. No present-day attire.
```

### `REF_CHAR_STUDENT1` و `REF_CHAR_STUDENT2` — شاگردان (دو شیت جدا)

```text
Create TWO clearly differentiated young male Najaf seminary student 3D character sheets from the mid-20th-century setting. Student 1: taller, thin face, simple light robe. Student 2: shorter, broad cheekbones, darker outer garment. Historically grounded clerical student headwear derived from approved references, age approximately 20-30. Individual turnarounds, neutral/listening/thinking/doubt/return-to-focus expressions. No identical faces or confusing wardrobe swaps.
```

**خروجی مرحله:** یک `character_lineup.png` شامل **پنج موجود شیطانی دقیقاً** به ترتیب چپ به راست D1, D2, LEADER, D3, D4؛ یک شیت مستقل برای هر انسان. عکس مرجع علامه و رفرنس خروجی به هر شات متصل شود. اگر امکان `seed` یا تصویر مرجع چندگانه وجود دارد، برای هر کاراکتر تنظیمات یکسان نگه‌دار.

## ۵. شیت محیط‌ها، لباس و اشیا

| ID | محیط | الزام |
|---|---|---|
| `REF_ENV_CITY` | کوچه/نمای حرم در نجف قدیم | بافت شهری دوره، پرهیز از خودرو و تابلو مدرن |
| `REF_ENV_SHRINE` | ورودی و رواق حرم | معماری قابل‌شناسایی و تأیید با عکس مرجع |
| `REF_ENV_SHRINE_ZARIH` | نمای نزدیک ضریح | شبکه‌ها، نور و کاشی‌کاری مطابق عکس؛ بدون اضافه‌کردن تصویر اشخاص مقدس |
| `REF_ENV_HOME` | خانه و محل صرف غذا | خانه ساده عالم دینی، بدون تجمل یا وسایل جدید |
| `REF_ENV_ROOM` | اتاق استراحت | پنجره، تشک، متکا و کتاب‌ها در همه نماها ثابت |
| `REF_ENV_ROOF` | بام خانه در خواب | جان‌پناه کوتاه، چیدمان پنج نشیمن ثابت، آسمان دودی |
| `REF_ENV_CLASS` | اتاق درس و شاگردان | معماری و ابزار علمی هماهنگ با دوره |

**پرامپت مادر شیت محیط:**

```text
Design a period-grounded cinematic 3D environment continuity sheet for [ENVIRONMENT_ID] in mid-20th-century Najaf, Iraq. Front establishing view, camera reverse angle, left/right side, an overhead simplified layout, detail crops of doors, windows, floor, wall materials, and primary props; physically-based materials; consistent layout and natural light sources. Match historical photographic references wherever available. Keep exact door/window locations fixed, avoid anachronisms, no embedded text.
```

**آبجکت قفل‌شده:** فنجان قهوه پنج‌نفره (تعداد فنجان‌های دیده‌شده ممکن است کمتر باشد اما جلسه همیشه پنج عضو دارد)، کتاب‌ها و نسخه‌های خطی بدون نوشته جعلی، سفره و ظرف، بستر استراحت، پنجره‌های ثابت اتاق، لباس‌های تصویب‌شده.

## ۶. شات‌لیست صوت‌محور — پیش‌طرح ۲۷ شات / ۱۲۰ ثانیه

**توجه:** این اعداد فقط توزیع پیشنهادی ۱۲۰ ثانیه هستند. با فایل صوتی واقعی دوباره زمان‌بندی می‌شوند. برای هر شات، دو پرامپت انگلیسیِ آماده تولید ارائه شده است. عبارت‌های `REF_...` به **تصاویر/شیت‌های واقعی تأییدشده** ارجاع دارند؛ ایجنت باید آن‌ها را در ابزار سازنده تصویر و ویدئو به‌عنوان reference image متصل کند، نه اینکه فقط متن را کپی کند.

- ساخت Keyframe: ابتدا فریم آغاز با رفرنس شخصیت و محیط؛ برای شات‌های دارای حرکت پیچیده علاوه بر آن فریم پایان.
- تولید ویدئو: هر بار یک اکشن اصلی، یک حرکت دوربین؛ پرهیز از جمله‌های دستورِ چندحرکتی و تبدیلات میان‌صحنه‌ای داخل یک ویدئو.
- رندر: کلیپ‌ها ۱ ثانیه handle اضافه برای تدوین داشته باشند، اما مرزهای نهایی از فایل صوت تعیین شوند.

### SH01 — نمای باز از نجف قدیم و گنبد و گلدسته‌های حرم

- **زمانِ صرفاً پیشنهادی:** 00:00 تا 00:05 (5 ثانیه)
- **لنگر در صوت اصلی:** «معرفی داستان و اشاره به علامه امینی»
- **تصویر و میزانسن:** نمای باز از نجف قدیم و گنبد و گلدسته‌های حرم؛ بدون نوشته در تصویر.
- **یادداشت تدوین/صدا:** صدای اصلی آغاز روایت، بدون گفتار اضافی

**IMAGE PROMPT — فریم سینمایی**

```text
Wide establishing view from an authentic mid-20th-century Najaf street toward the Imam Ali shrine. Quiet human-scale street, subdued warm morning light, architectural details verified against approved shrine references, dignified religious period drama, no modern buildings. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH01. Slow forward dolly along the old street toward the distant shrine. Gentle movement of a few passersby, natural cloth and dust motion, absolutely stable architecture and camera geometry. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH02 — علامه از پشت در ورودی حرم دیده می‌شود

- **زمانِ صرفاً پیشنهادی:** 00:05 تا 00:10 (5 ثانیه)
- **لنگر در صوت اصلی:** «یه زمانی رفتم تو حرم امیرالمؤمنین»
- **تصویر و میزانسن:** علامه از پشت در ورودی حرم دیده می‌شود؛ قاب سه‌ربع با شخصیت قفل‌شده.
- **یادداشت تدوین/صدا:** احساس ورود و احترام

**IMAGE PROMPT — فریم سینمایی**

```text
Medium-wide back three-quarter shot of REF_CHAR_AMINI entering REF_ENV_SHRINE, modest Shia clerical clothing exactly matching approved archival photo and character sheet, restrained worshippers, intricate tilework, golden gentle illumination, no visual invention of sacred figures. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH02. Subtle tracking camera following Amini for two measured steps toward shrine interior. Correct shoe and robe motion, mild depth-of-field change, preserve identical face and clothing. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH03 — کلوزآپ آرام از علامه در توسل

- **زمانِ صرفاً پیشنهادی:** 00:10 تا 00:16 (6 ثانیه)
- **لنگر در صوت اصلی:** «آقاجان نجاتم بده»
- **تصویر و میزانسن:** کلوزآپ آرام از علامه در توسل؛ ضریح در عمق تصویر، اشک بسیار جزئی و غیراغراق‌آمیز.
- **یادداشت تدوین/صدا:** اوج عاطفی اول؛ همگام با «نجاتم بده»

**IMAGE PROMPT — فریم سینمایی**

```text
Emotionally restrained medium close-up of REF_CHAR_AMINI praying toward REF_ENV_SHRINE_ZARIH, face and turban faithfully matching approved reference, gently raised hands, sincere and tired eyes, soft gold reflections, intimate cinematic shallow focus, no other sacred person visible. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH03. Very slow push-in, one natural blink, subtle breath and slight movement of fingers. No forced lip sync because the authentic narration is the only speech track. Maintain hands and facial identity. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH04 — خروج آرام علامه از حرم، همان لباس و زمان روز.

- **زمانِ صرفاً پیشنهادی:** 00:16 تا 00:20 (4 ثانیه)
- **لنگر در صوت اصلی:** «همینو گفتم و برگشتم»
- **تصویر و میزانسن:** خروج آرام علامه از حرم، همان لباس و زمان روز.
- **یادداشت تدوین/صدا:** برش روی پایان جمله

**IMAGE PROMPT — فریم سینمایی**

```text
Side tracking medium shot of REF_CHAR_AMINI walking calmly out of the shrine courtyard into an old Najaf passage, modest movement, warm daylight, historical architectural continuity, contemplative tone. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH04. Gentle lateral follow movement for three walking steps; keep garments natural and no sudden camera sweep. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH05 — اتاق ساده خانه و سفره جمع‌وجور

- **زمانِ صرفاً پیشنهادی:** 00:20 تا 00:24 (4 ثانیه)
- **لنگر در صوت اصلی:** «اومدم منزل ناهار خوردم»
- **تصویر و میزانسن:** اتاق ساده خانه و سفره جمع‌وجور؛ بدون نمایش تجمل.
- **یادداشت تدوین/صدا:** صدای محیط بسیار ضعیف

**IMAGE PROMPT — فریم سینمایی**

```text
Period-appropriate modest Najaf scholar home dining room, REF_CHAR_AMINI seated at a simple floor-level meal, traditional dishes without excessive detail, soft light through an arched window, quiet naturalistic composition, historical domestic realism. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH05. Locked camera with subtle hand motion as Amini sets aside a small bowl and moves away from lunch. Avoid mouth close-up and avoid adding dialogue. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH06 — نمای متوسط از آماده‌سازی بستر و دراز کشیدن.

- **زمانِ صرفاً پیشنهادی:** 00:24 تا 00:29 (5 ثانیه)
- **لنگر در صوت اصلی:** «اومدم یه چرتی بزنم بخوابم»
- **تصویر و میزانسن:** نمای متوسط از آماده‌سازی بستر و دراز کشیدن.
- **یادداشت تدوین/صدا:** آهنگ تنفسی و سکوت کوتاه

**IMAGE PROMPT — فریم سینمایی**

```text
Modest scholarly sleeping room REF_ENV_ROOM, REF_CHAR_AMINI reclining on a period-accurate floor bedding with a small pillow, afternoon light, simple shelves, dark books and cream plaster, peaceful restrained image. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH06. Slow camera drift toward Amini as he reclines and gradually closes his eyes, with natural anatomy and continuous motion. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH07 — کلوزآپ چشم بسته و دیزالو به بافت مه‌آلود پشت‌بام

- **زمانِ صرفاً پیشنهادی:** 00:29 تا 00:33 (4 ثانیه)
- **لنگر در صوت اصلی:** «چشمامو که بستم، در خواب دیدم»
- **تصویر و میزانسن:** کلوزآپ چشم بسته و دیزالو به بافت مه‌آلود پشت‌بام؛ تمایز خواب.
- **یادداشت تدوین/صدا:** نقطه ورود به خواب؛ افکت محیط نه روی گفتار

**IMAGE PROMPT — فریم سینمایی**

```text
Extreme close-up of the approved Amini face with eyes closed, one soft reflection of rooftop shapes in gentle drifting shadow, cinematic dream threshold, subtle lavender-gray edge lighting, no grotesque distortion. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH07. Very gentle push on closed eyelid then a smooth dream dissolve to rooftop atmospheric haze. No morphing face and no abrupt lens jumps. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH08 — نمای باز با حضور دقیقاً پنج موجود: یک رئیس و چهار زیردست

- **زمانِ صرفاً پیشنهادی:** 00:33 تا 00:39 (6 ثانیه)
- **لنگر در صوت اصلی:** «بالای پشت‌بام منزلم پنج تا موجود عجیب نشسته»
- **تصویر و میزانسن:** نمای باز با حضور دقیقاً پنج موجود: یک رئیس و چهار زیردست؛ فرم سایه‌ها مشخص.
- **یادداشت تدوین/صدا:** در تصویر ترس کنترل‌شده

**IMAGE PROMPT — فریم سینمایی**

```text
Dream rooftop REF_ENV_ROOF in old Najaf at twilight, EXACTLY FIVE distinct unsettling humanoid jinn figures REF_CHAR_LEADER + REF_CHAR_D1 + REF_CHAR_D2 + REF_CHAR_D3 + REF_CHAR_D4 seated together; all fully visible, coherent scale, low stone parapet, ash-gray smoky sky, grounded dramatic fantasy realism, no horns unless in approved character sheets. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH08. Measured crane rise from rooftop parapet to reveal exactly five seated silhouettes. Only subtle body shifts and cloth movement, preserve precise character count and original seat order. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH09 — نمای نزدیک‌تر از تفاوت چهره‌ها و پوست

- **زمانِ صرفاً پیشنهادی:** 00:39 تا 00:43 (4 ثانیه)
- **لنگر در صوت اصلی:** «از شکل و شمایلشون فهمیدم این‌ها از شیاطینند»
- **تصویر و میزانسن:** نمای نزدیک‌تر از تفاوت چهره‌ها و پوست؛ انسانی اما نامأنوس.
- **یادداشت تدوین/صدا:** نمایش خواب، نه ادعای تصویر مستند

**IMAGE PROMPT — فریم سینمایی**

```text
Slow dramatic five-person group portrait of REF_CHAR_LEADER and four locked subordinate character designs from approved lineup, eerie facial proportions and sharp eyes, physically consistent materials, low-contrast green-gray light, psychologically unsettling rather than gory. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH09. Slow pan across all five faces, each making a different tiny glance. Preserve all distinctive faces and the exact group lineup. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH10 — رئیس در مرکز قاب و دیگران در پیرامون، اختلاف قدرت آشکار.

- **زمانِ صرفاً پیشنهادی:** 00:43 تا 00:46 (3 ثانیه)
- **لنگر در صوت اصلی:** «بزرگه معلومه بزرگشونه، بقیه نوچه‌هاشن»
- **تصویر و میزانسن:** رئیس در مرکز قاب و دیگران در پیرامون، اختلاف قدرت آشکار.
- **یادداشت تدوین/صدا:** معرفی جایگاه رئیس

**IMAGE PROMPT — فریم سینمایی**

```text
Medium low-angle shot of REF_CHAR_LEADER sitting one step higher than four subordinates on dream rooftop, austere dark garment, powerful still posture, four fixed silhouettes in midground, cinematic hierarchy framing. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH10. Subtle low-angle push-in as leader raises one hand and the others grow quiet. No face mutation. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH11 — جزئیات فنجان‌های قهوه واقعی با دست صحیح

- **زمانِ صرفاً پیشنهادی:** 00:46 تا 00:51 (5 ثانیه)
- **لنگر در صوت اصلی:** «اینا نشسته بودن قهوه می‌خوردن»
- **تصویر و میزانسن:** جزئیات فنجان‌های قهوه واقعی با دست صحیح؛ لحظه مکث رازآلود.
- **یادداشت تدوین/صدا:** فولی خیلی کم؛ بدون پوشاندن صدا

**IMAGE PROMPT — فریم سینمایی**

```text
Close insert shot of aged traditional small coffee cups held by two distinct demon hands on old Najaf rooftop, wisps of steam, leader and others softly visible out of focus, eerie contrast between ordinary coffee ritual and abnormal beings, accurate fingers. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH11. Only a tiny cup lift and slight steam rise, focus racks gently from cup to leader. No hand deformation, no extra fingers. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH12 — زیر‌دست اول برای گزارش جلو خم می‌شود.

- **زمانِ صرفاً پیشنهادی:** 00:51 تا 00:55 (4 ثانیه)
- **لنگر در صوت اصلی:** «این کوچیکتره به اون بزرگه داشت کاراشو می‌گفت»
- **تصویر و میزانسن:** زیر‌دست اول برای گزارش جلو خم می‌شود.
- **یادداشت تدوین/صدا:** آغاز گزارش نخست

**IMAGE PROMPT — فریم سینمایی**

```text
Two-shot REF_CHAR_D1 reporting to REF_CHAR_LEADER on the fixed rooftop set, D1 cunning and slender, leader listening with severe restraint, warm coffee steam against desaturated dusk, deliberate speaking composition. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH12. D1 leans forward and gestures subtly; leader keeps unblinking focused stare. No invented character speech, narration continues. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH13 — کات بسیار کوتاه به دوست در کتابخانه/کوچه.

- **زمانِ صرفاً پیشنهادی:** 00:55 تا 00:57 (2 ثانیه)
- **لنگر در صوت اصلی:** «رفتم پیش رفیق امینی»
- **تصویر و میزانسن:** کات بسیار کوتاه به دوست در کتابخانه/کوچه.
- **یادداشت تدوین/صدا:** فلاش‌بک کوتاه

**IMAGE PROMPT — فریم سینمایی**

```text
Flashback vision: REF_CHAR_FRIEND alone in a modest historical Najaf study beside books, thoughtful face; faint abstract shadow reaching the edge of frame, no demon physically touching the person, natural realism. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH13. Gentle head turn of the friend toward the empty room, a faint shadow crosses the wall, no magical control effect. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH14 — مونتاژ استعاری وسوسه: سایه‌های گذرا و افکار تکرارشونده، نه نورهای کارتونی.

- **زمانِ صرفاً پیشنهادی:** 00:57 تا 01:02 (5 ثانیه)
- **لنگر در صوت اصلی:** «تو مخش انقدر ... کار شیطان مخ‌مخه‌ست»
- **تصویر و میزانسن:** مونتاژ استعاری وسوسه: سایه‌های گذرا و افکار تکرارشونده، نه نورهای کارتونی.
- **یادداشت تدوین/صدا:** این صحنه برای بخش توضیح گوینده درباره روش وسوسه کشیده/کوتاه شود

**IMAGE PROMPT — فریم سینمایی**

```text
Psychological close-up of REF_CHAR_FRIEND in anxious inner reflection, subtle repetition of an out-of-focus corridor pattern behind him suggesting intrusive thoughts, muted desaturated tones, never text floating around the head, no supernatural possession imagery. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH14. Tiny camera arc as the friend grows uneasy and looks away; muted rhythmic shadow passes behind, maintain anatomically stable expression and period wardrobe. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH15 — دوست در برابر اثر نوشته/موفقیت علمی علامه

- **زمانِ صرفاً پیشنهادی:** 01:02 تا 01:06 (4 ثانیه)
- **لنگر در صوت اصلی:** «بد نیست انقدر امینی گنده شده؟ حسادتشو یه مقدار آوردم بالا»
- **تصویر و میزانسن:** دوست در برابر اثر نوشته/موفقیت علمی علامه؛ حسادت با نگاه نشان داده شود.
- **یادداشت تدوین/صدا:** روی عبارت «حسادت» کات به نگاه

**IMAGE PROMPT — فریم سینمایی**

```text
Period scholar friend REF_CHAR_FRIEND seeing stacked research books associated with REF_CHAR_AMINI, expression subtly tightening into envy, respectful emotionally nuanced 3D close-up; no literal visual judgment and no text with fake Arabic characters. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH15. Natural micro-expression from neutral curiosity to suppressed jealousy, subtle hand tightening over a book. Preserve modest intensity. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH16 — واکنش اول رئیس، تأیید مقتدرانه.

- **زمانِ صرفاً پیشنهادی:** 01:06 تا 01:08 (2 ثانیه)
- **لنگر در صوت اصلی:** «گفت احسنت»
- **تصویر و میزانسن:** واکنش اول رئیس، تأیید مقتدرانه.
- **یادداشت تدوین/صدا:** تأیید کوتاه

**IMAGE PROMPT — فریم سینمایی**

```text
Tight portrait of REF_CHAR_LEADER in the exact rooftop lighting, faint cold smirk and a tiny approving nod, dangerous composure, shallow depth of field, approved facial geometry. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH16. One small approving nod and almost imperceptible smile, clean hold for edit. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH17 — گزارش دوم همراه با تصویر شاگردان در فضای درس

- **زمانِ صرفاً پیشنهادی:** 01:08 تا 01:13 (5 ثانیه)
- **لنگر در صوت اصلی:** «رفتم پیش چند تا از شاگردای امینی ... شبهه»
- **تصویر و میزانسن:** گزارش دوم همراه با تصویر شاگردان در فضای درس؛ بدون جزئیات مذهبی ساختگی.
- **یادداشت تدوین/صدا:** از تداخل شیطان و شاگردان در یک قاب چندجهانی خودداری شود

**IMAGE PROMPT — فریم سینمایی**

```text
Medium-wide period religious classroom with REF_CHAR_STUDENT1 and REF_CHAR_STUDENT2 among wooden desks and manuscripts, attentive yet worried glances, a subtle shadow beyond an arch symbolizing doubt, respectful treatment of religious learning, historical Najaf atmosphere. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH17. Slow sideways camera slide; students exchange measured uncertain looks and glance down at notes. Do not create text on manuscripts. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH18 — بازگشت کوتاه رئیس و آغاز گزارش سوم با حرکت دوربین به زیر‌دست سوم.

- **زمانِ صرفاً پیشنهادی:** 01:13 تا 01:17 (4 ثانیه)
- **لنگر در صوت اصلی:** «گفت احسنت ... من با زن علامه امینی»
- **تصویر و میزانسن:** بازگشت کوتاه رئیس و آغاز گزارش سوم با حرکت دوربین به زیر‌دست سوم.
- **یادداشت تدوین/صدا:** پل گزارشی کوتاه

**IMAGE PROMPT — فریم سینمایی**

```text
Rooftop three-quarter medium shot from leader REF_CHAR_LEADER toward the distinct subordinate REF_CHAR_D3, leader acknowledging previous report while D3 leans in to speak, fixed identical group positions, careful continuity. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH18. Leader nods once, camera pans only a few degrees to D3 taking turn. No crossing of camera axis. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH19 — همسر در خانه با چهره متفکر، نه متهم.

- **زمانِ صرفاً پیشنهادی:** 01:17 تا 01:19 (2 ثانیه)
- **لنگر در صوت اصلی:** «رو ذهنش انقدر کار کردم»
- **تصویر و میزانسن:** همسر در خانه با چهره متفکر، نه متهم.
- **یادداشت تدوین/صدا:** نمای کوتاه همسر

**IMAGE PROMPT — فریم سینمایی**

```text
REF_CHAR_WIFE in modest historical Najaf home interior, respectful full traditional covering according to approved sheet, privately concerned while looking out from an arched window, warm afternoon light, compassionate portrayal. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH19. Wife slowly looks from a folded cloth toward the distant window, no exaggerated distress, no demon visual near body. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH20 — همسر به مسیر خارج از نجف فکر می‌کند

- **زمانِ صرفاً پیشنهادی:** 01:19 تا 01:24 (5 ثانیه)
- **لنگر در صوت اصلی:** «که امینی رو از شهر نجف خارج کنه»
- **تصویر و میزانسن:** همسر به مسیر خارج از نجف فکر می‌کند؛ فقط تداعی سفر، نه تحقق خروج.
- **یادداشت تدوین/صدا:** وسوسه از طریق نگرانی، نه بدخواهی همسر

**IMAGE PROMPT — فریم سینمایی**

```text
Symbolic family worry: REF_CHAR_WIFE beside a modest packed fabric travel bag still unopened, distant view of Najaf rooftops through window, solemn uncertain expression, warm muted realism, the scholar has NOT departed. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH20. Very slow move from unclosed travel bag to wife looking out window; restrained motion, no actual departure scene. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH21 — گزارش چهارم روی پشت‌بام

- **زمانِ صرفاً پیشنهادی:** 01:24 تا 01:28 (4 ثانیه)
- **لنگر در صوت اصلی:** «یکی دیگه ... به امینی ... تو ذهنش بندازم که از نجف بره»
- **تصویر و میزانسن:** گزارش چهارم روی پشت‌بام؛ کات ذهنی علامه کنار وسایل مطالعه، تردیدِ گذرا.
- **یادداشت تدوین/صدا:** برای افکار خود علامه شات تصویری جدا در تدوین در صورت نیاز استفاده شود

**IMAGE PROMPT — فریم سینمایی**

```text
REF_CHAR_D4 nervously reporting before REF_CHAR_LEADER on the fixed rooftop, the subordinate uneasy and slightly bent, leader starting to grow displeased, threatening gray rim light and realistic textures. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH21. D4 motions uncertainly with one hand while leader stops smiling and tenses. Avoid jump cut in single generated clip. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH22 — اوج خشم رئیس: از نشسته به نیم‌خیز

- **زمانِ صرفاً پیشنهادی:** 01:28 تا 01:36 (8 ثانیه)
- **لنگر در صوت اصلی:** «مگه من بهت نگفتم که نذار امینی بره حرم؟»
- **تصویر و میزانسن:** اوج خشم رئیس: از نشسته به نیم‌خیز؛ چهار زیردست واکنش.
- **یادداشت تدوین/صدا:** طبق تأکید گوینده روی «نذار امینی بره حرم؟» ضرباهنگ بیشتر شود

**IMAGE PROMPT — فریم سینمایی**

```text
Cinematic medium-low angle REF_CHAR_LEADER erupting in restrained but commanding anger on rooftop, one hand stabbing toward nervous REF_CHAR_D4, other three subordinates freeze, harsh side rim light, exactly five characters, grounded dark fantasy, no flames or violence. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH22. Leader abruptly leans forward from sitting position, points once, then holds an angry gaze; four subordinate reactions are small. Film with a controlled quick push-in and end on his eyes. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH23 — مونتاژ معنوی برگشت به توسل: همان نمای تأییدشده حرم، نور طبیعی و فروکش سایه‌های ذهنی.

- **زمانِ صرفاً پیشنهادی:** 01:36 تا 01:43 (7 ثانیه)
- **لنگر در صوت اصلی:** «امینی رفت حرم، همه کارهای شماییم به هم خورد»
- **تصویر و میزانسن:** مونتاژ معنوی برگشت به توسل: همان نمای تأییدشده حرم، نور طبیعی و فروکش سایه‌های ذهنی.
- **یادداشت تدوین/صدا:** نقطه اوج: هماهنگ با «همه کارهای شما به هم خورد»

**IMAGE PROMPT — فریم سینمایی**

```text
Intercut-ready symbolic portrait of REF_CHAR_AMINI praying at the same verified shrine lattice, glorious but realistic reflected gold light, outside shadow dissolving softly; reverent imagery of spiritual hope, no visible Imam or other sacred person, match shot 3 in identity and shrine geometry. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH23. Slow push toward the exact Amini prayer pose, daylight reflections brighten subtly and diffuse darkness fades; no beams attacking creatures, no exaggerated VFX. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH24 — رئیس مستقیم به جایگاه ناظر نگاه می‌کند

- **زمانِ صرفاً پیشنهادی:** 01:43 تا 01:48 (5 ثانیه)
- **لنگر در صوت اصلی:** «نشون به این نشون که الآن هم داره ما رو می‌بینه»
- **تصویر و میزانسن:** رئیس مستقیم به جایگاه ناظر نگاه می‌کند؛ لحظه کشف.
- **یادداشت تدوین/صدا:** یک سکوت یا افت موسیقی زیر جمله

**IMAGE PROMPT — فریم سینمایی**

```text
Extreme close-up of REF_CHAR_LEADER turning his piercing gaze straight toward camera on dream rooftop, the other four figures as dim frozen shapes behind, controlled dread, cinematic compressed perspective, no uncanny face melting. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH24. Leader slowly shifts gaze directly into lens, stops speaking, holds a beat; depth of field isolates his eyes. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH25 — پنج موجود هم‌زمان رو به دوربین، بدون تغییر تعداد.

- **زمانِ صرفاً پیشنهادی:** 01:48 تا 01:52 (4 ثانیه)
- **لنگر در صوت اصلی:** «همه‌شون رو کردن به من»
- **تصویر و میزانسن:** پنج موجود هم‌زمان رو به دوربین، بدون تغییر تعداد.
- **یادداشت تدوین/صدا:** ضربه تصویری

**IMAGE PROMPT — فریم سینمایی**

```text
Full group front view on rooftop: EXACTLY FIVE approved demon characters all facing the unseen Amini viewpoint, unmistakable distinct silhouettes and face designs, night wind, horror-through-sudden-recognition rather than gore. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH25. Coordinated turn of exactly five heads toward camera, slight stagger for realism, maintain seated body positions and unique characters, quick controlled camera sway. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH26 — فریم انتهایی هجوم نمادین و کات سخت به چشم باز علامه.

- **زمانِ صرفاً پیشنهادی:** 01:52 تا 01:55 (3 ثانیه)
- **لنگر در صوت اصلی:** «اومدن سمت من، من از خواب بیدار شدم»
- **تصویر و میزانسن:** فریم انتهایی هجوم نمادین و کات سخت به چشم باز علامه.
- **یادداشت تدوین/صدا:** در تدوین به پلان بیداری کات شود

**IMAGE PROMPT — فریم سینمایی**

```text
Dream perspective of five unnatural silhouettes advancing a step toward viewer through rooftop haze, foreboding but nonviolent, designed to hard-cut to Amini waking. Separate approved waking-room plate needed for final edit. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH26. All five lean and take one restrained synchronized step closer; end with rapid forward motion blur for a hard match cut, no gore and no grabbing camera. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

### SH27 — علامه بیدار، آرامش پس از شگفتی

- **زمانِ صرفاً پیشنهادی:** 01:55 تا 02:00 (5 ثانیه)
- **لنگر در صوت اصلی:** «یعنی یه حرم رفتن، یه توسل ...»
- **تصویر و میزانسن:** علامه بیدار، آرامش پس از شگفتی؛ اختتام به نمای حرم با پایان صوت.
- **یادداشت تدوین/صدا:** با آخرین کلمه گوینده فید به سیاهی

**IMAGE PROMPT — فریم سینمایی**

```text
Medium close-up REF_CHAR_AMINI sitting upright after waking in REF_ENV_ROOM, startled breath subsiding into gratitude and inner composure, afternoon window light, cinematic quiet resolution, optional separately edited last-frame dissolve to verified shrine exterior. Apply the global visual style, approved continuity references and negative constraints from sections 3-5. Single clear 16:9 cinematic keyframe, no typography.
```

**IMAGE-TO-VIDEO PROMPT — حرکت همین تصویر**

```text
Animate only the exact approved keyframe for SH27. Amini opens eyes, sits up naturally, breathes once, turns his gaze to window, holds a contemplative end pose. No added lips or external spoken sentence. Keep cast identity, wardrobe, lens and location topology identical to input references. Natural 24 fps motion. No extra characters, no newly generated speech, no captions. Provide clean editable head/tail handles.
```

## ۷. مدیریت تایم‌لاین پس از تحلیل صوت

ایجنت باید با الگوریتم زیر خروجی واقعی بسازد:

1. هر لنگر بالا را به `(audio_start, audio_end)` نگاشت کن.
2. عبارت «کار شیطان مخ‌مخه‌ست...» یک **توضیح طولانی گوینده** است و با مجموعه نماهای دوست / سایه / تفکر پوشش داده شود؛ ممکن است SH13–SH15 مدت بسیار بیشتری نیاز داشته باشند.
3. «احسنت»‌ها با ریتم خود کلمه و مکث آن اجرا شوند؛ تکرارِ واکنش رئیس صرفاً در همان جای واقعی صوت باشد.
4. بخش تأکید «مگه من بهت نگفتم که نذار امینی بره حرم» باید متناسب با مکث و شدت صدای واقعی، دست‌کم یک نمای واکنش و یک نمای چهره رئیس داشته باشد؛ در صورت طولانی‌بودن، SH22 را به دو برداشت تقسیم کن.
5. جمله «الآن هم داره ما رو می‌بینه» باید روی تماس چشمی رئیس با دوربین تمام شود؛ سپس چرخش هم‌زمان گروه.
6. بیداری نباید جلوتر از جمله «من از خواب بیدار شدم» اتفاق بیفتد.
7. کات نهایی دقیقاً روی پایان صدای اصلی یا یک tail صوتی طبیعی قرار گیرد.

فرمت نمونه `edit/final_timeline.csv`:

```csv
shot_id,audio_in,audio_out,visual_asset,transition,anchor,verified
SH01,TO_BE_MEASURED,TO_BE_MEASURED,SH01_master.mov,cut,"معرفی داستان",false
SH02,TO_BE_MEASURED,TO_BE_MEASURED,SH02_master.mov,cut,"رفتم تو حرم",false
```

**هیچ `TO_BE_MEASURED` نباید در فایل تایم‌لاین نهایی باقی بماند.**

## ۸. خط تولید خودکار/نیمه‌خودکار ایجنت

### Gate A — Audio Lock

- [ ] فایل صوت اصلی موجود و سالم است.
- [ ] مدت دقیق، هش و سطح صدا ثبت شد.
- [ ] متن و بازه زمانی جمله‌ها با بازشنوی بررسی شد.
- [ ] تعداد شات‌ها بر اساس سرعت واقعی روایت بازتنظیم شد.

### Gate B — Design Lock

- [ ] عکس چهره واقعی علامه تأیید شد.
- [ ] تمام شیت‌های انسانی و شیاطین کامل شد.
- [ ] پنج موجود کنار هم بدون تکرار چهره نمایش داده شدند.
- [ ] معماری حرم، خانه و پشت‌بام تأیید و قفل شد.
- [ ] نمونه ۵ تا ۸ثانیه‌ای آزمایشی برای ثبات چهره و حرکت ساخته شد.

### Gate C — Storyboard / Animatic

- [ ] برای همه شات‌ها Keyframe ساخته شد.
- [ ] یک استوری‌بورد صفحه‌بندی‌شده با شماره شات و موج صوتی ساخته شد.
- [ ] Animatic با عکس ثابت روی **صوت واقعی** چیده و بازبینی شد.
- [ ] قاب‌بندی‌های تکراری و پرش محور دوربین حذف شدند.

### Gate D — Final Generation

- [ ] کلیپ‌ها تک‌شات تولید و هویت کاراکترها کنترل شد.
- [ ] بازتولیدهای ناموفق با `take02`, `take03` ذخیره شدند.
- [ ] کلیپ تأییدشده هر شات با `master` مشخص شد.
- [ ] صحنه‌هایی که به دو حرکت نیاز داشتند به شات‌های مجزا تفکیک شدند.

### Gate E — Edit & Sound

- [ ] صدای اصلی بدون حذف یا دوبله، ستون ثابت تایم‌لاین است.
- [ ] موسیقی از ابتدا زیر گفتار باقی می‌ماند و مانع فهم واژه‌ها نیست.
- [ ] افکت‌های محیطی ملایم و دقیق، تنها در نقاط مناسب هستند.
- [ ] هیچ لب‌خوانی ناهماهنگ یا گفتار غیرموجود دیده/شنیده نمی‌شود.
- [ ] زیرنویس از متن **همان صوت** تولید شده است.

### Gate F — QC & Delivery

- [ ] شمار شخصیت‌های روی پشت‌بام همیشه **یک رئیس + چهار زیردست = پنج** است.
- [ ] چهره، عمامه، عبا، دست‌ها و قد علامه در کلیپ‌ها تغییر نکرده است.
- [ ] هر زیردست از ابتدا تا انتها صورت و لباس مشخص خود را دارد.
- [ ] ضریح یا معماری خانه میان نماها جابه‌جا نمی‌شود.
- [ ] کیفیت حرکت دست و فنجان، راه‌رفتن، پلک، نشستن و بیداری تأیید شده است.
- [ ] همزمانی کات‌ها با نقاط مهم کلام واقعی با بازبینی صوتی پذیرفته شده است.
- [ ] خروجی نهایی از نظر فریم سیاه، سکوت ناخواسته، فریز و artifact بررسی شده است.

## ۹. ساختار فایل و تحویل پروژه

```text
amini-tawassul/
├── README.md
├── PRODUCTION_BIBLE.md
├── audio/
│   ├── master_original.wav          # or actual original extension
│   ├── audio_metadata.json
│   ├── transcript_verified.fa.txt
│   ├── word_timestamps.json
│   ├── phrase_timestamps.json
│   └── subtitles.fa.srt
├── references/
│   ├── historical_amini/
│   ├── historical_najaf/
│   ├── shrine/
│   └── references_licenses.csv
├── characters/
│   ├── character_bible.json
│   ├── REF_CHAR_AMINI/
│   ├── REF_CHAR_LEADER/
│   ├── REF_CHAR_D1/
│   ├── REF_CHAR_D2/
│   ├── REF_CHAR_D3/
│   ├── REF_CHAR_D4/
│   ├── REF_CHAR_WIFE/
│   ├── REF_CHAR_FRIEND/
│   ├── REF_CHAR_STUDENT1/
│   └── REF_CHAR_STUDENT2/
├── environments/
│   ├── REF_ENV_CITY/
│   ├── REF_ENV_SHRINE/
│   ├── REF_ENV_SHRINE_ZARIH/
│   ├── REF_ENV_HOME/
│   ├── REF_ENV_ROOM/
│   ├── REF_ENV_ROOF/
│   └── REF_ENV_CLASS/
├── storyboard/
│   ├── storyboard_contact_sheet.pdf
│   ├── storyboard_contact_sheet.png
│   ├── SH01.png ... SH27.png
│   └── animatic_with_original_audio.mp4
├── video/
│   ├── SH01/take01.mp4
│   ├── SH01/master.mov
│   └── ...
├── edit/
│   ├── final_timeline.csv
│   ├── final_timeline.json
│   └── edit_project/
├── exports/
│   ├── final_16x9.mp4
│   ├── final_clean.mp4
│   └── subtitles.fa.srt
└── reports/
    ├── continuity_qc.md
    ├── audio_sync_qc.md
    └── production_log.md
```

## ۱۰. معیارهای پذیرش محصول

- **صداقت با صوت:** همه جملات شنیداریِ نهایی از فایل اصلی هستند، بدون بازنویسی، حذف عمدی، یا اضافه‌کردن صدای روایتگر.
- **زمان:** طول ویدئو با طول صوت اصلی منطبق است؛ دقیقاً ۱۲۰ ثانیه فقط وقتی صوت یا تدوین مجاز آن همین مدت باشد.
- **تصویر:** شخصیت‌ها شبیه شیت قفل‌شده بمانند؛ پنج موجود از نظر شمار و هویت ثابت باشند.
- **درام:** شروع آرام در حرم، گره‌افکنی در خواب، تکرار وسوسه‌ها، بحران در توبیخ رئیس، پایان معنوی بعد از بیداری.
- **کیفیت:** حداقل 1080p/24fps، بدون اعوجاج آشکار، نماهای منسجم، تدوین روان و فولی حرفه‌ایِ کنترل‌شده.
- **قابلیت ویرایش:** خروجی فقط یک MP4 نباشد؛ فریم‌های مرجع، شات‌های خام، تایم‌کدها و پروژه تدوین تحویل شود.
- **مسئولیت تاریخی:** متن یا تیتراژ ادعا نکند جزئیات رؤیا مستقلاً راستی‌آزمایی شده‌اند.

## ۱۱. پرامپت نهاییِ یک‌تکه برای سپردن به ایجنت

> **AGENT EXECUTION BRIEF**
>
> تو کارگردان، استوری‌بورد آرتیست، طراح شخصیت، متخصص تولید تصویر‌به‌ویدئو، تدوین‌گر و کنترل‌کیفیت یک انیمیشن ۳بعدی واقع‌گرایانه هستی. کل سند `PRODUCTION_BIBLE.md` را بخوان. مأموریت تو ساخت فیلم روی **صوت واقعیِ تحویل‌شده** است، نه تولید یک صدای جدید. ترتیب کار اجباری: ابتدا تحلیل صوت، زمان‌بندی دقیق و رونویسی؛ سپس گردآوری تصویر واقعی علامه و شیت تمام کاراکترها؛ سپس قفل محیط‌ها؛ سپس استوری‌بورد روی صوت و Animatic؛ سپس Keyframe و I2V هر شات؛ در پایان مونتاژ، زیرنویس، QC و تحویل دارایی‌های قابل ویرایش. از شناسه‌های `REF_...` به‌عنوان رفرنس واقعی تصویر استفاده کن. زمان‌بندی‌های ۱۲۰ ثانیه‌ای این سند صرفاً پیش‌طرح هستند؛ تابع فایل صوت نهایی باش. بدون صوت فقط دارایی‌های مقدماتی بساز. در همه صحنه‌های خواب، دقیقاً پنج موجود (یک رئیس، چهار زیردست) وجود دارد. تغییر چهره علامه، لباس کاراکترها، معماری ضریح، دیالوگ و صدا ممنوع است. خطاها و تصمیم‌های هنری را در `production_log.md` ثبت کن. تا جای ممکن خودکار پیش برو، اما اگر به فایل صوت، مجوز استفاده از تصویر تاریخی یا یک مرجع بنیادی نیاز داری، همان ورودی مشخص را درخواست کن؛ ادعای تکمیل مرحله‌ای که واقعاً اجرا نشده نکن.

---

**ورودیِ لازم برای شروع اجرای واقعی:** فایل صوت کارفرما (ترجیحاً WAV، اما MP3/M4A هم پذیرفته شود) + در صورت وجود عکس مرجع دلخواه از علامه امینی. سایر مشخصات تولید در همین سند موجود است.
