Useful git scripts

## Credits

Many of these scripts are a combination of hints and tricks I found online.


gitlog
-

```
gitlog [[switches]]
```

```switches```      Additional git log command line switches. This parameter is optional; will be passed to git log


gitgrep
-
```
gitgrep [regex] [[dir]] [[switches]]
```

```regex``` The regular expression to use in the grep

```dir```The root directory in which to run the git grep. This parameter is optional; default is './'.

```switches``` Additional git grep command line switches. This parameter is optional; will be passed to git grep.

