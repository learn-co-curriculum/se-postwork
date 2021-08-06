# Ruby and Rails Resources

If you're looking aiming for a job as a Rails developer, or looking to refactor your Rails projects, these resources will help you level up your Ruby and Rails skills.

## Ruby Koans

Visit <a href="http://rubykoans.com" target="_blank">http://rubykoans.com</a> to read about the Ruby Koans.

Clone the git repository from <a href="https://github.com/edgecase/ruby_koans" target="_blank">https://github.com/edgecase/ruby_koans</a>:

```sh
git clone git@github.com:edgecase/ruby_koans.git
```

Follow the instructions to become enlightened.

Expected time to complete all 282 challenges is about 5 hours. You shouldn't try to do it all in one sitting. Instead, try to make progress in 30-60 minute chunks.

## Upcase Rails Tutorials

The fine folks at Thoughtbot have a great collection of resources for Rails developers. Have a look at these video lessons in particular:

- <a href="https://thoughtbot.com/upcase/test-driven-rails" target="_blank">Test-Driven Rails</a>
- <a href="https://thoughtbot.com/upcase/advanced-activerecord-querying" target="_blank">Advanced ActiveRecord Querying</a>
- <a href="https://thoughtbot.com/upcase/intermediate-ruby-on-rails-five" target="_blank">Intermediate Ruby on Rails (Rails 5)</a>

Each tutorial will take between 3-5 hours to complete, but they're very much worth your time!

## Advanced Rails

We've seen that Rails provides tons of common web application functionality out of the box. Surprise! Rails has _way_ more to offer than what Flatiron covers in the curriculum.

For each of these features, start by exploring the documentation; then, implement these features to an existing project or lab for practice.

#### Caching

Start by reading the <a href="https://guides.rubyonrails.org/caching_with_rails.html" target="_blank">Rails Guide on Caching</a>.

Figure out the pages, queries, and computations that are most common and add caching to speed up load times on each of them. You should add some benchmarks or measurements to your application with and without caching so that you can validate that the caching is making a difference.

#### Storing Files

Uploading files is a common feature to add to applications. Read the <a href="https://guides.rubyonrails.org/active_storage_overview.html" target="_blank">Rails Guide on ActiveStorage</a>. Add file uploads of some kind to an app - whether that's images, sound files, text files, or something else.

#### Sending Email

Most 'real' business applications need to send emails. For instance, any application that has users logging in should send confirmation and password reset emails (in addition to whatever newsletter or spam you'd like to send).

ActionMailer is Rails built-in module for sending email. Read about <a href="https://guides.rubyonrails.org/action_mailer_basics.html" target="_blank">ActionMailer Basics</a> in the Rails Guides. Then set up mailer an app to send some automated email, like when a user creates an account, or subscribes to blog posts.

#### Jobs

Applications have some tasks to do that shouldn't necessarily get done right away - they might take a while, so might block the page response time. ActiveJob is Rails's module for setting jobs to be run later. Read the <a href="https://devcenter.heroku.com/articles/delayed-job) might be helpful" target="_blank">Rails Guide on ActiveJob](https://guides.rubyonrails.org/active_job_basics.html) and move your email send into a delayed job. Make sure that you get jobs to run on Heroku (the [Heroku guide on DJ</a>.

If you want an added bonus, set up Resque (or another background job queue). Delayed Job can create extra load on your database, which starts to be a problem when you've got ~100s of transactions per second.

#### Realtime Messages

If you want to build features like notifications or chat, you need to be able to send messages from Rails outside of the HTTP request / response cycle. <a href="https://guides.rubyonrails.org/action_cable_overview.html" target="_blank">Action Cable</a> is Rails's module for setting up websocket connections and sending messages to clients.

Add some realtime features to an app. If you need additional support on understanding websockets and Action Cable, the <a href="https://www.learnenough.com/action-cable-tutorial" target="_blank">Learn Enough Action Cable to be Dangerous tutorial</a> might be a useful reference.
