---
title: "ISS Events"
subtitle: "Workshops and events in conjunction with CIST 2026"
---

<div class="tab-bar" role="tablist" aria-label="ISS Events">
  <button class="tab-btn active" role="tab" aria-selected="true" aria-controls="consortium" data-tab="consortium">Doctoral Consortium</button>
  <button class="tab-btn" role="tab" aria-selected="false" aria-controls="workshop" data-tab="workshop">ISR Paper Development Workshop</button>
</div>

<div class="tab-panel active" id="consortium" role="tabpanel">

<nav class="tab-toc" aria-label="On this page">
<strong>On this page</strong>
<ul>
<li><a href="#dc-overview">Overview</a></li>
<li><a href="#dc-requirements">Application Requirements</a></li>
<li><a href="#dc-chairs">Doctoral Consortium Co-Chairs</a></li>
</ul>
</nav>

## Third INFORMS Information Systems Society Doctoral Consortium {#dc-overview}

**Date:** Friday afternoon, October 30, 2026 (immediately preceding CIST)

**Location:** San Francisco, CA

The INFORMS Information Systems Society (ISS) invites doctoral students researching Information Systems and related fields to participate in its Third Doctoral Consortium. This half-day event will be held on Friday afternoon, October 30, 2026, immediately preceding the Conference on Information Systems and Technology (CIST) in San Francisco, CA.

Participants will have the opportunity to:

- Engage with a diverse panel of senior faculty mentors on research topics, teaching strategies, and job-market preparation.
- Receive in-depth feedback on dissertation research and progress.
- Build professional connections and expand networks within the IS research community and beyond.

We welcome applications from all PhD students, although preference will be given to students in the dissertation phase of their PhD program (typically in their 4th or 5th year in the PhD program). Selection criteria include research novelty, diversity of research topics, and capacity.

### Application Requirements {#dc-requirements}

Each applicant must submit one application that comprises the following four items, combined into one PDF file:

- Cover letter
- Applicant CV
- 5-page abstract of dissertation research
- Nomination letter from advisor (no more than one nominee per advisor)

To apply, please complete the [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSd8jLbjvx-zgtNr7FAfSVMYM4uWM5qi5k7g_eNcEHxYCev4Xg/viewform?usp=dialog) by **Tuesday, June 30, 2026 (11:59 p.m. Pacific Time)**.

Applicants will be notified of decisions by **Tuesday, August 18, 2026**. There is no registration fee for this event.

Please contact Ling Xue at [ling.xue@uga.edu](mailto:ling.xue@uga.edu) with any questions.

### Doctoral Consortium Co-Chairs {#dc-chairs}

- Martin Bichler, Technical University of Munich
- Ting Li, Erasmus University Rotterdam
- D.J. Wu, Georgia Institute of Technology
- Ling Xue, University of Georgia

</div>

<div class="tab-panel" id="workshop" role="tabpanel">

<nav class="tab-toc" aria-label="On this page">
<strong>On this page</strong>
<ul>
<li><a href="#ws-overview">Overview</a></li>
<li><a href="#ws-submit">How to Submit</a></li>
<li><a href="#ws-mentors">Mentors</a></li>
</ul>
</nav>

## Third INFORMS ISS Information Systems Research Paper Development Workshop for Early Career Scholars {#ws-overview}

**Date:** Friday afternoon, October 30, 2026 (in conjunction with CIST 2026)

**Location:** San Francisco, CA

Greetings, IS community, particularly early-career scholars!

This year, we are once again planning "INFORMS ISS–ISR Paper Development Workshop for Early Career Scholars." The workshop will be held in the afternoon of Friday, October 30, 2026, in San Francisco, in conjunction with CIST 2026.

Chad Ho from George Washington University will co-organize the workshop with me.

As you may know, we have held similar workshops at ECIS and PACIS, as well as at CIST in the last two years, and I believe they were both fun and quite effective.

Submissions can be on any topic of interest to Information Systems scholars, and may use any research methodology (qualitative, quantitative, design, multi-method, etc.).

The selected papers will be mentored by at least two members of the ISR Editorial Board. Please note that the workshop is not associated with any publication. The goal is to provide authors with meaningful feedback that can help enhance the paper's quality as it is prepared for submission to a suitable journal. Authors do not have an obligation to submit their paper to ISR simply because it has been accepted and discussed at this workshop. Also, please note that participation in the workshop does not imply favorable consideration or outcome at ISR.

The length of the papers submitted to the workshop should not exceed 24 pages (double-spaced, 12 font) – this includes everything, including references. The first page (not counted in the 24 pages) must have the title of the paper, the name(s), affiliation(s), and email address(es) of all the author(s), and 3-5 keywords.

### How to Submit {#ws-submit}

Please send your paper as an attachment (word or pdf format) as per the following instructions:

- **To:** [eic-isr@virginia.edu](mailto:eic-isr@virginia.edu)
- **Cc:** [rgc2xs@virginia.edu](mailto:rgc2xs@virginia.edu)
- **Subject:** "Submission to INFORMS-ISS ISR Paper Development Workshop 2026"

Please include the title of the manuscript and the name of the author seeking to attend the workshop (with email address) in the body of the email.

Submissions should be sent by email from **August 31 through September 7, 2026**. Papers submitted before August 31 and after September 7 (midnight Pacific Time) will not be considered. We will try to notify authors of the decisions by **September 25**.

### Mentors {#ws-mentors}

We now have commitments from the following members of the ISR Editorial Board, with additional mentors expected to join as the program is finalized. What a group of mentors!

**Senior Editors:**

- Bardhan, Indranil
- Cheng, Hsing (Kenny)
- Goh, Khim Yong
- Jiang, Zhengrui
- Mehra, Amit
- Sia, Choon Ling

**Associate Editors:**

- Adjerid, Idris
- Chan, Jason
- Chatterjee, Sutirtha
- He, Shu
- Ho, Chad
- Khern-am-nuai, Warut
- Kwon, Eric
- Li, Jingjing
- Pang, Min-Seok
- Ramaprasad, Jui
- Sanyal, Pallab
- Yang, Yi

While this workshop is primarily intended for early-career scholars, we may make a few exceptions based on special circumstances. Please clearly mention your special circumstances in your cover note. We look forward to receiving your submissions.

Suprateek Sarker<br>
Editor-in-Chief, ISR

</div>

<script>
(function () {
  var btns = document.querySelectorAll('.tab-btn');
  var panels = document.querySelectorAll('.tab-panel');
  function activate(id) {
    btns.forEach(function (b) {
      var on = b.dataset.tab === id;
      b.classList.toggle('active', on);
      b.setAttribute('aria-selected', on ? 'true' : 'false');
    });
    panels.forEach(function (p) {
      p.classList.toggle('active', p.id === id);
    });
  }
  btns.forEach(function (b) {
    b.addEventListener('click', function () {
      activate(b.dataset.tab);
      history.replaceState(null, '', '#' + b.dataset.tab);
    });
  });
  function fromHash() {
    var hash = decodeURIComponent(location.hash.slice(1));
    if (!hash) return;
    var el = document.getElementById(hash);
    if (!el) return;
    var panel = el.closest('.tab-panel');
    if (panel) {
      activate(panel.id);
      if (el !== panel) el.scrollIntoView();
    }
  }
  window.addEventListener('hashchange', fromHash);
  fromHash();
})();
</script>
