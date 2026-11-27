---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you reside in the United States, subject to the Exceptions to Arbitration set forth below, you and Trusted each agree that any and all disputes between consumer users of Trusted and the Trusted Group
  entity_types:
  - text: When you set up an individual user account on Trusted, we create a member profile
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: These Terms permit you to use Trusted for your personal, non-commercial use only.
  - summary: Lawful purposes only
    text: You represent and warrant that you will use Trusted solely for lawful purposes in a manner consistent with these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you choose, or are provided with, a username, password, or any other piece of information as part of our security procedures
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trusted Health
provenance_date: '2026-11-10'
provider_name: Trusted Health
provider_slug: trusted-health
slug: trusted-health-eligibility
source_date: '2026-11-10'
source_filename: trusted-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.trustedhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trusted Health\naid: trusted-health\nurl: https://www.trustedhealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you reside in the United States, subject to the Exceptions to Arbitration set forth below, you and Trusted\n    each agree that any and all disputes between consumer users of Trusted and the Trusted Group\nentity_types:\n- type: individual\n  text: When you set up an individual user account on Trusted, we create a member profile\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: These Terms permit you to use Trusted for your\
  \ personal, non-commercial use only.\n- summary: Lawful purposes only\n  text: You represent and warrant that you will use Trusted solely for lawful purposes in a manner consistent with\n    these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you choose, or are provided with, a username, password, or any other piece of information as part of\n    our security procedures\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trusted-health/eligibility/trusted-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Trusted Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Healthcare
- Nursing
- Staffing
- Travel Nursing
- Allied Health
- Workforce
---
