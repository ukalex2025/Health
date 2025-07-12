# 💪 Wellness Tracker PWA

A Progressive Web App for tracking your daily wellness data with offline support and screenshot integration.

## ✅ FIXED ISSUES
- **Data persistence**: All entries now save to localStorage automatically
- **Image handling**: Screenshots are properly stored and exported
- **Mobile optimization**: Better touch interface and responsive design
- **Offline support**: Works without internet connection

## 🚀 Features

### 📱 **Mobile-First Design**
- Optimized for both phone and laptop
- Touch-friendly interface
- Collapsible sections to save space
- Responsive layout

### 📸 **Enhanced Screenshot System**
- **Take photos directly** using device camera
- **Upload multiple images** for each category
- **Organized by category**: Sleep, Heart Rate, Exercise, Other
- **Automatic date association**
- **Preview and remove** images easily

### 💾 **Reliable Data Storage**
- **localStorage persistence** - data survives browser restarts
- **Automatic saving** after each action
- **Error handling** for storage issues
- **Visual feedback** with toast notifications

### 📊 **PDF Reports**
- **Complete data export** with all screenshots
- **Professional formatting** for printing
- **Automatic file naming** with dates
- **Image compression** for smaller file sizes

### 🔧 **PWA Features**
- **Install on home screen** (phone/desktop)
- **Offline functionality**
- **Fast loading** with caching
- **Native app feel**

## 🔧 Setup Instructions

### For Phone/Tablet:
1. Open `wellness-tracker.html` in your mobile browser
2. Look for "Add to Home Screen" popup or browser menu
3. Install the app
4. Access from your home screen like a native app

### For Laptop/Desktop:
1. Open `wellness-tracker.html` in Chrome, Edge, or Firefox
2. Look for install button in address bar
3. Install the PWA
4. Access from your desktop/start menu

## 📋 How to Use

### Daily Entry:
1. **Set date** for your entry
2. **Add screenshots** for each category using camera or file picker
3. **Fill in your data** (sleep, exercise, mood, etc.)
4. **Save entry** - data persists automatically

### Taking Screenshots:
- **📷 Take Photo**: Use device camera directly
- **📁 Choose File**: Select from gallery/files
- **Multiple uploads**: Select several images at once
- **Remove images**: Click × on any image

### Export & Reports:
- **📤 Export**: Download JSON file with all data
- **📄 PDF Report**: Generate printable report with images
- **📋 Copy Last**: Duplicate previous entry data

## 🛠️ Technical Details

### Files:
- `wellness-tracker.html`: Main PWA application
- `manifest.json`: PWA configuration
- `sw.js`: Service worker for offline functionality
- `Health Log.html`: Original version (now with fixed data persistence)

### Data Storage:
- All data stored locally in browser localStorage
- No cloud dependency
- Automatic backup on each save
- Export functionality for manual backups

### Browser Compatibility:
- Chrome/Edge: Full PWA support
- Firefox: PWA support (limited install options)
- Safari: Works but limited PWA features
- Mobile browsers: Excellent support

## 🔒 Security & Privacy
- **No cloud storage**: All data stays on your device
- **No tracking**: No external analytics or tracking
- **Secure**: HTTPS not required for localhost use
- **Private**: Screenshots and data never leave your device

## 📱 Mobile Tips
- **Save to home screen** for best experience
- **Use camera button** for quick screenshot capture
- **Swipe gestures** work naturally
- **Auto-save** prevents data loss

## 🎯 Comparison: Original vs PWA

| Feature | Original HTML | PWA Version |
|---------|---------------|-------------|
| Data persistence | ❌ Broken | ✅ Fixed |
| Mobile experience | ⚠️ Basic | ✅ Optimized |
| Offline support | ❌ None | ✅ Full |
| Camera access | ❌ File only | ✅ Direct camera |
| Installation | ❌ Bookmark only | ✅ Native app |
| Performance | ⚠️ Slow | ✅ Fast |

## 🆘 Troubleshooting

### Data not saving:
- Check browser localStorage quota
- Clear browser cache and reload
- Try incognito/private mode

### Images not uploading:
- Check file size (keep under 10MB per image)
- Ensure camera permissions are granted
- Try different image formats (JPG, PNG work best)

### PWA not installing:
- Use HTTPS or localhost
- Check browser PWA support
- Look for install banner or browser menu option

---

**Recommendation**: Use the PWA version (`wellness-tracker.html`) as it fixes all the data persistence issues and provides a much better mobile experience! 