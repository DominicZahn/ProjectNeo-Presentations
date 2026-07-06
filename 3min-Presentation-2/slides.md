---
theme: ./theme
themeConfig:
  paginationX: l
  paginationY: b
  paginationPagesDisabled: 1 2

info: |
  ## 3min Presetionation for Project Neo
drawings:
  persist: false
mdc: true
colorSchema: light

duration: 3min

layout: cover
class: text-right text-white
title: Project Neo
hideInToc: true
transition: slide-left
coverAuthor: Dominic Zahn
coverDate: 7/6/2026
coverBackgroundUrl: /bullet_dodge_neo.webp
---

<h1 style="color: lightgray"><b>Project Neo</b></h1>

<span style="color: white">Fighting the Ghost in the Machine</span>

---
title: Reality
class: text-right
layout: image-right
image: /recordings/whatWeGot.GIF
---

<div class="h-15"/>

<h3 class="text-left" v-click="1">🎯<b>Goal:</b> Head 40cm lower</h3>
<br>
<h3 class="text-left" v-click="1">🚧 <b>Constraints:</b> Dyn. Stability</h3>

<div class="h-15"/>

# What we really got!

<div class="h-15"/>
<h3 class="text-left" v-click="2">✅ Bilateral Contacts</h3>
<br>
<h3 class="text-left" v-click="3">✅ Full sagittal Model</h3>

---
title: How we got here
layout: end
---

# How did we end up here?

---
title: Problems
layout: center
---

# Just happy little Accidents*

<Footnotes>
  <Footnote>*Problems ...</Footnote>
</Footnotes>

<code v-click="1" class="absolute left-4em bottom-6em border-solid border-2 border-red">
  cc: internal compiler error: Segmentation fault signal terminated program cc1<br>
  Please submit a full bug report, with preprocessed source (by using -freport-bug).<br>
</code>
<b v-click="1" class="text-red absolute left-5em bottom-8.5em"><code>gcc</code> limits Size of Dynamics</b>


<code v-click="2" class="absolute left-6em top-6em border-solid border-2 border-red">
  QP solver returned error status 3 (ACADOS_MINSTEP) in SQP iteration 2, QP iteration 23.
</code>
<b v-click="2" class="text-red absolute left-7em top-4em">Convergence Error</b>

<code v-click="3" class="absolute left-13em top-11em border-solid border-2 border-orange text-nowrap">
  lam, pi, S_p, sl, su, A, B, b, Q, R, S, q, r, C, D, lg, ug, P, K,, Lr, pcond_*, f_condH, lbx, ubx, lbu, ubu, ...
</code>
<b v-click="3" class="text-orange absolute left-14em top-8.5em">Acados Symbol Chaos</b>

<code v-click="4" class="absolute left-2em bottom-13em border-solid border-2 border-orange text-nowrap">
  cpin.constraintDynamics(...)
</code>
<b v-click="4" class="text-orange absolute left-3em bottom-13.5em">Pinocchios Contact Model</b>

---
src: ./pages/credits.md
---
<!-- CREDITS -->
---
src: ./pages/appendix.md
---
<!-- APPENDIX -->
