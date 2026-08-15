<div align="center">

<!-- TANVIR AI Chatbot Logo -->
<img src="assets/logo.jpg" alt="TANVIR AI Chatbot Logo" width="180" height="180"/>

# ✨ TANVIR AI Chatbot ✨

### 🤖 সম্পূর্ণ স্মার্ট WhatsApp AI চ্যাটবট — প্রশ্ন, ছবি তৈরি, সবকিছু!

[![Version](https://img.shields.io/badge/Version-3.0.0-00d4ff?style=for-the-badge&color=00d4ff)](package.json)
[![License](https://img.shields.io/badge/License-ISC-aa66ff?style=for-the-badge&color=aa66ff)](package.json)
[![Language](https://img.shields.io/badge/Language-Bangla%20%26%20English-00ffaa?style=for-the-badge&color=00ffaa)](index.js)
[![Made by TANVIR](https://img.shields.io/badge/Made%20by-TANVIR-ff55f7?style=for-the-badge&color=ff55f7)](https://t.me/tanvirmunshi)

<img src="assets/banner.jpg" alt="TANVIR AI Chatbot Banner" width="100%"/>

</div>

---

## 🌟 পরিচিতি

**TANVIR AI Chatbot** হলো একটি শক্তিশালী WhatsApp AI চ্যাটবট যা আপনার যেকোনো প্রশ্নের জবাব দিতে পারে — পড়াশোনা, কোডিং, রান্না, ভ্রমণ, স্বাস্থ্য, বিনোদন, প্রযুক্তি... যা কিছু ভাবেন! সাথে আছে **ছবি তৈরি**-এর সুবিধা (Image Generation)।

এটি একটি টার্মিনাল ড্যাশবোর্ডের মাধ্যমে নিয়ন্ত্রণ করা যায়, যেখানে আপনি WhatsApp পেয়ারিং কোড দিয়ে বটটিকে চালু করতে পারবেন।

> 💫 **নির্মাতা:** TANVIR
> 📩 **Telegram:** [@tanvirmunshi](https://t.me/tanvirmunshi)

---

## 🚀 ফিচারসমূহ (Features)

| ফিচার | বিবরণ |
|---|---|
| 🧠 **AI প্রশ্ন-উত্তর** | বাংলা ও ইংরেজি — যেকোনো ভাষায় উত্তর দেয় |
| 📸 **ইমেজ জেনারেশন** | `/image` কমান্ড বা সাধারণ বাক্যেই ছবি বানায় |
| 🗣️ **Typing Indicator** | টাইপ করছে দেখিয়ে উত্তর দেওয়ার প্রস্তুতি জানায় |
| 🧠 **Short Memory** | প্রতি chat-এর সাম্প্রতিক কথোপকথনের context ধরে রাখে |
| 💻 **টার্মিনাল ড্যাশবোর্ড** | সুন্দর নিওন-থিম ওয়েব প্যানেল |
| 🔗 **WhatsApp লিংকিং** | ফোন নম্বর দিয়ে সহজ পেয়ারিং কোড |
| 🔁 **অটো-রিকানেক্ট** | সংযোগ ছাড়লে আবার যুক্ত হয় |
| ⚡ **সেলফ-পিং** | Render ফ্রি টিয়ারে ঘুমানোর হাত থেকে বাঁচায় |

---

## ⌨️ কমান্ড লিস্ট

```
/start     → 🤗 Welcome মেসেজ (বট চালু)
/help      → 📚 সব কমান্ডের তালিকা
/menu      → 📚 কমান্ড মেনু
/commands  → 📚 কমান্ড লিস্ট
/about     → 👤 বট ও নির্মাতার পরিচয়
/credits   → 🤍 নির্মাতা ক্রেডিট
/info      → 👤 বটের তথ্য
/owner     → 👑 বট মালিক
/ping      → ⏱️ বট status ও uptime
/status    → ⏱️ লাইভ status
/alive     → 🟢 বটের অবস্থা
/image <বর্ণনা> → 🎨 ছবি তৈরি (যেমন: /image একটা সূর্যাস্ত)
```

**প্রাকৃতিক ভাষায় ছবি:**
```
একটা গাড়ির ছবি বানাও
draw a cat
```

**আর যেকোনো কিছু লিখে দাও — AI সব জানবে!**

---

## 🛠️ ইনস্টলেশন (Installation)

### ধাপ ১: প্রজেক্ট ক্লোন ও নির্ভরতা ইনস্টল
```bash
git clone https://github.com/tanviraxon/tanvir-ahmed-chatbot.git
cd tanvir-ahmed-chatbot
npm install --omit=dev
```

> **নোট:** Render-এ ডিপ্লয় করতে `npm install --omit=dev` ব্যবহার করুন।

### ধাপ ২: এনভায়রনমেন্ট সেটআপ
`.env` ফাইলে আপনার প্রি-ফারেন্স অনুযায়ী পরিবর্তন করুন:
```env
PORT=3000
RENDER_EXTERNAL_URL=https://tanvir-chatbot.onrender.com
```

### ধাপ ৩: বট চালু করুন
```bash
npm start
```

---

## 🔗 WhatsApp লিংকিং (কীভাবে ব্যবহার করবেন)

1. ব্রাউজারে ড্যাশবোর্ড খুলুন → `http://localhost:3000`
2. আপনার **নম্বর** দিন (কান্ট্রি কোড সহ, `+` ছাড়া — যেমন: `+8801712345678`)
3. **LOGIN START** বাটনে ক্লিক করুন
4. **যেই কোড** দেখাবে এটি নোট করে রাখুন
5. WhatsApp → **Settings → Linked Devices → Link a Device → Link with phone number** → কোডটি দিন
6. 🎉 বট অনলাইন! এখন যেকোনো মেসেজে উত্তর দেবে

---

## 🐳 Docker দিয়ে চালানো (ঐচ্ছিক)

```bash
docker build -t tanvir-chatbot .
docker run -p 3000:3000 tanvir-chatbot
```

---

## ☁️ Render ডিপ্লয়মেন্ট

1. **render.yaml** প্রজেক্টের রুটে আছে — [Render.com](https://render.com) থেকে *New → Blueprint*
2. Service নাম: `tanvir-chatbot`
3. Region: `Singapore` (BD ব্যবহারকারীদের জন্য সবচেয়ে কাছের)
4. Persistent Disk মাউন্ট: `/opt/render/project/src/auth_info`
5. ডিপ্লয়ের পর আপনার URL দিন `RENDER_EXTERNAL_URL` আপডেট করুন

---

## 📁 প্রজেক্ট স্ট্রাকচার

```
tanvir-chatbot/
├── index.js          # মূল বট কোড (Express + Baileys)
├── package.json      # নির্ভরশীলতা
├── .env.example      # এনভায়রনমেন্ট টেমপ্লেট
├── render.yaml       # Render Blueprint
├── Dockerfile        # ডককার উদাহরণ
├── Procfile          # Heroku-সামঞ্জ্যপূর্ণ
└── assets/           # লোগো ও ব্যনার
     ├── logo.jpg
     └── banner.jpg
```

---

## 🔧 টেকনোলজি

| টেকনোলজি | কাজ |
|---|---|
| Node.js / Express | সার্ভার ও API |
| @whiskeysockets/baileys | WhatsApp কানেকশন |
| Pollinations API | ইমেজ জেনারেশন |
| nxtai API | AI রিপ্লাই |
| pino | লগিং |

---

## ❗ সমস্যা সমাধান (FAQ)

**Q: পেয়ারিং কোড আসছে না?**
A: নম্বরটি সঠিক ফর্মেটে দিন (কান্ট্রি কোড সহ, + ছাড়া)। ইন্টারনেট চেক করুন ৩০ সেকেন্ড পরে আবার চেষ্টা করুন।

**Q: ছবি তৈরি হচ্ছে না?**
A: Pollinations সার্ভার কখনো ব্যস্ত থাকে। ৩০-৬০ সেকেন্ড পরে আবার চেষ্টা করুন।

**Q: বট হারিয়ে গেছে (অফলাইন)?**
A: ড্যাশবোর্ডে **RESET SESSION** বাটনে ক্লিক করুন এবং আবার পেয়ার করুন।

---

<div align="center">

## 🛡️ লাইসেন্স

এই প্রজেক্টটি **ISC License** এর আওতায় প্রকাশিত।

---

### 🕊️ শুভেচ্ছা

**Made with ❤️ by TANVIR**

💬 [Telegram](https://t.me/tanvirmunshi) · ⚙️ Powered by AI

---

`<TANVIR AI Chatbot — v3.0.0>`
</div>
