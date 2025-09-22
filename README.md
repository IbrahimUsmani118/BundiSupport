# Bundi Support

Welcome to the support page for **Bundi** Messaging App.

---

## 📬 Contact us
- **Ibrahim Usmani** — onlyibrahim13@gmail.com  
- **Joel Minaya** — jminaya20@gmail.com

---

## 📖 Frequently Asked Questions (FAQs)

### 1) What is Bundi?
Bundi is a messaging app that lets you chat with friends, share media, and stay connected in a simple, secure way.

### 2) How does image uploading and duplicate blocking work?
- You can upload an image up to two times without restriction.  
- On the third attempt with the same image, the upload is blocked to prevent duplicates and reduce spam.  
- To do this, Bundi computes a non-reversible fingerprint (perceptual hash) of the image and uses a counter to enforce the rule. The hash does not allow reconstruction of the original image.

### 3) What permissions does Bundi request on iOS and why?
- **Camera** — so you can take and upload photos (e.g., a profile picture or a photo to share in chat).  
- **Photo Library** — so you can choose images from your library to share or set as a profile picture.  
- **Notifications (optional)** — to alert you about new messages.  

You can manage these anytime in your device’s Settings.

### 4) How can I report a bug?
Email us with:
- **Device & OS:** (e.g., iPhone 13, iOS 18.0)  
- **App version/build:** (from **Bundi → Settings → About**)  
- **Steps to reproduce:** numbered steps from a fresh launch  
- **Expected vs. actual result**  
- **Screenshots/logs:** if available

### 5) How do I delete my account or data?
Go to **Settings → Account → Delete Account** (if available). If you don’t see this option, email us at the addresses above and we’ll assist.

---

## 🛠 Troubleshooting
- Restart the app/device.  
- Update **Bundi** to the latest version (TestFlight or App Store).  
- Check permissions: Camera/Photos/Notifications enabled.  
- Network: verify a stable internet connection (Wi-Fi or cellular).  
- Storage: ensure you have sufficient free space for media.  

Still stuck? Reach out at **onlyibrahim13@gmail.com** or **jminaya20@gmail.com**.

---

## 🧪 TestFlight: What to Test (Beta)

### Messaging & UI
1. Log in and open **Friends**.  
2. Select **Ibrahim** and tap **Chat** (bottom right).  
3. Send a text message; verify it appears in the thread.  
4. Tap the attachment icon → allow **Photo Library** access → select an image → tap the blue send arrow.  
**Expected:** Message/media send successfully; thread updates immediately.

### Duplicate-Image Blocking
1. Choose a single photo and send it **once**.  
2. Send the same photo a **second** time.  
3. Attempt to send the same photo a **third** time.  

**Expected:**
- First and second uploads succeed.  
- Third upload is blocked with a clear message (e.g., “This image has already been uploaded twice and can’t be sent again.”).

If the behavior differs, please include screenshots and a short description in your bug report.

---

## 🔐 Privacy & Data
For detailed information on data collection, use, and retention, see the **Privacy Policy** in-app or on our website. We do **not** sell or rent your data. Duplicate protection uses non-reversible image fingerprints to detect repeats.

---

Thank you for helping us improve **Bundi**!
