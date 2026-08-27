# Devadex Fairgrounds OS

An offline operations system for agricultural fairgrounds: exhibitor records, livestock classes and the premium book, the junior auction, vendor booths and the ground map, gate ticketing, and the off-season rental calendar.

## What it does

- **Exhibitor records.** One record per exhibitor, covering name, club or family affiliation, email, and phone, with a flag for junior exhibitor status.
- **Livestock classes and the premium book.** Departments (broad categories) and classes (specific competitions within a department).
- **Junior auction.** Sales, each with a name, date, and commission rate applied to hammer price.
- **Vendor booths and ground map.** Booths defined with a short code, zone name, X/Y grid position, size, and daily rate; each booth renders as a block on a ground map.
- **Gate ticketing.** Ticket types with a price (e.g. adult single-day, child single-day, season pass).
- **Off-season rental calendar.** Facilities (arena, hall, RV lot, etc.) defined with a daily rate and optional capacity.
- **Data access and API.** Every dashboard action is backed by a JSON API under /api/... on the same server; the API is usable directly (examples given in USAGE.md using curl), independent of the dashboard.
- **Dashboard.** Browser-based dashboard served by the built-in web server, with six tabs: Exhibitors, Livestock & Premium Book, Junior Auction, Vendor Booths & Map, Gate Ticketing, and Rental Calendar.

## Who it is for

A county or state fair board running the show on paper, and anyone maintaining a fairground the rest of the year.

---

Available for acquisition as an outright transfer of ownership.

This repository is **documentation only**. It describes what the product is, what has been
measured, and what is known to be incomplete. It contains no source code. See
[LICENSING.md](LICENSING.md).

---

## What is included

One finished product.

| Product | Scale |
|---|---|
| Devadex Fairgrounds OS | 33 tests |

Feature-by-feature detail is in [PRODUCTS.md](PRODUCTS.md).

## Measured

| Measure | Value |
|---|---|
| Tests passing | 33 |
| Tests failing | 0 |
| Tests skipped | 0 |
| Files delivered | 32 |
| Authored lines | 2,463 |

Every figure came from running the software while the data room was prepared, and a buyer can
reproduce each one from the delivered files. Method and known gaps are in
[VERIFICATION.md](VERIFICATION.md).

## How it is sold

Outright transfer of ownership, sold as is. No ongoing maintenance or support obligation, and no
licence-back, so the seller keeps nothing that depends on it.

A full data room is available under a signed non-disclosure agreement: product inventory,
provenance, third-party notices, the complete verification record, and an open-items document
listing every known gap. See [ACQUISITION.md](ACQUISITION.md).

## Documents

| Document | What is in it |
|---|---|
| [PRODUCTS.md](PRODUCTS.md) | Every product, described |
| [VERIFICATION.md](VERIFICATION.md) | What was measured, how, and what is not proven |
| [LICENSING.md](LICENSING.md) | Proprietary status, and what this repository is |
| [ACQUISITION.md](ACQUISITION.md) | How to open a conversation |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Why code contributions are not taken |

---

Jesse Duncan, doing business as Devadex Labs. Proprietary; all rights reserved.
