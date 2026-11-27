---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for an organization, you must have authority to do so.
    type: business
  minimum_age:
    text: This beta is for people who are at least 19 years old and have reached the age of majority where they live.
    value: '19'
  restricted_uses:
  - summary: Unlawful, abusive or harmful use
    text: Do not use Brightmoot for unlawful activity, harassment, impersonation, spam, malware, credential theft, deliberate prompt injection intended to cause harm, unauthorized access, infringement, or attempts to bypass access controls or overload the service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Closure and deletion are handled manually during beta after proportionate identity verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BrightMoot
provenance_date: '2026-11-09'
provider_name: BrightMoot
provider_slug: brightmoot-com
slug: brightmoot-com-eligibility
source_date: '2026-11-09'
source_filename: brightmoot-com-eligibility.yml
source_heading: Eligibility
source_page: https://brightmoot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrightMoot\naid: brightmoot-com\nurl: https://brightmoot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for an organization, you must have authority to do so.\nrestricted_uses:\n- summary: Unlawful, abusive or harmful use\n  text: Do not use Brightmoot for unlawful activity, harassment, impersonation, spam, malware, credential theft,\n    deliberate prompt injection intended to cause harm, unauthorized access, infringement, or attempts to bypass\n    access controls or overload the service.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Closure and deletion are handled manually during beta after proportionate identity verification.\nminimum_age:\n  value: '19'\n  text: This beta is for people who are at least 19 years old and have reached the age of majority where they live.\n"
source_yaml_url: https://artifacts.apis.io/brightmoot-com/eligibility/brightmoot-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BrightMoot's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Community
- Platform
- Multiplayer
---
