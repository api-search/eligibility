---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A “Member” is an individual that has registered with us to use our Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Listing of offered products on the Website could be used only for lawful purposes by Users of the Website.
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
name: Defense Unicorns
provenance_date: '2026-11-09'
provider_name: Defense Unicorns
provider_slug: defense-unicorns
slug: defense-unicorns-eligibility
source_date: '2026-11-09'
source_filename: defense-unicorns-eligibility.yml
source_heading: Eligibility
source_page: https://defenseunicorns.com/legal/site-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Defense Unicorns\naid: defense-unicorns\nurl: https://defenseunicorns.com/legal/site-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A “Member” is an individual that has registered with us to use our Service.\nrestricted_uses:\n- summary: Lawful use only\n  text: Listing of offered products on the Website could be used only for lawful purposes by Users of the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/defense-unicorns/eligibility/defense-unicorns-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Defense Unicorns's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- DevSecOps
- Kubernetes
- Defense
- Software Delivery
- Compliance
- Open Source
- Air Gap
---
