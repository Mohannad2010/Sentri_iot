Sentri: Smart Logic Home Controller 🛡️

نظام "سنتري" للتحكم المنزلي بالمنطق الذكي

📖 Overview | نظرة عامة
English:

Sentri is an advanced IoT controller that goes beyond simple switching. It implements a Smart Mode Engine that allows a single interface to execute complex household scenarios (Sleep, Work, All) with a mix of AC relay control and DC PWM dimming.

بالعربية:

"سنتري" هو متحكم إنترنت أشياء متطور يتجاوز مجرد التشغيل والإطفاء البسيط. يعتمد النظام على محرك أوضاع ذكي يسمح بتنفيذ سيناريوهات منزلية معقدة (النوم، العمل، التشغيل الكامل) عبر مزيج من التحكم في الريليهات (AC) وتعتيم الإضاءة (DC PWM).

🎮 Smart Operation Modes | أوضاع التشغيل الذكية
English:

The system features 3 dedicated physical switches to trigger preset scenarios:

Sleep Mode: Ideal for nighttime; turns off all lights, keeps one primary socket active, and disables the second for safety.

Work Mode: Optimized for productivity; activates all sockets, sets LED strip brightness to 35%, and switches on the workspace light.

All Mode: One-touch activation for the entire system (All lights & sockets ON).

بالعربية:

يتميز النظام بـ 3 مفاتيح فيزيائية مخصصة لتفعيل سيناريوهات محددة مسبقاً:

وضع النوم: مثالي لفترة الليل؛ يطفئ جميع الأضواء، يترك قابساً واحداً يعمل، ويعطل القابس الثاني للأمان.

وضع العمل: مخصص للإنتاجية؛ يشغل جميع المقابس، يضبط سطوع اللد على 35%، ويشغل ضوء مكتب العمل.

وضع الكل: تفعيل بلمسة واحدة لجميع أجزاء النظام (كل الأضواء والمقابس تعمل).

🛠️ Technical Highlights | مميزات تقنية

Dual-Layer Control: Integrated with Arduino IoT Cloud for voice control (Siri/Google Home) and physical switches for local reliability.

تحكم ثنائي الطبقات: متكامل مع سحابة أردوينو للتحكم الصوتي عبر (سيري وجوجل هوم)، مع مفاتيح فيزيائية لضمان الموثوقية والعمل محلياً حتى عند انقطاع الإنترنت.

Safety Isolation Logic: Uses high-impedance mode (INPUT_PULLUP) on inactive relays to ensure zero current leakage and prevent "ghost" triggering.

منطق العزل الآمن: يستخدم وضع المقاومة العالية (INPUT_PULLUP) على الريليهات غير النشطة لضمان عدم وجود أي تسريب للتيار ومنع التشغيل العشوائي.

Flicker-Free DC Dimming: Advanced 5kHz PWM frequency control via the MJE13005 transistor for smooth, professional LED strip transitions.

تعتيم تيار مستمر بدون وميض: تحكم متقدم بتردد 5 كيلو هرتز (PWM) عبر ترانزستور MJE13005 لضمان انتقال ناعم واحترافي لسطوع أشرطة اللد.

Smart State Sync: Real-time synchronization between the physical environment and the cloud dashboard upon connection.

مزامنة الحالة الذكية: مزامنة فورية بين الحالة الفعلية للمفاتيح ولوحة التحكم السحابية بمجرد الاتصال.

📦 Required Libraries | المكتبات المطلوبة

English: Before uploading the code, ensure you have installed the following libraries via the Arduino Library Manager:

WiFiManager (by tablatronix)

ArduinoIoTCloud (by Arduino)

Arduino_ConnectionHandler (by Arduino)


بالعربية: قبل رفع الكود، تأكد من تثبيت المكتبات التالية عبر مدير المكتبات في أردوينو (Library Manager):

WiFiManager

ArduinoIoTCloud

Arduino_ConnectionHandler

Conclusion | خاتمة

English:

Sentri represents a successful integration of custom hardware logic and modern IoT cloud services. By balancing physical control with voice automation and safety-first programming, this project serves as a robust, completed solution for smart home management.

Note from the Developer:

This project was fully designed and coded by a 16-year-old student with a passion for engineering and automation. It stands as a testament that with curiosity and the right tools, innovation has no age limit.

بالعربية:

يمثل مشروع "سنتري" نموذجاً ناجحاً للدمج بين منطق العتاد المخصص وخدمات السحاب الذكية الحديثة. من خلال الموازنة بين التحكم الفيزيائي والأتمتة الصوتية، ومعايير البرمجة التي تضع الأمان أولاً، يعد هذا المشروع حلاً متكاملاً وقوياً لإدارة المنزل الذكي.

كلمة من المطور:

تم تصميم وبرمجة هذا المشروع بالكامل من قبل طالب في السادسة عشرة من عمره، مدفوعاً بالشغف بالهندسة والأتمتة؛ ليكون دليلاً على أن الابتكار لا يعرف حدوداً عمرية متى ما توفر الطموح والأدوات الصحيحة.
