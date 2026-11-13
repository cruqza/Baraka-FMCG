# Baraka Manufacturers — Dashboard Analysis Report

**Project:** Baraka Manufacturers Dashboard (`Baraka.pbix`)  
**Analyst:** Erickson Nyaga   
**Date:** 13 November 2026  
**Data period:** January 2023 – December 2025 (36 months)  
**Currency:** Kenyan Shilling (KES)  


---

## Executive Summary

BaraKa Manufacturers is a regional FMCG distributor operating 7 markets across East Africa (Kenya and East Africa community). The dashboard reveals three structural issues:

1. **Target underperformance is chronic, not cyclical.** All 7 markets are behind target; every market has run consecutive monthly misses since January 2024.
2. **Seasonality is extreme and predictable.** January is the weakest month and December is the strongest — every year, by a consistent margin.
3. **Discounting is the single largest margin drag.** Moving from no discount to a 15% high discount erodes margin by ~17 percentage points; the Government segment and Maize Flour / Bar Soap SKUs carry the largest absolute loss.

---

## 1. Which markets are behind target, and since when?

### 1.1 Findings

All 7 markets are behind target on a 3-year aggregate. The shortfall is broad-based but modest — the company is ~435 KES short overall (0.14%).

| Market | Total Sales (KES) | Target (KES) | % of Target | Cumulative Variance |
|---|---|---|---|---|
| Nairobi | 115,864,491 | 116,039,673 | −0.15% | −175,182 |
| Mombasa | 52,075,511 | 52,150,717 | −0.14% | −75,206 |
| Kisumu | 40,758,786 | 40,820,455 | −0.15% | −61,669 |
| Nakuru | 34,719,764 | 34,771,655 | −0.15% | −51,891 |
| Kampala | 24,564,843 | 24,601,667 | −0.15% | −36,824 |
| Dar es Salaam | 20,630,932 | 20,664,278 | −0.16% | −33,346 |
| Kigali | 12,422,057 | 12,422,555 | −0.004% | −498 |

### 1.2 When they fell behind

- **First month behind:** January 2023 (all markets)
- **First continuous period:** January 2024 → October 2025 (12 consecutive months of misses across all 7 markets)
- **Recovery months:** Intermittent over-achievement in 2023 (Feb–Apr, Jun–Dec) and 2025 (Mar, Sep, Nov, Dec)
- **No market has recovered** to exceed target since the 2024–2025 run of consecutive misses began

At the company level, of 36 monthly observations, the firm was behind target in 19 months. The 2024 calendar year was a complete miss (12/12 months behind).

### 1.3 Key insight

The underperformance is not a recent phenomenon — Kigali was already 94% below target in 2023. However, the 2024–2025 run of consecutive misses is the most persistent since the start of the data period. Nairobi and Mombasa carry the largest total gap in absolute KES terms.

---

## 2. Which months are strongest and weakest each year?

### 2.1 Monthly sales by year

| Year | Weakest month | Sales (KES) | Strongest month | Sales (KES) | Peak-to-trough spread |
|---|---|---|---|---|---|
| 2023 | Jan | 6,501,707 | Dec | 10,413,325 | 3,911,618 |
| 2024 | Jan | 6,874,710 | Dec | 10,794,656 | 3,919,946 |
| 2025 | Jan | 7,351,267 | Dec | 11,808,996 | 4,457,729 |

### 2.2 Pattern

The seasonal pattern is identical every year:

- **December is consistently the strongest month** — driven by year-end/H1 demand and channel stocking ahead of the new year.
- **January is consistently the weakest month** — a post-holiday consumption dip; demand recovers through February–March before building through the year.
- **Year-over-year growth:** December +13.4%, January +13.0% (steady top-line improvement each year).
- **Absolute spread:** The December-to-January gap widened from ~3.9M in 2023 to ~4.5M in 2025, indicating that seasonality is intensifying, not fading.

### 2.3 Action

The consistency of this pattern makes it a reliable planning signal. January can be budgeted as a trough; December can be budgeted as the peak. The company should not be surprised by the January dip — it is a structural feature, not an anomaly.

---

## 3. Where is discounting costing the most margin?

### 3.1 Margin by discount band

| Discount band | Description | Sales (KES) | Margin | Profit (KES) |
|---|---|---|---|---|
| None | No discount applied | 105,814,395 | 31.0% | 32,768,825 |
| Low | ~3% discount | 84,186,683 | 28.0% | 23,576,204 |
| Medium | ~7% discount | 64,637,927 | 23.3% | 15,062,022 |
| High | ~15% discount | 46,397,379 | 13.8% | 6,386,521 |

**Going from no discount to HIGH discount erodes margin by 17.2 percentage points** — the single largest cost factor in the business.

### 3.2 Margin loss by segment (High discount vs no discount)

| Segment | No-discount margin | High-discount margin | Loss (pp) | Profit lost (KES) |
|---|---|---|---|---|
| **Government** | 28.8% | 14.3% | **−14.6 pp** | 668,537 |
| Distributors | 24.1% | 11.2% | −12.9 pp | −1,606,854 |
| Supermarkets | 30.4% | 18.2% | −12.2 pp | 16,557,222 |
| Small shops | 34.5% | 22.5% | −12.0 pp | 7,576,552 |
| Hotels and restaurants | 31.8% | 20.3% | −11.4 pp | 3,186,847 |

**The Government segment loses the most margin per sale** — every 100 KES of sales drops from 28.8 KES profit to 14.3 KES profit under a 15% discount.

### 3.3 Margin loss by product (High discount vs no discount)

| Product | No-discount margin | High-discount margin | Loss (pp) | Profit lost (KES) |
|---|---|---|---|---|
| Baraka Maize Flour 2kg | 27.7% | 9.5% | **−18.2 pp** | 6,997,632 |
| Baraka Bar Soap 800g | 30.7% | 12.7% | −18.0 pp | 3,513,300 |
| Baraka Tissue 10-pack | 28.0% | 10.5% | −17.4 pp | 2,483,275 |
| Baraka Cooking Oil 1L | 31.9% | 14.8% | −17.0 pp | 6,856,227 |
| Baraka Detergent 1kg | 32.5% | 15.6% | −16.9 pp | 3,627,219 |
| Baraka Mango Juice 1L | 39.5% | 24.6% | −14.8 pp | 2,904,651 |

### 3.4 Top-line takeaway

Discounting is converting a healthy ~31% margin into ~14% at the highest discount tier. The **Government segment** and the **Maize Flour and Bar Soap SKUs** carry the largest absolute margin loss.



*Report generated from Baraka.pbix.*
