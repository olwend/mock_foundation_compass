# Foundation Mock Component
## Taking live NHM website as basis and reworking for pure Foundation local project

To increase knowledge of NHM website, Foundation and SCSS stylesheets.
main.css (etc/clientlibs/nhmwww/main.css)
foundation.css (etc/clientlibs/nhmwww/main/foundation.css)

## Compass
In order to compile the css from scss ```bundle exec compass watch```


## cta-button AEM NHM implementation
	* large-6 medium-6 columns large6-margin
	* par parsys - N/A this is an AEM requirement called by above
	* ctabutton parbase section - rename to simplify
	* N/A image handling with data-interchange (default, retina, small, medium, large)
	* footer thumb-caption  visit and home-thumb-right h3 have margin
	* data-gtm=CTA is ID for Google tag manager N/A

## featured-article
	* herosection
	* par2 parsys - N/A this is an AEM requirement called by above
	* featuredarticle parbase section
	* N/A image handling with data-interchange (default, retina, small, medium, large)
	* href wraps the component
	* container - image container - image (data interchange) - row - text container

N.B. The image is smaller than required for the text container to sit over it.

## header text images
	*
	*
	*

## Note
I used https://image.online-convert.com/convert-to-svg to convert jpg to svg, but this is not of required quality.
This would need sourcing from AEM assets (low priority), so I've continued with jpeg format.

## Styling
The custom scss is included into app.css write  by ```@import "foundation/components/xxxxxx.scss";``` in app.scss

Only header font-color and font-size are uncommented in ```_settings.scss``` as this is a minimal implementation.





