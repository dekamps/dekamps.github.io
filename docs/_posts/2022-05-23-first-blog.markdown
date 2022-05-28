---
layout: post
title:  "Welcome to My Blog Posts!"
date:   2022-05-23 10:53:54 +0000
categories: neuroscience cognition language
---

# Time for online presence!

The specific occasion for starting a blog is novel work by Frank van der Velde on the neural blackboard architecture. It addresses the question of how human
language capabilities can be realised by neuronal networks. Although there has been remarkable progress in natural language processing (NLP) and neural machine
translation (NMT) using artificial neural networks, in particular so-called transformers, the question of how humans do this has not been solved satisfactorily.
In particular the compositional aspect is poorly understood:
the capability of humans to form an astronomical number of grammatical sentences based on a relatively limited vocabulary, but in a
way that sets them apart from the even larger number of word strings that could be formed purely at random.
Language is a bout who does what to whom, when, and if the sentence is grammatical, your average human will be able to make sense of the roles that each word plays in a sentence,
even if the sentence is semantically nonsense. The question of how a clump of noisy spiking neurons can realise this capability is still one o the large mysteries
of science.

The essence of the neural blackboard architecture (NBA) is the idea that groups of neurons collectively firing represents words, concepts, actions. These neurons are driven
by the sensory pathways that they're part of. The advantage of such an idea of neural representation is that neurons are grounded: a group of neurons firing can be directly
related to seeing an object or hearing a sentence (let's forego the harder problem of imagination for a while). Grounded representations have a directly attributable meaning
and in this way neural representations avoid a problem that has bedevilled artificial intelligence: the symbol grounding problem. The representations are localised and
presumably the neural representation of 'cat' can't arbitrarily move across the brain: it is a specific group of neurons that code for 'cat', presumably, so the representation
is localised, i.e. remains in situ. (It is probably also defined by a specific firing rate patterns but that doesn't affect the main argument). One consequence is that
neural representations can't be copied easily like strings can be copied in computer memory.


This creates all sorts of problems. As an example, consider the 'problem of 2', exemplified by the sentence 'the little star is beside the big star'. If a specific localised
group of neurons codes for 'star', how can we use their activation to represent two different instances of the same concept that moreover stand in different grammatical
roles with respect to each other? We opted for the existence of groups of neurons that represent abstract grammatical roles. If the neurons whose activation represents 'star'
can somehow be temporarily linked to two different abstract role groups, the problem of 2 would be solved. Moreover, if these abstract role neurons can link relatively easily
to each other, they can function as a kind switch board. Instead of thousands of groups of neurons somehow linking up all to each other, if each group can link to the switch
board the combinatorial expressivity of language can be realised by a relatively modest amount 'cabling'.

In a functional architecture, the 'link' between assemblies is more than just some connecting white matter. The links must be able to form for the specific purpose of
representing a sentence. The links must remain active after the sentence has been read, or heard because one would expect a healthy person to be able to answer questions
about the sentence they've just observed. We simulated both the representation process and the question answer process and they suggested that the links should be gated
by well-timed control signals.

The proposal has drawn considerable critticism, some of it well founded, some of it not so much. The most pertinent criticism was that our proposal required several
blackboards, each representing different grammatical categories.

In the new version, this proliferation of blackboards has gone. The main innovation is a different linguistic basis for the architecture. The original NBA adhered to the
tree-like structures favoured by traditional - in the Chomskian sense - linguistic theories. Frank has worked on the basis of head-dependent structures which are flatter and
only a single blackbord structure is necessary (a possible second one with a phonological role must still be worked out).

In the next series of blog posts I will go more into the detail of the original theory and the criticism it attracted, because this will help to understand where the innovation
comes from. I will then develop my own understanding of the novel NBA structure which will be called head-NBA on specific examples.

Stay tuned.