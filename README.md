# R4XCAP — GitHub Actions Android APK Builder

Is repository mein aapka latest **R4XCAP** (`app/src/main/assets/index.html`) + Android WebView Wrapper + GitHub Actions workflow ready hai.

## APK Kaise Banaye (3 Easy Steps)
1. GitHub par ek naya repository banao (jaise `R4XCAP-App`) aur is ZIP ke saare files upload/push kar do (make sure `.github/workflows/build-apk.yml` bhi upload ho).
2. GitHub repo mein **Actions** tab kholo → **Build R4XCAP Android APK** par click karo → **Run workflow** dabao (ya push karte hi auto start ho jayega).
3. ~2 minute mein build green ho jayega — niche **Artifacts → R4XCAP-Android-APK** download karo, unzip karo, aur `R4XCAP-Android.apk` apne Android phone mein install kar lo!

## Included Native Features
- **HTTPS Secure Context (`WebViewAssetLoader`)**: Saved API keys (`localStorage` + `IndexedDB`), Turbo MP4 Export (`WebCodecs`), aur Audio Mixer 100% persist aur kaam karte hain.
- **Native File Picker**: Video, Audio, `.SRT`, Alight Motion `.XML`, aur DaFont `.ZIP/.TTF/.OTF` files seedha phone storage se select hoti hain.
- **Native Downloads Bridge**: Exported `.mp4`, `.srt`, `.vtt`, aur `.xml` files directly `Downloads/R4XCAP/` folder mein save hoti hain.
