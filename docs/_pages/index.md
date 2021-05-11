---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single

author:
  name: "Marc Faddoul"
  avatar: "/assets/images/potluck.jpg"
  bio: "AI researcher, trying to make technology more socially aware."
  location: "France"
  links:
    - label: "Berkeley Home"
      icon: "fas fa-fw fa-link"
      url: "https://www.ischool.berkeley.edu/people/marc-faddoul/"
    - label: "Twitter"
      icon: "fab fa-fw fa-twitter-square"
      url: "https://twitter.com/MarcFaddoul"
    - label: "Linkedin"
      icon: "fab fa-fw fa-linkedin"
      url: "https://www.linkedin.com/in/marc-faddoul/"

# Add links to section titles (see header bar in _data/navigation.yml)
breadcrumbs: true

sidebar:
  - title: "Education"
    text: "School of Information, UC Berkeley<br><br>
           Telecom Paris, Institut Polytechnique de Paris"

classes:
  - wide
  - landing
  - dark-theme

#excerpt: "Hi. This is Marc."
#header:
# image: /assets/images/swarm-intel.jpeg
# overlay_color: "#333"
# overlay_filter: 0.5
# show_overlay_excerpt: true
 
 
feature_row:
  - image_path: /assets/images/lemonde.jpeg
    alt: "placeholder image 2"
    title: "Le Monde"
    excerpt: "Interview with Marc Faddoul on YouTube's new content moderation policy."
    url: "https://www.lemonde.fr/pixels/article/2020/03/06/videos-complotistes-youtube-a-la-capacite-de-moderer-son-contenu-lorsqu-il-en-a-la-volonte-politique_6032050_4408996.html"
    btn_label: "Read More"
    btn_class: "btn--inverse"
    
  - image_path: /assets/images/brookings-covid.jpeg
    alt: "placeholder image 2"
    title: "Brookings Institution"
    excerpt: "COVID-19 is triggering a massive experiment in algorithmic content moderation. *by Marc Faddoul*"
    url: "https://www.brookings.edu/techstream/covid-19-is-triggering-a-massive-experiment-in-algorithmic-content-moderation/"
    btn_label: "Read More"
    btn_class: "btn--inverse"

  - image_path: /assets/images/algorithmic-humility.jpeg
    alt: "placeholder image 2"
    title: "O'Reilly Media"
    excerpt: "*Toward Algorithmic Humility* an essay by Marc Faddoul on the design of algorithmic sentencing tools and their alarming false positive rates."
    url: "https://www.oreilly.com/library/view/97-things-about/9781492072652/ch70.html#toward_algorithmic_humility"
    btn_label: "Read More"
    btn_class: "btn--inverse"

---
<!---
 TODO have url open in new tab (new button class)
 TODO add newspaper logo
 TODO open links in new tabs
    https://rubygems.org/gems/jekyll-target-blank
    https://stackoverflow.com/questions/45003852/how-to-open-urls-in-new-tab-in-config-yml-of-jekyll-github-pages-site

 TODO make the masterhead sticky
--->

I am a transdisciplinary researcher and technologist. 

I have carried research in academia (UC Berkeley), big tech (Facebook AI) and start-up environments (Bloom, Jalgos).

I went from building algorithms to analysing how they impact our society. Nowdays, I focus on tracking and exposing algorithmic biases.

[Below](index.html#in-the-news) is a selection of my works that have been featured in the media, 
including the New York Times, O'Reilly, the Brookings Institute...

# Research & Projects

- [Tracking.Exposed](http://tracking.exposed){:target="_blank"}: Monitoring the algorithms of YouTube, Facebook, Amazon and PornHub.
- Visiting Researcher, [Human Rights Center](https://humanrights.berkeley.edu), UC Berkeley
- Affiliated Scholar, [Tech Policy Lab](https://citrispolicylab.org/), CITRIS and Banatao Institute
- [Algorithmic Fairness and Opacity research group](https://afog.berkeley.edu/), School of Information, UC Berkeley

## Former Projects

**An analysis of YouTube's promotion of conspiratorial content** <br>
Lead author of an [audit](https://arxiv.org/abs/2003.03318) of YouTube's recommendation engine. 
The study was published with [the New York Times](https://www.nytimes.com/interactive/2020/03/02/technology/youtube-conspiracy-theory.html), 
and was [cited](https://malinowski.house.gov/sites/malinowski.house.gov/files/Letter%20to%20YouTube%20--%20Malinowski_Eshoo_final_0.pdf) by US Congress in a formal letter to the CEO's of Google and YouTube. 
Interviews featured in [le Monde](https://www.lemonde.fr/pixels/article/2020/03/06/videos-complotistes-youtube-a-la-capacite-de-moderer-son-contenu-lorsqu-il-en-a-la-volonte-politique_6032050_4408996.html) 
and the [BBC](https://www.bbc.co.uk/sounds/play/w3csymts).<br>
The analysis relied on a monitoring infrastructure paired with a machine learning classifier to detect conspiratorial content.

**Uncovering physiognomic filter-bubbles on TikTok**
An experiment which showed how race and appearance impact recommendability on TikTok. 
Featured in [BuzzFeed](https://www.buzzfeednews.com/article/laurenstrapagiel/tiktok-algorithim-racial-bias), 
[Vox](https://www.vox.com/recode/2020/2/25/21152585/tiktok-recommendations-profile-look-alike), 
[Wired UK](https://www.wired.co.uk/article/tiktok-filter-bubbles), 
[Forbes](https://www.forbes.com/sites/janicegassam/2020/04/14/does-tiktok-have-a-race-problem/#236b246a3260)... 

**AlgoTransparency**
[AlgoTransparency](https://algotransparency.org/) is aimed at monitoring the channels most promoted by YouTube's recommendation engine to logged-out users.

**Investigating Sniper Ad Targeting**
A [master thesis](http://www.ischool.berkeley.edu/projects/2019/sniper-ad-targeting) project investigating whether and how an malign ads can be tailored and sent to a single individual. 
Advised by Professor [Deirdre Mulligan](https://www.ischool.berkeley.edu/people/deirdre-mulligan). Introductory video [here](https://www.youtube.com/watch?v=bKdFlBHqhjI).

**Auditing a Judicial Algorithm**
In depth-analysis of a Pretrial Risk-Assessment Tool used in the U.S to determine whether a defendant should be placed in detention before their trial. Research [presented](https://cssh.northeastern.edu/philosophy/our-recent-past-talks/) at the Information Ethics Roundtable at Northeastern University.

**Cybersecurity Consulting**
Consulting within the [Citizen Clinic](https://cltc.berkeley.edu/about-us/citizen-clinic/) for a civil-rights NGO from central-America, to help them defend against cyber-threats and state-surveillance. 

# Professional Experience

**Associate Researcher - [UC Berkeley](https://www.ischool.berkeley.edu/)** (2019-2020): Development of novel algorithmic approaches to detect disinformation and borderline content, with Professor [Hany Farid](https://en.wikipedia.org/wiki/Hany_Farid).

**Research Scientist - [Facebook AI](https://ai.facebook.com)** (2020): Research collaboration with UC Berkeley to improve disinformation classification algorithms.

**Algorithm Designer - [Bloom](https://bloomsocialanalytics.com/EN/)** (2018): Design an influence ranking model for social media posts.

**Algorithm Designer - [Jalgos](https://jalgos.com/)** (2016): Design and Implementation of data-intensive algorithmic solutions for Fortune 500 companies.

**Freelance Developer** (2013-17): Several projects, involving discrete optimisation, resource allocation and web semantics.

# Talks & Lectures

**Université Paris 2 Panthéon-Assas** - Dec 2020: Guest Lecturer, [Primavera de Philippi](https://en.wikipedia.org/wiki/Primavera_De_Filippi)'s class Digital Administrations.

**US CyberCommand** - July 2020: Recommender Systems and Power Dynamics
1h30 lecture for members of the State Deparetement and US Cyber Command, in a series hosted by [Clint Watts](https://en.wikipedia.org/wiki/Clint_Watts).

**UC Berkeley** - [GEESE](https://geesegraduates.org/about/) Panel: The Role and Impact of Auditing Algorithms

**UC Berkeley** - Fall 2019: Guest Lecturer, [Steve Weber](https://en.wikipedia.org/wiki/Steven_Weber_(professor))'s Applied Behavioral Economics

**Northeastern University** - Spring 2019: [Information Ethics Roundtable](https://cssh.northeastern.edu/philosophy/our-recent-past-talks/), paper presentation.

# Education

**[UC Berkeley School of Information](https://www.ischool.berkeley.edu/) - Master of Science**<br>
Transdisciplinary perspectives on societal, legal and ethical impacts of technology on society. (MIMS program)

**[Télécom Paris](https://www.telecom-paris.fr/en/home) - Diplome d'Ingénieur**<br>
Télécom is France's top Computer Science school. The engineering degree (undergrad + MS) captures a broad technical understanding of computational systems and networks.
Double-degree MS in Data Science at [Eurecom](https://www.eurecom.fr/).

# In the news

{% include feature_row %}