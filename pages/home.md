---
layout: base
permalink: /
class: home
---

<section class="hero">
  <div class="usa-grid">
    <h2>Find treatment facilities</h2>
    <h2 class="hero-heading">Search for treatment facilities for substance abuse, addiction, and mental health problems in the United States or U.S. Territories confidentially and anonymously.</h2>
  </div>
</section>
<section class="usa-section home-main">
  <div class="usa-grid">
    <div class="usa-width-seven-twelfths">
      <form class="form-search-home" action="{{ site.baseurl }}/search-results/">
        <fieldset class="fieldset-search">
<!--           <legend class="search-legend">Find treatment facilities</legend>
 -->          <div class="form-search-home-inner1">
            <div class="usa-input-grid">
              <label for="location">Location</label>
              <span class="usa-form-hint">Address, city, state, or zip code</span>
              <input id="location" name="location" type="text">
              <i class="fa fa-map-marker-alt" aria-hidden="true"></i>
              <a class="form-search-home-location" href="#">
                <i class="material-icons">my_location</i><span>Use my current location</span>
              </a>
            </div>
            <input type="submit" value="Search">
          </div>
        </fieldset>
      </form>
    </div>
    <div class="usa-width-five-twelfths trial-info">
      <h2>Find treatment facilities confidentially and anonymously</h2>
      <p>Your personal information and the search criteria you enter into the Locator is secure and anonymous. SAMHSA does not collect or maintain any information you provide.</p>
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
      <h2>Learn about substance abuse treatment</h2>
      <p>SAMHSA aims to answer questions and find the best ways to prevent, diagnose, or substance abuse, addiction, and mental health problems.</p>
      <ul>
        <li><a href="">Types of treatment</a></li>
        <li><a href="#">Who conducts treatment</a></li>
        <li><a href="#">How the government is involved</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
<!--       <div class="info-callouts-img">
        {% include svg/clipboard.svg %}
      </div> -->
      <h2>Know the risks and benefits</h2>
      <p>Information on SAMHSA is provided and updated by survey responses.</p>
      <ul>
        <li><a href="">Risks and benefits</a></li>
        <li><a href="">How veterans are protected</a></li>
        <li><a href="">How to choose a facility</a></li>
      </ul>
    </section>
    <section class="usa-width-one-third">
<!--       <div class="info-callouts-img">
        {% include svg/phone.svg %}
      </div> -->
      <h2>Call SAMHSA's National Helpline</h2>
      <p>1-800-662-HELP (4357)</p>
      <p>Free and confidential information in English and Spanish for individuals and family members facing substance abuse and mental health issues. 24 hours a day, 7 days a week.</p>
      <ul>
        <li><a href="">Questions to ask</a></li>
      </ul>
    </section>
  </div>
</section>
