# Airlift Container Lines — Business Context

Last updated: 2026-04-08
Source: Audio interview with Shreedhar (owner), website

---

## The Business

**Company:** Airlift Container Lines
**Owner:** Shreedhar (Sai's father-in-law)
**Based:** India
**In operation:** 17 years
**Website:** https://www.airliftcontainerlines.com

Two services:
1. **Custom Clearance** — handling all export/import documentation with Indian customs
2. **Freight Forwarding** — coordinating shipments via air (IATA) or sea (NVOCC)

Both go hand in hand. A shipment needs both, and if they're not coordinated, the shipment fails.

---

## How the Business Actually Works

### The Core Process (Export Custom Clearance)

1. Shipper/exporter gets a purchase order from a consignee (e.g. Walmart India buying from an Indian factory)
2. Terms agreed under Incoterms (UCC 800 / world trade agreement)
3. Exporter generates invoice + packing list with: origin, destination, HS code, mode of shipment, payment terms
4. Airlift takes this documentation, uploads it into customs software (**Oinus** — one of 3-4 companies making this software) as a formatted checklist
5. The IEC number (Import Export Code — unique identifier for every exporter) is entered first. This auto-populates most of the exporter's background data in the customs server
6. Airlift adds: consignee details, destination, HS code, quantity, applicable IGST (tax), export promotion benefits (GST refund, ROSCTL, EPCG)
7. Document submitted to customs server (ICEGATE) with digital signature — Airlift is a registered customs house agent (CHA)
8. Customs system verifies → generates **Shipping Bill** (the master ID for all future correspondence on this shipment — banks, revenue dept, export benefits all reference this)
9. Physical shipment arrives at port → customs cross-examines
10. **LEO (Let Export Order)** issued → container cleared to load on vessel/aircraft

### The Freight Forwarding Side

- Takes inquiry from shipper
- Identifies HS code → determines if the cargo has restrictions/special handling
- Places booking with carrier (airline or shipping line) or NVOCC
- Gets competitive rate from carriers
- Has partner networks overseas for pickup/delivery worldwide (mutual — they pick up in India for overseas partners, overseas partners pick up for them)
- Generates quote for client
- Negotiates payment terms

---

## What They're Good At

**The real moat is customs expertise.** 17 years of knowing:
- Which HS code applies to which commodity (150+ chapters, each with its own customs law)
- Which notifications/amendments are currently applicable to a chapter
- How to navigate customs disputes — including negotiating at 2 AM when a vessel is leaving in 90 minutes

**Sectors where they have deep experience:**
- Engineering goods (major strength)
- Textiles & carpets — specifically **Chapter 63** (bed linens, home furnishings) and **Chapter 64**
- Chemicals
- Food items (dehydrated)
- Auto parts (Japan)
- Electrical & electronics
- Leather
- Petroleum coke (full vessel loads)

**Notable past clients / shipments:**
- Walmart (regular shipments — home furnishings, Chapter 63/64)
- IRCC — Indian Railway Construction Corporation (Metro project — transformers from Germany)
- US Military (uniforms + other defense items across locations)
- BARC — Bhabha Atomic Research Centre (specialized magnets from Japan)
- ABB Motors (fertilizer plants — motors exported from Germany)
- NASA (light drones)
- Aircon
- Petrochemical companies (petroleum coke, full vessel shiploads)

**Commodity types handled:**
Engineering goods, textiles, carpets, chemicals, electrical & electronics, leather, food (processed + dehydrated), auto parts, PET films, iron & steel scrap, petroleum coke, specialized industrial components (magnets, transformers, motors), defense items

---

## Key Domain Knowledge (Important for AI)

### HS Codes
Every commodity is classified under a Harmonized System (HS) code. There are 150+ chapters. The HS code determines: customs duty, export benefits, applicable regulations, and documentation requirements. Airlift currently specializes in Chapter 63 (home furnishings/bed linens) and Chapter 64.

### Export Benefits
Exporters are entitled to several government benefits:
- **IGST refund** — input tax credit refund
- **ROSCTL** — export promotion scheme
- **EPCG license** — Export Promotion Capital Goods: allows importing machinery at 5% duty (instead of 35%) in exchange for export obligation (10x the machine value or 5x duty saved)

### Customs Technology Stack
- **ICEGATE** — India's national customs server
- **NIC (National Informatics Centre)** — collects data from every port in India; customs officers can pull any exporter's full shipment history by IEC number in 2 minutes
- **Oinus** — private customs checklist software Airlift uses to format and upload documents
- **RMS (Risk Management System)** — self-declaration system; most shipments pass through automatically; random checks happen

### How Customs Officers Work
- They cross-reference international commodity prices — if you import peanuts from Brazil at $20 but the global price is $40, they flag it
- They track every exporter's history by IEC number across all ports
- They have 48-hour windows to report or release — holding beyond that requires escalation to vigilance
- Experienced officers (especially those promoted to senior customs operations) are highly sophisticated about pricing and classification

---

## Current Business State

**Team:** Strong on customs clearance operations. Weak on marketing/sales.

**Growth:** Flat. Sustaining, not growing. Revenue comes from:
- Repeat clients (existing relationships)
- Referrals from Shreedhar's personal network (friend circle + industry contacts)
- 1-2 overseas network partners (US + other countries) — some have previously "ditched" by bypassing Airlift directly

**Marketing:** Almost none. Shreedhar handles all relationship-driven sales personally. No dedicated marketing function.

**Financial:** Previously had more capital, "misventured" 3-4 years ago. Currently in a sustaining mode, protecting the team and waiting for growth opportunity.

---

## Problems & Pain Points

### 1. Documentation Errors (Most Costly)
Each HS code has its own customs law and procedures. If documents don't match exactly:
- Customs raises a query
- Need to renegotiate, reclassify, or resubmit
- Worst case: withdraw the shipment (attracts heavy penalties + time loss)
- Missing a vessel = next vessel may be 15 days away
- Can lose the client entirely

**Recent example:** EPCG license filing had a misdeclared factory location (different district than what was on the container stuffing report). Customs held the shipment. Export benefit on the shipment was 6 lakh rupees. Customs officer tried to extract 2 lakh bribe. Shreedhar negotiated personally at 2 AM, settled at 40,000, got LEO at 12:30 AM — 90 minutes before the vessel left.

### 2. Customs Disputes
Custom officers can hold shipments and use it as leverage. Requires deep knowledge of customs law to push back. Shreedhar is the primary person who handles these — the team can't operate at this level without him.

### 3. Growth Bottleneck
All sales/relationships run through Shreedhar personally. No systems, no team, no online presence driving inbound. This is the #1 constraint on growth.

### 4. Network Partner Risk
Overseas partners have bypassed Airlift in the past, going direct to clients. No formal agreements or protection.

---

## Growth Levers (Identified by Shreedhar)

1. **New customers** — the only real growth path
2. **Better website** — current site exists but not driving anything
3. **Online marketing** — Facebook, Instagram, industry platforms
4. **Individual overseas partnerships** — Shreedhar's preferred model: exclusive bilateral relationships with freight forwarders in other countries (they pick up for Airlift, Airlift delivers for them). Better than group networks.
5. **Network platforms (secondary)** — JC Trans and similar global freight groups exist but Shreedhar is skeptical: they float one inquiry to 10 competing agents simultaneously. He doesn't want that — wants exclusive, trusted partnerships.
6. **Referrals** — more structured referral system vs. purely personal network
7. **Online marketing** — Facebook, Instagram; currently zero presence

---

## Sai's Goal

Take this on as a side project. Use AI to drive growth for Airlift — possibly starting with:
- Better web presence / lead generation
- Automating or streamlining documentation processes
- Building a systematic approach to network partner acquisition
- Identifying where AI can reduce the dependency on Shreedhar personally

This is still early stage. Need to identify highest-leverage starting point.
