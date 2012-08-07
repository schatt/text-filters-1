Text Filters
============

A few text filters for BBEdit/Text Wrangler

-------------

## perl-tidy


This filters either selected text or the entire document through perltidy:

 http://perltidy.sourceforge.net/
 
It currently uses the built in perl-best-practices style parameters. A full list of formatting options are available here:

 http://perltidy.sourceforge.net/perltidy.html#formatting_options
 
You will need to install the Perl::Tidy module from cpan:

```
$ cpan install Perl::Tidy

```

-------------

## wp-phptidy

This will clean up PHP code based on the WordPress coding standards:

 http://codex.wordpress.org/WordPress_Coding_Standards
 
The wp-phptidy.php script is available at:

 https://github.com/scribu/wp-phptidy
 
To install from the command line:

```
$ curl -C - -O https://raw.github.com/scribu/wp-phptidy/master/wp-phptidy.php

$ chmod 744 ./wp-phptidy.php

$ mv ./wp-phptidy.php /usr/local/bin
```
 
