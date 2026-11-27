---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian to agree to these Terms on your behalf).
    value: null
  restricted_uses:
  - summary: Not for emergencies or medical advice
    text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.
  - summary: Not a medical device
    text: The Services, Content and our Products are not medical devices and are not intended to be used as medical devices.
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
name: Osmind
provenance_date: '2026-11-10'
provider_name: Osmind
provider_slug: osmind
slug: osmind-eligibility
source_date: '2026-11-10'
source_filename: osmind-eligibility.yml
source_heading: Eligibility
source_page: https://www.osmind.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Osmind\naid: osmind\nurl: https://www.osmind.org/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n- type: business\n  text: If you’re agreeing to these\
  \ Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Not for emergencies or medical advice\n  text: THE SERVICES SHOULD NEVER BE USED AS A SUBSTITUTE FOR EMERGENCY CARE.\n- summary: Not a medical device\n  text: The Services, Content and our Products are not medical devices and are not intended to be used as medical\n    devices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services and have gotten your parent or guardian\n    to agree to these Terms on your behalf).\n"
source_yaml_url: https://artifacts.apis.io/osmind/eligibility/osmind-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Osmind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Psychiatry
- Electronic Health Records
- Behavioral Health
- Digital Health
- Health Tech
---
