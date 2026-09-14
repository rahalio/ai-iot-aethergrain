# AetherGrain — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Platform security lead

- As a security lead, I want transmitters authenticated without provisioning NVM keys, so stolen flash does not yield credentials.
- As a security lead, I want fail-closed on grain mismatch, so clones cannot join by replaying app tokens alone.
- As a security lead, I want RF-PUF as a factor beside certificate auth, so physical and logical identity both gate access.

### RF engineer

- As an RF engineer, I want enrollment across multiple channel conditions, so mobility does not destroy accuracy.
- As an RF engineer, I want receiver-compensation status per hub, so swapping radios does not invalidate the fleet.

### SOC analyst

- As a SOC analyst, I want impersonation alerts with device and hub IDs, so I can isolate a star-topology branch quickly.
- As a SOC analyst, I want forensic packs of auth decisions, so incidents do not require raw RF captures.

### Identity administrator

- As an identity admin, I want attested enrollment and revocation of RF templates, so lost sensors are cryptographically forgotten at the hub.
- As an identity admin, I want encrypted template migration to a replacement hub, so building refits do not re-touch every endpoint.

### Compliance officer

- As a compliance officer, I want evidence that endpoint secrets are not stored for RF-PUF mode, so audits reflect the product claim.
- As a compliance officer, I want retention limits on RF feature templates, so device biometrics are not kept forever.
