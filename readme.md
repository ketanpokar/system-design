## System Design Basics
* Key Characteristics and Fundamentals of Distributed Systems
* Monolithic VS Microservice (Service Discovery, Resiliency)
* Vertical vs horizontal scaling [Watch1](https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=2)
* Load Balancing / Application Delivery Controller (ADC) [Read1](https://www.citrix.com/en-in/solutions/app-delivery-and-security/load-balancing/what-is-load-balancing.html#:~:text=Load%20balancing%20is%20a%20core,responsiveness%20and%20prevent%20server%20overload.) [Read2](https://logz.io/blog/best-open-source-load-balancers/) [Watch1](https://www.youtube.com/watch?v=K0Ta65OqQkY&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=3)
* Consistent Hashing [Watch1](https://www.youtube.com/watch?v=zaRkONvyGr8&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=4) [Read1](https://medium.com/system-design-blog/consistent-hashing-b9134c8a9062) [Read2](https://www.toptal.com/big-data/consistent-hashing) [Read3](https://en.wikipedia.org/wiki/Consistent_hashing)
* Throughput, Latency
* CAP theorem
* ACID vs BASE
* Redundancy and Replication
* Partitioning/Sharding 
* Optimistic vs pessimistic locking
* Strong vs eventual consistency
* SQL vs NoSQL
* Types of NoSQL (Key value, Wide column, Document-based, Graph-based)
* Caching
* Data center/racks/hosts
* CPU/memory/Hard drives/Network bandwidth
* Random vs sequential read/writes to disk
* DNS lookup
* HTTP, HTTPS, HTTP2
  * HTTP
  * HTTPS [Read1](https://www.thesslstore.com/blog/how-does-https-work/)
  * HTTP & SSL/TLS
  * Public key infrastructure and certificate authority(CA)
  * Symmetric vs asymmetric encryption
* WebSockets
* Long-Polling vs WebSockets vs Server-Sent Events
* TCP/IP model
* IPv4 vs IPv6
* TCP vs UDP
* Consistent Hashing
* CDNs & Edges
* Data Partitioning
* Indexes
* Master-Slave, Master-Master
* Active-Passive, Active-Active
* Leader election
* Design patterns and Object-oriented design
* Virtual machines and containers
* Pub-sub architecture 
* REST, GraphQL
* MapReduce
* Bloom filters and Count-Min sketch
* Paxos 
* Multithreading, locks, synchronization, CAS(compare and set)
* Proxies

## Building Blocks of Any Frequently Asked System Design Question
* Authentication
  * JWT
  * OAUTH2 
* File / Media Upload
  * S3, Multiple Quality Files
  *   
* WIP...


## Tools and Technologies
* Databases [Comparison](https://db-engines.com/en/system/InfluxDB%3BMicrosoft+Azure+Cosmos+DB%3BTimescaleDB)
* Cassandra
* MongoDB/Couchbase 
  * Mongo: [Read1](https://www.tutorialspoint.com/mongodb/mongodb_overview.htm), [Read2](https://docs.mongodb.com/manual/tutorial/getting-started/), [Read3](https://www.dotnettricks.com/learn/mongodb/what-is-mongodb-and-why-to-use-it), [Read4](https://studio3t.com/knowledge-base/articles/mongodb-advantages-use-cases/), [Read5](https://www.objectrocket.com/blog/mongodb/top-use-cases-for-mongodb/), [Read6](https://docs.mongodb.com/manual/core/replica-set-elections/), [IQ's](https://www.interviewbit.com/mongodb-interview-questions/)
* RabbitMQ / Kafka / Pub-Sub [comparison](https://www.cloudamqp.com/blog/when-to-use-rabbitmq-or-apache-kafka.html) [Comparison](https://engineering.3ap.ch/post/rabbitmq-vs-pubsub-part-1/)
  * RabbitMQ: [Watch1](https://www.youtube.com/watch?v=deG25y_r6OY), [Watch2](https://www.youtube.com/watch?v=WmBwTtE5PTQ) 
  * Google PubSub: [Watch Playlist](https://www.youtube.com/watch?v=cvu53CnZmGI&list=PLIivdWyY5sqKwVLe4BLJ-vlh9r9zCdOse)
* Mysql / PostgreSQL
  * Scalability in Postgres 
* Redis / Memcached
* InfluxDB [Suitable for TimeSeries, IoT data]
* Zookeeper
* NGINX
* HAProxy
* Solr, Elastic search
* Amazon, EC2, S3
* Docker, Kubernetes
* Hadoop/Spark and HDFS
* Eureka, Hysterix
* Heroku / Azure DevOps
* Jenkins CI/CD
    
## System Design Problems (HLD + LLD)
* TinyURL
* Instagram | Photo hosting platform
* Timeline | Newsfeed | Twitter
* Dropbox | Google Drive
* Whatsapp | Facebook Messenger [NL](https://www.youtube.com/watch?v=L7LtmfFYjc4&t=690s) [GS](https://www.youtube.com/watch?v=vvhC64hQZMk&t=1267s) [Ref](https://medium.com/@thinkwik/web-sockets-vs-xmpp-which-is-better-for-chat-application-113e3520b327)
* MakeMyTrip | BookMyShow
* Amazon | Flipkart
* Youtube | Netflix [NL](https://medium.com/@narengowda/netflix-system-design-dbec30fede8d)
* Uber | IRCTC
* Swiggy | Zomato
* Yelp | Nearby
* Twitter Search
* Google Search
* SplitWise
* Zerodha
* API Rate Limiter
* Web Crawler
* Rate limiting system 
* Distributed cache 
* Typeahead Suggestion | Auto-complete system
* Recommendation System
* Design a tagging system like tags used in LinkedIn

## Low Level Design Problems (Machine Coding Round) [Reference](https://www.linkedin.com/pulse/cracking-he-low-level-design-lld-interview-shashi-bhushan-kumar/)
* Elevator system 
* Snake and Ladder game
* Tic Tac Toe
* ATM machine - https://medium.com/swlh/atm-an-object-oriented-design-e3a2435a0830
* Traffic Control System
* Vehicle Parking System
* Online Coding Platform [problem-statement](https://github.com/hocyadav/leetcode-lld-flipkart-coding-blox)
* File Sharing System
* Object Oriented Design Prerations [https://www.oodesign.com/]
* SOLID Principles
* Design Patterns [https://refactoring.guru/design-patterns]
* [More Problems List](https://workat.tech/machine-coding/article/how-to-practice-for-machine-coding-kp0oj3sw2jca)
* More Good Resources:
  * https://refactoring.guru/design-patterns/what-is-pattern
  * http://www.cs.unibo.it/~cianca/wwwpages/ids/esempi/coffee.pdf Recomended by - [sudoCode](https://www.youtube.com/watch?v=B3zrIwz_t4M)
  * https://cseweb.ucsd.edu//~wgg/CSE210/ecoop93-patterns.pdf Recomended by - [sudoCode](https://www.youtube.com/watch?v=B3zrIwz_t4M)

## Engineering Blogs [Ref](https://github.com/mrbajaj/engineering-blogs/blob/master/README.md)
* Airbnb-http://nerds.airbnb.com/
* AirPair-https://www.airpair.com/posts
* Artsy-http://artsy.github.io/
* Asana-https://eng.asana.com/
* Bandcamp-http://bandcamptech.wordpress.com/
* BenefitFocus-http://engineering.benefitfocus.com/
* Bitly-http://word.bitly.com/
* Bittorrent-http://engineering.bittorrent.com/
* Cerner-http://engineering.cerner.com/
* Chartbeat-http://engineering.chartbeat.com/
* Cloudera-http://blog.cloudera.com/blog/
* Cloudflare-http://blog.cloudflare.com/
* Docker-http://blog.docker.com/category/engineering/
* Dropbox-https://blogs.dropbox.com/tech/
* Ebay-http://www.ebaytechblog.com/
* Etsy-https://codeascraft.com/
* Eventbrite-https://engineering.eventbrite.com/
* Facebook-https://code.facebook.com/posts/
* Flickr-http://code.flickr.net/
* Fiftythree-http://making.fiftythree.com/
* Flipboard-http://engineering.flipboard.com/
* Foursquare-http://engineering.foursquare.com/
* Github-http://githubengineering.com/
* Gnip-https://engineering.gnip.com/
* GoSquared-https://engineering.gosquared.com/
* Grouper-http://eng.joingrouper.com/
* Groupon-https://engineering.groupon.com/
* Harry's-http://engineering.harrys.com/
* Heroku-http://engineering.heroku.com/
* Honeybadger-http://blog.honeybadger.io/
* Indeed-http://engineering.indeed.com/blog/
* Instagram-http://instagram-engineering.tumblr.com/
* Intent-http://engineering.intenthq.com/
* Linkedin-https://engineering.linkedin.com/blog
* Livechat-http://developers.livechatinc.com/blog/
* Medallia-http://engineering.medallia.com/blog/
* Monetate-http://engineering.monetate.com/
* Netflix-http://techblog.netflix.com/
* Oyster-http://tech.oyster.com/
* Paypal-https://www.paypal-engineering.com/
* Pinterest-http://engineering.pinterest.com/
* Prezi-https://medium.com/prezi-engineering
* Quora-http://engineering.quora.com/
* Rightscale-http://eng.rightscale.com/
* Salesforce-https://developer.salesforce.com/blogs/engineering/
* Shopify-http://www.shopify.com/technology
* Simple-https://www.simple.com/engineering
* Slideshare-http://engineering.slideshare.net/
* Songkick-http://devblog.songkick.com/
* Soundcloud-https://developers.soundcloud.com/blog/
* Spotify-https://labs.spotify.com/
* Square-https://corner.squareup.com/
* Strava-http://engineering.strava.com/
* Tumblr-http://engineering.tumblr.com/
* Twitter-https://blog.twitter.com/engineering
* Twilio-https://www.twilio.com/engineering/
* Thumbtack-https://www.thumbtack.com/engineering/
* Wayfair-http://engineering.wayfair.com/
* Wealthfront-http://eng.wealthfront.com/
* Webengage-http://engineering.webengage.com/
* Yahoo-http://yahooeng.tumblr.com/
* Yammer-http://engineeringblog.yelp.com/
* Yelp-http://engineeringblog.yelp.com/
* Zenpayroll-http://engineering.zenpayroll.com/
* Zillow-https://engineering.zillow.com/

## Other Useful Resources:
* HOW TO ACE A SYSTEMS DESIGN INTERVIEW-https://www.palantir.com/2011/10/how-to-ace-a-systems-design-interview/
* HighScalability Blog-http://highscalability.com/
* Distributed Systems-http://book.mixu.net/distsys/single-page.html
* Distributed Deep Dive - https://ably.com/blog/introducing-distributed-deep-dive-interview-series-by-ably-realtime
* Architecture for microservice by Microsoft - https://docs.microsoft.com/en-us/dotnet/architecture/microservices/

## System Design Interview Approach Template
### THINGS TO CONSIDER [5 min]
<pre><code>    (1) Features
    (2) API
    (3) Availability
    (4) Latency
    (5) Scalability
    (6) Durability
    (7) Class Diagram
    (8) Security and Privacy
    (9) Cost-effective
</code></pre>
### FEATURE EXPECTATIONS [5 min]
<pre><code>    (1) Use cases
    (2) Scenarios that will not be covered
    (3) Who will use
    (4) How many will use
    (5) Usage patterns
</code></pre>
### ESTIMATIONS [5 min]
<pre><code>    (1) Throughput (QPS for read and write queries)
    (2) Latency expected from the system (for read and write queries)
    (3) Read/Write ratio
    (4) Traffic estimates
            - Write (QPS, Volume of data)
            - Read  (QPS, Volume of data)
    (5) Storage estimates
    (6) Memory estimates
            - If we are using a cache, what is the kind of data we want to store in cache
            - How much RAM and how many machines do we need for us to achieve this ?
            - Amount of data you want to store in disk/ssd
</code></pre>
###  DESIGN GOALS [5 min]
<pre><code>    (1) Latency and Throughput requirements
    (2) Consistency vs Availability  [Weak/strong/eventual =&gt; consistency | Failover/replication =&gt; availability]
</code></pre>
### HIGH LEVEL DESIGN [5-10 min]
<pre><code>    (1) APIs for Read/Write scenarios for crucial components
    (2) Database schema
    (3) Basic algorithm
    (4) High level design for Read/Write scenario
</code></pre>
### DEEP DIVE [15-20 min]
<pre><code>    (1) Scaling the algorithm
    (2) Scaling individual components: 
            -&gt; Availability, Consistency and Scale story for each component
            -&gt; Consistency and availability patterns
    #### Think about the following components, how they would fit in and how it would help
            a) DNS
            b) CDN [Push vs Pull]
            c) Load Balancers [Active-Passive, Active-Active, Layer 4, Layer 7]
            d) Reverse Proxy
            e) Application layer scaling [Microservices, Service Discovery]
            f) DB [RDBMS, NoSQL]
                    &gt; RDBMS 
                        &gt;&gt; Master-slave, Master-master, Federation, Sharding, Denormalization, SQL Tuning
                    &gt; NoSQL
                        &gt;&gt; Key-Value, Wide-Column, Graph, Document
                            Fast-lookups:
                            -------------
                                &gt;&gt;&gt; RAM  [Bounded size] =&gt; Redis, Memcached
                                &gt;&gt;&gt; AP [Unbounded size] =&gt; Cassandra, RIAK, Voldemort
                                &gt;&gt;&gt; CP [Unbounded size] =&gt; HBase, MongoDB, Couchbase, DynamoDB
            g) Caches
                    &gt; Client caching, CDN caching, Webserver caching, Database caching, Application caching, Cache @Query level, Cache @Object level
                    &gt; Eviction policies:
                            &gt;&gt; Cache aside
                            &gt;&gt; Write through
                            &gt;&gt; Write behind
                            &gt;&gt; Refresh ahead
            h) Asynchronism
                    &gt; Message queues
                    &gt; Task queues
                    &gt; Back pressure
            i) Communication
                    &gt; TCP
                    &gt; UDP
                    &gt; REST
                    &gt; RPC
</code></pre>
### JUSTIFY [5 min]
<pre><code>(1) Throughput of each layer
(2) Latency caused between each layer
(3) Overall latency justification
</code></pre>

#### More Resources: 
  * <a href="https://medium.com/javarevisited/25-software-design-interview-questions-to-crack-any-programming-and-technical-interviews-4b8237942db0"> 25 Interview Questions </a>
  * <a href="http://highscalability.com/all-time-favorites">High-Scalability</a>
  * <a href="https://www.hiredintech.com/classrooms/system-design/lesson/52">Hired In Tech </a>
  * <a href="https://workat.tech/system-design/article/best-resources-for-system-design-interview-i-dbv5ok8vtjya">workat.tech</a>
  * <a href="https://github.com/checkcheckzz/system-design-interview">System Design</a>
  * <a href="https://github.com/shashank88/system_design">SYSTEM DESIGN PREPARATION</a>
  * <a href="https://github.com/donnemartin/system-design-primer">The System Design Primer</a>
  * <a href="https://www.youtube.com/watch?v=xpDnVSmNFX0&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=1"> Gaurav Sen Playlist </a>
  * <a href="https://www.youtube.com/c/TechDummiesNarendraL/playlists"> Narendra L - Tech Dummies </a>
  * <a href="https://github.com/prasadgujar/low-level-design-primer"> low-level-design-primer </a>
  * [System Design Interesting Reads](https://docs.google.com/document/d/1iKk6vJbWtI02AllnIEZTrKWQb4dT2QthJdRt05vq6Hw/edit)
  * [Real Time Analytics on Big Data Architecture](https://docs.microsoft.com/en-us/azure/architecture/solution-ideas/articles/real-time-analytics)
  * [how-i-finally-got-some-awesome-offers](https://leetcode.com/discuss/interview-experience/1172461/how-i-finally-got-some-awesome-offers)
  * [Pragmatic Programming Techniques](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
  * [Multithreading](http://www.albahari.com/threading/)
  * [Helpful list of LeetCode Posts on System Design](https://leetcode.com/discuss/interview-question/1140451/helpful-list-of-leetcode-posts-on-system-design-at-facebook-google-amazon-uber-microsoft)
  * [Booking.com interview exp] https://leetcode.com/discuss/interview-experience/1184565/Booking-or-Amsterdam-or-Senior-Java-Developer-or-Apr-2021-Offer
  
#### Credit: 
  * <a href="https://leetcode.com/discuss/career/229177/My-System-Design-Template">https://leetcode.com/discuss/career/229177/My-System-Design-Template</a>
  * <a href="https://www.youtube.com/watch?time_continue=1&v=UzLMhqg3_Wc&feature=emb_logo">https://www.youtube.com/watch?time_continue=1&v=UzLMhqg3_Wc&feature=emb_logo</a>
