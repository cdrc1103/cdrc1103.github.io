---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-bg.jpg # Optional: add a hero image
  # actions:
  #   - label: "View Recent Projects"
  #     url: "/projects/"
excerpt: "Senior AI Engineer - GenAI & ML Platforms"
intro: 
  - excerpt: "Senior AI Engineer specialized in planning and delivering robust GenAI & ML platforms • 4 years of enterprise consulting experience • Open to opportunities in Singapore"
sfeature_row:
  - image_path: # Optional
    alt: "Generative AI"
    title: "Generative AI"
    excerpt: "Deep knowledge about creating production LLM applications, RAG, and Agentic AI systems that deliver measurable EBIT impact."
  - image_path: # Optional
    alt: "Leadership"
    title: "Team Leadership"
    excerpt: "Experienced in leading cross-functional teams, mentoring junior team members, and managing stakeholder communication."
  - image_path: # Optional
    alt: "Software Development"
    title: "Software Development"
    excerpt: "Skilled in end-to-end software solution delivery from ideation to production deployment, with focus on scalability and business outcomes."
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

## Key Achievements

- 🚀 **40% efficiency gain** deploying Gen AI platform in tier-1 financial institution
- 💰 **€1.5M+ cost savings** through AI-driven process automation
- 👥 **Built and mentored** high-performing data science team of 3
- 📈 **Led business development** activities generating €5M+ in AI investments

---

## Recent Projects

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