# Quote-collector-app
Smart quote collector app with AI-generated and personalized quote recommendations, built using Flutter.
# ✨ Reverie — AI-Powered Quotes & Book App

Reverie is a beautiful Flutter app that uses AI to generate powerful quotes based on your situation, discover books, and save your favourite wisdom — all in one elegant dark-themed experience.

---

## 📱 Features

- **Situation Quotes** — Type what you're going through and get 7 powerful AI-generated quotes instantly
- **Book Overview** — Get detailed summaries, key lessons, and ratings for any book
- **Book Recommendations** — Get personalized book recommendations based on your interests
- **Save Quotes** — Save your favourite quotes to your personal collection
- **Favorites** — Browse and manage your saved quotes
- **Share Quotes** — Share quotes to WhatsApp, Instagram, Twitter, Facebook or copy to clipboard
- **Local Storage** — Chat history, book history, and preferences saved locally on device
- **Beautiful Dark UI** — Elegant dark theme with gold accents and Cormorant Garamond typography

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Flutter | Cross-platform mobile framework |
| Dart | Programming language |
| Google Gemini API | AI quote & book generation |
| SharedPreferences | Local data storage |
| Provider | State management |
| Google Fonts | Typography (Cormorant Garamond, Jost) |

---

## 📁 Project Structure

```
lib/
├── data/
│   ├── app_theme.dart              # App colors, typography, theme
│   └── share_service.dart          # Share functionality
├── models/
│   └── quote.dart                  # Quote data model
├── providers/
│   └── quotes_provider.dart        # State management for quotes
├── screens/
│   ├── splash_screen.dart          # Splash/loading screen
│   ├── home_screen.dart            # Main home screen
│   ├── ai_screen.dart              # AI features hub
│   ├── ai_situation_quotes_screen.dart  # Situation-based quotes
│   ├── ai_book_overview_screen.dart     # Book overview & summary
│   ├── ai_book_recommendations_screen.dart # Book recommendations
│   ├── favorites_screen.dart       # Saved favourite quotes
│   ├── quote_detail_screen.dart    # Individual quote detail
│   └── add_edit_quote_screen.dart  # Add/edit custom quotes
├── services/
│   ├── ai_service.dart             # Google Gemini API integration
│   └── storage_service.dart        # Local storage (SharedPreferences)
├── widget/
│   ├── quote_card.dart             # Reusable quote card widget
│   └── category_chip.dart          # Category chip widget
├── firebase_options.dart           # Firebase configuration
└── main.dart                       # App entry point
```

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.x or higher)
- Dart SDK
- Android Studio / VS Code
- Google Gemini API key (free at [aistudio.google.com](https://aistudio.google.com))

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/reverie.git
cd reverie
```

2. **Install dependencies**
```bash
flutter pub get
```

3. **Add your Gemini API key**

Open `lib/services/ai_service.dart` and replace:
```dart
static const String _apiKey = 'YOUR_GEMINI_API_KEY';
```

4. **Run the app**
```bash
flutter run
```

---

## 🔑 Getting a Free API Key

1. Go to [aistudio.google.com](https://aistudio.google.com)
2. Sign in with your Google account
3. Click **"Get API Key"** → **"Create API key"**
4. Copy and paste it into `ai_service.dart`

---

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^6.x.x
  shared_preferences: ^2.x.x
  google_fonts: ^6.x.x
  http: ^1.x.x
  share_plus: ^7.x.x
  firebase_core: ^3.x.x
  firebase_auth: ^5.x.x
  cloud_firestore: ^5.x.x
  google_sign_in: ^6.x.x
```

---

## 📸 Screens

| Screen | Description |
|---|---|
| Splash | Beautiful animated loading screen |
| Home | Browse and manage your quote collection |
| AI Hub | Access all AI-powered features |
| Situation Quotes | Get quotes based on your current situation |
| Book Overview | Detailed book summaries and key lessons |
| Book Recommendations | Personalized reading suggestions |
| Favorites | Your saved quotes collection |
| Quote Detail | Full quote view with share options |

---

## 🎨 Design

- **Theme:** Dark with gold accents
- **Primary Font:** Cormorant Garamond (quotes)
- **Secondary Font:** Jost (UI elements)
- **Color Palette:**
    - Background: `#0D0D0D`
    - Gold: `#C9A84C`
    - Surface: `#1A1A1A`
    - Text Primary: `#F5F0E8`

---


---

## 👩‍💻 Developer

**Humaira and wafa**
- Built with Flutter & Google Gemini AI
- Project: Reverie — *because every quote tells a story*

---
<img width="124" height="275" alt="image" src="https://github.com/user-attachments/assets/cc0371a5-ade8-4276-8477-3bf2a4a916bf" />


## 📄 License

This project is for educational purposes.
