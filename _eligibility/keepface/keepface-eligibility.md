---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: By using the Service you represent that you and any organisation you act for are not subject to sanctions, embargoes, or other restrictions that would make our provision of the Service unlawful.
  entity_types:
  - text: '"Brand" means a business or individual using the Service to source, contact, and pay influencers.'
    type: business
  - text: '"Influencer" means an individual or agency creating content and accepting brand collaborations through the Service.'
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of legal majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: No off-platform bypass of fees
    text: Brands cannot bypass the Service to contact Influencers off-platform, scrape Influencer contact details, or solicit them through third-party agencies for the purpose of avoiding fees, for twelve (12) months after the most recent Campaign or Intelligence Profile unlock involving that Influencer.
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
name: KeepFace
provenance_date: '2026-11-09'
provider_name: KeepFace
provider_slug: keepface
slug: keepface-eligibility
source_date: '2026-11-09'
source_filename: keepface-eligibility.yml
source_heading: Eligibility
source_page: https://keepface.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KeepFace\naid: keepface\nurl: https://keepface.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: By using the Service you represent that you and any organisation you act for are not subject to sanctions,\n    embargoes, or other restrictions that would make our provision of the Service unlawful.\nentity_types:\n- type: business\n  text: '\"Brand\" means a business or individual using the Service to source, contact, and pay influencers.'\n- type: individual\n  text: '\"Influencer\" means an individual or agency creating content and accepting brand collaborations through\n\
  \    the Service.'\nrestricted_uses:\n- summary: No off-platform bypass of fees\n  text: Brands cannot bypass the Service to contact Influencers off-platform, scrape Influencer contact details,\n    or solicit them through third-party agencies for the purpose of avoiding fees, for twelve (12) months after\n    the most recent Campaign or Intelligence Profile unlock involving that Influencer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of legal majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/keepface/eligibility/keepface-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from KeepFace's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Influencer Marketing
- Creator Economy
- Marketing
- Social Media
- Affiliate Marketing
- Advocacy
- Campaign Management
- MCP
- AI Agents
- Attribution
- Webhook
---
