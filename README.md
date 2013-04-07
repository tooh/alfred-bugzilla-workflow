#Alfred workflow for Bugzilla

## Install

For now I distribute the workflow as a .alfredworkflow zip file.
Download the zip, expand it and Install the workflow as usual.

## Setup

The workflow needs some configuration.

1. In this version the URI is configured for the Mozilla Bugzilla server. This must be changed if you use your own server.
2. The workflow uses the Bugzilla XMLRPC webservices. You have to supply your username and password. This has to be configured in the supplied perl script.


    my $Bugzilla_uri= "http:///bugzilla.mozilla.org/xmlrpc.cgi";
    my $Bugzilla_login = "";                # your account
    my $Bugzilla_password = "";             # your password
    my $Bugzilla_remember = 1;


## Bug tracker

Have a bug or a feature request? Please open a new issue. Before opening any issue, please search for existing issues and read the [Issue Guidelines](https://github.com/necolas/issue-guidelines), written by [Nicolas Gallagher](https://github.com/necolas/).

## Author

**Peter Florijn**

+ [http://twitter.com/peterflorijn](http://twitter.com/peterflorijn)
+ [http://github.com/tooh](http://github.com/tooh)


## Copyright and license

