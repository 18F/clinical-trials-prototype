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
      <button class="js-glossary-toggle button usa-button-unstyled link-compound"><i class="fa fa-info-circle" aria-hidden="true"></i>Glossary</button>
      <span class="divider-vertical"></span>
      <a class="link-compound" href="#">
        <i class="fa fa-bookmark-o" aria-hidden="true"></i>Saved facilities <span class="saved_studies-count">2</span>
      </a>
      <span class="divider-vertical"></span>
      <a class="page-links-icon_link" href="#">
        <i class="fa fa-print" aria-hidden="true"></i>
        <span class="usa-sr-only">Print</span>
      </a>
      <a class="page-links-icon_link" href="#">
        <i class="fa fa-envelope" aria-hidden="true"></i>
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
<!--       <div class="search_result-search-input">
        <label class="" for="search_field-condition">Condition or disease</label>
        <span class="usa-form-hint">(e.g. breast cancer)</span>
        <input id="search_field-condition" name="input-type-text" type="text" value="PTSD">
      </div>
      <div class="search_result-search-input">
        <label class="" for="search_field-keyword">Other terms</label>
        <span class="usa-form-hint">(e.g. NCT number)</span>
        <input id="search_field-keyword" name="input-type-text" type="text" value="">
      </div> -->
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
        <i class="fa fa-search" aria-hidden="true"></i>
        <span class="search_result-button-modify">Modify search</span>
      </button>
    </form>
    <a class="search_result-link-advanced_search" href="#0">Advanced search</a>
  </div>
</div>
<nav class="search_result-info_bar">
  <div class="usa-grid">
    <p class="search_result-count">
      <span class="search_result-count-showing">Showing 1-10 out of 230 results for:</span> <b>Palo Alto</b>.
    </p>
<!--     <div class="filter-remove">
      <a href="#0">Seeking participants <i class="fa fa-times-circle" aria-hidden="true"></i></a>
    </div> -->
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
<!--     <div class="usa-grid-full search_results-heading">
      <div class="usa-width-two-thirds">
        <p class="search_results-heading-study">Facilities</p>
      </div>
      <div class="usa-width-one-third">
        <p class="term" data-term="Intervention">
          Intervention type
          <i class="fa fa-info-circle" aria-hidden="true"></i>
        </p>
      </div>
    </div> -->
    <ol class="search_result-list usa-unstyled-list">
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Western Pacific Med Corp Western Pacific Reseda</a>
            </h3>
            <p class="search_result-metadata">
              <span>7232 Canby Avenue</span>
              <span>Reseda, CA 91335</span>
              <span>Tel: 818-705-5561</span>
              <span><a href="#">Website</a></span>
              <span><a href="#">Directions</a></span>
            </p>
          </div>
          <div class="usa-width-one-third">
            <h4 class="search_result-intervention-heading">Intervention type</h4>
            <p class="search_result-metadata">
              <span>1.5 miles</span>
              <span><a href="#">More info</a></span>
            </p>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Western Pacific Med Corp Western Pacific Reseda</a>
            </h3>
            <p class="search_result-metadata">
              <span>7232 Canby Avenue</span>
              <span>Reseda, CA 91335</span>
              <span>Tel: 818-705-5561</span>
              <span><a href="#">Website</a></span>
              <span><a href="#">Directions</a></span>
            </p>
          </div>
          <div class="usa-width-one-third">
            <h4 class="search_result-intervention-heading">Intervention type</h4>
            <p class="search_result-metadata">
              <span>1.5 miles</span>
              <span><a href="#">More info</a></span>
            </p>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Western Pacific Med Corp Western Pacific Reseda</a>
            </h3>
            <p class="search_result-metadata">
              <span>7232 Canby Avenue</span>
              <span>Reseda, CA 91335</span>
              <span>Tel: 818-705-5561</span>
              <span><a href="#">Website</a></span>
              <span><a href="#">Directions</a></span>
            </p>
          </div>
          <div class="usa-width-one-third">
            <h4 class="search_result-intervention-heading">Intervention type</h4>
            <p class="search_result-metadata">
              <span>1.5 miles</span>
              <span><a href="#">More info</a></span>
            </p>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Western Pacific Med Corp Western Pacific Reseda</a>
            </h3>
            <p class="search_result-metadata">
              <span>7232 Canby Avenue</span>
              <span>Reseda, CA 91335</span>
              <span>Tel: 818-705-5561</span>
              <span><a href="#">Website</a></span>
              <span><a href="#">Directions</a></span>
            </p>
          </div>
          <div class="usa-width-one-third">
            <h4 class="search_result-intervention-heading">Intervention type</h4>
            <p class="search_result-metadata">
              <span>1.5 miles</span>
              <span><a href="#">More info</a></span>
            </p>
          </div>
        </article>
      </li>
      <li class="search_result-item">
        <article>
          <div class="usa-width-two-thirds">
            <h3 class="search_result-heading">
              <a href="{{ site.baseurl }}/study-detail/">Western Pacific Med Corp Western Pacific Reseda</a>
            </h3>
            <p class="search_result-metadata">
              <span>7232 Canby Avenue</span>
              <span>Reseda, CA 91335</span>
              <span>Tel: 818-705-5561</span>
              <span><a href="#">Website</a></span>
              <span><a href="#">Directions</a></span>
            </p>
          </div>
          <div class="usa-width-one-third">
            <h4 class="search_result-intervention-heading">Intervention type</h4>
            <p class="search_result-metadata">
              <span>1.5 miles</span>
              <span><a href="#">More info</a></span>
            </p>
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
