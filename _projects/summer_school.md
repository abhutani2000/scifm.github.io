---
title: Summer School
layout: tabs
card-title: SciFM Summer School
card-content: SciFM Summer School 2024 organized by the University of Michigan (UM) and Argonne National Laboratory (ANL).
card-image: assets/img/scifm_transparent_logo.png
---

<div class="tab-content" id="pills-tabContent">
    <div class="tab-pane fade show active" id="about" role="tabpanel" aria-labelledby="pills-about-tab"> 
        {% include blurb.html item=site.data.descriptions.summer_school %}
    </div>
    <div class="tab-pane fade" id="organizers" role="tabpanel" aria-labelledby="pills-organizers-tab">
        <section>
        {% include role-organizer.html image=true%}
        </section>
    </div>
    <div class="tab-pane fade" id="schedule" role="tabpanel" aria-labelledby="pills-schedule-tab">
        {% include schedule.html %}
    </div>
</div>