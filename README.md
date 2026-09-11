# Commons Cloud Fabric

Shared platform control plane for the tenant-neutral Post-Secondary Digital
Commons. Commons Cloud Fabric
provides normalized identity, service discovery, policy distribution, storage,
messaging, secrets integration, observability, and cross-system events. It does
not own AI, compute, media, or social-domain behavior.

## Ecosystem dependencies

Commons Cloud Fabric is the foundation dependency for shared identity, policy, events,
secrets, storage, service discovery, and observability. It must not import domain
logic from the product systems. Product integrations cross versioned contracts
and continue in a documented degraded mode when optional adapters are absent.

- [Consolidated ecosystem architecture](../psdc-architecture/docs/architecture/Consolidated-Ecosystem-Architecture.md)
- [Dependency contract](../psdc-architecture/docs/architecture/Ecosystem-Dependency-Contract.md)
- [Open-source-only policy](../psdc-architecture/docs/vision/11-Open-Source-Only-Policy.md)
- [Human choices register](../psdc-architecture/docs/governance/Human-Choices-and-Decisions-Register.md)
- [Full technology stack](../psdc-architecture/docs/vision/14-Full-Technology-Stack-and-Open-Source-Alternatives.md)
- [Commons architecture](../psdc-architecture/docs/vision/constitutional/Post-Secondary-Digital-Commons-Architecture.md)

## Layout

- `services/` — shared APIs and control-plane services
- `platform/` — infrastructure abstractions and operational dependencies
- `connectors/` — explicit integrations with the other ecosystems
- `apps/` — operator and developer portals
- `infrastructure/` — local and future production deployment assets
