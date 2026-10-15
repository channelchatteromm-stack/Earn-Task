EarnTask Android App — APK banane ka asaan tutorial
==================================================

Yeh Android project hai. ZIP ka naam badal kar .apk karne se APK nahi banta.
Is project mein GitHub Actions workflow diya hai jo online APK compile karta hai.

PHONE SE APK BANANE KA TAREEQA (computer ki zaroorat nahi):

1. Is ZIP ko download karke phone mein extract kar lo.
2. Browser mein https://github.com khol kar free account sign in/create karo.
3. New repository banao. Naam: EarnTask (Public ya Private dono theek).
4. Repository mein Add file > Upload files chuno.
5. ZIP ko pehle extract karo. Extract hue EarnTaskReady folder KE ANDAR ki saari files/folders upload karo.
   Dhyaan: app, .github, build.gradle, settings.gradle aur gradle.properties repository ke root par hone chahiye.
   .github folder hidden ho sakta hai. Agar phone se upload nahi ho raha, GitHub website ke bajaye GitHub Desktop/computer use karo.
6. Upload/commit files to the main branch.
7. Repository ke Actions tab mein jao.
8. Agar prompt aaye, “I understand my workflows, go ahead and enable them” dabao.
9. “Build EarnTask APK” workflow kholo aur “Run workflow” dabao. Agar push par build pehle hi start ho gaya ho, us run ko kholo.
10. Build complete hone tak wait karo; status green tick hona chahiye.
11. Successful run ke neeche Artifacts section mein “EarnTask-debug-apk” download karo.
12. Artifact ZIP ko extract karo. Uske andar app-debug.apk milega.
13. APK phone par bhejo/open karo. Android agar pooche, browser/file manager ke liye “Install unknown apps” permission sirf tab allow karo jab tum is build par bharosa karte ho. Phir Install dabao.

APP KYA KARTI HAI?
- Offline demo task tracker
- Demo balance phone par save hota hai
- Practice digital-safety tasks
- Demo withdrawal notice

IMPORTANT:
- Balance sirf demo points hain. Yeh app real paise earn nahi karti aur UPI payment nahi bhejti.
- APK debug build hai, personal testing ke liye. Public release ke liye signed release build ki zaroorat hoti hai.
- GitHub par upload karne se pehle code dekh lo; kisi bhi account mein password/API keys mat daalo.
- Build fail ho to Actions ke red failed run ko kholo aur error ka screenshot/text bhejo.
