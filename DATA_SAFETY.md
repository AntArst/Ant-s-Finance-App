# Data Safety Information for Google Play Console

This document provides the information needed to fill out the Data Safety section in Google Play Console for Ant's Finance Tracker.

## App Overview
- **App Name:** Ant's Finance Tracker
- **Package Name:** com.arstant.antfinapp
- **Privacy Policy URL:** [Your Privacy Policy URL - e.g., GitHub Pages, website, etc.]

## Data Collection and Sharing

### Does your app collect or share any of the required user data types?

**Answer: NO**

The app does not collect or share any user data with external services. All data processing occurs locally on the user's device.

### Data Types Collected

**None** - The app does not collect any data types listed in Google Play's data safety form.

### Data Types Shared

**None** - The app does not share any data with third parties.

## Google Play Console Data Safety Form Answers

When filling out the Data Safety form in Google Play Console:

1. **Does your app collect or share any of the required user data types?**
   - Select: **No**

2. **Data types collected:**
   - Leave all unchecked (no data collected)

3. **Data types shared:**
   - Leave all unchecked (no data shared)

4. **Security practices:**
   - Data is encrypted in transit: **Not applicable** (app is offline)
   - Data is encrypted at rest: **Yes** (via device OS security)
   - Users can request data deletion: **Yes** (via app uninstall)

5. **Privacy Policy:**
   - Provide the URL to your Privacy Policy

## Detailed Breakdown

### Personal Information
- **Collected:** No
- **Shared:** No
- **Reason:** App operates completely offline; no personal information is collected or transmitted.

### Financial Information
- **Collected:** No (stored locally only, not collected)
- **Shared:** No
- **Reason:** Financial data is stored locally on the device. Users import their own data via CSV files. This data never leaves the device and is not transmitted to any external service.

### Files and Documents
- **Collected:** No
- **Shared:** No
- **Reason:** Users can import CSV files from their device storage. The app reads these files locally but does not transmit them anywhere. Users can also export CSV files, which are saved to their device storage.

### App Activity
- **Collected:** No
- **Shared:** No
- **Reason:** No analytics, tracking, or activity monitoring is performed.

### Device or Other IDs
- **Collected:** No
- **Shared:** No
- **Reason:** No device identifiers are collected or used.

## Data Security

### Encryption
- **In Transit:** Not applicable (app operates offline)
- **At Rest:** Data is stored in device's local storage, protected by the device's operating system security

### Data Deletion
- Users can delete all app data by uninstalling the app
- Users can clear imported data by removing CSV files
- All data is stored locally and can be deleted at any time

## Permissions Used

### Storage Permission
- **Purpose:** To read CSV files that users choose to import
- **Data Access:** Only files explicitly selected by the user
- **Data Sharing:** No data is shared

### File Access
- **Purpose:** To save exported CSV templates
- **Data Access:** Only files created by the app
- **Data Sharing:** No data is shared

## Third-Party Services

### External Links
- The app may open external websites (e.g., sankeymatic.com) when users click links
- This is user-initiated and does not involve data collection
- No data is transmitted to these external sites

## Compliance Checklist

- ✅ App does not collect personal information
- ✅ App does not collect financial information (stores locally only)
- ✅ App does not share data with third parties
- ✅ App does not use analytics or tracking
- ✅ App operates offline-first
- ✅ All data processing occurs locally
- ✅ Users have full control over their data
- ✅ Privacy Policy is available
- ✅ Data can be deleted by uninstalling the app

## Additional Notes for Play Console

- The app uses local storage (SharedPreferences) for app preferences only
- CSV files are accessed only when explicitly selected by the user
- No network requests are made except for optional external link opening
- No user accounts or authentication
- No cloud synchronization
- No analytics or crash reporting
- No advertising

---

**Important:** This document is for reference when filling out the Google Play Console Data Safety form. Make sure your actual Privacy Policy is publicly accessible and linked in your Play Console listing.

