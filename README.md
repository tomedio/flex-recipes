# Symfony Recipes Repository

This repository contains Symfony Flex recipes for Tomedio packages.

## Available Recipes

### Stripe Symfony Bundle

A Symfony bundle for integrating Stripe payment processing with Symfony applications.

## Usage

To use these recipes in your Symfony project, add this repository to your `composer.json`:

```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "https://raw.githubusercontent.com/tomedio/symfony-recipes/main/index.json",
                "flex://defaults"
            ]
        }
    }
}
```

Then, when you install a package that has a recipe in this repository, Symfony Flex will automatically apply the recipe.

## Contributing

If you want to contribute to this repository, please follow these steps:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request

## License

This repository is licensed under the MIT License.
