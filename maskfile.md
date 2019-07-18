# Tasks for my project

## valid \<b> \<other>

> `## valid \<b> \<other>`: It works fine thanks the backslashes.

~~~ sh
# It works fine.
echo "$b is not like the $other"
~~~

## invalid <b> <other>

> `## invalid <b> <other>`: No backslash, which means that
> `<b>` and `<other>` are mis-interpreted as HTML tags!

Not only is `<b>` not displayed, it also damages text formatting by
making all of the subsequent text bold.

Despite `<other>` not being a valid HTML tag, it is not displayed.

~~~ sh
# It still works.
echo "$b is not like the $other"
~~~
