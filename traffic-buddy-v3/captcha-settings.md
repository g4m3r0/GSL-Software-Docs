---
description: >-
  This documentation provides an overview of the Captcha Solving Settings page,
  explaining each available option to help you configure the feature
  effectively.
---

# Captcha Settings

### Overview

The CAPTCHA SOLVING SETTINGS page allows you to integrate a third-party, automatic CAPTCHA solving service with the application. When configured, the application can delegate CAPTCHA challenges to this service, which solves them and sends back the solution. This enables smoother, uninterrupted operation when navigating websites that are protected by CAPTCHAs.To use this functionality, you must first register and have an active account with one of the supported CAPTCHA solving providers.

<figure><img src="../.gitbook/assets/captcha settings.png" alt="Traffic Buddy: Captcha Solving Settings"><figcaption></figcaption></figure>

### Available Settings

Below is a detailed explanation of each setting available on the page.

#### Captcha Solving Service

* **Purpose:** This dropdown menu allows you to select the CAPTCHA solving provider you wish to use.
* **How to use:** Click the dropdown and select the name of the service you have an account with. The application supports a variety of popular providers, which are listed here.

#### API Key

* **Purpose:** This is your personal authentication key provided by the CAPTCHA service. The application uses this key to securely connect to your account and request CAPTCHA solutions.
* **How to use:** Log in to your account on your chosen CAPTCHA provider's website. Find the API Key (often in the "Account" or "API" section of their dashboard), copy it, and paste it into this text field.

#### Timeout (in Seconds)

* **Purpose:** This setting defines the maximum time the application will wait for the solving service to return a solution for a single CAPTCHA.
* **How to use:** Enter a whole number representing the timeout duration in seconds. If the service does not provide a solution within this time, the request will be cancelled. A typical value is between 60 and 120 seconds, but this may vary depending on the provider and CAPTCHA complexity.

### Saving Your Configuration

After you have configured the settings, you must save them.•Save Button: Click the Save button (icon shaped like a floppy disk) to apply and store your changes. If you do not save, any changes you made will be lost when you navigate to a different page.

