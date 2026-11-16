# খাবার হিসাব PWA v2

নতুন ফিচার: সকাল/দুপুর/রাতের আলাদা rate, মিল চালু/বন্ধ, custom meal add/delete, dashboard-এ সক্রিয় মিল অনুযায়ী card, billing cycle start day, মাসভিত্তিক হিসাব ও previous balance carry-forward, JSON Backup/Restore, dark/light mode, offline PWA.

চালাতে index.html খুলুন। PWA install/offline cache-এর জন্য HTTPS hosting বা localhost ব্যবহার করুন। ডেটা এই ব্রাউজারের localStorage-এ থাকে।

হিসাবের সময়সীমা: নির্বাচিত মাসের শুরুর দিন থেকে পরের মাসের আগের দিন পর্যন্ত। আগের সময়ের খরচ - জমা = opening balance; opening balance + চলতি সময়ের খরচ - চলতি সময়ের জমা = closing balance.

এই v2 নতুন storage key ব্যবহার করে; আগের সংস্করণের localStorage ডেটা স্বয়ংক্রিয়ভাবে migrate হবে না। পুরোনো ডেটা থাকলে v1 থেকে CSV export করে রাখুন।