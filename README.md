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

Safety Isolation: Uses high-impedance mode (INPUT_PULLUP) on inactive relays to ensure zero current leakage.

Flicker-Free Dimming: 5kHz PWM frequency via MJE13005 for smooth DC LED control.
