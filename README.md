# PLP Cloud

Phone LCD Parts ERP System — Arabic RTL / English-ready static PWA frontend.

## Structure

- `index.html` — main application
- `manifest.webmanifest` — installable PWA metadata
- `favicon-*.png` / `apple-touch-icon.png` — PLP branding

## Backend

This frontend is connected to the PLP Supabase project using the public publishable key. Authorization remains enforced by Supabase Auth + RLS + database permissions.

Project URL:
`https://vgstkvshalbywbposzzl.supabase.co`

> Never replace the publishable key with a service-role/secret key.

## GitHub

Upload the contents of this folder to the root of your `PLP-Cloud` repository.

The same packaging approach is intentionally close to the TN Auto reference: a simple static PWA that can be hosted directly from GitHub Pages or another static host.

## Notes

The backend contains the full ERP accounting, inventory, sales, purchasing/import, treasury, customer/supplier, employee/payroll, fixed asset, partner and control-center engines. This frontend provides the PLP shell and live read/report connections to those secured RPCs.
