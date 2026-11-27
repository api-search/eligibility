---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: individual
  minimum_age:
    text: you are not under the age of 13;
    value: '13'
  restricted_uses:
  - summary: Commercial endeavors
    text: The Site may not be used in connection with any commercial endeavors.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Outlier
provenance_date: '2026-11-10'
provider_name: Outlier
provider_slug: outlier
slug: outlier-eligibility
source_date: '2026-11-10'
source_filename: outlier-eligibility.yml
source_heading: Eligibility
source_page: https://www.outlier.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outlier\naid: outlier\nurl: https://www.outlier.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Commercial endeavors\n  text: The Site may not be used in connection with any commercial endeavors.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '13'\n  text: you are not under the age of 13;\n"
source_yaml_url: https://artifacts.apis.io/outlier/eligibility/outlier-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Outlier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Education
- E-Learning
- Dual Enrollment
- E-Commerce
- Shopify
- Agentic Commerce
- MCP
---
