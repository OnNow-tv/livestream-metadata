# Livestream Metadata

**OnNow.tv, leader in livestream aggregation, announces V1 of livestreaming metadata standards**

The pandemic catapulted livestreaming from niche medium to essential resource. Viewers of all ages and backgrounds found an exciting new resource for entertainment and information. Talented creators leaped into a new way to engage fans and keep doing the things they love, from teaching meditation to spinnin’ records. However, the majority of consumers have difficulty discovering livestream programming.

Livestreaming has seen meteoric growth in the first half of 2020. [Twitch](https://www.twitch.tv/), the longstanding livestreaming hub with significant market share,​ shattered total hours watched records in Q2 ​of 2020, growing by 83% YoY and totaling up more than 5 billion hours watched since the beginning of 2018. The platform boasted more than ​7.7 million unique active channels​ in August 2020. Other established livestreaming options such as [Facebook](https://www.facebook.com/) and [YouTube](https://www.youtube.com/) reported similarly skyrocketing watch hours. This boost impacted livestreams of all kinds, including in categories like ​food & drink​ and music. As concert livestreams become more frequent, the appetite for paying for a livestreamed event is also growing: [Bandsintown](https://www.bandsintown.com/)’s​ August 2020 survey of several thousand live music fans indicated 80% of them were willing to pay for a show by their favorite artist, up from a mere 10% in April 2020.

Amid all this promise, however, the livestreaming ecosystem remains fragmented, scattered across social media and livestreaming-specific platforms, and hard to navigate for creators and fans alike. There is no single system for categorizing this fast-evolving medium. Consumer research revealed that only ​12% of streaming video viewers​ found it easy to discover the kind of content that interested them on streaming platforms.

As livestreaming catches on among creators and viewers, it needs this important groundwork now, rather than a patchwork system that stakeholders are forced to fix later.The lack of livestream metadata standards will impede market growth by contributing to further fragmentation and undermining discoverability.

[OnNow.tv](https://www.onnow.tv/) is proposing new livestream metadata standards that will make data about livestreams more consistent, distributable, useful, and valuable to fans and creators. Metadata, the descriptive information included with audiovisual files, include basics, such as the creator name and title of a livestream, as well as broadcast details and tags and categories. Metadata standards allow media to be presented to more people across more online destinations with greater efficiency. As monetization of livestreams expands, metadata may play a crucial role in protecting creators’ rights and increasing revenue opportunities.

For creators, clear metadata standards would reduce time spent describing and classifying their content. Simple, easy to understand fields would replace the repetitive platform-specific data entry they are currently required to complete. This simplicity will help media move across platforms as needed or desired, and potential viewers will have an easier time finding and supporting creators’ efforts.

For the livestream industry, metadata can increase efficiency and reduce friction in data distribution. As data becomes more widely available and easily interpretable, platforms and services will find everything from ad sales to viewer growth initiatives scale far more easily with accurate, universal metadata. Like the barcode did for retail, warehousing, and logistics, metadata standards can transform livestream businesses and benefit all stakeholders.

**A Call for Industry Collaboration**

OnNow.tv is establishing a consortium to refine and implement new and evolving livestreaming metadata standards. These standards would apply to all simultaneously broadcast video and audio streams.

To start the process, OnNow.tv has drawn up a first version for a metadata standard to build a better livestream ecosystem. OnNow.tv’s team has laid out some of the basics​ ​below. The goal: To develop an agreed-upon standard and corresponding style guide.

[StageIt](https://www.stageit.com/) and [Tixr](https://www.tixr.com/) are joining OnNow.tv as initial partners in this effort. All other stakeholders in the livestreaming world are invited to join the consortium and contribute to the development of a better infrastructure for the industry by emailing ​[metadata@onnow.tv](mailto:metadata@onnow.tv)​ to become part of the upcoming consortium.

> “OnNow.tv​ was an early mover in this space and they are once again ahead of the pack with establishing universal metadata so all players in livestreaming can work collaboratively on growing the industry as a whole.”
> 
> Karen Allen, the author of ​[Twitch for Musicians](https://www.amazon.com/Twitch-Musicians-Step-Step-Livestream-ebook/dp/B07WKLVHRZ)​

In addition, the OnNow.tv team thinks developers have an important role to play in improving and using livestream metadata. ​OnNow.tv​ encourages the community to contribute to this project and will be hosting their standard on ​**Github** (​[https://github.com/OnNow-tv/livestream-data/​](https://github.com/OnNow-tv/livestream-metadata/)) to track changes and gather feedback from the developer community as they proceed towards the official release of the standard.

“We are not a streaming platform or service, but an online guide to help viewers find and tune into livestreams that matter to them,” explains [Matthew Adell](https://www.onnow.tv/about/), CEO and co-founder of OnNow.tv. “Because of the nature of our work we have had to untangle the varied metadata definitions and we see how improving metadata as an industry will benefit everyone. We see firsthand how a metadata standard, one that looks ahead to the thriving future of this medium, will increase the business value and creative energy of livestreaming across the board.”

“The phenomenal growth of digital music in a machine-readable world was accelerated by the adoption of metadata standards, in other words who created what song,” notes Vickie Nauman, founder of [CrossBorderWorks](https://www.crossborderworks.com/) and expert in rights/metadata​. “Our new livestreaming market also needs consistency in how we identify events and I thoroughly support ​OnNow.tv​ as it leads the way with their proposed livestreaming metadata standards.”

“As popular as livestreaming is, one of the biggest challenges for creators is promoting their stream beyond their followers. Music streamers in particular are experimenting across many platforms at once, which makes having a centralized listing of upcoming streams like ​OnNow.tv a treasured resource,” say Karen Allen, the author of ​[Twitch for Musicians](https://www.amazon.com/Twitch-Musicians-Step-Step-Livestream-ebook/dp/B07WKLVHRZ)​ and recognized livestreaming expert. “OnNow.tv​ was an early mover in this space and they are once again ahead of the pack with establishing universal metadata so all players in livestreaming can work collaboratively on growing the industry as a whole.”

**Quick Introduction to the Livestream Metadata Standards**

The livestream metadata standards includes specifically defined fields for basic information about the livestream (date, language, title) and the creators, performers, and/or hosts. There are also fields related to event type (if the livestream is also a physical event), ticketing, broadcast type, and cadence (if the livestream is part of a series or recurring stream). These data fields will guide creators and help viewers discover livestreams. They will help platforms organize and present livestreams in a more broadly readable format.

For a full list of fields included in V1 of the livestream metadata standard, please see ​this table​:

|Name                            |Type               |Definition                                                                     |Recomendations                                     |Required or optional|Example                                                                                                                                                                                                                             |
|--------------------------------|-------------------|-------------------------------------------------------------------------------|---------------------------------------------------|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|EventID                         |Text               |Unique text identifier for livestream                                          |Do not use the same ID for more than one livestream|Required            |id12345                                                                                                                                                                                                                             |
|Start Date                      |Date (ISO Standard)|The calendar day livestream starts                                             |                                                   |Required            |09/20/2020                                                                                                                                                                                                                          |
|Start Time                      |Time (ISO Standard)|The time of day the livestream starts in it’s originating timezone             |                                                   |Required            |10:00                                                                                                                                                                                                                               |
|End Date                        |Date (ISO Standard)|The calendar day livestream ends                                               |                                                   |Required            |09/20/2020                                                                                                                                                                                                                          |
|End Time                        |Time (ISO Standard)|The time of day the livestream ends in it’s originating timezone               |                                                   |Optional            |14:00                                                                                                                                                                                                                               |
|Original Time Zone              |Time (ISO Standard)|The timezone in which the livestream originates                                |                                                   |Required            |PST                                                                                                                                                                                                                                 |
|Title                           |Text               |The title of the livestream to be displayed to users                           |Use 50 characters or fewer to avoid elipses        |Required            |Live Nation presents Bosa and friends                                                                                                                                                                                               |
|Description                     |Text               |The description of the livestream to be displayed to users                     |Use 500 characters or fewer to avoid elipses       |Required            |Live Nation presents a night of excitement and live music for up to 40 attendies or right to your home from the comedy store in Los Angeles. This is a once in a lifetime event with amazing performers streamed right to your home.|
|Image                           |16×9 jpeg          |The image that will be associated with the livestream                          |HD or 4k is optimal                                |Required            |                                                                                                                                                                                                                                    |
|Host/Organizer/Producer         |Text               |The name of the Host, Organizer or Producer (Proper names, last name first)    |If a proper name, last name first                  |Required            |Live Nation                                                                                                                                                                                                                         |
|Headliner                       |Text               |The name of the top billed performer                                           |If a proper name, last name first                  |Optional            |BOSA                                                                                                                                                                                                                                |
|Performers                      |Text               |The name(s) of the secondary performers (Separate multiple entires with commas)|If a proper name, last name first                  |Optional            |Diplo, Skrillex, Beats Antique                                                                                                                                                                                                      |
|Is Free                         |Boolean (Y or N)   |Notification as to if the livestream is free                                   |                                                   |Required            |Y                                                                                                                                                                                                                                   |
|Is Registration Required        |Boolean (Y or N)   |Notification as to if the livestream requires advance registration             |                                                   |Optional            |N                                                                                                                                                                                                                                   |
|Ticket Link                     |URL                |URL for page to purchase tickets                                               |                                                   |Optional            |https://www.tixr.com/groups/xs/events/wynn-las-vegas-diplo-livestream-19814                                                                                                                                                         |
|View Livestream Link(s)         |URL (s)            |URL(s) for livestream broadcast (separate multiple entries with commas)        |                                                   |Required            |https://www.twitch.tv/producerssocial                                                                                                                                                                                               |
|Category                        |Text               |Hierarchical list of content descriptors                                       |Use 40 characters or fewer to avoid elipses        |Required            |Music                                                                                                                                                                                                                               |
|Tags                            |Text               |Non-hierarchical list of single word content descriptors                       |Use 25 characters or fewer to avoid elipses        |Optional            |Festival, show                                                                                                                                                                                                                      |
|Is Recurring                    |Boolean (Y or N)   |Notification that the liveastream is recurring                                 |                                                   |Optional            |Y                                                                                                                                                                                                                                   |
|Publish Date                    |Date               |Date Metadata is available to public                                           |                                                   |Optional            |09/20/2020                                                                                                                                                                                                                          |
|Venue Name                      |Text               |The name of the location or venue for the livestream                           |Use 40 characters or fewer to avoid elipses        |Optional            |The Comedy Store                                                                                                                                                                                                                    |
|Sales or Registration Start Date|Date (ISO Standard)|Date tickets or registration become available                                  |                                                   |Optional            |09/20/2020                                                                                                                                                                                                                          |
|Is Sold Out                     |Boolean (Y or N)   |Notification that tickets are sold out                                         |                                                   |Optional            |N                                                                                                                                                                                                                                   |
|Is Cancelled                    |Boolean (Y or N)   |Notification that livestream is cancelled                                      |                                                   |Optional            |N                                                                                                                                                                                                                                   |
|Is a Live Broadcast             |Boolean (Y or N)   |Notification that the content of the livestream is a live broadcast            |                                                   |Optional            |Y                                                                                                                                                                                                                                   |
|Language                        |Text               |Primary language of the livestream                                             |                                                   |Optional            |English                                                                                                                                                                                                                             |
|Registration Link               |URL                |URL for page to register                                                       |                                                   |Optional            |https://www.tixr.com/groups/xs/events/wynn-las-vegas-diplo-livestream-19814                                                                                                                                                         |
|Recurring Schedule              |RFC 2445 Standard  |Schedule for upcoming episodes                                                 |                                                   |Optional            |                                                                                                                                                                                                                                    |
|Sponsor                         |Text               |Displays sponsor name                                                          |Use 40 characters or fewer to avoid ellipsis       |Optional            |OnNow.tv                                                                                                                                                                                                                            |
|Is All Day                      |Boolean (Y or N)   |Notification that livestream is 24 hour                                        |                                                   |Required            |N                                                                                                                                                                                                                                   |
|Is Physical Event               |Boolean (Y or N)   |Notification that event also has physical attendance                           |                                                   |Optional            |Y                                                                                                                                                                                                                                   |

