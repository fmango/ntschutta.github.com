---
layout: page
title: Nathaniel T. Schutta
tagline: Author, speaker, teacher
---
{% include JB/setup %}
Welcome to my little corner of the Internet! If you didn't find this
site by accident, odds are you've seen me speak at [No Fluff Just
Stuff](http://www.nofluffjuststuff.com/home/main), a user group
meeting or one of the several conferences I've been lucky enough to
speak at! Want to know more about me? Check out my
[biography](about.html). Curious about my presentation style? You
can learn all about it at [Presentation Patterns](http://presentationpatterns.com).
    
## Upcoming Talks:

[Software Architect](http://www.software-architect.co.uk)  
London, UK  
16-19 October 2012  
* [The who and what of Agile – personas and story maps](/slides/Agile_who_what_handouts.pdf)
* [HTML5 for developers](/slides/HTML5_Developers_handouts.pdf)
* [Beyond jQuery](/slides/Beyond_jQuery_handouts.pdf)
* [The mobile app smackdown: native apps vs. the mobile web](/slides/mobile_apps_vs_web_handouts.pdf)

<a href="http://www.nofluffjuststuff.com"> 
<img src="http://www.nofluffjuststuff.com/images/nfjs_logo200.gif" alt="No Fluff Just Stuff"/> </a>
[Twin Cities Software
Symposium](http://www.nofluffjuststuff.com/conference/minneapolis/2012/10/home)  
Minneapolis, MN  
26-28 October 2012  
* [HTML5](/slides/HTML5_handouts.pdf)
* [Designing for Mobile](/slides/designing_for_mobile_handouts.pdf)
* [The mobile app smackdown: native apps vs. the mobile web](/slides/mobile_apps_vs_web_handouts.pdf)
* [JavaScript Libraries You Aren't Using...Yet](/slides/js_libraries_survey_handouts.pdf)
* [Leading Technical Change](/slides/Leading_Change_handouts.pdf)
* [Hacking Your Brain for Fun and Profit](/slides/Hacking_Your_Brain_handouts.pdf)

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
