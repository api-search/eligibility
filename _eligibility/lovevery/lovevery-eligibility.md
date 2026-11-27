---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: These Terms of Service apply to Lovevery Website and Mobile App users, customers, and prospective customers located in the United States and Canada.
  entity_types:
  - text: The Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: The Services are available only to, and may only be used by, individuals who are 18 years and older who can form legally binding contracts under applicable law. Individuals under the age of 18, but over the age of 13, may use the Services only in conjunction with and under the supervision of a parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: No bulk, wholesale or resale
    text: You agree not to purchase bulk, wholesale, or commercial quantities of our Products or sell, resell, lease, rent, or use for or in any shared-use club
  - summary: No medical or professional advice use
    text: you agree not to use the Website, Mobile App, Parent Courses, Services, or Content for such purposes.
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
name: Lovevery
provenance_date: '2026-11-09'
provider_name: Lovevery
provider_slug: lovevery
slug: lovevery-eligibility
source_date: '2026-11-09'
source_filename: lovevery-eligibility.yml
source_heading: Eligibility
source_page: https://lovevery.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lovevery\naid: lovevery\nurl: https://lovevery.com/pages/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: These Terms of Service apply to Lovevery Website and Mobile App users, customers, and prospective customers\n    located in the United States and Canada.\nentity_types:\n- type: individual\n  text: The Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: No bulk, wholesale or resale\n  text:\
  \ You agree not to purchase bulk, wholesale, or commercial quantities of our Products or sell, resell, lease,\n    rent, or use for or in any shared-use club\n- summary: No medical or professional advice use\n  text: you agree not to use the Website, Mobile App, Parent Courses, Services, or Content for such purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available only to, and may only be used by, individuals who are 18 years and older who\n    can form legally binding contracts under applicable law. Individuals under the age of 18, but over the age of\n    13, may use the Services only in conjunction with and under the supervision of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/lovevery/eligibility/lovevery-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Lovevery's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Retail
- Children
- Education
- Subscription
---
