---
title: "Upcoming Meetings"
---

# Upcoming Meeting in winter 2026

* *Februari 5, 2026* from 14.30 to 17.30 at [UvA Science Park](https://www.uva.nl/en/shared-content/locaties/en/sciencepark/science-park.html) in Lab42, room L3.36.

<div style="width: 100%; font-size: smaller; text-align: center; margin-bottom: 8px; margin-top: 8px;">
</div>

<table class="schedule">
    <tr>
        <th style="width:20%">Time</th>
        <th>Program</th>
    </tr>
    <tr class="talk">
        <td>14:30-14:45</td>
        <td>Opening</td>
    </tr>
    <tr class="talk">
        <td>14:45-15:30</td>
        <td> <a href="https://www.cs.ru.nl/~tomc/"> Tom Claassen </a> (Radboud University Nijmegen) - Sound and complete causal inference with background knowledge in the presence of latent confounders and selection bias.
        <br>
        <br>
        Causal discovery from observational data has come a long way over the years. In particular constraint-based approaches come complete with provable guarantees on sound- & completeness, even when latent confounders and selection effects may be present (Zhang,2008). The result is a so-called maximally informative PAG, representing a Markov equivalence class as the output causal model. A downside is that often many edge marks (read ‘causal orientations’) remain undetermined. This is where additional background information can be invaluable, possibly helping to orient many additional edge marks. Meek already showed how to do this for CPDAGs (i.e. without latent confounders) some 30 years go. Recent work by Wang et al. (2022,2024) and Venkateswaran & Perkovic (2025) has made good progress to extend this result to the causally insufficient case for certain types of PAGs, but so far the general task still eludes resolution.
        In this talk I will present a new approach that aims to do just that. It generalises and simplifies some of the orientation rules recently discovered, and adds a few twists to Zhang’s familiar set. The resulting algorithm is very fast in processing arbitrary background information on edge marks in the PAG, even for large graphs. In addition, it can be used to verify consistency between background knowledge and a given PAG, and offers a straightforward way to generate all possible MAGs consistent with a given PAG plus available background info.
        </td>
    </tr>
    <tr class="talk">
        <td>15:45-16:30</td>
        <td> <a href="https://nl.linkedin.com/in/onno-zoeter-75330a2a2"> Onno Zoeter </a> (Booking.com) - When the problem becomes richer than supervised learning. A real-world use of causality in machine learning. 
        <br>
        <br>
        The classic supervised learning problem that is taught in machine learning courses and is the subject of many machine learning competitions is often too narrow to reflect the problems that we face in practice. Historical datasets typically reflect a combination of a source of randomness (for example customers making browsing and buying decisions) and a controlling mechanism such as a ranker or highlighting heuristics (badges, promotions, etc.). Or there might be a selection mechanism (such as the decision to not accept transactions with high fraud risk) that influences the training data. A straightforward regression approach would not be able to disentangle the causal influence of the controller and the phenomenon under study. As a result it risks making incorrect predictions as the controller is changed.  
        In practice however, such problems are typically treated as a classic regression problem in a first iteration and attempts to identify and correct for these complications come as afterthoughts or are not undertaken at all. Ideally there is a rigorous and flexible formalism that captures the correct framing of the problem from the very start, accompanied by a set of practical algorithms that work well in practice for each of the identified cases. In our initial set of successes, structural causal models have proven to be an effective language to express the understanding of the phenomena and to make accurate causal predictions for changes just in the part that is under control, e.g. the ranker, the acceptance policy, etc.   
        This overall research objective is the main goal of the Mercury Machine Learning Lab, one of the labs within Booking AI Research. The Mercury lab is a collaboration between the University of Amsterdam, the Technical University of Delft and Booking.com. It brings together the fields of information retrieval, causality and reinforcement learning where the topic is studied under different names e.g. off-line evaluation, transportability and s-recoverability and off-policy learning. 
        This presentation will sketch the problem, highlight some of the theoretical results so far and describe a significant real-world application. 
        </td>
    </tr>
    <tr class="drinks">
        <td>16:30-17:30</td>
        <td>Drinks at <a target="_blank" href="https://www.cafe-restaurantpolder.nl">Polder</a></td>
    </tr>
</table>