# Data Url To Img Viewer

## How can I use
  just add #data:image/png;base64,iVBORw0KGgoAAAANSU ...
  
  like
  https://hi098123.github.io/Data-Url-Viewer/#data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==
  
## Why not use param '?'
  becuase ?data= ... can go server and response (if uri too long server can response ERROR)
  just use # is html > id content
  '#' can processing client side
  
  like
  [... More Than 3 Times Long]()
  
## layout
  like chrome
  
  background: #0e0e0e;
  
  and img on center
  or select white layout #white#data:image/png;base64,iVBORw0K...

# open source
  download.js - dandavis

## I am use
  non server save and send file or viewing

## BUT!
  IE url max length is 2047.. it can't real data
  i will find IE problem
