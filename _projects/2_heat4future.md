---
layout: page
title: Heat4Future
description: An open-source collaboration for early-stage planning of decarbonized district-heating systems.
img: assets/img/heat4future-overview.jpg
permalink: /projects/heat4future/
importance: 2
category: work
related_publications: false
---

Heat4Future is an open-source collaboration for the preliminary, evidence-based assessment of sustainable district-heating supply systems. It supports strategic planning when detailed local data are not yet available, helping to explore renewable heat sources and thermal storage for a specific location.

The work was developed collaboratively by Nina Kicherer, Pablo Benalcazar, Peter Lorenzen, Olessya Kozlenko, Sadi Tomtulu, and Jan Trosdorff. The tool and its methodology are documented in the open-access MethodsX paper, *Heat4Future: A strategic planning tool for decarbonizing district heating systems*.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/heat4future-overview.jpg" title="Heat4Future workflow" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Heat4Future links heat demand, renewable supply options, and climatic conditions to strategic planning outputs.
</div>

Using minimal user inputs, Heat4Future combines weather and environmental data, thermal-load estimation, thermal-energy storage, and strategic heat-planning modules. It produces hourly profiles of heat demand, generation, and storage over a full year, allowing alternative district-heating configurations to be compared at the outset of a planning process.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/heat4future-modules.jpg" title="Heat4Future modules" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  The four main modules combine user-defined system characteristics with weather and river-temperature data to produce load, generation, and storage results.
</div>

The workflow begins with the location, target year, annual heat demand, building types, and available technologies. It then derives the inputs needed to assess a district-heating configuration, including hourly thermal loads and the operation of buffer and seasonal storage.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/heat4future-hamburg-schedule.jpg" title="Hourly generation schedule for Hamburg in 2050" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Illustrative annual scheduling of renewable and low-carbon heat sources for a Hamburg 2050 case study.
</div>

The Hamburg case illustrates how industrial and urban surplus heat, geothermal energy, heat pumps, combined heat and power, biomass, solar thermal, and seasonal storage can be represented in an hourly supply schedule.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/heat4future-validation.jpg" title="Heat4Future validation comparison" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Comparison of annual heat production from Heat4Future with validation data across the modeled technologies.
</div>

The source code is available on <a href="https://gitlab.com/c4dht/strategic-heat-planning-project">GitLab</a> under the MIT License. Read the <a href="https://doi.org/10.1016/j.mex.2025.103222">open-access paper</a> for the method and its demonstration.
