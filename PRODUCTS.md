# Devadex Fairgrounds OS

The product in this package.

Every entry below is taken from the package's own documentation. Nothing here is a plan or a
roadmap item; all of it is built.

---

## Devadex Fairgrounds OS

33 tests

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

### Who it is for

A county or state fair board running the show on paper, and anyone maintaining a fairground the rest of the year.

---

Full detail, including file-level inventory and provenance, is in the data room, available under a
signed non-disclosure agreement. See [ACQUISITION.md](ACQUISITION.md).
