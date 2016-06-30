# weinre-headstart
Weinre - Headstart

WEb INspector REmote

See https://www.npmjs.com/package/weinre

weinre is WEb INspector REmote. Pronounced like the word "winery". Or maybe like the word "weiner". Who knows, really.

weinre is a debugger for web pages, like FireBug (for FireFox) and Web Inspector (for WebKit-based browsers), except it's designed to work remotely, and in particular, to allow you debug web pages on a mobile device such as a phone.

TRY IT ON https://tonicdev.com/

Based on:

The Book 'JavaScript Promgramming - Pushing the Limits'
Chapter 1: Best practices, page 15 Weinre

Start the Weinre Server as follows:

weinre --boundHost -all-

Finally, you need to add a script tag to your test page, to set it up as a debug target:

<script src="http://1.2.3:8080/target/target-script-min.js"></script>

Here, replace http://1.2.3:8080/ with the location of your local Weinre server (which is running off your desktop machine).

With Weinre set up, you can simply open the page on the mobile device you want to test (or whichever desktop browser you want to test). Then open Chrome on your desktop machine and visit http://localhost:8080/client.

If all goes well, you should see two green IP addresses, one for the remote target (the mobile device) and one for the remote client (the desktop machine). 
