---
api_specs:
- filename: crispy-sh-openapi-generated.yml
  format: yaml
  label: crispy-sh API
  slug: crispy-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crispy-sh/openapi/_ae-authored/crispy-sh-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Crispy for an organization, you represent that you can bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter this agreement.
    value: '18'
  restricted_uses:
  - summary: Unlawful spam or unlawfully obtained contact data
    text: send unlawful spam or outreach or process unlawfully obtained contact data
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
name: crispy-sh
provenance_date: '2026-11-09'
provider_name: crispy-sh
provider_slug: crispy-sh
slug: crispy-sh-eligibility
source_date: '2026-11-09'
source_filename: crispy-sh-eligibility.yml
source_heading: Eligibility
source_page: https://crispy.sh/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crispy-sh\naid: crispy-sh\nurl: https://crispy.sh/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Crispy for an organization, you represent that you can bind that organization.\nrestricted_uses:\n- summary: Unlawful spam or unlawfully obtained contact data\n  text: send unlawful spam or outreach or process unlawfully obtained contact data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/crispy-sh/eligibility/crispy-sh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from crispy-sh's own page on 2026-11-09.
synthetic: false
tags:
- LinkedIn
- Founders
- Outreach
- Automation
- Software-as-a-Service
---
