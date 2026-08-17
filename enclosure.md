# Enclosure

## Internal Component Dimensions:
  (Add +0.5mm print tolerance to all pocket dimensions)
1. Main Board (XIAO nRF52840 + Wio-SX1262): 21.5mm x 18.3mm x 25.5mm pocket with standoff mounting points.
2. Battery (2000mAh LiPo): 50.5mm x 70.5mm x 10.5mm retaining tray located below main electronics.
3. Solar Charger (CN3065): 40.5mm x 20.5mm x 7.5mm slot near the battery.
4. BMP280 Sensor: Isolated 15mm x 12mm x 5mm vented chamber at the shaded bottom of the housing to prevent solar heat soak while allowing ambient airflow.

## Enclosure & Solar Shield Specifications:
- Outer Shell: Wall thickness = 3.0mm, minimum internal corner fillets = 2.0mm.
- Roof / Solar Shield: Integrates a 168mm x 168mm top mounting plate tilted at 30 degrees to hold a 165mm x 165mm solar panel. The roof must overhang the main enclosure body on all sides to shed rainwater (drip edge).
- Fastening & Sealing: 4x corner post holes for M3 heat-set inserts and M3x12 screws. Include a 2.0mm tongue-and-groove channel along the lid-to-base perimeter for a custom silicone/TPU gasket.
- External IO: 1x 6.5mm hole for an SMA antenna connector (top or upper side), and 2x rear mounting loops for zip-ties or hose clamps (pole/wall mounting).

## Pole Mount System (50mm to 75mm Diameter Poles):
- Rear Saddle: Integrated 120-degree V-block (V-notch) mounting block molded onto the back wall. The V-notch geometry must accommodate cylindrical poles ranging from 50mm up to 75mm in outer diameter without wobbling.
- Band Clamp Channels: 2x horizontal pass-through slots (14mm wide x 3.5mm high) embedded through the rear saddle to accept standard stainless steel worm-gear hose clamps or heavy-duty UV-resistant cable ties.
- Grip Feature: Ribbed/serrated texture along the inner face of the V-saddle to prevent vertical slippage on metal or PVC poles.


Ensure all code uses standard CSG operations (difference, union, hull), includes helpful comments, uses dynamic variables for wall thickness and tolerances, and is optimized to print without support material where possible.
