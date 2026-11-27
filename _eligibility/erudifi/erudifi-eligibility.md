---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Non-Filipino citizens, and persons under the age of 18 are not permitted to access or use our Services unless their parent has consented in accordance with applicable law.
  entity_types:
  - text: 'For Students: Non-Filipino citizens, and persons under the age of 18 are not permitted to access or use our Services unless their parent has consented in accordance with applicable law.'
    type: individual
  - text: 'For partner schools and institutions: A corporation, branch office, or partnership registered and in good standing with the Philippine Securities and Exchange Commission (SEC), has a permanent place of business in the Philippines'
    type: business
  minimum_age:
    text: persons under the age of 18 are not permitted to access or use our Services unless their parent has consented in accordance with applicable law
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: The Company also reserves the right to reject any registration, deny access to the Site and/or decline any loan application in violation of these Terms and Conditions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Erudifi
provenance_date: '2026-11-09'
provider_name: Erudifi
provider_slug: erudifi
slug: erudifi-eligibility
source_date: '2026-11-09'
source_filename: erudifi-eligibility.yml
source_heading: Eligibility
source_page: https://bukas.ph/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Erudifi\naid: erudifi\nurl: https://bukas.ph/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Non-Filipino citizens, and persons under the age of 18 are not permitted to access or use our Services unless\n    their parent has consented in accordance with applicable law.\nentity_types:\n- type: individual\n  text: 'For Students: Non-Filipino citizens, and persons under the age of 18 are not permitted to access or use\n    our Services unless their parent has consented in accordance with applicable law.'\n- type: business\n  text: 'For partner schools and institutions: A corporation,\
  \ branch office, or partnership registered and in good\n    standing with the Philippine Securities and Exchange Commission (SEC), has a permanent place of business in\n    the Philippines'\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: The Company also reserves the right to reject any registration, deny access to the Site and/or decline any\n    loan application in violation of these Terms and Conditions.\nminimum_age:\n  value: '18'\n  text: persons under the age of 18 are not permitted to access or use our Services unless their parent has consented\n    in accordance with applicable law\n"
source_yaml_url: https://artifacts.apis.io/erudifi/eligibility/erudifi-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Erudifi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Education
- Student Financing
- Lending
- Financial Services
- Southeast Asia
---
