## Depot

In the context of this [model](../domain-inventory.md), a [depot][depot]

<img align="right" src="../images/depot_equals.svg" />

<ul>
 <li><i>equals</i> an <a href="ECO.hazardous.chemical.storage.depot.md">ECO hazardous chemical storage depot</a></li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
</ul>


<img align="right" src="../images/depot_extends.svg" />

<ul>
 <li><i>extends</i> an <a href="hazardous.chemical.storage.facility.md">hazardous chemical storage facility</a></li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
 <li> </li>
</ul>


<img align="right" src="../images/depot_contains.svg" />

<ul>
 <li><i>contains</i> some <a href="staff.building.md">staff buildings</a> and some <a href="storage.building.md">storage buildings</a> and a <a href="loading.bay.md">loading bay</a></li>
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
 <li> </li>
 <li> </li>
 <li> </li>
</ul>


<img align="right" src="../images/depot_complies_with.svg" />

<ul>
 <li><i>complies_with</i> some <a href="EPA.regulation.md">EPA regulations</a></li>
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
"The ECO storage [depot][depot] operates in accordance with the Environmental Protection Agency [EPA regulations][EPA.regulation] controlling
the storage of environmentally damaging chemicals."

[Quote:][delivery]
"When a [truck][truck] arrives at the [loading bay][loading.bay], the clerk enters the manifest accompanying the load and
checks in the [drums][drum] one at a time."


### Derivations

<table>
<tr><th align="left"> Phrases </th><th align="left"> Derivations </th></tr>
<tr>
<td style="vertical-align:top">

* a [truck][truck] arrives at the [loading bay][loading.bay]
* "environmentally damaging" = **hazardous**
* “operates in accordance with” = _complies with_

</td>
<td style="vertical-align:top">

* so: the ECO [depot][depot] _contains_ a [loading bay][loading.bay]
* so: the ECO [depot][depot] is a [hazardous chemical][hazardous.chemical] storage facility
* so: the ECO [depot][depot] _complies with_ EPA [hazardous chemical][hazardous.chemical] storage regulations

</td>
</tr>
</table>


[narrative]: ../original-narrative.md#eco-depot
[delivery]: ../original-narrative.md#drum-delivery


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

