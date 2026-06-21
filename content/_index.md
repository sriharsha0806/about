---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: markdown
    id: current-focus
    content:
      text: |
        <section class="home-editorial">
          <div class="home-editorial__intro">
            <h2>Current focus</h2>
            <p>I work on evaluation alignment and long-horizon agents at JPMC. The thread through my recent work is making LLM systems measurable, dependable, and useful inside enterprise workflows.</p>
          </div>
          <div class="focus-rail">
            <div>
              <span>01</span>
              <h3>Evaluation alignment</h3>
              <p>Designing feedback loops, evaluator-optimizer patterns, and quality gates that improve model behavior without relying on vibes.</p>
            </div>
            <div>
              <span>02</span>
              <h3>Long-horizon agents</h3>
              <p>Building agent workflows with routing, tool use, escalation, memory boundaries, and reliability checks for multi-step work.</p>
            </div>
            <div>
              <span>03</span>
              <h3>Production LLM systems</h3>
              <p>RAG, Text2SQL, MCP services, rate limits, retrieval quality, serving constraints, and the infrastructure needed to operate at scale.</p>
            </div>
          </div>
        </section>
  - block: markdown
    id: selected-systems
    content:
      text: |
        <section class="systems-showcase">
          <div class="systems-showcase__header">
            <h2>Selected systems shipped</h2>
            <p>Recent work across enterprise RAG, agentic automation, semantic search, and applied computer vision.</p>
          </div>
          <div class="system-list">
            <article>
              <div>
                <h3>Enterprise RAG platform</h3>
                <p>Health insurance SOP assistant with hybrid retrieval, department-scoped metadata, Azure ingestion, Azure AD access control, and sub-second serving.</p>
              </div>
              <strong>5K+ daily users</strong>
            </article>
            <article>
              <div>
                <h3>Evaluation-driven quality loop</h3>
                <p>DSPy evaluator-optimizer pattern, SME feedback, GEPA optimization, and Best-of-N sampling for sensitive workflows.</p>
              </div>
              <strong>40% quality lift</strong>
            </article>
            <article>
              <div>
                <h3>Text2SQL and agent automation</h3>
                <p>LangChain and LangGraph systems with routers, clarity agents, SQL generation, MCP-backed tools, guardrails, and human handoff.</p>
              </div>
              <strong>27% SQL gain</strong>
            </article>
            <article>
              <div>
                <h3>Bosch AI systems</h3>
                <p>Semantic defect search, bug-to-test linkage, interior monitoring, evidential uncertainty, GradCam++ analysis, and production ML tooling.</p>
              </div>
              <strong>75x throughput</strong>
            </article>
          </div>
        </section>
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: markdown
    id: research-reviewing
    content:
      text: |
        <section class="research-strip">
          <div>
            <h2>Research &amp; publications</h2>
            <p>Before production GenAI systems, I worked on semantic segmentation research at IIIT Hyderabad.</p>
            <ul class="pub-list">
              <li>
                <span class="pub-venue">CVPR Workshops 2018</span>
                <a class="pub-title" href="https://arxiv.org/abs/1806.08522">Efficient Semantic Segmentation using Gradual Grouping</a>
                <span class="pub-meta">Vallurupalli, Annamaneni, et al. · IIIT Hyderabad · <a href="https://arxiv.org/abs/1806.08522">arXiv</a> · <a href="https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w12/Vallurupalli_Efficient_Semantic_Segmentation_CVPR_2018_paper.pdf">PDF</a></span>
              </li>
            </ul>
          </div>
          <div>
            <h3>Technical reviewing</h3>
            <p>I review GenAI/ML books including <em>AI Agents in Action</em>, <em>AI Apps with LangChain</em>, <em>Generative AI Applications with AWS</em>, <em>Optimization Bootcamp</em>, and <em>Context Engineering with DSPy</em>.</p>
          </div>
          <div class="research-links">
            <a href="books/">Books</a>
            <a href="blog/">Blog</a>
            <a href="about-me/">About</a>
          </div>
          <p class="resume-source">Prefer the source? Download my résumé in <a href="uploads/resume.tex">LaTeX</a>.</p>
        </section>
---
