---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization, and "you" means that organization.
    type: other
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: High-stakes decisions about people
    text: Use the Service to make decisions about a person's medical care, legal position, employment, credit, housing, or insurance.
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
name: Cerebrum
provenance_date: '2026-11-09'
provider_name: Cerebrum
provider_slug: askcerebrum-org
slug: askcerebrum-org-eligibility
source_date: '2026-11-09'
source_filename: askcerebrum-org-eligibility.yml
source_heading: Eligibility
source_page: https://askcerebrum.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cerebrum\naid: askcerebrum-org\nurl: https://askcerebrum.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" means that organization.\nrestricted_uses:\n- summary: High-stakes decisions about people\n  text: Use the Service to make decisions about a person's medical care, legal position, employment, credit, housing,\n    or insurance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/askcerebrum-org/eligibility/askcerebrum-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cerebrum's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Scientific
- Search
- Open Data
- Education
- Company
---
