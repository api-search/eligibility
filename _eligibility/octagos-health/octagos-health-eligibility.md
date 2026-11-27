---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: International Use. The Site are intended for users located within the United States.
  entity_types:
  - text: you agree that you are at least 13 years old or a duly organized, validly existing business, organization, or other legal entity in good standing
    type: individual
  - text: you may use the Site for non-personal and/or commercial use only if you are an organization and only in furtherance of an otherwise applicable agreement
    type: business
  minimum_age:
    text: The Site is not intended for children under the age of 13 (or the applicable age of minority in your jurisdiction)
    value: '13'
  restricted_uses:
  - summary: No commercial use without permission
    text: You may not use any Octagos Site for any other purpose, including any commercial purpose, without the prior express written permission of an authorized representative of Octagos in each instance
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be asked to register an account or have any account registered for you, and provide certain registration details or other information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Octagos Health
provenance_date: '2026-11-10'
provider_name: Octagos Health
provider_slug: octagos-health
slug: octagos-health-eligibility
source_date: '2026-11-10'
source_filename: octagos-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.octagos.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Octagos Health\naid: octagos-health\nurl: https://www.octagos.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: International Use. The Site are intended for users located within the United States.\nentity_types:\n- type: individual\n  text: you agree that you are at least 13 years old or a duly organized, validly existing business, organization,\n    or other legal entity in good standing\n- type: business\n  text: you may use the Site for non-personal and/or commercial use only if you are an organization and only in\n    furtherance of an otherwise applicable agreement\n\
  restricted_uses:\n- summary: No commercial use without permission\n  text: You may not use any Octagos Site for any other purpose, including any commercial purpose, without the prior\n    express written permission of an authorized representative of Octagos in each instance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be asked to register an account or have any account registered for you, and provide certain registration\n    details or other information.\nminimum_age:\n  value: '13'\n  text: The Site is not intended for children under the age of 13 (or the applicable age of minority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/octagos-health/eligibility/octagos-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Octagos Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Cardiology
- Remote Patient Monitoring
- Medical Devices
- Artificial Intelligence
- Health IT
- Interoperability
- FHIR
- EHR Integration
- Clinical Workflow
---
