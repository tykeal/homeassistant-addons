<!--
SPDX-FileCopyrightText: 2026 Andrew Grimberg <tykeal@bardicgrove.org>
SPDX-License-Identifier: Apache-2.0
-->

# Home Assistant Add-ons by tykeal

A collection of Home Assistant add-ons for property management and guest
network automation.

## Installation

1. Open your Home Assistant instance
2. Navigate to **Settings → Add-ons → Add-on Store**
3. Click the **⋮** menu (top right) → **Repositories**
4. Add this repository URL:

   ```
   https://github.com/tykeal/homeassistant-addons
   ```

5. Click **Add**, then refresh the page
6. The add-ons listed below will appear in the store

## Add-ons

### [RentalSync Bridge][rentalsync]

Multi-PMS booking sync and iCal export bridge. Syncs booking data from
property management systems (Cloudbeds, Guesty) and exports RFC 5545
compliant iCal feeds with room-level granularity. Includes a web-based
admin interface and automatic background sync.

### [Captive Portal][captive-portal]

Guest Wi-Fi captive portal integrated with TP-Link Omada controllers.
Supports voucher-based and booking-based authentication (via Rental
Control), role-based admin access, comprehensive audit logging, and
resilient controller communication.

## License

Apache-2.0 — See [LICENSE](LICENSE) for details.

[rentalsync]: https://github.com/tykeal/homeassistant-rentalsync-bridge
[captive-portal]: https://github.com/tykeal/homeassistant-captive-portal
