---
layout: page
title: Student Links
---

### Student Links

Websites, simulations, and interactive tools appropriate for students to explore on their own. Note the <strong>grade range</strong> when sharing.

<div style="margin: 1.5rem 0; padding: 1rem; background: #f7f7f7; border-radius: 8px;">
  <strong>Jump to:</strong>
  <a href="#elementary">Elementary (K-6)</a> ·
  <a href="#intermediate">Intermediate (7-9)</a> ·
  <a href="#high-school">High School (10-12)</a> ·
  <a href="#all-grades">All Grades</a> ·

</div>

<input type="text" id="page-search" placeholder="Search this page for keywords..." 
  style="width: 100%; max-width: 500px; padding: 10px 14px; font-size: 1rem; border: 1px solid #ccc; border-radius: 6px; margin: 1.5rem 0; display: block;">

<script>
document.getElementById('page-search').addEventListener('input', function() {
  var query = this.value.toLowerCase();
  var cards = document.querySelectorAll('.link-card');
  var groups = document.querySelectorAll('.grade-group');

  cards.forEach(function(card) {
    var text = card.textContent.toLowerCase();
    var match = text.includes(query);
    card.style.display = match ? '' : 'none';

    var divider = card.previousElementSibling;
    if (divider && divider.classList.contains('section-divider')) {
      divider.style.display = match ? '' : 'none';
    }
  });

  groups.forEach(function(group) {
    var visibleCard = group.querySelector('.link-card:not([style*="display: none"])');
    group.style.display = visibleCard ? '' : 'none';
  });
});
</script>

<style>
.section-divider {
  border: none;
  border-top: 2px solid #ccc;
  margin: 3rem 0 2rem 0;
}
.link-card {
  display: flex;
  gap: 20px;
  align-items: flex-start;
  margin: 2rem 0;
  padding: 1.5rem;
  border-radius: 8px;
  background: #f7f7f7;
}
.link-thumb {
  width: 120px;
  height: 150px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  flex-shrink: 0;
}
.link-title {
  font-weight: bold;
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}
.link-desc {
  margin-bottom: 0.75rem;
}
.link-grade {
  display: inline-block;
  background: #800000;
  color: #fff;
  font-weight: bold;
  font-size: 0.85rem;
  padding: 4px 12px;
  border-radius: 20px;
}
</style>

<div class="grade-group">
  <h3 id="elementary">Elementary (K-6)</h3>

  <hr class="section-divider">
  <div class="link-card">
    <img class="link-thumb" src="/assets/img/example-link-preview2.png">
    <div>
      <div class="link-title"><a href="https://example.com" target="_blank">Example Junior High Tool</a></div>
      <div class="link-desc">A short description of what the tool does and why it's useful across Grades 7–9.</div>
      <div class="link-grade">Grades 7–9</div>
    </div>
  </div>
</div>

<div class="grade-group">
  <h3 id="intermediate">Intermediate (7-9)</h3>

  <hr class="section-divider">
  <div class="link-card">
    <img class="link-thumb" src="/assets/img/example-link-preview3.png">
    <div>
      <div class="link-title"><a href="https://example.com" target="_blank">Example Grade 7 Tool</a></div>
      <div class="link-desc">A short description here.</div>
      <div class="link-grade">Grade 7</div>
    </div>
  </div>
</div>

<div class="grade-group">
  <h3 id="high-school">High School (10-12)</h3>

  <hr class="section-divider">
  <div class="link-card">
    <img class="link-thumb" src="/assets/img/example-link-preview4.png">
    <div>
      <div class="link-title"><a href="https://example.com" target="_blank">Example Grade 9 Tool</a></div>
      <div class="link-desc">A short description here.</div>
      <div class="link-grade">Grade 9</div>
    </div>
  </div>
</div>

<div class="grade-group">
  <h3 id="all-grades">All Grades</h3>

  <hr class="section-divider">
  <div class="link-card">
    <img class="link-thumb" src="/assets/img/phet_logo.png">
    <div>
      <div class="link-title"><a href="https://phet.colorado.edu/en/simulations/filter?type=html" target="_blank">PhET Simulations</a></div>
      <div class="link-desc">
        <p>PhET (or “Physics Education Technology”) Interactive Simulations let students explore physics and Earth science concepts in a visual way. The simulations are designed to be flexible so that they can be used as lecture demonstrations, labs, or homework activities.</p>
        <p>They use an intuitive, game-like environment where students can learn through scientist-like exploration within a simplified environment, where dynamic visual representations make the invisible visible, and where science ideas are connected to real-world phenomena.</p>
        <p>Geophysics examples include: Sound Waves, Normal Modes, Magnet and Compass, and Gravity Force Lab.</p></div>
      <div class="link-grade">All Grades</div>
    </div>
  </div>
</div>

<p style="margin-top: 2rem;">
  Know of a link that should be here? 
  <a href="mailto:mungo@mun.ca">Tell us!</a>
</p>
