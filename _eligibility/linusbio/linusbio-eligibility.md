---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'The LinusBio Offerings are intended for people located within the United States. At this time, the Lab cannot receive Samples from residents located in the following locations: New York.'
  entity_types:
  - text: You must be at least 18 years old to access or use the Products and Services, or to prescribe, order, authorize or consent to the performance of either Test.
    type: individual
  - text: If you are an individual who would access any of the Products and Services on behalf of, or in connection with your work for, an entity, organization, or company, you represent and warrant that you have authority to bind, and you hereby bind, such entity, organization, or company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to access or use the Products and Services, or to prescribe, order, authorize or consent to the performance of either Test.
    value: '18'
  restricted_uses:
  - summary: No claims to federal health programs
    text: If you are a federal health care program beneficiary, you also agree that you will not submit a claim for reimbursement to any federal or state health care program for the costs of the Products or Medical Services.
  - summary: Lab sample restriction for New York residents
    text: 'At this time, the Lab cannot receive Samples from residents located in the following locations: New York.'
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
name: LinusBio
provenance_date: '2026-11-09'
provider_name: LinusBio
provider_slug: linusbio
slug: linusbio-eligibility
source_date: '2026-11-09'
source_filename: linusbio-eligibility.yml
source_heading: Eligibility
source_page: https://traced.life/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LinusBio\naid: linusbio\nurl: https://traced.life/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'The LinusBio Offerings are intended for people located within the United States. At this time, the Lab\n    cannot receive Samples from residents located in the following locations: New York.'\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access or use the Products and Services, or to prescribe, order, authorize\n    or consent to the performance of either Test.\n- type: business\n  text: If you are an individual who\
  \ would access any of the Products and Services on behalf of, or in connection\n    with your work for, an entity, organization, or company, you represent and warrant that you have authority to\n    bind, and you hereby bind, such entity, organization, or company to these Terms.\nrestricted_uses:\n- summary: No claims to federal health programs\n  text: If you are a federal health care program beneficiary, you also agree that you will not submit a claim for\n    reimbursement to any federal or state health care program for the costs of the Products or Medical Services.\n- summary: Lab sample restriction for New York residents\n  text: 'At this time, the Lab cannot receive Samples from residents located in the following locations: New York.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access or use the Products and Services, or to prescribe, order, authorize\n    or consent to\
  \ the performance of either Test.\n"
source_yaml_url: https://artifacts.apis.io/linusbio/eligibility/linusbio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from LinusBio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Diagnostics
- Precision Medicine
- Biotechnology
- Exposomics
- Life Sciences
- Autism
- Commerce
- Agents
---
