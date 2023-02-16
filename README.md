# sb-gops-module3
sb-gops-module3 has sb-gops-module1 as submodule

add a submodule
~~~
git submodule add -b main https://github.com/sandbox-gitops/sb-gops-module1.git path/to/other

git add .gitmodules  path/

git commit -am "added submodule"
~~~

clone this project
~~~
~~~

check status from submodules
~~~
git submodule foreach git status
~~~
