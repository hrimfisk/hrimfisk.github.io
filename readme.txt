1/11/2024 - These instructions may be out of date by now, or I just didnt execute them properly. They have been modified but not tested

1. Install Ruby

2. Open Git Bash

3. Navigate to desired folder (Currently E:/Portfolio/)

4. run command: bundle init

5/16/2024
if gemfile already eixsts, run command: bundle install

5. run command: jekyll new --skip.bundle . --force 
(only include force if the directory is not empty and you are OK with files being overwritten)

6. Open Gemfile

7. Replace two lines of code
replace line 10 with
gem "jekyll", "~> 3.9.3"
replace line 15 with
gem "github-pages", "~> 228", group: :jekyll_plugins

8. run command: bundle install

9. run command: bundle add webrick

10. Copy website files into folder

11. run command: bundle exec jekyll serve


if the site already exists, follow steps 2 and 9

if you get this error: undefined method `tainted?'
run command: bundle update liquid
then step 9

1/11/2024
To restore previous server 

1. Copy all portfolio files to desire folder

2. Open Git Bash

3. Navigate to desired folder (Current D:/Portfolio/Portfolio/)

4. run command: bundle install

5. run command: bundle exec jekyll serve

local web address: http://localhost:4000

5/16/2024
if bundle exec jekyll serve produces an error
run command: bundle update

if bundle exec jekyll serve produces this warning:
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

open Gemfile.fie and change this:

group :jekyll_plugins do
    gem 'jekyll-seo-tag'
end

to this:

group :jekyll_plugins do
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
    gem 'jekyll-seo-tag'
end

then run command: bundle update
then bundle exec jekyll serve should work