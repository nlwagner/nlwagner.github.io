---
layout: page
permalink: /research/
title: research
description: a short tour and motivation of my research across the solar system
nav: true
---

My research lies at the intersection of Geophysics, Geodesy, and Geodynamics to investigate the structural, compositional, and thermal state of planetary interiors.
Why should we care about planetary interiors?
Because they help us understand why each planet and moon look and behave so differently from one another!
["Comparative Planetology"](https://en.wikipedia.org/wiki/Comparative_planetary_science) is a central theme across my research.
It basically means that understanding differences in the observed properties of a planet or moon can help us understand others.
The most obvious comparison is to Earth.
Why is Earth special?
Why does life (as far as we know...) only happen here?
Why is Earth the only rocky body with plate tectonics?
It seems Earth's geodynamic evolution plays a role, but how?
This idea extends past Earth towards all the terrestrial planets/moons (Mercury, Venus, our Moon, and Mars).
Why doesn't Mercury have an atmosphere?
Why does Venus have such a thick atmosphere and no magnetic field?
Why is [Tharsis (a large volcanic region on Mars)](https://en.wikipedia.org/wiki/Tharsis) so damn large?
ETC....

To make sense of all of this, I've partaken in research along four(ish) themes that investigate connecting what we currently understand about the interior states of planets and moons today, the initial conditions these bodies started in, and the evolutionary quagmire in between.
Below are short summaries of each of these themes which link to separate pages where I ramble more about work colleagues and I have done across my career. 


<h2>
  <a
    class="research-theme-heading research-link-tidal"
    href="{{ '/research/tidal-tomography/' | relative_url }}"
  >
    Tidal Tomography →
  </a>
</h2>

Tidal Tomography is a relatively new technique in the world of geodesy that offers a way to directly use measurements of very precise changes in the surface height and gravity of a planet or moon to infer how its internal structure varies laterally.
This last phrase is the crux of why this method is revolutionizing our understanding of planetary interiors.
At its core, it aims to answer "How can the changing shape and gravity field of a planetary body reveal its deep internal structure?"
Traditional geodesy uses data, such as tidal $k_2$ and $h_2$, that assume a spherically symmetric interior.
In other words, it assumes the planet these data are measured from is like an onion and only varies as a function of its radius.
This was a great approximation for decades, but as we have started to ask more complicated questions about planetary interiors and data got better, it was realized we need to consider how lateral variations can affect things.
If you want to know more, please click the link above!

<figure class="research-figure" style="max-width: 850px;">

  <img
    src="{{ '/assets/img/tidal-tomography/rovira-navarro2025.jpg' | relative_url }}"
    alt="Illustration of tidal tomography on Ganymede"
    style="width: 100%; height: auto;"
  >

  <figcaption>
    Squishy Ganymede from
    <a
      href="https://doi.org/10.1029/2025GL114708"
      target="_blank"
      rel="noopener"
    >
      Rovira-Navarro et al. (2025)
    </a>.
  </figcaption>

</figure>

---

<h2>
  <a
    class="research-theme-heading research-link-flexure"
    href="{{ '/research/flexure-gravity/' | relative_url }}"
  >
    Lithospheric Flexure &amp; Gravity →
  </a>
</h2>

My Ph.D. dissertation was titled "Deformation of the Martian Lithosphere Through Time" so perhaps it's not a surprise that this theme is present in my research portfolio.
We can distill this entire theme into the question: "How do planetary lithospheres support loads, and what can gravity and topography tell us about their structure and strength?"
The lithosphere of rocky (and icy, literally) bodies behaves a lot like icebergs in the ocean. 
The density difference between ice and water is slightly negative, and thus for any amount of an iceberg sitting above the surface, there is a proportional amount sitting just below the water supporting it.
There is a mathematical tool we use called ["isostasy"](https://en.wikipedia.org/wiki/Isostasy) that represents a balance of forces.
In our iceberg analogy, the pressure across two columns must be equal (called quite creatively equal-pressures or ["Airy"](https://en.wikipedia.org/wiki/George_Biddell_Airy) isostasy).
For an iceberg, this means that the entire iceberg thickness ($H$) must produce the same pressure at depth underneath the iceberg as a column of only water sitting right beside it.
Mathematically, if the density of the ocean is $\rho_{\mathrm{ocean}}$, the density of the iceberg is $\rho_{\mathrm{ice}}$, and the column of water is $W$, then the equivalence between these two columns must be exactly:
\begin{equation}
 \rho_{ice}H = \rho_{ocean}W
\end{equation}
and the exact amount our little iceberg sticks above the waves (let's call $D$) is simply $D = H - W$, and thus
\begin{equation}
D = H\left(1-\frac{\rho_{\mathrm{ice}}}{\rho_{\mathrm{ocean}}}\right).
\end{equation}

If we assume ice to have a density of 900kg/m$^3$ and water to be 1000kg/m$^3$ then with a total iceberg of 100 meters, then only 10 meters of that entire iceberg will be visable above the surface of the water!
This is a simple illustrative example, but mountains, valleys, impact craters, and any other variation in topography or density interface on or in a planet or moon also obey this simple idea
Of course there are ways to make this more complex (see the "equal masses" method of [Hemingway & Matsuyama (2017)](https://doi.org/10.1002/2017GL073334) or ["Pratt"](https://en.wikipedia.org/wiki/John_Pratt_(archdeacon_of_Calcutta)) isostasy), but the basic principle can allow us to probe the near-subsurface of various planetary bodies by only knowing how topography and gravity vary across their surfaces. 
I haven't even discussed where gravity comes into the picture here, but I've rambled enough in this "short" summary of this theme.

If you want to know more, please click the link above!

---

<h2>
  <a
    class="research-theme-heading research-link-geodynamics"
    href="{{ '/research/geodynamics/' | relative_url }}"
  >
    Planetary Geodynamics &amp; Evolution →
  </a>
</h2>

How do planetary interiors and lithospheres deform and evolve through time?

If you want to know more, please click the link above!


---

<h2>
  <a
    class="research-theme-heading research-link-mission"
    href="{{ '/research/mission-science/' | relative_url }}"
  >
    Mission Science &amp; Development →
  </a>
</h2>

What measurements are needed to distinguish between competing models of planetary interiors and geological evolution?

If you want to know more, please click the link above!


---

{% nocite rovira-navarro2025 Hemingway2017 --file research_refs %}
## References

{% bibliography --file research_refs --cited_in_order --group_by none --template research_ref %}



