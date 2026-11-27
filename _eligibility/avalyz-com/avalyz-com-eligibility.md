---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer residing in the European Union, Directive 2011/83/EU (article 16(m)) provides that the 14-day right of withdrawal expires for digital content not supplied on a tangible medium once performance has begun with your prior express consent and your acknowledgement that you thereby lose that right.
    type: individual
  - text: If you act as a professional, you indemnify Framework SARL AU against any claim, penalty, judgment and all reasonable costs (including defence costs) arising from a test you ran without authorization, an inaccurate attestation or a breach of the Acceptable use policy.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Load, offensive or sensitive-domain tests without proof
    text: run a load test, an offensive security probe or a write-mode test on a sensitive domain without technical proof
  - summary: Real personal data in forms
    text: No real personal data of third parties in forms; Avalyz uses fictitious data prefixed "avalyz-test".
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Technical proof of control of the domain (tag, file or DNS) is still required for load tests, offensive security probes and sensitive domains (government, police, armed forces, justice, banking and payments, health, energy and infrastructure).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Avalyz
provenance_date: '2026-11-09'
provider_name: Avalyz
provider_slug: avalyz-com
slug: avalyz-com-eligibility
source_date: '2026-11-09'
source_filename: avalyz-com-eligibility.yml
source_heading: Eligibility
source_page: https://avalyz.com/av/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avalyz\naid: avalyz-com\nurl: https://avalyz.com/av/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer residing in the European Union, Directive 2011/83/EU (article 16(m)) provides that\n    the 14-day right of withdrawal expires for digital content not supplied on a tangible medium once performance\n    has begun with your prior express consent and your acknowledgement that you thereby lose that right.\n- type: business\n  text: If you act as a professional, you indemnify Framework SARL AU against any claim,\
  \ penalty, judgment and all\n    reasonable costs (including defence costs) arising from a test you ran without authorization, an inaccurate\n    attestation or a breach of the Acceptable use policy.\nrestricted_uses:\n- summary: Load, offensive or sensitive-domain tests without proof\n  text: run a load test, an offensive security probe or a write-mode test on a sensitive domain without technical\n    proof\n- summary: Real personal data in forms\n  text: No real personal data of third parties in forms; Avalyz uses fictitious data prefixed \"avalyz-test\".\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Technical proof of control of the domain (tag, file or DNS) is still required for load tests, offensive\n    security probes and sensitive domains (government, police, armed forces, justice, banking and payments, health,\n    energy and infrastructure).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avalyz-com/eligibility/avalyz-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Avalyz's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Testing
- Web App
- Software-as-a-Service
- Automation
---
