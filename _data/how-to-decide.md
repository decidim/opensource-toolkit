


### Build it or adapt it?

You might have a need that requires your team to build new software. When should you build it from scratch and when should you adopt an existing solution? You may think: "but our needs are very specific." Or: "We want to ensure our software looks like the rest of the software we use (logos, colors, styles, branding), so we'd rather build it from scratch". To this, you might want to consider the following:

1. Lots of governments, businesses, or organizations have similar processes, and there's probably a good, resilient, and constantly mantained solution that you could adopt out of the box. Do you need to have a software that enables citizens to have their own digital identities, and that they are compatible with citizen files and government procedures? How about [MOSIP](https://www.digitalpublicgoods.net/r/modular-open-source-identity-platform)? Do you want to track beneficiaries for social programmes and implement case management tools so case workers can follow-up on them? How about using [Aam Digital](https://www.digitalpublicgoods.net/r/aam-digital)? 

You can check proven open source solutions for the public good by accessing the [Digital Public Goods Alliance Registry](https://www.digitalpublicgoods.net/), an iniative of the UN that recognizes well built, well mantained software, can be a public good serving millions. They have an extensive review process that ensure the software within the registry is of good quality.

2. Most software nowadays is web software, and web software relies on 3 ubiquitous technologies that determine how any software looks on a web browser (think logos, colors, shapes of buttons, etc.): **HTML, CSS and Javascript**. These three languages are basic parts of any developer's toolbelt, and are independent of functionality. Good agnostic software will consider your branding needs a basic part of implementing it and good web developers should be able to modify a web application so that it uses your branding and looks like you built it from scratch. 


### The hidden costs of building versus adopting

You may want to have total control over the product you are building and don't want to deal with the learning curvfe of adopting a software that may well be complicated. Here's some reasons you should consider:

1. Building from scratch is prone to missing important features. We take a lot of functionality for granted, which only comes from extensively using, testing and continously mantaining the same piece of software over the years. A lot of that functionality may be either invisible to end users or leave vulnerabilities open for hackers to discover. For example: An extensive log of all events that happen on the software is not visible to end users, but is crucial to diagnose errors in an application which is bound to happen. Imagine a piece of software serving an entire country and a part of it start to fails. You put your team to diagnose the issue but since event logging is not an end-user facing feature, it was never prioritised nor built. Now developers are left on the dark when trying to solve the issue. Using a piece of software that has a global community using it, means there is thousands of teams and organizations using and  testing it. Issues are detected and patched faster and new features get built.

2. Software obsolescense is a thing. Most non-developers are thinking software is a one-time investment, where you build the software, install it and then are done with it. However any successful software needs to be continously mantained. From adding new features to patching edge-cases that were not considered in the initial version. 

There's also an invisible risk in not updating a piece of software you run: All software is built to run on a specific version of a programming language and specific operating system tools, which they too are continously updated and mantained. Global teams mantaining these programming languages, libraries and operating systems track these updates by releasing new versions, and abandon or deprecate older versions which cease to receive updates. Once hackers find vulnerabilities in languages, libraries or operating systems, these teams patch the vulnerabilities only in their currently supported versions. If your team is not actually working to mantain the software you built by upgrading all of the languages, libraries and operating systems it depends on, it can become prone to attacks in a matter of a couple of years. You can protect yourself from this hassle by adopting an existing software solution that has continuous updates, so that you can benefit from security patches and new feartures.

### Is this reusable?



