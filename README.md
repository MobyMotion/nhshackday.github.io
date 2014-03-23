# nhshackday.github.io


The new NHSHackday website


## Adding events

To add an event you should create a new file in the _posts/events/ folder with a filename like: ```YYYY-MM-DD-LOCATION.md```

The following page-matter should be at the top of the file between the  ```---```.

```YAML
layout: event
permalink: /previous/events/2014/01/cardiff
title:  "Cardiff"
summary: "Held at the Hadyn Ellis Building in Cathays, Cardiff and organised by Dr Anne-Marie Cunningham."
date:   2014-01-25 00:00:00
date_range:
    - 2014-01-25 00:00:00
    - 2014-01-26 00:00:00
categories: events
label: 2014
blog-posts:
    - BCon.cc at NHSHackday : http://www.webdevbros.net/2014/02/20/cardiff-nhs-hack-day-or-weekend-and-bcon-cc/
    - NHS Hack Day : http://blogs.cardiff.ac.uk/development/2014/01/26/nhs-hack-day/
```

## Adding projects

To add an event you should create a new file in the _posts/projects/ folder with a filename like: ```YYYY-MM-DD-PROJECTNAME.md```

The following page-matter should be at the top of the file between the ```---```

```YAML
---
layout: post
title:  "iPatch"
summary: "iPatch is an application for tracking the treatment of lazy eyes in children and adults. iPatch is a project from NHS HackDay Cambridge, November 2013."
date:   2014-02-01 17:33:13
categories: projects
logo: ipatch.png
logo-with-name: true
website: http://ipatch.azurewebsites.net/
---
```


## Adding sponsors