# mutt and GPG

~~~shell
git clone https://github.com/tasmo/mutt-and-gpg $HOME/.mutt
~~~

I recommend to put mutt's config path in your environment:

~~~shell
echo "export MAILCONF='~/.mutt'" > $HOME/.profile && \
source $HOME/.profile
~~~
