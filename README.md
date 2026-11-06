# Veda Bharath · User Management

A separate, buildless dashboard based on the supplied design-system document, logo, screen recording and live Super Admin pages. Uses the original Figtree font and Veda Bharath logo. No dependencies or build step.

Run locally: `python3 -m http.server 4173 --directory dist`.

Includes overview summaries, customer directory, warehouse network, administrator management, search, status/location filters, sorting, pagination, CSV export, detail/edit/create dialogs, activity history and browser-local persistence. Sample records do not update the original Veda Bharath application. Creating an administrator does not send an invitation or provision access.

Local changes use the `veda-people-v1` localStorage key. No real customer information or credentials are embedded. Native dialogs handle modal focus and Escape; layouts support small screens and reduced motion.
