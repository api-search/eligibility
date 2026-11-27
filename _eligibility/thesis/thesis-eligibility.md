---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is intended for users located in the United States. If you access this Site from outside the United States, you do so at your own risk and are responsible for compliance with local laws.
  entity_types:
  - text: This Site is intended for use by individuals who are at least 18 years of age and who access the Site in connection with business, employment, or professional purposes.
    type: individual
  - text: If you are accessing this Site on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: individuals who are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No PHI submission
    text: Do not submit Protected Health Information (PHI), patient data, or other confidential health information through this Site.
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
name: Thesis
provenance_date: '2026-11-10'
provider_name: Thesis
provider_slug: thesis
slug: thesis-eligibility
source_date: '2026-11-10'
source_filename: thesis-eligibility.yml
source_heading: Eligibility
source_page: https://thesiscare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thesis\naid: thesis\nurl: https://thesiscare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is intended for users located in the United States. If you access this Site from outside the United\n    States, you do so at your own risk and are responsible for compliance with local laws.\nentity_types:\n- type: individual\n  text: This Site is intended for use by individuals who are at least 18 years of age and who access the Site in\n    connection with business, employment, or professional purposes.\n- type: business\n  text: If you are accessing this Site\
  \ on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms.\nrestricted_uses:\n- summary: No PHI submission\n  text: Do not submit Protected Health Information (PHI), patient data, or other confidential health information\n    through this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: individuals who are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/thesis/eligibility/thesis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Thesis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical
- Care Management
- Health Plans
- AI Agents
---
