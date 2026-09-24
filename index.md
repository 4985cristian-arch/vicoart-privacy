# Vicoart Privacy Policy

**Effective date: 24 September 2026**

Vicoart respects your privacy and is committed to protecting personal information processed when you use the Vicoart mobile application.

This Privacy Policy explains what information Vicoart processes, why it is processed, how it is handled, the service providers involved, how long information may be retained, and the choices and rights available to users.

Vicoart is currently operated by **Cristian Dumitrache, United Kingdom**.

For privacy-related questions:

**privacy@vicoart.com**

For general support:

**support@vicoart.com**

## 1. About Vicoart

Vicoart is a wall visualisation application designed to help users preview decorative finishes on photographs of real walls.

The application allows users to create an account, create projects, select or photograph a room image, identify and refine a wall selection, preview decorative finishes, compare results, and save project variations locally on their device.

Vicoart uses user accounts for authentication and account-related functionality.

Saved Vicoart projects are currently primarily local to the user's device. Vicoart does not currently provide cloud synchronisation of saved projects.

## 2. Information Vicoart Processes

### Account information

When you create or use a Vicoart account, information associated with your account and authentication may be processed, including:

- your email address;
- a user or account identifier;
- authentication and session information;
- email-confirmation status;
- information required for password recovery;
- information required for account security and account deletion.

Vicoart uses Supabase to provide authentication and account-management infrastructure.

Passwords are handled through Supabase Auth. According to Supabase's current documentation, passwords are stored as cryptographic hashes rather than as plain-text passwords.

### Photos and room images

When you choose a photograph from your device or take a photograph for use in Vicoart, the image is used to provide Vicoart's wall-selection and decorative-finish visualisation functionality.

Before a photograph is uploaded for processing, Vicoart creates a sanitised processing copy designed to remove source metadata such as EXIF information, GPS location metadata, XMP data, comments and the original source filename.

The original photograph in your device gallery is not modified by this sanitisation process.

Vicoart does not intentionally collect precise location information from photographs.

### Wall-selection information

When you select or refine a wall, Vicoart may process information such as:

- selection points;
- image dimensions;
- wall-selection masks;
- wall boundaries;
- image-derived identifiers;
- information required to identify and process the selected wall.

### Generated previews and project information

Vicoart may create and process:

- wall masks;
- decorative-finish previews;
- project names;
- finish selections;
- saved project variations;
- locally managed project images;
- local project records.

Saved projects and their durable project media are primarily stored locally on the user's device.

## 3. How Information Is Used

Vicoart processes information as necessary to:

- create and manage user accounts;
- authenticate users;
- provide email confirmation;
- maintain and restore authentication sessions;
- provide password-recovery functionality;
- provide account-deletion functionality;
- identify and refine selected walls;
- provide AI-assisted wall segmentation;
- generate decorative-finish previews;
- display Before and After results;
- save and reopen projects and variations locally;
- maintain the security and reliability of the service;
- prevent misuse and control access to service infrastructure;
- respond to support and privacy requests.

Vicoart does not use room photographs for advertising.

Vicoart does not sell personal information.

## 4. Account Authentication

Vicoart uses **Supabase** to provide user authentication and account-management services.

Authentication processing may include your email address, user identifier, authentication and session information, email-confirmation status, and information required to provide password recovery and account security.

Passwords are handled by Supabase Auth. According to Supabase's current documentation, passwords are stored as cryptographic hashes rather than as plain-text passwords.

Vicoart uses authentication information to provide account creation, email confirmation, sign-in, session management, password recovery, sign-out and account deletion.

Supabase may process this information as a service provider supporting Vicoart's authentication infrastructure.

## 5. Transactional Account Emails

Vicoart uses **Resend** as part of its transactional email infrastructure for account-related communications, including account confirmation and password-recovery emails.

Information necessary to deliver these messages, such as the recipient email address and email-related technical information, may be processed by Resend.

According to Resend's current published GDPR information, email and log data is retained for 30 days on its Free, Pro and Scale plans, while different or configurable retention arrangements may apply to Enterprise services.

These retention practices are controlled by Resend and may change over time.

## 6. Local Project Storage

Vicoart stores project information primarily on the user's device.

This may include:

- project names;
- locally managed copies of project images;
- wall-selection masks;
- generated previews;
- finish selections;
- saved project variations;
- local project database records.

Saved projects remain on the device and are not synchronised through a Vicoart cloud project-storage service.

In versions supporting local account separation, new projects and explicitly imported project copies are associated with the signed-in account within the active local workspace. Normal project screens show that account's projects, not projects associated with another account on the same device. Signing out does not delete those projects. Signing in on another device does not restore them.

Older projects without an account association are not automatically assigned to the next person who signs in. Where the recovery feature is available, users must confirm permission to inspect them and separately confirm importing a copy. Importing preserves the unassigned original and its media. This permission confirmation does not independently verify historical ownership.

This separation is enforced by the application. It is not encryption of local project files or protection against unrestricted access to the device's storage.

Vicoart uses Android backup and device-transfer exclusions for specified Vicoart project data where supported. However, backup and transfer behaviour may also depend on the Android version, device manufacturer and backup or transfer mechanism.

## 7. Image Processing and Service Providers

Some Vicoart functionality requires off-device processing.

### Vicoart backend and Render

Images and related information required for wall selection and preview processing may be transmitted over encrypted HTTPS connections to the Vicoart backend.

The current Vicoart backend uses **Render** infrastructure.

The backend processes information required to provide wall selection, preview generation and related technical functionality.

### Replicate

Vicoart uses **Replicate** to provide AI-assisted wall segmentation.

For this purpose, a sanitised processing copy of a room image and information necessary to identify the selected wall may be transmitted to Replicate.

According to Replicate's current documentation, for predictions created through its API, input parameters, output values, output files and logs are automatically removed after one hour by default.

Vicoart does not rely on Replicate as permanent storage for users' Vicoart projects.

### Supabase

Vicoart uses **Supabase** for authentication and account-management infrastructure.

Supabase may process account identifiers, email addresses, authentication and session information, and other information required to provide these services.

### Resend

Vicoart uses **Resend** for transactional account email delivery.

Resend may process email addresses and technical information necessary to send and operate account-related emails.

## 8. Temporary Backend Processing

The Vicoart backend may temporarily hold processing information such as:

- wall selections;
- masks;
- preview images;
- intermediate processing information.

The backend is designed around temporary processing rather than permanent server-side project storage.

The current backend uses a nominal expiry period of approximately 15 minutes for certain temporary selections, masks and previews.

This period should not be interpreted as a guarantee that every technical copy is physically deleted at the exact expiry second. Infrastructure cleanup, active requests, crashes, provider processing and other technical processes may affect the exact timing of physical deletion.

Saved project copies stored locally on the user's device are separate from this temporary backend processing.

## 9. Data Sharing

Vicoart does not sell personal data and does not share user information with advertisers.

Information may be processed by service providers where necessary to operate Vicoart, including:

- **Supabase** — authentication and account management;
- **Resend** — transactional account email delivery;
- **Render** — Vicoart backend infrastructure;
- **Replicate** — AI-assisted wall segmentation.

These providers process information in connection with the technical services they provide.

Vicoart may change or replace infrastructure providers as the service develops. Material changes affecting how personal information is processed will be reflected in this Privacy Policy where required.

## 10. International Processing

Some service providers used by Vicoart may process information outside the United Kingdom.

Where applicable, Vicoart will seek to maintain appropriate arrangements for international processing in accordance with applicable data-protection requirements.

Users should be aware that information processed by infrastructure and technology providers may be processed in countries different from their country of residence.

## 11. Advertising, Analytics and Tracking

The current version of Vicoart does not include advertising.

Vicoart does not use room photographs to create advertising profiles.

The current Vicoart application does not use room photographs for behavioural advertising or cross-app advertising tracking.

If Vicoart introduces advertising, marketing analytics or materially different tracking technologies in the future, this Privacy Policy will be updated where required.

## 12. Payments, Trials and Subscriptions

The current version of Vicoart does not provide subscription billing, trial entitlements or per-user paid-generation quotas.

If paid functionality, subscriptions or other payment features are introduced in the future, relevant privacy information will be updated where necessary.

## 13. Deleting a Project

You can delete projects available to your signed-in account in My Projects. Deletion removes the selected project's local record and is designed to remove its Vicoart-managed images, wall masks, previews and saved variations. It does not delete another account's projects or original photographs stored independently in your gallery.

Deleting an imported legacy project copy does not delete the preserved unassigned original. If media removal is interrupted or fails, files may remain in deletion quarantine while recovery retries cleanup. Disappearance from My Projects does not guarantee immediate physical removal of every associated file.

Temporary information that has already been transmitted for backend or provider processing remains subject to the applicable temporary-processing and retention practices described in this Privacy Policy.

## 14. Deleting Your Vicoart Account

Vicoart provides an in-app **Delete Account** function.

Delete Account requests deletion of the authenticated Vicoart account. Once remote deletion is confirmed, automatic local cleanup targets only the account and local workspace recorded for that deletion on this device. It is designed to remove that partition's projects and associated durable media and clear the local authentication session. It preserves other accounts' local projects, unassigned legacy originals, previously retained legacy workspaces and original gallery photographs.

If deletion is interrupted, Vicoart retains recovery information and restricts access until the applicable recovery steps complete. Where the remote result is uncertain and the local target is known, the user may explicitly choose local cleanup; completing that cleanup does not establish that the remote account was deleted.

An older interrupted deletion may not identify an account safely. Where the app offers the confirmed option to keep unidentified data quarantined and sign out, it retains the old local workspace and unresolved deletion record rather than guessing ownership or erasing all device data. Subsequent sign-ins cannot access that retained workspace through normal project screens. This action does not itself delete the remote account. The current app provides no restore, export or device-wide erase action for that retained workspace.
Information already processed by infrastructure providers may remain subject to applicable technical, security, backup, legal or retention processes.

Users who cannot access the Vicoart application can find account-deletion instructions and request assistance here:

**[Delete Your Vicoart Account](https://privacy.vicoart.com/delete-account/)**

## 15. Data Retention

Vicoart aims to retain personal information only for as long as necessary for the purposes described in this Privacy Policy, subject to applicable legal, security and technical requirements.

Account information is processed through Supabase for as long as necessary to provide and secure the user's Vicoart account, unless the account is deleted or retention is otherwise required.

Local projects normally remain on the device across sign-out and restart until removed through an applicable deletion action. Unassigned legacy originals remain after import, and previously quarantined legacy workspaces remain after subsequent account deletion in a new workspace. The app does not currently implement an automatic expiry or a user-facing erase action for those retained legacy workspaces.

Failed project-media cleanup and interrupted import copies may remain pending recovery. Recovery distinguishes unpublished import copies from preserved originals and successfully saved projects. Historical shared temporary files without reliable account attribution are not automatically erased during account deletion; age-based startup cleanup may apply, but is restricted in protected recovery states. Vicoart does not guarantee immediate account-attributed removal of every historical temporary file.

Backend wall-selection, mask and preview processing information is intended to be temporary rather than permanent project storage.

According to Replicate's current published documentation, input parameters, output values, output files and logs associated with API predictions are automatically removed after one hour by default.

According to Resend's current published GDPR information, email and log data is retained for 30 days on its Free, Pro and Scale plans, with different or configurable arrangements potentially applying to Enterprise services.

Third-party service providers may maintain additional security, backup or legally required records in accordance with their applicable terms, policies and legal obligations.

## 16. Data Security

Vicoart uses technical measures intended to reduce privacy and security risks.

These include:

- encrypted HTTPS communication with the Vicoart backend;
- sanitisation of photographs before upload;
- removal of source metadata from uploaded processing copies;
- controlled local application storage;
- authentication and session controls;
- authenticated account deletion;
- restricted backend operations;
- rate and provider-use protections;
- separation of development and staging configuration;
- Android backup and device-transfer exclusions for specified project data.

No internet-connected service can guarantee absolute security.

Vicoart therefore aims to minimise the information transmitted and retained and to limit processing to information required to provide and protect the service.

## 17. Children's Privacy

The current Vicoart beta service is intended for users aged **18 and over**.

Vicoart does not knowingly seek to collect personal information from children through the current beta service.

If Vicoart becomes aware that personal information has been submitted contrary to this restriction, appropriate steps will be considered in accordance with applicable law.

## 18. Your Privacy Rights

Depending on applicable data-protection law, users may have rights concerning their personal data, including rights relating to:

- access;
- correction;
- deletion;
- restriction of processing;
- objection to certain processing;
- data portability where applicable;
- withdrawal of consent where processing relies on consent;
- making a complaint to an appropriate data-protection authority.

Privacy questions or requests can be sent to:

**privacy@vicoart.com**

Because Vicoart stores projects primarily on the user's device and uses temporary backend processing, Vicoart may not always be able to associate every temporary processing object with a particular individual after processing has ended.

## 19. Changes to This Privacy Policy

Vicoart may update this Privacy Policy when:

- application functionality changes;
- authentication or account functionality changes;
- service providers or infrastructure change;
- payments, subscriptions or cloud functionality are introduced;
- data-processing practices change;
- legal or regulatory requirements change.

The effective date at the top of this Privacy Policy will be updated when material changes are made.

## 20. Contact

**Vicoart**

**Operator:** Cristian Dumitrache, United Kingdom  
**Privacy:** privacy@vicoart.com  
**Support:** support@vicoart.com  
**Website:** vicoart.com
