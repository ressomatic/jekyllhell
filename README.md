NO, BAD README, BAD


Alright, so to start the blog on my PC:
1. do /bin/bash --login
2. do rvm 2.7
3. run bundle exec jekyll serve
4. try to run docker run docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve
5. append sudo to it because you always forget
6. run sudo docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve
7. ruby is missing gems. you've installed them a few times. install them again.
8. run sudo docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve. ruby is still missing the same gems.
9. I'm not restarting my computer for the nth time. Can I just, like, reload?
10. man I dunno, fine. restart.
11.  try to run docker run docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve
12.  oh shit the docker sock. dockerd. DOCKERD.
13.  no, sudo dockerd.
14.   try to run docker run docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve
15.   IT STILL TAKES FUC
16.   sudo docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4.0 bundle exec jekyll serve
17.   ruby is missing gems.
18.   sweet baby jesus.
