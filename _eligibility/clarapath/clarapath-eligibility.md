---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We operate the Services from the United States of America. If you choose to access the Services from outside the United States of America, you are responsible for complying with applicable local laws.
  entity_types:
  - text: You may use our Services only if you can form a legally binding contract with us
    type: individual
  - text: If you are an individual and you access or use our Services on behalf of a company, organization, principal, or other entity, such as your employer (each, together with its affiliates, an “Organization”), then
    type: business
  minimum_age:
    text: To use our Services, you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No protected health information
    text: store “protected health information” (as such term is defined under the Health Insurance Portability and Accountability Act of 1996)
  - summary: No images without COPPA parental consent
    text: store or process any images on or through the Services for which you have not obtained required verifiable parental consent under the Children’s Online Privacy Protection Act (COPPA) or similar applicable laws
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
name: Clarapath
provenance_date: '2026-11-09'
provider_name: Clarapath
provider_slug: clarapath
slug: clarapath-eligibility
source_date: '2026-11-09'
source_filename: clarapath-eligibility.yml
source_heading: Eligibility
source_page: https://clarapath.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clarapath\naid: clarapath\nurl: https://clarapath.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We operate the Services from the United States of America. If you choose to access the Services from outside\n    the United States of America, you are responsible for complying with applicable local laws.\nentity_types:\n- type: individual\n  text: You may use our Services only if you can form a legally binding contract with us\n- type: business\n  text: If you are an individual and you access or use our Services on behalf of a company, organization, principal,\n  \
  \  or other entity, such as your employer (each, together with its affiliates, an “Organization”), then\nrestricted_uses:\n- summary: No protected health information\n  text: store “protected health information” (as such term is defined under the Health Insurance Portability and\n    Accountability Act of 1996)\n- summary: No images without COPPA parental consent\n  text: store or process any images on or through the Services for which you have not obtained required verifiable\n    parental consent under the Children’s Online Privacy Protection Act (COPPA) or similar applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use our Services, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/clarapath/eligibility/clarapath-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Clarapath's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Devices
- Robotics
- Pathology
- Histology
- Laboratory Automation
- Diagnostics
- Life Sciences
---
