# Tasks for my project

Click on **Raw** to see the source file.

## invalid <b> <other>

> `## invalid <b> <other>`

`<b>` and `<other>` are mis-interpreted as HTML tags!

Not only is `<b>` not displayed, it also damages text formatting by
making subsequent text bold.

Despite `<other>` not being a valid HTML tag, it is not displayed.

~~~ sh
# It works.
echo "$b is not like the $other"
~~~

## valid \<b> \<other>

> `## valid \<b> \<other>

~~~ sh
# It works.
echo "$b is not like the $other"
~~~

## underscore <arg_with_underscores>

> `## underscore <arg_with_underscores>`

As a side note, arguments with underscores don't seem to be interpreted as HTML tags.

~~~ sh
echo "$arg_with_underscores"
~~~
