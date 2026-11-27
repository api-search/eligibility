---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable use policy violations
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i) that violates any third-party right
  - summary: Export restrictions
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Motiva
provenance_date: '2026-11-10'
provider_name: Motiva
provider_slug: motiva
slug: motiva-eligibility
source_date: '2026-11-10'
source_filename: motiva-eligibility.yml
source_heading: Eligibility
source_page: https://www.motiva.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motiva\naid: motiva\nurl: https://www.motiva.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Acceptable use policy violations\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i)\n    that\
  \ violates any third-party right\n- summary: Export restrictions\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/motiva/eligibility/motiva-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Motiva's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Email Marketing
- Marketing Automation
- Artificial Intelligence
- Machine Learning
- Generative AI
- Oracle Eloqua
- Personalization
---
