---
title: "AURA Lab - Team"
layout: gridlay
excerpt: "AURA Lab: Team members"
sitemap: false
permalink: /team/

# Photos: upload to images/teampic/, then enter the filename below.
# Leave optional fields empty until the student's details are confirmed.
masters_students:
  - name: "Joshua Goetz"
    role: "Master's Student"
    email: "jlg5119@rit.edu"
    photo: ""
    program: "Industrial and Systems Engineering"
    profile_url: "https://www.linkedin.com/in/joshua-goetz"
    profile_label: "LinkedIn"

undergraduate_students:
  - name: "Amey Dhupkar"
    role: "Undergraduate Student"
    email: "aad7390@rit.edu"
    photo: "amey-dhupkar.png"
    program: "B.S. in Civil Engineering Technology"
    graduation: "Expected May 2028"
    bio: "Amey has engineering internship experience in water and wastewater infrastructure and hospital construction. His work has included project coordination, procurement, technical documentation, and construction progress tracking. His technical skills include Microsoft Project, STAAD.Pro, Civil 3D, AutoCAD, and Revit."
    college: "College of Engineering Technology"
    activity: "Construction Head, RIT ASCE Concrete Canoe"
    activity_url: "https://campusgroups.rit.edu/ritcc/leadership-team/"
    profile_url: "https://www.linkedin.com/in/amey-dhupkar-8988b3375/"
    profile_label: "LinkedIn"
  - name: "Cameron Phillip"
    role: "Undergraduate Student"
    email: "cgp1977@rit.edu"
    photo: "cameron-phillip.png"
    program: "B.S. in Civil Engineering Technology"
    graduation: "Expected May 2029"
    academic_details: "Minor: Mathematics; Concentration: Renewable Energy"
    bio: "Cameron is interested in sustainable energy, with experience in renewable energy market research and a solar energy farm proposal. His project experience includes building design using Revit and AutoCAD, concrete mix design, and technical proposal writing. He also serves as a teaching assistant in the CETEMS department."
    college: "College of Engineering Technology"
    activity: "Vice President, RIT Concrete Canoe Competition Team"
    activity_url: "https://campusgroups.rit.edu/ritcc/leadership-team/"
    profile_url: "https://www.linkedin.com/in/cameron123phillip/"
    profile_label: "LinkedIn"
---

<style>
  .aura-team { --team-border: #e4e7eb; --team-muted: #58636e; }
  .aura-team, .aura-team * { box-sizing: border-box; }
  .aura-team .team-section { margin: 0 0 36px; }
  .aura-team .team-section + .team-section {
    padding-top: 28px;
    border-top: 1px solid var(--team-border);
  }
  .aura-team .team-heading { margin: 0 0 24px; }
  .aura-team .team-pi {
    display: grid;
    grid-template-columns: minmax(180px, 260px) minmax(0, 1fr);
    gap: 28px;
    align-items: start;
  }
  .aura-team .team-pi-photo {
    display: block;
    width: 100%;
    height: 300px;
    object-fit: cover;
    object-position: center;
  }
  .aura-team .team-members {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 32px;
  }
  .aura-team .team-member {
    display: grid;
    grid-template-columns: 140px minmax(0, 1fr);
    gap: 18px;
    align-items: start;
  }
  .aura-team .team-photo,
  .aura-team .team-photo-placeholder {
    display: block;
    width: 140px;
    height: 140px;
    border: 1px solid var(--team-border);
  }
  .aura-team .team-photo { object-fit: cover; object-position: center; }
  .aura-team .team-photo-placeholder {
    display: flex;
    align-items: center;
    justify-content: center;
    background: #f3f5f7;
    color: var(--team-muted);
    font-size: 14px;
  }
  .aura-team .team-bio { grid-column: 1 / -1; margin: 0; line-height: 1.6; }
  .aura-team .team-name { margin: 0 0 8px; font-size: 21px; line-height: 1.3; }
  .aura-team .team-role { color: var(--team-muted); font-style: italic; }
  .aura-team .team-details { min-width: 0; }
  .aura-team .team-details p { margin: 0 0 10px; }
  .aura-team .team-details a { overflow-wrap: anywhere; }
  .aura-team .team-education { padding-left: 20px; margin: 16px 0; }
  .aura-team .team-links { margin-top: 14px; }
  .aura-team .team-recruitment {
    border-top: 1px solid var(--team-border);
    padding-top: 24px;
    margin-top: 12px;
  }
  @media (max-width: 991px) {
    .aura-team .team-members { grid-template-columns: minmax(0, 1fr); }
  }
  @media (max-width: 600px) {
    .aura-team .team-pi { grid-template-columns: minmax(0, 1fr); gap: 20px; }
    .aura-team .team-pi-photo { max-width: 260px; }
    .aura-team .team-member { grid-template-columns: 110px minmax(0, 1fr); gap: 14px; }
    .aura-team .team-photo,
    .aura-team .team-photo-placeholder { width: 110px; height: 110px; }
  }
</style>

<div class="aura-team" markdown="0">
  <h1>Team</h1>

  <section class="team-section" aria-labelledby="principal-investigator">
    <h2 id="principal-investigator" class="team-heading">Principal Investigator</h2>
    <div class="team-pi">
      <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/chen%202026.JPG"
           class="team-pi-photo" alt="Chen Xia" width="260" height="300">
      <div class="team-details">
        <h3 class="team-name">Chen Xia, Ph.D., LEED AP</h3>
        <p class="team-role">Assistant Professor</p>
        <p>Department of Civil Engineering Technology, Environmental Management and Safety<br>
           Rochester Institute of Technology</p>
        <ul class="team-education">
          <li>Ph.D., Architectural Engineering, Pennsylvania State University–University Park</li>
          <li>M.S., Construction Management, Tongji University</li>
          <li>B.S., Construction Cost Engineering, Chongqing University</li>
        </ul>
        <p><strong>Email:</strong> <a href="mailto:cxxite@rit.edu">cxxite@rit.edu</a><br>
           <strong>Address:</strong> 1 Lomb Memorial Dr, Rochester, NY 14623</p>
        <p class="team-links">
          <a href="https://scholar.google.com/citations?user=y1ZRz6AAAAAJ&amp;hl=en">Google Scholar</a> &middot;
          <a href="https://www.linkedin.com/in/chen-xia-leed-ap-9ab040199/?locale=en">LinkedIn</a> &middot;
          <a href="https://www.researchgate.net/profile/Chen-Xia-9?ev=hdr_xprf">ResearchGate</a>
        </p>
      </div>
    </div>
  </section>

  {% assign student_groups = "masters_students,undergraduate_students" | split: "," %}
  {% for group in student_groups %}
  <section class="team-section" aria-labelledby="{{ group }}">
    <h2 id="{{ group }}" class="team-heading">{% if group == "masters_students" %}Master's Students{% else %}Undergraduate Students{% endif %}</h2>
    <div class="team-members">
      {% for member in page[group] %}
      <article class="team-member">
        {% if member.photo != "" and member.photo != nil %}
        <img class="team-photo" src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo | uri_escape }}"
             alt="{{ member.name | escape }}" width="140" height="140" loading="lazy">
        {% else %}
        <div class="team-photo-placeholder" role="img" aria-label="Photo of {{ member.name | escape }} coming soon">Photo coming soon</div>
        {% endif %}
        <div class="team-details">
          <h3 class="team-name">{{ member.name | escape }}</h3>
          <p class="team-role">{{ member.role | escape }}</p>
          {% if member.program != "" and member.program != nil %}
          <p>{{ member.program | escape }}{% if member.graduation %}<br>{{ member.graduation | escape }}{% endif %}</p>
          {% if member.academic_details %}
          <p>{{ member.academic_details | escape }}</p>
          {% endif %}
          {% endif %}
          {% if member.college and member.college != "" %}
          <p>{{ member.college | escape }}</p>
          {% endif %}
          <p>Rochester Institute of Technology</p>
          <p><a href="mailto:{{ member.email | escape }}">{{ member.email | escape }}</a></p>
          {% if member.activity and member.activity != "" %}
          <p><a href="{{ member.activity_url | escape }}">{{ member.activity | escape }}</a></p>
          {% endif %}
          {% if member.profile_url != "" and member.profile_url != nil %}
          <p class="team-links"><a href="{{ member.profile_url | escape }}">{{ member.profile_label | default: "Learn more" | escape }}<span class="sr-only"> about {{ member.name | escape }}</span></a></p>
          {% endif %}
        </div>
        {% if member.bio %}
        <p class="team-bio">{{ member.bio | escape }}</p>
        {% endif %}
      </article>
      {% endfor %}
    </div>
  </section>
  {% endfor %}

  <p class="team-recruitment"><strong>We are looking for passionate new Ph.D. and master's students to join the team!</strong> <a href="mailto:cxxite@rit.edu">Contact me</a>.</p>
</div>
