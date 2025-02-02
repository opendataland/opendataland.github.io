---
layout: splash
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_image: assets/images/pdm-adjusted-banner.png
  actions:
    - label: "Learn More"
      url: "/about/"
excerpt: >
  Join the volunteer movement to improve, collect, and publish open geospatial data that can be used by government agencies, private industry, and nonprofits to better inform policy decisions.<br />
feature_row:
  - image_path: /assets/images/fra_railroadtunnels.png
    alt: "customizable"
    title: "Railroad Tunnels in Colorado"
    excerpt: "Assist the Federal Railroad Administration in mapping the location of railroad tunnels in Colorado."
  - image_path: /assets/images/covered-bridge-in-forest-2.jpg
    alt: "fully responsive"
    title: "Bridges in Michigan"
    excerpt: "More details on this project available soon!"
  - image_path: /assets/images/mountain_trail_stock.jpg
    alt: "100% free"
    title: "Trail Network in Washington"
    excerpt: "More details on this project available soon!"
gallery:
  - url: https://www.usgs.gov/
    image_path: https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/USGS_logo_green.png
    alt: "USGS"
  - url: https://www.transportation.gov/
    image_path: https://www.transportation.gov/sites/dot.gov/files/sxsw/images/us-dot.png
    alt: "US DOT"
  - url: https://railroads.dot.gov/
    image_path: https://www.transportation.gov/sites/dot.gov/files/sxsw/images/us-dot.png
    alt: "FRA"
---

{% include feature_row %}

{% capture notice-2 %}
# *"Many government agencies and private companies are unwilling to accept the legal risk of using data not explicitly placed in the public domain. Removing these restrictions fosters data sharing, the creation of knowledge, and cultivates understanding.”*

### Derald Dudley, Transportation Theme Lead, NSDI, USDOT
{% endcapture %}

<div class="notice">{{ notice-2 | markdownify }}</div>

## Who uses Public Domain Map data?

{% include gallery id="gallery" %}

Interested in using Public Domain Map for your agency? Reach out to info@publicdomainmap.org
