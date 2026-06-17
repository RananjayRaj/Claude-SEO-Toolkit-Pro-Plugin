# SEO Toolkit Pro

**A free Claude plugin with 12 specialized SEO skills.** Covers technical auditing, keyword research, content strategy, AI search optimization, local SEO, and more.

Works with **Claude Cowork** (desktop) and **Claude Code** (terminal).

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Skills](https://img.shields.io/badge/Skills-12-green.svg)](#all-12-skills)
[![Claude](https://img.shields.io/badge/Claude-Cowork%20%7C%20Code-orange.svg)](https://claude.ai)

---

## What This Plugin Does

Install one `.plugin` file and get 12 ready-to-use SEO skills inside Claude. Each skill handles a specific part of SEO - from crawlability checks to AI search optimization - so you can run audits, generate briefs, cluster keywords, and build content strategies without leaving your Claude session.

The skills also chain together. Run keyword clustering first, feed the top cluster into the content brief generator, then pass that brief through the AEO optimizer. One session, raw keywords to a fully optimized, AI-ready content brief.

---

## Installation

### Claude Cowork (Desktop App)

1. Download `seo-toolkit-pro.plugin` from the [Releases](../../releases) page
2. Open Claude Cowork on your desktop
3. Click the **Plugins** icon in the left sidebar
4. Select **Install from file**
5. Choose the `.plugin` file you downloaded
6. Click **Install** - the plugin appears in your skills panel instantly

> Requires a Claude Pro or Max plan. Upgrade at [claude.ai](https://claude.ai) if you're on the free tier.

### Claude Code (Terminal)

1. Download `seo-toolkit-pro.plugin` from the [Releases](../../releases) page
2. Open your terminal and navigate to your project folder
3. Run:
   ```bash
   claude plugins install /path/to/seo-toolkit-pro.plugin
   ```
4. Confirm the install - Claude Code loads the skills automatically in your next session

> Claude Code requires a paid plan. If you haven't set it up yet:
> ```bash
> npm install -g @anthropic-ai/claude-code
> ```

---

## All 12 Skills

### 1. Technical SEO Auditor
Full technical health check for any website. Covers crawlability, indexation, URL structure, redirects, Core Web Vitals, mobile usability, and security. Output is a prioritized issue list with exact fix instructions.

**Trigger:** `/technical-audit` or *"run a technical SEO audit on mysite.com"*

### 2. Keyword Clustering + Intent Mapper
Give it a flat list of keywords. It groups them into semantic clusters, assigns search intent (informational, commercial, transactional) to each cluster, maps the funnel stage (TOFU/MOFU/BOFU), and recommends whether to create a new page or optimize an existing one.

**Trigger:** `/keyword-cluster` or *"cluster these keywords for my site"*

### 3. Topical Authority Planner
Give it a topic and it builds your entire content strategy. Pillar pages, cluster posts, interlinking map, and a 6-month content roadmap.

**Trigger:** `/topical-authority` or *"build a topical authority plan for AI marketing"*

### 4. SEO Content Brief Generator
Give it a keyword and get a complete, ready-to-write content brief. Includes heading structure, word count target, semantic keywords, competitor gap analysis, FAQ section, and internal link suggestions.

**Trigger:** `/content-brief` or *"create a content brief for the keyword AI marketing tools"*

### 5. SEO Keyword Optimization
Focused on making existing content search-ready. Covers meta descriptions, title tags, on-page keyword placement, and optimization recommendations for live pages.

**Trigger:** `/keyword-research` or *"optimize this page for SEO"*

### 6. AEO Answer Engine Optimizer
Optimizes your content to appear in Google AI Overviews, Bing Copilot, Perplexity, and voice search results. Includes direct-answer formatting and FAQ schema recommendations.

**Trigger:** `/aeo-optimizer` or *"optimize for Google AI Overviews"*

### 7. GEO Content Optimizer
Generative Engine Optimization - structures your content so ChatGPT, Claude, and Gemini cite it when answering questions in your niche. This is the future of organic visibility.

**Trigger:** `/geo-optimizer` or *"optimize for ChatGPT and Perplexity"*

### 8. Content Cannibalization Detector
Finds pages on your site that are competing for the same keywords and splitting your rankings. Recommends whether to consolidate or differentiate each conflicting pair.

**Trigger:** `/cannibalization-check` or *"find keyword cannibalization on my site"*

### 9. Core Web Vitals Optimizer
Diagnoses LCP, INP, and CLS issues with specific fixes - render-blocking resources, image optimization, layout shift causes. Actionable output, not just scores.

**Trigger:** `/core-web-vitals` or *"fix my Core Web Vitals"*

### 10. Internal Linking Strategist
Plans your internal link architecture. Covers PageRank distribution, orphan page fixes, anchor text strategy, and hub-and-spoke content structure.

**Trigger:** `/internal-links` or *"plan internal linking for my site"*

### 11. Local SEO Playbook Generator
Complete local SEO strategy for any business. Google Business Profile optimization, citation targets, review management templates, NAP consistency audit, and geo-targeted content recommendations.

**Trigger:** `/local-seo` or *"local SEO strategy for Acme Plumbing in Austin TX"*

### 12. Schema Tag Generator
Generates ready-to-paste JSON-LD structured data for any page type: Article, FAQ, Product, LocalBusiness, HowTo, Event, and more. Zero coding required.

**Trigger:** `/schema-generator` or *"generate schema markup for my FAQ page"*

---

## 3 Ways to Use the Skills

### Method 1: Slash Commands

Type `/` followed by the command name in Claude.

```
/technical-audit yoursite.com
/keyword-cluster [paste your keyword list]
/content-brief best project management software
```

### Method 2: Natural Language

Just describe what you need. Once the plugin is installed, Claude picks the right skill automatically.

```
"Do a technical SEO audit of this website"
"Generate a content brief for the keyword AI marketing tools"
"My two pages are competing for the same keyword - help me fix it"
```

### Method 3: Chained Workflows (Recommended)

Feed the output of one skill into the next to build a full SEO pipeline.

**Example chain:**
1. Run **Keyword Clustering** on your keyword list
2. Take the top cluster, run **SEO Content Brief Generator** on it
3. Take that brief, run **AEO Answer Engine Optimizer** on it

Each output becomes the input for the next step. One session: raw keywords to a fully optimized, AI-ready content brief.

---

## Quick Reference

| Skill | Slash Command | Example Trigger |
|-------|--------------|-----------------|
| Technical SEO Auditor | `/technical-audit` | "technical audit of mysite.com" |
| Keyword Clustering | `/keyword-cluster` | "cluster these keywords" |
| Topical Authority Planner | `/topical-authority` | "topical authority plan for [topic]" |
| SEO Content Brief | `/content-brief` | "content brief for keyword [keyword]" |
| SEO Keyword Optimization | `/keyword-research` | "optimize this page for SEO" |
| AEO Optimizer | `/aeo-optimizer` | "optimize for Google AI Overviews" |
| GEO Content Optimizer | `/geo-optimizer` | "optimize for ChatGPT/Perplexity" |
| Cannibalization Detector | `/cannibalization-check` | "find keyword cannibalization" |
| Core Web Vitals | `/core-web-vitals` | "fix my Core Web Vitals" |
| Internal Linking | `/internal-links` | "plan internal linking for my site" |
| Local SEO Playbook | `/local-seo` | "local SEO strategy for [business]" |
| Schema Generator | `/schema-generator` | "generate schema for [page type]" |

---

## Plugin Structure

```
seo-toolkit-pro/
  .claude-plugin/
    plugin.json
  commands/
    aeo-optimizer.md
    cannibalization-check.md
    content-brief.md
    core-web-vitals.md
    geo-optimizer.md
    internal-links.md
    keyword-cluster.md
    keyword-research.md
    local-seo.md
    schema-generator.md
    technical-audit.md
    topical-authority.md
  skills/
    aeo-answer-engine-optimizer/
      SKILL.md
    content-cannibalization-detector/
      SKILL.md
    core-web-vitals-optimizer/
      SKILL.md
    geo-content-optimizer/
      SKILL.md
    internal-linking-strategist/
      SKILL.md
    keyword-clustering-intent-mapper/
      SKILL.md
    local-seo-playbook-generator/
      SKILL.md
      references/
      scripts/
    schema-tag-generator/
      SKILL.md
    seo-content-brief-generator/
      SKILL.md
      references/
      scripts/
    seo-keyword-optimization/
      SKILL.md
    technical-seo-auditor/
      SKILL.md
    topical-authority-planner/
      SKILL.md
  README.md
```

---

## FAQ

**Do I need a paid Claude plan?**
Yes. Claude Cowork requires Claude Pro ($20/month) or Max. Claude Code also requires a paid plan. The plugin itself is free.

**Does this work with the Claude web version?**
The skills are built for Claude Cowork and Claude Code. Some skills can be triggered in the web version if you paste the skill content manually, but the cleanest experience is through the plugin.

**Can I use multiple skills in one session?**
Yes. Claude remembers context within a session, so you can chain skills back-to-back without re-explaining your site or niche each time. See the [Chained Workflows](#method-3-chained-workflows-recommended) section above.

**The plugin isn't triggering automatically. What do I do?**
Make sure the plugin is listed as "active" in your plugins panel. If it shows as installed but not active, toggle it on, then start a new session.

---

## Contributing

Contributions are welcome. If you'd like to improve an existing skill or add a new one:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/new-skill`)
3. Commit your changes (`git commit -m 'Add new skill'`)
4. Push to the branch (`git push origin feature/new-skill`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

Built by [Rananjay](https://www.linkedin.com/in/rananjayraj/) - The AI Driven Marketer

Follow along on [LinkedIn](https://www.linkedin.com/in/rananjayraj/) for more Claude skills, AI marketing workflows, and automation breakdowns.
