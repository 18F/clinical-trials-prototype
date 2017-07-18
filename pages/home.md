---
layout: base
permalink: /
class: home
---

<section class="hero">
  <div class="usa-grid">
    <h2 class="hero-heading">ClinicalTrials.gov is the largest online database of privately and publicly funded clinical studies conducted around the world.</h2>
  </div>
</section>
<section class="usa-section">
  <div class="usa-grid">
    <div class="usa-width-five-twelfths trial-info">
      <h2>Explore more than 240,000 research studies in 201 countries</h2>
      <p>ClinicalTrials.gov is a resource provided by the U.S. National Library of Medicine. Listing a study does not mean it has been evaluated by the U.S. federal government. <a href="https://clinicaltrials.gov/ct2/about-studies/learn#Considerations">Know the risks of clinical studies</a> and talk to a healthcare professional before participating.</p>
    </div>
    <div class="usa-width-seven-twelfths">
      <form class="form-search-home" action="{{ site.baseurl }}/search-results/">
        <fieldset class="fieldset-search">
          <legend class="search-legend">Find a study <span class="usa-form-hint">(all fields are optional)</span></legend>
          <fieldset class="usa-fieldset-inputs usa-fieldset-tabs">
            <legend class="usa-sr-only">Study Status</legend>
            <ul class="usa-unstyled-list">
              <li>
                <input id="study-recruiting" type="radio" checked name="study-status" value="recruiting">
                <label class="label-radio" for="study-recruiting">Seeking participants</label>
              </li>
              <li>
                <input id="study-with-results" type="radio" name="study-status" value="all-studies">
                <label class="label-radio" for="study-with-results">With results</label>
              </li>
              <li>
                <input id="study-all" type="radio" name="study-status" value="all-studies">
                <label class="label-radio" for="study-all">Show all studies</label>
              </li>
            </ul>
          </fieldset>
          <div class="form-search-home-inner">
            <label for="condition">Condition or disease</label>
            <span class="usa-form-hint">For example: cancer, oxytoine, or radiation</span>
            <input id="condition" name="condition" type="text">
            <label for="keywords">Additional search terms</label>
            <span class="usa-form-hint">For example: NCT number, drug name, or investigator name</span>
            <input id="keywords" name="keywords" type="text">
            <div class="usa-input-grid usa-input-grid-medium">
              <label for="location">Location</label>
              <input id="location" name="location" type="text">
              <i class="fa fa-map-marker" aria-hidden="true"></i>
            </div>
            <div class="usa-input-grid usa-input-grid-small">
              <label for="distance">Distance</label>
              <select id="distance" name="distance">
                <option></option>
                <option value="50">50 miles</option>
                <option value="100">100 miles</option>
                <option value="250">250 miles</option>
                <option value="500">500 miles</option>
                <option value="any">Any distance</option>
              </select>
            </div>
            <input type="submit" value="Search">
            <a href="#">Advanced Search</a>
          </div>
        </fieldset>
      </form>
      <div class="search-links">
        <a href="#"><i class="fa fa-globe"></i>Search on the map</a>
        <a href="#"><i class="fa fa-book"></i>Browse by topic</a>
      </div>
    </div>
  </div>
</section>
<!-- {% include advanced-search.html %} -->
<section class="info-callouts usa-section">
  <div class="usa-grid">
    <section class="usa-width-one-third">
<!--       <div class="info-callouts-img">
        {% include svg/search.svg %}
      </div> -->
      <h2>Learn about clinical studies</h2>
      <p>Clinical studies aim to answer scientific questions and find the best ways to prevent, diagnose, or treat diseases and medical conditions. These studies involve research using human volunteers, or participants.</p>
      <ul>
        <li><a href="">Types and phases of clinical studies</a></li>
        <li><a href="#">Who conducts clinical studies</a></li>
        <li><a href="#">How the government is involved</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
<!--       <div class="info-callouts-img">
        {% include svg/clipboard.svg %}
      </div> -->
      <h2>Know the risks and benefits</h2>
      <p>Information on ClinicalTrials.gov is provided and updated by the sponsor or principal investigator of the clinical study. ClinicalTrials.gov is not involved in the studies themselves.</p>
      <ul>
        <li><a href="">Risks and benefits of clinical studies</a></li>
        <li><a href="">How participants are protected</a></li>
        <li><a href="">How to read the study record</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
<!--       <div class="info-callouts-img">
        {% include svg/phone.svg %}
      </div> -->
      <h2>Talk to a healthcare professional</h2>
      <p>Participating in a clinical study is an important personal decision. We urge  you to learn everything you can about studies you’re considering and discuss all options with a healthcare professional.</p>
      <ul>
        <li><a href="">Questions to ask</a></li>
      </ul>
    </section>
  </div>
</section>
