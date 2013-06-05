# Octopress Openweathermap

Aside to display weather current conditions in the sidebar of your Octopress site.

Live example at [stombi.net](http://www.stombi.net/).

## Setup

1. Copy ```openweathermap.html``` to your ```_includes/custom/asides``` directory.
2. Grab an API key at [openweathermap.org](http://openweathermap.org/) (it's free)
3. Update your ```_config.yml``` file to include ```openweathermap_*``` variables as shown in example below which is also in the provided ```_config.yml``` file:

		# Weather
		# API key
		openweathermap_key: 
		# H1 title
		openweathermap_title: Weather
		# City name
		openweathermap_city_name: Los Angeles
		# Units : metric or imperial
		openweathermap_units: imperial
		# Lang : en, ru, it, sp, ua, de, pt, ro, pl, fi, nl, fr, bg, se, zh_tw, zh_cn, tr 
		openweathermap_lang: en
		# cache data to localStorage n seconds
		openweathermap_cache: 3600

4. Add ```openweathermap.html``` to your default_asides variable in the ```_config.yml``` settings file. Example:

	default_asides: [custom/asides/openweathermap.html, custom/asides/about.html, asides/twitter.html, asides/recent_posts.html]
 
5. Regenerate your blog
