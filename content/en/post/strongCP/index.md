---
title: A General Introduction to the Strong CP Problem
summary: An introduction about strong CP problem and its solutions. Readers are assumed to have basic knowledge of quantum field theory, but not more.
author: admin
tags:
  - strong CP problem
  - dark matter
  - parity
  - left-right symmetry
  - physics
  - research
  - baryogenesis
date: '2023-08-13'
reading_time: true
# Optional external URL for project (replaces project detail page).
external_link: ''
share: false
image:
   focal_point:
   preview_only: true

# links:
#   - icon: paperclip
#     icon_pack: fab
#     name: 
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

*Written for people not familiar with this topic. Experts may find it trivial.*

{{< toc >}}


## A Description for the Strong CP problem

It has been a long time since we found that the Standard Model (SM) is a **chiral** theory, i.e. left and right-handed particles have different properties.
Though it could be a natural, or simple, feeling, to claim that a beautiful model should be left-right symmetric, it does not seem cautious to impose this symmetry when we consider beyond Standard Model (BSM) physics until we find some really solid reason.
Fortunately, there is a problem, known as the *strong CP problem*, that can be solved eligantly under the left-right symmetry, or known in a more professional phrase, *parity symmetry*.

So, what is strong CP problem, and how parity symmetry can solve it?

Perhaps you have heard about the neutron electric dipole moment (EDM). What can the dipole moment be?

A naive calculation from classical physics is straightforward: the neutron contains one up-quark and two down-quarks. One can easily build a coordiante system and label the angle {{< math >}}$\theta${{< /math >}} in a way shown in the following picture. Apparently the dipole moment is
{{< math >}}
$$
\frac{d_n}{e} \simeq 10^{-13} \sqrt{1-\cos \theta}~\mathrm{cm}
$$
{{< /math >}}


{{< figure src="featured.png" width="50%" caption="A classical description for the neutron EDM and the strong CP phase. Taken from [Anson Hook's lecture note](https://inspirehep.net/literature/1707528).">}}

If there is no force to make the angle {{< math >}}$\theta${{< /math >}} some fixed value, we would expect this angle is randomly distributed, and thus the neutron EDM. However, current experiment has shown this number to be always close to zero: we never observe any single neutron with an EDM larger than {{< math >}}$10^{-26}e~\rm cm${{< /math >}}!

This immediately implies the vanishing of the {{< math >}}$\theta${{< /math >}} term. But why?

The vanishing of this {{< math >}}$\theta${{< /math >}} is called the *strong CP problem*. Strictly speaking, strong CP problem is not a solid problem. You can just accept it and claim it as a coincidence. But, perhaps it's a long-standing pursue of particle physics community, it's just difficult for us to accept such a unnaturally small parameter in a model.

If you can't accept it and must turn to solid problems like dark matter, emmmmmm, there is no objection. And as far as I know, the number of people who believe "strong CP problem is a problem" is as much as those who does not believe so. Just take it easy and think about it in a way you want.


You may wonder are there any quantum-level description of the above stuff. Yes. In SM, we can chirally rotate the quark fields like {{< math >}}$\psi \rightarrow \psi e^{i \gamma_5 \theta_s}${{< /math >}}, and the Lagrangian acquires an extra term (if you are not familiar with this, you can refer to Chapter 29 and 30 of Matthew Schwartz's textbook for quantum field theory)
{{< math >}}
$$
\mathcal{L} \rightarrow \mathcal{L} + \theta_s\frac{g_s^2}{32\pi^2} G_{\mu \nu} \tilde{G}^{\mu \nu},
$$
{{< /math >}}
where the {{< math >}}$G${{< /math >}} field is the gluon field.
Actually, since the fermion fields are not observable and can be written in any basis, the above term is generally existing and must be included in the Lagrangian.
Rotating the quark field can shift the angle {{< math >}}$\theta_s${{< /math >}} into {{< math >}}$\arg (Y_u Y_d)${{< /math >}}, where {{< math >}}$Y_{u,d}${{< /math >}} is the Yukawa matrix.
The difference, on the other hand, {{< math >}}$\bar{\theta} \equiv \theta_s -\arg (Y_u Y_d) ${{< /math >}}, will not be changed and thus is physical!

Computation shows that this angle is indeed proportional to the neutron EDM
{{< math >}}
$$
\frac{d_n}{e} \simeq 5 \times 10^{-16} \bar{\theta}~\mathrm{cm}.
$$
{{< /math >}}
So the smallness of this {{< math >}}$\bar{\theta}${{< /math >}} is the strong CP problem.

## Parity solution
We can immediately think about it in this way: there must be some rules that forces the quarks to be aligned along a straight line! One possibility is that the neutron must be left-right symmetric, or parity-symmetric. And thus strong CP problem is solved.
The parity symmetry at the quantum level can be described as
{{< math >}}
$$
SU(2)_L \leftrightarrow SU(2)_R, Q \leftrightarrow \bar{Q}, L \leftrightarrow \bar{L}, H_L \leftrightarrow H_R.
$$
{{< /math >}}
Here we use the [two-component Weyl notation for fermions](https://inspirehep.net/literature/804666). {{< math >}}$Q${{< /math >}} and {{< math >}}$L${{< /math >}} are quarks and leptons, respectively. Right-handed fermions are doublets under {{< math >}}$SU(2)_R${{< /math >}}. You can easily prove that this makes {{< math >}}$\bar{\theta}${{< /math >}} vanishes at tree level.

This solution is called the *parity solution* to the strong CP problem.

## Axion solution

Another way to think about this problem is: maybe there is an "axis" where the quarks are forced to be aligned along?

Emmmm yeah that's possible. At quantum level, we say there is a new particle whose vacuum expectation value (vev) makes the neutron EDM to be 0. This particle is called *QCD axion*.
The Lagrangian is
{{< math >}}
$$
\mathcal{L} = \frac{a}{f_a} \frac{g_s}{32\pi^2} G_{\mu \nu} \tilde{G}^{\mu \nu} + \frac{1}{2} \partial_\mu a \partial^\mu a
$$
{{< /math >}}

The axion vev is acquired when {{< math >}}$\langle a \rangle /f_a = - \theta_s${{< /math >}}. This cancels the anomaly term and thus the strong CP problem is solved. For the details of the potential of {{< math >}}$\theta_s${{< /math >}} term and axion, see [Anson Hook's lecture note](https://inspirehep.net/literature/1707528).

The Lagrangian itself is not a UV-complete theory. The UV model can be various, but in common, axion is the angular degree of freedom of some complex scalar {{< math >}}$P${{< /math >}}. The potential of {{< math >}}$P${{< /math >}} at UV has a {{< math >}}$U(1)${{< /math >}} rotational symmetry called Peccei-Quinn symmetry. The radial mode of the field {{< math >}}$P${{< /math >}} acquires a vev that breaks the PQ symmetry, and thus axion becomes the Nambu-Goldstone boson of {{< math >}}$U(1)_{\rm PQ}${{< /math >}}. {{< math >}}$f_a${{< /math >}} is the symmetry breaking scale, also the radius of the axion rotation. We call it *axion decay constant*.

QCD axion is also a good dark matter candidate. And further, [a recent idea](https://inspirehep.net/literature/1757727) proposes to utilize the initial axion rotation to generate the baryon asymmetry of the universe. This new mechanism, similar to the famous Affleck-Dine baryogenesis with axion playing the role of the scalar, is named as *axiogenesis*. Axion rotation and axiogenesis is one of the interesting and promising direction in the recent particle physics community.