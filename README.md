# Commons Cloud Fabric

Algonquin's institution-owned cloud control plane, based on the neutral
Post-Secondary Digital Commons cloud repository. Commons Cloud Fabric
provides normalized identity, service discovery, policy distribution, storage,
messaging, secrets integration, observability, and cross-system events. It does
not own AI, compute, media, or social-domain behavior.

## Ecosystem dependencies

Commons Cloud Fabric is the foundation dependency for shared identity, policy, events,
secrets, storage, service discovery, and observability. It must not import domain
logic from the product systems. Product integrations cross versioned contracts
and continue in a documented degraded mode when optional adapters are absent.

- [Consolidated ecosystem architecture](../algonquin-architecture/docs/architecture/Consolidated-Ecosystem-Architecture.md)
- [Dependency contract](../algonquin-architecture/docs/architecture/Ecosystem-Dependency-Contract.md)
- [Open-source-only policy](../algonquin-architecture/docs/vision/11-Open-Source-Only-Policy.md)
- [Human choices register](../algonquin-architecture/docs/governance/Human-Choices-and-Decisions-Register.md)
- [Full technology stack](../algonquin-architecture/docs/vision/14-Full-Technology-Stack-and-Open-Source-Alternatives.md)
- [Commons architecture](../algonquin-architecture/docs/vision/constitutional/Post-Secondary-Digital-Commons-Architecture.md)

## Layout

- `services/` — shared APIs and control-plane services
- `platform/` — infrastructure abstractions and operational dependencies
- `connectors/` — explicit integrations with the other ecosystems
- `apps/` — operator and developer portals
- `infrastructure/` — local and future production deployment assets
