# মামুন টেলিকম Android App

এই প্রজেক্টে GitHub Actions workflow দেওয়া আছে। GitHub-এ upload/push করলে Actions স্বয়ংক্রিয়ভাবে APK build করবে।

## মোবাইল থেকে APK বানানোর সহজ নিয়ম
1. GitHub-এ নতুন repository তৈরি করুন।
2. এই ZIP-এর ফাইলগুলো repository-তে upload করুন (ZIP ফাইল নিজে নয়; ZIP খুলে সব ফাইল)।
3. Actions ট্যাব → Build Mamun Telecom APK → Run workflow।
4. কাজ শেষ হলে workflow-এর Artifacts থেকে `Mamun-Telecom-APK` ডাউনলোড করুন।
5. ZIP খুলে `app-debug.apk` ফোনে install করুন।

নোট: প্রথমবার GitHub-এ upload করার পর build হতে কয়েক মিনিট লাগতে পারে।
