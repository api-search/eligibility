---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms permit you to use the Services for your personal, non-commercial use only.
    type: individual
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Scraping, spidering or crawling
    text: (d) spam, phish, pharm, pretext, spider, crawl, or scrape;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgiBot
provenance_date: '2026-11-09'
provider_name: AgiBot
provider_slug: agibot
slug: agibot-eligibility
source_date: '2026-11-09'
source_filename: agibot-eligibility.yml
source_heading: Eligibility
source_page: https://store.agibot.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgiBot\naid: agibot\nurl: https://store.agibot.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Terms permit you to use the Services for your personal, non-commercial use only.\nrestricted_uses:\n- summary: Scraping, spidering or crawling\n  text: (d) spam, phish, pharm, pretext, spider, crawl, or scrape;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your\
  \ state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/agibot/eligibility/agibot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AgiBot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Humanoid Robots
- Embodied AI
- Artificial Intelligence
- Manufacturing
- Hardware
- Middleware
- ROS 2
- gRPC
- Protocol Buffers
- Simulation
- Machine Learning
- Open Source
- MCP
- Agentic Commerce
- China
---
