# Story Generator

Story Generator is a Flutter application that uses **Google Gemini AI** to generate bedtime stories based on objects detected in an uploaded image. The app processes images, identifies objects, and creates engaging stories in different genres and languages.

## Features
- 📸 **Image Upload:** Users can upload an image to identify objects.
- 🤖 **AI-Powered Storytelling:** Uses Google Gemini AI to generate unique stories based on detected objects.
- 📝 **Genre Selection:** Choose from multiple genres for a customized storytelling experience.
- 🌍 **Multi-Language Support:** Generates stories in different languages and cultural settings.
- 🎨 **User-Friendly UI:** A clean and interactive design for seamless navigation.

## Installation
### Prerequisites
- Flutter SDK (Latest Stable Version)
- Android Studio or Visual Studio Code
- A Google Gemini AI API Key



## Project Structure
```
📂 story-generator/
├── 📂 android/        # Android-specific files
├── 📂 ios/            # iOS-specific files
├── 📂 lib/            # Main Flutter app
│   ├── 📂 models/     # Data models
│   ├── 📂 services/   # AI & API service logic
│   ├── 📂 ui/         # UI components
│   ├── main.dart      # App entry point
├── pubspec.yaml       # Dependencies & configurations
```

## API Integration
The app interacts with **Google Gemini AI** to generate content:
- `lib/services/ai_service.dart` contains AI request logic.
- Uses **Google Generative AI SDK** to process image and text prompts.


## Contributing
Feel free to fork, modify, and submit pull requests! Contributions are welcome. 😊

## License
This project is open-source and available under the **MIT License**.

---
🚀 **Developed by IMxGIRISH**
