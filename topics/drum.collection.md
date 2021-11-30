## Drum Collection

In the context of this [model](../domain-inventory.md), a [drum collection][drum.collection]

<img align="right" src="../images/drum_collection_collects.svg" />

<ul>
 <li><i>collects</i> a <a href="drum.load.md">drum load</a> from a <a href="loading.bay.md">loading bay</a></li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
</ul>



### Narrative Source

[Quote:][narrative]
"[Drum][Drum] collections are initiated by the [loading bay clerk][loading.bay.clerk], who types in an order manifest
for the number and type of [drums][drum] that are required.
The system identifies the [drums][drum] that are to be retrieved from the [storage buildings][storage.building].
A manifest for the order is sent to the [loading bay clerk][loading.bay.clerk]."

### Derivations

<table>
<tr><th align="left"> Phrases </th><th align="left"> Derivations </th></tr>
<tr>
<td style="vertical-align:top">

* "collections are initiated ..."
* "who types in ..."
*
* "order is sent ..."

</td>
<td style="vertical-align:top">

* so: a [loading bay clerk][loading.bay.clerk] _initiates_ [drum collections][drum.collection]
* so: a [loading bay clerk][loading.bay.clerk] _types_ an order manifest
* the system _identifies_ the [drums][drum] to be retrieved from the [storage buildings][storage.building]
* the system _sends_ an order manifest _to_ a [loading bay clerk][loading.bay.clerk]

</td>
</tr>
</table>

### Implications

* a [loading bay clerk][loading.bay.clerk] _enters_ a collection order _into_ the system
* a collection order _lists_ a drum count for each [hazard type][hazard.type]
* the system _produces_ a collection manifest for a [loading bay clerk][loading.bay.clerk]
* a collection manifest _lists_ the drum locations
* a drum location _identifies_ the storage building for each drum in a collection
* a building identifier _locates_ some [drums][drum]

### Additional Concepts

There are holes evident in the original narrative. Many of them were filled during the analysis
through _semantic implication_. However, a few important elements of the domain are still missing.
Also, several [depot management system][depot.management.system] use-cases are implied.
We need to make those use-cases explicit and supply the missing domain elements.

_How does a [loading bay clerk][loading.bay.clerk] initiate a collection?_
* the system presents loading bay operations to a [loading bay clerk][loading.bay.clerk]
* a [loading bay clerk][loading.bay.clerk] selects drum collection from the loading bay operations
* a [loading bay clerk][loading.bay.clerk] enters a drum count and [EPA][EPA] [hazard type][hazard.type] into the system

_How is a collection ended?_
* a [loading bay clerk][loading.bay.clerk] notifies the system of a collected drum load
* the system removes the collected [drums][drum] from the [drum inventory][drum.inventory]

[narrative]: ../original-narrative.md#drum-collection


<div align="center"><b>&sect; &sect; &sect;</b></div>

[EPA]: EPA.md
[EPAs]: EPA.md
[EPA.regulation]: EPA.regulation.md
[EPA.regulations]: EPA.regulation.md
[building.description]: building.description.md
[building.descriptions]: building.description.md
[chemical.description]: chemical.description.md
[chemical.descriptions]: chemical.description.md
[company.regulation]: company.regulation.md
[company.regulations]: company.regulation.md
[depot]: depot.md
[depots]: depot.md
[depot.building]: depot.building.md
[depot.buildings]: depot.building.md
[depot.distance.unit]: depot.distance.unit.md
[depot.distance.units]: depot.distance.unit.md
[depot.management]: depot.management.md
[depot.managements]: depot.management.md
[depot.management.system]: depot.management.system.md
[depot.management.systems]: depot.management.system.md
[depot.manager]: depot.manager.md
[depot.managers]: depot.manager.md
[depot.map]: depot.map.md
[depot.maps]: depot.map.md
[depot.monitoring]: depot.monitoring.md
[depot.monitorings]: depot.monitoring.md
[depot.volume.unit]: depot.volume.unit.md
[depot.volume.units]: depot.volume.unit.md
[depot.vulnerability]: depot.vulnerability.md
[depot.vulnerabilities]: depot.vulnerability.md
[depot.weight.unit]: depot.weight.unit.md
[depot.weight.units]: depot.weight.unit.md
[drum]: drum.md
[drums]: drum.md
[drum.collection]: drum.collection.md
[drum.collections]: drum.collection.md
[drum.delivery]: drum.delivery.md
[drum.deliveries]: drum.delivery.md
[drum.description]: drum.description.md
[drum.descriptions]: drum.description.md
[drum.identifier]: drum.identifier.md
[drum.identifiers]: drum.identifier.md
[drum.inventory]: drum.inventory.md
[drum.inventories]: drum.inventory.md
[drum.label]: drum.label.md
[drum.labels]: drum.label.md
[drum.storage]: drum.storage.md
[drum.storages]: drum.storage.md
[drum.storage.allocation]: drum.storage.allocation.md
[drum.storage.allocations]: drum.storage.allocation.md
[drum.storage.license]: drum.storage.license.md
[drum.storage.licenses]: drum.storage.license.md
[drum.storage.license.description]: drum.storage.license.description.md
[drum.storage.license.descriptions]: drum.storage.license.description.md
[hazard.type]: hazard.type.md
[hazard.types]: hazard.type.md
[hazardous.chemical]: hazardous.chemical.md
[hazardous.chemicals]: hazardous.chemical.md
[license.inventory]: license.inventory.md
[license.inventories]: license.inventory.md
[loading.bay]: loading.bay.md
[loading.bays]: loading.bay.md
[loading.bay.clerk]: loading.bay.clerk.md
[loading.bay.clerks]: loading.bay.clerk.md
[safety.violation]: safety.violation.md
[safety.violations]: safety.violation.md
[staff.building]: staff.building.md
[staff.buildings]: staff.building.md
[storage.building]: storage.building.md
[storage.buildings]: storage.building.md
[truck]: truck.md
[trucks]: truck.md

