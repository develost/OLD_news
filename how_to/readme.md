# About push of information
This is the repository of everithing appened to us.

## How to commit without generating push of information
 - do not start the commit summary with - (minus) or + (plus)

## How to create news with an image:
 - put the image into the correct folder /\<year\>/\<month\>
 - name the image as \<day\>_\<description\>.jpg
 - only jpg image are supported for now
 - push is done with commit, start with +
 - body with text message
 - url with image url
 
```
 + body(a message with #test hash) url(https://raw.githubusercontent.com/develost/news/master/2015/04/13_first prerelease_version_websu.jpg)
``` 

## How to create news without image
 - put an MD file into the correct folder, describing if you want what is appened
 - the correct folder is /\<year\>/\<month\> 
 - name of the textfile il \<day\>_\<description\>.md
 - you can use markdown formatting if you want
 - push is done with commit, start with -
 - body with text message, include link to the md file if desidered

```
 - body(test a message with #test hash)
 - body(this is a #test url https://github.com/develost/news/blob/master/how_to/readme.md) 
```

