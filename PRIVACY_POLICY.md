# Privacy Policy for Alfamart Growtopia Bot

Last Updated: August 2026

Thank you for using the Alfamart Growtopia Discord Bot ("the Bot"). This Privacy Policy explains what data the Bot collects, how it is used, and how it is stored. By adding the Bot to your server or interacting with it, you agree to the collection and use of information in accordance with this policy.

## 1. Information We Collect

To function properly, the Bot collects and stores the following information:

*   **Discord User IDs:** Used to link your Discord account to your in-game profile, manage roles, and track your subscriptions/taxes.
*   **Discord Server (Guild) IDs:** Used to maintain server-specific configurations and embeds.
*   **User Roles & Nicknames:** The bot reads server roles to synchronize your Discord permissions with your in-game guild rank (Member, Elder, Co-Leader, Leader).
*   **In-Game Names (GrowIDs):** Provided by users/managers to track guild membership, clash contributions, and subscription durations.
*   **Message Content:** The bot reads message content strictly for specific features, such as filtering spam/images in designated channels and generating ticket transcripts for the support system.

## 2. How We Use Your Information

The data collected is used solely for the core functionality of the Bot:
*   **Guild Management:** Syncing your Discord roles automatically based on your in-game rank and paid subscription/tax status.
*   **Subscription Tracking:** Calculating expiration dates for guild members and sending tax reminders.
*   **Ticket System:** Creating, logging, and saving transcripts for support tickets.
*   **Server Utilities:** Updating live status embeds (like Potion expirations) and checking clash schedules.

## 3. Data Storage and Security

*   All collected data is stored securely using **Google Firebase** (Realtime Database/Firestore).
*   We do not sell, rent, or share your data with any third parties.
*   Data is only accessible by the Bot's developers for maintenance, debugging, and providing support.

## 4. Message Content & Server Members Intents

The Bot utilizes Discord's Privileged Intents to function:
*   **Server Members Intent:** Required to detect when members join/leave, automatically grant/remove roles based on their database profile, and update live member counts.
*   **Message Content Intent:** Required for the ticket system to read and log support conversations, and for the anti-spam system to detect and delete illicit images.

## 5. Data Deletion

You have the right to request the deletion of your data. If you wish to have your GrowID, Discord ID, or any associated data removed from our database, please open a ticket in the official support server or contact the bot developer directly.

## 6. Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be reflected in this document with an updated "Last Updated" date.

## 7. Contact Us

If you have any questions or concerns regarding this Privacy Policy, please contact the bot developer or reach out via the official Discord support server.
