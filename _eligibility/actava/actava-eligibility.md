---
api_specs:
- filename: actava-models-api-openapi.yml
  format: yaml
  label: Actava.ai Models API
  slug: actava-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actava/openapi/actava-models-api-openapi.yml
- filename: actava-chat-completions-api-openapi.yml
  format: yaml
  label: Actava.ai Chat Completions API
  slug: actava-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actava/openapi/actava-chat-completions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The CURA Services may not be available in all countries or regions, and we may use technical means, including IP address controls, to restrict access from jurisdictions where we do not offer them.
  entity_types:
  - text: You must be at least 18 years of age to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent and warrant that you have authority to do so and to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Sole-basis decisions with significant effects
    text: Use the CURA Services to make, or as the sole basis for, decisions that produce legal or similarly significant effects on individuals (including clinical, coverage, eligibility, employment, or credit decisions) without meaningful review by a qualified human
  - summary: PHI and regulated data
    text: Submit PHI or other regulated data outside of an environment covered by an executed BAA
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
name: Actava.ai
provenance_date: '2026-11-09'
provider_name: Actava.ai
provider_slug: actava
slug: actava-eligibility
source_date: '2026-11-09'
source_filename: actava-eligibility.yml
source_heading: Eligibility
source_page: https://www.actava.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Actava.ai\naid: actava\nurl: https://www.actava.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The CURA Services may not be available in all countries or regions, and we may use technical means, including\n    IP address controls, to restrict access from jurisdictions where we do not offer them.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent and warrant that you have authority\n    to do so and to bind that organization to\
  \ these Terms.\nrestricted_uses:\n- summary: Sole-basis decisions with significant effects\n  text: Use the CURA Services to make, or as the sole basis for, decisions that produce legal or similarly significant\n    effects on individuals (including clinical, coverage, eligibility, employment, or credit decisions) without\n    meaningful review by a qualified human\n- summary: PHI and regulated data\n  text: Submit PHI or other regulated data outside of an environment covered by an executed BAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/actava/eligibility/actava-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Actava.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Machine Learning
- Platform
---
