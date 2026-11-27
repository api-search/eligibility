---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for users located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Use on behalf of third parties
    text: (d) use or access the Service on behalf of or to provide any product or Service to third parties;
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
name: Greenlite
provenance_date: '2026-11-09'
provider_name: Greenlite
provider_slug: greenlite
slug: greenlite-eligibility
source_date: '2026-11-09'
source_filename: greenlite-eligibility.yml
source_heading: Eligibility
source_page: https://greenlite.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Greenlite\naid: greenlite\nurl: https://greenlite.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for users located within the United States. We make no representation that the Service\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: Use on behalf of third parties\n  text: (d) use or access the Service on behalf of or to provide any product or Service to third parties;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/greenlite/eligibility/greenlite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Greenlite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Construction
- Permitting
- Plan Review
- Compliance
- Government
- Real Estate
---
