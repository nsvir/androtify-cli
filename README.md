# Androtify-cli
Androtify sends a persistent notification to your Android phone from a shell script.

INSTALLATION
===========
|     CLIENT    |     CLOUD    | SERVER |
| ------------- | ------------ | ------ |
| [ShellScript] | Google cloud | [Flow] |

- Install the [flow] on your android device:
- `git clone https://github.com/nsvir/androtify.git androtify`
- `cd androtify`
- `echo DESTINATION_MAIL='your mail address' >> config`
- `echo SECRET='your secret key' >> config` [Documentation]
- `./androtify "My title" "Hello World!"`
- `./androtify --help`

USAGE
=====

```
> ./androtify
Usage: ./androtify				Remove the notification
Usage: ./androtify title		Only display a title
Usage: ./androtify title body	Display a title and a body
```

CONFIGURATION
=============

`./androtify` initialize the configuration file

DESTINATION_MAIL is the destination mail
SECRET is your secret key

More information here: https://llamalab.com/automate/cloud/

[Automate]: https://play.google.com/store/apps/details?id=com.llamalab.automate
[ShellScript]: https://github.com/nsvir/androtify
[Flow]: https://github.com/nsvir/androtify
[Documentation]: https://llamalab.com/automate/cloud/
