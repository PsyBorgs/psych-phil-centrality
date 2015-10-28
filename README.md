# PsychPhil Centrality Networks

This is a digital history of psychology project with the general aim of finding out which psychologists and philosophers were most central to the formation of the various professional associations around 1900. Note that the American Psychological Association starts a little earlier in 1892. The Western Philosophical Association started in 1900, the American Philosophical Association in 1902, and the Southern Sociological for Philosophy and Psychology in 1904. Early on, they had a fair bit of overlap in their memberships, which is the key to this project.

The idea for this project is derived from two articles.
The first article is [an essay written by Chris D. Green](http://psychclassics.yorku.ca/Special/Institutions/associntro.htm) about the early psychological and philosophical associations.

Second, read a [popular blog post by Kieran Healy](http://kieranhealy.org/blog/archives/2013/06/09/using-metadata-to-find-paul-revere/).
This post was written soon after it was revealed to the public that the NSA in the US is collecting metadata on a vast number of electronic communications among Americans. Although that seemed to many to be a tremendous invasion of privacy, the NSA’s excuse was that, because they were only collecting metadata (i.e. when, where, and between whom communications were made, but not the actual content of the messages), privacy laws were not being broken.

In response, Healy showed that with only the memberships lists of various revolutionary organizations in 1770s America (a reasonable analog to metadata), and a little math, it would have been trivially easy to pinpoint Paul Revere (long before his famous “ride”) as a “dangerous" revolutionary because he was (mathematically) “central” to the collection of people who were members of those groups.

In any case, we’re not going to save the world from the NSA, but we decided to use the same technique to discover who was “central” to American psychologist/philosophers around 1900.

We created a CSV similar to Healy’s, but with the rows representing the names of all the members (of all four associations), and the columns representing the four associations themselves (APsychA, [WPhilA][WPhilA], [APhilA][APhilA], and [SSPP][SSPP]). To begin, we entered a `1` for member and `0` for non-member.

[WPhilA]: http://psychclassics.yorku.ca/Special/Institutions/WPA.htm
[APhilA]: http://psychclassics.yorku.ca/Special/Institutions/firstAPhilAproc.htm
[SSPP]: http://psychclassics.yorku.ca/Special/Institutions/firstSSPPproc.htm

(Note: You can find the 1900 membership of the APsychA in the second issue of the 1901 vol of Psychological Review [online with the York University library].)
