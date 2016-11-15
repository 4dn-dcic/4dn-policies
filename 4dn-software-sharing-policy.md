# 4D Nucleome Project - Software Sharing Policy

*Version 1.1 - 14 October 2016*

- - -

4D Nucleome Publication, Data Release, and Software Sharing Policies distinguish two release tiers:

* Tier 1 concerns release to network members
* Tier 2 concerns release to the public

This policy will be reviewed and, if necessary, updated on a semi-annual basis.

- - -

This policy is based on the ENCODE software release policy (https://www.encodeproject.org/about/data-use-policy/).

_Rationale: To ensure reproducibility of analyses and to encourage reuse of software._

Developers of significant new 4DN-related software will make their programs, including source code, freely available to the network and to the public. Examples include data processing pipelines and implementations of statistical, visualization, and modeling tools developed by 4DN funded groups to process or analyze data produced by the network. Developers are strongly encouraged to integrate support for data format standards agreed upon by the the 4DN network into their software.

## What to Release

The network requires the release of analysis pipelines used for major 4DN products. The network requires release of software tools and pipelines used to process any released data and used for major analyses and modeling in planned 4DN publications. When released together with specific datasets or modeling applications, the software should be released together with the parameter files that would allow fully reproducible runs as well as a minimum sample data set. Furthermore, a complete description of all external dependencies (such as libraries and their specific versions) of the software needs to be provided.

We also strongly encourage release of software likely to be useful to multiple groups either within the network or in the broader community.


## When to Release

The decision of when software should be released should balance the benefit to the network and the broader community, against the labor involved in software release and maintenance. 

Software tools for data analysis and processing should be released as soon as they are sufficiently stable and no later than the time of the data release (according to the Tier system described at the beginning of this document). 

Other software should be released with the release of the manuscript according to the publication policy and the Tier system. 

__Software that has been released only within the network (Tier 1)  cannot be used in any publications of network members, whether for projects funded by 4DN or otherwise.__ By requiring that any software used to generate hypotheses or results presented in a publication is publicly available (Tier 2), we will enable the broader community to repeat studies and reproduce findings.


## How to Release

Tier 2 (i.e. released to the public) software should be released by version controlled public repositories (e.g. Github, GitLab, BitBucket). These repositories should be linked via the 4DN DCIC and 4DN OH. Software should be well-documented and there should be a contact person for questions. Software development should continue through version-controlled deposition, and the software version used to generate each dataset must be documented using a consistent versioning scheme, e.g. Semantic Versioning  (http://www.semver.org).

Whenever possible, 4DN funded software should be released under an open source license. It is, however, the sole responsibility of network members to follow any relevant rules of their institution with respect to software licensing. 

In order to avoid multiple versions of the same software being maintained by different network members, network members who wish to contribute modifications of shared software tools (both Tier 1 and Tier 2) should do so using standard collaborative software development procedures such as Pull Requests on GitHub repositories. They should also clearly document what changes they made and the rationale for the modifications. 


## Who Releases

Developers who release software publicly (Tier 2) should ensure that their software is included in the 4DN resource catalog. 


## Other Considerations

__Accompanying publications__: In addition to the release of well-documented code, we strongly encourage developers to publish citable descriptions of their software. We recommend that authors describe their software in methodological papers so that they can receive credit for their work. These can be published in conventional journals, and/or disseminated pre-publication through pre-print servers (e.g. bioRxiv). 

__Dissemination of more complex pipelines__: For most complex analyses, multiple software components are routinely combined to generate intermediate datasets. For reproducibility of these results, analysts should document all software components used, and the specific software versions utilized. We encourage (1) documenting these components; (2) providing scripts that reproduce key figures in 4DN publications; (3) establishing reusable, publicly accessible analysis pipelines (e.g. Galaxy, virtual machines, Docker, workflows compatible with systems provided by (commercial) cloud-based analysis providers); and (4) linking these through the DCIC website.

__Current and future support for released software__: Tier 2 Software that will be released for publication and to repositories (e.g., Github) should state the types and degree of support users can expect for them to download, run, and troubleshoot the available software as well as whether or not updates and “fixes” should be expected. In many cases, the expectation is that there is minimal support for users, ie, the software is provided for reproducibility purposes, and not for outside use. The state of the software should be documented in a README file that is part of the software. 


## Contributors

### Policy Working Group - Grantees

_Co-Chairs_: Nils Gehlenborg, Leonid Mirny

Stephanie Alexander, Ewan Birney, Job Dekker, Larry Gerace, Mike Levine, Timothée Lionnet, Chuck Murry, Shankar Subramaniam, Huimin Zhao

### Policy Working Group - Program Staff

Iddil Bekirov, Olivier Blondel, Lisa Chadwick, Lisa Postow

Additional comments provided by William Noble, Hanspeter Pfister, and David Baddeley


## Revisions

- Version 1.1 - 14 October 2016
  - Replaced "consortium" with "network". 
- Version 1.0 - 16 August 2016 
  - Approved by Steering Committee during 16 August 2016 call.



