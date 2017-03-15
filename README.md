## Redmine issue closing

### Description

Manual and automatic management of issues statuses

### To install:

Go to app folder and run:

```ruby
$ cd plugins && mkdir issuecloser && cd ..
```

Copy plugin files to folder /plugins/issuecloser
```ruby
git clone https://github.com/isheninp/redmine_issue_closer.git plugins/issuecloser
```
Do not change folder path!

Go to app folder and run:
```ruby
$ bundle check || bundle install
	
$RAILS_ENV=production bundle exec rake issuecloser:install
```
### License
MIT License. Copyright 2016-2017 isheninp@gmail.com

![C](http://www.google-analytics.com/collect?v=1&t=pageview&tid=UA-93741657-1)

