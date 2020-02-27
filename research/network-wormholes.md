---
layout: splash
title: "Network Wormholes"
classes: wide
date: 2020-02-11
tags: [social networks, strength of weak ties, twitter data, phone data, network wormholes]
excerpt: "Social Networks, Strength of Long Ties"
mathjax: "true"
---
{::comment}
Can put the following above to create a header image.
header:
  image: "/images/wormholes/singapore_wormholes.png"
{:/comment}


# Network Wormholes
![Singapore](/images/wormholes/singapore_wormholes.png){:class="img-responsive"}{:height="900px" width="700px"}

{{ fig_img | markdownify | remove: "

" | remove: "
" }} Singapore Twitter network colored by different language communities. Network wormholes overlaid in yellow lines.. 

{::comment}
<figure>
	<a href="https://science.sciencemag.org/content/362/6421/1410">
		<img src="/images/wormholes/singapore_wormholes.png" width="600">
	</a>
	<figcaption>Singapore Twitter network colored by different language communities. Network wormholes overlaid in yellow lines.</figcaption>
</figure>

{:/comment}

## Abstract
Long-range connections that span large social networks are widely assumed to be weak, composed of sporadic and emotionally distant relationships. However, researchers historically have lacked the population-scale network data needed to verify the predicted weakness. Using data from 11 culturally diverse population-scale networks on four continents—encompassing 56 million Twitter users and 58 million mobile phone subscribers—we find that long-range ties are nearly as strong as social ties embedded within a small circle of friends. These high-bandwidth connections have important implications for diffusion and social integration.

This work was published in [*Science*](https://science.sciencemag.org/content/362/6421/1410).
Here is a [short video](https://www.dropbox.com/s/t847u2lrwxsbt5e/scipak_strength_of_long_ties.mp4?dl=0) that explains the main findings.

## Dataset
For this study, I collected 158 million Twitter user accounts between 2013 and 2014 and constructed bidirected @mention networks in eight countries. The edgelists for these eight countries, with @mention frequency as weights, can be found in [Harvard Dataverse](https://doi.org/10.7910/DVN/NPRNCC).