# jupiter

An open source Learning Record Store (LRS) supporting the xAPI and Caliper specifications

## Background

The new Caliper APIs for defining and storing learning activities are scheduled for a 2015 delivery. This is a specification being developed by the [IMS](http://www.imsglobal.org/) who have a proven history of working with some of the largest educational entities to develop interoperability standards that tend to carry a lot of weight in the industry.

In some ways the Caliper API is a more formalized approach to defining a granular learning activity specifically for the education sector. The goals of the effort are laid out in the [Caliper Analytics](http://www.imsglobal.org/caliper/index.html) web page:

* establish a means for consistently capturing and presenting measures of learning activity, which will enable more efficient development of learning analytics features in learning environments
* define a common language for labeling learning data, which will set the stage for an ecosystem of higher-order applications of learning analytics
* provide a standard way of measuring learning activities and effectiveness, which will enable designers and providers of curriculum to measure, compare and improve quality
* leverage data science methods, standards and technologies build upon existing IMS standards

We see the introduction of the new Caliper API as a great time to bring new technology to bear on the problem of storing, querying and reporting on the vast amounts of data generated by learning interactions.

## The Current Landscape

* [Learning Locker](http://learninglocker.net/)   One of the first open source Learning Record Store (LRS) for the Experience API.
* [Scorm Cloud](http://scorm.com/scorm-solved/scorm-cloud-features/) and [Scorm Engine](http://scorm.com/scorm-solved/scorm-engine/) are SCORM and Tin Can API compliant LRS's developed by Rustici. The commercial company behind both the SCORM standard and Experience API (aka Tin Can API).
* [WaxLRS](http://www.saltbox.com/home.html)  A nice LRS platform offered as a pay-as-you-go service and a nice set of analytics. 
* [Watershed LRS](http://site.watershedlrs.com/)  Another commercial LRS that seems to be focused on corporate training.

There are no known implementations of a record store implementing the Caliper API. It is assumed that the IMS may sponsor or develop their own reference implementation when the specification is released. Of course, we submit Jupiter for their consideration.
                                                 
## About Jupiter

Jupiter is the next generation, open source, learning record store. We are pushing the bounds of today's technology to build a highly scalable, fault-tolerant, cloud-based repository capable of ingesting both Caliper API and Experience API payloads.

### Metis

Included with Jupiter is Metis, an open source UI-based query tool and metrics dashboard. Metis gives users an extensive query builder so even the most novice users can quickly and easily craft queries to drive reporting. All of the queries generated by Metis are automatically integrated into data visualizations and tabular data views, as well as immediate export into a variety of formats for external consumption.

Metis also provides active monitoring, so users can instantly see the health of their cluster and receive notification messages when resources are compromised by network or hardware failures.

## About Jove

Transcordia is making use of Jupiter in its hosted LRS offering. Jove unleashes the full scalability of Jupiter using the Amazon Web Services platform. Jove is capable of handling tens of thousands of learning events per second using the latest in petabyte-scale auto-clustering technologies. This hosted environment is free for those organizations  storing up to 1M events per year. After that limit, prices are only $1 for each 10,000 events per month.

## About Transcordia

Transcordia is comprised of individuals who have decades of experience building enterprise-scale big data (did I just say "big-data"?) repositories in a variety of verticals. For the past several years, we have been involved in the educational space and wish to bring our talents to bear to improve the scalability, performance, query-ability, and visualization of learning record stores.

We hope that by initiating this endeavor in an open source manner and developing a system that exceeds the capabilities of today's commercial offerings, we can encourage participation from educational institutions, research organizations, and anyone else willing to support our efforts through evangelism, financial support, or most welcome, coding and pull-requests.
