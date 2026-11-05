---
layout: default
title: Privacy policy
---
# PersonalOS Offsite Backups privacy policy

Effective November 5, 2026.

This app is operated by its account owner for private personal backups. It is not offered to other users.

## Google data access and use

The app requests the Google Drive `drive.file` permission. It uses that permission to create, read, verify, and manage backup files and folders that it creates, or that the owner explicitly selects for it. It does not request access to the owner's entire Drive, Gmail, contacts, or calendar.

Selected backup contents and names are encrypted on the owner's device before upload. Google Drive stores encrypted backup objects and ordinary service metadata, such as encrypted object names, sizes, and transfer times. Downloads are decrypted locally for authorized recovery and integrity checks. Google processes the stored data under its own terms and privacy policies.

## Credentials, storage, and sharing

OAuth credentials and encryption keys are stored in access-restricted files under the owner's control. Recovery material is kept separately in encrypted form. This documentation website does not receive or store credentials, keys, or backup contents. GitHub hosts this website and may process ordinary website access information under its own privacy statement.

The app does not sell data, use it for advertising, or share it with an independent app developer. Backup data is used only for the owner's backup and recovery purposes. It is not used to train general-purpose AI models. Use and transfer of Google user data adhere to the Google API Services User Data Policy, including its Limited Use requirements.

## Retention and controls

The owner controls retention of backup objects and local recovery material. The pilot uses copy-only transfers and does not automatically prune backups. The owner can stop the service, revoke the app's permission in Google Account connections, and remove app-created backups from Drive. Revocation does not itself delete stored backups or local recovery keys.

This is an owner-operated app with no third-party support desk. Its owner controls the support email shown on the Google OAuth consent screen and the source repository linked below. This policy will be updated if the app's data practices change.

[App information](./) · [Documentation source](https://github.com/thetimmyman/personalos-backup-disclosures)
