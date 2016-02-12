# Remark Test Grading Cloud Edition - Partner Branding

## Table of Contents
- [Partner Configuration](#partner-configuration)
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

## Partner Configuration

Remark Test Grading Cloud Edition allows partners to customize the following fields when branding the application:

### Partner Name

The full name of the partner.

**Example:**

```json
{
    "partnerName": "Gravic, Inc."
}
```

### Partner Short Name

The shortened name of the partner, if applicable.

**Example:**

```json
{
    "partnerShortName": "Gravic"
}
```

### Product Name

The name of the product.

**Example:**

```json
{
    "productName": "Remark Test Grading Cloud Edition"
}
```

### Product Description

A short description of the product.

**Example:**

```json
{
    "productDescription": "Remark Test Grading Cloud Edition"
}
```

### Favicon (Bookmark Icon)

An absolute or relative URL to the image to use as the application's favicon.

**Example:**

```json
{
    "faviconUrl": "/Content/branding/Gravic/images/favicon.ico"
}
```

### Partner Logo

An absolute or relative URL to the image to display as logo for the partner.

**Example:**

```json
{
    "brandLogoUrl": "/Content/branding/Gravic/images/logo.png"
}
```

### Contact Link

An absolute URL to the "Contact" page for the partner.

**Example:**

```json
{
    "contactUsUrl": "http://remarksoftware.com/contact"
}
```

### About Link

An absolute URL to the "About" page for the partner.

**Example:**

```json
{
    "aboutUsUrl": "http://remarksoftware.com/about"
}
```

### Acceptable Use Policy

An absolute or relative URL to an HTML page containing the Acceptable Use Policy text.

**Example:**

```json
{
    "acceptableUsePolicyUrl": "/Content/branding/Gravic/templates/acceptable-use-policy.html"
}
```

### Terms of Use

An absolute or relative URL to an HTML page containing the Terms of Use text.

**Example:**

```json
{
    "termsOfUseUrl": "/Content/branding/Gravic/templates/terms-of-use.html"
}
```

### Terms of Service

An absolute or relative URL to an HTML page containing the Terms of Service text.

**Example:**

```json
{
    "termsOfServiceUrl": "/Content/branding/Gravic/templates/terms-of-service.html"
}
```

### Privacy Policy

An absolute or relative URL to an HTML page containing the Privacy Policy text.

**Example:**

```json
{
    "privacyPolicyUrl": "/Content/branding/Gravic/templates/privacy-policy.html"
}
```

### Processing Instructions

An absolute or relative URL to an HTML page containing instructions for email processing.

**Example:**

```json
{
    "processingInstructionsUrl": ""
}
```

### Online Help

An absolute or relative URL to the application's online help.

**Example:**

```json
{
    "onlineHelpUrl": "/Help/Gravic/index.html"
}
```

### Notification Email Alias

The alias to use for the sender when sending email notifications.

**Example:**

```json
{
    "notificationAlias": "Remark Test Grading Cloud Edition"
}
```

### Notification Email Address

The email address to use for the sender when sending email notifications.

**Example:**

```json
{
    "notificationEmail": "no-reply@gravic.com"
}
```

### API Notification Email Alias

The alias to use for the sender when sending email notifications for the Remark Web API.

**Example:**

```json
{
    "statusChangeNotificationEmailAlias": "RWA Notifications"
}
```

### API Notification Email Address

The email address to use for the sender when sending email notifications for the Remark Web API.

**Example:**

```json
{
    "statusChangeNotifcationEmail": "rwanotifications@gravic.com"
}
```

### Host Name

The hostname where the application is being hosted.

**Example:**

```json
{
    "hostName": "remarktesting.gravic.com"
}
```

### Incoming Email Domain

The domain to allow email submissions from.

**Example:**

```json
{
    "incomingEmailDomain": "remarktesting.gravic.com"
}
```
