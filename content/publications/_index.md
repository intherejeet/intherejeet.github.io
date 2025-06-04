---
title: "Publications"
date: 2024-01-01
menu:
  main:
    weight: 20
---

My research publications address fundamental challenges in AI Security, Computer Vision, Natural Language Processing, and Trustworthy AI. The work spans theoretical foundations to practical implementations, with particular emphasis on machine learning security, adversarial robustness, and safety mechanisms for large language and multimodal models. Publications are listed in reverse chronological order with venue-specific categorization.

{{< rawhtml >}}
<div class="publications-filter">
  <button class="filter-btn active" data-filter="all">All</button>
  <button class="filter-btn" data-filter="conference">Conference</button>
  <button class="filter-btn" data-filter="workshop">Workshop</button>
  <button class="filter-btn" data-filter="preprint">Preprint</button>
</div>

<style>
.publications-filter {
  margin: 20px 0;
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
}

.filter-btn {
  padding: 8px 16px;
  border: 1px solid var(--border);
  background: var(--code-bg);
  color: var(--primary);
  cursor: pointer;
  border-radius: 4px;
  transition: all 0.3s ease;
}

.filter-btn:hover,
.filter-btn.active {
  background: var(--primary);
  color: var(--theme);
}

.publication-item {
  margin-bottom: 30px;
  padding-bottom: 20px;
  border-bottom: 1px solid var(--border);
}

.publication-item:last-child {
  border-bottom: none;
}

.publication-title {
  font-size: 1.1em;
  font-weight: 600;
  margin-bottom: 8px;
}

.publication-authors {
  color: var(--secondary);
  margin-bottom: 5px;
}

.publication-venue {
  font-style: italic;
  margin-bottom: 10px;
}

.publication-links {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

.publication-links a {
  font-size: 0.9em;
  color: var(--primary);
  text-decoration: none;
  padding: 4px 8px;
  border: 1px solid var(--border);
  border-radius: 3px;
  transition: all 0.3s ease;
}

.publication-links a:hover {
  background: var(--primary);
  color: var(--theme);
}

.publication-year {
  font-size: 1.3em;
  font-weight: bold;
  margin: 30px 0 20px 0;
  color: var(--primary);
  border-bottom: 2px solid var(--primary);
  padding-bottom: 5px;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const filterBtns = document.querySelectorAll('.filter-btn');
  const publications = document.querySelectorAll('.publication-item');
  
  filterBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      filterBtns.forEach(b => b.classList.remove('active'));
      this.classList.add('active');
      
      const filter = this.dataset.filter;
      
      publications.forEach(pub => {
        if (filter === 'all' || pub.dataset.type === filter) {
          pub.style.display = 'block';
        } else {
          pub.style.display = 'none';
        }
      });
    });
  });
});
</script>
{{< /rawhtml >}} 