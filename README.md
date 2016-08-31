# Androtify-cli
Androtify sends a persistent notification to your Android phone from a shell script.

INSTALLATION
===========
|       SHELL     |     CLOUD    |       ANDROID       |
| --------------- | ------------ | ------------------- |
| [Androtify-cli] | Google cloud |   [Androtify-flow]  |

- Install the [Flow] on your android device and run it.
- `git clone https://github.com/nsvir/androtify.git androtify`
- `cd androtify`
- `echo DESTINATION_MAIL='your mail address' >> config` [What is my mail address ?] [Documentation]
- `echo SECRET='your secret key' >> config` [Where is my secret key ?] [Documentation]
- `./androtify "My title" "Hello World!"`
- `./androtify --help`

USAGE
=====

```
> ./androtify --help
Usage: ./androtify				Remove the notification
Usage: ./androtify title		Only display a title
Usage: ./androtify title body	Display a title and a body
```

CONFIGURATION
=============

`rm -f config; ./androtify` re/initialize the configuration file

DESTINATION_MAIL is the destination mail
SECRET is your secret key

More information here: https://llamalab.com/automate/cloud/

[Automate]: https://play.google.com/store/apps/details?id=com.llamalab.automate
[Androtify-cli]: https://github.com/nsvir/androtify-cli#androtify-cli
[Androtify-flow]: https://github.com/nsvir/androtify-flow#androtify-flow
[Flow]: https://github.com/nsvir/androtify-flow#androtify-flow
[Documentation]: https://llamalab.com/automate/cloud/

HELP
====
n.svirchevsky@gmail.com
https://llamalab.com/automate/

AUTOR
=====
Nicolas Svirchevsky n.svirchevsky@gmail.com
