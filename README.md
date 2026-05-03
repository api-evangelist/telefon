# Telefon

Telefon is a cloud-based programmable communications platform providing voice, SMS, number management, and call recording APIs for developers and enterprises. The platform covers 180+ countries with competitive per-minute and per-message pricing and AI-powered transcription.

**Human URL:** [https://www.telefon.com](https://www.telefon.com)
**Developer URL:** [https://developers.telefon.com](https://developers.telefon.com)

## APIs

### Telefon Voice API
Programmable voice for calls, conferencing, IVR, SIP trunking, and WebRTC.
- **OpenAPI Spec:** [openapi/telefon-voice-openapi.yml](openapi/telefon-voice-openapi.yml)

### Telefon SMS API
Global A2P SMS and MMS with delivery receipts and two-way messaging.
- **OpenAPI Spec:** [openapi/telefon-sms-openapi.yml](openapi/telefon-sms-openapi.yml)

### Telefon Number Management API
Phone number provisioning across 70+ countries — local, mobile, toll-free, short codes.
- **OpenAPI Spec:** [openapi/telefon-numbers-openapi.yml](openapi/telefon-numbers-openapi.yml)

### Telefon Call Recording API
Dual-channel recording with AI transcription in 30+ languages and PII redaction.
- **OpenAPI Spec:** [openapi/telefon-recording-openapi.yml](openapi/telefon-recording-openapi.yml)

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/telefon-voice-openapi.yml](openapi/telefon-voice-openapi.yml) | Voice API — calls and conferencing |
| [openapi/telefon-sms-openapi.yml](openapi/telefon-sms-openapi.yml) | SMS API — send/receive messages |
| [openapi/telefon-numbers-openapi.yml](openapi/telefon-numbers-openapi.yml) | Number Management API |
| [openapi/telefon-recording-openapi.yml](openapi/telefon-recording-openapi.yml) | Recording API with transcription |

### JSON Schemas
| File | Description |
|---|---|
| [json-schema/telefon-call-schema.json](json-schema/telefon-call-schema.json) | Call object JSON Schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/telefon-call-structure.json](json-structure/telefon-call-structure.json) | Call object field structure |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/telefon-context.jsonld](json-ld/telefon-context.jsonld) | JSON-LD context for Telefon data types |

### Examples
| File | Description |
|---|---|
| [examples/telefon-create-call-example.json](examples/telefon-create-call-example.json) | Create a voice call |
| [examples/telefon-send-sms-example.json](examples/telefon-send-sms-example.json) | Send an SMS message |

### Spectral Rules
| File | Description |
|---|---|
| [rules/telefon-rules.yml](rules/telefon-rules.yml) | Spectral ruleset for Telefon API conventions |

### Naftiko Capabilities
| File | Description |
|---|---|
| [capabilities/shared/telefon-voice.yaml](capabilities/shared/telefon-voice.yaml) | Shared Voice API capability |
| [capabilities/shared/telefon-sms.yaml](capabilities/shared/telefon-sms.yaml) | Shared SMS API capability |
| [capabilities/telephony-platform.yaml](capabilities/telephony-platform.yaml) | Communications platform workflow (REST port 8080, MCP port 9090) |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/telefon-vocabulary.yml](vocabulary/telefon-vocabulary.yml) | Telefon platform vocabulary |

## Common Properties

| Property | URL |
|---|---|
| Getting Started | https://developers.telefon.com/getting-started |
| Authentication | https://developers.telefon.com/authentication |
| SDKs | https://www.telefon.com/sdks |
| Status | https://status.telefon.com |
| Terms of Service | https://www.telefon.com/terms |
| Pricing | https://www.telefon.com/pricing |

## Maintainers
- **Telefon API Team** — api@telefon.com
