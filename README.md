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
  [https://hi098123.github.io/Data-Url-Viewer/#white#data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAQAAAAEACAYAAABccqhmAAAZU0lEQVR4Xu2d4XrkrA6Dv73/i97zZPZ02pkA8asokLbav2vAyLKwSTL9899///3975v8+/uXu/rnzx+0O2UNtMDAmPq6TdXztzfXjP2N9kH9dWE7mseJiRLDGXvsrbFlB8+qRR4rgaIBUdZwwUF9jQB4kHfGXImhZxfaLBGAN9ycZKAhUchDT9QZ+0sFQCO/zj4CEAGwsy8CYIf0sgkjABEAO7kiAHZIL5swAhABsJMrAmCH9LIJuwIwo1fs3kx2bu5pv6vc/Dr7cNf+tnlct/or96eweCUPFX9dcVLWpnx78Kr3FGAl8BREJ6mdc9GAjDCnmNC1FbF0rtGbayUPlSR0xUlZW4lHBOANtQjAnkY0CRUMIwDOlH+daxSPCEAE4JB5EYBDiJ4GqQDqWHUtKYjKiTPjPoGWZGkBzlcfBvqdmoJy99RixcGpABpARQCK7Bm8bkwFrr7ipyWtPpQ1nGN+vAAopy3t7yiIik+UWDMebVGfNlyVvdN4OBOEisZKoVb2PYO7NH7WCmAG4WaASJMtAqCkQ33MHWNe9/7TcsY+IgA3urjbXHGdUlSUUgGwFFXwZSvw9zVWHqgP/tD3AFY67Eq0UdLSEjUCQFOkbT/j5IwA7LGPABT5mxagCJRoFgEQgfsyTDkgIwBF3CMARaBEswiACFwEQLsJV9SSXr7QdmJGiTqiGW3vFAzpmJWYOEWf7luRA2WNVAA3ulBcSXblQlEhHB2zEpMIQEOG6CkxUjIXGRSf6NrKPlIB7BGguEcA6rUAxTZPAUwCR0lK+906Bc5ZUiFVCEfHUGzPIfA6OhWAKUFo70wThBJ384cSMRXA+dNcwT0CUJc0hdO5A8gdwBMBKqQK4eiYCEAE4IkAJc/oxKnDemxJE4dWRKMLOpogiq90jWPE9hbUr5 ... More Than 5 Times Long](https://hi098123.github.io/Data-Url-Viewer/#white#data:image/png;base64,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)
  
## layout
  like chrome
  
  background: #0e0e0e;
  
  and img on center
  
  or select white layout #white#data:image/png;base64,iVBORw0K...

# open source
  [download.js - dandavis](http://danml.com/download.html)

## I am use
  non server save and send file or viewing

## BUT!
  IE url max length is 2047.. it can't real data
  i will fix IE problem
