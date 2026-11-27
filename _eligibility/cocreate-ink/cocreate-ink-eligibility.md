---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Competitors barred from access
    text: No employee, independent contractor, agent, or affiliate of any competitor of CO:CREATE, including any company that provides a platform to facilitate the sale of digital collectables or tattoos is permitted to view, access, or use any portion of the Service without express written permission from CO:CREATE.
  - summary: Financial activities subject to licensing
    text: carry out financial activities subject to registration or licensing, including but not limited to creating, listing, or buying securities, commodities, options, real estate, or debt instruments
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may also require you to verify your identity, your payment method, and/or your eligibility to use the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Co:Create
provenance_date: '2026-11-09'
provider_name: Co:Create
provider_slug: cocreate-ink
slug: cocreate-ink-eligibility
source_date: '2026-11-09'
source_filename: cocreate-ink-eligibility.yml
source_heading: Eligibility
source_page: https://www.cocreate.ink/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Co:Create\naid: cocreate-ink\nurl: https://www.cocreate.ink/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitors barred from access\n  text: No employee, independent contractor, agent, or affiliate of any competitor of CO:CREATE, including any company\n    that provides a platform to facilitate the sale of digital collectables or tattoos is permitted to view, access,\n    or use any portion of the Service without express written permission from CO:CREATE.\n- summary: Financial activities\
  \ subject to licensing\n  text: carry out financial activities subject to registration or licensing, including but not limited to creating,\n    listing, or buying securities, commodities, options, real estate, or debt instruments\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may also require you to verify your identity, your payment method, and/or your eligibility to use the\n    Service\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/cocreate-ink/eligibility/cocreate-ink-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Co:Create's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Low-Code
- Collaboration
- Digital Products
- E-Commerce
- Analytics
---
