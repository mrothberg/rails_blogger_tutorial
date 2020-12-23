# README

Following tutorial: http://tutorials.jumpstartlab.com/projects/blogger.html

Issues with tutorial
- (I5 Authentication) before_filter has been deprecated/removed, replacement method is before_action
- (I4 A Few Gems, 'Adding to the Model') the given `validates_attachment_content_type :image, :content_type => ["image/jpg", "image/jpeg", "image/png"]` line does not work, instead replaced with `validates_attachment_content_type :image, content_type: /\Aimage\/.*\z/`

---------------------
This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
