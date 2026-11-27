---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Valeo App, you confirm that you are of at least 18 years of age, or such other age of majority as per the laws of the jurisdiction applicable to you.
    value: '18'
  restricted_uses:
  - summary: No impersonation or inaccurate information
    text: You can’t impersonate others or provide inaccurate information.
  - summary: No political, racist or similar comments
    text: You can’t raise or comment or write review on any political, racist or such other issue which effect’s a person, community or society.
  - summary: No account trading or credential harvesting
    text: You can’t attempt to buy, sell, or transfer any aspect of your account (including your username) or solicit, collect, or use login credentials of other users.
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
name: Valeo
provenance_date: '2026-11-09'
provider_name: Valeo
provider_slug: feelvaleo-com
slug: feelvaleo-com-eligibility
source_date: '2026-11-09'
source_filename: feelvaleo-com-eligibility.yml
source_heading: Eligibility
source_page: https://feelvaleo.com/en-ae/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valeo\naid: feelvaleo-com\nurl: https://feelvaleo.com/en-ae/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No impersonation or inaccurate information\n  text: You can’t impersonate others or provide inaccurate information.\n- summary: No political, racist or similar comments\n  text: You can’t raise or comment or write review on any political, racist or such other issue which effect’s a\n    person, community or society.\n- summary: No account trading or credential harvesting\n  text: You\
  \ can’t attempt to buy, sell, or transfer any aspect of your account (including your username) or solicit,\n    collect, or use login credentials of other users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Valeo App, you confirm that you are of at least 18 years of age, or such other age of majority\n    as per the laws of the jurisdiction applicable to you.\n"
source_yaml_url: https://artifacts.apis.io/feelvaleo-com/eligibility/feelvaleo-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Valeo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Home Care
- Lab Testing
- United Arab Emirates
- Saudi Arabia
- Qatar
- Kuwait
---
