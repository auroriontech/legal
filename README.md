# Aurorion Legal Documents

This repository contains all legal documents for Aurorion products and services.

## Document Structure

### iOS App Documents
- **`AURORION-EULA-IOS.md`** - End User License Agreement for iOS app
- **`AURORION-EULA-IOS.txt`** - Plain text version (auto-generated for App Store submission)
- **`AURORION-PRIVACY-IOS.md`** - Privacy Policy for iOS app
- **`AURORION-PRIVACY-IOS.txt`** - Plain text version (auto-generated for App Store submission)

### Web/SPA Documents
- **`AURORION-EULA-WEB.md`** - End User License Agreement for web application
- **`AURORION-PRIVACY-WEB.md`** - Privacy Policy for website

### Archive
- **`privacy-policy-26052025.pdf`** - Website privacy policy (PDF version)
- **`Privacy.md`** - Legacy privacy document

## Compliance

All documents are written in accordance with:
- **UK GDPR** (General Data Protection Regulation)
- **Data Protection Act 2018** (DPA 2018)
- **PECR 2003** (Privacy and Electronic Communications Regulations)

**Data Controller:**
Aurorion Tech Ltd
SC835759 (Scotland)
4 Shadepark Gardens, Dalkeith, Scotland, EH22 1BX

## Automated Plain Text Generation

### GitHub Action

A GitHub Action automatically converts markdown (`.md`) files to plain text (`.txt`) versions using [pandoc](https://pandoc.org/).

**Workflow file:** `.github/workflows/convert-md-to-txt.yml`

### How It Works

1. **Automatic Trigger:** When you push changes to any `.md` file (except README.md), the workflow runs
2. **Manual Trigger:** You can also run it manually from GitHub Actions tab
3. **Conversion:** Uses `pandoc` to convert markdown to plain text while preserving content
4. **Auto-commit:** Automatically commits and pushes the generated `.txt` files

### Manual Trigger

To manually trigger the conversion:

1. Go to the **Actions** tab in GitHub
2. Select **"Convert Markdown to Plain Text"** workflow
3. Click **"Run workflow"**
4. Choose the branch and click **"Run workflow"** button

### Why Plain Text Versions?

- **App Store Requirements:** Apple requires plain text versions of legal documents for iOS app submission
- **Consistency:** Auto-generation ensures `.md` and `.txt` versions are always in sync
- **Single Source of Truth:** Edit only the `.md` files; `.txt` files are generated automatically

## Editing Legal Documents

### For iOS Documents

1. Edit **`AURORION-EULA-IOS.md`** or **`AURORION-PRIVACY-IOS.md`**
2. Commit and push your changes
3. The GitHub Action will automatically generate the `.txt` versions
4. The `.txt` files will be committed and pushed automatically

### For Web Documents

1. Edit **`AURORION-EULA-WEB.md`** or **`AURORION-PRIVACY-WEB.md`**
2. Commit and push your changes
3. Deploy to website as needed

## Key Features

### iOS EULA Highlights
- On-device voice transcription (no voice recording/storage)
- Specific location data collection details (GPS, address components)
- Partner institution data sharing (transparent, opt-out-able)
- Internal review for compliance and safety
- UK GDPR compliant with full user rights

### iOS Privacy Policy Highlights
- Clear voice processing explanation
- Detailed location data handling
- Third-party service providers (Azure OpenAI, Cloudflare, Apple Services)
- International data transfers (UK GDPR Article 45)
- Data retention policies
- Complete user rights under UK GDPR

## Last Updated

All documents: **October 21, 2025**

## Contact

**Privacy Inquiries:** privacy@aurorion.app
**Support:** support@aurorion.app
**Website:** https://aurorion.app
