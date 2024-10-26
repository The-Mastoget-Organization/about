[Go Back to Mastoget](https://mastoget.x10.bz)  

# About Mastoget

Mastoget is your decentralized feed retriever for the Mastodon network. This amazing site feeds all the public posts posted across the entire Mastodon network to your web browser.
<br><br>
Mastoget can retrieve randomly selected Mastodon-instances (CURRENTLY 6) at a time this is to avoid overloading this site's servers (and unstable instances causes Mastoget to blank out) as every visitor visit means an individual request to these Mastodon instances. 
<br><br>
We use relays and processors so that the entire Mastoget system will not fall when the traffic boosts up and to avoid downtimes.

<br><br>
[About Mastoget](https://github.com/The-Mastoget-Organization/about)  <br>
[Mastodon Profile](https://mastodon.social/@mastoget)  <br>
[Github Profile](https://github.com/The-Mastoget-Organization/)  <br>
[Source Code](https://github.com/The-Mastoget-Organization/source)  <br>
[Privacy Policy](https://github.com/The-Mastoget-Organization/privacypolicy)<br>
[Terms of Service](https://github.com/The-Mastoget-Organization/termsofservice)<br>
[Mastodon Instances List](https://github.com/The-Mastoget-Organization/servers-list)<br>
[Bug/Issue Reporting](https://github.com/The-Mastoget-Organization/about/issues)<br><br>  


# Decentralization (PARTIALLY CANCELLED)
We ae still commited to the decentralization but it is now decentralization on Vercel nodes that Mastoget is hosted on.

## Redirector
Used to redirect main indexed traffic to the main processors or to the emergency processor.<br>
✓Mastoget - Vercel

## Main Processors
It gathers the data from a relay.<br>
✓Mastogetprocessor - Vercel<br>
✓Getmasprocessor - Vercel<br>
✓Masgetprocessor - Vercel<br>
✓Mastoprocessor - Vercel

## Emergency Processor
In case that the main processors are down, a processor located on the same server as the redirector. Its performance was not great but atleast its there to make sure that our system will avoid downtimes.<br>
✓Mastoget/Fallback - Vercel

## Current Active Relays
It gathers the data from various Mastodon instances.<br>
✓Masget1Vercel - Vercel<br>
✓Masget2Vercel - Vercel<br>
✓Masget3Vercel - Vercel<br>
✓Masget4Vercel - Vercel<br>
✓Masget5Vercel - Vercel<br>
✓Masget6Vercel - Vercel<br>
✓Masget7Vercel - Vercel<br>
✓Masget8Vercel - Vercel<br>
✓Masget9Vercel - Vercel<br>
✓Masget10Vercel - Vercel<br>
✓Masget11Vercel - Vercel<

## Content Delivery Network 
It is used for delivering vital assets like the Mastoget logo, Favicons, and Vital Files.<br>
✓Cloudinary

### Check First before Redirect Technique
This technique does first check if the relay or the processor is up before redirecting thus avoiding the user to land into an error page.

### Contact Information
As of the moment, TheDoggyBrad Software Labs handles the communications for Mastoget. You may reach him via email at admin@gosocial.x10.bz.
<br><br>
&copy; The Mastoget Organization. All Rights Reserved.

