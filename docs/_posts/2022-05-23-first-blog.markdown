---
layout: post
title:  "Welcome to My Blog Posts!"
date:   2022-05-23 10:53:54 +0000
categories: neuroscience cognition language
---

# Time for online presence!

The specific occasion for starting a blog is novel work by Frank van der Velde on the neural blackboard architecture. It addresses the question of how human
language capabilities can be realised by neuronal networks. Although there has been remarkable progress in natural language processing (NLP) and neural machine
translation (NMT) using artificial neural networks, for example using transformers, the question of how humans use language this has not been solved satisfactorily.
In particular the compositional aspect is poorly understood:
the capability of humans to form an astronomical number of grammatical sentences based on a relatively limited vocabulary, but in a
way that sets them apart from the even larger number of word strings that could be formed purely at random.
Language is about who does what to whom, when. If the sentence is grammatical, your average human will be able to do that. This is true for almost every grammatical sentence,
humans can make sense of the roles that each word plays in a sentence,
even if the sentence is semantically nonsense, even when some of the words are pseudo words.
The question of how a clump of noisy spiking neurons can realise this capability is still one of the large mysteries
in science.

The essence of the neural blackboard architecture (NBA) is a few key ideas. First, the idea that groups of neurons collectively firing represents words, concepts, actions.
These neurons are driven by the sensory pathways that they're part of. The advantage of such an idea of neural representation is that neurons are grounded: a group of neurons
firing can be directly
related to seeing an object or hearing a sentence (let's forego the harder problem of imagination for a while). Grounded representations have a directly attributable meaning
and in this way neural representations avoid a problem that has bedevilled artificial intelligence: the symbol grounding problem. This idea was certainly not novel, and many
find this a relatively uncontroversial idea, although there are those who feel, or felt at the time, that neural representations should be distributed and therefore
not localised. But in general, the idea of localised grounded neural representations seems acceptable to many. For language representation, this has consequences and imposes
limitations that are less generally known or accepted. They were pointed about by Jackendoff, for example, when he posed four challenges to neuroscience. Let's examine
one of these in a bit more detail.

If  representations are localised and
presumably the neural representation of 'cat' can't arbitrarily move across the brain: it is a specific group of neurons that code for 'cat', presumably, so the representation
is localised, i.e. remains in situ. (It is probably also defined by a specific firing rate patterns but that doesn't affect the main argument). One consequence is that
neural representations can't be copied easily like strings can be copied in computer memory.
This creates all sorts of problems. As an example, consider the 'problem of 2', exemplified by the sentence 'the little star is beside the big star'. If a specific localised
group of neurons codes for 'star', then how can we use their activation to represent two different instances of the same concept that, moreover, stand in different grammatical
roles with respect to each other?

We opted, again not uniquely, to assume the existence of groups of neurons that represent abstract grammatical roles. If the neurons whose activation represents 'star'
can somehow be temporarily linked to two different abstract role groups, the problem of 2 would be solved. Moreover, if these abstract role neural populations
can link relatively easily
to each other, they can function as a kind switch board. Instead of thousands of groups of neurons, each representing 'words' and 'concepts' somehow linking up diectly to
each other, linking them to a switch
board can realise the combinatorial expressivity of language by a relatively modest amount 'cabling'.


This idea that somehow dynamical linkage between neural populations would account for neural language representation may have surfaced around 2006, when we published
a paper in Brain and Behavioural Sciences describing the NBA, but to my knowledge we were the first to propose a concrete neural model based on these ideas, one
that goes into the details of not only how language can be represented, but also how you can retrieve it, as required for example when answering questions about the
information that is represented in sentences you have just processed.

At the time other proposals were out, sometimes underpinned by significant simulation examples. Notable are the tensor product approach by Smolensky, SHRUTI by Shastri
and collaborators.  The NBA was different by the way it used transient linking between in situ representations.
In a functional architecture, the 'link' between assemblies is more than just some connecting white matter. The links must form for the specific purpose of
representing a sentence. The links must remain active after the sentence has been read, or heard because one would expect a healthy person to be able to answer questions
about the sentence they've just observed. We simulated both the representation process and the question answer process and they suggested that the links should be gated
by well-timed control signals, and be directional. These core ideas remain.

The proposal has drawn considerable critticism, some of it well founded, some of it not so much. The most pertinent criticism was that our proposal required several
blackboards, each representing different grammatical categories. In the new version, this proliferation of blackboards has gone.
The main innovation is a different linguistic basis for the architecture. The original NBA adhered to the
tree-like structures favoured by traditional - in the Chomskian sense - linguistic theories. Frank has worked on the basis of head-dependent structures which are flatter and
only a single blackbord structure is necessary (a possible second one with a phonological role must still be worked out).

In the next series of blog posts I will go more into the detail of the original theory and the criticism it attracted, because this will help to understand where the innovation
comes from. I will then develop my own understanding of the novel NBA structure which will be called head-NBA on specific examples.

Stay tuned.