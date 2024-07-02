[Go Back to Mastoget](https://mastoget.x10.bz)  

# About Mastoget

Mastoget is your feed retriever for the Mastodon network. This amazing site feeds all the public posts posted across the entire Mastodon network to your web browser.
<br><br>
Mastoget can retrieve 10 randomly selected Mastodon-servers at a time; this is to avoid overloading this site's servers as every visitor visit means an individual request to these Mastodon instances. 
<br><br>
We use relays and processors so that the entire Mastoget system will not fall when the traffic boosts up and to avoid downtimes.


[Mastodon Profile](https://mastodon.social/@mastoget)  <br>
[Github Profile](https://github.com/The-Mastoget-Organization/)  <br>
[Source Code](https://github.com/The-Mastoget-Organization/source)  <br>
[Privacy Policy](https://github.com/The-Mastoget-Organization/privacypolicy)<br>
[Terms of Service](https://github.com/The-Mastoget-Organization/termsofservice)<br>
[Mastodon Servers/Instances List](https://github.com/The-Mastoget-Organization/servers-list)<br>
[Bug/Issue Reporting](https://github.com/The-Mastoget-Organization/about/issues)

## Redirector
Used to redirect main indexed traffic to the main processor or to the emergency processor.<br>
✓Mastoget - x10 Hosting

## Main Processor
It gathers the data from a relay.<br>
✓Mastogetprocessor - Vercel

## Emergency Processor
In case that the main processor is down, a processor located on the same server as the redirector. Its performance was not great but atleast its there to make sure that our system will avoid downtimes.<br>
✓Mastoget (Emergency.PHP) - x10 Hosting

## Current Active Relays
It gathers the data from various Mastodon servers.<br>
✓Masget1 - x10 Hosting<br>
✓Masget2 - x10 Hosting<br>
✓Masget3 - x10 Hosting<br>
✓Masget4 - x10 Hosting<br>
✓Masget5 - Vercel<br>
✓Masget6 - Vercel<br>
✓Masget7 - Vercel<br>
✓Masget8 - Vercel

## Content Delivery Network 
It is used for delivering vital assets like the Mastoget logo, Favicons, and Vital Files.<br>
✓Cloudinary


## Check First before Redirect Technology
This technology does check first if the relay or processor is up before redirecting thus avoiding the user to land into an error page.<br><br>
Important Note: As of the moment, it is only implemented on the redirector level, so that if Vercel is down it will not be used anymore and will rely on an emergency processor. The implementation of the said technology in the processor level is still under development.

&copy; The Mastoget Organization. All Rights Reserved.

