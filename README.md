# A brief history of the modern Web Platform

## 2004-02

- [CSS 2.1 Candidate Recommendation (CR)](http://www.w3.org/TR/2004/CR-CSS21-20040225/)
  published; the spec will later go back to normal Working Draft status for
  a time before returning again to CR in July 2007, and then be published
  as a final W3C Recommendation in June 2011.

- [Safari 1.2](http://weblogs.mozillazine.org/hyatt/archives/2004_02.html#004874)
  released; notable in that it's the first version of Safari with
  XMLHttpRequest (XHR) support (following Internet Explorer and Firefox).

- [Flickr launched](http://en.wikipedia.org/wiki/Flickr); making
  innovative use of XHR and client-side browser technologies to drive its
  user interface, adding
  ["tagging" features inspired by del.icio.us](http://en.wikipedia.org/wiki/Tag_%28metadata%29#History),
  and eventually moving to provide APIs to expose Flickr for data using in
  other sites and Web applications, it will go on to be often cited as a
  key example of a "Web 2.0" site/service.

- [Gmail launched](http://en.wikipedia.org/wiki/Gmail)
  in invitation-only beta, and
  [Facebook launched](http://en.wikipedia.org/wiki/Timeline_of_Facebook#2004),
  with membership initially restricted to students of Harvard University.

## 2004-04

- [Web Applications 1.0 first public draft published](http://www.hixie.ch/specs/html/apps/web-apps-1)
  (the document that will eventually become the HTML5 spec).

  The publication of the Web Applications 1.0 first draft follows a couple
  of blog postings from Ian Hickson earlier in the year, 
  [Ramblings from the North](http://ln.hixie.ch/?start=1080506019&count=1)
  and
  [Void filling: Web Applications Language](http://ln.hixie.ch/?start=1074466808&count=1),
  in which Hickson writes:

  > About 11 months ago, I mentioned that the W3C had so far failed to
  > address a need in the Web community: There is no language for Web
  > applications[...] I've been taking the opportunity to work on a
  > proposal for a Web Applications specification[...] something along the
  > same lines as Web Forms 2, but specifically for client-side application
  > development.

  In the following month, Hickson writes a related 
  [Backwards Compatibility](http://ln.hixie.ch/?start=1085764602&count=1)
  blog posting in which is gives some more detail about the rationale
  behind the Web Applications 1.0 spec:

  > Authors still want to write Web applications, and the currently
  > deployed standards are inadequate. Since completely new standards won't
  > cut it [...] this leaves us with the solution we (Opera and Mozilla)
  > have been advocating: updating HTML and the DOM.

## 2004-06

- [WHATWG launched](http://www.whatwg.org/news/start); announcement:

  > The group aims to develop specifications based on HTML and related
  > technologies to ease the deployment of interoperable Web Applications
  > [...] for implementation in mass-market Web browsers, in particular
  > Safari, Mozilla, and Opera; [the group] intends to ensure that all its
  > specifications address backwards compatibility concerns [...] and
  > specify error handling behavior to ensure interoperability even in the
  > face of documents that do not comply to the letter of the
  > specifications.

  The announcement of the launch of the WHATWG follows just after a
  [W3C Workshop on Web Applications and Compound Documents](http://www.w3.org/2004/04/webapps-cdf-ws/)
  held at Adobe offices in San Jose. For the workshop, Opera and Mozilla
  jointly submit and present a position paper with a set of proposed
  [Design Principles for Web Application Technologies](http://www.w3.org/2004/04/webapps-cdf-ws/papers/opera.html);
  but some
  [subsequent blog postings](http://www.w3.org/html/wg/wiki/2004WebAppsWorkshop/reactions)
  from Brendan Eich, David Baron, and Ian Hickson make it clear that they've
  come away from the workshop with a realization that their goals with respect
  to Web applications are not in sync with others in attendance. Brendan Eich:

  > The dream of a new web, based on XHTML+SVG+SMIL+XForms, is just that --
  > a dream. It won't come true no matter how many toy implementations
  > there are[...] The best way to help the Web is to incrementally improve
  > the existing web standards, with compatibility shims provided for IE,
  > so that web content authors can actually deploy new formats
  > interoperably[...] Mozilla is joining with Opera and others to explore
  > the sort of incremental improvements to HTML proposed by us at the
  > workshop.

## 2004-07 to 2005-02

- [HTML `canvas` element created by the Safari team at Apple](http://ln.hixie.ch/?start=1089635050&count=1)
  and
  [first specified as part of Web Applications 1.0](http://web.archive.org/web/20041009144718/http://whatwg.org/specs/web-apps/current-work/).

- [Web 2.0 Conference](http://web.archive.org/web/20041001091530/www.web2con.com/pub/w/32/program.html)
  first takes place in San Francisco, eventually causing the term <i>Web 2.0</i>
  to be brought into general use.

- [Google Suggest](http://labs.google.com/suggestfaq.html)
  and 
  [Google Maps launched](http://en.wikipedia.org/wiki/Google_maps#Development_history)
  in beta with support across all major browsers (Internet Explorer, Mozilla,
  Opera, and Safari).

- [Ajax: A New Approach to Web Applications](http://www.adaptivepath.com/ideas/essays/archives/000385.php)
  by Jesse James Garrett (coining the term <i>Ajax</i> to describe the use
  of XHR in modern Web applications).

## 2005-03 to 2005-05

- [Cross-document messaging (`postMessage`)](http://web.archive.org/web/20050301091946/http://whatwg.org/specs/web-apps/current-work/)
  first specified, as part of Web Applications 1.0.

- [Acid2](http://en.wikipedia.org/wiki/Acid2) published as a means to test
  the level of standards conformance in Web browsers.

- [Opera 8](http://en.wikipedia.org/wiki/History_of_the_Opera_web_browser#Version_8)
  released; notable in that it is the first release version of Opera with
  (limited) XHR support.

- [The Web Platform - Browsers and Applications](http://www.w3.org/2005/Talks/0513-webplatform/)
  talk presented by Dean Jackson in the W3C track at WWW2005, with the
  goals of the "Web Platform" outlined as:

  * To (better) enable the Web as an application platform (on all devices)
  * To help users by requiring support for standards in the browser.
  * To give Web developers a better programming environment (with new
    interfaces).

  During the rest of 2005 and after, the term "the Web Platform" will see
  increasing use, specifically for the standard set of client-side browser
  technologies available for building modern Web applications.

## 2005-07 to 2005-11

- [`<!DOCTYPE html>` (HTML5 doctype) first introduced](http://web.archive.org/web/20050701075402/http://www.whatwg.org/specs/web-apps/current-work/).

- [Client-side local storage](http://www.whatwg.org/specs/web-apps/2005-09-01/)
  first specified, as part of Web Applications 1.0.

- [del.icio.us begins providing a REST API that makes data available in JSON](http://inkdroid.org/journal/2005/09/21/delicious-json/);
  within the next three years, Flickr, Yahoo, Google, and most other major
  providers of Web-based services begin to provide APIs that expose data
  formatted in JSON.

- [What Is Web 2.0](http://www.oreillynet.com/pub/a/oreilly/tim/news/2005/09/30/what-is-web-20.html)
  article by Tim O'Reilly. Subsequent discussions of the term
  <i>Web 2.0</i> often cite this article; excerpt:

  > It's clear that standards and solutions [...] will enable the next
  > generation of applications. [...] AJAX is also a key component of Web
  > 2.0 applications such as Flickr[...] We're entering an unprecedented
  > period of user interface innovation, as web developers are finally able
  > to build web applications as rich as local PC-based applications.

- [Web API](http://www.w3.org/2006/webapi/) and
  [Web Application Formats](http://www.w3.org/2006/appformats/)
  Working Groups chartered at the launch of the W3C
  [Rich Web Client Activity](http://www.w3.org/News/2005#x200501115c).

## 2006-01 to 2006-02

- [Firebug](https://addons.mozilla.org/en-US/firefox/addon/firebug/versions/?page=5#version-0.2)
  first version released.

- [Opera Mini](http://en.wikipedia.org/wiki/Opera_Mini)
  released; it will play a role in expanding Web access to more parts of
  the world, and will end up consistently accounting for a significant
  percentage of worldwide mobile Web-browsing traffic.

- [JSON Internet Draft published](http://ietfreport.isoc.org/all-ids/draft-crockford-jsonorg-json-00.txt)
  by Doug Crockford; however, it had already been documented by Crockford
  elsewhere going back to at least late 2002, and a number of major
  Web-based services had already started to provide APIs that exposed data
  formatted in JSON.

- [HTML parsing algorithm](http://web.archive.org/web/20060202011253/http://whatwg.org/specs/web-apps/current-work/)
  first specified, as part of Web Applications 1.0.

## 2006-07 to 2006-11

- [Twitter launched](http://techcrunch.com/2006/07/15/is-twttr-interesting/)
  and
  [Facebook opened](http://en.wikipedia.org/wiki/Timeline_of_Facebook#2006)
  widely for all users to join.

- [jQuery 1.0](http://blog.jquery.com/2006/08/26/jquery-10/) released.

- [Internet Explorer version 7](http://en.wikipedia.org/wiki/Internet_Explorer#Version_7)
  released with CSS and DOM improvements -- five years after the release of IE6.

- [Reinventing HTML](http://dig.csail.mit.edu/breadcrumbs/node/166)
  posting by Tim Berners-Lee:

  > Some things are clearer with hindsight of several years. It is
  > necessary to evolve HTML incrementally. The attempt to get the world to
  > switch to XML, including quotes around attribute values and slashes in
  > empty tags and namespaces all at once didn't work[...] The plan is to
  > charter a completely new HTML group. Unlike the previous one, this one
  > will be chartered to do incremental improvements to HTML, as also in
  > parallel xHTML.

- [Proposed charter](http://lists.w3.org/Archives/Public/www-archive/2006Nov/0045.html)
  for HTML Working group posted by Ian Hickson (following
  [the earlier posting of shorter proposed charter](http://lists.w3.org/Archives/Public/www-archive/2006Nov/0000.html),
  [specific feedback](http://lists.w3.org/Archives/Public/www-archive/2006Nov/0000.html)
  and some
  [public discussion about charter review](http://lists.w3.org/Archives/Public/www-archive/2006Nov/thread.html#msg53)).

## 2007-03 to 2007-05

- [Fifth W3C HTML Working Group](http://www.w3.org/2007/03/HTML-WG-charter.html)
  chartered (though only the second W3C HTML working group to focus on the core
  HTML language), with a mission <i>to continue the evolution of HTML (including
  classic HTML and XML syntaxes)</i> and with a statement that <i>this group
  will maintain and produce incremental revisions to the HTML specification [to
  produce] a language evolved from HTML4 for describing the semantics of
  documents and applications on the World Wide Web.</i>

- [`video` and `audio` elements added to the HTML spec](http://html5.org/r/394-699).

- [Google Gears](http://gearsblog.blogspot.com/2007/05/posted-by-aaron-boodman-and-erik.html)
  released; some of its key features eventually become standard parts of
  the Web platform, and by the end of 2009 its development will end up
  being permanently halted.

## 2007-06

- [iPhone](http://en.wikipedia.org/wiki/History_of_the_iPhone#World_timeline)
  first released; notable among other things in that it doesn't include
  support for Adobe Flash, it will end up consistently accounting for
  significantly more mobile Web-browsing traffic than any other mobile
  device.

## 2007-10 to 2007-12

- [HTML "offline Web applications" feature introduced](http://html5.org/tools/web-apps-tracker?from=848&to=1115)
  (`applicationCache` interface, <i>aka</i> appCache)

- [CSS Transforms](https://www.webkit.org/blog/130/css-transforms/) 
  (`transform-*` properties) and [CSS Transitions](https://www.webkit.org/blog/138/css-animation/)
  (`transition-*` properties) created by the Safari team at Apple.

- [Downloadable-fonts support added to WebKit](https://www.webkit.org/blog/124/downloadable-fonts/);
  (`@font-face` rule). Eventually, by mid-2009, downloadable fonts will be
  supported in all major browsers. (Note that Internet Explorer was the
  first to have downloadable-fonts support, starting with the release of
  IE4 in 1997 -- and the feature had actually been part of the CSS2.0
  Recommendation published in 1998.)

- [Futhark JavaScript engine released in beta](http://my.opera.com/desktopteam/blog/2007/10/25/opera-9-5-beta-released)
  as part of Opera 9.5; for a time it will be the fastest JavaScript engine
  on the market, and help to initiate a JavaScript-engine performance race
  among browser projects, starting in mid-2008.

- [SunSpider JavaScript benchmark introduced](https://www.webkit.org/blog/152/announcing-sunspider-09/)
  by the Safari team at Apple; during the latter half of 2008 and after, it
  will become widely used by other major browser projects in documenting
  the relative performance improvements in their JavaScript engines.

## 2008-01 to 2008-07

- [First W3C Working Draft of HTML5 published](http://www.w3.org/News/2008.html#entry-6935).

- [Acid3](http://en.wikipedia.org/wiki/Acid3)
  published as a means to test the level of standards conformance in Web
  browsers.

- [SquirrelFish JavaScript engine announced](https://www.webkit.org/blog/189/announcing-squirrelfish/)
  by the Safari team at Apple (an incremental rewrite of the "JavaScriptCore"
  engine to turn it into a bytecode interpreter, resulting in large
  performance improvements); during the following months, browser projects
  rewrite their JavaScript engines in a race to improve performance.

- [Web Sockets and Web Workers](http://html5.org/tools/web-apps-tracker?from=1835&to=1968)
  first specified.

## 2009-02 to 2009-03

- [CSS Animations created by the Safari team at Apple](https://www.webkit.org/blog/324/css-animation-2/)
  (`@keyframes` rule and `animation-*` properties).

- [Internet Explorer version 8](http://en.wikipedia.org/wiki/Internet_Explorer#Windows_Internet_Explorer_8)
  released; it is the first version of IE to pass [Acid2](http://en.wikipedia.org/wiki/Acid2).

## 2010-02

- [Google Gears development officially stopped](http://gearsblog.blogspot.com/2010/02/hello-html5.html)
  by the Gears team at Google, following a gradual shift "towards bringing
  all of the Gears capabilities into web standards like HTML5".

## 2010-04

- [Steve Jobs "Thoughts on Flash"](http://www.apple.com/hotnews/thoughts-on-flash/);
  excerpt:

  > [...] the mobile era is about low power devices, touch interfaces and
  > open web standards – all areas where Flash falls short[‥.] Rather than
  > use Flash, Apple has adopted HTML5, CSS and JavaScript – all open
  > standards[...] Perhaps Adobe should focus more on creating great HTML5
  > tools for the future, and less on criticizing Apple for leaving the
  > past behind.

## 2011-03

- [Internet Explorer version 9](http://en.wikipedia.org/wiki/Internet_Explorer_9)
  released, with major improvements in standards support (including
  support for SVG and the HTML `canvas` and `video` elements).

- [Video conferencing and peer-to-peer communication](http://html5.org/tools/web-apps-tracker?from=5944&to=5945)
  section added to the WHATWG HTML spec by Ian Hickson.
  
  [Announced on the WHATWG mailing list](http://lists.w3.org/Archives/Public/public-whatwg-archive/2011Mar/0238.html),
  this new section of the HTML spec introduces the `getUserMedia` method,
  `PeerConnection` interface, and `MediaStream` interface (initially just
  named `Stream`). The content of the section will eventually be forked
  by the W3C WebRTC Working Group to create the
  [WebRTC spec](http://dev.w3.org/2011/webrtc/editor/webrtc.html), but even
  at this point in 2011 when it is first introduced, it already provides
  for all of the following:

  > Getting a multimedia stream (video, audio, or both) from local devices
  > (video cameras, microphones, Web cams) or from prerecorded files
  > provided by the user; Recording such streams locally; Connecting to
  > remote peers using NAT-traversal technologies such as ICE, STUN, and
  > TURN; Sending the locally-produced streams to remote peers and
  > receiving streams from remote peers; Displaying such streams (both the
  > locally-produced ones and the remotely-obtained ones) locally using the
  > video or audio elements; Sending arbitrary data to remote peers.

## 2011-11

- [Flash Player for mobile devices end-of-lifed by Adobe](http://blogs.adobe.com/conversations/2011/11/flash-focus.html);
  the news is widely interpreted as a major shift by Adobe toward HTML5 and
  away from Flash; excerpt from the announcement:

  > HTML5 is now universally supported on major mobile devices, in some
  > cases exclusively. This makes HTML5 the best solution for creating and
  > deploying content in the browser across mobile platforms.

## 2012-02

- [Adobe reduces Flash roadmap to just two areas: gaming and premium video](http://www.adobe.com/devnet/flashplatform/whitepapers/roadmap.html);
  the news is widely interpreted as a further focusing by Adobe away from
  Flash and toward HTML5 and other "modern web technologies":

  > With the growth of competition in the browser market, browser vendors
  > are increasingly innovating and providing functionality that makes it
  > possible to deploy rich motion graphics directly via browser
  > technologies, a role once served primarily by Flash Player.
  > Increasingly, rich motion graphics are being deployed directly via the
  > browser using HTML5, CSS3, JavaScript and other modern web
  > technologies. Adobe expects that this trend will continue and
  > accelerate, and Adobe will continue to play an active role in this
  > space.
