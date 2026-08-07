---
layout: page
title: Grade 7
---

### Grade 7 Resources

Resources aligned to the Grade 7 NL curriculum: physical sciences and the Earth's crust. Here you'll find worksheets, demos, and activity ideas.

<input type="text" id="page-search" placeholder="Search this page for keywords..." 
  style="width: 100%; max-width: 500px; padding: 10px 14px; font-size: 1rem; border: 1px solid #ccc; border-radius: 6px; margin: 1.5rem 0; display: block;">

<script>
document.getElementById('page-search').addEventListener('input', function() {
  var query = this.value.toLowerCase();
  var cards = document.querySelectorAll('.resource-card');
  var dividers = document.querySelectorAll('.section-divider');

  cards.forEach(function(card) {
    var text = card.textContent.toLowerCase();
    var match = text.includes(query);
    card.style.display = match ? '' : 'none';

    // Find the divider right before this card and match its visibility
    var divider = card.previousElementSibling;
    if (divider && divider.classList.contains('section-divider')) {
      divider.style.display = match ? '' : 'none';
    }
  });
});
</script>

<style>
.resource-card {
  display: flex;
  gap: 20px;
  align-items: flex-start;
  margin: 2rem 0;
  padding: 1.5rem;
  border-radius: 8px;
  background: #f7f7f7;
}
.resource-thumb {
  width: 120px;
  height: 150px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  flex-shrink: 0;
}
.resource-title {
  font-weight: bold;
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}
.resource-desc {
  margin-bottom: 1rem;
}
.resource-links {
  display: flex;
  flex-direction: column;
  gap: 8px;
}
.resource-links a {
  font-weight: bold;
}
</style>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/mineral_preview.png">
  <div>
    <div class="resource-title">A Mineralogist's Mystery</div>
    <div class="resource-desc">
Students take on the role of a mineralogist tasked with identifying unknown minerals from a Labrador mine site, using tests for colour, lustre, streak, hardness, and other properties to solve the case. Includes the Science 7 textbook lab manual and a student handout.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/mineral_lab.docx">Download Student Handout (.docx)</a>
      <a href="/assets/resources/mineral_manual.pdf">Download Lab Manual (.pdf)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/igneous_preview.png">
  <div>
    <div class="resource-title">Igneous Rocks: Cooling Rate and Crystal Size</div>
    <div class="resource-desc">
A MUNGO-made experiment using Epsom salt solutions cooled at different rates to model how igneous rocks form, comparing slow "plutonic" cooling (large crystals) to fast "volcanic" cooling (tiny crystals). Guides students through the full scientific method, from hypothesis to conclusions. Includes a student lab handout.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/igneous_rocks_lab.docx">Download Student Handout (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/sedimentary_rock_preview.png">
  <div>
    <div class="resource-title">Sedimentary Rock Demonstration</div>
    <div class="resource-desc">
A MUNGO-made 19-minute classroom demonstration using a "sedimentator tube" to show how sediment settles by grain size and lithifies into conglomerate, sandstone, and shale. Covers erosion, deposition and sorting, rock classification, and lithification through compaction and cementation. Includes a demonstration plan.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/sedimentary_rock_demonstration.docx">Download Demonstration Plan (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/metamorphic_preview.png">
  <div>
    <div class="resource-title">Metamorphic Rocks: Modelling Foliation with Play-Doh and Pennies</div>
    <div class="resource-desc">
A MUNGO-made hands-on activity using Play-Doh and pennies to model how pressure aligns minerals into layers, forming a foliated metamorphic rock like schist. Includes a comparison with granite and gneiss samples to show how foliation helps identify metamorphic rocks.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/metamorphic_rocks.docx">Download Student Handout (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/earth_layers_preview.png">
  <div>
    <div class="resource-title">Make Your Own Earth Layers Model</div>
    <div class="resource-desc">
A MUNGO-made hands-on activity where students cut, stack, and glue colored paper circles to build a labelled model of Earth's layers. Includes student and teacher versions, plus a ready-to-photocopy sheet of Earth layer cutouts.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/earth_layer_student.docx">Download Student Version (.docx)</a>
      <a href="/assets/resources/earth_layer_teacher.docx">Download Teacher Version (.docx)</a>
      <a href="/assets/resources/earth_layer_photocopy.docx">Download Earth Layer Cutouts (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/burin_STSE_preview.png">
  <div>
    <div class="resource-title">Waves of Disaster: The 1929 Grand Banks Earthquake & Burin Peninsula Tsunami</div>
    <div class="resource-desc">
A MUNGO-made STSE activity examining the 1929 Grand Banks earthquake and the tsunami it triggered on the Burin Peninsula. Students analyze cable-break data to understand how the event unfolded, then explore the science, technology, and societal questions around tsunami warning systems in the Atlantic.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/burin_STSE_student.docx">Download Student Version (.docx)</a>
      <a href="/assets/resources/burin_STSE_teacher.docx">Download Teacher Version (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/destruction_preview.png">
  <div>
    <div class="resource-title">STEM Challenge: Resisting Destruction from Earthquakes</div>
    <div class="resource-desc">
A MUNGO-made engineering design challenge where students build earthquake-resistant towers from linguini and marshmallows, then test them on a DIY shake table. Walks through the full engineering design process, from background earthquake science to building, testing, and reflecting. Includes lesson plans for two class-length options, a grading rubric, and a teacher's answer key (teacher version only).
    </div>
    <div class="resource-links">
      <a href="/assets/resources/resisting_destruction.docx">Download Teacher Version (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/geologist_job1_preview.png">
  <div>
    <div class="resource-title">STEM JOBS: Geologist</div>
    <div class="resource-desc">
A career-focused reading resource for Grade 7 students. Covers what geology is, the different types of geologists, and what it takes to pursue the career, with a short answer and multiple-choice quiz at the end to check understanding.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/geologist_job2_student.pdf">Download Student Version (.pdf)</a>
      <a href="/assets/resources/geologist_job2_teacher.pdf">Download Teacher Version (.pdf)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/core_concepts_preview.png">
  <div>
    <div class="resource-title">Core Concepts</div>
    <div class="resource-desc">
      A set of classroom-ready activities covering foundational Earth science concepts. Hands-on and self-contained, so no prior teacher training workshop is needed to use them. Provided by <a href="https://miningmatters.ca" target="_blank">Mining Matters</a>.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/core_concepts.pdf">Download PDF</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/erosion_prevention_preview.png">
  <div>
    <div class="resource-title">Erosion Prevention Activity</div>
    <div class="resource-desc">
      Students design, build, and test their own erosion-prevention system, then evaluate how well it holds up under 1 L of water poured over a mud mountain. Provided by <a href="https://miningmatters.ca" target="_blank">Mining Matters</a>.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/erosion_prevention.pdf">Download PDF</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/folding_faulting_preview.png">
  <div>
    <div class="resource-title">Folding and Faulting: Play-Dough Mountain Building</div>
    <div class="resource-desc">
      A hands-on model using layered Play-Doh to simulate folding and erosion, a quick Popsicle-stick demo showing how brittle rock breaks to form faults, and more. Provided by <a href="https://miningmatters.ca" target="_blank">Mining Matters</a>.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/folding_faulting.pdf">Download PDF</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/rock_cycle_CMM_preview.png">
  <div>
    <div class="resource-title">The Rock Cycle</div>
    <div class="resource-desc">
      A poster from the Canadian Museum of Nature illustrating the rock cycle and how rocks transform between igneous, sedimentary, and metamorphic forms. Provided by <a href="https://miningmatters.ca" target="_blank">Mining Matters</a>.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/rock_cycle_CMM.pdf">Download PDF</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/soil_sleuth_preview.png">
  <div>
    <div class="resource-title">Be a Soil Sleuth Lab</div>
    <div class="resource-desc">
      A hands-on lab where students test a soil sample against clay, sand, and gravel using simple drainage tests to identify its characteristics. Includes student worksheet, teacher version, and the accompanying lab manual from the Science 7 textbook.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/soil_sleuth_lab.pdf">Download Lab Manual (.pdf)</a>
      <a href="/assets/resources/soil_sleuth_student.pdf">Download Student Version (.pdf)</a>
      <a href="/assets/resources/soil_sleuth_teacher.pdf">Download Teacher Version (.pdf)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/wegener_preview.png">
  <div>
    <div class="resource-title">Continental Drift Activity</div>
    <div class="resource-desc">
      A <a href="https://www.usgs.gov" target="_blank">USGS</a> resource where students cut out and piece together continents using Wegener's fossil evidence to reconstruct an ancient supercontinent, then evaluate how compelling the fit is. Includes a Wegener student handout and a present-day world map showing continental shelves.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/wegener_student.pdf">Download Student Handout (.pdf)</a>
      <a href="/assets/resources/wegener_world.pdf">Download World Map (.pdf)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/geological_scale_preview.png">
  <div>
    <div class="resource-title">Earth's History on a Rope</div>
    <div class="resource-desc">
      A MUNGO-made geological time scale activity where you make a scaled-down model of Earth's 4.6-billion-year history using a length of rope, place major events at their true relative distances apart, then compare that timeline to their own lifespan to grasp just how recent human history really is. The Google Drive folder includes a student worksheet, teacher version, 8 blank event labels, and a Google Sheet for converting milestone dates to rope length.
    </div>
    <div class="resource-links">
      <a href="https://drive.google.com/drive/folders/1zUiD3ygeIwNnyNoYK_7TnhTzG5b8ghQw?usp=drive_link" target="_blank">View Folder in Google Drive</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/earthquakeepicenter_preview.png">
  <div>
    <div class="resource-title">Finding an Earthquake Epicenter Activity</div>
    <div class="resource-desc">
A MUNGO-made activity exploring how earthquakes and seismic waves work, reading real seismograms, and using data from three seismic stations to triangulate an earthquake's epicenter on a map.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/EarthquakeEpicenter_student.docx">Download Student Version (.docx)</a>
      <a href="/assets/resources/EarthquakeEpicenter_teacher.docx">Download Teacher Version (.docx)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
<div class="resource-card">
  <img class="resource-thumb" src="/assets/img/minecraft_activity_preview.png">
  <div>
    <div class="resource-title">Minecraft Activities: Geology of NL and Geophysics</div>
    <div class="resource-desc">
Explore a custom Minecraft world made by MUNGO that models Newfoundland's real bedrock geology. Visit landmarks like fossil sites and structural features, then use in-game gravity and magnetic maps to hunt for ore deposits like a geophysicist. Includes exploration and mining activities (with Junior High and Senior High versions), plus download instructions.
    </div>
    <div class="resource-links">
      <a href="/assets/resources/minecraft_geology_activity.docx">Download "Exploring Newfoundland Geology in Minecraft" (.docx)</a>
      <a href="/assets/resources/minecraft_mining_activity.docx">Download "Mining like a Pro in Minecraft!" (.docx)</a>
      <a href="/assets/resources/minecraft_instructions.pdf">Download Minecraft World Download Instructions (.pdf)</a>
    </div>
  </div>
</div>

<hr class="section-divider">
