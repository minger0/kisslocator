# KISSLocator
Keywords: locator, floor plan, map, campus, building, floor, office, store, desk, seat, colleague

Do you have some maps you want to place objects on?

Do you want to locate a colleague, a building, a room, or some other objects?

KISSLocator keeps it simple for you. The setup takes about a minute, so give it a try!

# How does it work?

KISSLocator is a html/js solution, that provides you url links to the locations on your maps, in the following format.

```
<domain>/KISSLocator.html?area=<map name>&x=<x coordinate>&y=<y coordinate>#map<floor id>
```

Example after a download to your local disk:

```
file:///C:/my/code/locator/KISSLocator.html?area=palace&x=524.889970788705&y=419.57781456953643#map0
```

An overview of the uploaded maps:
```
file:///C:/my/code/locator/KISSLocator.html 
```


The url links can be used in mail subscriptions, or added to shared personal properties.

It is easy and practical to source into an intranet wiki (given that html/js is allowed), but it can be also used on shares, without http.

# Install
(1) Upload your map images (svg, png, jpg, etc.), along with the KISSLocator.html, the KISSLocator_config.js, and the topleft_arrow_transparent_bg.png to the same intranet, shared, or wiki location

(2) Update the KISSLocator_config.js file so that it stores references to your uploaded maps

(3) Enjoy!
