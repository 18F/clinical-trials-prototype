---
layout: base
permalink: /
---

<section class="usa-section hero">
  <div class="usa-grid">
    <h2>ClinicalTrials.gov is the largest online database of clinical studies conducted around the world.</h2>
  </div>
</section>
<section class="usa-section">
  <div class="usa-grid">
    <div class="usa-width-one-half trial-info">
      <h2>Find a study</h2>
      <p>ClinicalTrials.gov is a resource maintained by the U.S. National Library of Medicine. Listing a study does not mean it has been reviewed by the U.S. federal government. Know <a href="https://clinicaltrials.gov/ct2/about-studies/learn#Considerations">the risks of clinical studies</a> and talk to a medical professional before volunteering for a study.</p>
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
          <legend class="search-legend">Search through 240,000+ studies in the U.S. and 201 other countries</legend>
          <fieldset class="usa-fieldset-inputs">
            <legend class="legend-study-status"><span class="usa-sr-only">Study Status</span>Search for studies that are:</legend>
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
          <label for="condition">Condition or disease</label>
          <span class="usa-form-hint">For example: cancer, oxytoine, or radiation</span>
          <input id="condition" name="condition" type="text">
          <label for="keywords">Keywords</label>
          <span class="usa-form-hint">For example: NCT number, drug name, investigator name</span>
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
        </fieldset>
      </form>
    </div>
  </div>
</section>
<!-- {% include advanced-search.html %} -->
<section class="info-callouts">
  <div class="usa-grid">
    <h2>What is ClinicalTrials.gov?</h2>
    <section class="usa-width-one-third">
      <h3>Learn about clinical studies</h3>
      <p>Clinical studies aim to answer scientific questions and find the best ways to prevent, diagnose, or treat diseases and medical conditions. These studies involve research using human volunteers, or participants.</p>
      <ul>
        <li><a href="">Types of clinical studies</a></li>
        <li><a href="#">Phases of clinical studies</a></li>
        <li><a href="#">Who conducts clinical studies</a></li>
        <li><a href="#">How the government is involved</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
      <h3>What you need to know</h3>
      <p>Information on ClinicalTrials.gov is provided and updated by the sponsor or principal investigator of the clinical study. ClinicalTrials.gov is not involved in the studies themselves. </p>
      <ul>
        <li><a href="">Risks and benefits of clinical studies</a></li>
        <li><a href="">How participants are protected </a></li>
        <li><a href="">How to read the study record</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
      <h3>Talk to your doctor</h3>
      <p>Participating in a clinical study is an important personal decision. We encourage you to learn everything you can about studies you’re considering and discuss your options with a medical professional.</p>
      <ul>
        <li><a href="">Questions to ask</a></li>
      </ul>
    </section>
  </div>
</section>
<footer class="usa-footer usa-footer-big" role="contentinfo">
  <div class="usa-grid usa-footer-return-to-top">
    <a href="#">Return to top</a>
  </div>
  <div class="usa-footer-primary-section">
    <div class="usa-grid-full">
      <nav class="usa-footer-nav">
        <h4>Additional links</h4>
        <ul class="usa-unstyled-list usa-width-one-fourth">
          <li><a href="javascript:void(0);">About ClinicalTrials.gov</a></li>
          <li><a href="javascript:void(0);">About the National Library of Medicine</a></li>
          <li><a href="javascript:void(0);">Careers</a></li>
          <li><a href="javascript:void(0);">Contact</a></li>
          <li><a href="javascript:void(0);">Press</a></li>
        </ul>
        <ul class="usa-unstyled-list usa-width-one-fourth">
          <li><a href="javascript:void(0);">National Institute of Health</a></li>
          <li><a href="javascript:void(0);">National Library of Medicine</a></li>
          <li><a href="javascript:void(0);">Department of Health and Human Services</a></li>
        </ul>
        <ul class="usa-unstyled-list usa-width-one-fourth">
          <li><a href="javascript:void(0);">Copyright</a></li>
          <li><a href="javascript:void(0);">Privacy</a></li>
          <li><a href="javascript:void(0);">Accessibility</a></li>
          <li><a href="javascript:void(0);">USA.gov</a></li>
          <li><a href="javascript:void(0);">Freedom of Information Act</a></li>
          <li><a href="javascript:void(0);">Department of Health and Human Services</a></li>
        </ul>
      </nav>
    </div>
  </div>
</footer>
