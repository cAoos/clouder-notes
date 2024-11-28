---
{"dg-publish":true,"permalink":"/work/clouder/projects/00-icesi/000-documentation/000-leads/01-flows/lead-send-task-to-the-owner/lead-send-task-to-the-owner/"}
---

## Description

Este flujo se encarga de crear una tarea para el asesor indicándole que tiene un nuevo lead por atender, asi mismo se envía un correo para notificar la situación.
## Need to be improve? 
_It means improves related structure and physical design not functionality_

- [ ] Si
- [x] No

## Status

- [ ] Equal on both environments
- [ ] Sandbox ahead
- [ ] Production ahead

## Diagrama

[Diagrama](obsidian://open?vault=NotesV0.2&file=work%2FClouder%2FProjects%2F00_Icesi%2F000_Documentation%2F000_Leads%2F01_Flows%2FLead_Send-task-to-the-Owner%2FLead_Send-task-to-the-Owner.bpmn)

<?xml version="1.0" encoding="utf-8"?><!-- created with bpmn-js / http://bpmn.io --><!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="620" height="447" viewBox="5 107 620 447" version="1.1"><defs><pattern id="djs-grid-pattern-67981" width="10" height="10" patternUnits="userSpaceOnUse"><circle cx="0.5" cy="0.5" r="0.5" style="fill: rgb(204, 204, 204);"/></pattern></defs><g class="djs-group"><g class="djs-element djs-shape" data-element-id="StartEvent_1" style="display: block;" transform="matrix(1 0 0 1 462 112)"><g class="djs-visual"><circle cx="18" cy="18" r="18" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(32, 80, 34); stroke-width: 2px; fill: rgb(200, 230, 201); fill-opacity: 0.95;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="36" height="36" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><circle cx="18" cy="18" r="23" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="StartEvent_1_label" style="display: block;" transform="matrix(1 0 0 1 513 117)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(32, 80, 34);"><tspan x="0" y="9.899999999999999">Inicio : Created </tspan><tspan x="15.890625" y="23.099999999999998">- Update</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="74" height="27" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="84" height="37" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Gateway_1vvtcbe" style="display: block;" transform="matrix(1 0 0 1 455 175)"><g class="djs-visual"><polygon points="25,0 50,25 25,50 0,25" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(107, 60, 0); stroke-width: 2px; fill: rgb(255, 224, 178); fill-opacity: 0.95;"/><path d="m 16,15 7.42857142857143,9.714285714285715 -7.42857142857143,9.714285714285715 3.428571428571429,0 5.714285714285715,-7.464228571428572 5.714285714285715,7.464228571428572 3.428571428571429,0 -7.42857142857143,-9.714285714285715 7.42857142857143,-9.714285714285715 -3.428571428571429,0 -5.714285714285715,7.464228571428572 -5.714285714285715,-7.464228571428572 -3.428571428571429,0 z" style="fill: rgb(107, 60, 0); stroke-linecap: round; stroke-linejoin: round; stroke: rgb(107, 60, 0); stroke-width: 1px;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="50" height="50" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="2" y="2" rx="4" width="46" height="46" class="djs-outline" style="transform-box: fill-box; transform: rotate(45deg); transform-origin: center center; fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Gateway_1vvtcbe_label" style="display: block;" transform="matrix(1 0 0 1 436 235)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(107, 60, 0);"><tspan x="3.7080078125" y="9.899999999999999">¿Se actualizó el </tspan><tspan x="14.9921875" y="23.099999999999998">Owner o se </tspan><tspan x="15.322998046875" y="36.3">actualizó el </tspan><tspan x="17.991455078125" y="49.5">reclutador </tspan><tspan x="0" y="62.7">auxiliar del Lead?</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="87" height="66" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="97" height="76" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Event_0l31mfq" style="display: block;" transform="matrix(1 0 0 1 462 492)"><g class="djs-visual"><circle cx="18" cy="18" r="18" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(131, 19, 17); stroke-width: 4px; fill: rgb(255, 205, 210); fill-opacity: 0.95;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="36" height="36" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><circle cx="18" cy="18" r="24" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Event_0l31mfq_label" style="display: block;" transform="matrix(1 0 0 1 472 535)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(131, 19, 17);"><tspan x="0" y="9.899999999999999">Fin</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="16" height="14" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="26" height="24" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Activity_1xy5btp" style="display: block;" transform="matrix(1 0 0 1 290 240)"><g class="djs-visual"><rect x="0" y="0" width="100" height="80" rx="10" ry="10" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; fill: white; fill-opacity: 0.95;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="20.421875" y="22">Send Task: </tspan><tspan x="26.1533203125" y="36.4">Envío de </tspan><tspan x="13.478515625" y="50.8">notificación al </tspan><tspan x="8.654296875" y="65.19999999999999">asesor (Owner)</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="100" height="80" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="14" width="110" height="90" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Activity_0w97kva" style="display: block;" transform="matrix(1 0 0 1 290 360)"><g class="djs-visual"><rect x="0" y="0" width="100" height="80" rx="10" ry="10" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; fill: white; fill-opacity: 0.95;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="17.6484375" y="14.799999999999999">Send Email: </tspan><tspan x="26.1533203125" y="29.199999999999996">Envío de </tspan><tspan x="11.478515625" y="43.599999999999994">notificación de </tspan><tspan x="26.4892578125" y="57.99999999999999">correo al </tspan><tspan x="30.9921875" y="72.39999999999999">Owner.</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="100" height="80" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="14" width="110" height="90" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="TextAnnotation_04pwqn9" style="display: block;" transform="matrix(1 0 0 1 10 245)"><g class="djs-visual"><rect x="0" y="0" width="190" height="70" rx="0" ry="0" style="stroke-linecap: round; stroke-linejoin: round; stroke: none; stroke-width: 2px; fill: none;"/><path d="m 0, 0 m 10,0 l -10,0 l 0,70 l 10,0" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="7" y="17.799999999999997">Notificación de ventas: Un nuevo</tspan><tspan x="7" y="32.199999999999996">lead ha sido ingresado en el </tspan><tspan x="7" y="46.599999999999994">sistema. Revisa los detalles </tspan><tspan x="7" y="60.99999999999999">ahora.</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="190" height="70" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="200" height="80" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="TextAnnotation_0rf660i" style="display: block;" transform="matrix(1 0 0 1 10 385)"><g class="djs-visual"><rect x="0" y="0" width="217" height="40" rx="0" ry="0" style="stroke-linecap: round; stroke-linejoin: round; stroke: none; stroke-width: 2px; fill: none;"/><path d="m 0, 0 m 10,0 l -10,0 l 0,40 l 10,0" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="7" y="17.799999999999997">Template: Lead.Send_task_to_owner</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="217" height="40" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="227" height="50" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_1akhp4u" style="display: block;"><g class="djs-visual"><defs><marker id="marker-7c65at6rm2vb7lxk1zfiuj731" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-7c65at6rm2vb7lxk1zfiuj731');" d="M480,148L480,175"/></g><rect x="475" y="143" rx="4" width="10" height="37" class="djs-outline" style="fill: none;"/><path d="M480,148L480,175" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_1uq8xnn" style="display: block;"><g class="djs-visual"><defs><marker id="marker-263ie88l1fa8zbmi20ohppbbo" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-263ie88l1fa8zbmi20ohppbbo');" d="M505,200L615,200C617.5,200,620,202.5,620,205L620,465C620,467.5,617.5,470,615,470L485,470C482.5,470,480,472.5,480,475L480,492"/></g><rect x="475" y="195" rx="4" width="150" height="302" class="djs-outline" style="fill: none;"/><path d="M505,200L620,200L620,470L480,470L480,492" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Flow_1uq8xnn_label" style="display: block;" transform="matrix(1 0 0 1 562 183)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="0" y="9.899999999999999">No</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="15" height="14" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="25" height="24" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_1dw5kvk" style="display: block;"><g class="djs-visual"><defs><marker id="marker-8xoq7j7bjpqpfw7uz2ea8b5my" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-8xoq7j7bjpqpfw7uz2ea8b5my');" d="M455,200L345,200C342.5,200,340,202.5,340,205L340,240"/></g><rect x="335" y="195" rx="4" width="125" height="50" class="djs-outline" style="fill: none;"/><path d="M455,200L340,200L340,240" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Flow_1dw5kvk_label" style="display: block;" transform="matrix(1 0 0 1 392 182)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="0" y="9.899999999999999">Si</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="11" height="14" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="21" height="24" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_0gjvumc" style="display: block;"><g class="djs-visual"><defs><marker id="marker-apms67sip7v5urxxcaf1on2qq" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-apms67sip7v5urxxcaf1on2qq');" d="M340,320L340,360"/></g><rect x="335" y="315" rx="4" width="10" height="50" class="djs-outline" style="fill: none;"/><path d="M340,320L340,360" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_1erg6p3" style="display: block;"><g class="djs-visual"><defs><marker id="marker-54f81vrb0otva48c2y7w6bt39" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-54f81vrb0otva48c2y7w6bt39');" d="M340,440L340,465C340,467.5,342.5,470,345,470L475,470C477.5,470,480,472.5,480,475L480,490"/></g><rect x="335" y="435" rx="4" width="150" height="60" class="djs-outline" style="fill: none;"/><path d="M340,440L340,470L480,470L480,490" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Association_0wizwvo" style="display: block;"><g class="djs-visual"><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; stroke-dasharray: 0, 5;" d="M290,280L200,280"/></g><rect x="195" y="275" rx="4" width="100" height="10" class="djs-outline" style="fill: none;"/><path d="M290,280L200,280" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Association_0tw5bq9" style="display: block;"><g class="djs-visual"><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; stroke-dasharray: 0, 5;" d="M290,400L227,400"/></g><rect x="222" y="395" rx="4" width="73" height="10" class="djs-outline" style="fill: none;"/><path d="M290,400L227,400" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g></svg>