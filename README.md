# Platform-Locale-Bundle

The Locale bundle extends the OroLocaleBundle and provides additional core locale functionality. 

## Table of Contents

- [Twig Extensions](#migration-extensions)
- [Todo](#todo)

## Twig Extensions

This bundle provides a convenient twig extension to translate localised entity attributes based on current request locale.

**Example**:

```twig
<html>
    <body>
        <h1>
            {{ service.titles|localized_value }}
        </h1>
    </body>
</html>
```

## Todo

