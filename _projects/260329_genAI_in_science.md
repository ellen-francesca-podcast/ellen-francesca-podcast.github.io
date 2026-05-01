---
layout: page
title: How does generative AI change scientific discovery?
description: A podcast episode about how generative AI tools like Claude, ChatGPT change our day-to-day work as scientists in academia.
img: /assets/img/podcast_logo.png
importance: 1
category: podcast
---

## 🎙️ Episode

<iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/episode/6G5OhWceJnC6FgLX91D4I9?si=b43yEcKVQYm8V_Wn_kSrog" width="100%" height="352" frameBorder="0" allowfullscreen="TODO: insert link" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

**Description:**
How is research changing in the age of AI?
In this episode, Ellen and Francesca discuss how generative AI has entered nearly every stage of their PhDs: brainstorming, literature review, hypothesis generation, coding, writing, reviewing, and publishing. They reflect on the tools they use, the ones that did not live up to expectations, and how their own practices have evolved as the technology has improved and attitudes toward it have shifted.
The conversation explores both the promise and the risks of AI in research: faster workflows, new forms of intellectual support, and lower barriers to getting started, but also the dangers of homogenised thinking, AI slop, uneven adoption across fields, and growing uncertainty around authorship, expertise, and scientific originality. Ellen and Francesca reflect on how differently AI is being adopted across disciplines and by individual researchers, and ask what all of this means for the future of science. Are we moving toward a world of AI scientists, or one in which more of us become "hobby scientists"?

**Detailed outline**

We started our PhDs after ChatGPT became first available to the public

In this episode we discuss how generative AI changed our scientific practice in every step of the research process:

1. [**Literature review and brainstorming**](#1-literature-review-and-brain-storming)

   Main takeaway: AI helps researchers navigate information overload, but it may also push many people toward the same papers, ideas, and trends.

2. [**Data analysis and method development**](#2-data-analysis-and-method-development)

   

3. [**Writing**](#3-writing)

   Main takeaway: Generative AI makes scientific writing faster and often clearer, but it also lowers the cost of producing polished text that could be mistaken for high impact work. 

4. [**Peer review**](#4-peer-review)

   Main takeaway:

And last, but not least, we discuss how we see generative AI changing the future of scientific research (#5-Discussion-The-future-of-scientific-research)

## 1. Literature review and brain storming

One reason AI literature tools have become so attractive is simple: the volume of scientific work has become overwhelming. In many fields, it no longer feels possible to keep up with the full literature, so researchers increasingly rely on AI tools to search, summarize, and synthesize papers [[19]](#ref-19).

That can be genuinely useful. In our episode, we talk about using AI to understand complex papers more quickly, ask clarifying questions, and brainstorm ideas across disciplinary boundaries. Used well, AI can act like a personal tutor or discussion partner.

**Is generative AI homogeneising research?**

But this convenience comes with a risk: homogenization. As [An Unsolicited Guide to Being A Researcher](https://emerge-lab.github.io/papers/an-unsolicited-guide-to-good-research.pdf) puts it, if everyone reads the same things, it becomes harder to do distinctive work and “Become a weird butterfly.”

> "Do not let social media source most of your reading. This is a way to be behind the puck / wind up chasing the same trend. Virality based social media is inherently homogenizing. It is hard to contribute unique research if you’re reading the same thing as everyone else. Become a weird butterfly." [An Unsolicited Guide to Being A Researcher](https://emerge-lab.github.io/papers/an-unsolicited-guide-to-good-research.pdf)

AI seems to intensify that problem. A 2026 Nature paper [[15]](#ref-15) found that scientists using AI tools publish more and receive more citations, but the collective range of scientific topics shrinks, and

> "AI tools seem to automate established fields rather than explore new ones, highlighting a tension between personal advancement and collective scientific progress." [[15]](#ref-15)

**Machine readable and accessible science**

There is also an access problem. AI systems often work best on open, machine-readable literature, but important parts of the scientific record are still harder to access, and scientific figures remain a major challenge for current multimodal systems. That means the papers an AI tool can summarize well are not always the same papers a human researcher most needs to read.

Another problem of why generative AI might miss _novel ideas_ or _good science_ could be because the science is not machine readible or behind a paywall. The latter adresses the fact that most peer reviewed articles in journals, such as Science, Cell, Nature etc is behind a pay wall only available if you pay for the access or are part of the university and therefore not contained and accessible to many generative agents claimed to be adressed by specific tools that also include all publications (for example [Elicit]() that we talked about in the podcast)

The other point adresses the fact whether we should start producing science that is machine readable. For example, Figures and illustrations which make up a large point of scientific publications, are at this moment, less accessible to generative AI tools [[16]](#ref-16).

**Science slop**

A useful term for this growing problem is **science slop**: work that looks scientific on the surface, but adds little or no real understanding. Jonathan Oppenheim describes it as

> "work that looks plausibly correct and technically competent but isn’t, and doesn’t advance our understanding. It has the _form_ of scholarship without the _substance_. The formalism looks correct, the references are in order, and it will sit in the literature forever, making it marginally harder to find the papers that actually matter." [[14]](#ref-14)

Major science outlets are now discussing the parallel problem of **AI slop** in scientific publishing. Nature describes a “tide” of AI-generated or AI-assisted submissions hitting preprint servers and conferences, while _Science_ has called for researchers to resist AI slop altogether [[5]](#ref-5), [[11]](#ref-11).

What worries us is not only that more low-quality work can now be produced, but that it becomes harder to filter out. For example, we notice that the most interesting sounding papers are often AI slop drawing a parallel to fake news: If something is not real, you can make up the most interesting, implausible but attention grapping stories. At the moment it is still quite easy to spot a AI-generated paper from real science for example based on the images. But we can expect the generated-AI content to become increasingly better. In the future, more experienced researchers may still have an easier time spotting low-quality work, but the filtering burden becomes much heavier for junior researchers and potentially even harder when AI systems increasingly mediate what we read.

## 2. Data analysis and method development

One area where generative AI is becoming increasingly powerful is **coding**. In our own experience, these tools are especially useful for repetitive or boilerplate-heavy tasks: generating plotting functions, setting up environments, writing Docker files, and translating code between programming languages. At the same time, their success still depends a lot on the task, the programming language, and how well the problem can be specified.

**From writing code to supervising it**

As Lior Prachter, a PI in computational biology, who didnt code in more than 20 years describes using Claude and Codex to port edgeR into Python in about a week:

> As someone who had not coded seriously for more than 20 years, I found Claude’s efficiency and accuracy enabling in a way that would have been inconceivable a few years ago. At this point, it is reasonable to predict that what took a week for this project may soon take less than a day. **This raises the question of what the role of preprints, conference proceedings, and journal publications will be in the scientific enterprise of the future (Zeilberger, 1993).** [[17]](#ref-17)

This shift is not limited to academia. Spotify’s co-CEO recently said that some of the company’s best developers had **not written a single line of code since December**, and were instead supervising AI-generated code through the company’s internal tooling [[21]](#ref-21)

**Is there a promise and reality gap?**

But this is not a simple success story. In the episode, we also talk about the **gap between the promise and the reality** of coding agents. They can be amazing for setup, translation, and quick prototyping, yet still frustrating for method development when scientific control, debugging, and precise reasoning matter. In that sense, AI does not remove the need for expertise — it shifts expertise toward planning, verification, and judgment.

- it is a skill you need to learn, how to communicate with the agent

And requires assumption of that someone knows how to code? And

## 3. Writing

A recent Science study analyzing more than two million preprints (arXiv, bioRxiv and SSRN) found that LLM adoption was associated with posting 36–60% more manuscripts. But for LLM-assisted manuscripts, greater writing complexity was associated with *lower* publication probability. This observation is reverse of the historical pattern: higher writing completixity = higher publication probability. One possible interpretation is that generative AI makes it easier to produce more text, without necessarily improving the underlying quality of the work. [[20]](#ref-20)

**"Vibe citing"**

Alex Adams, coined the term "vibe citing" to describe the LLM tendency to derive or amalgamate real sources into uncanny imitations.
More hallucinated references

**Democratization**

At the same time, writing support is one of the clearest ways in which AI can genuinely democratize science. In our episode, we talked about how these tools can help non-native English speakers phrase things more clearly and compete on more equal terms in an English-dominated publishing system. [[8]](#ref-8)

This is important because of the measurable burden for non-native English speakers. A study found that non-native English speakers spend substantially more time writing papers in English than native speakers, and a later summary estimated this burden at up to **51% more time**. They are also more likely to face rejection or revision requests because of their English writing. [[22]](#ref-22)

In that sense, AI can act as a kind of scientific translator: not replacing scientific thinking, but helping researchers express their ideas more clearly in the language that currently dominates publication.

**Journal and conference policies around LLM usage**

Science’s most [recent policies](https://www.science.org/content/page/science-journals-editorial-policies#image-text) 

> allow the use of large language models for certain processes without any disclosure, such as editing the text in research papers to improve clarity and readability or assisting in the gathering of references. However, the use of AI beyond that—for example, in drafting manuscript text— must be declared. And the use of AI to create figures is not allowed. All authors must certify and be responsible for all content, including that generated with the aid of AI 

Journals are starting to put out specific guidelines 

## 4. Peer review

Peer review is a necessary step for publishing in recognized journals or conferences. It means that someone else from the scientific community (aka a peer) has to review your publication: they provide feedback, ask clarifying questions and give the journal an indication of whether the article is publishable or not. 

This process is always on a voluntary basis: no money, no recognition etc. which makes it difficult to find reviewers or also reviewers that know your field but don't know your work directly. Sometimes that causes reviewers to review your paper without knowing the field and hence understanding the impact of the work or limited time because of an overwhelmhing amount of review request. Especially, the latter is believed to cause a ever increasing amount of AI generative peer reviews [[23]](#ref-23).

[2]

We have more manuscripts submitted, we need AI to review papers to some extend. But how can we make sure it is not just checking for 
    

What measures are being taken by journals or conferences?

- Journals start putting all peer reviews online to counteract AI generated reviews

AI to refine peer reviews, 

For further reading check out this [[Nature review]] (#ref-23) that was published after we recorded the episode. 


## Discussion: The future of scientific research

The final question what we asked ourselves was:

> Are we moving toward a world of AI scientists, or one in which more of us become "hobby scientists"?

**What skills will remain import to have, which not?**

> The temptation today is just to fully automate scientific workflows, to just directly switch to AI scientists or self-driving laboratories that generate hypothesis design experiments and draft manuscripts end to end. But these systems can be dazzling. But science is not an assembly line, nor does it have fixed objectives to optimize. It's an enterprise that is built on interpretation, contestation and responsibility in which human judgment is crucial. [[7]](#ref-7) TODO: check this reference!!

And I really think that this idea of like taste and human judgment, what ideas we find worth pursuing, what are questions we find worth pursuing, what are the things we actually want to be included in the manuscript of writing?

How will we motivate and raise a new generation of scientists, motivate them to learn and think for themselves without 

Interesting perspective on this and great read is: [The machine are fine, I am worried about us](https://ergosphere.blog/posts/the-machines-are-fine/)

**scientific research in academia vs industry**

An open question is: Will scientific research slowly transition to industry? because they have more resources. Or will academic institutions remain the main drivers because of the partially government enabled fundings and therefore being able to work on scientific problems that do not directly need to be profitable?

**the future of preprints**

What about preprints? Like Lior Prachter wrote in his reflection to the coding transformation he also raises the question about the usefullness of preprints. In addition to them becoming increasingly faster we also want to add


## Main takeaways

We went from being ashamed from using AI, trying to hide when we ask ChatGPT for help to adopting it in our day-to-day life. However, in academia we are still missing policies and guidelines on the use of AI. Journals are starting to put out specific guidelines 

**senior scientists will benefit**

Throughout the discussion and this summary we highlighted often that **senior** scientists will be able to make the most of AI. Basically, when you have the knowledge and terms to land in the right search and probability space of the LLM you can benefit the most from it. But what about the rest of us? What about the junior researchers and stuff?

**increased amount of publication, less breakthroughts**

Since a few years we see an increased amount of publications 

**Fast pace, no time to think**

What we notice is that with AI science is moving at an increased pace. Because we now have so much help the expectation or the trend is to published more 

TODO: Include quotes from the podcast

# Resources

## Articles and essays

<a id="ref-1"></a>[1] [AI can turbocharge scientists' careers — but limit their scope](https://www.nature.com/articles/d41586-026-00162-2)

<a id="ref-2"></a>[2] [AI can improve your peer review — and make it more polite](https://www.nature.com/articles/d41586-026-00536-6)

<a id="ref-3"></a>[3] [AI is threatening science jobs. Which ones are most at risk?](https://www.nature.com/articles/d41586-026-00444-9)

<a id="ref-4"></a>[4] [AI agents are hiring human "meatspace workers" — including some scientists](https://www.nature.com/articles/d41586-026-00454-7)

<a id="ref-5"></a>[5] [AI slop is causing a crisis in computer science](https://www.nature.com/articles/d41586-025-03967-9)

<a id="ref-6"></a>[6] [Grant proposals drafted with AI help more likely to win NIH funding](https://www.nature.com/articles/d41586-026-00369-3)

<a id="ref-7"></a>[7] [AI agents are "aeroplanes for the mind": five ways to ensure that scientists are responsible pilots](https://www.nature.com/articles/d41586-026-00665-y)

<a id="ref-8"></a>[8] [The AI co-scientist is here](https://www.nature.com/articles/s41591-026-04275-z)

<a id="ref-9"></a>[9] ["Obviously ChatGPT" — how reviewers accused me of scientific fraud](https://www.nature.com/articles/d41586-024-00349-5)

<a id="ref-10"></a>[10] ["Einstein" bot sharpens debate over AI in the classroom](https://www.nature.com/articles/d41586-026-00764-w)

<a id="ref-11"></a>[11] [Resisting AI slop](https://www.science.org/doi/10.1126/science.aee8267)

<a id="ref-12"></a>[12] [Could AI slow science? Confronting the production-progress paradox](https://www.normaltech.ai/p/could-ai-slow-science)

<a id="ref-13"></a>[13] [Before AI Can Accelerate Science, We Have to Fix Science](https://timrequarth.substack.com/p/before-ai-can-accelerate-science)

<a id="ref-14"></a>[14] [We are in the era of Science Slop](https://superposer.substack.com/p/we-are-in-the-era-of-science-slop)

<a id="ref-15"></a>[15] [Artificial Intelligence tools expand scientists' impact but contract science's focus](https://www.nature.com/articles/s41586-025-09922-y)

<a id="ref-16"></a>[16] [Science should be machine readable](https://www.biorxiv.org/content/10.64898/2026.01.30.702911v1)

<a id="ref-17"></a>[17] [From Articles to Code: On-Demand Generation of Core Algorithms from Scientific Publications](https://arxiv.org/abs/2507.22324)

<a id="ref-18"></a>[18] [The Quickening](https://liorpachter.wordpress.com/2026/02/19/the-quickening/)

<a id="ref-19"></a>[19] [As scientists face a flood of papers, AI developers aim to help](https://www.science.org/content/article/scientists-face-flood-papers-ai-developers-aim-help)

<a id="ref-20"></a>[20] [Scientific production in the era of large language models](https://www.science.org/doi/10.1126/science.adw3000)

<a id="ref-21"></a>[21] [Spotify says its best developers haven't written a line of code since December, thanks to AI](https://techcrunch.com/2026/02/12/spotify-says-its-best-developers-havent-written-a-line-of-code-since-december-thanks-to-ai/)

<a id="ref-22"></a>[22] [Amano, T., Ramírez-Castañeda, V., Berdejo-Espinola, V., Borokini, I., Chowdhury, S., Golivets, M. et al. The manifold costs of being a non-native English speaker in science. PLoS Biol. 21, e3002184 (2023).](https://doi.org/10.1371/journal.pbio.3002184)

## Papers and reports

<a id="ref-23"></a>[23]  [Pangram Predicts 21% of ICLR Reviews are AI-Generated](https://www.pangram.com/blog/pangram-predicts-21-of-iclr-reviews-are-ai-generated)

<a id="ref-24"></a>[24] [The Compute Divide in Machine Learning: A Threat to Academic Contribution and Scrutiny?](https://arxiv.org/abs/2401.02452)

<a id="ref-25"></a>[25] [Relativistic Covariance and Nonlinear Quantum Mechanics: Tomonaga-Schwinger Analysis](https://arxiv.org/abs/2511.15935)

 <a id="ref-26"></a>[26][Steve Hsu on X: post on GPT-5 and theoretical physics research](https://x.com/hsu_steve/status/1996034522308026435)

 <a id="ref-26"></a>[27] [Peer review in the time of artificial intelligence](https://www.nature.com/articles/s41565-026-02177-2)

## Talks and videos

- [Open-Source and Science in the Era of Foundation Models](https://www.youtube.com/watch?v=yPfrzFzvKSA)
- [Still Far From Achieving Autonomous Closed-Loop Scientific Research — Sam Altman](https://www.youtube.com/watch?v=U2lEJKnQaaw)
- The night science podcast: Google research scientists (TODO: add link)
