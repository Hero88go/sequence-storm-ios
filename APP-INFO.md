# Sequence Storm iOS App — Info

## App Store Connect
- **App Name**: Sequence Storm
- **Bundle ID**: `com.geekmagnetinc.sequencestorm`
- **Apple ID**: TBD — fill after App Store Connect entry exists
- **SKU**: sequence-storm-ios
- **Primary Language**: English (U.S.)
- **Platform**: iOS

## Apple Developer
- **Team ID**: L52G64VBAZ
- **Account Holder (Owner)**: Kristin Boster (kristin@kristinboster.com)
- **Developer (Chandler)**: hero88go@gmail.com — under Kristin's account
- **Company**: Geek Magnet Inc

## Codemagic
- **Project**: sequence-storm-ios (TODO: create)
- **Repo**: github.com/Hero88go/sequence-storm-ios (TODO: create)
- **Provisioning Profile name**: `sequence-storm-profile`
- **Distribution Cert name**: `sequence-storm-distribution`

## Local Setup (one-time)
```
cd "c:/Users/Chandler/NEW project/sequence-storm-ios"
npm install
npx cap add ios
npx cap sync ios
```

## Asset Pipeline
- Replace `assets/icon.png` with a 1024x1024 PNG branded for Sequence Storm
- Then: `npx @capacitor/assets generate --ios`

## Web Source
- Source HTML: `c:/Users/Chandler/NEW project/sequence-storm.html`
- iOS-shipped copy: `www/index.html` (viewport patched for safe-area-inset)

## App Store Description (draft)
**Subtitle**: Simon Says reimagined
**Description**:
Watch the sequence. Repeat it. Daily puzzles, endless mode, speed blitz.
Pure reaction and memory — see how far you can go.

## Notes
- Pure local game — no backend, no Convex.
- 4-pad layout already mobile-friendly (`--pad-size: min(28vw, 140px)`).
- CRT scanline aesthetic.
