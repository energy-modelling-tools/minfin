---
theme: jekyll-theme-primer
layout: sub-page
title: MINFin
permalink: /learning_capacity/
---

<section class="bg-gray-light py-5 fade-in-center">
  <div class="container-lg p-responsive">

    <div class="text-center fade-in-center">
      <h2 class="alt-h2 mb-4">Learning & Capacity Building</h2>
    </div>

    <!-- E-Learning Material -->
    <div class="mt-4 animate-in">
      <h3 class="alt-h3 mt-3" style="font-size: 1.25rem;">🎓 OpenLearn Course: <strong>Financial Modelling for Energy Transitions – MINFin, FinTrack and FinCoRE</strong></h3>
      <p class="animate-in" style="font-size: 0.95rem; text-align: justify;">
        The <strong>Financial Modelling for Energy Transitions</strong> course provides participants with the foundational skills to evaluate the financial viability 
        of energy transition investments on the national level, particularly in low- and middle-income countries. 
        The course introduces <strong>MINFin (Model for Informed National Financing)</strong>, an Excel-based cashflow model designed to identify and assess climate finance gaps 
        at the national level. Participants will also work with two complementary data visualisation tools:
      </p>
      <ul class="animate-in text-gray" style="font-size: 0.95rem;">
        <li><strong>FinTrack (Climate Finance Tracker):</strong> Maps funding sources, highlights underutilised financing resources, and details financing access criteria.</li>
        <li><strong>FinCoRE (Financing Costs for Renewables Estimator):</strong> Offers historical and forward-looking projections of cost of capital.</li>
      </ul>
      <p class="animate-in" style="font-size: 0.95rem; text-align: justify;">
        By the end of the course, participants will be equipped to apply these tools and principles to effectively address the financial needs of climate transitions. 
      </p>
      <p class="animate-in">
        <a href="https://www.open.edu/openlearncreate/course/view.php?id=14218" target="_blank" class="btn btn-outline-primary sky-blue-accent" style="border-color: #3490dc; color: #3490dc;">
          Access the Course →
        </a>
      </p>
    </div>

    <!-- User Interface / Download Link -->
    <div class="mt-5 animate-in">
      <h3 class="alt-h3 mt-3" style="font-size: 1.25rem;">💻 User Interface: <strong>MINFin-Excel</strong></h3>
      <p class="animate-in" style="font-size: 0.95rem; text-align: justify;">
        <strong>MINFin</strong> features an intuitive Excel-based interface designed for accessibility across ministries, including non-specialist users. 
        By removing the need for advanced modelling software or programming skills, MINFin enables energy and finance ministries to collaborate directly 
        in assessing the financial viability of national energy transition plans. 
        The tool includes structured templates, guided workflows, and integrated analysis dashboards, making advanced financial modelling 
        a shared and transparent function within government. 
        When paired with the OpenLearn course, MINFin offers a robust, easy-to-use foundation for credible financial planning.
      </p>
      <p class="animate-in">
        <a href="https://github.com/MINFinModel/MINFin-Excel/tree/main?tab=readme-ov-file" target="_blank" class="btn btn-outline-primary sky-blue-accent" style="border-color: #3490dc; color: #3490dc;">
          Download MINFin-Excel →
        </a>
      </p>
    </div>

   <!-- EMP Events -->
    <div class="mt-5 animate-in">
      <h3 class="alt-h3 mt-3" style="font-size: 1.25rem;">🌍 EMP Events</h3>
      <p class="animate-in" style="font-size: 0.95rem; text-align: justify;">
        MINFin is not currently featured at any Energy Modelling Platform (EMP) events, but its introduction is planned for <strong>2026</strong>. 
        For the latest updates, subscribe to the <a href="https://climatecompatiblegrowth.com/newsletter/" target="_blank" class="text-blue text-decoration-none">CCG Newsletter</a>.
      </p>
    </div>

    <!-- Other Teaching Events -->
    <div class="mt-5 animate-in">
      <h3 class="alt-h3 mt-3" style="font-size: 1.25rem;">📚 Other Teaching Events</h3>

      <div class="application-card mt-3 p-4 border border-gray-200 rounded">
        <h4 class="mb-2">Zambia Introduction to Financial Modelling Workshop</h4>
        <p class="text-gray" style="font-size: 0.95rem; text-align: justify;">
          In <strong>March 2025</strong>, CCG delivered in-country training to <strong>28 participants</strong> from a diverse mix of public and private energy and financial institutions in Zambia. 
          The training formed part of a six-month project to develop a <strong>Financing Strategy for Zambia’s Integrated Resource Plan (IRP)</strong> and served as a key element of the project’s 
          co-creation and capacity building approach. The workshop marked the first introduction of two CCG open-source finance modelling tools – <strong>MINFin</strong> and <strong>FinTrack</strong> – 
          alongside the IAEA’s project finance tool, <strong>FINPLAN</strong>. 
          These tools were presented through a combination of lectures, discussion, and hands-on training sessions.
        </p>
        <p class="animate-in">
          <a href="https://www.linkedin.com/posts/climate-compatible-growth-ccg_data2deal-zambia-irpfinancingstrategy-activity-7316468550330642435--vk6/" target="_blank" class="btn btn-outline-primary sky-blue-accent" style="border-color: #3490dc; color: #3490dc;">
            View Workshop Post →
          </a>
        </p>
        <p class="text-center mt-3">
          <img src="assets/img/EMP/Zambia.jpg" alt="Zambia Financial Modelling Workshop Group Photo" class="img-fluid rounded shadow-sm" style="max-width: 500px;">
        </p>
      </div>
    </div>

    <!-- Optional Placeholder for Future Training Section -->
    <div class="mt-5 animate-in">
      <h3 class="alt-h3 mt-3" style="font-size: 1.25rem;">📘 Upcoming Learning Opportunities</h3>
      <p class="animate-in" style="font-size: 0.95rem; text-align: justify;">
        A new Open University course on <strong>national-scale financial modelling for energy transitions</strong> will launch soon. 
        Stay tuned for updates and registration details here.
      </p>
    </div>

  </div>
</section>

<style>
/* Fade-in animation for main title */
.fade-in-center {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeInUp 1s ease forwards;
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Animate-in effects for all elements */
.animate-in {
  opacity: 0;
  transform: translateY(30px);
  animation: animateIn 0.8s ease-out forwards;
  animation-delay: var(--animation-delay, 0s);
}

/* Staggered animation delays */
.animate-in:nth-child(1) { --animation-delay: 0.1s; }
.animate-in:nth-child(2) { --animation-delay: 0.2s; }
.animate-in:nth-child(3) { --animation-delay: 0.3s; }
.animate-in:nth-child(4) { --animation-delay: 0.4s; }
.animate-in:nth-child(5) { --animation-delay: 0.5s; }
.animate-in:nth-child(6) { --animation-delay: 0.6s; }
.animate-in:nth-child(7) { --animation-delay: 0.7s; }
.animate-in:nth-child(8) { --animation-delay: 0.8s; }
.animate-in:nth-child(9) { --animation-delay: 0.9s; }
.animate-in:nth-child(10) { --animation-delay: 1.0s; }

/* Column animations with staggered delays for 3-column layout */
.col-md-4.float-left.animate-in:nth-child(1) { animation-delay: 0.1s; }
.col-md-4.float-left.animate-in:nth-child(2) { animation-delay: 0.2s; }
.col-md-4.float-left.animate-in:nth-child(3) { animation-delay: 0.3s; }

/* Column hover effects */
.col-md-4.float-left {
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.col-md-4.float-left:hover {
  transform: translateY(-4px);
}

/* Standardize column height and content distribution */
.col-md-4.float-left > h3 {
  flex-shrink: 0;
  min-height: 5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin-bottom: 1rem;
  line-height: 1.3;
}

.col-md-4.float-left > p:first-of-type {
  flex-shrink: 0;
  text-align: center;
  margin-bottom: 1rem;
}

/* Standardized image container */
.col-md-4 img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  object-position: center;
  border-radius: 8px;
  transition: transform 0.3s ease;
}

.col-md-4 img:hover {
  transform: scale(1.02);
}

/* Text content area - flexible height */
.col-md-4.float-left > p.text-gray {
  flex: 1;
  margin-bottom: 1.5rem;
  line-height: 1.5;
}

/* Details section at bottom - aligned */
.col-md-4.float-left > details {
  margin-top: auto;
  align-self: flex-start;
}

/* Button alignment */
.col-md-4.float-left > details > summary {
  margin: 0;
}

/* List item animations */
li.animate-in:nth-child(1) { animation-delay: 0.1s; }
li.animate-in:nth-child(2) { animation-delay: 0.2s; }
li.animate-in:nth-child(3) { animation-delay: 0.3s; }
li.animate-in:nth-child(4) { animation-delay: 0.4s; }
li.animate-in:nth-child(5) { animation-delay: 0.5s; }
li.animate-in:nth-child(6) { animation-delay: 0.6s; }
li.animate-in:nth-child(7) { animation-delay: 0.7s; }
li.animate-in:nth-child(8) { animation-delay: 0.8s; }
li.animate-in:nth-child(9) { animation-delay: 0.9s; }

@keyframes animateIn {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* Hover effects for interactive elements */
.animate-in:hover {
  transform: translateY(-2px);
  transition: transform 0.3s ease;
}

/* Enhanced container animations */
.container .animate-in {
  animation-delay: 0.3s;
}

/* Button hover animations */
.btn.animate-in:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  transition: all 0.3s ease;
}

/* Image animations */
img.animate-in:hover {
  transform: scale(1.05);
  transition: transform 0.3s ease;
}

.toggle-arrow::after {
  content: '↓';
  display: inline-block;
  margin-left: 6px;
  transition: transform 0.3s ease;
}
details[open] .toggle-arrow::after {
  transform: rotate(180deg);
}
</style>