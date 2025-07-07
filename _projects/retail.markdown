---
layout: project
title: "Empowering the Frontline"
project-date: "March 2024–Current"
date: 2001-05-01 00:00:00
description: "From complex store data to clear and confident actions."
teaser-image: assets/img/retail-teaser.png
tags: [Research, Strategy, Gamification]
---

<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container content-wrapper">
    <h1>{{ page.title }}</h1>
    <p>{{ page.description }}</p>
    <div class="none">
      <img src="/assets/img/retail-teaser.png" class="img-fluid rounded" alt="Retail Screens">
    </div>
  </div>
</div>

<div class="full-width-section" style="background-color: #fff;">
  <div class="container content-wrapper">
    <div class="row">
      <div class="col-8">
        <h2>🎯 Overview</h2>
        <p><strong>Flow</strong> is a B2B retail platform in Japan that turns in-store data — from POS, sensors, and cameras — into insights. But dashboards alone weren’t enough.</p>
        <p>I focused on a bigger goal: helping non-technical store staff feel confident acting on data, not just watching it.</p>
        <p>Constraints created focus: we saw an opportunity to simplify data literacy, support new staff, and use LLMs to translate raw metrics into clear, human-language guidance.</p>
      </div>
      <div class="col-4">
        <p><strong>Role</strong></p>
        <p>Lead UX Designer (Solo)</p>
        {% for tag in page.tags %}
        <span class="badge rounded-pill bg-dark">{{ tag }}</span>
        {% endfor %}
        <p>{{ page.project-date }}</p>
      </div>
    </div>
  </div>
</div>

<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container content-wrapper">
    <h3>🔍 The Challenge</h3>
    <p>Japan’s retail sector is under pressure — aging demographics, ecommerce competition, and labor shortages. Physical stores must adapt, but many struggle with digital tools.</p>
    <p>Flow’s platform was underused and perceived as “just a dashboard.” We needed to shift it into a day-to-day decision-support tool for busy frontline staff.</p>
    <ul>
      <li>Low data literacy → users overwhelmed by raw metrics</li>
      <li>High turnover → poor knowledge transfer</li>
      <li>HQ and store teams misaligned</li>
      <li>No clear guidance on “what to do” with the data</li>
    </ul>
  </div>
</div>

<div class="full-width-section" style="background-color: #fff;">
  <div class="container content-wrapper">
    <h3>🕰️ Before: Legacy Dashboard Experience</h3>
    <p>The original dashboard overwhelmed users with difficult to understand metrics, lacked clear next steps, and presented the same UI across diverse store contexts — creating confusion and low engagement.</p>
    <div style="max-width: 600px; margin: 2rem auto;">
      <img src="/assets/img/legacy-dashboard.png" class="img-fluid rounded" alt="Dashboard Screenshot">
    </div>
  </div>
</div>

<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container content-wrapper">
    <h3>🔎 Discovery & Design Process</h3>
    <ul>
      <li>Audited the legacy platform UX</li>
      <li>Ran <strong>25+ interviews</strong> across 6 retail brands</li>
      <li>Synthesized key themes: tech fatigue, fragmented knowledge, low data confidence</li>
      <li>Mapped common workflows — from shift planning to store performance reviews</li>
      <li>Reframed data presentation using a simple structure: <em>What’s happening? → So what? → Now what?</em></li>
    </ul>
    <div style="max-width: 600px; margin: 2rem auto;">
      <img src="/assets/img/interviews.png" class="img-fluid rounded" alt="User Interview Repository">
    </div>
  </div>
</div>

<div class="full-width-section" style="background-color: #fff;">
  <div class="container content-wrapper">
    <h3>🧩 From Dashboards to Action</h3>
    <p>Rather than build more charts, I turned raw store data — both qualitative and quantitative — into contextual, scannable suggestions staff could actually use on the floor.</p>
    <p>Behind the scenes, select inputs (e.g. traffic patterns, sales drops, staff observations) are fed into a large language model (LLM) that generates relevant, natural-language prompts. I treated prompt engineering as part of the UX — refining tone, clarity, and relevance through iterative tuning informed by staff feedback.</p>
    <p>The resulting guidance appears in card format — grouped under categories like: <strong>Ideas</strong>, <strong>Improvement</strong>, and <strong>Completed</strong>. They’re lightweight, symbolic, and a little bit gamified — designed to reduce friction and encourage follow-through.</p>
    <div class="row text-left mt-5">
      <div class="col-md-4 mb-4">
        <img src="/assets/img/flow-cards-tasklist.png" alt="Task List" class="img-fluid rounded mb-3">
        <h6>Store Task List</h6>
        <p>A list of simple, data-backed actions — with checkmarks and a progress bar to help staff stay on track.</p>
      </div>
      <div class="col-md-4 mb-4">
        <img src="/assets/img/flow-cards-task.png" alt="Action Card" class="img-fluid rounded mb-3">
        <h6>One Card at a Time</h6>
        <p>Each card offers a clear task, with context and reasoning. Users can complete, skip, or browse at their own pace.</p>
      </div>
      <div class="col-md-4 mb-4">
        <img src="/assets/img/flow-cards-complete.png" alt="All Done" class="img-fluid rounded mb-3">
        <h6>Progress Reinforced</h6>
        <p>A sense of completion matters. The wrap-up view helps reinforce habit-building and daily return use.</p>
      </div>
    </div>
  </div>
</div>

<div class="full-width-section" style="background-color: #EDEFF2;">
  <div class="container content-wrapper">
    <h3>👀 Early Impact & Signals</h3>
    <ul>
      <li>Helped shift product perception from passive dashboard → active support tool</li>
      <li><strong>Retired the native iOS app</strong>:
        <ul>
          <li>Freed up development resources</li>
          <li>Reduced friction — web app available on any device, instantly</li>
          <li>Faster iteration with a single codebase</li>
        </ul>
      </li>
      <li>LLM-driven natural language suggestions became a key enabler — turning complex data into guidance staff could act on</li>
    </ul>
  </div>
</div>
