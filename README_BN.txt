ALL-IN-ONE DIGITAL NOTEBOOK — ANDROID + GITHUB PAGES

ফিচার:
- বাংলা/English interface
- নোট যোগ, সম্পাদনা, মুছে ফেলা
- সার্চ, ক্যাটাগরি ও তারিখ অনুযায়ী সাজানো
- JSON backup export/import
- Service worker দিয়ে অফলাইনে খোলার সুবিধা
- Local browser storage; নোট নিজে থেকে GitHub/Cloud-এ যায় না

Android থেকে প্রকাশ:
1. ZIP ডাউনলোড করে File Manager-এ Extract করুন।
2. https://github.com/new খুলে Public repository তৈরি করুন; নাম দিন all-in-one-notebook
3. Add file > Upload files থেকে index.html, manifest.json, sw.js, icon-192.png, icon-512.png আপলোড করে Commit changes চাপুন। README চাইলে আপলোড করতে পারেন।
4. Repository > Settings > Pages > Build and deployment: Deploy from a branch নির্বাচন করুন।
5. Branch: main, folder: /(root) নির্বাচন করে Save করুন।
6. কয়েক মিনিট পরে Pages-এ দেখানো ওয়েব ঠিকানা খুলুন।

দীর্ঘমেয়াদি ব্যাকআপ:
- নোটবুক খুলে Backup Export চাপুন।
- তৈরি হওয়া notebook-backup-তারিখ.json ফাইল Google Drive-এ আপলোড করুন।
- অন্য ফোন/ব্রাউজারে নোট ফেরাতে Import Backup চাপুন এবং JSON ফাইল নির্বাচন করুন।
- একই ব্রাউজারের site data মুছে ফেললে local notes হারাতে পারে; তাই নিয়মিত backup জরুরি।

গুরুত্বপূর্ণ নিরাপত্তা:
- Public repository-তে ব্যক্তিগত নোট বা backup JSON আপলোড করবেন না।
- GitHub Version History শুধু repository-র কোড/ফাইলের পরিবর্তন দেখায়; browser-এ লেখা নোটের history নয়।
- এটি প্রাথমিক, একক-ব্যবহারকারীর সংস্করণ। একাধিক ডিভাইসে স্বয়ংক্রিয় sync বা account login নেই।

পাসওয়ার্ড স্ক্রিন:
- ওয়েবসাইট খুললে পাসওয়ার্ড চাইবে।
- এটি কেবল সাধারণ বাধা; পাসওয়ার্ড HTML/JavaScript ফাইলে দেখা বা পাশ কাটানো সম্ভব।
- তাই সংবেদনশীল/ব্যক্তিগত নোট সুরক্ষার জন্য এটিকে যথেষ্ট নিরাপদ ধরে নেবেন না।
- সত্যিকারের নিরাপত্তার জন্য Cloudflare Access, Firebase Authentication বা অন্য সার্ভার-ভিত্তিক login লাগবে। GitHub Pages একা private authentication দেয় না।

ইনস্টল:
- GitHub Pages-এ HTTPS লিংক Chrome-এ খুলুন।
- Install app বাটন চাপুন। না দেখালে Chrome-এর ⋮ মেনু > Add to Home screen / Install app।
- PWA ইনস্টল করতে manifest, icons ও service worker একই root-এ থাকতে হবে।

পাসওয়ার্ড:
- প্রাথমিক পাসওয়ার্ড: 01767062398
- Forgot password-এ রিকভারি কোড: NB-RESET-62398
- রিকভারি কোড দিয়ে নতুন পাসওয়ার্ড (কমপক্ষে ৮ অক্ষর) সেট করা যাবে।
- সতর্কতা: এগুলো static client-side gate; public GitHub source থেকে পাসওয়ার্ড/রিকভারি কোড দেখা ও বাধা পাশ কাটানো সম্ভব। সংবেদনশীল তথ্যের জন্য এটি নিরাপদ authentication নয়।

PDF ও প্রিন্ট:
- নোটবুকের PDF ডাউনলোড বা Print / প্রিন্ট বাটনে চাপুন।
- নতুন ট্যাবে প্রিন্ট উইন্ডো খুলবে। Android Chrome-এর print dialog-এ printer dropdown থেকে "Save as PDF" নির্বাচন করে PDF সেভ করুন।
- শুধু সার্চ/ক্যাটাগরি ফিল্টারে দেখা নোটগুলোই PDF/প্রিন্ট হবে।
- ব্রাউজার পপ-আপ ব্লক করলে সাইটের জন্য pop-ups অনুমতি দিন।
