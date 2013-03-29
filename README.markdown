# Predator Alert Tool for OkCupid

The Predator Alert Tool for OkCupid (PAT-OKC) is an add-on to your Web browser that alerts of you of any red flags for a given profile as you browse [OkCupid](https://en.wikipedia.org/wiki/OkCupid). A "red flag" is simply a public action taken by the given profile that is concerning, such as answering Match Questions in the same way an undetected rapist is statistically likely to answer them. For instance, given the following question, an answer of "Yes." would be alarming:

> Have you ever been in a situation where you tried, but for various reasons did not succeed, in having sexual intercourse with an adult by using or threatening to use physical force (twisting their arm, holding them down, etc.) if they did not cooperate?

This is not a hypothetical question, nor is the answer universally obvious. This is, in fact, the exact phrasing of a question used in a study called "Repeat Rape and Multiple Offending Among Undetected Rapists" by David Lisak and Paul M. Miller, published in Violence and Victims, Vol 17, No. 1, 2002 (Lisak and Miller 2002).

Tragically, *a statistically significant portion of respondents answered in the affirmative.* While much smaller than the portion of respondents who answered with a "no," the fact that some people blithely answered "yes" makes these questions worth asking up-front, to everyone, all the time. The Predator Alert Tool for OkCupid automates this process and issues warnings if its heuristics find a concerning match.

This early warning system can help OkCupid users make better informed choices about what measures they feel they need to take to remain safe while using the service.

## System requirements

The following software must be installed on your system before installing the Predator Alert Tool for OkCupid user script.

### Mozilla Firefox

If you use the [Mozilla Firefox](http://getfirefox.com/) web browser (version 12.0 or higher), ensure you have the [Greasemonkey extension](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) installed (at version 1.0 or higher).

### Google Chrome

If you use the [Google Chrome](https://chrome.google.com/) web browser (version 23 or higher), ensure you have the [Tampermonkey extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) installed.

## Installing

To install the Predator Alert Tool for OkCupid, go to [http://maybemaimed.com/playground/predator-alert-tool-for-okcupid/](http://maybemaimed.com/playground/predator-alert-tool-for-okcupid/) and click "[Download and install](https://userscripts.org/scripts/source/163064.user.js)" near the middle of the page:

> [Download and install Predator Alert Tool for OkCupid](https://userscripts.org/scripts/source/163064.user.js)

If you enjoy this script, please consider tossing a few metaphorical coins in [my cyberbusking hat](http://maybemaimed.com/cyberbusking/). :) Your donations are sincerely appreciated! Can't afford to part with any coin? It's cool. [Tweet your appreciation, instead](https://twitter.com/intent/tweet?text=Early+warning+of+tornados%3F+Check.+Want+an+early+warning+system+for+%23rape+%23culture%3F+http%3A%2F%2Fmaybemaimed.com%2Fplayground%2Fpredator-alert-tool-for-okcupid%2F+Predator+Alert+%23Tool+for+%40OkCupid.).

If [maybemaimed.com is censored](http://maybemaimed.com/where-im-censored/) where you are, you can alternatively go to [the Userscripts.org page for Predator Alert Tool for OkCupid](https://userscripts.org/scripts/show/163064) and click on "[Install](http://userscripts.org/scripts/source/163064.user.js)". If the tool is also unavailable there, you can alternatively [download PAT-OKC from GitHub.com](https://github.com/meitar/pat-okcupid/raw/master/okcupid-predator-alert-tool.user.js).

## Using

After installing the Predator Alert Tool for OkCupid (PAT-OKC), you will be presented with a welcome screen that describes the tool's use, its limitations, and provides links to helpful safety information.

![Screenshot of PAT-OKC welcome screen.](http://i.imgur.com/VlgRNj3.png)

Click on the "Go" button and you'll begin the installation questionnaire, modeled after the survey in Lisak and Miller's study, cited above. It'll look like this:

![Screenshot of PAT-OKC questionnaire.](http://i.imgur.com/rzuz7kj.png)

Complete the Match Questions in the PAT-OKC questionnaire just as you would an ordinary OkCupid question. When you submit your answer, you'll automatically be redirected to the next required question. You'll also be able to pause the questionnaire periodically and resume it later.

When you've completed all of the questions, you'll be presented with a pop-up box that offers a brief summary of how to use the Predator Alert Tool for OkCupid:

![Screenshot of PAT-OKC summary after completing its quesionnaire.](http://i.imgur.com/cbfoMvY.png)

If you encounter a profile on an OkCupid page whose behavior on the site is concerning, PAT-OKC will highlight links to that user's profile in a red, blocky outline. Viewing that user's OkCupid profile page will offer a full explanation of why that user's profile was red-flagged.

## Frequently Asked Questions

Before you report a new issue with the Predator Alert Tool for OkCupid (PAT-OKC), please check to ensure your question is not already addressed in the list below.

* [Where can I learn more about this issue?](#where-can-i-learn-more-about-this-issue)

### Where can I learn more about this issue?

The following articles are important reads that offer additional background and context for this issue:

* [Meet The Predators](https://yesmeansyesblog.wordpress.com/2009/11/12/meet-the-predators/)
* [Tracking rape culture's social license to operate online](http://maybemaimed.com/2012/12/21/tracking-rape-cultures-social-license-to-operate-online/)
* [Help dating websites' Rape Culture FAADE Away](http://days.maybemaimed.com/post/39785638940/last-october-i-introduced-the-fetlife-alleged)

Each of the pages listed above also contain numerous additional links. I'd recommend reading them, too.

## Change log

* Version 0.2.1:
    * First public release.
* Version 0.2:
    * Initial orientation path and installation quesionnaire.
* Version 0.1:
    * Initial working prototype.