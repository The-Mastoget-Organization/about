[Go Back to Mastoget](https://mastoget.x10.bz)  

# About Mastoget

Mastoget is your decentralized feed retriever for the Mastodon network. This amazing site feeds all the public posts posted across the entire Mastodon network to your web browser.
<br><br>
Mastoget can retrieve 20 randomly selected Mastodon-instances at a time this is to avoid overloading this site's servers (despite we are expanding our systems) as every visitor visit means an individual request to these Mastodon instances. 
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


# Decentralization
Since June 2024, we started the path of making Mastoget decentralized that it will not depend on a single server nor a single site and it is still ongoing and growing...

## Redirector
Used to redirect main indexed traffic to the main processors or to the emergency processor.<br>
✓Mastoget - x10 Hosting

## Main Processors
It gathers the data from a relay.<br>
✓Mastogetprocessor - Vercel<br>
✓Getmasprocessor - Vercel<br>
✓Masgetprocessor - Vercel<br>
✓Mastoprocessor - Vercel

## Emergency Processor
In case that the main processors are down, a processor located on the same server as the redirector. Its performance was not great but atleast its there to make sure that our system will avoid downtimes.<br>
✓Mastoget (Emergency.PHP) - x10 Hosting

## Current Active Relays
It gathers the data from various Mastodon instances.<br>
✓Masget1LibreSpeedx10 - x10 Hosting<br>
✓Masget2LibreSpeedx10 - x10 Hosting<br>
✓Masget3Mastogetrelayx10 - x10 Hosting<br>
✓Masget4Mastogetrelayx10 - x10 Hosting<br>
✓Masget5Vercel - Vercel<br>
✓Masget6Vercel - Vercel<br>
✓Masget7Vercel - Vercel<br>
✓Masget8Vercel - Vercel<br>
✓Masget9Vercel - Vercel<br>
✓Masget10Vercel - Vercel<br>
✓Mastogetrelayx10(11) - x10 Hosting

## Instances Selector
This randomly selects the instances that each relays will load. It is refreshed every 10 minutes.<br>
✓Generator1.PHP / Instances1.XML / Cron-job.org<br>
✓Generator2.PHP / Instances2.XML / Cron-job.org<br>
✓Generator3.PHP / Instances3.XML / Cron-job.org<br>
✓Generator4.PHP / Instances4.XML / Cron-job.org<br>
✓Generator5.PHP / Instances5.XML / Cron-job.org<br>
✓Generator6.PHP / Instances6.XML / Cron-job.org<br>
✓Generator7.PHP / Instances7.XML / Cron-job.org<br>
✓Generator8.PHP / Instances8.XML / Cron-job.org<br>
✓Generator9.PHP / Instances9.XML / Cron-job.org<br>
✓Generator10.PHP / Instances10.XML / Cron-job.org<br>

## Critical Relay (Processor Bypass)
This relay is only used when big subsets of active relays are down. This bypasses the selection of relays.<br>
✓Mastoget-Critical - x10 Hosting

## Content Delivery Network 
It is used for delivering vital assets like the Mastoget logo, Favicons, and Vital Files.<br>
✓Cloudinary

### Check First before Redirect Technique
This technique does first check if the relay or the processor is up before redirecting thus avoiding the user to land into an error page.

### Contact Information
As of the moment, TheDoggyBrad Software Labs handles the communications for Mastoget. You may reach him via email at admin@gosocial.x10.bz.
<br><br>
&copy; The Mastoget Organization. All Rights Reserved.

