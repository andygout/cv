## Andy Gout

![Andy Gout](https://avatars0.githubusercontent.com/u/10484515?v=3&s=128)

Formerly in talent management and found there wasn't enough time in the day to code whilst holding down a full-time job, so decided to create that time by becoming a web developer. Self-taught by building a database-driven site that lists theatre production and playtext details, a gap that remains in the market and a side project I will rebuild using best practices honed from my time at Makers Academy.

Presently I'm looking to begin my new career in an environment with equally passionate individuals where I can continue to learn fast amongst a team so as to return value quickly. I'm a Ruby convert (having started out with PHP) and am a nut for relational databases.


## Skills

#### Relational databases

Fully confident in creating schema required for a given set of relationships and employing those with SQL; learned through the building of [TheatreBase](https://github.com/andygout/theatrebase_php) (prior to Makers Academy):

- Each theatrical production lists its most specific location setting, escalating to broader locations (i.e. Shoreditch -> London -> England -> Europe); therein I encountered the problem of a location being the setting within a pre-existing place (i.e. the Hagia Irene in Constantinople rather than Istanbul) and solved it by creating an additional table to inform the selection process ([first approach to problem on Stack Overflow](http://stackoverflow.com/questions/21658272/create-loop-within-sql-select-statement-until-chain-broken))
- Awards listings required deep multidimensional arrays and the correct schema to support it, i.e. the Laurence Olivier Awards contain many ceremonies (2014, 2015...), which contain many categories (Best Actor, Best New Play...), which contain many nominations, each of which contains (potentially multiple) productions, playtexts, people or companies (which could in turn contain yet more people)
- My current favourite SQL command: `COALESCE` ([Sitepoint discussion](http://community.sitepoint.com/t/sql-update-using-case-when-with-php-variable-as-argument/114817/8))


#### Team Player

- Originated idea chosen after successful pitch for two week final project at Makers Academy: [Movie Snaps](https://github.com/andygout/Movie-Snaps), a web app that allows users to upload photos of themselves at locations where movie scenes were shot (ideally re-enacting a scene), hooking up to GoogleMaps and OMDb APIs and utilising Amazon Web Services for image file storage ([live demo hosted on Heroku](https://movie-snaps.herokuapp.com/))
- Worked with an Agile methodology to ensure all team members were across the entire codebase with discussions of improvements consistently during process (resulting in, at my suggestion, an overhaul of the routing to make more RESTful)
- Invaluable experience dealing with a multi-branched GitHub repo and merge conflicts
- Proud of two lines of ActiveRecord (Rails' ORM) code which obviated the need for a lengthy Ruby method that had been written: `has_many :visits , :through => :scenes` (in model); and
 `@list = Movie.joins(:visits).group(:name).count` (in controller)


#### Ruby with PostgreSQL database
- [Chitter](https://github.com/andygout/chitter-challenge), a Twitter clone built using Ruby on a Sinatra server with a PostgreSQL database
- Successful implementation of password encryption and reset functionality utilising Mailgun API to email recovery token to user
- Employed DataMapper ORM which taught me the concept of dirty resources


#### JavaScript

- [Bowling scorecard app](https://github.com/andygout/bowling-challenge), built entirely in JavaScript and tested with Jasmine, to handle logic of a bowling game, including the fiendishly anomalous final frame
- Spruced up with some swanky jQuery
- Live demo hosted on [Heroku](https://dry-harbor-7560.herokuapp.com/)


#### Language enthusiast (not *only* code)

- Ongoing learning of Japanese, Mandarin and Cantonese, through instructional books/audio and regular language community meet-ups - とても たのしい です!


#### Miscellaneous

- Can do a mean Christopher Walken impression on request


## Education

#### [Makers Academy](http://beta.makersacademy.com/) (Apr to Jul 2015)

- Experience aplenty of buddying-up and coding solo
- Emphasis on being a self-starting learner
- Taught best practice of key principles (especially those expressed as an acronym): OOP, TDD, BDD, DDD, SOLID, MVC
- Ruby, Rails, JavaScript, jQuery, AngularJS
- RSpec, Capybara, Cucumber, Jasmine, Karma, Protractor
- Agile approach; pair programming; group projects
- Subsequently an alumni helper: first contact for current students encountering problems; chosen for technical prowess, communication skills and approachability demonstrated during course


#### Autodidacticism (ongoing)

- PHP; SQL with MySQL database: used to build TheatreBase, which I'll be rebuilding in Ruby on Rails, fully tested and cleaner


#### Royal Holloway, University of London (Sep 2001 to Jun 2004)

- 2:1 BA (Hons) in Drama and Theatre Studies


#### Moulsham High School (Sep 1994 to Jun 2001)

- A Levels: English (A); Drama (A); and Art (B)
- GCSEs: 9 x A grades; 1 x B grade


## Employment

#### United Agents (Nov 2009 to Apr 2015)
*Literary Management*

- Professional representation of playwrights; TV and screenwriters; theatre directors and designers
- Negotiation of copyright licences; commissioning agreements; artist contracts
- Understanding and application of worldwide copyright laws


#### Independent Talent Group (Nov 2004 to Mar 2009)
*Actor Management (Assistant to Managing Director)*

- Representation of internationally recognised performers (including knights, dames and Oscar winners)
- Contract negotiation and complex schedule management
- Accompanying clients and professionals to industry events


## Links

- [Stack Overflow](http://stackoverflow.com/users/1780767/andy-gout)
- [Sitepoint Forums](http://community.sitepoint.com/users/andygout/activity)
- [Codewars](http://www.codewars.com/users/andygout)