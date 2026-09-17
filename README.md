# sb-growth-spark

I am creating  a slick, Ai Inspired Investment Marketing site for StoragBlue,   Here is the JSON code that ChatGPT created for the site structure.  Please refer to attached deck. {
  "project": "StorageBlue Growth Fund, LP (SBGF)",
  "goal": "Create an institutional-grade investor website for the StorageBlue Growth Fund, LP (SBGF) using Goldman Sachs (goldmansachs.com) as the reference for design, tone, and motion. Use the attached 'SBGF V10.pdf' as the authoritative content source for all copy, data, and visuals. The site should highlight the fund’s institutional credibility, proven performance, and leadership in self-storage innovation.",
  "style": {
    "look_and_feel": "Minimal, modern, premium. Inspired by Goldman Sachs — focus on trust, whitespace, typography, and soft transitions.",
    "color_palette": {
      "primary": "#0E1A2B",
      "secondary": "#4A5B6C",
      "accent": "#C8A95D",
      "background": "#FFFFFF",
      "text": "#2C2C2C"
    },
    "typography": {
      "headline_font": "Playfair Display or Libre Baskerville",
      "body_font": "Inter or Source Sans Pro",
      "tone": "Institutional, concise, data-driven, authoritative"
    },
    "imagery": {
      "themes": ["NYC skyline", "industrial storage", "logistics", "architectural abstraction"],
      "effects": "Subtle parallax, low-opacity overlays, soft scroll animations"
    }
  },
  "structure": {
    "pages": [
      {
        "title": "Home",
        "content": [
          "Hero: 'StorageBlue Growth Fund, LP — Institutional Access to the Future of Self-Storage.'",
          "Subheadline: '$350M Growth Fund | $1B Buying Power | 35+ Years of Proven Performance.'",
          "Primary CTAs: 'Request Access', 'Download Overview'.",
          "Highlights Section: Strategy, Edge, Opportunity — drawn from pages 2–6 of the deck.",
          "Market Validation Carousel: Public Storage, Blackstone, CubeSmart logos (from page 11)."
        ]
      },
      {
        "title": "About",
        "content": [
          "Founder-driven story and StorageBlue’s 35+ year legacy (pages 25–26).",
          "Timeline from American Self-Storage to StorageBlue to SBGF.",
          "Quote: 'You can’t match the passion for success as in a Founder-driven company.'"
        ]
      },
      {
        "title": "Strategy",
        "content": [
          "Fund overview: $350M target raise, $1B buying power, 16–24% IRR, 65/35 leverage (pages 18–23).",
          "Map of target markets: NY/NJ, FL, TX, NV, AZ, CA, TN.",
          "Distribution waterfall visualization (page 23)."
        ]
      },
      {
        "title": "Portfolio",
        "content": [
          "Case studies and realized returns (pages 15–16).",
          "Interactive map of 6 initial StorageBlue facilities (page 20).",
          "KPIs: IRR %, MOIC, Total SqFt."
        ]
      },
      {
        "title": "Market Insight",
        "content": [
          "Key industry stats (pages 10–11, 44–45).",
          "Charts showing CAGR, rental rates, ownership fragmentation.",
          "Narrative: 'An underserved market meets institutional expertise.'"
        ]
      },
      {
        "title": "Innovation",
        "content": [
          "Automation and AI in self-storage (pages 40–42).",
          "Highlight: AI chatbots, predictive maintenance, dynamic pricing, revenue optimization."
        ]
      },
      {
        "title": "Leadership",
        "content": [
          "Executive Team and Advisors (pages 26–31).",
          "Grid layout with hover bios, board affiliations, and brand ambassador Ja Rule."
        ]
      },
      {
        "title": "Contact",
        "content": [
          "Request Access form (Name, Email, Firm, AUM, Accreditation).",
          "Static pages for Legal Disclaimer (page 46) and Contact Info (page 47)."
        ]
      }
    ]
  },
  "features": {
    "responsive_design": true,
    "sticky_header": true,
    "micro_interactions": true,
    "analytics_placeholder": true,
    "dark_mode_toggle": true,
    "lazy_loading": true,
    "investor_portal_placeholder": true
  },
  "copy_rules": {
    "rewrite_guidelines": [
      "Convert deck bullet points into polished, web-ready copy.",
      "Keep tone concise and authoritative.",
      "Use data visualizations for all numeric content.",
      "Add disclaimers on all fund-related content: 'Not an offer to sell or a solicitation to buy securities.'"
    ]
  },
  "compliance": {
    "include_disclaimer": true,
    "footer_text": "© StorageBlue, LLC 2025. Not an offer to sell or a solicitation to buy securities. See PPM for full terms and risks."
  },
  "deliverables": [
    "Responsive investor-grade website with CMS-ready sections.",
    "Animations, data visualizations, and secure 'Request Access' form.",
    "SEO metadata, social preview images, sitemap.xml, and robots.txt."
  ]
}

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://sb-growth-spark.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/d5652cca-6fb3-4915-9ebf-f48c892f9083).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
