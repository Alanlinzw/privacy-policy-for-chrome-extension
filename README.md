# privacy-policy-for-chrome-extension
Privacy Policy for 高效待办清单 Chrome Extension
# Privacy Policy for 高效待办清单 (To-Do List) Extension

**Last Updated:** 2023-10-27

Thank you for using 高效待办清单 (To-Do List), a Chrome extension developed by Alan Smith. Your privacy is important to us. This Privacy Policy explains what information we collect and why we need it.

## 1. Information We Collect and Use

Our extension is designed to be a private, personal productivity tool. We handle the following types of data:

**a) User-Generated Content:**
This is the core data of the extension, created and managed entirely by you. It includes:
*   Your to-do items (daily, monthly, future plans)
*   Notes and progress text associated with your tasks
*   Subtasks for your monthly to-dos
*   Hyperlinks you add to your tasks
*   Ledger entries (date, item, amount, payment method, details)

**How we use it:** This data is used solely to provide the core functionality of the extension. It is displayed back to you within the extension's interface (popup and dashboard).

**b) Financial Information:**
The "Ledger" feature allows you to voluntarily record your financial transactions. This information is treated as sensitive and is part of your User-Generated Content.

**c) Personally Identifiable Information (PII):**
Currently, the extension does not collect any PII. However, for a planned future feature (Google Sheets synchronization), we will require access to your email address through Google's OAuth 2.0 process. This information will be used exclusively to identify and manage your spreadsheet in your Google Drive and will not be used for any other purpose.

## 2. Data Storage

All the data you create is stored locally and securely on your device using **Chrome's Storage API (`chrome.storage.sync`)**.

The key benefit of `chrome.storage.sync` is that your data is automatically synchronized across all Chrome browsers where you are logged into the same Google account. This data is associated with your Google account's private cloud storage, and **we, the developers, have no access to it.**

## 3. Permissions Justification

Our extension requests the following permissions to function correctly:

*   **`storage`**: Essential for saving your to-do lists and ledger data so it persists between browser sessions and syncs across your devices.
*   **`alarms`**: Used to run a daily background task that resets daily tasks and moves due future plans to the daily list.

## 4. Third-Party Services

The extension uses one third-party library, **SortableJS**, to enable drag-and-drop functionality. This library is bundled locally within the extension and **does not make any external network requests or transmit any data**.

## 5. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page. You are advised to review this Privacy Policy periodically for any changes.

## 6. Contact Us

If you have any questions about this Privacy Policy, you can contact us at:

*   **Email:** martinlinzhiwu@gmail.com
