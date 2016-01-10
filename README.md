# MacOS_Notify

## Description

Simple script to dispatch messages to MacOS Notification Center.

It uses AppleScript to interact with the Notification Center.

The first argument is the title of the notification, and the second one the content of the message to dispatch.

[More information](http://xaviertorello.cat/#portfolio "Xavier Torelló Porfolio")



## How it works?

Call notify script with the title and the content of the message:

```
notify.sh "title" "text"
```

//Remember to add quotes to each argument if you need to use sentences with spaces



## How to install it?

1. Download [notify.sh]( "MacOS Notify script") and save it wherever you want. 

  * It's recommended to deploy it inside the $PATH to ensure high usability, `/usr/local/bin` by default.

2. Set execution grants to ensure quick execution `chmod +x notify.sh`

  * Alternative: call it via `bash notify.sh "title" "text"`



## License

GPL v3 or later



## Support

Please direct any feedback to [Xavier Torelló](http://xaviertorello.cat "Xavier Torelló") [http://xaviertorello.cat/#contact]
