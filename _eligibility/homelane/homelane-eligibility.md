---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: the products/services on this Platform are directed solely at those who use/avail the products/services within India.
  entity_types:
  - text: Use of the Platform is available only to persons who can form legally binding contracts under applicable law.
    type: individual
  - text: If you are registering as a business entity, you represent that you have the authority to bind the entity to these Terms.
    type: business
  minimum_age:
    text: If you are a minor i.e. under the age of 18 years but at least 13 years of age you may use this Platform only under the supervision of a parent or legal guardian who agrees to be bound by these Terms of Use.
    value: '18'
  restricted_uses:
  - summary: Use only for permitted purposes
    text: You shall use the Platform and the services provided therein only for purposes that are permitted by (a) the Terms of Use; and (b) any applicable law, regulation, or generally accepted practices or guide in the relevant jurisdictions;
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
name: HomeLane
provenance_date: '2026-11-09'
provider_name: HomeLane
provider_slug: homelane
slug: homelane-eligibility
source_date: '2026-11-09'
source_filename: homelane-eligibility.yml
source_heading: Eligibility
source_page: https://www.homelane.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HomeLane\naid: homelane\nurl: https://www.homelane.com/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: the products/services on this Platform are directed solely at those who use/avail the products/services\n    within India.\nentity_types:\n- type: individual\n  text: Use of the Platform is available only to persons who can form legally binding contracts under applicable\n    law.\n- type: business\n  text: If you are registering as a business entity, you represent that you have the authority to bind the entity\n    to these Terms.\nrestricted_uses:\n- summary: Use\
  \ only for permitted purposes\n  text: You shall use the Platform and the services provided therein only for purposes that are permitted by (a)\n    the Terms of Use; and (b) any applicable law, regulation, or generally accepted practices or guide in the relevant\n    jurisdictions;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are a minor i.e. under the age of 18 years but at least 13 years of age you may use this Platform\n    only under the supervision of a parent or legal guardian who agrees to be bound by these Terms of Use.\n"
source_yaml_url: https://artifacts.apis.io/homelane/eligibility/homelane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HomeLane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Interior Design
- Home Services
- Home Improvement
- Furniture
- Modular Kitchen
- Retail
- India
---
