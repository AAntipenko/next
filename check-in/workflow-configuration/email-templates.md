# Email Templates

## Overview

Here, you'll find various email templates for different purposes. All email templates are designed to be adaptable to different languages.

Special keywords can be utilized to construct your email templates.

Email Templates:

(1)

**Personal Invitations:** These templates are meant for sending personalized information, including personal data and an individual QR code, PIN, barcode, external ID, or registration link. They must handle confidential personal information.

(2)

**Outlook Invitations**: These messages are general and are sent to all invitees in the Outlook calendar for a meeting. They should not include any personal data.

(3)

**Visit Cancellation Notifications:** These messages are personalized and are sent to all visitors of a scheduled visit in the event of its cancellation. They may contain personal data.

(4)

**Group Invitations:** These messages are group invitations, providing a list of QR codes or PINs for all visitors of the visit. They are sent to the visitor(s) of the visit (referred to as group leaders) and must include personal access data such as a PIN or QR code for all visitors.

(5)

\*\*Online Registration Confirmations: \*\*This type of message is sent to the visitor after a successful online registration. It might contain personal data.

### **Personal Invitation**

Personal invitations can be sent:

1. Automatically (by the System based on the Invitations Settings)
2. Manually (by the user).

![](../../.gitbook/assets/CB4t3IilvJcOtRmPiwP5k\_image.png)

![](<../../.gitbook/assets/nO6gP8 Z5TUTLYnoH9aAe\_image.png>)

### Outlook Invitation

Configure your outlook invitation. Outlook invitation will be sent automatically as soon as the event is created. Read more in Outlook Plugin.

![](<../../.gitbook/assets/ uVfrZsofR\_D338hzgLrO\_image.png>)

### Visit Cancellation

Personal cancellation is sent automatically when the visit is deleted.

![](../../.gitbook/assets/5oxXq4BwNZcSLy6fEAEEh\_image.png)

### Group Invitation

![](../../.gitbook/assets/qDVa95n1vMF6JFn07OTfy\_image.png)

Use "|" as a column separator in the table.

{VisitorList} {firstname}|{lastname}|PIN {pin}| {QR} {/VisitorList}

:::hint{type="info"} Note that group invitations are marked with the letter "G".

![](../../.gitbook/assets/kKePNxj9CJzzp4CIwelGO\_image.png) :::

#### Example 1 (with PINs)

{VisitorList} {firstname}|{lastname}|PIN {pin} {/VisitorList}

![](../../.gitbook/assets/0GOLiCiJLKDhNhvZZE\_w8\_image.png)

#### Example 2 (with QR-Codes)

{VisitorList} {firstname}|{lastname}|PIN {pin}| {QR} {/VisitorList}

![](../../.gitbook/assets/vOKzOIh\_VtVZROfJ171Ba\_image.png)

### Online Registration

## Customize Invitation Template

![](<../../.gitbook/assets/QU2qtPlWJXlbj2tS3 AGN\_image.png>)

Customize your invitation template using the Email Editor based on your preferences.

Utilize Special Keywords to enable the System to dynamically replace values based on visit and visitor data.

### Special Keywords

| **Key name**       | **Description**                                   |
| ------------------ | ------------------------------------------------- |
| {Title}            | Visit title                                       |
| {VisitorName}      | Visitor's full name                               |
| {FirstName}        | Visitor's first name                              |
| {LastName}         | Visitor's last name                               |
| {Organizer}        | The organizer's first and last name               |
| {Address}          | Visit address                                     |
| {Floor}            | Floor in the building of the visit location       |
| {Room}             | Room number in the building of the visit location |
| {StartDate}        | Visit start date                                  |
| {StartTime}        | Visit start time and time zone (UTC format)       |
| {EndDate}          | Visit end date                                    |
| {EndTime}          | Visit end time and time zone (UTC format)         |
| {Description}      | Full description of the visit                     |
| {Map}              | Location map                                      |
| {MapURL}           | Link to the on-line map of the visit location     |
| {PIN}              | PIN code for visitor registration                 |
| {StaticPIN}        | Static PIN code for visitor registration          |
| {QR}               | QR code for visitor registration                  |
| {Barcode}          | Barcode for visitor registration                  |
| {ExternalID}       | External ID for visitor registration              |
| {RegistrationLink} | Link to online registration                       |

## Uploading an HTML template for emails

In some cases, it is preferable to use an HTML template, particularly when sending high-quality images that need to be displayed correctly to the end user.

The HTML template can be created by a friendlyway developer, or you may reach out to any other vendor to design the required HTML template. Alternatively, you can utilize an online HTML editor such as '[HTML Editor: online HTML editor with real-time preview](https://htmleditor.gitlab.io/)' or '[HTML Editor - Online Web Content Composer](https://html5-editor.net/).'

Once you receive the HTML file, you should upload it to the platform and save it. Subsequent invitations will be dispatched based on the HTML template.

![](<../../.gitbook/assets/AtRKbQXjV8SaJZDgja qs\_image.png>)
