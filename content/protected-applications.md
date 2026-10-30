---
title: "CMS protected applications: information and privacy"
---

The Centre for Music and Science (CMS) at the University of Cambridge uses Cloudflare Access to protect selected internal applications. These services are available only to people authorised for the relevant application.

## Signing in

You can sign in using a one-time code sent to your authorised email address. Where Google sign-in is offered, you can instead use a Google account associated with an authorised email address. A Google account alone does not grant access: Cloudflare checks your identity against the application's access rules. If your Google account email does not match an authorised address, use the one-time code or contact us for help.

## Information used for Google sign-in

When you choose Google sign-in, Google authenticates you and provides Cloudflare Access with your Google account's basic identity information, including your name and email address. Cloudflare uses the email address to check whether you are allowed to access the requested application. This sign-in integration requests the OpenID Connect, email and basic profile scopes; it does not request access to your Google Drive, Gmail messages or calendar.

Cloudflare Access also records authentication events to help CMS protect its services, investigate problems and administer access. These records can include your email address, IP address, the application, the time of the attempt, the identity provider and whether access was allowed. A protected application may process further information for its own purpose; its own privacy information applies to that use.

## Who receives the information

Google provides the sign-in service, and Cloudflare processes the identity and access information to protect CMS applications. Authorised CMS service administrators can use access and authentication records to manage security and troubleshoot the service. Google and Cloudflare also handle information under their own privacy notices:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/)

## Retention and your choices

Cloudflare's standard Access log retention for its Free plan is 24 hours. Other records, such as the list of people authorised to use an application, may be kept for as long as needed to administer access. You can contact CMS to ask about your access or to request its removal. Removing access to an application does not by itself remove an authorisation from your Google account; you can manage third-party connections in your [Google Account](https://myaccount.google.com/connections).

## Contact and data protection

For questions about the service or its access rules, contact [cms@mus.cam.ac.uk](mailto:cms@mus.cam.ac.uk).

The University of Cambridge's [general privacy information](https://www.information-compliance.admin.cam.ac.uk/data-protection/general-data) explains how the University handles personal information and your rights. For data protection enquiries or to exercise your rights, contact [data.protection@admin.cam.ac.uk](mailto:data.protection@admin.cam.ac.uk).
