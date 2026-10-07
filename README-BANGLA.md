# Fiber Network Android App

এই project-টি ফোন থেকে GitHub Actions দিয়ে APK build করার জন্য প্রস্তুত।

## ফোনে APK বানানোর নিয়ম
1. GitHub-এ নতুন repository তৈরি করুন।
2. এই ZIP-এর `FiberNetworkApp` folder-এর ভেতরের সব ফাইল repository-তে upload করুন।
3. GitHub → Actions → **Build Fiber Network APK** → **Run workflow** চাপুন।
4. Build শেষ হলে Actions run খুলে **Artifacts** থেকে `FiberNetwork-debug-apk` ZIP download করুন।
5. ZIP খুলে `app-debug.apk` install করুন।

## GPS
অ্যাপের ভিতরে Android native location permission ব্যবহার করা হয়েছে। Chrome-এর file:// GPS permission-এর ওপর নির্ভর করে না।
