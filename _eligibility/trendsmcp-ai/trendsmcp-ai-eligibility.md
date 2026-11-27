---
api_specs:
- filename: trendsmcp-ai-trends-api-openapi.yml
  format: yaml
  label: trendsmcp-ai Trends API
  slug: trendsmcp-ai-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsmcp-ai/openapi/trendsmcp-ai-trends-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: you are not located in, ordinarily resident in, or a national of any country subject to comprehensive sanctions (including, at the time of drafting, Cuba, Iran, North Korea, Syria, the Crimea region, and the so-called Donetsk and Luhansk regions of Ukraine)
  entity_types:
  - text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher) and legally capable of entering into a binding contract to use the Service.
    type: individual
  - text: If you are using the Service on behalf of a company, organization, or any other legal entity, you represent and warrant that (a) you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher)
    value: '18'
  restricted_uses:
  - summary: Fully automated consequential decisions
    text: use the Service to make fully automated, consequential decisions about individuals (such as credit, employment, housing, insurance, or law-enforcement decisions);
  - summary: High-risk applications
    text: use the Service for high-risk applications where failure or inaccuracy could reasonably be expected to lead to death, personal injury, or severe environmental damage;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: trendsmcp-ai
provenance_date: '2026-11-10'
provider_name: trendsmcp-ai
provider_slug: trendsmcp-ai
slug: trendsmcp-ai-eligibility
source_date: '2026-11-10'
source_filename: trendsmcp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.trendsmcp.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: trendsmcp-ai\naid: trendsmcp-ai\nurl: https://www.trendsmcp.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not located in, ordinarily resident in, or a national of any country subject to comprehensive sanctions\n    (including, at the time of drafting, Cuba, Iran, North Korea, Syria, the Crimea region, and the so-called Donetsk\n    and Luhansk regions of Ukraine)\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher)\n    and legally capable\
  \ of entering into a binding contract to use the Service.\n- type: business\n  text: If you are using the Service on behalf of a company, organization, or any other legal entity, you represent\n    and warrant that (a) you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Fully automated consequential decisions\n  text: use the Service to make fully automated, consequential decisions about individuals (such as credit, employment,\n    housing, insurance, or law-enforcement decisions);\n- summary: High-risk applications\n  text: use the Service for high-risk applications where failure or inaccuracy could reasonably be expected to lead\n    to death, personal injury, or severe environmental damage;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher)\n"
source_yaml_url: https://artifacts.apis.io/trendsmcp-ai/eligibility/trendsmcp-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from trendsmcp-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Trends
- Data
- Analytics
- MCP
- Company
---
