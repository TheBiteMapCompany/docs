# Legal Documentation for Deployment

This directory contains the standard legal documents required for deploying apps under the `com.thebitemap` domain (The Bite Map Company).

## Files

*   **TERMS_OF_SERVICE.md**: General terms regarding account usage, user content, and liability.
*   **PRIVACY_POLICY.md**: Details on data collection (Location, Camera, Photos), third-party services, and user rights.
*   **EULA.md**: End User License Agreement, including Apple-specific terms and User-Generated Content (UGC) clauses.

## Usage Guide

### 1. Preparation
Before publishing, open each file and replace the following placeholders:
*   `[Date]`: The current date or effective date.
*   `[Support Email Address]`: The support email for the specific app (e.g., `support@thebitemap.com` or `bites-support@thebitemap.com`).

### 2. App Store Connect (iOS)
*   **Privacy Policy URL:** Host the `PRIVACY_POLICY.md` content on a public URL (e.g., GitHub Pages or your website) and provide the link in App Store Connect under App Privacy.
*   **EULA:** You can use Apple's standard EULA, but since this app has UGC (User Generated Content) features, it is recommended to provide a custom EULA that explicitly mentions moderation and reporting. Paste the text from `EULA.md` into the license agreement section or host it and provide a link.

### 3. Google Play Console (Android)
*   **Privacy Policy:** Provide a link to the hosted Privacy Policy in the App Content section.
*   **Terms of Service:** While not strictly required as a field in the console for all apps, it is best practice to link to it from within the app's "About" or "Settings" screen.

## Hosting
You can easily host these files using GitHub Pages for this repository or copy the content to your company website.
