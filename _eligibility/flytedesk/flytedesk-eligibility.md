---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual acting on behalf of a school, company, or other entity, you represent that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing ad services excluded
    text: Advertiser acknowledges that the Advertising Service is not available to entities that run, provide, enable or promote similar advertising services, whether for themselves or for others.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Advertiser may be required to submit a credit application in order to be considered for other payment arrangements with Flytedesk.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FlyteDesk
provenance_date: '2026-11-09'
provider_name: FlyteDesk
provider_slug: flytedesk
slug: flytedesk-eligibility
source_date: '2026-11-09'
source_filename: flytedesk-eligibility.yml
source_heading: Eligibility
source_page: https://www.flytedesk.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlyteDesk\naid: flytedesk\nurl: https://www.flytedesk.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are an individual acting on behalf of a school, company, or other entity, you represent that you\n    have the authority to bind that entity\nrestricted_uses:\n- summary: Competing ad services excluded\n  text: Advertiser acknowledges that the Advertising Service is not available to entities that run, provide, enable\n    or promote similar advertising services, whether for themselves\
  \ or for others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Advertiser may be required to submit a credit application in order to be considered for other payment arrangements\n    with Flytedesk.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flytedesk/eligibility/flytedesk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from FlyteDesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Media
- Campus Media
- College Advertising
- Marketing
- AdTech
- GraphQL
- Media Buying
- Higher Education
---
