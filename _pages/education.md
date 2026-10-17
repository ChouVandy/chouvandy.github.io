---
layout: archive
title: "Education"
permalink: /education/
author_profile: true
---

<style>
  .edu-grid {
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 20px;
  }
  .edu-card {
    display: block;
    text-decoration: none !important;
    color: inherit;
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 24px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }
  .edu-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
    border-color: #0366d6;
  }
  .edu-card-university { border-left: 6px solid #007acc; }
  .edu-card-highschool { border-left: 6px solid #28a745; }
  .edu-card-primary    { border-left: 6px solid #ff9800; }
  
  .edu-title {
    margin: 0 0 8px 0;
    font-size: 1.25em;
    font-weight: 700;
    color: #24292e;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .edu-school {
    margin: 0 0 8px 0;
    font-size: 1em;
    font-weight: 600;
    color: #586069;
  }
  .edu-meta {
    font-size: 0.9em;
    color: #0366d6;
    font-weight: 600;
  }
  .arrow-icon {
    font-size: 0.9em;
    color: #aaa;
    transition: transform 0.3s ease, color 0.3s ease;
  }
  .edu-card:hover .arrow-icon {
    transform: translateX(6px);
    color: #0366d6;
  }
</style>

<div class="edu-grid">

  <!-- 1. សាកលវិទ្យាល័យ -->
  <a href="/education/university/" class="edu-card edu-card-university">
    <div class="edu-title">
      <span><i class="fas fa-graduation-cap" style="color: #007acc; margin-right: 10px;"></i>កម្រិតឧត្តមសិក្សា (University)</span>
      <i class="fas fa-arrow-right arrow-icon"></i>
    </div>
    <div class="edu-school">បរិញ្ញាបត្រវិទ្យាសាស្ត្រវិស្វកម្ម ជំនាញវិទ្យាសាស្ត្រទិន្នន័យ (ITC)</div>
    <div class="edu-meta">មើលព័ត៌មានលម្អិត &rarr;</div>
  </a>

  <!-- 2. អនុវិទ្យាល័យ និង វិទ្យាល័យ -->
  <a href="/education/high-school/" class="edu-card edu-card-highschool">
    <div class="edu-title">
      <span><i class="fas fa-school" style="color: #28a745; margin-right: 10px;"></i>មធ្យមសិក្សាទុតិយភូមិ និងបឋមភូមិ (High School)</span>
      <i class="fas fa-arrow-right arrow-icon"></i>
    </div>
    <div class="edu-school">វិទ្យាល័យ...</div>
    <div class="edu-meta">មើលព័ត៌មានលម្អិត &rarr;</div>
  </a>

  <!-- 3. បឋមសិក្សា -->
  <a href="/education/primary/" class="edu-card edu-card-primary">
    <div class="edu-title">
      <span><i class="fas fa-child" style="color: #ff9800; margin-right: 10px;"></i>កម្រិតបឋមសិក្សា (Primary Education)</span>
      <i class="fas fa-arrow-right arrow-icon"></i>
    </div>
    <div class="edu-school">សាលាបឋមសិក្សា ហ៊ុន សែន អូរច្រា (ខេត្តប៉ៃលិន)</div>
    <div class="edu-meta">មើលព័ត៌មានលម្អិត ទីតាំង និងរូបភាព &rarr;</div>
  </a>

</div>