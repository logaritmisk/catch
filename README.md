# Catch

Sometimes you want to highlight some information in a stream of data, and there is no easy way doing that.

You can grep, but what if you want to see everything, not only the thing you grep on.

Catch solves this!


**Tested on:**

- Mac OS X 10.7.4 (Lion)


## Usage

    cat /var/log/syslog | catch 'foobar'

Will highlight foobar in green

    cat /var/log/syslog | catch 'foobar' '(.*)'

Will highlight all lines that contains 'foobar'



## Todo

* Test on Ubuntu
* Better README
* Change color