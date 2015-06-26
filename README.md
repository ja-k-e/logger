# logger
Good lookin’ logs

In action: http://codepen.io/jakealbaugh/pen/xGXXov

##usage
```
var log = new Logger();

log.info("Hey, here’s some ‘info’, the number 2 is equal to:", 2);
log.pass("Great Job! You ‘pass’!");
log.warn("Watch yourself. I will only ‘warn’ you once...");
log.fail("Woah, bro! Total ‘fail’! This following object is totally not what you were looking for.", { awesome: false } );
log.go("Let’s just ‘go’ with something a bit more basic.");
log.info([0,1,2,3,4,5], { more: 'data'} );
```
