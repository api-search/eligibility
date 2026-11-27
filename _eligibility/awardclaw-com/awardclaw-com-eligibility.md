---
api_specs:
- filename: awardclaw-com-availability-api-openapi.yml
  format: yaml
  label: AwardClaw Availability API
  slug: awardclaw-com-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-availability-api-openapi.yml
- filename: awardclaw-com-briefing-api-openapi.yml
  format: yaml
  label: AwardClaw Briefing API
  slug: awardclaw-com-briefing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-briefing-api-openapi.yml
- filename: awardclaw-com-cards-api-openapi.yml
  format: yaml
  label: AwardClaw Cards API
  slug: awardclaw-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-cards-api-openapi.yml
- filename: awardclaw-com-drops-api-openapi.yml
  format: yaml
  label: AwardClaw Drops API
  slug: awardclaw-com-drops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-drops-api-openapi.yml
- filename: awardclaw-com-me-api-openapi.yml
  format: yaml
  label: AwardClaw Me API
  slug: awardclaw-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-me-api-openapi.yml
- filename: awardclaw-com-news-api-openapi.yml
  format: yaml
  label: AwardClaw News API
  slug: awardclaw-com-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-news-api-openapi.yml
- filename: awardclaw-com-watches-api-openapi.yml
  format: yaml
  label: AwardClaw Watches API
  slug: awardclaw-com-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardclaw-com/openapi/awardclaw-com-watches-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Automated access without written consent
    text: Use automated scripts, bots, or scrapers to access the Service without our written consent
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
name: AwardClaw
provenance_date: '2026-11-09'
provider_name: AwardClaw
provider_slug: awardclaw-com
slug: awardclaw-com-eligibility
source_date: '2026-11-09'
source_filename: awardclaw-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.awardclaw.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AwardClaw\naid: awardclaw-com\nurl: https://www.awardclaw.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\nrestricted_uses:\n- summary: Automated access without written consent\n  text: Use automated scripts, bots, or scrapers to access the Service without our written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/awardclaw-com/eligibility/awardclaw-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AwardClaw's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Awards
- Airlines
- Flight Deals
- Automation
- Newsletters
---
