---
layout: post
title: "World Press Photo Gallery"
date: 2024-07-26 20:58:27 +0000
categories: blog
---

### **> *A web application designed for photojournalism enthusiasts***

[![World Press photo ](https://raw.githubusercontent.com/hericlibong/worldPressPhotoGalery/main/media/worldpressphoto.PNG)](ttps://github.com/hericlibong/worldPressPhotoGalery)

[**WorldPressPhotoGallery**](https://github.com/hericlibong/worldPressPhotoGalery) is a web application designed for photojournalism enthusiasts. It allows users to view, select, and vote for the most striking news images, highlighted for their photojournalistic impact.

Each week, we collect these emblematic images from the weekly selections of major media outlets. This collection is performed through scraping, using Scrapy, to gather the most compelling works of global photojournalism. Subsequently, with Django, we provide an interface where users can interact with these images, assess them, and soon, share their impressions.

#### Main Features
Voting and Rating: Registered users can vote for their favorite images and rate them on a scale from 1 to 10.


<a href ="https://github.com/hericlibong/worldPressPhotoGalery">
    <img src = "media/worlpressphoto_rated.PNG" alt = "picture rated" width = "600" height = "400">
</a>
Image Size: The size of the image can be adjusted by specifying the width and height attributes in the HTML `<img>` tag. For example:

```html
<img src="/media/worldpressphoto_rated.PNG" alt="picture rated" width="600" height="400">
```



![worldpressphoto_rated](/media/worldpressphoto_rated.PNG)

#### Technology
This application utilizes Scrapy to collect images through spiders dedicated to each media outlet. The images are processed via Scrapy items before being sent to the database.

**Scrapy**: Collects images via individual spiders.
**Django**: The collected images are stored in a SQLite3 database and managed by a model of the framework, then displayed in the views and templates.

#### Supported Media
The list of supported media includes renowned international publications:

- Washington Post (USA)
- Sydney Morning Herald (Australia)
- CNN (USA)
- Le Temps (Switzerland)
- The Week Pictures (USA)
- Guardian (UK)
- Atlantic (USA)
- Spiegel (Germany)
- Die Welt (Germany)

These publications source images from **major international news agencies**, including:

- Associated Press (AP)
- Reuters
- Agence France-Presse (AFP)
- Getty Images
- European Pressphoto Agency (EPA)

See on [Github](https://github.com/hericlibong/worldPressPhotoGalery)
<a href="https://github.com/hericlibong/worldPressPhotoGalery">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Repository" width="50" height="50"/>
</a>
