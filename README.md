# Ruby on rails ABECEDA!


ROR Community FAVORITE BOOKS/GUIDES:
------------------------------------

######[Agile Web Development with Rails 4](https://pragprog.com/book/rails4/agile-web-development-with-rails-4)######[Rails Crash Course by Anthone Lewis](http://www.amazon.com/Rails-Crash-Course-No-Nonsense-Development/dp/1593275722/ref=sr_1_1?s=books&ie=UTF8&qid=1459021284&sr=1-1&keywords=Rails+Crash+Course)######[Michael Hartl Rails Tutorial ScreenCasts/book](https://www.railstutorial.org/book)######[The Rails 4 Way by Obie Fernandez, Kevin Faustino](http://www.amazon.com/Rails-Edition-Addison-Wesley-Professional-Ruby/dp/0321944275)######[Rails 4 In Action by Ryan Bigg](http://www.amazon.com/Rails-Action-Revised/dp/1617291099/ref=sr_1_1?s=books&ie=UTF8&qid=1459021353&sr=1-1&keywords=Rails+4+In+Action+by+Ryan+Bigg)######[The Complete Web Developer Bootcamp](https://www.udemy.com/job-ready-web-developer/)######[The RSpec Book](http://www.amazon.com/RSpec-Book-Behaviour-Development-Cucumber/dp/1934356379/ref=sr_1_1?ie=UTF8&qid=1459022027&sr=8-1&keywords=rspec)######[GO Rails - Advanced Rails videos..](https://gorails.com/)######[Upcase - Advanced online course](https://upcase.com)

RESOURCES:
----------

http://www.tutorialspoint.com/ruby-on-rails/rails-quick-guide.htm

http://guides.rubyonrails.org/getting_started.html

http://api.rubyonrails.org

http://guides.railsgirls.com

http://ruby-doc.org

http://rubydoc.info

http://programmableweb.com/apis	

http://www.bootstraphero.com/the-big-badass-list-of-twitter-bootstrap-resources/

http://startbootstrap.com

http://mailchimp.com

http://getstream.io


#### Docker or Vagrant for development deployments using puppet/chef (Search it!)
#### Capistrano deployment to AWS (Search it!)
#### moltin.com,  shopify.com  //ecommerce platform (Search it!)

__________________________________________________________________________________________

FAST COMMAND LINE:
------------------
```
rubymine . = opens up rubymine
edit . = opens up textwrangler
open . = opens finder of current directory
open <file> = opens file
open http://google.com = opens browser 
open -a TextEdit = opens file in text editor
open -a firefox = opens firefox
./ is alias that represents current directory
../ is alias that represents parent directory
Command + Option + I = opens Chrome Developer Tools View

<command> then <options> then <arguments>
options: is always preced by a -
command: is always a single word

man echo = gives manual pages of command echo, q to exit
man curl = information on curl command - used to scrape content
pwd = present working directory or print working directory, current path
w = who is online
users = how many users
whoami = who you are logged in as
finger <user> = information about user
groups = tells which groups you are part of
whereis <command> = locations of command
which <command> = which command will be run by default
whatis <command> = shows all options of command
-v, - -version, - -help  //command options, example ruby -v
Exit: q, x, ctrl + q, ESC
semicolons between commands //adding multiple commands to the same line
ps -a = all users processes
ps aux = a for all, u for user, x for background processes
ps -cx = more detail on processes
ps -cvx = more detail
top = all running processes, q to get out of display
cntrl + c = stops process
kill <pid> = kills process id
kill -9 <pid> = force kill
killall <proc*> = kills all processes
mkdir <directoryname> = create directory
mv <file1> <file2> = move file1 to file2, does not copy
cp <file1> <file2> = copies file1 to file2
cp -R <directory1> <directory2> = -R is recursive, copy directories until all directories are copied.
rmdir <directoryname> = remove empty directory, won’t remove if contains files
rm -R <directoryname> = removes all files or directories recursively
rm <file> = remove file
rm -rf <file> = remove files recursively and -f is “force overwriting, destructive

ls -ahlG: list all and in color
ls *.txt: this list all files that end in .txt
ls -al = a; hidden files (start with "."). l; long formatls -lah:
***first return . means the current working directory in our case: /Users/chas
***2nd return .. means the parent directory of current, in our case: /Users
cd / = changes directory to root
***type cd then first few characters of directory and press tab and it will fill in the rest for you
cd Library: changes to library directory
cd Library/Preferences: changes to Preferences directory
cd ~  or cd = (tilde) changes directort to the home directory of user
cd <foldername> = change directory
cd .. = moves back (up) 1 diretory. 
cd ../..: moves back 2 directories
cd ../../../ moves up as many directories
cd Users/chas: is a relative path
cd /Users/chas: is an absolute path
cd ~: is short cut to Users/chas path
cd -: is move back to last known directory, good for toggling between 2 directories
cd software\ development	//use back slash when space in file name
```
up/down arrows: review previous commands
----------------------------------------

Option + click line: move cursor to click point and then press option and press left mouse button.
```
Ctrl + d or exit = logout
Ctrl + l = clear the terminal
Ctrl + u = cut/delete the line
Ctrl + y = paste the last thing to be cut
Ctrl + xx = toggle between the start of line and current cursor position
Ctrl + a = go to the beginning of line
Ctrl + e = go to end of line
Ctrl + _ = undo
Ctrl + c = interrupt/kill whatever you are running
Ctrl + z = stops the current command, resume with fg in foreground, bg in background
Tab: to complete the command or filename
Tab + Tab: when tab doesn’t complete, it will show list of possbile matches
fn + down arrow = page down
fn + up arrow = page up
fn + left arrow = home, beginning
fn + right arrow = end of list
--------------------------------

ping <domainname/host> = ping host and output results
whos <domainname> = get whois information for domainname
hostname = host name of server
dig <domainname> = get DNS information on domainname
dig -x <domainname/host> = reverse look up host
dig <domainname.com> NS +all +answer = nameservers 
dig <domainname.com> ANY +all +answer = view all DNS records; A, MX, NS, etc.
gzip <file> = compresses <file> and renames it to file.gz
gzip -d file.gz = decompresses file.gz back to file
-------------------------------------------------------------------------------------------------------
touch <filename> = create or update file, example: touch file1 file2 file3 (this creates 	new empty files simultaneously, if files already exist it doesn't overwrite the 	files but, merely changes the last access times for the files to the current time)
nano <filename> = open nano to create or modify an existing file (nano is a unix text 
editor - GNU license)
sudo nano <filename> = if get permission denied message
cat <filename> = display contents of file
cat <filename> <filename>: displays contents of both files
less: same but, can go backwards and better memory use
less <filename>: invokes cat command and provides control over scrolling
f for forward, b for backwards or use spacebar for forward, q to quit
press g to go to beginning of document, shift g to end of document

```


__________________________________________________________________________________________

MAC SHORTCUTS:
--------------
```
cmd + tab; switches between apps
cmd + shift + 3: take screenshot, save to desktop
cmd + shift + 4: select area, save to desktop
cmd + shift + 4, then press spacebar, then click on window: pix of current window
cmd + x: cut
cmd + c: copy
cmd + v: paste
cmd + a: select all
cmd + s: save
cmd + shift + s: save as
cmd + p: print
cmd + delete: move selected files to trash
cmd + shift + f: find by file name
fn + delete: backspace delete
cmd + z: undo last action
cmd + /: when highlight code in editor it will comment out the block of code
```

Safari Shortcuts:
-----------------
```
copy, paste, print are same as mac
cmd + f: find
cmd + g: find again
cmd + plus: zoom in
cmd + minus: zoom out
cmd + r: reload page
cmd + option + e: empty cache
cmd + m: minimize safari
cmd + n: new safari window
```
__________________________________________________________________________________________

GITHUB:
-------


http://cheat.errtheblog.com/s/git

Fork = taking a copy of repo, making edits without impacting original, all branches are copied in a fork. fork is at GitHub to GitHub operation, not to your PC. Fork is usually done to take the codebase in a different direction with intent of merging back w/original.
Pull = request to project manager to add your changes to original repo from fork or branch
Branch = snapshot of repo and then merge back into repo, to test new code before merging back. Also used when multiple programmers are updating the same repo. If you both merge Git identifies any conflict between the 2 branches and tells you how to resolve conflicts
Clone = intent is to use it for your own purposes and no one else has access to it

3 configuration levels or options:
----------------------------------
1. system		// setting will hold true for all users
2. global		// global sounds like all users but, it's only per user that set them
3. local		// this is per repository

Settings are stored:
----------------------------------
1. system; /etc/gitconfig
2. global; ~/.gitconfig
3. local; .git/config

Create/Edit User:
----------------------------------
```
which git	#git directory
git version	#git version
git config --get user.name	#user name
git config --get user.email	#user email
git config --global user.name “max”	//configure with your username
git config --global user.email “max@kudosX.com”	   //configure with user email
git config --global color.ui true
nano .git/config to edit or 
cat .git/config to view text

.gitignore = created by rails new command, it ignores log/db files, psw/api key files

git init = creates git repo in current project directory, hidden folder .git
```
1st time:
----------------------------------
```
1. go to github and create repo
git init		//if haven’t initialized project folder yet
git add -A
git commit -m “message of new commit”
git remote add origin git@github.com:KudosX/cheat_sheets.git	//repo name
git push -u origin master		
```
2nd+ times:
----------------------------------
```
git add -A			#git stage 
git commit -m “added gems”	#git commit
git push 			#push to github
```
Add readme file:
----------------------------------
```
nano readme
git add readme			//adds readme file to git staging
```
Commands:
----------------------------------
```
git checkout -f			//rolls code back to last commit, all errors melt away
git remote -v			//to see where remotes point to
git status
git log
git log - -oneline		//easier to read
git log - -stat			//stats of additions/deletions
git log - -stat - -oneline	//easier to read adds/deletes
git log - -oneline - -stat - -all //show all branches and stats on oneline
gitk				//opens up gui 
git reset - -hard HEAD		#discards most recent changes, goes back to last commit
git branch 			#to see list of all branches currently in repository
git branch -a			#list branches remote and local machine
git clone <url>			#makes a local copy of a remote repository
git checkout <name>		#switches to new branch name, all saves to <name> branch
```
Creating Branches:
----------------------------------
the concept of creating a branch is to experiment with your code without affecting the good working code in case you break something.  if you want to bring it back into your good code then you put it back into the main branch
```
git branch 			#to see list of all branches currently in repository
git branch -a			#list branches remote and local machine
git branch <branchname>		#to create new branch name <name>	
git checkout <branchname> // will make a copy of all files from master branch to this branch and then can make changes to the same files without affecting files on master branch
git checkout master 		// will move back to the master branch
```
Merge branch with master:
----------------------------------
```
git checkout master
git merge <branchname>		//will merge branch to master
git diff <hash1> <hash2>	//will show content changed between the 2 hash files
git branch -d <branchname>	#to delete branch, doesn’t delete hashes
git remote add <name> url	#sets up remote branch on github, now use git push to save changes remotely
git push
git pull			#to retrieve changes remotely
git push <remote> <branch>	//this pushes branch to remote branch
example: git push origin master  //pushes master branch to origin branch
```
__________________________________________________________________________________________


HEROKU:
----------------------------------
```
heroku - -version
heroku login
heroku keys:add		//added github_rsa.pub SSH keys
heroku create		//create new app, this creates a git remote associated with your local git repo
heroku rename <new name>	//pinterestx.herokuapp.com or git.heroku.com/pinterestx.git

move gem ‘sqlite3’ to :development, :test group in gemfile
add to gemfile
group :production do
 gem ‘pg’
 gem ‘rails_12factor’
end

bundle install - -without production 	//tells rails to ignore productio

git add -A			 
git commit -m “herokurized - moved sqlite3 gem and added pg in production”	
git push			//skip this if you don’t want changes posted on github
git push heroku master
```

heroku open
----------------------------------
//open webpage in shell with this command

heroku logs
----------------------------------
- -tail	//displays logs of interaction with browser

control c
----------------------------------
//to close streaming logs

heroku ps
----------------------------------
//how many dynos are running

heroku ps:scale web=2
----------------------------------
//would scale your app to 2 dynos

heroku ps:scale web=1
----------------------------------
//scale it back to 1

procfile:
----------------------------------
//is a text file in your root file on heroku to declare what command should be  executed to start your app. in this case it is: web: bundle exec puma -C config/puma.rb (web means it will be attached to http routing stack of heroku and receive web traffic)(the command is to run puma the web server).

heroku local web
----------------------------------
//examines procfile and view your app at http://localhost:5000
 make any changes to your local app and run “heroku local” to view app at localhost:5000

heroku addons:create <addon>
----------------------------------

heroku addons
----------------------------------
//list addons your app is using

heroku addons:open <addon>
----------------------------------
//this will open up addon to view its results

heroku run rails console
----------------------------------
//to open a one-off dyno rails console of your app on heroku, just like on mac

exit
----------------------------------
//to exit console

heroku run bash
----------------------------------
//start a console, this creates an ephemeral filespace, use normal bash commands like ls

exit
----------------------------------
//to exit. can’t SSH into heroku.  once exit the one-off dyno is removed

heroku config
----------------------------------
//to view config vars on heroku

heroku pg
----------------------------------
//view details of pg database

heroku pg:psql
----------------------------------
//to connect to database using psql query

https://devcenter.heroku.com/articles/heroku-postgresql

heroku run rake db:migrate
----------------------------------
//to execute rake command in heroku, actually does it in a one-off then removes itself

https://devcenter.heroku.com/categories/ruby


__________________________________________________________________________________________

GEMSET:
----------------------------------

Ruby Managers: RVM, Chruby, RBENV 
http://kgrz.io/2014/02/04/Programmers-guide-to-choosing-ruby-version-manager.html
http://ryanbigg.com/2015/06/mac-os-x-ruby-ruby-install-chruby-and-you/

https://rvm.io/gemsets/basics

RVM: manages your different versions of Ruby and collection of gems by creating multiple gemsets. Each gemset is the collection of gems you need for a specific project.

Each gemset(collection of gems) is tied to a version of ruby.  have multiple gemsets per ruby version.

During installation of Ruby, RVM creates two gemsets:

default - automatically selected when no @gemset specified: rvm use 1.9.3
global  - super gemset, inherited by all other gemsets for the given ruby


rails -v
ruby -v
gem -v				//rubygems manager version
rvm -v				//rvm version 
rvm env
rvm install 2.3.0		//installs ruby 2.3.0 must put 0 at end
rvm - -default use 2.3.0	//set ruby 2.3.0 as default


Steps to create sticky gemset per application:
1. install RVM			//doesn’t matter which directory you are in
2. rvm get stable		//upgrade to the most stable version of RVM
3. rvm list			//list of installed ruby versions
4. rvm gemset list		//list of gemsets tied with current ruby version
5. rvm 2.2.2			//use ruby version 2.2.2
6. rvm gemset create kudos222 	//create gemset name kudos222, use for multiple projects
7. rvm 2.2.2@kudos222		//makes system use this gemset, @ gemset separator
8. sudo gem install rails - -no-ri - -no-rdoc	//installs latest rails without docs
9. cd /sites
10. rails new kudos		//creates new application
11. cd /kud
12. rvm use 2.2.2@kudos222 - -ruby-version	//this creates sticky gemset for app name
						//exactly as spelled ruby-version, don’t
						//put in ruby version number

rvm install 2.2.3	//installs ruby version 2.2.3
rvm upgrade 2.1.1 2.2.3	//upgrades ruby version, migrates gemsets, wrappers, aliases
			//see: https://rvm.io/rubies/upgrading/
rvm gemset copy 2.1.1@my_app 2.1.2@my_app	//copying gemset to new ruby version
rvm requirements	//installing anything required for rvm to work properly
which ruby		//which ruby currently using
rvm list		//list of installed rubies
rvm list known		//available versions of ruby
rvm install 2.1.4	//will install ruby version 2.1.4
rvm list gemsets 	//List rubies and gemsets for all installed rubies
rvm gemset list  	//List gemsets for current ruby
rvm gemset delete <gemsetname>	//deletes gemset
rvm env			//environment of rubygems
rvm gemdir		//see current gem directory of ruby version

Installing Rails, Creating and switching between gemsets:

$ rvm 2.1.1
$ gem install rails -v 4.1.0

$ rvm gemset create rails410 rails320
Gemset 'rails410' created.
Gemset 'rails320' created.

$ rvm 2.1.1@rails410
$ gem install rails -v 4.1.0

$ rvm 2.1.1@rails320
$ gem install rails -v 3.2.0

Switch between environments:

$ rvm 2.1.1@rails410 ; rails --version	//after ; is new command to output rails version

Rails 4.1.0

$ rvm 2.1.1@rails320 ; rails --version

Rails 3.2.0


__________________________________________________________________________________________

GEMS + BUNDLE:

http://guides.rubygems.org/rubygems-basics/#installing-gems

Bundler: keeps track of gems for different versions of ruby applications using gemfile

only load gems in group you will need the gem for such as; development, test or production

-add gem to gemfile and then run bundle install, generally good idea to close your rails server terminal and restart your rails app: rails server

gem env			#reveals where the gems live and environment
gem list		#shows gems in gemset
gem which bundler 	#more specific where gems live
gem install bundler	#installs latest bundler
bundle install		#reads the gemfile, downloads gems into hidden gem folder
bundle update		#will update outdated gems to newest. updating may break application
bundle outdated		#to see which gems are available for newer versions
which bundle		#file location
bundle -v
bundle show		//shows all gems that are part of the bundle 
bundle show —paths	//2 dashes, shows paths to all the gems
bundle version		//version of bundle
bundle outdated		//list installed gems with newer versions available
bundle exec		//run the command in context of the bundle
bundle check		//checks if dependencies listed in gemfile are satisfied by current installed gems
bundle list		//names and versions of all gems being used by application

gemfile:

gem ‘rails’, ‘4.2.0’	#is absolute: only version 4.2.0 will be used
gem ‘rails’, ‘>= 4.2.0’ #any newer version than 4.2.0 will be used
gem ‘rails, ‘~> 4.2.0’	#any minor version up to 4.3 so, 4.2.5, 4.2.9 but, not 4.3.0 or higher

gem install rails - -no-ri - -no-rdoc	//use this to install latest version rails/no docs
gem install rails			//will install latest version of rails
gem install rails -v 4.1.0		//install specific rails version
gem install rails - -no-ri - -no-rdoc - -versions 4.0.0	//no docs, 2 dashes no space
gem uninstall rails -v 3.2.0		//unistall rails or any other gem using uninstall
gem install <gem_name>	//install gems in current gemset
gem list		//list of gems in current gemset, rails being one of them
which gem		//path of installation, installed as part of Ruby since 1.8
gem -v			//version of gem
gem update —system	//2 dashes and updates to latest version of rubygems
gem env			//evironment of rubygems
gem -help		//help 
which rails		//path of rails install for current “use” environment
rails -v		//rails version being used by current gemset
bundle show [gemname]   //to see where gem is installed
gem which 		//see where gems live

__________________________________________________________________________________________

HOMEBREW:

brew doctor
brew prune
sudo brew prune
brew install get
brew update

__________________________________________________________________________________________

ACTIONCABLE, WEBSOCKETS, CHANNELS, MESSENGING, PUB/SUB:

Use Rails 5 with actioncable unless in the top 10k of alexa rankings use phoenixframework.org
Actioncable = is integrated websockets for rails
tubbo used pushr not pusher
radar says superior to actioncable, simple cable or connection from client to server
https://github.com/radar/rumbl
http://faye.jcoglan.com
search “examples of using phoenixframework”
http://www.phoenixframework.org/blog/phoenix-10-the-framework-for-the-modern-web-just-landed, great video of use
http://phoenix.thefirehoseproject.com/0.html


__________________________________________________________________________________________


DEPLOYMENT AUTOMATION:

capistrano
heroku


CONTINUOUS INTEGRATION:

Travis CI
Cruisecontrol


CONFIGURATION MANAGEMENT FRAMEWORK:

chef.io - chef server, delivery, compliance, analytics, high availability


VIRTUALIZATION:

Docker - allows you to run multiple applications on a single linux instance vs. a VM or VPS per app, also easy to package and ship programs


ANALYTICS:

localytics.com - free up to 10k MAU’s
mixpanel.com	- free up to 25k MAU’s, how users engage in your app
amplitude
flurry

https://medium.com/polecat-blog/mobile-analytics-mixpanel-vs-amplitud-vs-flurry-vs-localytics-aeb6bf02b734#.90d3lx6xo


__________________________________________________________________________________________


RAILS:

-always look at gems in toolbox or github to do something that has been done before.
-Much of the art of programming is learning what classes are available in the API and deciding when to subclass to inherit useful methods
-db table is plural, model is singular, controller is plural
-all ruby folders are /Users/chas/.rvm/rubies/
-all rails folders are /Users/chas/.rvm/gems/


WORKFLOW FOR NEW RAILS APP: (mainly from learn ruby on rails - john elder book)

1. rails new <appname>		//adds many gems and one controller and view
1a. rake db:create db:migrate //if using postgresql, otherwise will get error of no database
2. rails s
3. http://localhost:3000/	//view your new app in a browser
4. create rubyrails_version.txt file app folder for ruby, rails and gemset version

DELETE APP:

rake db:drop	//from app directory, if created model
cd .. && rm -rf <appname>	//use cd.. && - if in app directory

CHANGING GEMFILE:

1. /gemfile and delte gem ‘sqlite3’	//this deletes sqlite3 from dev and production, add
2. group :development,:test do
     gem’sqlite3’			//could make this postgres as well
   end
   group:production do
     gem’pg’,   ‘0.17.1’		//postgres, heroku only uses postgres
     gem’rails_12factor’,’0.02’		//this is specific for heroku
   end
3. bundle install- -without production	//runs bundle but, not for production

ADDING PAGES via CONTROLLER:

1. rails generate controller home index	//adds a page called index in home directory by adding controller, view, helpers, tests, coffee javascript assets, scss css assets
1a. rails generate controller home index about contact faq	//would add all these pages with 1 command
2. http://localhost:3000/home/index
3. config/routes.rb, change get ‘home/index’ to root ‘home#index’ . now our home page is at http://localhost:3000

ADDING MORE PAGES:

1. manually add “ABOUT US” page to app/views/home, name the file: about.html.erb
2. add some <h1>about us</h1>, <p>blah blah blah</p>
3. need to add about us page to controller so our app knows about it: app/controllers/home_controller.rb, add method
def about
end
4. config/routes.rb, add get ‘home/about’
5. http://localhost:3000/home/about

ADDING MANY PAGES AT ONCE via CONTROLLER:

1. rails generate controller home index about contact faq
2. this will add all the pages to your app/views/home directory and add methods to your controller and routes to your routes file. 
NOTE: don’t run this command after already added some pages, may get weird. 

ADDING LINKS/MENU VIA LAYOUTS/APPLICATION.HTML.ERB:

Creating partials is a 2 step process:
1. create partial, in our case views/home
2. call the partial from a file, in our case the layouts/application.html.erb

1. rake routes		//show all routes currently available, 1st column shows the route you need to use for the link_to tag, just add _path to end of it
2. <%= link_to ‘Home’, root_path %>
   <%= link_to ‘About Us’, home_about_path %>
//this tells app we want to make a hyperlink and “About Us” is anchor text that will show up on web page.  Then home_about_path is telling our app what route to follow, the _path is saying it’s the path to home_about or home/about
3. _header.html.erb	//creates new file at app/views/home, “_” means it’s a partial
add the code from #2 above
4. app/views/layouts/application.html.erb //is a framework for every page in our app
add <%= render ‘home/header’ %> just above the <%= yield %> tag.
5. the contents of application.html.erb get outputted every time a page is requested. The <%=yield%> tag is calling the contents of your page (i.e. app/views/aboutus) and outputting it in that spot. It also takes the partial and outputs just above the content.

USING BOOTSTRAP, JUMBOTRON, BUTTONS:

1. www.getbootstrap.com	//“components” link at top, add any code snippet to your page.
2. rubygems.org and look up bootstrap-sass and click on clipboard icon to copy gem# and version number and copy to gemfile
3. bundle install
4. add file to app/assets/stylesheets and name it bootstrap.css.scss or anything else
then add these 2 lines to the file
@import “bootstrap-sprockets”;
@import “bootstrap”;
5. add these 2 lines to the app/assets/javascripts/application.js file
//=require bootstrap-sprockets
//=require bootstrap		//make sure these 2 lines are above //=require_tree
6. wrap yield tag in a container div; go to application.html.erb and add
<div class=“container”>
  <%=yield %>
</div>
7. add a jumbotron to index page; go to app/views/home/index.html.erb and add
<div class=“jumbotron”
  <h1>Welcome</h1>
  <p>blah blah blah</p>
</div>
8. add some buttons to jumbotron, go to css link on getbootstrap.com and using their html code but, rails modify it to work in rails. add ruby to app/views/home/index.html.erb
<div class=“jumbotron”>
…
<%=link_to’About Us’,home_about_path,class:’btn btn-default’%>
<%=link_to’Home’,root_path,class:’btn btn-primary’%>
</div>

BOOTSTRAP - ADDING A NAVIGATION BAR:

-go to navbar under components at getbootstrap.com
1. copy and paste the code to app/views/home/_header.html.erb	//partial file
2. wrap link_to tags in li tags; <li><%=link_to’Home’,root_path%></li>
3. change html to ruby on brand tag <%=link_to’myAppName’,root_path,class:’navbar-brand’%>
4. can have footer, left side and ride side partials as well, just add them to application file.

CUSTOMIZING BOOTSTRAP:

-to customize tab at getbootstrap.com.  click on less variables and select jumbotron
NOTE: bootstrap by default uses LESS but, we loaded the gem bootstrap-sass, (SASS)
LESS uses @, SASS uses $
1. add color blue to jumbotron, go to app/assets/stylesheets/bootstrap.css.scss and add
$jumbotron-bg:blue;	//for gradients of blue use hex like: #0041a0
$navbar-default-bg:#014421;	//background color of navbar green
$body-bg:#fa9fb9;		//body of entire site pink
@import “bootstrap-spockets”;	//all customization above this line

INSTALLING DEVISE:

-go to rubygems.org and click on copy button of devise gem and paste in gemfile
1. bundle install
2. rails generate devise:install	//it prompts for more information
3. config/environments/development.rb add 
config.action_mailer.default_url_options={host:’localhost’,port:3000} //above “end”
4. config/environments/production.rb add
config.action_mailer.default_url_options={host:’yourDomainNameOfApplication.com’}
5. app/views/layouts/application.html.erb	//add alert information
<div class=“container”>
  <%flash.each do|name, msg|%>
    <%=content_tag(:div,msg,class:”alert alert-info”)%>
  <%end%>
  <%=yield %>
</div>		//snippet of code from alerts under components on getbootstrap.com
	//this is ruby loop, for each flash msg, do something, output msg in CSS div with class “alert alert-info”
NOTE: <%= means output this to the screen, <% means its ruby code
6. rails g devise:views		//this creates all the view pages /app/views/devise
7. rails g devise user		//creates user table and database migration
8. rake db:migrate		//pushes migration into database, can modify columns, rows before this command is run by going to db/migrate
9. rake routes			//to see list of pages we have and URL’s to find pages
10. http://mywebapp.com/users/sing_up	//this will be one of your pages in browser
11. app/views/devise		//is list of all pages to modify
12. page 111 in learn ruby on rails by john elder to change devise pages and navbar
13. page 111 to 205 to customize entire app, pinterest clone

PUSHING TO HEROKU:

1. sign up for heroku, download and install heroku toolbelt
2. heroku - -version
3. heroku login
4. heroku keys:add	//heroku will find your SSH keys itself, from github
5. heroku create	//gives us a weird URL where our app sits
6. heroku rename KudosBro123	//whatever name you want, if available as a subdomain
7. new URL for my app is now KudosBro123.herokuapp.com
8. git add
git commit-m “my comments”
git push
git push heroku master	//pushes it to heroku
9. go to heroku URL you made before and your app is live
10.heroku run rake db:migrate	//this will run migration on postgres in production

SCAFFOLD WORKFLOW:		//creates model, controller, views, migration and tests

-p.122 from Learn Ruby on Rails  - John Elder
1. rails g scaffold <myscaffoldnames> description:string	//creates new table, name is plural, description tells rails to create a column in our new table as string data type
2. edit migration file if necessary
Possible data types: :binary, :boolean, :date, :datetime, :decimal, :float, :integer, :primary_key, :references, :string, :text, :time, :timestamp
3. rake db:migrate or bundle exec rake db:migrate
4. Heroku rake db:migrate 	//if in production
5. Delete app/assets/stylesheets/scaffolds.css.scss file. running scaffold overwrites our bootstrap CSS file so, delete it.
6. rake routes		//to view all the files scaffold created, GET are view pages
7. modify app/views files and _partials using bootstrap
8. app/db/schema.rb	//is a snapshot of our current database.  NEVER edit. 
9. p. 111 to 205 of learn ruby on rails-john elder to customize
10. p. 163, storing passwords using environmental variables
11. rails g migration AddNameToUsers name:string	//add column Name to Users table
or rails g migration add_name_to_users name:string	//camel case  or underscores
12. rake db:migrate

TEMPLATES:

Rails recipes by chad fowler p. 256
http://guides.rubyonrails.org/rails_application_templates.html
-this is to auto create a standard application with gems/initializers
rails new <mynewapp> -m ~/sites/template.rb

GENERATORS:

Rails recipes by chad fowler p.259
http://guides.rubyonrails.org/generators.html
-to view list of baked in generators
rails new myapp
cd myapp
rails generate		//this will list general options and generators

gem search -r generator		//lists all the current remote generator gems

__________________________________________________________________________________________

RAILS COMMANDS:

rails -v
ruby -v

rails server		#start webrick server
rails s			#short version
http://localhost:3000/
http://localhost:3000/posts	#to view post application

control c		#to stop web server and return to command prompt
control d 		#to close session
rails c			#rails console, exit to exit console

>>User				//will return all users in the database
>>User.find(3)			//will give an error since ID 3 of foo was destroyed
>>User.find_by(id: 3)		//only returns user 3 data and then nil
>>User.find_by(email: “mikey@gmail.com”)	//finds all users by that email
>>@user = User.first		//first user

-when a browser sends requests to WEBrick web server, diagnostic messages are written to console and to log/development.log file, the same messages

-always use one session tab for messages and 2nd tab for rails commands and a 3rd for guard testing and a 4th for the rails console.  each terminal window is a separate process

-must restart web server only when make changes to gemfile or configuration files, they are loaded at web server launch

bundle list	#names and versions of all gems being used by application
bundle install	#installs gems from gemfile
rails		#list options
rails new [name]#generates new rails application
rails generate	#list options
irb		#starts interactive ruby console, enter exit to leave irb
rails console	#starts rails console, enter exit to leave console
rails dbconsole	#starts command line interface for current db
rails console production #opens rails console for production environment

rails generate scaffold Post title:string body:text	#app is blog post, title and body
rails g scaffold [name] - -skip - -no migration	#scaffold skipping existing files

rails generate controller demo index	//this tells rails to generate controller named demo and view named index
rails g controller - -h		#usage documentation
rails g controller [name]	#creates controller, views, helplers, tests and assets
rails destroy conroller [name]

rails g model - -h
rails g model User		#creates User model, migration and tests
rails g model Comment author:string body:text post:references #adds a 2nd model for an association w/post model
rails destroy model [name]

rails g migration add_ColumnName_to_TableName #adds a column to table
rails g migration add_author_to_posts author:string	#example with author being a string

rake - -tasks		#list of tasks your application can use along with short description
rake -T			#list of rake commands
rake -T db		//will list out only the db rake commands
rake db:migrate		#to add migration to database, default is development mode
rake db:migrate RAILS_ENV=production	//if want to do migrate for different environment
-look at db/schema.rb to see columns in database
rake db:schema:load	#resets database structer and removes all of your data
rake routes		#list of all available routes
rake db:test:clone	#clones current environments’ database schema
rake db:test:purge	#empties the test database
rake db:reset		#drop database and recreate, use rake db:migrate after
rake test		#runs all tests by default
rake test test/models/user_test.rb	#will just run this test
rake test:models	#runs all tests under test/models folder, in the past called unit tests
rake test:controllers	#runs all tests under test/controllers folder, previously called functional tests
rails g integration_test user_flow #this creates a file named test/integration/user_flow_test.rb 
-this creates a file to edit to test how a user interacts with your application

rake db:schema:dump RAILS_ENV=production	//this will change to production db


Production:

-In development it skips everything except the file processing
-assets have to be precompiled when go into production and this can take 1-5 minutes
-if using capistrano it does it for you but, do below on your development server if you want to test production before deploying or on a beta production staging server

RAILS_ENV=production bundle exec rake assets:precompile	


__________________________________________________________________________________________

RAILS RUNTIME GEMS:

Actionmailer - framework for email delivery and testing
Actionpack - framework for routing and responding to web requests
Activerecord - framework for connecctions to databases
Activesupport - utility classes and Ruby library extensions
Bundler - utitlity to manage gems
Railties - console commands and generators
Sprockets-rails - support for the rails asset pipeline

-when you install rails, a total of 44 gems are installed in your development environment

When start a new application and run: rails new <appname> these gems are also installed:
sqlite3 - adapter for the SQLite database
sass-rails - enables use of the SCSS syntax for stylesheets
uglifier - javascrpt compressor
coffee-rails - enables use of the coffeescript syntax for javascript
jquery-rails - adds the jQuery javascript library
turbolinks - faster loading of webpages
jbuilder - utility for encoding JSON data


BDD (Behavior-Driven Development) - BDD takes user stories and turns them into detailed scenarios that are accompanied by tests. Cucumber is good tool. I am just going to use minitest with capybara and not cucumber

DSL - DOMAIN SPECIFIC LANGUAGE:

-Ruby is a DSL, it is only used for building web applications, “domain” means area or field of activity
-some GEMS add their own DSL’s, cucumber gem provides DSL for turning user stories into automated tests.

MVC ARCHITECTURE: (from browser to MVC)

-controller can query multiple models and views to render back to browser
-A controller can have more than 1 action. Each action is method of the controller class
-action and method are used interchangeably
-to be precise, controller actions are implemented as methods
-controllers have 7 standard actions: index, show, new, create, edit, update, destroy 
-a controller that offers these actions is said to be RESTful (represetational state transfer)
-not every controller action has its own view file.  Many controllers, on completion, the destroy action will redirect to the index view, and create will redirect to either show or new.
-build models first then controllers then views.  build most difficult part first.
-most often a controller will have the same name as it’s main model, although a controller can access multiple models

Database, Twitter API, Other API’s
  ^
Model	View
  ^      ^ 
Controller		#controller communicates back to browser via app and web server
   ^
Router			#router is 1 way, only from browser and not back to browser
   ^			#routers job is to direct to appropriate controller
Application Server
   ^
Web Server
   ^
Browser


DEFINITIONS:

-class: an abstraction that encapsulates data and behavior 
-class definition: written code that describes a class 
-instance or object: a unique copy of a class that exists only while a program is running 
-inheritance: a way to make a class by borrowing from another class 
-class hierarchy: classes that are related by inheritance 
-method: a command that returns data from an object
-attribute or property: data that can be set or retrieved from the object 
-variable: a name that can be assigned a value or object 
-expression or statement: any combination of variables, classes, and methods that returns a result

model tests were previously called unit tests
controller tests were previously called functional tests
integration tests verify interaction between different controllers


NAMING RULES:

-db table is plural, model is singular, controller is plural, scaffold is plural
-Class name Model Rule: capitalized and singular, i.e. Visitor
-Class name Controller Rule: combine pluralized model name with “Controller” in CamelCase, i.e. VisitorsController
-model filename matches model class name, but lowercase, i.e. app/models/visitor.rb
-controller filename matches controller case name but, snake_case, i.e. app/controller/visitors_controller.rb
-views folder matches model class and/or controller name, but plural and lowercase, i.e. app/views/visitors

DATABASE DEFINITIONS:

-CRUD: Create, Read, Update, Destroy
—each table in database is represented by a class 
-each row of that table is represented by an instance or object of that class
-each column of that row is represented by an attribute of that object
-to see the posts title, call post.title
-4 major functions of database applications are create, read, update, delete; CRUD

Post.create title: “First Post”	
#in console this instantiates a new POST object, assigning value(attribute of title) and saving to db.

-database migrations are used to change database’s structure but, not saved to database until run:
rake db:migrate

MAILERS FOLDER:

Folder is for code that sends emails messages

HELPERS FOLDER:

Folder for view helpers, snippets of reusable code that generate HTML

__________________________________________________________________________________________

CLASSES:

-there is one class at the apex of the Ruby class heirarchy: BasicObject
-the Object class inherits from the BasicObject.  
-All classes in Ruby and Rails API’s inherit their behavior from Object
-Classes give organization and structure to a program. Methods get the work done.

class Example < Object		#Example class inherits from class Object, < means “inherits from”
class Example			#is also correct without explicitly subclassing from Object
 
-Much of the art of programming is learning what classes are available in the API and deciding when to subclass to inherit usefull methods

__________________________________________________________________________________________


OBJECTS and METHODS:

Everything in Ruby we create and manipulate is an object.  To distinguish one object from another, we define it as a class, give it a class name, and add behavior in the form of methods.
-Methods describe the class behavior

“def” stands for method definition, three methods defined below

def name . . . end		#each method assigns data to a variable
def birthdate . . . end		
def countdown . . . end		

-later we retrieve the data for use in our view file by instantiating the class and calling a method
-Ruby makes it easy for a method to return data when called; the value assigned by the last statement will be delivered when the method is called.
-any object can be assigned to a variable. This gives us access to the objects class methods anywhere we use the variable. 
-We can use the objects supplied by Ruby’s prefabricated objects defined by the Ruby API or create our own. The API catalog are prebuilt classes that are building blocks for any application. 

http://api.rubyonrails.org

-If we want to send data to a method, we define the method and indicate it will accept parameters
-Parameters are placeholders for data values. “empty placeholders”
-The values that are passed to a method are agruments. arguments are “actual values”
-enclose list of parameters in parentheses, optional but, helps readability.

-we can assign any object to a variable, the variable works like an alias.  
-We can use a variable anywhere as if it were the assigned object.

__________________________________________________________________________________________

DOT OPERATOR:

”dot” is the method operator. It allows us to call a method to get a result

-some classes such as Date provide class methods called directly on the class without instantiating it first.

Date.today
‘foobar’.reverse.update		#called method chaining

? indicates method will return a boolean value (true or false)
! indicates method will throw an exception on failure rather than failing silently


__________________________________________________________________________________________

STRING:

A series of characters enclosed in single or double quotes.

__________________________________________________________________________________________


SYMBOL:

-is like a variable, but can only be assigned a value once.  It is immutable, cannot be changed

:name

__________________________________________________________________________________________

ATTRIBUTES:

-In an object, methods do the work and data is stored as variables. 
-We can’t access data in variables from outside the object unless it is exposed as attributes.
-Classes can have attributes, which we can “set” and “get”. 
-Attributes are a convenient way to push data to an object and pull it out later.
-Attributes are also called properties.

attr_accessor :name	#here we want to expose the name attribute

-Attributes are just specialized methods that expose data outside the object.

__________________________________________________________________________________________

INSTANT VARIABLES:

-An ordinary variable can only be used within the method in which it appears inside an object, if you use the same name variable in 2 different methods in same object it will have different values
-The scope fo the variable is limited to the method in which it is used.

-an instance variable @ is available throughout an instance, within any method of that object.
-If you create 2 instances of the same class, with the same instance variable name, they will have different values. 
-instance variable is not visible outside the object, unless you use an attribute.

-You must use @ instant variables if you are rendering views in a controller, since in Rails, a view is NOT a separate class.  Under the hood it is part of the current controller object.

__________________________________________________________________________________________

DOUBLE BAR EQUALS OPERATOR:

||=	“or equals”

-is used for conditional assignment. Only assign a value to a variable if no value has been previously assigned, commonly done as a “default value” when no other value has been assigned.
 
@honorific ||= ‘Esteemed’	#this is equivalent to:

if not x
  x = y
end

__________________________________________________________________________________________

TERNARY OPERATOR AND INTERPOLATION:

-ternary is ruby golf, experience programmers use to reduce # of characters but, is much harder to understand because of it’s crypic nature.
-Interpolation is similar to reduce characters, must use “”double quotation marks and {}
titled_name = @example + ‘ ‘ + @name	#shortened to:
titled_name = “#{@example} #{@name}”

__________________________________________________________________________________________

PRIVATE:

-Any methods that follow the keyword “private” should only be used by methods in the same class or subclass.  

__________________________________________________________________________________________

HASH:

-retrieve a value based on its key often called dictionary, associative array or map, use the key to look up the value as in a dictionary

‘budy holly’ => Date.new(1936,9,7)	#using a “hashrocket” => or:
holly: Date.new(1936,9,7)		#colon associates the key and value

__________________________________________________________________________________________

ARRAY:

-an array can be instantiated with square brackets:
my_list = [ ]

-we can populate the array with values when we create it:
my_list = [‘apples, ‘oranges’]

-or same thing without commas and quotation marks:
my_list = %w( apples oranges )

-we can add new elements to an array with a “push” method:
my_list = Array.new
my_list.push ‘apples’		#or using << shovel operator
my_list << apples

http://www.ruby-doc.org/core-2.2.0/Array.html

__________________________________________________________________________________________

ITERATOR:

my_list.each 	

-each method applied to a hash or array, always followed by a block of code, each item is passed thru the block of code to be processed

__________________________________________________________________________________________

BLOCK:

-block is when you see a do . . . end structure. often following an iterator.
famous_birthdays.each do |name, date|
  if date.month == 12
    born_in_december << name
  end
end

-within the | | we assign the key and value to two variables, only available within the block
-as each key-value pair is presented by the iterator, the variables are assigned and statements executed
when we find the date is equal to 12 we add the name to the array
-variables are only available within the block of the method, not outside the method.

__________________________________________________________________________________________


STATIC PAGES:

-create file in public/ called index.html
<h1>hello all</h1>	
rails server
http://localhost:3000/

-add about us page to public/about.html
<h1>about us</h1>	
http://localhost:3000/about.html

__________________________________________________________________________________________

ROUTING:

http://guides.rubyonrails.org/routing.html

-open file config/routes.rb and add
Rails.application.routes.draw do
  root to: redirect(‘/about.html’)
end
http://localhost:3000/		#will show about us page

another example:
Rails.application.routes.draw do
  root to: ‘visitors#new’	#routes to VisitorsController “new” action
end

__________________________________________________________________________________________


CONTROLLER:

rails g controller [name]	#creates controller, views, helplers, tests and assets

-API’s are managed thru config/routes.rb and controllers/api controllers

-skinny controller, skinny model: separation of concerns more modular. data manipulation in model, controller contains enough code to instantiate a model and render a view
-more advanced, if there are many methods in a model, then turn methods into service objects that are called from a controller or model, they are placed in app/service folder
-controller can query multiple models and views to render back to browser
-A controller can have more than 1 action. Each action is method of the controller class
-action and method are used interchangeably
-to be precise, controller actions are implemented as methods
-controllers have 7 standard actions: index, show, new, create, edit, update, destroy, additional ones are; pagination, sorting, bulk edit
-a controller that offers these actions is said to be RESTful (represetational state transfer)
-not every controller action has its own view file.  Many controllers, on completion, the destroy action will redirect to the index view, and create will redirect to either show or new.
-most often a controller will have the same name as it’s main model, although a controller can access multiple models

Visitors#new	#controller class name with action (method) new, # is documentation convention

class VisitorsController < ApplicationController 
  def new 
    @owner = Owner.new 			#it knows to render view “new” file to browser
  end 
end

-ApplicationController does all the work rendering the view but, if we make the code explicit it would look like this:

class VisitorsController < ApplicationController 
  def new 
    @owner = Owner.new 
    render 'visitors/ new'
   end
end 

-flash messages are added in the controller or can go in your application layout file or partial 

__________________________________________________________________________________________

MODEL:

rails generate model		#creates model with access to database. if don’t need access to database
				#then refer to daniel kehoe book under models

-build models first then controllers then views.  build most difficult part first.

__________________________________________________________________________________________

VIEWS:

-app/vies/layouts/application.html.erb is the master layout file
-name the view file after the controller action, i.e. “new”
app/views/visitors/new.html.erb		#ERB templating engine or HAML or SLIM
<%= @owner.name %>		#the evaluating code will be replaced by results in controller action

__________________________________________________________________________________________

IRB: (INTERACTIVE RUBY SHELL)

irb		#ruby interpreter that runs any ruby code in command line, IRB doesn’t know Rails.

> load ‘./mytest.rb’	#will load and run any code in the mystest.rb file
> exit			#to exit irb

-type in a few characters and hit “tab” and IRB will complete based on its guess
-if nothing happens then more than 1 choice,hit twice and will give list of methods for object

-PRY replaces IRB with a more advanced console. Page 280 in Rails 4 Test Prescriptions

__________________________________________________________________________________________

RAILS CONSOLE:

rails console	   #it’s IRB for Rails, it loads your Rails application and allows you to interact in real time

>exit			#to exit rails console

__________________________________________________________________________________________

CSS:

-common to use multiple CSS files.  make a file for each theme on a page

__________________________________________________________________________________________

RAILS LOGGING:


http://guides.rubyonrails.org/debugging_rails_applications.html

/log/development.log	#everything written to console is also written in log file
/lob/production.log

-add your own messages to the log outby by using Rails logger:

def new
  Rails.logger.debug ‘DEBUG: entering the new method’		#this will appear in log file and console
  @owner = Owner.new
  Rails.logger.debug ‘DEBUG: Owner name is ‘ + @owner.name	#also appear
end

-In a Controller, you can just use the method “logger” on it’s own
-in a Model, you have to use “Rails.logger”(both class and method)
-messages written with the logger.debug method will not be recorded in  production log files

other methods:
logger.debug
logger.info
logger.warn
logger.error
logger.fatal

-when the program halts with an error it will display a “stack trace”.  About 60 lines of tracing, just look at the top couple lines it will show line number in file that created error:
app/controllers/visitors_controller.rb:7:in ‘new’	#line 7 of new method

__________________________________________________________________________________________


RAISE AN EXCEPTION:

-”raise” forces your application to halt and output any message you want in quotation marks
-there are many methods to “raise” 

def new
 Rails.logger.debug 'DEBUG: entering new method' @owner = Owner.new
 Rails.logger.debug 'DEBUG: Owner name is ' + @owner.name
 raise 'Deliberate Failure'
end

__________________________________________________________________________________________
 
TESTING:

minitest for unit testing
capybara for acceptance testing, integration testing from a user perspective
-in most cases capybara is used with rspec or minitest
minitest-rails-capybara to integrate both testing libraries with rails
minitest-reporters for test output customization including colorizing
guard for automated testing

-BDD(Behavior-Driven Developoment) is driven by feature tests and refines the product requirements and user experience.
-TDD(Test-Driven Development) is driven by unit tests and is more microscopic than BDD.TDD is good for refactoring code. 

PRY for debugging code from rails console. page 280 in Rails 4 Test Prescription for setup and gems
-the pry-rails gem allows it to become not only IRB replacement but, also Rails Console

-continuous integration (CI) which automatically runs tests whenever repository is updated common ones:
jenkins-ci.org, travis-ci.com, circleci.com

-FactoryGirl Gem is for generating factories or fixtures to populate a database with sample date.  A factory is an object that creates other objects.
-test doubles, 2 types: stubs and mocks. Stubs provide canned answers to calls made during the test, Mocks are pre-programmed objects that reproduce behavior of the object
-Capybara Gem for BDD, make sure to activate selenium driver if use javascript
-BDD process is complete when you can run rake test and see that every feature is implemented and functioning.

rake test		#runs all tests by default
rake test test/models/user_test.rb	#will just run this test
rake test:models	#runs all tests under test/models folder, in the past called unit tests
rake test:controllers	#runs all tests under test/controllers folder, previously called functional tests
__________________________________________________________________________________________

CONFIGURATION SECURITY:

config/secrets.yml	#set Unix environment variables in this file for secret passwords and API keys

-in ~ home directory open .bashrc or .bash_profile and enter in following environment variables
export GMAIL_USERNAME=“me@gmail.com”
export GMAIL_PASSWORD=“my password”
export MAILCHIMP_API_KEY=“my mailchimp api key”
export MAILCHIMP_LIST_ID=“your list ID”
export OWNER_EMAIL=“my@gmail.com”

-if your email/psw contains punctuation marks then put in single then double qoutes:
export GMAIL_PASSWORD=“‘my!&%password’”

-then in your config/secrets.yml file add the following environmental variables:(use spaces not tabs)(space after each colon and before the value for each entry)

development:
email_provider_username: <% = ENV[" GMAIL_USERNAME"] %>
email_provider_password: <% = ENV[" GMAIL_PASSWORD"] %> 
mailchimp_api_key: <% = ENV[" MAILCHIMP_API_KEY"] %> 
mailchimp_list_id: <% = ENV[" MAILCHIMP_LIST_ID"] %>
domain_name: example.com 			#this doesn’t need to be kept secret, thus not in variable 

owner_email: <% = ENV[" OWNER_EMAIL"] %>
secret_key_base: very_long_random_string 	#generated by the rails new command

test: 
secret_key_base: very_long_random_string 
# Do not keep production secrets in the repository, 
# instead read values from the environment. 
production: 
email_provider_username: <% = ENV[" GMAIL_USERNAME"] %> 
email_provider_password: <% = ENV[" GMAIL_PASSWORD"] %> 
mailchimp_api_key: <% = ENV[" MAILCHIMP_API_KEY"] %> 
mailchimp_list_id: <% = ENV[" MAILCHIMP_LIST_ID"] %> 
domain_name: <% = ENV[" DOMAIN_NAME"] %> 
owner_email: <% = ENV[" OWNER_EMAIL"] %> 
secret_key_base: <% = ENV[" SECRET_KEY_BASE"] %>

-if using unix environment variables in config/secrets.yml file there is no reason to add the file to .gitignore. 
-remember .yml files, indentation is required, use spaces not tabs, and space after each colon and before value of each entry.

__________________________________________________________________________________________

BEST GEMS:

chartkick	#charts gem
ActiveAdmin	#admin dashboard for rails
font-awesome	#works great with bootstrap
faker		#fake data generator for testing
brakeman	#security testing
rails-erd	#visual representation of database relationships
pry-rails
pry-byebug
pry-stack_explorer
pry-rescue
pry-debugger
better_errors
launchy		#errors from perspective of browser
high_voltage	#creating dynamic static pages in rails, use for about, contact, faq, legal, etc.
simpleform
Gibbon  	#wrapper for Mailchimp API
FactoryGirl	#testing
Capybara 	#BDD 
minitest-rails-capybara
minitest-reporters 	#for test output customization including colorizing
guard		#for automated testing
capistrano	#rails deployment

Rails Composer	#starter applications
OmniAuth	#sign in using facebook, twitter or github
devise		#authentication and authorization
pundit		#more advanced authorization
***use rails-devise-pundit starter application in rails composer
rails-signup-download #rails composer option to allow user to signup to download pdf file
rails-stripe-checkout #rails composer to process credit cards



BEST GEMS:


Gems to use for all applications:

source 'https://rubygems.org'
ruby "2.2.1"
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
gem "sqlite3", group: [:development, :test]
gem "pg",      group:  :production

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem "bootstrap-sass", "~> 3.3"
gem "font-awesome-rails", "~> 4.3"
gem "simple_form", "~> 3.1.0"
gem "devise", "~> 3.4.1"
gem "pundit", "~> 0.3.0"
gem "searcher", github: "radar/searcher"
gem "active_model_serializers", "~> 0.9.3"

gem "carrierwave", "~> 0.10.0"
gem "fog", "~> 1.29.0"
gems ‘gibbon’		#access to mailchimp API
gems ‘google_drive’	#access to google drive
gems ‘high_voltage’	#for static pages like “about”
gems ‘simple_form’	#forms made easy
gems ‘better_errors’	#helps with error messages
gems ‘quiet_assets’	#suppresses distracting messages in log files
gems ‘rails_layout’	#generates files for an application layout

gem "rails_12factor", group: :production
gem "puma", group: :production

gem 'twilio-ruby', '~> 4.9'

# gem "sinatra"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem "rspec-rails", "~> 3.2.1"
end

group :test do
  gem "capybara", "~> 2.4"
  gem "factory_girl_rails", "~> 4.5"
  gem "selenium-webdriver", "~> 2.45"
  gem "database_cleaner", "~> 1.4"
  gem "email_spec", "~> 1.6.0"
end

