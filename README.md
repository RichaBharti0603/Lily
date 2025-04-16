# Lily

💡 Problem Statement
Victims of domestic violence often can't call for help openly due to fear, surveillance, or proximity to their abuser. There is a need for a discreet, secure, and fast way to alert authorities or trusted contacts silently.

🎯 Objective
To develop a mobile application that enables users to send silent alerts (via tap pattern, voice command, or background button) to pre-configured emergency contacts or authorities without drawing attention.

🛠️ Core Features

Feature	Description
🔕 Silent SOS Trigger	Triple-tap on the phone screen, shake device, or whisper a code word to send an alert.
📍 Location Tracking	Sends current GPS location to emergency contacts.
🗣️ Secret Voice Command	User whispers a configured safe word (e.g., "I'm okay") that triggers an alert.
🧍‍♀️ Fake Interface	App looks like a harmless utility (e.g., calculator), but turns into emergency mode on input.
📸 Auto Media Capture (Optional)	Captures 3-second video/audio & sends with alert.
🔐 Data Encryption	Ensures that personal info & alert data is securely stored and transmitted.
💌 Emergency Contact Setup	User adds trusted contacts who receive alerts.
🛑 Cancel Alert Button	A hidden pattern/word to cancel accidental alerts.
📖 Awareness & Resources	Includes legal help, helpline numbers, support groups, blogs.
📱 Tech Stack (Mobile App First)
Frontend: Flutter (cross-platform UI)

Backend: Firebase (for Realtime DB, Auth, Notifications)

APIs:

Google Maps API (for location)

Twilio (for emergency SMS/call)

Google Speech-to-Text (for whisper commands)

Security: Encrypted local storage using Flutter Secure Storage or similar.

🧩 User Flow
Signup/Login
→ Setup emergency contacts
→ Set safe words, gestures, triggers.

Silent Trigger
→ App detects the trigger
→ Collects GPS, optional audio/video
→ Sends alert silently via Firebase backend or SMS.

Emergency Contacts Receive Alert
→ With location, message, & media (if any)

User Dashboard
→ Safe zone mapping
→ Awareness material
→ Cancel alert functionality

🎨 Design Vibe
Minimalist and calm color scheme (lavender, soft greys)

Clean, discreet UI (think: looks like a utility app)

Easily accessible emergency trigger without needing to unlock app

🌐 Future Add-ons
Multilingual support

Real-time chat with a counselor

AI voice detection for stress/emotion

Community support forums (moderated)

