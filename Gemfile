source "https://rubygems.org" #<-- source of gem


gem "sinatra", "1.4.4" #<--- gem name for general use (all groups)
gem "hashie"
gem "octokit", "~>2.0"
gem "awesome_print", :git => "git@github.com:awesome-print/awesome_print.git"

gem "pry", :group => :development #<---- this puts the gem availabitliy into a group. So if you're not in development it won't load "pry" this is in hash syntax
# gem "pry", :groups => [:development, :test <--- this would be for multiple groups 
group :test do #<-- this is in block syntax
  gem "rspec"
end
