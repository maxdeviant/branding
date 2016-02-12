# Remark Partner Branding

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

Remark Test Grading Cloud Edition allows partners to customize the following fields when branding the application:

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

**Example:**

```json
{
    "brandLogoUrl": "/Content/branding/Gravic/images/logo.png"
}
```

#### Contact Link

An absolute URL to the "Contact" page for the partner.

**Example:**

```json
{
    "contactUsUrl": "http://remarksoftware.com/contact"
}
```

#### About Link

An absolute URL to the "About" page for the partner.

**Example:**

```json
{
    "aboutUsUrl": "http://remarksoftware.com/about"
}
```

#### Acceptable Use Policy

An absolute or relative URL to an HTML page containing the Acceptable Use Policy text.

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

**Example:**

```json
{
    "termsOfServiceUrl": "/Content/branding/Gravic/templates/terms-of-service.html"
}
```

#### Privacy Policy

An absolute or relative URL to an HTML page containing the Privacy Policy text.

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
    "processingInstructionsUrl": ""
}
```

#### Online Help

An absolute or relative URL to the application's online help.

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

![Header Screenshot](https://github.com/remarksoftware/branding/blob/master/images/header.png)

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

![Footer Screenshot](https://github.com/remarksoftware/branding/blob/master/images/footer.png)

---

## Email Templates

Remark Test Grading Cloud Edition comes with default email templates which will be used when sending email notifications. These default templates are able to be customized using the provided set of properties.

It is also possible to use custom email templates.

**Default Email Template**

![Default Email Template Screenshot](https://github.com/remarksoftware/branding/blob/master/images/default-email-template.png)

### Table of Contents
- [Default Email Properties](#default-email-properties)
    - [Application Name](#application-name)
    - [Email Summary](#email-summary)
    - [Header](#header)
    - [Title](#title)
    - [Body](#body)
    - [Notes](#notes)
    - [Year](#year)
    - [Company](#company)
    - [Footer](#footer)

### Default Email Properties

The default email templates can be customized using an existing set of properties, which can be modified on a per-category basis.

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

The current calendar year.

#### Company

The name of the company.

#### Footer

The footer for the email.
