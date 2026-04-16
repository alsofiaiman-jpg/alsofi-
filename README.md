name: shifa_app
description: تطبيق شفاء - الرقية الشرعية الشاملة
publish_to: 'none'
version: 1.0.0+1

environment:
  sdk: '>=3.0.0 <4.0.0'

dependencies:
  flutter:
    sdk: flutter
  just_audio: ^0.9.37
  provider: ^6.1.2
  shared_preferences: ^2.2.2
  google_fonts: ^6.2.1
  cupertino_icons: ^1.0.6

flutter:
  uses-material-design: true
  assets:
    - assets/audio/
    - assets/data/ruqyah.json
  fonts:
    - family: Cairo
      fonts:
        - asset: assets/fonts/Cairo-Regular.ttf
        - asset: assets/fonts/Cairo-Bold.ttf
          weight: 700
