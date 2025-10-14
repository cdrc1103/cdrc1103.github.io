---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-bg.jpg # Optional: add a hero image
  actions:
    - label: "View Projects"
      url: "/projects/"
    - label: "Download Resume"
      url: "/assets/resume.pdf"
excerpt: "Lead AI Consultant - GenAI Platform Architecture"
intro: 
  - excerpt: "Lead AI Consultant specializing in robust AI platforms • 4 years of enterprise consulting experience • Open to positions in Singapore"
feature_row:
  - image_path: # Optional
    alt: "Generative AI"
    title: "Generative AI Expertise"
    excerpt: "Production-grade LLM applications, RAG systems, and AI platforms delivering measurable EBIT impact in Financial Services"
  - image_path: # Optional
    alt: "Leadership"
    title: "Team Leadership"
    excerpt: "Leading cross-functional teams, mentoring data scientists, and managing stakeholder relationships at C-level"
  - image_path: # Optional
    alt: "MLOps"
    title: "Production ML Systems"
    excerpt: "End-to-end AI solution delivery from ideation to deployment, with focus on scalability and business outcomes"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

## 🎯 Key Achievements

- 🚀 **40% efficiency gain** deploying Gen AI platform in tier-1 financial institution
- 💰 **€1.5M+ cost savings** through AI-driven process automation
- 👥 **Built and mentored** high-performing data science team of 3
- 📈 **Led business development** activities generating €5M+ in AI investments

---

## 💼 Recent Projects

{% assign portfolio_items = site.portfolio | limit: 3 %}
{% for item in portfolio_items %}
  <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
  <p>{{ item.excerpt }}</p>
{% endfor %}

<a href="/projects/" class="btn btn--primary">View All Projects →</a>

---

## 🌏 Open to Opportunities in Singapore

I'm actively seeking **Manager/Senior Manager roles in AI/ML** in Singapore's thriving tech ecosystem. With expertise in Generative AI and Financial Services, I'm ready to contribute to Singapore's position as Asia's AI hub.

<a href="/contact/" class="btn btn--success btn--large">Let's Connect</a>