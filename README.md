# rememberscrolljs

## jquery.rememberscroll.js a jQuery plugin that remembers where user scrolls in a web page. When the user comes back to the page later, it automatically jumps to the most recent scroll position. <br />
### Author: Steve Tang<br />

### function 
 - $.scrollTrack(seconds,expiredays)<br />
 - the function can be called from a jQuery $(document).ready block
### parameters:<br />
 -    seconds: the frequency, i.e. in every this number of seconds the page scroll position will be queried, default is 2 seconds<br />
 -    expiredays: number of days cookies will be effective to store position data, default is 365 days<br />
### Usage examples:
 -  $.scrollTrack()<br />
 -  $.scrollTrack(1)<br />
 -  $.scrollTrack(1, 365*5)<br />
 
