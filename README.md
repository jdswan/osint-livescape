# OSINT Livescape 0.3
## A live view of the OSINT landscape

OSINT Livescape is inspired by and an extension of the OSINT Landscape document v. 1 authored by H I Sutton ([@CovertShores](https://twitter.com/CovertShores)), Aliaume Leroy ([@Yaolri](https://twitter.com/Yaolri)), and Tony Roper ([@Topol_MSS27](https://twitter.com/)).

#### From Landscape to Livescape

OSINT Livescape removes the problems inherent to a static list of internet resources, and opens up new possibilities for crowd-sourced maintenance of the captured landscape.




#### Version Log

**0.1** "Exact copy" of the OSINT Landscape v. 1 guide
 * Every element on the original landscape document is represented by an element in a JSON dictionary.
 * JSON is temporary, so keys aren't rigorously systematic.
 * Elements have "display" (display name), and URL attributes.
 * Elements have "tags" attribute which duplicate or closely approximate the groupings present on the original landscape document.

**0.2** All elements without associated URL removed
 * A URL could not be located for some elements, or returned a 404 error. 
 * The following elements were deleted from the JSON dictionary.
   * fSignal
   * Download-Twitter-Videos
   * Instagram Downloader
   * Photo Map
   * Youtube DataViewer
   * AisDecoder
   * websta
   * Google+
   * izitru

**0.3** Status attribute added to elements
 * Staus reflects availability of service: up, down, and disabled for services still reachable but state they are currently offline due to API changes.
 * The following elements have a current status of "disabled"
   * peoplefindThor
   * socilab