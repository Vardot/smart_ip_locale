# Smart IP - Language Negotiation Redirect

This module adds language redirection via [Smart IP](https://www.drupal.org/project/smart_ip) module.

## Installation:
```
composer require drupal/smart_ip_locale
```

## Usage:
We recommend you use this module along with [Language Cookie](https://www.drupal.org/project/language_cookie) module. This way you prevent IP to Language resolution for every page request.

* Enable the module and go to: Administration » Configuration » Regional and language » Languages
* Enable the "Smart IP country code" detection method and re-arrange the detection methods as you see fit. The recommended arrangement is: "URL -> Cookie -> Smart IP country code".
* Edit the configuration of the module, by adding the country code mapping to each corresponding language.

## Dependencies:
* [Smart IP](https://www.drupal.org/project/smart_ip)

## Best used with:
* [Language Cookie](https://www.drupal.org/project/language_cookie)


