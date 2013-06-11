# CookieCons

Original Silktide's Cookie Consent source code with links, logos and embeded objects removed, so that it works as a free standalone jquery application.

## Requirements

jQuery 1.4 or higher.

## Installation

1. Copy the files to your server root or where it suits you.
2. Change the cookieconf.js configuration file to suit your needs.
3. Call the code in your header:

```html
<script src='scripts/jquery-1.7.2.min.js'></script>
<link href="css/cookiecons.css" rel="stylesheet" type="text/css" />
<script src='scripts/cookiecons.js'></script>
<script src='scripts/cookieconf.js'></script>
```
4. Change opening script tags of your social, analytics and advertisement code blocs to type='text/plain' and add the appropriate class:

```html
<script type="text/plain" class="cc-onconsent-advertising">
```

Alternate classes are:

- cc-onconsent-advertising
- cc-onconsent-social
- cc-onconsent-analytics
- cc-onconsent-inline-advertising
- cc-onconsent-inline-social
- cc-onconsent-inline-analytics

You can get code examples here:
[http://silktide.com/cookieconsent/documentation/code-examples](http://silktide.com/cookieconsent/documentation/code-examples)


