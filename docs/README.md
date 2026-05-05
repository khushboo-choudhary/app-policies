# Privacy Policy & Terms of Service

This folder contains the legal documents for Brain Test app.

## 📄 Files

- **privacy-policy.md** - Markdown version
- **privacy-policy.html** - Ready-to-host HTML version
- **terms-of-service.md** - Markdown version
- **terms-of-service.html** - Ready-to-host HTML version

## 🌐 How to Host These Documents

### Option 1: GitHub Pages (FREE & EASY) ✅ Recommended

1. **Create a GitHub Repository**
   ```bash
   # In your project folder
   git init
   git add docs/
   git commit -m "Add privacy policy and terms"
   ```

2. **Push to GitHub**
   - Create a new repository on github.com
   - Push your docs folder

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from a branch
   - Branch: main, folder: /docs
   - Save

4. **Your URLs will be**:
   - Privacy: `https://yourusername.github.io/braintest/privacy-policy.html`
   - Terms: `https://yourusername.github.io/braintest/terms-of-service.html`

### Option 2: Firebase Hosting (FREE)

1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```

2. Initialize Firebase:
   ```bash
   firebase init hosting
   ```

3. Deploy:
   ```bash
   firebase deploy --only hosting
   ```

### Option 3: Netlify (FREE)

1. Create account at netlify.com
2. Drag and drop the `docs` folder
3. Get instant URLs

### Option 4: Your Own Website

Upload the HTML files to your website's public folder.

## ✏️ Customization Required

Before publishing, update these placeholders:

### In Both Documents:
- **Email**: Replace `support@braintest.com` with your real email
- **Developer Name**: Replace "Brain Test Games" with your actual developer/company name
- **Last Updated Date**: Update when making changes

### In Terms of Service:
- **Governing Law** (Section 14): Add your country/state
- **Arbitration Rules** (Section 15): Specify your jurisdiction

## 🔗 Update App Code

After hosting, update URLs in `lib/screens/settings_screen.dart`:

```dart
// Line ~306 - Privacy Policy URL
const url = 'https://yourusername.github.io/braintest/privacy-policy.html';

// Line ~323 - Terms of Service URL
const url = 'https://yourusername.github.io/braintest/terms-of-service.html';
```

## 📱 Google Play Console Setup

1. **Privacy Policy** (REQUIRED):
   - Go to Play Console > Your App > Store Presence > App Content
   - Under "Privacy Policy", add your hosted URL
   - This is MANDATORY before publishing

2. **Terms of Service** (Optional):
   - Can be added in app description or as a link
   - Not required by Google Play but recommended

## ⚖️ Legal Notice

These are TEMPLATE documents. You should:

1. ✅ Review all content carefully
2. ✅ Customize to match your actual practices
3. ✅ Add any additional clauses relevant to your app
4. ⚠️ **Consider consulting a lawyer** for legal compliance
5. ✅ Keep documents updated as your app changes

## 🔄 When to Update

Update these documents when you:
- Add new features that collect data
- Integrate new third-party services
- Change how you handle user information
- Receive legal advice to modify terms
- Update in-app purchase policies

Always update the "Last updated" date when making changes!

## 📧 Support Email Setup

If you don't have a custom domain email:
- Use Gmail: Create a dedicated account like `braintest.support@gmail.com`
- Use your personal email temporarily
- Consider professional email service (Google Workspace, etc.)

## ✅ Compliance Checklist

Before publishing to Google Play:

- [ ] Customize privacy policy with your information
- [ ] Customize terms of service with your information
- [ ] Host documents online (they must be publicly accessible)
- [ ] Test URLs to ensure they work
- [ ] Update URLs in app settings screen
- [ ] Add Privacy Policy URL to Play Console
- [ ] Set up support email and test it works
- [ ] Review GDPR compliance if targeting EU users
- [ ] Review COPPA compliance for kids apps
- [ ] Update documents when app changes

## 🌍 GDPR Compliance (EU Users)

If you have EU users, ensure:
- Users can request data deletion
- Clear consent for data collection
- Option to opt out of personalized ads (already included)
- Data retention policies clearly stated

## 🎯 Quick Start

**Fastest way to publish:**

1. Create GitHub repository
2. Enable GitHub Pages on `/docs` folder
3. Get your URLs: `https://yourusername.github.io/reponame/privacy-policy.html`
4. Update `settings_screen.dart` with your URLs
5. Replace email addresses in HTML files
6. Add Privacy Policy URL to Google Play Console
7. Done! ✅

Need help? Contact a legal professional for compliance advice.
