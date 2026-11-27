# Pasumai Revive

The standalone deliverable is [`public/Pasumai Revive.html`](public/Pasumai%20Revive.html). Open it in a modern browser, or use Figma Make’s preview and select **Download HTML** in the public footer. The truck concept image, original Tamil wordmark, icons and Chart.js are embedded. Inter and Noto Sans Tamil load when available; the rest of the page uses system fallbacks offline.

## Demo access

Select **Login / Register**, choose a role and use **Quick demo access**, or enter the public demo credentials:

| Role           | Login                    | Password / PIN |
| -------------- | ------------------------ | -------------- |
| Shopkeeper     | `SHP-01`                 | `1234`         |
| Field operator | `OP-MRU01`               | `2026`         |
| Administrator  | `admin@pasumairevive.in` | `admin123`     |

The administrator email above is a **demo login identifier**, not a contact address.

### Try a connected workflow

1. As the **shopkeeper**, request an extra pickup for today and submit a test issue. Sign out from the profile menu.
2. As the **administrator**, open **Dispatch** and assign the request to the demo operator. Mark it urgent to move it to the top of the route. Resolve the issue in **Complaints** with a short shop-facing note.
3. As the **operator**, use **Scan QR → Use next assigned pod**, or select the specific stop in the route. Enter a weight and grade, complete the collection and open its receipt. Select that collection when creating a **Pre-processing** batch, then record a confirmed **Facility handoff**.
4. Sign back in as the **shopkeeper** to check the receipt, credits and resolved issue. As **administrator**, check the incoming batch and updated analytics, then export an admin report.
5. To test onboarding, submit a sample registration from the home page, approve it in **Vegetable shops**, and sign in using the new shop ID with the public demo PIN. The admin profile menu can reset all demo data.

## Prototype boundaries

- Records and demo sessions are stored in the current browser, not shared across devices. Use sample details only. Private browsing and some local-file browser policies can limit persistence.
- These roles demonstrate the user experience; they are not a security boundary. Production requires server-side authentication, authorization, a database, and audited workflows.
- QR and scale interactions are simulated. The route is a sequence, not GPS tracking. Enquiries and WhatsApp previews do not send messages. There is no payment processing, voucher fulfilment, or verified facility connection.
- Recovery KPIs are seeded or entered demo records. Simulator results are estimates. The study’s 10–18 kg/day range describes one surveyed shop and is not a service-area average.
- The vehicle is for collection and preliminary processing. Compost matures at a separate facility and release requires quality validation. ReviveAzolla is a separate experimental log.
