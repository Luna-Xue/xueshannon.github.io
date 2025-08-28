---
layout: page
title: People
---

<style>
:root{
  --ink:#2c3e50;
  --muted:#6b7b8c;
  --border:#e6e9ee;
  --card:#ffffff;
  --bg:#fafbfc;
  --brand:#1f6feb;
  --accent:#ff7b72;
}

.people-container{
  max-width: 1100px;
  margin: 0 auto;
  padding: 24px 20px 60px;
}

.section-header{
  margin: 36px 0 18px;
  border-bottom: 2px solid var(--border);
}
.section-header h2{
  margin: 0 0 8px 0;
  font-size: 2.2rem;
  font-weight: 800;
  color: var(--ink);
}
.section-sub{
  margin-top: 4px;
  font-size: 0.98rem;
  color: var(--muted);
}

/* 两列排布 */
.people-grid{
  display: grid;
  grid-template-columns: repeat(2, minmax(0,1fr));
  gap: 18px;
  margin-top: 16px;
}
@media (max-width: 768px){ 
  .people-grid{ grid-template-columns: 1fr;} 
}

.person-card{
  display: flex;
  gap: 14px;
  padding: 14px;
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.04);
  transition: transform .15s ease, box-shadow .15s ease;
}
.person-card:hover{
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.06);
}

.person-photo{
  width: 64px; height: 64px; flex: 0 0 64px;
  border-radius: 10px; overflow: hidden;
  background: #f1f4f8; display:grid;place-items:center;
  border: 1px solid var(--border);
  font-size: 28px;
}
.person-photo img{ width:100%; height:100%; object-fit: cover; display:block;}
.person-body{ min-width: 0; }

.person-name{
  font-weight: 700; color: var(--ink);
  line-height: 1.2; margin-bottom: 4px;
}
.person-name a{ color: var(--ink); text-decoration: none; }
.person-name a:hover{ color: var(--brand); }

.person-role{ font-size: .98rem; color: var(--ink); }
.person-affil{ font-size: .9rem; color: var(--muted); margin-top: 2px; }

hr{ border:0; border-top:1px solid var(--border); margin: 28px 0; }
</style>


<div class="people-container">

  <!-- ============ Ph.D. Students ============ -->
  <div class="section-header">
    <h2>Ph.D. Students</h2>
    <div class="section-sub">Current doctoral researchers in the group</div>
  </div>

  <div class="people-grid">
    <!-- Saurabh Raman Parkar -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/Avatar/sparkar.jpg" alt="Saurabh Raman Parkar"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🎓';">
      </div>
      <div class="person-body">
        <div class="person-name">
          <a href="https://srparkar.github.io/" target="_blank" rel="noopener">Saurabh Raman Parkar</a>
        </div>
        <div class="person-role">Incoming Ph.D. Student — AI-Integrated Sensing</div>
      </div>
    </div>
  </div>

  <hr>

  <!-- ============ Collaborators ============ -->
  <div class="section-header">
    <h2>Collaborators</h2>
    <div class="section-sub">Faculty & research partners</div>
  </div>

  <div class="people-grid">
    <!-- Prof. Shucheng Yu -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Shucheng Yu"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name">
          <a href="https://www.yu.edu/katz/faculty#:~:text=Liyang%20Yan%27s%20Bio-,Shucheng%20Yu,-AI" target="_blank" rel="noopener">Prof. Shucheng Yu</a>
        </div>
        <div class="person-role">Associate Professor</div>
        <div class="person-affil">Yeshiva University</div>
      </div>
    </div>

    <!-- Prof. Min Song -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Min Song"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://www.stevens.edu/profile/msong6" target="_blank" rel="noopener">Prof. Min Song</a></div>
        <div class="person-role">Professor</div>
        <div class="person-affil">Stevens Institute of Technology</div>
      </div>
    </div>

    <!-- Prof. Laxima Niure Kandel -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Laxima Niure Kandel"
             onerror="this.style.display='none'; this.parentElement.textContent='👩‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://faculty.erau.edu/Laxima.NiureKandel" target="_blank" rel="noopener">Prof. Laxima Niure Kandel</a></div>
        <div class="person-role">Assistant Professor</div>
        <div class="person-affil">Embry-Riddle Aeronautical University</div>
      </div>
    </div>

    <!-- Prof. Yulong Zou -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Yulong Zou"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://scholar.google.com/citations?user=v9zFuDEAAAAJ&hl=en" target="_blank" rel="noopener">Prof. Yulong Zou</a></div>
        <div class="person-role">Professor</div>
        <div class="person-affil">Nanjing University of Posts and Telecommunications</div>
      </div>
    </div>

    <!-- Prof. Hongbin Li -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Hongbin Li"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://www.stevens.edu/profile/hli" target="_blank" rel="noopener">Prof. Hongbin Li</a></div>
        <div class="person-role">Professor</div>
        <div class="person-affil">Stevens Institute of Technology</div>
      </div>
    </div>

    <!-- Prof. K.P. (Suba) Subbalakshmi -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. K.P. (Suba) Subbalakshmi"
             onerror="this.style.display='none'; this.parentElement.textContent='👩‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://www.stevens.edu/profile/ksubbala" target="_blank" rel="noopener">Prof. K.P. (Suba) Subbalakshmi</a></div>
        <div class="person-role">Professor</div>
        <div class="person-affil">Stevens Institute of Technology</div>
      </div>
    </div>

    <!-- Prof. Ying Wang -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Ying Wang"
             onerror="this.style.display='none'; this.parentElement.textContent='👩‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://www.stevens.edu/profile/ywang6" target="_blank" rel="noopener">Prof. Ying Wang</a></div>
        <div class="person-role">Associate Professor</div>
        <div class="person-affil">Stevens Institute of Technology</div>
      </div>
    </div>

    <!-- Prof. Yao Zheng -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Yao Zheng"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a href="https://www2.hawaii.edu/~yaozheng/" target="_blank" rel="noopener">Prof. Yao Zheng</a></div>
        <div class="person-role">Associate Professor</div>
        <div class="person-affil">University of Hawaiʻi at Mānoa</div>
      </div>
    </div>

    <!-- Prof. Moh Khalid Hasan -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Prof. Moh Khalid Hasan"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🏫';">
      </div>
      <div class="person-body">
        <div class="person-name"><a https://www.jmu.edu/cise/people/faculty/hasan-moh-khalid.shtml" target="_blank" rel="noopener">Prof. Moh Khalid Hasan</a></div>
        <div class="person-role">Assistant Professor</div>
        <div class="person-affil">James Madison University</div>
      </div>
    </div>
  </div>

  <hr>

  <!-- ============ Mentorships ============ -->
  <div class="section-header">
    <h2>Mentorships</h2>
    <div class="section-sub">Current group & individual mentees</div>
  </div>

  <!-- Group projects -->
  <div class="people-grid">
    <!-- AFRL SDR Challenge -->
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="AFRL SDR Challenge"
             onerror="this.style.display='none'; this.parentElement.textContent='🏆';">
      </div>
      <div class="person-body">
        <div class="person-name">
          <a href="https://wbi-innovates.zohobackstage.com/afrlsdr" target="_blank" rel="noopener">
            AFRL Software Defined Radio (SDR) Challenge 2024–2025
          </a>
        </div>
        <div class="person-role">Group Project</div>
        <div class="person-affil">Master, Undergraduate, and High School</div>
      </div>
    </div>
  </div>

  <!-- Individual mentees -->
  <div class="people-grid" style="margin-top:10px;">
    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Ruoxi Li"
             onerror="this.style.display='none'; this.parentElement.textContent='👩‍🎓';">
      </div>
      <div class="person-body">
        <div class="person-name">Ruoxi Li</div>
        <div class="person-role">M.S. — AI-Integrated Sensing</div>
      </div>
    </div>

    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Beula Jose"
             onerror="this.style.display='none'; this.parentElement.textContent='👩‍🎓';">
      </div>
      <div class="person-body">
        <div class="person-name">Beula Jose</div>
        <div class="person-role">M.S. — Wireless Security</div>
      </div>
    </div>

    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Zhifan Jiang"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🎓';">
      </div>
      <div class="person-body">
        <div class="person-name">Zhifan Jiang</div>
        <div class="person-role">M.S. — SDR</div>
      </div>
    </div>

    <div class="person-card">
      <div class="person-photo">
        <img src="img/avatar-placeholder.jpg" alt="Jiapeng Xiao"
             onerror="this.style.display='none'; this.parentElement.textContent='👨‍🎓';">
      </div>
      <div class="person-body">
        <div class="person-name">Jiapeng Xiao</div>
        <div class="person-role">M.S. — SDR</div>
      </div>
    </div>
  </div>

</div>
