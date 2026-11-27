---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not represent or warrant that the Site is appropriate or available for use in any particular jurisdiction other than the United States.
  entity_types:
  - text: If you do not accept these Terms, and/or if you are not of legal age to form a binding contract with Every.org, you may not use the Sites or the Services.
    type: individual
  - text: 'For U.S.-based organizations, in order to receive Disbursements from us via the Site, you will need to meet the following minimum requirements:'
    type: nonprofit
  minimum_age:
    text: if you are not of legal age to form a binding contract with Every.org, you may not use the Sites or the Services.
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: Our Site is meant solely for personal, non-commercial use.
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
name: Every.org
provenance_date: '2026-11-09'
provider_name: Every.org
provider_slug: every-org
slug: every-org-eligibility
source_date: '2026-11-09'
source_filename: every-org-eligibility.yml
source_heading: Eligibility
source_page: https://www.every.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Every.org\naid: every-org\nurl: https://www.every.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not represent or warrant that the Site is appropriate or available for use in any particular jurisdiction\n    other than the United States.\nentity_types:\n- type: individual\n  text: If you do not accept these Terms, and/or if you are not of legal age to form a binding contract with Every.org,\n    you may not use the Sites or the Services.\n- type: nonprofit\n  text: 'For U.S.-based organizations, in order to receive Disbursements from us via the Site, you will need\
  \ to\n    meet the following minimum requirements:'\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: Our Site is meant solely for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are not of legal age to form a binding contract with Every.org, you may not use the Sites or the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/every-org/eligibility/every-org-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Every.org's own page on 2026-11-09.
synthetic: false
tags:
- Charities
- Donations
- Fundraising
- Non-Profit
- Philanthropy
- Webhook
- Giving
---
