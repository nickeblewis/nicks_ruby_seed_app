# Nick's Ruby 'Seed' Application

This is the sample application for
[*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/). You can use this reference implementation to help track down errors if you end up having trouble with code in the tutorial. In particular, as a first debugging check I suggest getting the test suite to pass on your local machine:

    $ cd /tmp
    $ git clone git@github.com:nickeblewis/nicks_ruby_seed_app.git yournewrepository
    $ cd yournewrepository
    $ git remote rm origin
    $ git init

    Create new repository on github
    Follow their instructions to push the clone to Github 

    $ bundle install --without production
    $ bundle exec rake db:migrate
    $ bundle exec rake db:test:prepare
    $ bundle exec rspec spec/

    https://devcenter.heroku.com/articles/paperclip-s3
    https://github.com/galetahub/ckeditor
    https://github.com/tsechingho/ckeditor-rails

If the tests don't pass, it means there may be something wrong with your system. If they do pass, then you can debug your code by comparing it with the reference implementation.