SlidingMenu doc

if developing on the WTA fork of SlidingMenu:

< code changes, type type type >
git add whatever
git commit -m 'My message'
git pull
git pull jfeinstein10SlidingMenu master
git push

if just wanting to pull in his changes
git pull jfeinstein10SlidingMenu master
< conflicts >
git push
mvn clean deploy
