# Solar Layout Planner

A free rooftop solar planner for Indian homes and flats. Enter your roof and the size you want. It lays out the panels, strings and wiring, works out the no-drill ballast, and checks shade from cabins, tanks, walls and trees through the whole year. It then gives the cost, the subsidy, and a one-page brief to send to vendors.

**Open it:** https://coolboss.github.io/solar-layout-planner/

It is one HTML file. Nothing is uploaded: your roof stays in your own browser.

## What it does

- **Layout:** fits panels on any roof drawn as rectangles (L-shapes, cut-outs), with clearances and row spacing so rows don't shade each other in December.
- **Shade:** sun position for any date and minute, in sun time or clock time (IST). Includes trees and neighbouring buildings off the roof. Yearly shade loss is counted over 12 days of the year.
- **Edges:** solid wall or open railing for each side. Railings let full wind reach the edge panels; walls shade a little.
- **Wiring:** strings, inverter choice (single or three phase), cable sizes, voltage drop, breakers, and a single-line diagram.
- **No-drill mounting:** ballast blocks per panel from IS 875-3 style wind pressure, and the added roof load in kg/m².
- **Cost and subsidy:** indicative bill of materials, and PM Surya Ghar subsidy for homes or housing societies.
- **Flats or tower mode:** floors, flats sharing, society checklist, wind warning for tall buildings.
- **Site survey score:** nine must-have inputs. Yearly units are shown as a range that narrows as you measure more.
- **Trim the trees?** Compares units with the trees as they are, trimmed, and without them.
- **Vendors:** how to pick vendors from the official PM Surya Ghar list, a brief made from your design, questions to ask, and red flags.
- **Exports:** report, vendor brief, layout, wiring, 3D view, single-line diagram, bill of materials, project file.

## The example roof

The example is an L-shaped terrace in Vadodara with two mango trees, entered from photos and measurements. Load it from **Load example terrace**, or start blank.

## How accurate is it?

With measured inputs, the layout is close to exact and the yearly units are within about 10 to 15 %. With estimated tree or building heights, allow about 20 %.

Ballast, roof load and wind figures are planning values. They are not a design. Before installing, get:

- a signed wind calculation to IS 875-3 from the structure supplier,
- a structural engineer's check of the roof slab,
- written quotes and datasheets,
- approval from your electricity company for net metering.

## Disclaimer

Planning-grade tool. Inverter data, city wind speeds, wind coefficients and prices are typical values. Replace them with the datasheets of the equipment you buy. It does not replace a site survey, a wind design, the electricity company's approval or the electrical inspector.
