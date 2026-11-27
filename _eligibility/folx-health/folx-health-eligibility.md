---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are physically located in the United States and within a jurisdiction in which we offer our Service
  entity_types:
  - text: you are at least eighteen (18) years of age or the legal age of majority where you reside
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you are an authorized representative of the entity
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age or the legal age of majority where you reside if that jurisdiction has an older age of majority
    value: '18'
  restricted_uses:
  - summary: Jurisdictions where content is illegal
    text: Access to the Service from jurisdictions where the contents of the Service are illegal or penalized is prohibited.
  - summary: No care for minor children
    text: FOLX Health and its Providers are not able to provide healthcare services to minor children.
  - summary: Not for emergencies
    text: THE PLATFORM IS NOT APPROPRIATE FOR EMERGENCY CARE.
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
name: Folx Health
provenance_date: '2026-11-09'
provider_name: Folx Health
provider_slug: folx-health
slug: folx-health-eligibility
source_date: '2026-11-09'
source_filename: folx-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.folxhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Folx Health\naid: folx-health\nurl: https://www.folxhealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are physically located in the United States and within a jurisdiction in which we offer our Service\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age or the legal age of majority where you reside\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you are an authorized representative of the entity\nrestricted_uses:\n\
  - summary: Jurisdictions where content is illegal\n  text: Access to the Service from jurisdictions where the contents of the Service are illegal or penalized is prohibited.\n- summary: No care for minor children\n  text: FOLX Health and its Providers are not able to provide healthcare services to minor children.\n- summary: Not for emergencies\n  text: THE PLATFORM IS NOT APPROPRIATE FOR EMERGENCY CARE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age or the legal age of majority where you reside if that jurisdiction\n    has an older age of majority\n"
source_yaml_url: https://artifacts.apis.io/folx-health/eligibility/folx-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Folx Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- LGBTQIA+
- Telehealth
- Digital Health
- Gender-Affirming Care
- Mental Health
- Primary Care
---
