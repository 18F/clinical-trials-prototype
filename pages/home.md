---
layout: base
permalink: /
---

<section class="usa-section hero">
  <div class="usa-grid">
    <h2>ClinicalTrials.gov is a tool for finding research studies and results from around the world.</h2>
    <h3>239,000+ studies in 50 states and 196 countries</h3>
  </div>
</section>
<section class="usa-section">
  <div class="usa-grid">
    <div class="usa-width-one-half trial-info">
      <h2>Search for a trial to participate in</h2>
      <p>These trials are not  endorsed or regulated by NIH or the federal government. Please talk to your doctor before volunteering for a study. <a href="#">Read our Disclaimer</a> for details.</p>
    </div>
    <div class="usa-width-one-half">
      <form class="form-search" action="{{ site.baseurl }}/search-results/">
        <label for="keyword">Search by keyword</label>
        <span class="usa-form-hint">For example: cancer, oxytoine, or radiation</span>
        <input id="keyword" name="keyword" type="text">
        <p class="form-help-text">Search by condition, drug, intervention, or NCT number</p>
        <label for="location">Location</label>
        <span class="usa-form-hint">For example: Anywhere, USA</span>
        <input id="location" name="location" type="text">
        <i class="fa fa-map-marker" aria-hidden="true"></i>
        <a href="#">+ Advanced search</a>
        <input type="submit" value="Submit">
      </form>
    </div>
  </div>
</section>
{% include advanced-search.html %}
<div class="usa-grid search-links">
  <a href="#"><i class="fa fa-map-o"></i>Search on the map</a>
  <a href="#"><i class="fa fa-book"></i>Browse by topic</a>
</div>
<div class="usa-grid info-callouts">
  <section class="usa-width-one-third card usa-color-bg-primary-alt-lightest">
    <h3>Find a study to participate in</h3>
    <p>Search for studies near you that are looking for participants.</p>
    <p><a href="#">Learn more</a></p>
  </section>
  <section class="usa-width-one-third card usa-color-bg-gray-dark">
    <h3>Browse our comprehensive database</h3>
    <p>Explore over 239,000 studies by topic, condition, NTC number, or location.</p>
    <p><a class="link-white" href="#">Learn more</a></p>
  </section>
  <section class="usa-width-one-third card usa-color-bg-primary">
    <h3>Submit or edit a study record</h3>
    <p>Add a study listing, update a study, or add study results.</p>
    <p><a class="link-white" href="#">Learn more</a></p>
  </section>
</div>