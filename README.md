# JsonSchema Bundle

The component ships a Bundle to allow a quick integration with Symfony for the JsonSchema component of Jane.
To use it, you just have to add the main bundle class to your `config/bundles.php` file.
If you use Flex, it's automatic.

```php
return [
    // ...
    Jane\Bundle\JsonSchemaBundle\JaneJsonSchemaBundle::class => ['dev' => true],
];
```
