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

**Today's Progress**: Successfully set up Docker to get started on my  assigned issue withh [Open Food Network](https://github.com/openfoodfoundation/openfoodnetwork). I struggled to understand `root` and `non-root` user and a plethora of errors that I got trying to set up Docker as `non-root` user previously. There was, however, an error when I tried to run the app on `:localhost`. Luckily, it was a known issue that has already been solved. I just needed to sync my local repo with the upstream master. With this, I re-learnt how to `fetch` from remote repositories and `merge` changes made upstream to the local repo.

**Thoughts:** Docker build reminds me of that time when I was 13 waiting for an entire afternoon for The Sims to download and install on my family's Windows XP desktop...or maybe my laptop is getting old.Jokes aside, the above app that I am hoping to contribute to runs on an older version of Ruby that `is past its end of life and is now unsupported.`. My understanding of how versions of Ruby get managed might be lacking but it got me perplexed how applications originally created with then-best-of-its-time but now-oblivious language/framework version can continue being built with the same one or maintained or updated over time.

**Link to work:** [Issue #6140](https://github.com/openfoodfoundation/openfoodnetwork/issues/6140) 
