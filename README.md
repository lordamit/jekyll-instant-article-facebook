# Update
Update: I stopped using instant article. In short, Facebook changed their structure about how instant articles work. You can find more details [here](https://github.com/Automattic/facebook-instant-articles-wp/issues/925#issuecomment-385397596).

Personally, I found Instant Article to be user unfriendly because FB keeps introducing arbitrary changes.


# Facebook Instant Article for Jekyll ⚡ RSS Feed
### v1.0

Facebook instant article helps you to read articles from Facebook in a special format that loads blazingly fast in your Facebook app. This requires storing an instant version of your article in Facebook. To submit the articles to Facebook in an automatic way, there are two approaches.

- RSS
- API

This tool generates Facebook instant article compatible RSS feed. It is based on liquid tags, a single xml file and insanely simple!

## Why?
- Simple - requires **only one liquid based xml file**
- Low overhead
- Easy
- Configurable

## Features
By configuring several things in `_config.yml` and in the `front matter YAML` of your article in jekyll, you can offer several things for your reader in the instant version. These are:

- A header `image`, that will be by default your site logo, or will use an image specified in your front matter.
- `instantfeedback`, that will allow your readers to like images used in your article
- `credit`, that will append the credit related texts at the end of the instant article, in case you have used materials by others.  

## Documentation
For installation, configuration and other details, please head over to the [Wiki](https://github.com/lordamit/jekyll-instant-article-facebook/wiki) section.

## Contribute
Got any suggestion? Think you can improve it?
I would *love* to hear it. Send me a pull request, email me, post in [Issues](https://github.com/lordamit/jekyll-instant-article-facebook/issues) - your choice.

## For Awesome Users
Please include your site name in  ["Sites using"](https://github.com/lordamit/jekyll-instant-article-facebook/wiki/Sites-using-jekyll-instant-article-facebook) section to include your site's address. Lets build the community together. :)

Thank you!
