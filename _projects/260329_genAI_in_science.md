---
layout: page
title: How does generative AI change scientific discovery?
description: A podcast episode about how generative AI tools like Claude, ChatGPT change our day-to-day work as scientists in academia.
img: /assets/img/scientific-assessment-without-text.jpg
importance: 1
category: podcast
---

## 🎙️ Episode

<iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/episode/6G5OhWceJnC6FgLX91D4I9?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

**Description:**
How is research changing in the age of AI?
In this episode, Ellen and Francesca discuss how generative AI has entered nearly every stage of their PhDs: brainstorming, literature review, hypothesis generation, coding, writing, reviewing, and publishing. They reflect on the tools they use, the ones that did not live up to expectations, and how their own practices have evolved as the technology has improved and attitudes toward it have shifted.
The conversation explores both the promise and the risks of AI in research: faster workflows, new forms of intellectual support, and lower barriers to getting started, but also the dangers of homogenised thinking, AI slop, uneven adoption across fields, and growing uncertainty around authorship, expertise, and scientific originality. Ellen and Francesca reflect on how differently AI is being adopted across disciplines and by individual researchers, and ask what all of this means for the future of science. Are we moving toward a world of AI scientists, or one in which more of us become "hobby scientists"?

# Generative AI in every step of scientific research

1. [**Literature review and brainstorming**](#1-literature-review-and-brain-storming)

   Main takeaway: AI helps researchers navigate information overload, but it may also push many people toward the same papers, ideas, and trends.

2. [**Data analysis and method development**](#2-data-analysis-and-method-development)
 
   Main takeaway: In computational work, generative AI is shifting researchers from writing every line of code themselves toward planning, prompting, reviewing, and integrating code much faster than before.

3. [**Writing**](#3-writing)

   Main takeaway: Generative AI makes scientific writing faster and often clearer, but it also lowers the cost of producing polished text that could be mistaken for high impact work. 

4. [**Peer review**](#4-peer-review)

   Main takeaway: AI can help improve peer review, but the central question is whether it assists human judgment or replaces it.


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

But this is not a simple success story. In the episode, we also talk about the **gap between the promise and the reality** of coding agents. They can be amazing for setup, translation, and quick prototyping, yet still frustrating for method development when scientific control, debugging, and precise reasoning matter. In that sense, AI does not remove the need for expertise but instead  shifts expertise toward planning, verification, and judgment. From this the questions that follow are: Is programming or coding still a skill that you need to learn or is your time better inversted by improving your prompting and communication skills with the agent?

## 3. Writing

A recent Science study analyzing more than two million preprints (arXiv, bioRxiv and SSRN) found that LLM adoption was associated with posting 36–60% more manuscripts. But for LLM-assisted manuscripts, greater writing complexity was associated with *lower* publication probability. This observation is reverse of the historical pattern: higher writing completixity = higher publication probability. One possible interpretation is that generative AI makes it easier to produce more text, without necessarily improving the underlying quality of the work. [[20]](#ref-20)

**"Vibe citing"**

One of the more worrying side effects of writing with LLMs is not just vague prose, but unreliable references. GPTZero’s Head of Machine Learning, Alex Adams, coined the term **“vibe citing”** to describe the tendency of LLMs to derive or amalgamate real sources into uncanny imitations [[23]](#ref-23). This matters because if citations become unreliable literature reviews become noisier, and the scientific record becomes more difficult to trust.

**Democratization**

At the same time, writing support is one of the clearest ways in which AI can genuinely democratize science. In our episode, we talked about how these tools can help non-native English speakers phrase things more clearly and compete on more equal terms in an English-dominated publishing system. [[8]](#ref-8)

This is important because of the measurable burden for non-native English speakers. A study found that non-native English speakers spend substantially more time writing papers in English than native speakers, and a later summary estimated this burden at up to **51% more time**. They are also more likely to face rejection or revision requests because of their English writing. [[22]](#ref-22)

In that sense, AI can act as a kind of scientific translator: not replacing scientific thinking, but helping researchers express their ideas more clearly in the language that currently dominates publication.

**Policies and transparency around LLM usage**

Science’s most [recent policies](https://www.science.org/content/page/science-journals-editorial-policies#image-text) 

> allow the use of large language models for certain processes without any disclosure, such as editing the text in research papers to improve clarity and readability or assisting in the gathering of references. However, the use of AI beyond that—for example, in drafting manuscript text— must be declared. And the use of AI to create figures is not allowed. All authors must certify and be responsible for all content, including that generated with the aid of AI 

Publishers and journals are now starting to define clearer boundaries. *Science*, for example, says that reviewers may not enter any part of a manuscript into an LLM or other AI system. That reflects a broader concern with confidentiality, accountability, and the difference between language assistance and outsourced judgment.


## 4. Peer review

Peer review is a necessary step for publishing in recognized journals or conferences. Other researchers in the field evaluate a manuscript, ask clarifying questions, and help editors decide whether the work is ready to publish.

This process is always on a voluntary basis: no money, no recognition etc. which makes it difficult to find reviewers or also reviewers that know your field but don't know your work directly. Sometimes that causes reviewers to review your paper without knowing the field and hence understanding the impact of the work or limited time because of an overwhelmhing amount of review request. Especially, the latter is believed to cause a ever increasing amount of AI generative peer reviews [[23]](#ref-23).

**Improve clarity**

One possible benefit of AI is that it can improve the quality of written reviews. A recent *Nature* news article describes an AI coaching system that helped reviewers write more constructive and less toxic feedback. [[2]](#ref-2) 

We also discussed a more informal use of AI in the podcast: asking LLMs to critique a draft before submission, roleplay different kinds of reviewers, or point out missing controls and unclear claims. Used in that way, AI can strengthen a paper before it even enters formal peer review.

**Replace human judgement**

The concern is different when AI is no longer just editing or sharpening a review, but generating the actual judgment. Pangram’s analysis of ICLR 2026 reviews estimated that 21% of reviews were fully AI-generated, and that more than half involved AI in some form. [[28]](#ref-28)

That is where the deeper problem begins: not just automation, but the risk that human evaluation is being replaced by synthetic feedback that sounds plausible without reflecting real expertise or accountability.

A useful principle comes from a 2026 *Nature Nanotechnology* editorial: generative AI may support peer review, but it “must not replace” human judgment, expertise, and critical thinking. [[27]](#ref-27) 

*For further reading check out this [[Nature review]] (#ref-23) that was published after we recorded the episode.*

## Discussion: The future of scientific research

The final question what we asked ourselves was:

> Are we moving toward a world of AI scientists, or one in which more of us become "hobby scientists"?

That question is exciting, but also misleading if framed too simply. The temptation today is to imagine fully automated science: AI systems that generate hypotheses, design experiments, analyze results, and draft manuscripts end to end [[8]](#ref-8). But as Dashun Wang and colleagues argue:

> “The central goal should not be complete automation, but designing platforms that preserve creativity, responsibility and surprise.” [[7]](#ref-7)

Science is not just a pipeline for producing outputs. It depends on interpretation, judgment, disagreement, and responsibility. AI may be able to accelerate many parts of the process, but it does not (for now) remove the need for people to decide which questions are worth asking, which results are convincing, and which ideas are worth pursuing.

At the same time, this raises a difficult question for training the next generation of scientists. If AI makes it easier to skip directly to an answer, how do we still motivate people to learn the underlying concepts, struggle with hard problems, and develop scientific intuition for themselves? How can we make time to think, when we are used to everything progressing so fast?

A perspective we found interesting here is: [The machines are fine, I am worried about us](https://ergosphere.blog/posts/the-machines-are-fine/) [[29]](#ref-29).

### Scientific research in academia vs. industry

Another open question is whether AI will shift even more scientific power toward industry.

Large companies often have more compute, more engineering support, and more access to frontier models than academic labs. That could widen the gap between well-resourced institutions and smaller research groups. On the other hand, academia still has something industry often does not: the freedom to work on questions that are important without needing them to be immediately profitable [[24]](#ref-24).

### The future of preprints

The role of preprints may also change. If ideas can be turned into code, figures, and polished manuscripts much more quickly, then preprints become both more powerful and more fragile.

They are more powerful because they allow fast dissemination of ideas. But they also become more fragile because the barrier to producing something that *looks* like a paper is getting lower. As Lior Pachter notes in *The Quickening*, if implementing a method becomes dramatically faster, then we also have to ask what role preprints, conference proceedings, and journal publications will play in the future. [[18]](#ref-18)

## Main takeaways

We went from feeling slightly embarrassed about using AI in research to using it almost every day. At this moment, our main takeaways are:

### 1. AI helps most when you already know what you are doing

Throughout this discussion, one theme kept coming up: **senior researchers are often better positioned to benefit from AI**.

If you already know the field, the terminology, and the important caveats, it is much easier to ask the right questions, recognize bad answers, and use AI as a real accelerator. That also means junior researchers may benefit less or may even be more vulnerable to being misled by confident but incorrect outputs.

### 2. More scientific output does not automatically mean more scientific progress

Generative AI makes it easier to write, code, summarize, and produce manuscripts. That is likely one reason why we are seeing more scientific output.

But more papers do not necessarily mean more breakthroughs. One of the worries we discussed is that AI may accelerate **incremental** work much more than genuinely novel or risky ideas.

### 3. Human judgment becomes more important, not less

One of the strongest conclusions for us is that AI does not remove the need for expertise it changes where that expertise matters most.

If machines can generate text, code, figures, and even reviewer-style feedback, then the scarce skill becomes the ability to evaluate, interpret, and decide. Judgment, taste, and responsibility are not replaced by AI; they become more central.

### 4. AI can genuinely democratize parts of science

Not everything is a downside. We also discussed clear ways in which AI can lower barriers.

For example, it can help researchers understand work outside their immediate field, support non-native English speakers in writing, and make coding more accessible to people who are not primarily programmers. 

### 5. The pace of science is increasing — and that changes how it feels to do research

One thing we both noticed is that AI changes not only what we produce, but also the rhythm of research.

When everything becomes faster, the pressure to keep up also increases. That can be exciting, but it can also leave less time to think, reflect, and develop ideas slowly. The risk is that scientific work becomes more efficient, while the space for deep thinking becomes smaller.

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

<a id="ref-23"></a>[23] [GPTZero finds 100 new hallucinations in NeurIPS 2025 accepted papers](https://gptzero.me/news/neurips/?utm_source=chatgpt.com)

<a id="ref-29"></a>[29] [The machines are fine, I am worried about us](https://ergosphere.blog/posts/the-machines-are-fine/).


## Papers and reports

<a id="ref-24"></a>[24] [The Compute Divide in Machine Learning: A Threat to Academic Contribution and Scrutiny?](https://arxiv.org/abs/2401.02452)

<a id="ref-25"></a>[25] [Relativistic Covariance and Nonlinear Quantum Mechanics: Tomonaga-Schwinger Analysis](https://arxiv.org/abs/2511.15935)

 <a id="ref-26"></a>[26][Steve Hsu on X: post on GPT-5 and theoretical physics research](https://x.com/hsu_steve/status/1996034522308026435)

 <a id="ref-27"></a>[27] [Peer review in the time of artificial intelligence](https://www.nature.com/articles/s41565-026-02177-2)

 <a id="ref-28"></a>[28]  [Pangram Predicts 21% of ICLR Reviews are AI-Generated](https://www.pangram.com/blog/pangram-predicts-21-of-iclr-reviews-are-ai-generated)

## Talks and videos

- [Open-Source and Science in the Era of Foundation Models](https://www.youtube.com/watch?v=yPfrzFzvKSA)
- [Still Far From Achieving Autonomous Closed-Loop Scientific Research — Sam Altman](https://www.youtube.com/watch?v=U2lEJKnQaaw)
- The night science podcast: Google research scientists (TODO: add link)

Note: Illustration from this episode is from [The Turing Way](https://zenodo.org/records/8169292), [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).