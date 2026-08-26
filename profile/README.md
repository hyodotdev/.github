# [hyo.dev](https://www.hyo.dev)

An open source studio in Seoul, building standards, libraries, and products for developers.

**→ [www.hyo.dev](https://www.hyo.dev)**

## OpenIAP — one API for every store

[openiap.dev](https://www.openiap.dev) · [spec & source](https://github.com/hyodotdev/openiap)

In-app purchases are critical infrastructure, but every store ships its own API,
types, and events. OpenIAP is one type-safe purchase contract that spans all of
them, so product logic is written once.

**Stores covered**

| Store | Platform |
| --- | --- |
| App Store | iOS · macOS · visionOS |
| Google Play | Android |
| Amazon Appstore | Fire OS |
| Meta Horizon | Horizon OS |
| Vega OS | Fire TV |

**Native core** — [openiap-apple](https://github.com/hyodotdev/openiap/tree/main/packages/apple) (StoreKit 2) · [openiap-google](https://github.com/hyodotdev/openiap/tree/main/packages/google) (Play Billing)

**Framework SDKs** — [expo-iap](https://github.com/hyodotdev/openiap/tree/main/libraries/expo-iap) · [react-native-iap](https://github.com/hyodotdev/openiap/tree/main/libraries/react-native-iap) · [flutter_inapp_purchase](https://github.com/hyodotdev/openiap/tree/main/libraries/flutter_inapp_purchase) · [kmp-iap](https://github.com/hyodotdev/openiap/tree/main/libraries/kmp-iap) · [maui-iap](https://github.com/hyodotdev/openiap/tree/main/libraries/maui-iap) · [godot-iap](https://github.com/hyodotdev/openiap/tree/main/libraries/godot-iap)

## IAPKit — the OpenIAP purchase backend

[kit.openiap.dev](https://kit.openiap.dev)

Purchase validation and entitlement infrastructure for the OpenIAP ecosystem —
open source, with a hosted dashboard.

- **Purchase verification** — server-side receipt validation for every store
- **Entitlements** — subscription state tracked from store lifecycle events
- **MCP operations** — your coding agent creates and syncs store products
- **Revenue visibility** — MRR, churn, and refunds from connected notifications

## Backed by

OpenIAP is sponsored by **Meta** and **Amazon Developer**, funding the
maintenance, testing, and shared infrastructure behind one purchase contract for
every store.

If your company relies on OpenIAP in production, consider supporting its
long-term development:

**→ [github.com/sponsors/hyodotdev](https://github.com/sponsors/hyodotdev)** · [sponsorship options](https://www.openiap.dev/sponsors)

---

[www.hyo.dev](https://www.hyo.dev) · [hyo@hyo.dev](mailto:hyo@hyo.dev) · Seoul, South Korea
