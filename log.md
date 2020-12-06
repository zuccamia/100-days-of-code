# 100 Days Of Code - Log

### Day 0: November 8, 2020

**Today's Progress**: Moved my terminal cookbook app to Sinatra framework. I built an app that allows me to store, create, edit, remove and import from the internet a recipe using the  MVC model as part of Le Wagon coding bootcamp class.

**Thoughts:** It was really cool getting to know how to transform the `gets` and `put`' of `view` into html files and how html can interact with the database (in my case, a csv file) with `params`. I still, however, struggle to understand the underwork of http calls. For example, when  I called  an erb file in my `get` block, the code broke unless I changed the variables into instance variables (prefixed with `@`). I also ran into the same problem with Nokogiri and searching inside a html doc when running an app on a server, as I did with my [LINE chat bot](https://github.com/zuccamia/veg-dinner-linechat-bot).

**Link to work:** Unavailable as the repository is private to the bootcamp organization.

### Day 1: November 9, 2020

**Today's Progress**: Set up my first project on Rails and started learning [Bulma](https://bulma.io/) for a [volunteer project](https://github.com/zuccamia/patanjalijapan-yoga-app). I have been supporting a local health and wellness organization started up by a friend whom I met at a yoga event here in Tokyo. Previously I helped put together their [website](https://www.patanjali.jp/) and am now maintaining it.

**Thoughts:** I had some issues installing and kicking off Bulma (some `deprecated warnings` with `npm` and `errors` loading `binding.gyp` file) which I have no idea of...Guess I need to take some time to understand the basics of dependencies in software, node and npm. On a side note, after hours running into errors due to misspelling of multiple models, controllers, views files to build a terminal app in Ruby, working on Rails felt like independence day!!

**Link to work:** [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app)

### Day 2: November 10, 2020

**Today's Progress**: Read about Cron job and got to know that Heroku has free scheduler add-on that I can use for my volunteer project app. I also learned how to use SQLite today in the bootcamp class, had fun solving the challenges for querying.

**Thoughts:** Deep work matters. It took me a while to pick up the problem from last night after spending a few hours on the unrelated tasks in my current recruitment job.

**Link to work:** Same as Day 1.

### Day 3: November 11, 2020

**Today's Progress**: Successfully set up Docker to get started on my  assigned issue with [Open Food Network](https://github.com/openfoodfoundation/openfoodnetwork). I struggled to understand `root` and `non-root` user and a plethora of errors that I got trying to set up Docker as `non-root` user previously. There was, however, an error when I tried to run the app on `:localhost`. Luckily, it was a known issue that has already been solved. I just needed to sync my local repo with the upstream master. With this, I re-learnt how to `fetch` from remote repositories and `merge` changes made upstream to the local repo.

**Thoughts:** Docker build reminds me of that time when I was 13 waiting for an entire afternoon for The Sims to download and install on my family's Windows XP desktop...or maybe my laptop is getting old.Jokes aside, the above app that I am hoping to contribute to runs on an older version of Ruby that `is past its end of life and is now unsupported.`. My understanding of how versions of Ruby get managed might be lacking but it got me perplexed how applications originally created with then-best-of-its-time but now-oblivious language/framework version can continue being built with the same one or maintained or updated over time.

**Link to work:** [Issue #6140](https://github.com/openfoodfoundation/openfoodnetwork/issues/6140) 

### Day 4: November 18, 2020

**Today's Progress**: Finally got my docker built and successfully set up my local environment for [Open Food Network](https://github.com/openfoodfoundation/openfoodnetwork). Also made the quick search function of my [LINE chat bot Koko](https://github.com/zuccamia/veg-dinner-linechat-bot) work by replacing URI and Nokogiri parser with Rest-client and API.

**Thoughts:** I was scratching my head hard at why Nokogiri didn't work for me but I still wanted my bot to be able to scrape from the Internet. I almost just let it be until someone updated Nokogiri but I decided to just take another approach. It felt awesome to get something to work and persevering paid off, no matter how trivial that thing would be! 
The previous days (November 12-17) I was kept busy on other assignments (on DB) in my coding bootcamp.

**Link to work:** see above

### Day 5: November 19, 2020

**Today's Progress**: Created the schema and seeds for DB of the [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app) after learning about ActiveRecord migrations.

**Thoughts:** ActiveRecord is pretty magical but sometimes too magical, it's hard to remember all the syntax..

### Day 6: November 23, 2020

**Today's Progress**: After a couple days trying in vain to reproduce [an issue](https://github.com/openfoodfoundation/openfoodnetwork/issues/6140) that I am committed to resolving, I asked for help and got more instructions. I've found myself awkward at asking for help but I'm slowly getting better used to it...

**Thoughts:** The instructions I got turned out to be so...obvious. Not everything has to be engineered and technical solutions are not necessarily optimal; sometimes all it takes is a simple action from user side!

### Day 7: November 24, 2020

**Today's Progress**: Learned how Github pages work and pushed my first page there.

**Thoughts:** Frontend design took me so much more time to complete a seemingly easy task (easy = the solution is clear) than backend. That made me think those designers might be way underpaid!

### Day 8: November 25, 2020

**Today's Progress**: Explored the Ionic framework for building and deploying native mobile app. Also learned the concept of using Rails as an API for React front-end web app/native app. Had a meeting for web app development for a new service of a social entrepreneurship that I am volunteering for. My team mates are graduates from the same coding school I'm in. They handled the meeting well with on-point questions and consultation of technology and process for the CEO (which gave me a little proud moment😊).

**Thoughts:** The framework is pretty sleek and fun to work with, especially with the ready-made UI components resource (saves me tons of hours looking for the right and free button or nav bar look or icon package. Seriously, original designers deserve more money...). My problem is that I am still fairly new to JavaScript and now I am pretty much blind navigating through React 😎...But it's fun! I still need to know how to link Rails with React (TypeScript) in Ionic somehow...

**Link to work:**  [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app)

### Day 9: November 26, 2020

**Today's Progress**: Still trying to understand how to link Rails json with React fetch calls. It's supposed to be basic...but yeah, I am going to take it easy 🤨. 

**Thoughts:** Had a call with mom today. I realized how lonely my mom must have felt with a busy kid living abroad. Sometimes we become so enthralled in a pursuit that we unconsciously neglect the most important people in our lives.

**Link to work:** Same as day 9

### Day 10: December 6, 2020

**Today's Progress**: Went back to one of the unsolved optional Active Record challenges of my coding bootcamp curriculum. It took me a while to think in SQL again because the past weeks I have been spending time on front end (which takes **ample** time) with HTML, CSS and JavaScript. My mind was all about the perfect pixel, shadow and in-line boxes. I also participated in a startup event last weekend and that had occupied my mind for several days. 
Oh, I also learned that in Active Record, `limit(3)` is different from `first(3)` (assuming I'm querying a table with ordered records). The difference is, `first` by default follows the order by primary key. If I want it to behave like `limit`, I need to define a `default_scope` with an order method (not by primary key) for the queried model, or chain `.order` before `first`.
  
**Thoughts:** Doing many things at the same time is tempting because of the excitement, the novelty and the entailing adrenaline but more often than not I would end up doing not more than one thing properly (sometimes nothing!). Besides, returning to a project after leaving it to work on another one takes more efforts and time to just remind myself: "where was I again...? Gosh, it feels like I'm starting from scratch. Again!". Really, all I need is ABC!

**Link to work:** none today 😔 
