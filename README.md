# sb-gops-module3
sb-gops-module3 has sb-gops-module1 as submodule

add a submodule
~~~
git submodule add -b main https://github.com/sandbox-gitops/sb-gops-module1.git path/to/other

git add .gitmodules  path/

git commit -am "added submodule"
~~~

clone this project and init submodule
~~~
git clone https://github.com/sandbox-gitops/sb-gops-module3.git

git submodule update --init --recursive
~~~
or
~~~
git clone --recurse-submodules https://github.com/sandbox-gitops/sb-gops-module3.git
~~~

show also submodule diff/status
~~~
git config diff.submodule log
git  diff

git config status.submodulesummary 1
git status
~~~

check status from submodules
~~~
git submodule foreach git status
~~~
