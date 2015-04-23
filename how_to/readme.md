# About push of information
This is the repository of everithing appened to us.

## How to commit without generating push of information
 - do not start the commit summary with - (minus) or + (plus)

## How to create news with an image:
 - put the image into the correct folder /\<year\>/\<month\>
 - name the image as \<day\>_\<description\>.jpg
 - only jpg image are supported for now
 - push is done with commit, put + into commit summary
``` 
 + 
 pic(2015/04/23.jpg)
 fbmsg(test this is the fbmsg)
 twmsg(#test this is the twmsg)
 fblnk(http://www.develost.com)
``` 

## How to create news without image (currently disabled)
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

