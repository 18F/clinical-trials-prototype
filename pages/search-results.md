---
layout: base
permalink: /search-results/
class: search-results
---

<nav class="submenu">
  <div class="usa-grid">
    <ul class="breadcrumbs usa-unstyled-list">
      <li>
        <a href="{{ site.baseurl }}/">Home</a>
      </li>
      <li>Search results</li>
    </ul>
    <div class="page-links">
      <button class="js-glossary-toggle button usa-button-unstyled term link-compound"><i class="fa fa-info-circle" aria-hidden="true"></i>Glossary</button>
      <span class="divider-vertical"></span>
      <a class="link-compound" href="#">
        <i class="fa fa-bookmark-o" aria-hidden="true"></i>Saved studies <span class="saved_studies-count">2</span>
      </a>
      <span class="divider-vertical"></span>
      <a class="page-links-icon_link" href="#">
        <i class="fa fa-print" aria-hidden="true"></i>
        <span class="usa-sr-only">Print</span>
      </a>
      <a class="page-links-icon_link" href="#">
        <i class="fa fa-envelope-o" aria-hidden="true"></i>
        <span class="usa-sr-only">Email</span>
      </a>
      <a class="page-links-icon_link" href="#0">
        <i class="fa fa-download" aria-hidden="true"></i>
        <span class="usa-sr-only">Download search results</span>
      </a>
      <a class="page-links-icon_link" href="#0">
        <i class="fa fa-rss" aria-hidden="true"></i>
        <span class="usa-sr-only">Subscribe to updates on this search (RSS)</span>
      </a>
    </div>
  </div>
</nav>
<div class="search_result-search">
  <div class="usa-grid">
    <form class="" action="">
      <div class="search_result-search-input">
        <label class="" for="search_field-condition">Condition or disease</label>
        <span class="usa-form-hint">(e.g. breast cancer)</span>
        <input id="search_field-condition" name="input-type-text" type="text" value="PTSD">
      </div>
      <div class="search_result-search-input">
        <label class="" for="search_field-keyword">Other terms</label>
        <span class="usa-form-hint">(e.g. NCT number)</span>
        <input id="search_field-keyword" name="input-type-text" type="text" value="">
      </div>
      <div class="search_result-search-input">
        <label class="" for="search_field-location">Location</label>
        <span class="usa-form-hint">(e.g. Austin, TX)</span>
        <input id="search_field-location" name="input-type-text" type="text" value="Palo Alto, CA">
      </div>
      <div class="search_result-search-input search_result-search-input-distance">
        <label for="distance">Distance</label>
        <select id="distance" name="distance">
          <option></option>
          <option value="50">50 miles</option>
          <option value="100">100 miles</option>
          <option value="250">250 miles</option>
          <option value="500" selected>500 miles</option>
          <option value="any">Any distance</option>
        </select>
      </div>
      <button class="">
        <span class="usa-sr-only">Modify search</span>
        <i class="fa fa-search" aria-hidden="true"></i>
      </button>
    </form>
    <a class="search_result-link-advanced_search" href="#0">Advanced search</a>
  </div>
</div>
<nav class="search_result-info_bar">
  <div class="usa-grid">
    <p class="search_result-count">
      <span class="search_result-count-showing">Showing 1-16 out of 230 results for:</span><br><b>PTSD</b> (includes synonymous conditions like <b>shell-shock</b>, <b>post traumatic stress disorder</b>, and <a href="#0">5 related terms</a>) in <b>Palo Alto, CA</b>.
    </p>
    <div class="filter-remove">
      <a href="#0">Seeking participants <i class="fa fa-times-circle" aria-hidden="true"></i></a>
    </div>
    <form class="form-sort" action="">
      <label for="options">Sort by:</label>
      <select name="options" id="options">
        <option value="most-relevant">Most relevant</option>
        <option value="newest">Newest</option>
      </select>
    </form>
  </div>
</nav>
<div class="usa-grid">
  <aside class="search_result-filter usa-width-one-fourth">
    {% include search-results-filter.html %}
  </aside>
  <div class="usa-width-three-fourths search_results-main">
<!--     <div class="search_results-info">
      <form class="form-sort" action="">
        <label for="options">Sort by:</label>
        <select name="options" id="options">
          <option value="most-relevant">Most relevant</option>
          <option value="newest">Newest</option>
        </select>
      </form>
    </div> -->
    <div class="usa-grid-full search_results-heading">
      <div class="usa-width-two-thirds">
        <p class="search_results-heading-study">Study details</p>
      </div>
      <div class="usa-width-one-third">
        <p class="term" data-term="Intervention">
          Intervention type
          <i class="fa fa-info-circle" aria-hidden="true"></i>
        </p>
      </div>
    </div>
    <ol class="search_result-list usa-unstyled-list">
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting">
              <i class="fa fa-circle" aria-hidden="true"></i>
              Recruiting
            </p>
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Use of Mobile Apps for Those With <b>PTSD</b> and Their Partners</a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA and 46 other locations</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b></p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Non-personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Control training</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <span class="usa-label tooltip-label" aria-describedby="tooltip-text-content-1" tabindex="0">New</span>
          <div class="tooltip">
            <span class="tooltip-text" id="tooltip-text-content-1" role="tooltip">Study posted within the last 30 days</span>
          </div>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting"><i class="fa fa-circle" aria-hidden="true"></i> Enrolling by invitation</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Yoga Online Feasibility to Reduce <b>PTSD</b></a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b></p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Non-personalized Attention Control Training (ACT)</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-suspended-"><i class="fa fa-circle" aria-hidden="true"></i> Suspended</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Safety and Efficacy Study of TNX-102 SL in Patients With Military-related <b>PTSD</b></a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA and 46 other locations</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Depression</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting"><i class="fa fa-circle" aria-hidden="true"></i> Recruiting</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Efficacy of 60-minute Versus 90-minute Sessions in Treating <b>PTSD</b> Using Prolonged Exposure</a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b></p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Drug: Ketamine</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-suspended-"><i class="fa fa-circle" aria-hidden="true"></i> Terminated</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Intensive Weekend Retreat Multi-Couple Group Therapy for <b>PTSD</b></a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Substance Abuse</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Drug: Ketamine, doxazosin</li>
              <li>Drug: Doxazosin</li>
              <li>Drug: Perindopril</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <span class="usa-label tooltip-label" aria-describedby="tooltip-text-content-2" tabindex="0">New</span>
          <div class="tooltip">
            <span class="tooltip-text" id="tooltip-text-content-2" role="tooltip">Study posted within the last 30 days</span>
          </div>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting"><i class="fa fa-circle" aria-hidden="true"></i> Recruiting</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Attention Control Treatment for Post Traumatic Stress Disorder (<b>PTSD</b>)</a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA and 2 other locations</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Depression</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Non-personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Control training</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-suspended-"><i class="fa fa-circle" aria-hidden="true"></i> Suspended</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Safety and Efficacy Study of TNX-102 SL in Patients With Military-related <b>PTSD</b></a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA and 46 other locations</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Depression</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting"><i class="fa fa-circle" aria-hidden="true"></i> Recruiting</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Efficacy of 60-minute Versus 90-minute Sessions in Treating <b>PTSD</b> Using Prolonged Exposure</a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b></p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Drug: Ketamine</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-suspended-"><i class="fa fa-circle" aria-hidden="true"></i> Terminated</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Intensive Weekend Retreat Multi-Couple Group Therapy for <b>PTSD</b></a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Substance Abuse</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Drug: Ketamine, doxazosin</li>
              <li>Drug: Doxazosin</li>
              <li>Drug: Perindopril</li>
            </ul>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <span class="usa-label tooltip-label" aria-describedby="tooltip-text-content-3" tabindex="0">New</span>
          <div class="tooltip">
            <span class="tooltip-text" id="tooltip-text-content-3" role="tooltip">Study posted within the last 30 days</span>
          </div>
          <div class="usa-width-two-thirds">
            <p class="search_result-metadata study-status study-status-recruiting"><i class="fa fa-circle" aria-hidden="true"></i> Recruiting</p>
            <h3 class="search_result-heading">
              <a href="javascript:void(0);">Attention Control Treatment for Post Traumatic Stress Disorder (<b>PTSD</b>)</a>
            </h3>
            <p class="search_result-metadata">Location: Palo Alto, CA and 2 other locations</p>
            <span class="search_result-metadata-divider">|</span>
            <p class="search_result-metadata">Condition: <b>PTSD</b>, Depression</p>
          </div>
          <div class="usa-width-one-third">
            <h3 class="search_result-intervention-heading">Intervention type</h3>
            <ul class="search_result-intervention">
              <li>Behavioral: Personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Non-personalized Attention Control Training (ACT)</li>
              <li>Behavioral: Control training</li>
            </ul>
          </div>
        </article>
      </li>
    </ol>
<nav class="pagination" role="navigation" aria-label="Pagination">
  <ol>
    <li class="pagination-page"><a class="is-active" href="#0" aria-label="Page 1, Current Page" tabindex="-1">1</a></li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 2">2</a></li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 3">3</a></li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 4">4</a></li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 5">5</a></li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 6">6</a></li>
    <li class="c-page" aria-hidden="true">…</li>
    <li class="c-page"><a class="" href="#0" aria-label="Page 71">71</a></li>
    <li class="c-page-next"><a href="#0" aria-label="Next Page">Next <i class="fa fa-angle-right" aria-hidden="true"></i></a></li>
  </ol>
</nav>
  </div>
</div>
