# PyroCMS Bands In Town Widget

* Author: Michael Giuliana
* Twitter: [@rpnzldesign](http://www.twitter.com/rpnzl)
* Website: [http://rpnzl.com/](http://rpnzl.com/)
* Version: 1.1

## Important

Please review the Bands In Town API v2.0 [Overview](http://www.bandsintown.com/api/overview) and [Best Practices](http://www.bandsintown.com/api/best_practices) before utilizing this widget. **You must choose a custom, descriptive App ID as per Bands In Town's guidelines.**

## Description

This PyroCMS widget interacts with Bands In Town's API v2.0 and will display customized event information *for a single artist* as a table on your site. The current API does not allow for more general search criteria. This widget will be updated if BIT expands their API's capabilities.

This widget now caches API calls for five minutes with the help of PyroCache.

## Installation

Rename the **pyrocms-widget-bit** folder -> **bandsintown** and drop it into your **addons/shared_addons/widgets** directory.

## Configuration

Head over to the Admin Widgets module, drag the Bands In Town widget onto a widget area and fill out the required fields to get started.

**App ID** (*Required*) - You must choose a custom, descriptive App ID.

**Limit** (*Required*) - The max number of events to display. Setting to zero (0) will display zero (0) events. Set to a higher number (100) to reveal more.

**Location** (*Optional*) - City,State / City,Country / Lat,Lon / IP Address

**Radius** (*Optional*) - Radius in miles from your chosen location to search for shows.

**MBID** or **Artist Name** (*Required*) - One of these parameters is required to make an API call since BIT limits us to a single artist.

**Artist FB Page ID** (*Optional*) - Optional, to be used in combination with the artist's name or MBID.

**Display Options** - Alter the visibility of columns in the table that will be displayed by the widget.

