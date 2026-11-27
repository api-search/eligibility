---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: By using the Platform, you represent and warrant that you meet these eligibility requirements and that you are located in the United States or Canada.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Platform, unless you are a minor using the Platform with the informed consent of a parent or legal guardian.
    type: individual
  - text: A kit may be registered by you directly, or by an authorized party such as a healthcare provider or clinic acting on your behalf.
    type: other
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Platform, unless you are a minor using the Platform with the informed consent of a parent or legal guardian.
    value: '18'
  restricted_uses:
  - summary: No medical advice reliance
    text: Always consult a licensed healthcare provider before making any medical decisions based on your Report or any other content on the Platform.
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
name: Generation Lab
provenance_date: '2026-11-09'
provider_name: Generation Lab
provider_slug: generation-lab
slug: generation-lab-eligibility
source_date: '2026-11-09'
source_filename: generation-lab-eligibility.yml
source_heading: Eligibility
source_page: https://www.generationlab.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Generation Lab\naid: generation-lab\nurl: https://www.generationlab.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: By using the Platform, you represent and warrant that you meet these eligibility requirements and that you\n    are located in the United States or Canada.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Platform, unless\n    you are a minor using the Platform with the informed consent of a parent or legal guardian.\n- type: other\n  text: A kit may\
  \ be registered by you directly, or by an authorized party such as a healthcare provider or clinic\n    acting on your behalf.\nrestricted_uses:\n- summary: No medical advice reliance\n  text: Always consult a licensed healthcare provider before making any medical decisions based on your Report or\n    any other content on the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to use the Platform, unless\n    you are a minor using the Platform with the informed consent of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/generation-lab/eligibility/generation-lab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Generation Lab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Longevity
- Health
- Biotechnology
- Diagnostics
- Aging
- Epigenetics
- Health Tech
---
