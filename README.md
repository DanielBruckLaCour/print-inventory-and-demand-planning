# Print Inventory and Demand Planning Framework

A practical framework for forecasting print demand, calculating production quantities, managing stock across locations, and planning replenishment.

## 1. The Inventory Problem

Businesses often produce printed materials in quantities that do not match actual demand.

Some end up storing brochures, catalogs, packaging, and promotional materials they no longer need. Others run out of stock and have to arrange additional production under time pressure.

Both problems can be costly.

The challenge is to match production quantities with expected usage while accounting for existing stock, supplier lead times, and changes in business requirements.

This framework covers the planning and controls needed to manage that process.

## 2. Classify Printed Inventory

Different materials have different consumption patterns and storage requirements.

| Inventory type | Examples | Main planning factor |
|---|---|---|
| Marketing materials | Brochures, flyers, catalogs | Campaign demand |
| Business stationery | Letterheads, envelopes, forms | Regular usage |
| Packaging | Boxes, labels, inserts | Product volume |
| Promotional materials | Branded merchandise, giveaways | Event and campaign schedules |
| Retail materials | Point-of-sale displays, product cards | Store-level demand |
| Operational materials | Manuals, instructions, documentation | Usage and replacement rates |

Materials that change frequently should generally be planned differently from standardized items used throughout the year.

## 3. Forecast Demand

Start with actual consumption records and adjust them for confirmed future requirements.

Consider:

- Monthly or quarterly usage.
- Upcoming campaigns and events.
- Product launches.
- Changes in sales or distribution volume.
- Seasonal demand.
- New locations or markets.
- Existing stock and outstanding orders.

**Average monthly demand = Total units consumed ÷ Number of months observed**

Example:

A business consumes 12,000 brochures over six months.

Average monthly demand = 12,000 ÷ 6 = 2,000 brochures.

This provides a baseline. Increase or reduce the forecast when there is evidence that future demand will differ.

## 4. Calculate Replenishment Requirements

A business needs to know how much stock it has, what is already committed, and how long replacement production will take.

**Inventory position = Available usable stock + Confirmed incoming stock − Allocated stock**

### Reorder point

**Reorder point = Average demand during lead time + Safety stock**

Example:

- Average monthly demand: 2,000 units
- Production and delivery lead time: 1 month
- Safety stock: 500 units

Reorder point = 2,500 units.

When inventory position reaches this level, replenishment should be reviewed.

Safety stock should reflect demand fluctuations, supplier reliability, and the consequences of running out. It should not be an arbitrary percentage applied to every product.

## 5. Calculate Production Quantities

Before placing an order, account for existing inventory and confirmed deliveries.

**Required production quantity = Forecast demand + Target closing stock − Available usable inventory − Confirmed incoming stock**

Example:

| Item | Quantity |
|---|---:|
| Forecast demand | 8,000 |
| Target closing stock | 2,000 |
| Available usable inventory | 3,000 |
| Confirmed incoming stock | 1,000 |
| **Required production** | **6,000** |

Check the result against supplier minimum order quantities, production economics, and available storage capacity.

## 6. Manage Inventory Across Locations

A consolidated stock figure can hide shortages in individual markets.

Track consumption and available quantities by location.

| Location | Opening stock | Consumption | Incoming stock | Closing stock |
|---|---:|---:|---:|---:|
| Location A | Record | Record | Record | Calculate |
| Location B | Record | Record | Record | Calculate |
| Location C | Record | Record | Record | Calculate |

**Closing stock = Opening stock + Incoming stock − Consumption**

Before arranging new production, check whether usable stock can be transferred from another location. Account for the cost and time involved in redistribution.

## 7. Control Excess and Obsolete Stock

Printed materials can become unusable when branding, product information, pricing, or campaign details change.

Review inventory for:

- Outdated artwork or messaging.
- Materials approaching a planned replacement date.
- Products with low or declining consumption.
- Damaged stock.
- Quantities exceeding realistic demand.
- Materials held at locations where they are no longer required.

Check existing inventory before approving another production run. Producing more of an item that is about to be replaced creates avoidable waste.

## 8. Plan Around Production Lead Times

Replenishment requires more than the supplier's stated manufacturing time.

Include the time needed for:

1. Demand review and quantity approval.
2. Artwork preparation and confirmation.
3. Supplier scheduling.
4. Proofing and approval.
5. Production and finishing.
6. Quality inspection.
7. Packaging and transportation.
8. Receipt and inventory updates.

Use actual supplier performance when estimating lead times. Allow for additional time where international shipping, customs clearance, or multiple delivery locations are involved.

## 9. Monitor Inventory Performance

Track a small number of measures that reveal whether inventory decisions are working.

| KPI | What it measures |
|---|---|
| Inventory turnover | How frequently stock is consumed and replenished |
| Stockout frequency | How often required materials are unavailable |
| Excess inventory | Stock above planned requirements |
| Forecast accuracy | Difference between forecast and actual demand |
| Obsolete inventory | Stock that can no longer be used |
| Replenishment lead time | Time from order placement to receipt |
| Inventory carrying cost | Cost of holding stock |
| Location-level availability | Stock availability at each location |

Review these measures alongside one another. Reducing inventory is not an improvement if it creates frequent shortages.

## 10. Inventory Review Checklist

**Before production**

- [ ] Review historical consumption.
- [ ] Confirm upcoming campaigns and requirements.
- [ ] Check usable stock across locations.
- [ ] Review incoming purchase orders.
- [ ] Calculate the required production quantity.
- [ ] Confirm supplier lead times and minimum quantities.
- [ ] Verify artwork and specifications.

**During inventory management**

- [ ] Record stock receipts and consumption.
- [ ] Monitor location-level quantities.
- [ ] Review reorder points.
- [ ] Identify damaged and obsolete materials.
- [ ] Update demand forecasts.
- [ ] Review upcoming replenishment requirements.

**After replenishment**

- [ ] Confirm delivered quantities.
- [ ] Update inventory records.
- [ ] Record shortages or rejected materials.
- [ ] Compare actual consumption with forecasts.
- [ ] Adjust future production quantities.

## 11. Repository Resources

The framework can be supported by these reusable files:

| File | Purpose |
|---|---|
| `templates/demand-forecast.md` | Record expected demand |
| `templates/inventory-register.md` | Track stock by product and location |
| `templates/replenishment-planner.md` | Calculate replenishment requirements |
| `templates/location-stock-allocation.md` | Plan distribution between locations |
| `calculations/reorder-point.md` | Calculate reorder levels |
| `calculations/production-quantity.md` | Calculate required production |
| `checklists/inventory-review.md` | Review inventory before and after production |
| `examples/multi-location-inventory-example.md` | Demonstrate multi-location planning |

## 12. Inventory Planning Rules

1. Base forecasts on consumption records and confirmed requirements.
2. Check usable inventory before ordering more.
3. Set reorder points according to demand and actual lead times.
4. Track stock separately by location.
5. Identify materials at risk of becoming obsolete.
6. Consider storage and handling costs when setting production quantities.
7. Compare forecasts with actual consumption and adjust future plans.

## Conclusion

Print inventory decisions affect production quantities, storage requirements, purchasing, and delivery.

Businesses need accurate consumption records, realistic demand forecasts, and visibility across all locations. Without these, they risk holding stock they cannot use or running out of materials they still need.

The objective is to keep the right materials available in the right quantities, without tying up resources in unnecessary inventory.

## About Daniel Bruck LaCour

Daniel Bruck LaCour is an entrepreneur and owner of IPS Merch and International Printing Services. His professional focus includes global print management, print production, packaging, branded merchandise, promotional products, fulfillment, and international distribution.
