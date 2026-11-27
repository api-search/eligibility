---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to them from territories where any of the contents of the Service are illegal is prohibited.
  entity_types:
  - text: If you are accessing or using the Service on behalf of an entity, you represent that you are authorized to bind such entity, in which case the terms “you” and “user” shall also include such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or disruptive use
    text: You warrant to KBRA that you will not use the Service for any purpose that is unlawful or prohibited by these Terms of Use, including but not limited to attempting or actually (i) disrupting, impairing or interfering with the Service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain content may require you to register your email and other basic information. Other content may require you to register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kroll Bond Rating Agency
provenance_date: '2026-11-09'
provider_name: Kroll Bond Rating Agency
provider_slug: kroll-bond-rating-agency
slug: kroll-bond-rating-agency-eligibility
source_date: '2026-11-09'
source_filename: kroll-bond-rating-agency-eligibility.yml
source_heading: Eligibility
source_page: https://www.kbra.com/legal/terms-of-use/website
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kroll Bond Rating Agency\naid: kroll-bond-rating-agency\nurl: https://www.kbra.com/legal/terms-of-use/website\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to them from territories where any of the contents of the Service are illegal is prohibited.\nentity_types:\n- type: business\n  text: If you are accessing or using the Service on behalf of an entity, you represent that you are authorized\n    to bind such entity, in which case the terms “you” and “user” shall also include such entity.\nrestricted_uses:\n- summary: No unlawful or disruptive use\n  text: You warrant to\
  \ KBRA that you will not use the Service for any purpose that is unlawful or prohibited by\n    these Terms of Use, including but not limited to attempting or actually (i) disrupting, impairing or interfering\n    with the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain content may require you to register your email and other basic information. Other content may require\n    you to register for an account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kroll-bond-rating-agency/eligibility/kroll-bond-rating-agency-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Kroll Bond Rating Agency's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit Ratings
- Financial Services
- Financial Data
- Structured Finance
- Fixed Income
- Risk Management
- Analytics
- Market Data
- NRSRO
---
