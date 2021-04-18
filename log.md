# 100 Days Of Code - Log

### Day 0: November 8, 2020

**Today's Progress**: Moved my terminal cookbook app to Sinatra framework. I built an app that allows me to store, create, edit, remove and import from the internet a recipe using the  MVC model as part of Le Wagon coding bootcamp class.

**Thoughts:** It was really cool getting to know how to transform the `gets` and `put`' of `view` into html files and how html can interact with the database (in my case, a csv file) with `params`. I still, however, struggle to understand the underwork of http calls. For example, when  I called  an erb file in my `get` block, the code broke unless I changed the variables into instance variables (prefixed with `@`). I also ran into the same problem with Nokogiri and searching inside a html doc when running an app on a server, as I did with my [LINE chat bot](https://github.com/zuccamia/veg-dinner-linechat-bot).

**Link to work:** Unavailable as the repository is private to the bootcamp organization.

### Day 1: November 9, 2020

**Today's Progress**: Set up my first project on Rails and started learning [Bulma](https://bulma.io/) for a [volunteer project](https://github.com/zuccamia/patanjalijapan-yoga-app). I have been supporting a local health and wellness organization started up by a friend whom I met at a yoga event here in Tokyo. Previously I helped put together their [website](https://www.patanjali.jp/) and am now maintaining it.

**Thoughts:** I had some issues installing and kicking off Bulma (some `deprecated warnings` with `npm` and `errors` loading `binding.gyp` file) which I have no idea of...Guess I need to take some time to understand the basics of dependencies in software, node and npm. On a side note, after hours running into errors due to misspelling of multiple models, controllers, views files to build a terminal app in Ruby, working on Rails felt like independence day!!

**Link to work:** [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app-web)

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

**Today's Progress**: Created the schema and seeds for DB of the [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app-web) after learning about ActiveRecord migrations.

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

**Link to work:**  [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app-web)

### Day 9: November 26, 2020

**Today's Progress**: Still trying to understand how to link Rails json with React fetch calls. It's supposed to be basic...but yeah, I am going to take it easy 🤨. 

**Thoughts:** Had a call with mom today. I realized how lonely my mom must have felt with a busy kid living abroad. Sometimes we become so enthralled in a pursuit that we unconsciously neglect the most important people in our lives.

**Link to work:** Same as day 9

### Day 10: December 6, 2020

**Today's Progress**: Went back to one of the unsolved optional Active Record challenges of my coding bootcamp curriculum. It took me a while to think in SQL again because the past weeks I have been spending time on front end (which takes **ample** time) with HTML, CSS and JavaScript. My mind was all about the perfect pixel, shadow and in-line boxes. I also participated in a startup event last weekend and that had occupied my mind for several days. 
Oh, I also learned that in Active Record, `limit(3)` is different from `first(3)` (assuming I'm querying a table with ordered records). The difference is, `first` by default follows the order by primary key. If I want it to behave like `limit`, I need to define a `default_scope` with an order method (not by primary key) for the queried model, or chain `.order` before `first`.
  
**Thoughts:** Doing many things at the same time is tempting because of the excitement, the novelty and the entailing adrenaline but more often than not I would end up doing not more than one thing properly (sometimes nothing!). Besides, returning to a project after leaving it to work on another one takes more efforts and time to just remind myself: "where was I again...? Gosh, it feels like I'm starting from scratch. Again!". Really, all I need is ABC!

**Link to work:** none today 😔 

### Day 11: December 7, 2020

**Today's Progress**: Pivoted from Ionic React to Rails and React Native for building the yoga app. Created my first simple user signup and login authentication and login session API on Rails with `bcrypt` with [this tutorial](https://qiita.com/OgiharaRyo/items/9949e5a2cda5e48060f0#%E4%B8%80%E8%A6%A7%E3%83%9A%E3%83%BC%E3%82%B8%E3%81%A8%E4%BD%9C%E6%88%90%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0). There is one issue with this method where the password will be exposed in the URL when returning the login API token JSON. So I went to read about `devise`, tried integrating it with my current User model but did not work out well...so I've decided to set another time to understand it properly. 

**Thoughts:** One reason for pivoting is I am likely to learn React after the code camp anyway and React Native is based on React. It's better to learn once and reinforce than to scratching the surface everywhere😟.

**Link to work:** [Patanjali Japan Foundation App](https://github.com/zuccamia/patanjalijapan-yoga-app-web)

### Day 12: December 8, 2020

**Today's Progress**: Continuing on the yoga app, created the simple reminder form where an user can click Yes or No to log his/her activity for the day. Then styled the app with simple `bootstrap` (which took me almost the same time as the authentication...I hope to get better with time and practice 🥺) because even I wouldn't want to try out the app with the default look. Deployed to Heroku but there was an issue with the image of the logo disappearing on Heroku 😔. I also learned that source image path for `views` in Rails (when running on local host) is `assets/<file_name>.png` and not `../../assets/images/<file_name>.png` 🤯. Maybe Heroku doesn't follow that?

**Thoughts:** Having a direction is already half of the work done. I spent several weeks looking up and trying out different frameworks to build the app but less than 10 hours (combined) to actually build it once I decided on which framework to use.
And yes, Heroku is slow in Japan...

**Link to work:** [Patanjali Japan Foundation App - Web](https://pjf-web-app.herokuapp.com/)

### Day 13: December 9, 2020

**Today's Progress**: Had a problem of pushing local repo to remote one because I nested a repo for web app and another for mobile app inside the original repo locally. Came across `git submodule` and `git subtree` while searching for a solution but although it's exactly what I had in mind, the 2 methods are a bit advanced for my current level with configurations and all. So  I decided to just separate the web and mobile app into independent repos for now.
Also started working on the React Native app. Ran into a `can't find a variable` in a built-in module and am currently stuck...
Complete the user progress feature for the web version instead.

**Thoughts:** While I still can, enjoy the process of learning, not just to churn out an end product!

**Link to work:** [PJF App - Mobile](https://github.com/zuccamia/patanjali-japan-app-mobile)
 
### Day 14: April 7, 2021

**Today's Progress**: First time using AWS for Active Storage on a Rails API and successfully figured out how to upload single and multiple attachments. I also learned about `config/master.key` and how Rails encrypt and store credential keys with it. After my teammate helped set up a AWS storage account and configure the the active storage gem for AWS, it was my turn to add attachment associations and whitelist the attribute for the `Model`. The associations work fine but when I tried to attach and upload (a photo in our case) either in Rails console or via a simple form on `View`, it failed with a `undefined method []' for nil:NilClass`. I had to scratch my head hard, 'but _what_ was `nil`???'. I double checked if the photo(s) params were thoroughly whitelisted, if the associations were correct and if the active storage methods I used were right. They were alright, which confused me further. Thankfully I found a very similar [issue](https://github.com/rails/rails/issues/40763) that gave me a hint. My teammate and I decided to to pair-programming and we figured out how to add the credentials on my local machine. Eventually, the issue occurred because rails failed to read the storage.yml. Credential keys in the `storage.yml` file are read and encrypted in the `credentials.yml.enc` with a Rails `master.key`. However, this `master.key` is by default not pushed to Github. Therefore I didn't have the `master.key` to decrypt the `credentials.yml.enc` created by Lily. There are 2 ways we could solve it:
1. Ask the person who added and configured the AWS active storage gem for her rails `master.key`. Then create your own local file with this key (the easier way).
```
touch config/master.key
```
Paste the master key string as it is.

2. Ask the person who created the team's AWS account for the secrets and keys. Then create your own `credentials.yml.enc`
```
rm config/credentials.yml.enc                                  // remove the old encrypted credentials
EDITOR="code --wait" bin/rails credentials:edit               // use VS Code to open and edit the decrypted keys
// save and close the file to update and encrypt keys
```
_note_: you can change code to atom or vim or any other editor of your choice.

And because `master.key` is **not** pushed elsewhere but stays on the server, we would need to provide this key as a **config variable**.

**Thoughts**: Pairing is fun and can be really productive too!

**Link to work:** Not available since it's currently an organization's private repo.

### Day 15: April 17, 2021

**Today's Progress**: Pending migration error messages in Rails API is not as explicit as that of Rails!
```
2021-04-17T13:18:39.846818+00:00 app[web.1]: I, [2021-04-17T13:18:39.846747 #4]  INFO -- : [b721c8fe-b74e-4ec6-84c0-352e5711e46d] Processing by Api::V1::ExperiencesController#index as HTML
2021-04-17T13:18:39.858532+00:00 app[web.1]: D, [2021-04-17T13:18:39.858453 #4] DEBUG -- : [b721c8fe-b74e-4ec6-84c0-352e5711e46d]   Experience Load (7.1ms)  SELECT "experiences".* FROM "experiences"
2021-04-17T13:18:39.860473+00:00 app[web.1]: I, [2021-04-17T13:18:39.860413 #4]  INFO -- : [b721c8fe-b74e-4ec6-84c0-352e5711e46d] Completed 500 Internal Server Error in 13ms (ActiveRecord: 7.1ms | Allocations: 268)
2021-04-17T13:18:39.861940+00:00 app[web.1]: F, [2021-04-17T13:18:39.861802 #4] FATAL -- : [b721c8fe-b74e-4ec6-84c0-352e5711e46d]
2021-04-17T13:18:39.861941+00:00 app[web.1]: [b721c8fe-b74e-4ec6-84c0-352e5711e46d] ActiveRecord::StatementInvalid (PG::UndefinedTable: ERROR:  relation "experiences" does not exist
2021-04-17T13:18:39.861942+00:00 app[web.1]: LINE 1: SELECT "experiences".* FROM "experiences"
2021-04-17T13:18:39.861943+00:00 app[web.1]: ^
2021-04-17T13:18:39.861945+00:00 app[web.1]: ):
```
A tiny little thing that made me proud was I didn't google at all but figured this out myself...One day at a time 🙂

I also completed a quick Github Learning Lab lesson on working in teams with pull requests. There's an interesting note on things to consider when reviewing PR that I definitely want to keep in mind. It is about `Observing the progress`, that is to focus first and foremost on whether the goal of PR can be reasonably achieved, rather than polising style/wording. The closer the PR to merging, the more robust reviewing will be. Minor changes can be suggested within the PR but major modifications should be suggested with a separate PR based on the author's branch.

### Day 16: April 18, 2021

**Today's Progress**: My little summary about RESTful principles.
RESTful refers to REpresentational State Transfer
**An architecture is considered RESTful when:**
- A `client` is separate from a `server`
- _Statelessness_: `server` can respond to requests from `client` without having to know the session state or any stored context on `client` side
- _Resource_: `client` and `server` communicates by _resource_ that contains nouns, instead of commands what are verbs

**Simple anatomy of a REST request:**
 HTTP VERBS | PATH | HEADER | BODY
------------|------|--------|-----
`GET`, `POST`, `PUT`, `DELETE`| | `Accept`:`<MIME type/MIME sub-type>`| Data
_note_: Default MIME type (such as `text/plain`) is **not** encompassing.
 

