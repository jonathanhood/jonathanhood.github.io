jonathanhood.github.io
======================

My github hosted personal site. This basically contains the output of the pelican site contained in my website repository. To
regenerate this site::

  > git clone https://github.com/jonathanhood/website
  > git clone https://github.com/jonathanhood/jonathanhood.github.io
  > cd website
  > git submodule init
  > git submodule update
  > make html
  > cp -R output/* ../jonathanhood.github.io
  > cd ../jonathanhood.github.io
  > git add .
  > git push
  
After about 10 minutes, jonathanhood.org will be updated with the latest content.
