---
theme: seriph
layout: cover
author: Martinus Suijkerbuijk
# Using a direct static Unsplash image to guarantee a full bleed cover scale
background: /TerraSentinel.png
title: 'The Counterstack'
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# CHANGED: Swapped to text-left so it doesn't break your grid container
class: text-left
drawings:
  persist: false
transition: fade-out
comark: true
duration: 35min

# favicon, can be a local file path or URL
favicon: '/favicon.png'

fonts:
  sans: 'Inter'
  serif: 'Playfair Display'
---

<div class="h-full w-full flex flex-col justify-center max-w-xl px-12 py-12 text-left">

<h1 class="text-5xl font-bold leading-tight text-white font-sans">
  The Counterstack: Building Infrastructure for Climate Accountablity
  
</h1>

<p class="text-m opacity-80 mt-4 text-gray-200">
  Martinus Suijkerbuijk | NTNU
</p>

<p class="text-xs opacity-80 mt-4 text-gray-300">
  09_06_2026 | Berlin
</p>

<div @click="$slidev.nav.next" class="mt-12 py-1 cursor-pointer inline-block self-start opacity-60 hover:opacity-100 transition text-sm text-white">
   START<carbon:arrow-right class="inline align-middle ml-1" />
</div>

</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

<h1 class="text-2xl font-bold leading-tight px-12 py-12 text-white font-sans">
We have excellent climate justice theory and active frontline communities. What we lack is the <b>infrastructure that connects investigation to law, and community testimony to court-ready evidence</b>.<br><br>Not a product. <br><br>Not a platform. <br><br>A commons stack—an intentional, justice-oriented apparatus built on <b>protocol logic, not platform logic</b>.</h1>
<br>
<br>


<!--
“I do correlate that to AI in part because I see AI use,” she says. As a tech-savvy judge who uses AI to vet court documents, she’s learned to recognize how large language models write. She can tell from the prose and at times, hallucinated cases and fabricated quotes. 

“I’m also actually seeing better-drafted pleadings,” she says. 
-->

<style>
h1 {
  background-color: #ffffff;
  background-image: linear-gradient(45deg, #afafaf 10%, #8f8f8f 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: fade-out
level: 2
class: text-left
---

<div class="px-12">
<h1 class="text-3xl font-bold leading-tight px-12 py-12 text-white font-sans">Ecologies of Violence</h1>

<div class="text-l font-regular leading-tight text-white font-sans">
  <b>Temporal Asymmetry</b> Climate and infrastructure violence operates across multiple scales and temporalities:<br>
  - <b>Fast violence</b> (deportations, police raids, facility seizures) is operationalized with precision<br>
  - <b>Slow violence</b> (aquifer depletion, e-waste exposure, soil contamination) is externalized, pushed downstream to communities with no power to refuse<br><br>

  <b>Structural violence</b> (liability caps, jurisdictional fragmentation, classification regimes) is naturalized—treated as inevitable features of "how systems work"<br>
  <b>Extractive violence</b> (mineral supply chains, energy infrastructure, data economies) is disavowed—rendered invisible, costs pushed offshore<br>
</div>
<br>

<b>Data infrastructure alone does not produce justice.</b> Visibility without forum, without standing, without power rebalancing, produces spectacle. We need something different.

</div>

---
class: text-left
---

<div class="px-12">

<h1 class="text-3xl font-bold leading-tight py-12 text-white font-sans">DESIGN CONSTRAINTS</h1>

```
Temporal Asymmetry
Standing Doctrine Pluralism
Remedy Frameworks (What Courts Can Actually Award)
Authority & Decentralization
```

The title will be inferred from your slide content, or you can override it with `title` and `level` in your frontmatter.
</div>

---
transition: fade-out
---

**The Problem:** Legal forums operate on fast/present timescales. Environmental harm is slow/cumulative. These temporalities don't align.


| Jurisdiction                          | Individual + Direct Harm | Distributed/Future Harm | Ecosystem Standing  | Realistic Timeline         |
| ------------------------------------- | ------------------------ | ----------------------- | ------------------- | -------------------------- |
| **US Federal Courts**                 | ✅ Required               | ❌ Narrow                | ❌ No                | 3-7 years                  |
| **Germany (Constitutional)**          | ✅ Yes                    | ✅ Future generations    | ⚠️ Proxy argument   | 2-3 years                  |
| **Philippines**                       | ✅ Yes                    | ✅ Emerging              | ✅ Rights-based      | 2-4 years                  |
| **Colombia/Peru**                     | ✅ Yes                    | ✅ Yes                   | ✅ Rights of Nature  | 2-4 years                  |
| **India (Supreme Court)**             | ✅ Yes                    | ✅ Yes                   | ✅ Ganges personhood | 2-5 years                  |
| **New Zealand**                       | ✅ Yes                    | ✅ Yes                   | ✅ Rivers as persons | 1-3 years                  |
| **Regional HR Courts (ECHR, IACTHR)** | ✅ Yes                    | ✅ Yes                   | ⚠️ Indirect         | 4-6 years, 3-5 years       |
| **UN Bodies**                         | ✅ Civil society          | ✅ Yes                   | ✅ Yes               | 2 years (per 5-year cycle) |


<!-- Footer -->

[OpenGlobalRights](https://www.openglobalrights.org/human-rights-victims-complaints-to-un-not-treated-effectively/)


<!--
Notes can also sync with clicks

[click] This will be highlighted after the first click

[click] Highlighted with `count = ref(0)`

[click:3] Last click (skip two clicks)
-->
---

| Forum | Standing Doctrine | Evidence Standard | Court-Ready Evidence Types | Timeline | Realistic Remedies |
|---|---|---|---|---|---|
| **Germany (Constitutional Court)** | Constitutional duty to climate; future generations; youth | High (expert qualification, methodology transparent) | Climate science + national emissions data + forecasting models | 2-3 yrs | Binding emissions targets; policy mandates |
| **Philippines (Supreme Court)** | Human rights + future generations (expanding) | Medium-high (flexible but documented) | Impact projections + generational equity analysis + climate attribution | 2-4 yrs | Rights recognition; adaptation mandates |
| **India (Supreme Court)** | Right to life + PIL; Ganges as legal entity | Medium (PIL accepts broad evidence) | Water quality data + ecological monitoring + contamination evidence | 2-5 yrs | Restoration orders; corporate liability |
| **Colombia (Constitutional Court)** | Rights of Nature (Atrato River model) | Medium (accepts OSINT if documented) | Satellite imagery + ecosystem monitoring + supply chain analysis | 2-4 yrs | Restoration; territorial protection |
| **Peru (Constitutional/Superior Courts)** | Indigenous rights + environmental rights | Medium | Agronomic data + satellite + indigenous testimony | 2-4 yrs | Restoration; damages; license revocation |
| **New Zealand (Courts)** | Rivers as legal persons (Te Awa Tupuranga) | Medium (flexible) | Ecological monitoring + OSINT + expert testimony | 1-3 yrs | Management mandates; restoration |

**Evidence is NOT court-ready in:**
- US Federal Courts (standing narrow; Daubert standard strict; 10+ year timeline)
- UK Courts (evidentiary thresholds high; common law hearsay rules strict)

---
title: Architecture
---

<h1 class="text-2xl font-regular leading-tight px-12 py-12 text-white font-sans">Three Approaches:</h1>


<p v-click>

</p>

<div class="grid px-12 gap-3 mt-4 text-sm" style="grid-template-columns: repeat(3, 3fr) 1.5fr 1fr">
  <div v-after.up class="p-3 rounded border border-primary/20 bg-primary/10">
    <div class="font-mono text-xs opacity-60 mb-1">AI-assisted harvesting and structuring of evidence across jurisdictions and source types.</div>
    <div>Agentic Engine</div>
  </div>
  <div v-click.fade-in class="p-3 rounded border border-primary/20 bg-primary/10">
    <div class="font-mono text-xs opacity-60 mb-1">Visualize relational and ontological networks—not just spatial relationships.</div>
    <div>Network-of-Complicity</div>
  </div>
  <div v-click.fade-in class="p-3 rounded border border-primary/20 bg-primary/10">
    <div class="font-mono text-xs opacity-60 mb-1">Represent harm across temporal scales and causation across jurisdictions.</div>
    <div>Evidence-Based Timeline</div>
  </div>
</div>


<div v-click mt-12 px-12>

[Protocol Logic](https://sli.dev/guide/animations#click-animation)

</div>


<!--
Here is another comment.
-->

---
transition: fade-out
layout: image-right
image: /graph.png
title: Architecture
---

<div class="relative z-10 h-full w-full flex flex-col justify-left items-center text-center">
  <h1 class="text-3xl font-bold leading-tight py-12 text-white font-sans">Architecture</h1>

</div>


---
title: TerraSentinel
---

<div 
  class="absolute inset-0 w-full h-full bg-cover bg-center z-0" 
  style="background-image: url('/TerraSentinel.png');opacity: 50% !important;"
></div>

<div class="relative z-10 h-full w-full flex flex-col justify-left items-center text-center">
<h1 class="text-3xl font-bold leading-tight py-12 text-white font-sans">Data-Driven Climate Accountability</h1>


</div>

<style>
.slidev-layout, 
.slidev-content,
#page-root,
section {
  height: 100% !important;
  width: 100% !important;
  max-height: 100vh !important;
  padding: 0 !important;
  margin: 0 !important;
  
}
</style>

---
layout: default
title: ShadowCorpus
---

# Live Dashboard: ShadowCorpus

<div class="w-full h-[75vh] mt-4 rounded-lg overflow-hidden border border-zinc-800">
  <iframe 
    src="http://localhost:5173/" 
    class="absolute top-0 left-0 border-none origin-top-left"
    style="
      width: 133.33%; 
      height: 133.33%; 
      transform: scale(0.75);
    "
    allow="autoplay; encrypted-media" 
    allowfullscreen
  ></iframe>
</div>


---
layout: cover
title: QuickRag
---

<div 
  class="absolute inset-0 w-full h-full bg-cover bg-center z-0" 
  style="background-image: url('https://www.palantir.com/q1-2026-letter/en/');opacity: 100% !important;"
></div>

<div class="relative z-10 h-full w-full flex flex-col justify-left items-center text-center">
<h1 class="text-3xl font-bold leading-tight py-12 text-white font-sans">Evidence-Generated Timeline</h1>


</div>

<style>
.slidev-layout, 
.slidev-content,
#page-root,
section {
  height: 100% !important;
  width: 100% !important;
  max-height: 100vh !important;
  padding: 0 !important;
  margin: 0 !important;
  
}
</style>

<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->


---
layout: cover
title: QuickRag
---

<div 
  class="absolute inset-0 w-full h-full bg-cover bg-center z-0" 
  style="background-image: url('/QuickRag.jpg');opacity: 100% !important;"
></div>

<div class="relative z-10 h-full w-full flex flex-col justify-left items-center text-center">
<h1 class="text-3xl font-bold leading-tight py-12 text-white font-sans">Evidence-Generated Timeline</h1>


</div>

<style>
.slidev-layout, 
.slidev-content,
#page-root,
section {
  height: 100% !important;
  width: 100% !important;
  max-height: 100vh !important;
  padding: 0 !important;
  margin: 0 !important;
  
}
</style>

<!--
Presenter note with **bold**, *italic*, and ~~striked~~ text.

Also, HTML elements are valid:
<div class="flex w-full">
  <span style="flex-grow: 1;">Left content</span>
  <span>Right content</span>
</div>
-->

