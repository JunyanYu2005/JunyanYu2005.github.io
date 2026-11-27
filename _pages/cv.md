---
layout: academic
title: "Background"
permalink: /cv/
author_profile: true
redirect_from:
  - /background/
  - /resume
  - /cv-json/
  - /resume-json
---

<section aria-labelledby="education">
  <h2 id="education">Education</h2>

  <p class="period">September 2023–present</p>
  <h3>The Chinese University of Hong Kong</h3>
  <p>B.A. in Chinese Language and Literature, with a minor in Linguistics (expected graduation: 2027).</p>
  <dl class="academic-facts">
    <dt>Cumulative GPA</dt><dd>3.731 / 4.000</dd>
    <dt>Major GPA</dt><dd>3.758 / 4.000</dd>
    <dt>Linguistics Coursework (A / A-)</dt>
    <dd>
      <ul>
        <li><strong>LING1000</strong> Invitation to Linguistics (A)</li>
        <li><strong>LING2006</strong> Semantics (A)</li>
        <li><strong>LING3101</strong> Morphology (A)</li>
        <li><strong>CHLL1110</strong> Introduction to Chinese Linguistics (A)</li>
        <li><strong>CHLL2121</strong> Introduction to Chinese Philology (A-)</li>
        <li><strong>CHLL2131</strong> Introduction to Chinese Phonology (A-)</li>
        <li><strong>CHLL3143</strong> Chinese Morphology (A)</li>
        <li><strong>CHLL3144</strong> The Study of Chinese Semantics (A)</li>
        <li><strong>CHLL3162</strong> Study of Cantonese (A)</li>
      </ul>
    </dd>
  </dl>

  <p class="period">September 2017–June 2023</p>
  <h3>Shaoxing No. 1 High School</h3>
  <p>Zhejiang, China</p>
  <dl class="academic-facts">
    <dt>Gaokao Score</dt><dd>673 / 750 (National College Entrance Examination; top 1% in Zhejiang Province)</dd>
  </dl>
</section>

<section aria-labelledby="languages">
  <h2 id="languages">Languages</h2>
  <dl class="academic-facts">
    <dt>Mandarin</dt><dd>Native; Putonghua Proficiency Test, Grade 1-B (95.7/100).</dd>
    <dt>English</dt><dd>IELTS overall 7.5 (Listening, Reading, Speaking 7.5; Writing 7.0).</dd>
    <dt>Cantonese</dt><dd>Professional proficiency (Cantonese Read-aloud Test, Grade B).</dd>
    <dt>Wu and Jin</dt><dd>Native bilingual proficiency (Shaoxing Wu and Yulin Jin).</dd>
    <dt>Hokkien and Hakka</dt><dd>Research proficiency.</dd>
  </dl>
</section>

<script>
  // Preserve links to sections of the former single-page CV.
  const formerCvSections = new Map([
    ['#research-interests', "{{ '/research/' | relative_url }}#interests"],
    ['#conference-presentations', "{{ '/research/' | relative_url }}#presentations"],
    ['#research-and-academic-experience', "{{ '/research/' | relative_url }}#service"],
    ['#selected-honours-and-awards', "{{ '/awards/' | relative_url }}#selected-awards"],
    ['#languages-and-research-skills', '#languages']
  ]);
  const currentSection = formerCvSections.get(window.location.hash);
  if (currentSection) window.location.replace(currentSection);
</script>
