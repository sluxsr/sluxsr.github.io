---
# the default layout is 'page'
icon: fas fa-chalkboard-teacher
order: 2
---
<style>
.teaching-timeline {
  max-width: 760px;
  margin: 2rem auto;
}

.teaching-item {
  display: grid;
  grid-template-columns: 120px 32px auto;
  column-gap: 1rem;
  align-items: flex-start;
  position: relative;
  padding-bottom: 1.25rem;
}

.teaching-term {
  font-weight: 800;
  background: #f3f5f7;
  padding: 0.25rem 0.8rem;
  border-radius: 999px;
  color: #444;
  text-align: right;
}

.teaching-marker::before {
  content: "";
  position: absolute;
  top: 0.7rem;     
  bottom: -3rem;  
  width: 2px;
  background: #e0e0e0;
}

.teaching-marker {
  position: relative;
  display: flex;
  justify-content: center;
}

.teaching-dot {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  border: 3px solid #fff;
  box-shadow: 0 0 0 2px #bbb;
  background: #fff;
  margin-top: 0.1rem;
}

.teaching-course {
  font-size: 0.96rem;
}

.teaching-course strong {
  font-weight: 700;
}
</style>

<div class="teaching-timeline">

  <div class="teaching-item">
    <div class="teaching-term">Fall 2026</div>
    <div class="teaching-marker">
      <span class="teaching-dot"></span>
    </div>
    <div class="teaching-course">
      <strong>CSC 321 – Introduction to Artificial Intelligence</strong>
      <span style="font-weight:400; margin-left:6px;">(Course number changed.)</span>
    </div>
  </div>

  <div class="teaching-item">
    <div class="teaching-term">Winter 2026</div>
    <div class="teaching-marker">
      <span class="teaching-dot"></span>
    </div>
    <div class="teaching-course">
      <strong>CSC 421 – Introduction to Artificial Intelligence</strong>
    </div>
  </div>

</div>
