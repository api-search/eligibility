---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: we make no representations that the Service is appropriate or available in any particular location.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) and capable of entering into a binding contract to use the Service.
    type: individual
  - text: If you are using Raid AI on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Use the Service in any way that violates any applicable law or regulation.
  - summary: Unauthorized content
    text: Upload or submit any content that you do not have the right to use or that infringes on any third-party intellectual property or privacy rights.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to create an account to use certain features of our Service. You agree to provide accurate and current information when registering.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Raid AI
provenance_date: '2026-11-10'
provider_name: Raid AI
provider_slug: raid-ai
slug: raid-ai-eligibility
source_date: '2026-11-10'
source_filename: raid-ai-eligibility.yml
source_heading: Eligibility
source_page: https://raidxai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raid AI\naid: raid-ai\nurl: https://raidxai.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: we make no representations that the Service is appropriate or available in any particular location.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) and capable of entering\n    into a binding contract to use the Service.\n- type: business\n  text: If you are using Raid AI on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n\
  - summary: Unlawful use\n  text: Use the Service in any way that violates any applicable law or regulation.\n- summary: Unauthorized content\n  text: Upload or submit any content that you do not have the right to use or that infringes on any third-party\n    intellectual property or privacy rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to create an account to use certain features of our Service. You agree to provide accurate\n    and current information when registering.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/raid-ai/eligibility/raid-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Raid AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Deepfake Detection
- AI Content Detection
- Media Forensics
- Voice / Audio Detection
- Image Forensics
- Document Forensics
- Fact Checking
- Trust and Safety
- Security
---
