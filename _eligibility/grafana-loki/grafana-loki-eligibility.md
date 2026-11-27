---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: any country subject to U.S. trade sanctions (Supplement No. 1 to Part 740, Export Administration Regulations, Country Group E:1)
  entity_types:
  - text: you are of sufficient legal age and legal capacity to legally agree to these Terms
    type: individual
  - text: If you are using the Service for a corporation, organization or entity, you represent and warrant that you (1) you have read and understand these Terms, (2) have full legal authority to agree to these Terms on behalf of the applicable entity
    type: business
  minimum_age:
    text: you are of sufficient legal age and legal capacity to legally agree to these Terms
    value: null
  restricted_uses:
  - summary: Professional use only, not consumer
    text: Only use our services, website and content for professional use only, and not for consumer purposes.
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
name: Grafana Loki
provenance_date: '2026-11-09'
provider_name: Grafana Loki
provider_slug: grafana-loki
slug: grafana-loki-eligibility
source_date: '2026-11-09'
source_filename: grafana-loki-eligibility.yml
source_heading: Eligibility
source_page: https://grafana.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grafana Loki\naid: grafana-loki\nurl: https://grafana.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: any country subject to U.S. trade sanctions (Supplement No. 1 to Part 740, Export Administration Regulations,\n    Country Group E:1)\nentity_types:\n- type: individual\n  text: you are of sufficient legal age and legal capacity to legally agree to these Terms\n- type: business\n  text: If you are using the Service for a corporation, organization or entity, you represent and warrant that you\n    (1) you have read and understand these Terms, (2) have full legal authority\
  \ to agree to these Terms on behalf\n    of the applicable entity\nrestricted_uses:\n- summary: Professional use only, not consumer\n  text: Only use our services, website and content for professional use only, and not for consumer purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of sufficient legal age and legal capacity to legally agree to these Terms\n"
source_yaml_url: https://artifacts.apis.io/grafana-loki/eligibility/grafana-loki-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Grafana Loki's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logs
- Logging
- Log Aggregation
- Observability
- Monitoring
- Open Source
- LogQL
- OpenTelemetry
- Telemetry
- Kubernetes
- Cloud-Native
---
