---
# the default layout is 'page'
icon: fas fa-info-circle
order: 1
---

**Shengyao Lu** (陆晟瑶) is an Assistant Professor in the [Department of Computer Science](https://www.uvic.ca/ecs/computerscience/index.php) (CS) at the [University of Victoria](https://www.uvic.ca) (UVic). She received her BSc. and Ph.D. degree at the [University of Alberta](https://www.ualberta.ca/en/index.html). Her research interests primarily lie in the areas of Explainable AI (XAI), graph neural networks (GNNs) and graph representation learning, reinforcement learning (RL) for reasoning, large language models (LLMs) toward artificial general intelligence (AGI).

<span style="font-size: 1.8rem; font-weight: 550;">Openings</span>  
I have multiple openings for MSc/PhD starting in Fall 2026. Background in LLM deployment/fine-tuning, visual-language alignment, graph-language alignment would be a strong asset. Please send me your CV if interested.

<style>
.news-section {
  max-width: 700px;
  margin-top: 2rem;
}

.news-section h2 {
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

.news-list {
  margin: 0;
  padding: 0;
}

.news-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 0.8rem;
}

.news-date {
  font-size: 0.9rem;
  font-weight: 700;
  background: #f3f5f7;
  padding: 0.2rem 0.6rem;
  border-radius: 999px;
  color: #555;
  margin-right: 0.8rem;
  white-space: nowrap;
  text-align: right;
}

.news-text {
  font-size: 1rem;
  font-weight: 500;
}

.news-pagination {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.8rem;
  margin-top: -0.3rem !important;
  margin-bottom: 0.5rem !important;
}

.news-page-btn {
  border: none;
  background: none;
  padding: 0;
  cursor: pointer;
  color: #777;
  transition: color 0.2s ease;
}

.news-page-btn:hover {
  color: #000;
}

.news-page-btn:disabled {
  opacity: 0.25;
  cursor: default;
}

.news-page-btn i {
  font-size: 0.9rem;
}

.news-page-info {
  font-size: 0.85rem;
  color: #666;
}
</style>

<div class="news-section">
  <h2>News</h2>

  <div class="news-list">
    <div class="news-item">
      <span class="news-date">11/2025</span>
      <span class="news-text">
        I attended my PhD convocation ceremony at the University of Alberta. ☺️
      </span>
    </div>
    <div class="news-item">
      <span class="news-date">11/2025</span>
      <span class="news-text">
        I was invited to give a public talk hosted by Spoon CoLearning.
      </span>
    </div>
    <div class="news-item">
      <span class="news-date">10/2025</span>
      <span class="news-text">
        My PhD thesis received the George Walker Award for Best Doctoral Thesis. 🥇
      </span>
    </div>
    <div class="news-item">
      <span class="news-date">09/2025</span>
      <span class="news-text">
        I started my appointment at UVic as a TTAP. 🔥
      </span>
    </div>
    <div class="news-item">
      <span class="news-date">06/2025</span>
      <span class="news-text">
        I have successfully defended my Ph.D. thesis. 
      </span>
    </div>
  </div>
  <!-- pagination controls -->
  <div class="news-pagination mt-3">
    <button id="news-prev" class="news-page-btn">
      <i class="fas fa-chevron-left"></i>
    </button>
    <span id="news-page-info" class="news-page-info"></span>
    <button id="news-next" class="news-page-btn">
      <i class="fas fa-chevron-right"></i>
    </button>
  </div>
</div>

{% raw %}
<script>
document.addEventListener('DOMContentLoaded', function () {
  const section = document.querySelector('.news-section');
  if (!section) return;

  const items = Array.from(section.querySelectorAll('.news-item'));
  const pageSize = 6; 
  let currentPage = 1;
  const totalPages = Math.max(1, Math.ceil(items.length / pageSize));

  const prevBtn = document.getElementById('news-prev');
  const nextBtn = document.getElementById('news-next');
  const pageInfo = document.getElementById('news-page-info');

  function renderPage() {
    const start = (currentPage - 1) * pageSize;
    const end = start + pageSize;

    items.forEach(function (item, idx) {
      if (idx >= start && idx < end) {
        item.style.display = '';
      } else {
        item.style.display = 'none';
      }
    });

    if (pageInfo) {
      pageInfo.textContent = 'Page ' + currentPage + ' / ' + totalPages;
    }
    if (prevBtn) prevBtn.disabled = (currentPage === 1);
    if (nextBtn) nextBtn.disabled = (currentPage === totalPages);
  }

  if (prevBtn) {
    prevBtn.addEventListener('click', function () {
      if (currentPage > 1) {
        currentPage -= 1;
        renderPage();
      }
    });
  }

  if (nextBtn) {
    nextBtn.addEventListener('click', function () {
      if (currentPage < totalPages) {
        currentPage += 1;
        renderPage();
      }
    });
  }

  renderPage();
});
</script>
{% endraw %}

<div class="row g-3 my-3">
  <div class="col-md-6">
    <figure class="text-center">
      <img src="/commons/pics/UAconvocation.JPG" class="img-fluid rounded" alt="convocation">
      <figcaption class="mt-2 text-muted" style="font-size: 0.9rem;">
        11/19/2025 @ UA. 
      </figcaption>
    </figure>
  </div>
  <div class="col-md-6">
    <!-- <img src="/assets/img/fig2.png" class="img-fluid rounded" alt="Figure 2"> -->
  </div>
</div>
