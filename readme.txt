1. Open Git Bash

2. Navigate to desired folder (Currently E:/Portfolio/)

3. run command: jekyll new --skip.bundle . --force 
(only include force if the directory is not empty and you are OK with files being overwritten)

4. Open Gemfile

5. Replace two lines of code
replace line 10 with
gem "jekyll", "~> 3.9.3"
replace line 15 with
gem "github-pages", "~> 228", group: :jekyll_plugins

6. run command: bundle install

7. run command: bundle add webrick

8. Copy website files into folder

9. run command: bundle exec jekyll serve


if the site already exists, follow steps 2 and 9