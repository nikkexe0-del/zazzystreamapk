# ZazzyStream Android APK

Native Android WebView wrapper for https://zestyyflix.vercel.app

## Setup

1. Add these 4 secrets to GitHub → Settings → Secrets → Actions:
   - `KEYSTORE_BASE64` — from KEYSTORE.txt
   - `KEYSTORE_PASSWORD` — zazzystream123
   - `KEY_ALIAS` — zazzystream
   - `KEY_PASSWORD` — zazzystream123

2. Push to `main` → Actions builds the APK automatically (~5 min)

3. Download from the Releases tab or Actions artifacts
