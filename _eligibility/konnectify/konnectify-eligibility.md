---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.
    type: individual
  - text: in the event You are entering into these Terms on behalf of any entity/company or its group, You possess the requisite authority to bind such entities, company, or its groups to these Terms.
    type: business
  minimum_age:
    text: You warrant to Us that You are aged 18 years or above
    value: '18'
  restricted_uses:
  - summary: No unlawful or infringing content
    text: (d) use the Services to store or process any content that infringes upon any person's intellectual property rights or is unlawful, racist, hateful, abusive, libelous, obscene, or discriminatory
  - summary: No sensitive personal information submitted
    text: You shall not disclose (and shall not permit any individual to disclose) any Sensitive Personal Information to Us for Processing.
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
name: Konnectify
provenance_date: '2026-11-09'
provider_name: Konnectify
provider_slug: konnectify
slug: konnectify-eligibility
source_date: '2026-11-09'
source_filename: konnectify-eligibility.yml
source_heading: Eligibility
source_page: https://konnectify.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Konnectify\naid: konnectify\nurl: https://konnectify.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You warrant to Us that You are aged 18 years or above and are competent to enter into this agreement.\n- type: business\n  text: in the event You are entering into these Terms on behalf of any entity/company or its group, You possess\n    the requisite authority to bind such entities, company, or its groups to these Terms.\nrestricted_uses:\n- summary: No unlawful or infringing content\n  text: (d) use the Services to\
  \ store or process any content that infringes upon any person's intellectual property\n    rights or is unlawful, racist, hateful, abusive, libelous, obscene, or discriminatory\n- summary: No sensitive personal information submitted\n  text: You shall not disclose (and shall not permit any individual to disclose) any Sensitive Personal Information\n    to Us for Processing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant to Us that You are aged 18 years or above\n"
source_yaml_url: https://artifacts.apis.io/konnectify/eligibility/konnectify-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Konnectify's own page on 2026-11-09.
synthetic: false
tags:
- Integration Platform
- Artificial Intelligence
- Automation
- Software-as-a-Service
- Low-Code
---
