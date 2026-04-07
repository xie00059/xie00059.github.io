+++
title = "About Me"

description = ""

# Whether to sort pages by "date", "weight", or "none". More on that below
sort_by = "none"

# Used by the parent section to order its subsections.
# Lower values have priority.
weight = 0

# Template to use to render this section page
# template = "section.html"

# Apply the given template to ALL pages below the section, recursively.
# If you have several nested sections each with a page_template set, the page
# will always use the closest to itself.
# However, a page own `template` variable will always have priority.
# Not set by default
# page_template =

# How many pages to be displayed per paginated page.
# No pagination will happen if this isn't set or if the value is 0
# paginate_by = 0

# If set, will be the path used by paginated page and the page number will be appended after it.
# For example the default would be page/1
# paginate_path = "page"

# Whether to insert a link for each header like the ones you can see in this site if you hover one
# The default template can be overridden by creating a `anchor-link.html` in the `templates` directory
# Options are "left", "right" and "none"
# insert_anchor_links = "none"

# Whether the section pages should be in the search index. This is only used if
# `build_search_index` is set to true in the config
# in_search_index = true

# Whether to render that section homepage or not.
# Useful when the section is only there to organize things but is not meant
# to be used directly
render = true

# Whether to redirect when landing on that section. Defaults to not being set.
# Useful for the same reason as `render` but when you don't want a 404 when
# landing on the root section page.
# Example: redirect_to = "documentation/content/overview"
redirect_to = ""

# Whether the section should pass its pages on to the parent section. Defaults to `false`.
# Useful when the section shouldn't split up the parent section, like
# sections for each year under a posts section.
transparent = false

# Your own data
[extra]
+++

<span class="tag is-success is-rounded" style="margin-bottom: 1.5rem;">
  <span style="display:inline-block;width:8px;height:8px;background:#48c774;border-radius:50%;margin-right:6px;"></span>
  On the academic job market
</span>

<!-- <p style="font-size:0.85rem;font-weight:700;letter-spacing:0.12em;text-transform:uppercase;margin-bottom:0.4rem;">
  Postdoctoral Researcher · The University of Queensland
</p> -->

<hr>

<p>I am a Postdoctoral Researcher at the TECH4HSE project, jointly affiliated with the University of Queensland and CSIRO's Data61, and I am currently on the academic job market.</p>

<p>Before that, I received my Ph.D. from UQ under the supervision of 
<a href="https://baigd.github.io/">Prof. Guangdong Bai</a>, where my 
research focused on privacy and security in software systems.</p>

<p>My research interests include Software Privacy and Testing, specifically focusing on Virtual Personal Assistant (VPA) services. I'm also broadly interested in applying black-box testing and natural language processing techniques to assess and enhance the privacy compliance of software systems.</p>

<div style="margin-top:1.5rem;">
  <span class="tag is-rounded" style="background:#f8b4b4;color:#333;margin:0.2rem;">Software Privacy</span>
  <span class="tag is-rounded" style="background:#fde68a;color:#333;margin:0.2rem;">Privacy Testing</span>
  <span class="tag is-rounded" style="background:#bfdbfe;color:#333;margin:0.2rem;">Privacy Compliance</span>
</div>

<hr style="margin-top:2rem;">

<section>
  <h2>Selected Publications</h2>

  <p>1. <b>[Privacy Compliance &amp; Analysis]</b> My core research investigates whether software systems (e.g.,  Virtual Personal Assistant apps) honour the privacy promises they make to users, and how privacy practices evolve across platforms over time.</p>
  <ul>
      <li>
      Scrutinizing Privacy Policy Compliance of Virtual Personal Assistant Apps [ASE'22] &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/skipper-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1145/3551349.3560416">DOI</a>
    </li>
    <li>
      Are Your Requests Your True Needs? Checking Excessive Data Collection in VPA Apps [ICSE'24]
      &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/pico-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1145/3597503.363910">DOI</a>
    </li>
    <li>
      On the Quality of Privacy Policy Documents of Virtual Personal Assistant Applications [PETS'24]
      &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/popets-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.56553/popets-2024-0028">DOI</a>
    </li>
    <li>
      Investigating Documented Privacy Changes in Android OS [FSE'24]<br>
      &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/android-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1145/3660826">DOI</a>
    </li>
  </ul>

  <p>2. <b>[Software Testing]</b> Testing and quality assurance underpin much of my privacy research. I also collaborate on broader software testing projects, applying similar analytical approaches to different software ecosystems.</p>
  <ul>
    <li>
      Identifying Multi-Parameter Constraint Errors in Python Data Science Library API Documentations [ISSTA'25]
      &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/pythondoc-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1145/3728945">DOI</a>
    </li>
    <li>
      VUI Testing of VPA Apps via Behavior Model-Enhanced LLM Agents [TOSEM’25] &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/vuitesting-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1145/3771555">DOI</a>
    </li>
    <li>
      When Voice Meets Touch: Conflict Analysis in Mobile Applications [TSE’26]
      &nbsp;·&nbsp; <a href="https://xie00059.github.io/publications/Voice_Meets_Touch-paper.pdf">PDF</a> &nbsp;·&nbsp; <a href="https://doi.org/10.1109/TSE.2026.3656691">DOI</a>
    </li>
  </ul>
</section>

<hr style="margin-top:2rem;">

<section>
  <h2>Education</h2>
  <ul>
    <li>
      <strong>Doctor of Philosophy in Computer Science</strong>, 2022 – 2026<br>
      The University of Queensland, Australia<br>
      · Supervisors: Guangdong Bai (primary), <a href="https://guoweiyang.github.io/">Guowei Yang</a>, and <a href="https://staff.itee.uq.edu.au/huang/">Zi (Helen) Huang</a><br>
      · Visiting PhD student of <a href="https://liyiweb.com/">Prof. Yi Li</a>, Nanyang Technological University, 2023
    </li>
    <li>
      <strong>Master of Engineering in Software</strong>, 2021<br>
      The University of Queensland, Australia<br>
      · Receive the Dean’s Commendation for Academic Excellence
    </li>
    <li>
      <strong>Bachelor of Software Engineering (Honours)</strong>, 2016 – 2020<br>
      The University of Queensland, Australia
    </li>
  </ul>
</section>

<hr style="margin-top:2rem;">

<section>
  <h2>Experience</h2>
  <ul>
    <li>
      <strong>Postdoctoral Researcher</strong>, 2025 – Present<br>
      UQ & CSIRO, Australia<br>
      · Advisors: <a href="https://scholar.google.com/citations?user=0vCxuH4AAAAJ&hl=en">Zhenchang Xing</a>, <a href="https://people.csiro.au/B/M/mohan-baruwalchhetri">Mohan Baruwal Chhetri</a>, and <a href="https://about.uq.edu.au/experts/25114">Naipeng Dong</a>
    </li>
    <li>
      <strong>Research Assistant</strong>, 2025<br>
      UQ & CSIRO, Australia
    </li>
    <li>
      <strong>Thesis Mentor</strong>, 2023 – Present<br>
      The University of Queensland, Australia
    </li>
  </ul>
</section>

<hr style="margin-top:2rem;">

<section>
  <h2>Selected Awards &amp; Grants</h2>
  <ul>
    <li>
      <strong>UQ-TUM Travel Grant Scheme</strong>, 2025, UQ Global Partnerships
    </li>
    <li>
      <strong>ACM SIGSOFT CAPS Scholarship</strong>, ICSE'24
    </li>
    <li>
      <strong>ACM Student Mentor Workshop Scholarship</strong>, ICSE'23
    </li>
    <li>
      <strong>ACM SIGSOFT CAPS Scholarship</strong>, ASE'22
    </li>
    <li>
      <strong>Best Paper Runner-Up</strong>, ADMA'21
    </li>
    <li>
      <strong>Dean's Commendation for Academic Excellence</strong>, 2021, UQ
    </li>
  </ul>
</section>

<hr style="margin-top:2rem;">

<section>
  <h2>Talks &amp; Visits</h2>
  <ul>
    <li>
      <strong>Guest Lecture</strong>, 2026, University of Queensland<br>
      · <em>"AI for Text Analysis"</em>
    </li>
    <li>
      <strong>Conference Presentation</strong>, PoPETs'24<br>
      · <em>"On the Quality of Privacy Policy Documents of Virtual Personal Assistant Applications"</em>
    </li>
    <li>
      <strong>Conference Presentation</strong>, ICSE'24<br>
      · <em>"Are Your Requests Your True Needs? Checking Excessive Data Collection in VPA Apps"</em>
    </li>
    <li>
      <strong>Conference Presentation</strong>, ASE'22<br>
      · <em>"Scrutinizing Privacy Policy Compliance of Virtual Personal Assistant Apps"</em>
    </li>
    <li>
      <strong>Research Visit</strong>, Nanyang Technological University, 2023<br>
      · Worked at NTU's SRSLab under the supervision of <a href="https://liyiweb.com/">Prof. Yi Li</a>
    </li>
  </ul>
</section>

<hr style="margin-top:2rem;">

<section>
  <h2>Academic Services</h2>
  <p><strong>Organizing Committee</strong></p>
  <ul>
    <li>Publicity Co-chair, ICECCS'26</li>
    <li>Area Chair, TheWebConf 2026 Workshop TIME (TIME'26)</li>
    <li>Volunteer, IWQoS'25, ICSE'23, ICFEM'23, ADMA'22</li>
  </ul>
  <p><strong>Program Committee &amp; Reviewers</strong></p>
  <ul>
    <li>TDSC'25 (Journal Reviewer)</li>
    <li>NDSS'26, NDSS'25, NDSS'24, ICSE'24 (Artifact Evaluation Track)</li>
    <li>MSR'25 (Technical PC Track)</li>
    <li>ICSE'25 (Shadow PC Track), MSR'23 (Junior PC Track)</li>
    <li>Sub-reviewer: ASE'24, NDSS'24, ICSE'24, ICSE'25, ISSTA'25, ICSE'26</li>
  </ul>
</section>
