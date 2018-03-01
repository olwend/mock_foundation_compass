# Foundation Mock Component

To increase knowledge of NHM website, Foundation and SCSS stylesheets.
main.css (etc/clientlibs/nhmwww/main.css)
foundation.css (etc/clientlibs/nhmwww/main/foundation.css)

## cta-button AEM NHM implementation
### Taking as basis and reworking for pure Foundation project

  * large-6 medium-6 columns large6-margin
  * par parsys - N/A this is an AEM requirement
  * ctabutton parbase section - rename to simplify
  * N/A image handling with data-interchange (default, retina, small, medium, large)
  * footer thumb-caption  visit and home-thumb-right h3 have margin
  * data-gtm=CTA is ID for Google tag manager N/A

## To Do
	* Understand which class - styling does what
	* Style as per NHM - add custom css
	* Shift thumb-caption onto image and set colour

## Note
I used https://image.online-convert.com/convert-to-svg to convert jpg to svg, but this is not of required quality.
This would need sourcing from AEM assets. (low priority)

## Quickstart

  * [Download this starter compass project and unzip it](https://github.com/zurb/foundation-compass-template/archive/master.zip)
  * Run `bower install` to install the latest version of Foundation

Then when you're working on your project, just run the following command:

```bash
bundle exec compass watch
```
