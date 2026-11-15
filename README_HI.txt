FF ID STORE — Android Studio starter project

Design: Gaming Marketplace (dark black + red)
App type: Free Fire player showcase / gaming community directory.

IMPORTANT:
This starter app intentionally does NOT support buying/selling/transferring game accounts.
Game publisher terms may restrict account trading. Do not collect passwords, OTPs,
recovery codes, or payment details. Check the publisher's current terms before
publishing or adding any account-related feature.

How to open:
1. Download and extract this ZIP.
2. Install Android Studio on a computer.
3. Open the extracted FF_ID_STORE folder in Android Studio.
4. Allow Gradle sync to finish.
5. Connect an Android phone with USB debugging enabled, or use an emulator.
6. Press Run.

Included:
- Dark gaming marketplace home screen
- Featured player showcase cards
- Search
- Create player showcase dialog
- Bottom navigation and profile placeholder

Limitations:
- Demo data is kept only in app memory and resets when the app restarts.
- No login, cloud database, image upload, admin moderation, or Play Store signing yet.
- This is Android source code, not a ready-to-install APK.


मोबाइल से Cloud APK build (GitHub Actions):
1. GitHub account बनाएं/लॉगिन करें (किसी अभिभावक की मदद लें यदि जरूरी हो)।
2. नया public या private repository बनाएं, नाम FF-ID-STORE रखें।
3. इस ZIP को extract करके इसके अंदर की सभी files/folders repository में upload करें।
4. Commit changes करें।
5. Repository में Actions tab खोलें। "Build FF ID STORE APK" workflow चुनें।
6. Run workflow दबाएं और build पूरा होने दें।
7. Workflow run के नीचे Artifacts में FF-ID-STORE-debug-apk डाउनलोड करें।
8. ZIP extract करके app-debug.apk फोन में install करें। Android पूछे तो केवल भरोसेमंद build होने पर install अनुमति दें।

यह debug APK है, Play Store release नहीं। यह project demo/local है; कोई production backend नहीं है।
