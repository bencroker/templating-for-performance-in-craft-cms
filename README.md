# Templating for Performance in Craft CMS

A set of templates that demonstrate poor vs. good practices when outputting lists of entries in templates.

## Requirements

Craft CMS 3.0.0 or later.

## Usage

1. Set up a section with the slug `articles` and the fields `order` (number field) and `relatedEntries` (entries field). 
3. Copy the templates in the `templates` folder to your project.
3. Optionally create and import a feed using the FeedMe plugin pointed at the `feed.twig` template.
4. Visit the listing templates (`your-domain/listing/0` - `your-domain/listing/10`) in your browser.

## License

All code is licensed under the MIT License with attribution.

<small>Created by [PutYourLightsOn](https://putyourlightson.com/).</small>
