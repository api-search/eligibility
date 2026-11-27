---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting this Agreement is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful content
    text: use the Services in an unlawful manner, or otherwise to publish or disseminate any material that is defamatory, pornographic, depicts acts of violence
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
name: Sitemate
provenance_date: '2026-11-10'
provider_name: Sitemate
provider_slug: sitemate
slug: sitemate-eligibility
source_date: '2026-11-10'
source_filename: sitemate-eligibility.yml
source_heading: Eligibility
source_page: https://sitemate.com/resources/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sitemate\naid: sitemate\nurl: https://sitemate.com/resources/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: use the Services in an unlawful manner, or otherwise to publish or disseminate any material that is defamatory,\n    pornographic, depicts acts of violence\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sitemate/eligibility/sitemate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sitemate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Construction
- FieldTech
- Automation
- Data Capture
---
