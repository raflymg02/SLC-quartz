---
title: Adaptive Hypermedia
draft: false
tags:
  - "#hypermedia"
---

P. De Bra, “Adaptive Hypermedia,” in _Handbook on Information Technologies for Education and Training_, H. H. Adelsberger, Kinshuk, J. M. Pawlowski, and D. G. Sampson, Eds., Berlin, Heidelberg: Springer Berlin Heidelberg, 2008, pp. 29–46. doi: [10.1007/978-3-540-74155-8_2](https://doi.org/10.1007/978-3-540-74155-8_2).


# Introduction

Adaptive hypermedia is an alternative to the traditional “one-size-fits-all” approach in the development of hypermedia systems. Adaptive hypermedia systems **build a model of each individual user's goals, preferences and knowledge**, and use this model throughout the interaction with the user, in order to **adapt to the needs of that user**. For example, a student in an adaptive educational hypermedia system will be given a presentation that is adapted specifically to his or her knowledge of the subject, with suggested set of the most relevant links to proceed further.

# History

## Before 1996

Adaptive Hypermedia research can be traced back to the early 1990s. At that time, the two main parent areas - Hypertext and User Modeling - had achieved a level of maturity that allowed for the cross-fertilization of research ideas. Initially, **research efforts were independent**, with early researchers unaware of each other's work. The support from the already established user modeling research community was influential in helping the existing research teams to **find each other**, and in recognizing and promoting **adaptive hypermedia as an independent research direction** in user modeling.

By that time, several innovative adaptive hypermedia techniques had been developed, and several research-level adaptive hypermedia systems had been built and evaluated. For more information, the reader is referred to the review of adaptive hypermedia systems, methods and techniques at that time (Brusilovsky, 1996).

## After 1996

The year of 1996 can be considered **a turning point** in adaptive hypermedia research. Adaptive hypermedia has gone through a period of rapid growth. In particular, several new research teams have commenced projects in adaptive hypermedia, and many students have selected adaptive hypermedia as the subject area for their PhD theses.

The surge in adaptive hypermedia research can be attributed to two key factors. The first factor is the rapid increase in the use of the Word Wide Web. The Web **demands adaptivity** due to its **widely diverse audience**. The second factor is the accumulation and consolidation of research experience in the field. It is clearly visible that research in adaptive hypermedia performed and reported up to 1996 has **provided a good foundation** for the new generation of research. In addition, a large number of systems developed since 1996 are either real world systems, or research systems developed for real world settings.

# Systems, Methods, Techniques
## Where to use?

The review identified six kinds of adaptive hypermedia systems in 1996 – educational hypermedia, on-line information systems, on-line help systems, information retrieval hypermedia, institutional hypermedia, and systems for managing personalized views in information spaces.

Educational hypermedia and on-line information systems are now established leaders. Together, they account for about two thirds of the research efforts in adaptive hypermedia. Information retrieval (IR) hypermedia is challenging the leaders. The traditional scope of IR hypermedia was extended and now includes also systems for managing personalized views.

### Educational Hypermedia
		![[Pasted image 20240216150228.png]]
### On-line information systems
		![[Pasted image 20240216150243.png]]
### Hypermedia for information retrieval
		![[Pasted image 20240216150323.png]]
		![[Pasted image 20240216150345.png]]
## Adapting to What?
### User Characteristics
- User interests

	User interests is a long-standing but previously underutilized aspect in adaptive hypermedia systems. Now, user interests have gained prominence with the advent of Web Information Retrieval (IR) systems. This feature is also becoming popular in various online information systems such as kiosks, encyclopedias, and museum guides. In these systems, the user’s interests serve as **a basis for recommending relevant hypernodes.**


- User's individual traits
	
	User's individual traits is a group name for user features that together **define a user as an individual**, such as personality factors, cognitive factors, and learning styles. Many researchers agree on the importance of modeling and using individual traits, but there is little agreement on which features can and should be used, or how to use them. To progress in this area, we either need to learn more about the relationships between user traits and possible interface settings, or treat user traits as a black box and attempt to model them and adapt to them using non-symbolic technologies.

### Environment

Users of the same server-side Web application can reside virtually everywhere and use different equipment. Therefore, adaptation to user’s environment has become an important issue. Simple adaptation to the platform (hardware, software, network bandwidth) usually involves selecting the type of material and media (i.e., still picture vs. movie) to present the content. More advanced technologies can provide considerably different interface to the users with different platforms and even use platform limitation to the benefits of user modeling.

## What can be adapted?

Figure 1 shows the updated taxonomy of technologies for the year 2000.
![[Pasted image 20240127151658.png]]
# Future Trends
## Direction of Expansion
- Integration with other apps
	
	A possible direction of expansion within classic hypermedia, is the embedding of adaptive hypermedia into various application systems. While the majority of modern application systems differ from what constitutes a traditional area of "adaptive hypermedia" systems, they often include hypermedia components. This has benefits such as informing the users of its value and enabling the system to have a more reliable user model.


- Open corpus adaptive hypermedia

	Currently, almost all adaptive hypermedia systems work with closed corpus data. The key to adaptivity in most of the advanced adaptive hypermedia systems is knowledge about hyperdocuments and links, on the basis of indexing of documents and fragments with the user’s possible knowledge, goals, background, etc. Future adaptive hypermedia systems should be able to “understand” hyperdocuments and links without the help of a human indexer.


- Handheld and mobile devices
	
	"Mobile hypermedia" refers to hypermedia applications developed for handheld and mobile devices like portable computers or personal information managers (PIM). This context provides several research challenges. First, most of these devices have relatively small screens. They require the development of advanced adaptive presentation and navigation support techniques, with the possibility of involving a combination of text and sound presentation. Second, user location and movement in a real space becomes an important and easy-to-get part of a user model (ex. with a GPS). A meaningful adaptation to user position in space (and time) is a new opportunity that has to be explored.
## New Technologies
- Natural language generation (NLG)
	
	A few recent examples indicate that NLG techniques can expand known borders of adaptation in hypermedia. For example, NLG can provide adaptive narration, adaptive guidance, and adaptive comparison. We expect that some more NLG technologies will find their way to adaptive hypermedia systems.


- Non-symbolic AI
	
	A solid amount of research in modern AI is connected with various “non-symbolic” approaches such as case-based reasoning, machine learning, Bayesian models, and neural networks. They can enhance user modeling by analyzing entire navigation traces, automatically gather knowledge about hypermedia documents, and assist in adaptation decisions.

## New Architecture
- Authoring tools
	
	In many cases, an adaptive hypermedia system developed for a particular domain can be generalized into a framework that can be applied to building several similar systems in the same domain. A framework applied to developing several systems almost always grows into a toolkit, a shell, or even an authoring system that could significantly simplify the development of new systems for the domain.


- Component-based frameworks and user model servers
	
	A system built with a component-based architecture consists of several components that interact with each other. A useful component-based architecture can improve the process of development, by allowing development team to concentrate their efforts on building a few components, while re-using other necessary components developed by other teams.


# Conclusion

At the eve of the year 2000, we can identify more kinds of adaptive hypermedia systems methods and techniques than we could a few years ago. Thus, it is natural to expect that some adaptive hypermedia systems of the future will not be able to fit any classification or predictions. The taxonomy suggested in the review and extended in this paper will certainly need further extensions. One plausible extension could involve a two-dimensional classification system, categorizing systems by type (e.g., online information, performance support) and application area (e.g., education, medicine, e-commerce). Analyzing the similarities and differences among systems of different types serving the same area, such as medicine, could yield valuable insights.

We were not able to cover this and some other aspects in the single review. It is just an attempt to bring some order to the past and to predict the nearest future. We hope that it will be useful as an introduction into the field for newcomers and as a common ground for researchers and developers in the area.