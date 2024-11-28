---
{"dg-publish":true,"permalink":"/work/clouder/projects/00-icesi/000-documentation/000-leads/01-flows/lead-asociar-al-mercado-real/lead-asociar-al-mercado-real/"}
---

## Description

Este flujo se encarga de validar si el aspirante cumple con las condiciones de conversión automática por promedio de notas superiores a 4.0 y además que sea de último grado.
## Need to be improve? 
_It means improves related structure and physical design not functionality_

- [ ] Si
- [x] No

## Status

- [x] Equal on both environments
- [ ] Sandbox ahead
- [ ] Production ahead

## Diagrama

[Diagrama](obsidian://open?vault=NotesV0.2&file=work%2FClouder%2FProjects%2F00_Icesi%2F000_Documentation%2F000_Leads%2F01_Flows%2FLead_Asociar-al-mercado-real%2FLead_Asociar-al-mercado-real.bpmn)

---dg-publish: true---<?xml version="1.0" encoding="utf-8"?><!-- created with bpmn-js / http://bpmn.io --><!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="750" height="517" viewBox="-105 67 750 517" version="1.1"><defs><pattern id="djs-grid-pattern-139311" width="10" height="10" patternUnits="userSpaceOnUse"><circle cx="0.5" cy="0.5" r="0.5" style="fill: rgb(204, 204, 204);"/></pattern></defs><g class="djs-group"><g class="djs-element djs-shape" data-element-id="StartEvent_1" style="display: block;" transform="matrix(1 0 0 1 442 72)"><g class="djs-visual"><circle cx="18" cy="18" r="18" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(32, 80, 34); stroke-width: 2px; fill: rgb(200, 230, 201); fill-opacity: 0.95;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="36" height="36" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><circle cx="18" cy="18" r="23" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="StartEvent_1_label" style="display: block;" transform="matrix(1 0 0 1 483 77)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(32, 80, 34);"><tspan x="0" y="9.899999999999999">Inicio : Created </tspan><tspan x="15.890625" y="23.099999999999998">- Update</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="74" height="27" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="84" height="37" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Gateway_1if2nqd" style="display: block;" transform="matrix(1 0 0 1 435 135)"><g class="djs-visual"><polygon points="25,0 50,25 25,50 0,25" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(107, 60, 0); stroke-width: 2px; fill: rgb(255, 224, 178); fill-opacity: 0.95;"/><path d="m 16,15 7.42857142857143,9.714285714285715 -7.42857142857143,9.714285714285715 3.428571428571429,0 5.714285714285715,-7.464228571428572 5.714285714285715,7.464228571428572 3.428571428571429,0 -7.42857142857143,-9.714285714285715 7.42857142857143,-9.714285714285715 -3.428571428571429,0 -5.714285714285715,7.464228571428572 -5.714285714285715,-7.464228571428572 -3.428571428571429,0 z" style="fill: rgb(107, 60, 0); stroke-linecap: round; stroke-linejoin: round; stroke: rgb(107, 60, 0); stroke-width: 1px;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="50" height="50" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="2" y="2" rx="4" width="46" height="46" class="djs-outline" style="transform-box: fill-box; transform: rotate(45deg); transform-origin: center center; fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Activity_0t6de6n" style="display: block;" transform="matrix(1 0 0 1 260 190)"><g class="djs-visual"><rect x="0" y="0" width="100" height="80" rx="10" ry="10" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(91, 23, 109); stroke-width: 2px; fill: rgb(225, 190, 231); fill-opacity: 0.95;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(91, 23, 109);"><tspan x="27.818359375" y="22">Obtener </tspan><tspan x="10.984375" y="36.4">(Mercado real) </tspan><tspan x="11.490234375" y="50.8">- Get mercado </tspan><tspan x="39.828125" y="65.19999999999999">real</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="100" height="80" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="14" width="110" height="90" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Activity_0lw09jr" style="display: block;" transform="matrix(1 0 0 1 260 340)"><g class="djs-visual"><rect x="0" y="0" width="100" height="80" rx="10" ry="10" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(13, 67, 114); stroke-width: 2px; fill: rgb(187, 222, 251); fill-opacity: 0.95;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(13, 67, 114);"><tspan x="23.654296875" y="29.200000000000003">Actualizar </tspan><tspan x="30.984375" y="43.6">(Lead): </tspan><tspan x="14.8173828125" y="58">Mercado real</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="100" height="80" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="14" width="110" height="90" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Event_0z9xs4d" style="display: block;" transform="matrix(1 0 0 1 488 522)"><g class="djs-visual"><circle cx="18" cy="18" r="18" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(131, 19, 17); stroke-width: 4px; fill: rgb(255, 205, 210); fill-opacity: 0.95;"/></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="36" height="36" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><circle cx="18" cy="18" r="24" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Association_0jqvv7u" style="display: block;"><g class="djs-visual"><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; stroke-dasharray: 0, 5;" d="M260,230L181,230"/></g><rect x="176" y="225" rx="4" width="89" height="10" class="djs-outline" style="fill: none;"/><path d="M260,230L181,230" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Association_0o3eptf" style="display: block;"><g class="djs-visual"><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; stroke-dasharray: 0, 5;" d="M260,379L233,379"/></g><rect x="228" y="374" rx="4" width="37" height="10" class="djs-outline" style="fill: none;"/><path d="M260,379L233,379" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_0ws63zd" style="display: block;"><g class="djs-visual"><defs><marker id="marker-aabwjno5ln2ax3i8wqfciq3ui" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-aabwjno5ln2ax3i8wqfciq3ui');" d="M460,108L460,135"/></g><rect x="455" y="103" rx="4" width="10" height="37" class="djs-outline" style="fill: none;"/><path d="M460,108L460,135" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_1912mhk" style="display: block;"><g class="djs-visual"><defs><marker id="marker-5k288xo4qtf7t6wkbgzt0cyvj" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-5k288xo4qtf7t6wkbgzt0cyvj');" d="M485,160L635,160C637.5,160,640,162.5,640,165L640,485C640,487.5,637.5,490,635,490L511,490C508.5,490,506,492.5,506,495L506,522"/></g><rect x="480" y="155" rx="4" width="165" height="372" class="djs-outline" style="fill: none;"/><path d="M485,160L640,160L640,490L506,490L506,522" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_0rg97le" style="display: block;"><g class="djs-visual"><defs><marker id="marker-1rba3gpnztp5gq6vv3l82jfkd" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-1rba3gpnztp5gq6vv3l82jfkd');" d="M435,160L315,160C312.5,160,310,162.5,310,165L310,190"/></g><rect x="305" y="155" rx="4" width="135" height="40" class="djs-outline" style="fill: none;"/><path d="M435,160L310,160L310,190" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Gateway_1if2nqd_label" style="display: block;" transform="matrix(1 0 0 1 426 195)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(107, 60, 0);"><tspan x="0" y="9.899999999999999">¿El prospecto </tspan><tspan x="5.6875" y="23.099999999999998">tiene origen </tspan><tspan x="12.2265625" y="36.3">Colegio?</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="68" height="40" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="78" height="50" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="TextAnnotation_1pwk27g" style="display: block;" transform="matrix(1 0 0 1 -100 200)"><g class="djs-visual"><rect x="0" y="0" width="281" height="60" rx="0" ry="0" style="stroke-linecap: round; stroke-linejoin: round; stroke: none; stroke-width: 2px; fill: none;"/><path d="m 0, 0 m 10,0 l -10,0 l 0,60 l 10,0" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="7" y="17.799999999999997">- Colegio mercado real = Colegio (Lead)</tspan><tspan x="7" y="32.199999999999996">- Periodo académico = Periodo académico (Lead)</tspan><tspan x="7" y="46.599999999999994">- Grado = Grado (Lead)</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="281" height="60" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="291" height="70" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_00hh4uv" style="display: block;"><g class="djs-visual"><defs><marker id="marker-09n4eww07kti5b36i9h1z2enp" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-09n4eww07kti5b36i9h1z2enp');" d="M310,270L310,340"/></g><rect x="305" y="265" rx="4" width="10" height="80" class="djs-outline" style="fill: none;"/><path d="M310,270L310,340" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="TextAnnotation_05275tv" style="display: block;" transform="matrix(1 0 0 1 -100 360)"><g class="djs-visual"><rect x="0" y="0" width="333" height="31" rx="0" ry="0" style="stroke-linecap: round; stroke-linejoin: round; stroke: none; stroke-width: 2px; fill: none;"/><path d="m 0, 0 m 10,0 l -10,0 l 0,31.000000000000004 l 10,0" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px;"/><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 12px; font-weight: normal; fill: rgb(34, 36, 42);"><tspan x="7" y="17.799999999999997">- Mercado real (Lead) = Id mercado real (Get mercado real)</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="333" height="31" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="343" height="41" class="djs-outline" style="fill: none;"/></g></g><g class="djs-group"><g class="djs-element djs-connection" data-element-id="Flow_0zod2nd" style="display: block;"><g class="djs-visual"><defs><marker id="marker-8alcydw9n0jdxbh8zbenth6bs" viewBox="0 0 20 20" refX="11" refY="10" markerWidth="10" markerHeight="10" orient="auto"><path d="M 1 5 L 11 10 L 1 15 Z" style="stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 1px; fill: rgb(34, 36, 42);"/></marker></defs><path data-corner-radius="5" style="fill: none; stroke-linecap: round; stroke-linejoin: round; stroke: rgb(34, 36, 42); stroke-width: 2px; marker-end: url('#marker-8alcydw9n0jdxbh8zbenth6bs');" d="M320,420L320,485C320,487.5,322.5,490,325,490L501,490C503.5,490,506,492.5,506,495L506,522"/></g><rect x="315" y="415" rx="4" width="196" height="112" class="djs-outline" style="fill: none;"/><path d="M320,420L320,490L506,490L506,522" class="djs-hit djs-hit-stroke" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/></g></g><g class="djs-group"><g class="djs-element djs-shape" data-element-id="Event_0z9xs4d_label" style="display: block;" transform="matrix(1 0 0 1 498 565)"><g class="djs-visual"><text lineHeight="1.2" class="djs-label" style="font-family: Arial, sans-serif; font-size: 11px; font-weight: normal; fill: rgb(131, 19, 17);"><tspan x="0" y="9.899999999999999">Fin</tspan></text></g><rect class="djs-hit djs-hit-all" x="0" y="0" width="16" height="14" style="fill: none; stroke-opacity: 0; stroke: white; stroke-width: 15px;"/><rect x="-5" y="-5" rx="4" width="26" height="24" class="djs-outline" style="fill: none;"/></g></g></svg>