# Blended Blog
This is a simple blog template for Blended.

To use, download all of these files into the 'templates' folder of your Blended website.

## Plugins Needed

### Google Fonts

You need the [Blended Google Fonts](https://github.com/BlendedSiteGenerator/blended_google_fonts) plugin.

Install it by running `pip install blended_google_fonts`

Add `google_fonts = [["Open Sans", "300"], ["Roboto", "300"]]` to your `config.py` file.

### Twitter Cards

You need the [Blended Twitter Cards](https://github.com/BlendedSiteGenerator/blended_twitter_cards) plugin.

Install it by running `pip install blended_twitter_cards`

Add

```python
twitter_card = "summary"
twitter_site = "" # Your website URL
twitter_title = "{website_name} | {page_name}"
twitter_description = "{website_description}"
twitter_image = "" # Your website icon
```

to your `config.py`
