---
title: "CMS meeting backup privacy notice"
---

This notice describes how the Centre for Music and Science (CMS) at the University of Cambridge uses Google Drive for [CMS meeting backup](/meeting-backup/).

## What the app stores and why

The service makes encrypted snapshots of the meeting transcription database for recovery after a failure. Snapshots can contain meeting titles, transcripts, summaries, dates, account email addresses and sharing records. The service encrypts the database on the server before it uploads a snapshot. The decryption key is held separately by the service operator. Audio recordings are outside the backup.

## How the app uses Google Drive

During setup, CMS checks the Google account email address to confirm the intended University Drive account. The app uses the Google Drive `drive.file` permission. The uploader uses this permission to create encrypted snapshots in the designated University Drive folder, list and verify the backups, and remove expired snapshots. Authorised service administrators can retrieve and decrypt backups to recover the database. Google provides the storage service under its [privacy policy](https://policies.google.com/privacy), and the University publishes a [privacy notice for Google Workspace at Cambridge](https://help.uis.cam.ac.uk/policies/serviceprivacypolices/googleappsprivacy).

## Retention and your choices

The uploader removes snapshots older than 28 days from the active backup folder after an upload and integrity check succeed. Upload problems can delay that cleanup. A meeting deleted from the transcription service can still be present in an earlier backup. Snapshots moved to [Google Drive Trash](https://support.google.com/drive/answer/2375102) can remain there for a further 30 days. The operator can withdraw Drive permission through the [Google Account connections page](https://myaccount.google.com/connections).

## Contact and data protection

For questions about the backup service, contact [cms@mus.cam.ac.uk](mailto:cms@mus.cam.ac.uk). The University's [general privacy information](https://www.information-compliance.admin.cam.ac.uk/data-protection/general-data) explains how it handles personal information and your rights. For data protection questions or to exercise your rights, contact [data.protection@admin.cam.ac.uk](mailto:data.protection@admin.cam.ac.uk).
