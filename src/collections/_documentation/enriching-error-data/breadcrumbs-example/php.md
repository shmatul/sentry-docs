```php
Sentry\addBreadcrumb(new Sentry\Breadcrumb(
  Sentry\Breadcrumb::LEVEL_ERROR, 
  Sentry\Breadcrumb::TYPE_ERROR, 
  'error_reporting', 
  'foo bar'
));
```
