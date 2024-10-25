# Droptica’s Drupal Recipes: Security - Automatic logout of users after a period of inactivity

## Recipe description

This Recipe adds automatic logout of users after a period of inactivity.

After installing the Recipe, customize the settings on this page:
- `/admin/config/people/autologout`


## Download recipe

```shell
composer require droptica/ddr_security_automated_logout
```

## Installation

Optionally: Before installation, adjust the recipe files to your project (e.g., email variables, names, labels, etc.).

```shell
drush recipe recipes/contrib/ddr_security_automated_logout
```

## How to report issues and new features requests

Go to project page (@todo url) and create an issue.

## Do you need a Drupal Recipe for your project?

Typical problems that we solve with Recipes:

* **Standardizing Configuration Across Multiple Sites:**
  Need to keep dozens of websites consistent? Recipes can automate the setup of identical configurations, ensuring each site operates with the same settings, such as security or SEO configurations.

* **Onboarding New Sites Quickly:**
  Launching new websites with the same features and configuration becomes seamless, reducing the time needed for manual setup and potential human error.

* **Implementing a New Feature with Proven Solutions:**
  When adding a new feature to an existing website, you need a reliable and efficient solution. Recipes can help implement proven configurations, such as a simple CRM, an SEO-optimized blog, commerce payment gateway configuration for PayPal, a knowledge base for an intranet system, or an article content type for a news portal.

Contact us if you need support in creating a custom Drupal Recipe.

## Contact

https://www.droptica.com/drupal-recipes


## Changelog

### 2024-10-09
First version of the recipe.
