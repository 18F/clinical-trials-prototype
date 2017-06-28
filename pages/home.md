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
<!--       <form class="form-search" action="{{ site.baseurl }}/search-results/">
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
      </form> -->
      <form class="form-search-new" action="{{ site.baseurl }}/search-results/">
        <fieldset class="fieldset-search">
          <legend class="search-legend usa-sr-only">Search for studies which are:</legend>
          <fieldset class="usa-fieldset-inputs">
            <legend class="legend-study-status"><span class="usa-sr-only">Study Status</span>Search for studies which are:</legend>
            <ul class="usa-unstyled-list">
              <li>
                <input id="study-recruiting" type="radio" checked name="study-status" value="recruiting">
                <label class="label-radio" for="study-recruiting">Currently recruiting participants</label>
              </li>
              <li>
                <input id="study-all" type="radio" name="study-status" value="all-studies">
                <label class="label-radio" for="study-all">All studies</label>
              </li>
            </ul>
          </fieldset>
          <label for="input-type-text">Condition / Disease</label>
          <span class="usa-form-hint">For example: cancer, oxytoine, or radiation</span>
          <input id="input-type-text" name="input-type-text" type="text">
          <label for="input-type-text">Keywords</label>
          <span class="usa-form-hint">For example: NCT number, drug name, investigator name</span>
          <input id="input-type-text" name="input-type-text" type="text">
          <div class="usa-input-grid usa-input-grid-medium">
            <label for="city">Location</label>
            <input id="location" name="location" type="text">
            <i class="fa fa-map-marker" aria-hidden="true"></i>
          </div>
          <div class="usa-input-grid usa-input-grid-small">
            <label for="state">Distance</label>
            <select id="state" name="state">
              <option value="50">50 miles</option>
              <option value="100">100 miles</option>
              <option value="200" selected="selected">200 miles</option>
            </select>
          </div>
          <input type="submit" value="Search">
        </fieldset>
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
