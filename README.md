# Remark Partner Branding

This document provides information relating to customizing Remark Test Grading Cloud Edition for an individual partner's usage.

## Table of Contents
- [Partner Configuration](#partner-configuration)
- [Application Theming](#application-theming)
- [Email Templates](#email-templates)

## Partner Configuration

Remark Test Grading Cloud Edition is able to be configured for an individual partner.

### Table of Contents
- [Customizable Fields](#customizable-fields)
    - [Partner Name](#partner-name)
    - [Partner Short Name](#partner-short-name)
    - [Product Name](#product-name)
    - [Product Description](#product-description)
    - [Favicon (Bookmark Icon)](#favicon-bookmark-icon)
    - [Partner Logo](#partner-logo)
    - [Contact Link](#contact-link)
    - [About Link](#about-link)
    - [Acceptable Use Policy](#acceptable-use-policy)
    - [Terms of Use](#terms-of-use)
    - [Terms of Service](#terms-of-service)
    - [Privacy Policy](#privacy-policy)
    - [Processing Instructions](#processing-instructions)
    - [Online Help](#online-help)
    - [Notification Email Alias](#notification-email-alias)
    - [Notification Email Address](#notification-email-address)
    - [API Notification Email Alias](#api-notification-email-alias)
    - [API Notification Email Address](#api-notification-email-address)
    - [Host Name](#host-name)
    - [Incoming Email Domain](#incoming-email-domain)

### Customizable Fields

Remark Test Grading Cloud Edition allows partners to customize the application using a [JSON](https://en.wikipedia.org/wiki/JSON) document.

**Example:**
```json
{
    "partnerName": "Gravic, Inc.",
    "productName": "Remark Test Grading Cloud Edition",
    "brandLogoUrl": "/Content/branding/Gravic/images/logo.png"
}
```

The following properties are available for customization:

#### Partner Name

The full name of the partner.

**Example:**

```json
{
    "partnerName": "Gravic, Inc."
}
```

#### Partner Short Name

The shortened name of the partner, if applicable.

If no shortened name is required, this property should be the same as the [Partner Name](#partner-name).

**Example:**

```json
{
    "partnerShortName": "Gravic"
}
```

#### Product Name

The name of the product.

**Example:**

```json
{
    "productName": "Remark Test Grading Cloud Edition"
}
```

#### Product Description

A short description of the product.

**Example:**

```json
{
    "productDescription": "Remark Test Grading Cloud Edition"
}
```

#### Favicon (Bookmark Icon)

An absolute or relative URL to the image to use as the application's favicon.

**Example:**

```json
{
    "faviconUrl": "/Content/branding/Gravic/images/favicon.ico"
}
```

#### Partner Logo

An absolute or relative URL to the image to display as the logo for the partner.

This image will be shown in the application's [header](#header).

**Example:**

```json
{
    "brandLogoUrl": "/Content/branding/Gravic/images/logo.png"
}
```

#### Contact Link

An absolute URL to the "Contact" page for the partner.

This link will be available through the application's [footer](#footer).

**Example:**

```json
{
    "contactUsUrl": "http://remarksoftware.com/contact"
}
```

#### About Link

An absolute URL to the "About" page for the partner.

This link will be available through the application's [footer](#footer).

**Example:**

```json
{
    "aboutUsUrl": "http://remarksoftware.com/about"
}
```

#### Acceptable Use Policy

An absolute or relative URL to an HTML page containing the Acceptable Use Policy text.

This link will be available through the application's [footer](#footer).

**Example:**

```json
{
    "acceptableUsePolicyUrl": "/Content/branding/Gravic/templates/acceptable-use-policy.html"
}
```

#### Terms of Use

An absolute or relative URL to an HTML page containing the Terms of Use text.

**Example:**

```json
{
    "termsOfUseUrl": "/Content/branding/Gravic/templates/terms-of-use.html"
}
```

#### Terms of Service

An absolute or relative URL to an HTML page containing the Terms of Service text.

This link will be available through the application's [footer](#footer).

**Example:**

```json
{
    "termsOfServiceUrl": "/Content/branding/Gravic/templates/terms-of-service.html"
}
```

#### Privacy Policy

An absolute or relative URL to an HTML page containing the Privacy Policy text.

This link will be available through the application's [footer](#footer).

**Example:**

```json
{
    "privacyPolicyUrl": "/Content/branding/Gravic/templates/privacy-policy.html"
}
```

#### Processing Instructions

An absolute or relative URL to an HTML page containing instructions for email processing.

**Example:**

```json
{
    "processingInstructionsUrl": "/Content/branding/Gravic/templates/processing-instructions.html"
}
```

#### Online Help

An absolute or relative URL to the application's online help.

This link will be available through the application's [header](#header);

**Example:**

```json
{
    "onlineHelpUrl": "/Help/Gravic/index.html"
}
```

#### Notification Email Alias

The alias to use for the sender when sending email notifications.

**Example:**

```json
{
    "notificationAlias": "Remark Test Grading Cloud Edition"
}
```

#### Notification Email Address

The email address to use for the sender when sending email notifications.

**Example:**

```json
{
    "notificationEmail": "no-reply@gravic.com"
}
```

#### API Notification Email Alias

The alias to use for the sender when sending email notifications for the Remark Web API.

**Example:**

```json
{
    "statusChangeNotificationEmailAlias": "RWA Notifications"
}
```

#### API Notification Email Address

The email address to use for the sender when sending email notifications for the Remark Web API.

**Example:**

```json
{
    "statusChangeNotifcationEmail": "rwanotifications@gravic.com"
}
```

#### Host Name

The hostname where the application is being hosted.

If the application is being hosted somewhere other than `*.gravic.com`, additional configuration will be required.

**Example:**

```json
{
    "hostName": "remarktesting.gravic.com"
}
```

#### Incoming Email Domain

The domain to allow email submissions from.

**Example:**

```json
{
    "incomingEmailDomain": "remarktesting.gravic.com"
}
```

---

## Application Theming

The visual styles of Remark Test Grading Cloud Edition are able to be customized through the use of partner-specific themes.

### Table of Contents
- [Themeable Elements](#themeable-elements)
    - [Header](#header)
    - [Main Application](#main-application)
    - [Footer](#footer)

### Themeable Elements

The following elements within the application are currently eligible for theming:

#### Header

- Background Color
- Link Color
- Link Hover Color

**Header Screenshot**

![Header Screenshot](https://raw.githubusercontent.com/remarksoftware/branding/master/images/header.png)

#### Main Application

- Background Color
- Primary Text Color
- Link Color
- Link Hover Color

#### Footer

- Background Color
- Link Color
- Link Hover Color

**Footer Screenshot**

![Footer Screenshot](https://raw.githubusercontent.com/remarksoftware/branding/master/images/footer.png)

---

## Email Templates

Remark Test Grading Cloud Edition comes with default email templates which will be used when sending email notifications. These default templates are able to be customized using the provided set of properties.

It is also possible to use custom email templates. These templates will be able to make use of the same property substitutions as the default email templates.

**Default Email Template**

![Default Email Template Screenshot](https://raw.githubusercontent.com/remarksoftware/branding/master/images/default-email-template.png)

**Default Alert Email Template**

![Default Alert Email Template Screenshot](https://raw.githubusercontent.com/remarksoftware/branding/master/images/default-alert-email-template.png)

### Table of Contents
- [Default Email Properties](#default-email-properties)
    - [Theme Color](#theme-color)
    - [Application Name](#application-name)
    - [Email Summary](#email-summary)
    - [Header](#header)
    - [Title](#title)
    - [Body](#body)
    - [Notes](#notes)
    - [Year](#year)
    - [Footer](#footer)

### Default Email Properties

The default email templates can be customized using an existing set of properties, which can be modified on a per-category basis.

### Theme Color

A valid CSS color to use to theme the email.

#### Application Name

The name of the application.

#### Email Summary

A short summary of the email.

#### Header

The header for the email.

#### Title

The title of the email.

#### Body

The body of the email.

#### Notes

Any additional notes for the email recipient.

#### Year

This value will default to the current year.

#### Footer

The footer for the email.

---

&copy; 2016 Gravic, Inc.
