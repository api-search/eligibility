---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims concerning whether the Platform may be used or the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Referral program abuse
    text: Referrers cannot refer themselves or create multiple, fictitious or fake accounts with Delphia.
  - summary: Bulk or spam distribution
    text: Bulk email distribution, distribution to strangers, or any other use of the services described herein in a manner that is not promoted is expressly prohibited
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Delphia is not under any obligation to accept any individual as a Registered Customer and may accept or reject any registration at its sole and complete discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delphia
provenance_date: '2026-11-09'
provider_name: Delphia
provider_slug: delphia
slug: delphia-eligibility
source_date: '2026-11-09'
source_filename: delphia-eligibility.yml
source_heading: Eligibility
source_page: https://delphia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delphia\naid: delphia\nurl: https://delphia.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims concerning whether the Platform may be used or the Content may be downloaded, viewed,\n    or be appropriate for use outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Referral program abuse\n  text: Referrers cannot refer themselves or create multiple, fictitious or fake accounts with Delphia.\n- summary: Bulk or spam distribution\n  text: Bulk email distribution, distribution to strangers, or any other use of the services\
  \ described herein in\n    a manner that is not promoted is expressly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Delphia is not under any obligation to accept any individual as a Registered Customer and may accept or\n    reject any registration at its sole and complete discretion.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delphia/eligibility/delphia-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Delphia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Fintech
- Investing
- Artificial Intelligence
- Data
- Quantitative Finance
---
