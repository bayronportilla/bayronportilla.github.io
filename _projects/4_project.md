---
layout: page
title: Secular evolution on hierarchical three body systems
description:
img:
importance: 3
category: MSc
---

Planets and disks have been
observed around binary stars both in circumstellar and in
circumbinary configuration. Statistical trends
  have been stablished for the former case. For example, observations show that the
  ocurrence rate of planets increases with the binary separation
  making it indistinguishable from the single-star case for values beyond 200 au.
  The dynamics of planets in circumstellar and circumbinary configuration is expected
  to be richer than in the single-star case.   

In my masters research project, I studied the secular dynamics of young circumstellar
planets in binary systems. To what extent the change in stellar bulk properties (mass, radius, and luminosity)
during the pre-main-sequence modifies the secular dynamics of the planet? To answer this question,
I derived formulas up to octupolar order for the equations of motion of the
hierarchical system including the conservative
terms due to gravity, the non-conservative
terms due to non-sphericity of the bodies and also
due to tides, and a general relativity
correction to the argument of the pericenter motion. Those were implemented on C-based modular code [(SecDev3B)](https://github.com/bayronportilla/SecDev3B)
which integrates the equations of motion updating the stellar bulk parameters
at each timestep from the output of stellar evolutionary codes.  

I revisited the secular evolution of the highly eccentric planet
HD 80606b assuming constant stellar properties and found that the timescale of evolution
differs greatly when one includes the
octupolar terms because those induce additional modulations on
the eccentricity and semi-major axis evolution. Using stellar evolution tracks, I simulated
a hypothetical circumstellar planet on a $$0.6 \ M_\odot \ (\times 2)$$ binary
and found that the stellar contraction decreases by a factor of two the time it would take for
the orbit of the planet to decay to a half of its initial value. We conclude that
the effect of stellar evolution during the pre-main-sequence
has the potential to alter the orbital configuration of planets in binary systems

In you want to learn more, check out the publication.
