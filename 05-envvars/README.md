1) Create an executable file that prints home and shell for the current user.
Example:
```
$ ./user_summary
Home: /root
Shell: /bin/ash
```

2) Set the environmental variable APPLICATION_VERSION to the version of
the project specified in the file ```composer.json```

Example:
```
$ source application_version
$ echo $APPLICATION_VERSION
1.3.1
```

Tips: env, jq, tr

More info about sourcing: http://mywiki.wooledge.org/BashGuide/Sourcing
