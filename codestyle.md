# Код стайл для верстки. 


### Конфигурация для stylelint
```json
{
    "extends": "stylelint-config-standard",
    "rules": {
        "indentation": 4,
        "string-quotes": "single",
        "no-duplicate-selectors": true,
        "color-hex-case": "lower",
        "color-hex-length": "long",
        "color-named": "never",
        "color-no-hex": true,
        "selector-no-qualifying-type": true,
        "selector-no-id": true,
        "selector-no-combinator": true,
        "selector-combinator-space-after": "always",
        "selector-attribute-quotes": "always",
        "selector-attribute-operator-space-before": "always",
        "selector-attribute-operator-space-after": "always",
        "selector-attribute-brackets-space-inside": "never",
        "declaration-block-trailing-semicolon": "always",
        "declaration-no-important": true,
        "declaration-colon-space-before": "never",
        "declaration-colon-space-after": "always",
        "property-no-vendor-prefix": true,
        "value-no-vendor-prefix": true,
        "number-leading-zero": "always",
        "function-url-quotes": "always",
        "function-url-data-uris": "always",
        "comment-empty-line-before": "always",
        "at-rule-no-vendor-prefix": true,
        "selector-pseudo-element-colon-notation": "single",
        "selector-pseudo-class-parentheses-space-inside": "always",
        "selector-no-vendor-prefix": true,
        "selector-no-type": true,
        "media-feature-range-operator-space-before": "always",
        "media-feature-range-operator-space-after": "always",
        "media-feature-parentheses-space-inside": "never",
        "media-feature-name-no-vendor-prefix": true,
        "media-feature-colon-space-before": "never",
        "media-feature-colon-space-after": "always"
    }
}
```