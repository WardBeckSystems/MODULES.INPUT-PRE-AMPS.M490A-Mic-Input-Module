# M490A · Input Pre Amps

Ward-Beck Systems M490A, 1978|11. Wiki page: [M490A on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M490A.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 22 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 11 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 6 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 15 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 4 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 5 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 33 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [12 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1978 - M490A - 006.jpg](MANUALS/1978%20-%20M490A%20-%20006.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | Frequency Response: Noise: -60 to -30 dBm (ref _ 150 ohm source) ±0.5 dB from 30 Hz to 20 kHz _ -125 dBm EIn at maximum SENSITIVIty (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.35 % THD from 30 Hz to 20 kHz at 20 dB above nomina ] operating evel or Tess _ Less than 0.1% at kHz at 20 dB above nomina 1 operating level or Tess_ Less than 0.5 % at kHz through cue channel at 20 dB above nomina ] operating level or Tess |
| **Source impedance** | 150 ohms ba lanced/unba lanced |
| **Input impedance** | 750 ohms minimum |
| **Output impedances** | 30,000 ohms baLanced (program circuits) 60,000 ohms baLanced (cue circuits) |
| **Output level** | dBm nomina 1 +25 dBm maximum (equivalent voltage 600 ohms) Input and output termina ]s designated by numbers are in phase, or Tower number of numbered pair is in phase with ower number of other numbered pair |
| **Phasing** |  |
| &nbsp;&nbsp;Input levels | (to operate Ch ON, Ch 0FF |
| &nbsp;&nbsp;Logic 0 | 0 to +13 volts Logic 1: +16 to +24 volts_ Externa] Contro] Output: (Open collector current sink.) Minimum Load impedance: 600 ohms Maximum Load current: 40 MA_ Maximum supply voltage: +24 volts. Saturated collector voltage +2 volts maximum at 40 mA Toad |

## Circuit description

From [1978 - M490A - 008.jpg](MANUALS/1978%20-%20M490A%20-%20008.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**CIRCULI DESCRIPTION**

M49OA MIC InPUt MODULE M49OA MIC InPUT MODULE Program Channel Switch 28 is CMOs dua ] flip-flop serving a $ Latch to maintain the status of 22 and 25 _ once they have been set to either the on or the OFF position 22 is CMOS ana 1og switch, serving as the active switching element of the PROGRAM channe] The contro] voltage to operate 22 is derived from the logic circuitry within the module and is coupled to 22 via CR1. to switch the channel on this control voltage is in the order of 10 vo ] ts When the contro] voltage drops to volts_ the switch will be 0FF, resulting in signa ] attenuation of more than 100 dB number of individual input functions govern the status of the dua] flip-flop 28 _ description of each input function follows: Initial Reset When power is initially applied to the system, the combination of CR9 CR10 CR11 and C40 will Pull down both clear inputs of 28 until C40 is fully charged thus ensuring that switches 22 and 25 are in the OFF position_ Booster_Amplifier Following 22 integrated circuits 23 and 24 amp] i fy the audios j gna 1 to nomina level of dBm (equivalent voltage) From the amplifier output the signa 1 is routed to the PROGRAM AssiGn switches Sw4 and Sw5 followed by the Teft and right mixing bus outputs Channel On Program Outputs Momentary operation of the CHANNEL on switch Sw9 will Produce negative going pulse at 28 pin and preset the A-section of 28 Alternatively, momentary ground closure of the EXTERNAL CHANNEL on contro] input at P2, pin N wili result in the same condition Both PROGRAM outputs P1 and P2 are designed to feed into stereo buses and each is divided into Teft and right output Operation of ASSIGNMENT SWITCHES Sw4 or SW5 wii1 result in simultaneous assignment to both Te ft and right channels of the appropriate mixing buses Once the flip-flop is &quot;preset its output at pin 15 changes from to (approximately +10 volts) _ On _ Fuithe ernore causi2the]PRoG arafeitebul?itg {ni tce CHANNEL On indicator Tamp DS3 to switch on With Q12 saturated the contro] common potential appears at the emitters of Q13 and Q14 positive base potential 1$ applied to either Q13 or Q14 depending on whether InpUt SELECTOR switch SW1 or SW2 is depressed Effectively Q13 and Q14 operate similarly to two AND gates The collectors of the two transistors represent the outputs of the ANDgates They appear at P2 pin 13 and These terminals are capab ]e of inking maximum current of 40 MA each from 24 volt source and maybe used for muting purposes Cue Channel The CUEs igna ] originates from bridging takeoff at the input of the slide attenuator Owing to the high input impedance of the CUE channe] its operation has no effect on the main PROGRAM channe] 25 represents the audio switch for the CUE channe] Similarly to 22 the contro] voltage for 25 is generated in the Logic circuitry as described further on The output of 25 is fo]owed by the booster amp] i fier 26 which in turn feeds the cue bus mixing network R101 through R104 _ 1 Control Logic The contro] voltages required to operate the PROGRAM and the CUE switch 22 switch 25 are generated with thea id of circuitry 109ic utilizing integrated circuits 27 through 210

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHdXOFFiS1RGN1U/view?resourcekey=0-p8-NmNmKlbJFo4cwdVTZfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHdXOFFiS1RGN1U&resourcekey=0-p8-NmNmKlbJFo4cwdVTZfA" width="240" alt="1978 - M490A - wbsps - module - M490A 001.jpg"></a><br><sub>1978|11 · wbsps - module - M490A 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1E0cmZOREdyMkE/view?resourcekey=0-oXaA9ZYyAoR98j_2MBEfYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1E0cmZOREdyMkE&resourcekey=0-oXaA9ZYyAoR98j_2MBEfYQ" width="240" alt="1978 - M490A - wbsps - module - M490A 002.jpg"></a><br><sub>1978|11 · wbsps - module - M490A 002</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1978|11 · wbsps - module - M490A 001_small](https://drive.google.com/file/d/0B0yR0b5T78SKZ3JVVnNHT0gtd0k/view?resourcekey=0-yx9b8hICXNlf3jmUWw1Hmw) · [1978|11 · wbsps - module - M490A 002_small](https://drive.google.com/file/d/0B0yR0b5T78SKbExqMm5JbHpIa1E/view?resourcekey=0-_LzGrFiwTnE3ZBVh7FvG7A)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeVZJUVRsWGRfZFU/view?resourcekey=0-UJuZURmh62zzS2u9BcKd9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeVZJUVRsWGRfZFU&resourcekey=0-UJuZURmh62zzS2u9BcKd9A" width="240" alt="1978 - M490A - 490-04-009 - IGNA PURPOSES FROM REMOTE EMFOCST ION' RELATED.jpg"></a><br><sub>1978|11 · 490-04-009 - IGNA PURPOSES FROM REMOTE EMFOCST ION' RELATED · <a href="MECHANICAL/1978%20-%20M490A%20-%20490-04-009%20-%20IGNA%20PURPOSES%20FROM%20REMOTE%20EMFOCST%20ION%27%20RELATED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZW5UdndSekx3OTQ/view?resourcekey=0-TsOb3ACrrMBqlS6dptNyJA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZW5UdndSekx3OTQ&resourcekey=0-TsOb3ACrrMBqlS6dptNyJA" width="240" alt="1978 - M490A - 490-04-009 - USED FOR IGNA PURPOSES FROM REMOTE OCATION.jpg"></a><br><sub>1978|11 · 490-04-009 - USED FOR IGNA PURPOSES FROM REMOTE OCATION · <a href="MECHANICAL/1978%20-%20M490A%20-%20490-04-009%20-%20USED%20FOR%20IGNA%20PURPOSES%20FROM%20REMOTE%20OCATION%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1lKHpnTICJh9KiuJpWwjL0ARMKAIf46sP/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1lKHpnTICJh9KiuJpWwjL0ARMKAIf46sP" width="240" alt="19xx - M490A - DOC - 490-03-004 - WITH WHITE EPEXT.jpg"></a><br><sub>19xx - M490A - DOC - 490-03-004 - WITH WHITE EPEXT</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmlvUmw3WHNpTkk/view?resourcekey=0-8WPulMeA27TLSLIVXltQbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmlvUmw3WHNpTkk&resourcekey=0-8WPulMeA27TLSLIVXltQbg" width="240" alt="1978 - M490A - 020 - PCB layout.jpg"></a><br><sub>1978|11 · 020 - PCB layout</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmpONlNCb3JkWG8/view?resourcekey=0-Fqppylqcsz2H76pqsmHMxA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmpONlNCb3JkWG8&resourcekey=0-Fqppylqcsz2H76pqsmHMxA" width="240" alt="1978 - M490A - 490-01-001 - MACHINE CONTROLS REVISED (2).jpg"></a><br><sub>1978|11 · 490-01-001 - MACHINE CONTROLS REVISED (2) · <a href="SCHEMATICS/1978%20-%20M490A%20-%20490-01-001%20-%20MACHINE%20CONTROLS%20REVISED%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTd1eGJ6MXEtRG8/view?resourcekey=0-4_S-sdHdEn8aqg6OwFy3SA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTd1eGJ6MXEtRG8&resourcekey=0-4_S-sdHdEn8aqg6OwFy3SA" width="240" alt="1978 - M490A - 490-01-001 - MACHINE CONTROLS REVISED.jpg"></a><br><sub>1978|11 · 490-01-001 - MACHINE CONTROLS REVISED · <a href="SCHEMATICS/1978%20-%20M490A%20-%20490-01-001%20-%20MACHINE%20CONTROLS%20REVISED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRHZ3UDJGSVlBR0k/view?resourcekey=0-CszFvl1JZ6d1_m0253yMYg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRHZ3UDJGSVlBR0k&resourcekey=0-CszFvl1JZ6d1_m0253yMYg" width="240" alt="1978 - M490A - 490-02-002 - CRII ILO IOK.jpg"></a><br><sub>1978|11 · 490-02-002 - CRII ILO IOK · <a href="SCHEMATICS/1978%20-%20M490A%20-%20490-02-002%20-%20CRII%20ILO%20IOK%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1knUDRxL4RvHFKTsjYd0jxH6wh3tzgISS/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1knUDRxL4RvHFKTsjYd0jxH6wh3tzgISS" width="240" alt="1978 - M490A - 490-02-002 - IOK SWIO CUT ZIO.jpg"></a><br><sub>1978|11 · 490-02-002 - IOK SWIO CUT ZIO · <a href="SCHEMATICS/1978%20-%20M490A%20-%20490-02-002%20-%20IOK%20SWIO%20CUT%20ZIO%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `19xx - M490A - INTEGRATED CIRCUIT DATA 74C76 DUAL J-K FLIP-FLOP WITH CLEAR AND PRESET.jpg`, `WBS M490A - Functional Diagram.jpg`, `WBS M490A - Schematic(1).jpg`, `WBS M490A - Schematic.jpg`, `WBS M490A - component layout.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHNSaFAxN1hZNE0/view?resourcekey=0-X12T3RxZSx9YqhIQiVJ2KQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHNSaFAxN1hZNE0&resourcekey=0-X12T3RxZSx9YqhIQiVJ2KQ" width="240" alt="1978 - M490A - 021 - Pin Out.jpg"></a><br><sub>1978|11 · 021 - Pin Out</sub></td></tr>
</table>

Not on Google Drive yet: `M490A - RTO-144 Connections.pdf`

## RTO-144 pinout

25 contacts, 4 contacts (P1), 22 contacts (P2). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 1 | LEFT PGRM 1 | audio | A3 + | high |
| 1 | MIC IN A | in | A1 + | high |
| 2 | LEFT PGRM 1 | audio | A3 - | high |
| 3 | RIGHT PGRM 1 | audio | A4 + | high |
| 3 | MIC IN B | in | A2 + | high |
| 4 | RIGHT PGRM 1 | audio | A4 - | high |
| 5 |  | unread |  | low |
| 6 | INSERT SEND | out | B1 + | high |
| 7 | INSERT RETURN | in | B2 + | high |
| 8 |  | unread |  | low |
| 9 |  | unread |  | low |
| 10 | NC | nc |  | high |
| 11 | IC 112 IC | other |  | high |
| 12 |  | unread |  | low |
| 13 |  | unread |  | low |
| 15 | CUE OUT , LEFT | out |  | high |
| 15 |  | unread |  | low |
| 16 | CUE OUT , LEFT | out |  | high |
| 17 |  | unread |  | low |
| 19 | NC | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | NC | nc |  | high |
| 20 | COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 |  | unread |  | low |
| 25 | V COM | ground |  | high |
| A | MIC IN A | in | A1 - | high |
| C | MIC IN B | in | A2 - | high |
| E |  | unread |  | low |
| F | INSERT SEND | out | B1 - | high |
| H | INSERT RETURN | in | B2 - | high |
| J |  | unread |  | low |
| L |  | unread |  | low |
| M |  | unread |  | low |
| N |  | unread |  | low |
| P |  | unread |  | low |
| R |  | unread |  | low |
| U |  | unread |  | low |
| V |  | unread |  | low |

**Straps:** Insert: JMP.6.7 · Insert: JMP.F.H

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclIxU1p3Z2hjRVU/view?resourcekey=0-z4x-9DGXUpHhftOE9dhxUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclIxU1p3Z2hjRVU&resourcekey=0-z4x-9DGXUpHhftOE9dhxUw" width="240" alt="1978 - M490A - 000 - Cover.jpg"></a><br><sub>1978|11 · 000 - Cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNVV0eG14TGU4YW8/view?resourcekey=0-IrnOg3goWaXDI_dQVEJwGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNVV0eG14TGU4YW8&resourcekey=0-IrnOg3goWaXDI_dQVEJwGA" width="240" alt="1978 - M490A - 003.jpg"></a><br><sub>1978|11 · 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWx4emdHZ2hKREU/view?resourcekey=0-kuCWSagmUvh8I3ZeaO_gFw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWx4emdHZ2hKREU&resourcekey=0-kuCWSagmUvh8I3ZeaO_gFw" width="240" alt="1978 - M490A - 004.jpg"></a><br><sub>1978|11 · 004</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWJweHR4TDJBRHM/view?resourcekey=0-MjaaOKaAoD5QmOZ80rlDTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWJweHR4TDJBRHM&resourcekey=0-MjaaOKaAoD5QmOZ80rlDTg" width="240" alt="1978 - M490A - 005.jpg"></a><br><sub>1978|11 · 005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0ZIMWtya3VHbDQ/view?resourcekey=0-BKGtKFFMBvPODvDJFJXHUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0ZIMWtya3VHbDQ&resourcekey=0-BKGtKFFMBvPODvDJFJXHUg" width="240" alt="1978 - M490A - 006.jpg"></a><br><sub>1978|11 · 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcV9mRlZwV0d6OXM/view?resourcekey=0-cOOJuJJcdO3IvevYrlh4zA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcV9mRlZwV0d6OXM&resourcekey=0-cOOJuJJcdO3IvevYrlh4zA" width="240" alt="1978 - M490A - 007.jpg"></a><br><sub>1978|11 · 007</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZk1CZW1RM18wWFU/view?resourcekey=0-ghkaXaOLTW3qAPRNECoS7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZk1CZW1RM18wWFU&resourcekey=0-ghkaXaOLTW3qAPRNECoS7A" width="240" alt="1978 - M490A - 008.jpg"></a><br><sub>1978|11 · 008</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEx4WjhkWmFFbFk/view?resourcekey=0-YXhVV3WrWIOEOwjwE6j1cA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEx4WjhkWmFFbFk&resourcekey=0-YXhVV3WrWIOEOwjwE6j1cA" width="240" alt="1978 - M490A - 009.jpg"></a><br><sub>1978|11 · 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbU9JdFM1dHJORzg/view?resourcekey=0-cjKueZYTwoLjPxdFDYBbLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbU9JdFM1dHJORzg&resourcekey=0-cjKueZYTwoLjPxdFDYBbLg" width="240" alt="1978 - M490A - 010.jpg"></a><br><sub>1978|11 · 010</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNW43b1pjT3U5c00/view?resourcekey=0-JHfF_ZDRGVSRLzklEI9v5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNW43b1pjT3U5c00&resourcekey=0-JHfF_ZDRGVSRLzklEI9v5Q" width="240" alt="1978 - M490A - 011.jpg"></a><br><sub>1978|11 · 011</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmdZbFFMUGRPWDQ/view?resourcekey=0-KkXCJ9zLirW7M-IxlxhIjw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmdZbFFMUGRPWDQ&resourcekey=0-KkXCJ9zLirW7M-IxlxhIjw" width="240" alt="1978 - M490A - 012.jpg"></a><br><sub>1978|11 · 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3pNaGlITFNxdFk/view?resourcekey=0-YpKaOucJPE-YWcmCjEtdQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3pNaGlITFNxdFk&resourcekey=0-YpKaOucJPE-YWcmCjEtdQg" width="240" alt="1978 - M490A - 013.jpg"></a><br><sub>1978|11 · 013</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKajB4U094TGljVVU/view?resourcekey=0-aUA0srPHE0SppRqmJtrieg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKajB4U094TGljVVU&resourcekey=0-aUA0srPHE0SppRqmJtrieg" width="240" alt="1978 - M490A - 014.jpg"></a><br><sub>1978|11 · 014</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZFBUOUpyTU1yajQ/view?resourcekey=0-ZA713wEuLeW7Rpz2IvsVBw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZFBUOUpyTU1yajQ&resourcekey=0-ZA713wEuLeW7Rpz2IvsVBw" width="240" alt="1978 - M490A - 015.jpg"></a><br><sub>1978|11 · 015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkthTDQyZElmb3M/view?resourcekey=0-6dUso-qLTBQDiaajWl2FWw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkthTDQyZElmb3M&resourcekey=0-6dUso-qLTBQDiaajWl2FWw" width="240" alt="1978 - M490A - 016.jpg"></a><br><sub>1978|11 · 016</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M490A - 490-01-001 - MACHINE CONTROLS REVISED (2).kicad_sch](KICAD/1978%20-%20M490A%20-%20490-01-001%20-%20MACHINE%20CONTROLS%20REVISED%20(2).kicad_sch)
- [1978 - M490A - 490-01-001 - MACHINE CONTROLS REVISED.kicad_sch](KICAD/1978%20-%20M490A%20-%20490-01-001%20-%20MACHINE%20CONTROLS%20REVISED.kicad_sch)
- [1978 - M490A - 490-02-002 - CRII ILO IOK.kicad_sch](KICAD/1978%20-%20M490A%20-%20490-02-002%20-%20CRII%20ILO%20IOK.kicad_sch)
- [1978 - M490A - 490-02-002 - IOK SWIO CUT ZIO.kicad_sch](KICAD/1978%20-%20M490A%20-%20490-02-002%20-%20IOK%20SWIO%20CUT%20ZIO.kicad_sch)
- [M490A.kicad_sym](KICAD/M490A.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
