# 🌍 Flutter Easy Localization Example

This project demonstrates how to implement **multi-language support** in a Flutter app using the [`easy_localization`](https://pub.dev/packages/easy_localization) package.  
It allows switching between **English** and **Arabic** dynamically at runtime.

---

## 🚀 Features

- 🌐 Multi-language support (English 🇺🇸 & Arabic 🇪🇬).
- 🔄 Switch languages with a single button click.
- 🎨 Simple and clean UI.
- 🛠️ Uses `easy_localization` for managing translations.

---

## 📂 Project Structure

lib/
│ main.dart
│
└── lang/
  ├── en-US.json
  └── ar-EG.json

---

## 📝 Translation Files

### 🇺🇸 en-US.json

{
  "hello_message": "Hello in the app",
  "appbar_text": "Localization in Flutter",
  "change_lang": "Change Language"
}
🇪🇬 ar-EG.json

{
  "hello_message": "مرحباً بك في التطبيق",
  "appbar_text": "تعدد اللغات في فلاتر",
  "change_lang": "تغيير اللغة"
}
🛠️ Getting Started
1️⃣ Clone the repo

git clone <https://github.com/EngmoustafaAhmad/flutter_easy_localization_example.git>
cd flutter_easy_localization_example
2️⃣ Install dependencies

flutter pub get
3️⃣ Run the app

flutter run
📷 Screenshots
English Arabic

## 🎥 Video Review

[![Watch the demo on YouTube](https://img.youtube.com/vi/4SP6VCXXBAs/0.jpg)](https://www.youtube.com/watch?v=4SP6VCXXBAs)


📦 Dependencies

dependencies:
  flutter:
    sdk: flutter
  easy_localization: ^3.0.7
  shared_preferences: ^2.3.3
