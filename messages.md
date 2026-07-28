Dental Clinic WhatsApp Bot Messages
State 0 – Language Detection (Internal Logic)

Purpose: Detect whether the user's message is in English or Arabic.

If the message contains Arabic script, reply in Arabic.
Otherwise, reply in English.
If the user switches languages during the conversation, the bot detects the change and continues in the new language.

Note: This is an internal process, so there is no customer-facing message.

State 1 – Greeting & Intent
🇬🇧 English

Welcome to SmileCare Dental Clinic! 🦷

We're happy to assist you today.

How can we help you?

1️⃣ Book an appointment
2️⃣ Ask a question

Please reply with 1 or 2.

🇸🇦 Arabic

مرحبًا بك في عيادة سمايل كير لطب الأسنان! 🦷

يسعدنا مساعدتك اليوم.

كيف يمكننا مساعدتك؟

1️⃣ حجز موعد
2️⃣ طرح سؤال

يرجى الرد بالرقم 1 أو 2.

State 2 – Choose Service
🇬🇧 English

Great! Which dental service are you interested in?

1️⃣ Dental Check-up

2️⃣ Teeth Cleaning

3️⃣ Teeth Whitening

4️⃣ Root Canal

5️⃣ Braces Consultation

Please reply with the number of your preferred service.

🇸🇦 Arabic

رائع!

ما الخدمة التي ترغب بها؟

1️⃣ فحص الأسنان

2️⃣ تنظيف الأسنان

3️⃣ تبييض الأسنان

4️⃣ علاج العصب

5️⃣ استشارة تقويم الأسنان

يرجى إرسال رقم الخدمة المطلوبة.

State 3 – Preferred Date & Time
🇬🇧 English

Perfect!

Please tell us your preferred appointment date and approximate time.

Example:

📅 Monday

🕙 10:00 AM

🇸🇦 Arabic

ممتاز!

يرجى إخبارنا بالتاريخ والوقت المناسبين لك.

مثال:

📅 الإثنين

🕙 10:00 صباحًا

State 4 – Offer Available Slots
🇬🇧 English

These appointment slots are currently available:

✅ Monday – 10:00 AM

✅ Monday – 2:00 PM

✅ Tuesday – 11:00 AM

Please reply with the number of your preferred slot.

🇸🇦 Arabic

المواعيد المتاحة حاليًا هي:

✅ الإثنين – 10:00 صباحًا

✅ الإثنين – 2:00 مساءً

✅ الثلاثاء – 11:00 صباحًا

يرجى إرسال رقم الموعد الذي تفضله.

State 5 – Booking Confirmation
🇬🇧 English

🎉 Your appointment has been confirmed!

Booking Summary

🏥 Clinic: SmileCare Dental Clinic

🦷 Service: Teeth Cleaning

📅 Date: Monday

🕙 Time: 10:00 AM

Thank you for choosing SmileCare Dental Clinic. We look forward to seeing you!

🇸🇦 Arabic

🎉 تم تأكيد موعدك بنجاح!

ملخص الحجز

🏥 العيادة: سمايل كير لطب الأسنان

🦷 الخدمة: تنظيف الأسنان

📅 التاريخ: الإثنين

🕙 الوقت: 10:00 صباحًا

شكرًا لاختيارك عيادة سمايل كير، ونتطلع إلى زيارتك.

Nudge 1 (+1 Hour)
🇬🇧 English

Hi! 👋

We noticed you haven't completed your appointment booking yet.

Would you like to continue?

🇸🇦 Arabic

مرحبًا! 👋

لاحظنا أنك لم تكمل حجز موعدك بعد.

هل ترغب في المتابعة؟

Nudge 2 (+24 Hours)

Note: In a real deployment, this reminder must be sent as a pre-approved WhatsApp template message because it is outside the 24-hour customer-service window.

🇬🇧 English

Hello!

We're still here if you'd like to book your dental appointment.

Reply to this message to continue.

🇸🇦 Arabic

مرحبًا!

ما زلنا بانتظارك إذا كنت ترغب في حجز موعد.

قم بالرد على هذه الرسالة للمتابعة.

Nudge 3 (+72 Hours)

Note: In a real deployment, this reminder must also be sent using a pre-approved WhatsApp template message.

🇬🇧 English

Hello!

We're available whenever you're ready to schedule your appointment.

Feel free to message us anytime.

🇸🇦 Arabic

مرحبًا!

نحن هنا عندما تكون مستعدًا لحجز موعدك.

يمكنك مراسلتنا في أي وقت.

Human Handoff
🇬🇧 English

Thank you for contacting SmileCare Dental Clinic.

Your request requires assistance from one of our team members.

We are connecting you to a human representative now. Please wait a moment.

🇸🇦 Arabic

شكرًا لتواصلك مع عيادة سمايل كير لطب الأسنان.

يتطلب طلبك مساعدة أحد أعضاء فريقنا.

سيتم تحويلك الآن إلى أحد ممثلي خدمة العملاء. يرجى الانتظار قليلًا.
