+++
date = "2016-06-25T17:28:01+01:00"
draft = true
title = "Modern-love"
pagetype = "project"
gitrepo = "https://github.com/technicalities/modern-love"
tech = ["php", "laravel"]
shortdesc = "A visualiser for sexualities"
+++

# Modern-love

<div id="epigram">There are two [kinds] of people in the world; those who constantly divide the people of the world into two kinds, and those who do not. (<a href="http://quoteinvestigator.com/2014/02/07/two-classes/">Robert Benchley</a>)</div>

<p>This site is, or will be, a visual guide to the modern explosion of conceivable romantic and sexual identities. Before, popularly, there was a simple dichotomy between straight and gay. Now, there are many continuous grades along many different lines - including not expressing any at all.
</p>

<p>This is very exciting for everyone! It doesn't matter if, like me, your apparently honest preferences are actually quite near to the old package deal; we all benefit from the end of unreflective and unfree sex - even if we subsequently remain much the same. Choice dignifies (or, in the <a href="https://en.wikipedia.org/wiki/Biology_and_sexual_orientation">hypothesised</a> absence of choice, insight does).</p>

<p>But it is hard to think clearly about these things. I find it helpful to see sex as a high-dimensionality space which suddenly has a half a dozen <a href="https://en.wikipedia.org/wiki/Degrees_of_freedom_%28statistics%29">degrees of freedom</a>. Luckily, even things like these can be represented very intuitively with graphics. Many people dislike being measured; many more dislike labels. But in my experience, humans like pictures and need words.</p>

<h3>Planned Features</h3>


1. A breakdown into seven+ continuous sliders.
2. Rotatable 3D graph of any three at once.
3. Maybe best to have a comic diagram of stick figures as well. WebGL project #1.
4. Outputs the current academic and tumblr jargon for the triangulation.
5. Also demographics, including legal discrimination around the world.
6. A string representation of your settings, a la the <a href="https://en.wikipedia.org/wiki/Geek_Code">Geek Code</a>.
7. Option to post your (anonymous!) data for a long-term survey into the diffusion of these ideas.
8. Take Questionnaire / Skip to data (Typeformesque)
9. A string representation of your settings.
10. Graphing any 3 of the seven dimensions.
11. Animations!
12. Allowing dynamic identities to be represented.

<br>LATER<br><br>
13. Estimate compatibility given two modstrings with confidence levels (and gender, obviously).  
14. Checkbox: "I don't like numbers".  
15. Add confidence levels for each variable. (Makes each axis 2D.)  
16. Function for getting graph output from modstring input.  
17. Empirical backing. (Who has open data? OKCupid research?)


<h3>Why model romance?</h3>

For a long time, sex and love followed a strict script. If you wanted to avoid spontaneous violence and life-long ostracision, you lived according to that script. The package varied over the years, but a recent form was: "find and love one person of the opposite gender and have sex with only them; live and breed with them forever; if you don't like sex then you are defective; if you find anything except genitals erotic then you are defective".

A mass of brave people are to thank for this unprecedented latitude: mostly feminists and hippies and queers. However, the academic forms that have grown on these movements are by and large totally unreadable. So you're stuck trying to sift the blogosphere of the predominating useless noise looking for well-written, rigorous signal.

The options are actually never binary, and most of us find it hard to think about spectrums. Here is a visual approach.
<br><br><ul>
<li>For understanding. The new options are confusing at first, and unfamiliar, and existing guides are full of jargon.
<li>For exploration. Emphasise the breadth of the possible space.
<li>For communication. Could plausibly prevent emotional damage if we were clearer with each other about what we need. Actual measures of compatibility are covered, dubiously, elsewhere.
<li>For Science! I will eventually implement an (optional!) survey in order to get a regional and gender and age-based map of the modern world.
<li>I want to learn WebGL.  
</ul>


<p>At the moment there are seven variables in <a href="{{ url('/model') }}">the site's model of romance</a> (see <a href="{{ url('/soproblematic') }}">the Problems page</a> for admissions of inadequacy as well as ideas for future depth and rigour): Libido, romantic intensity, orientation, synchrony, exclusivity, paraphilia, and natalism.</p>

<p>(I <i>like</i> naming concepts - but I'm aware that it's foolish to counter jargon with more Latinate neologisms; the final version will expand these into full questions: e.g. "To what degree are you?" and present intuitive sliders.)</p>
