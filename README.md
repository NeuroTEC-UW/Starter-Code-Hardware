# NeuroTECH Hackathon Hardware Cheat Sheets
### EEG

- [Muse 2](#muse-2)

- [OpenBCI EEG Cap](#openbci-eeg-cap)

- [Unicorn Naked BCI](#unicorn-naked-bci)

### Neuromodulation

- [TENS 3000](#tens-3000)

### VR/AR

- [Oculus Quest 2](#oculus-quest-2)

### Other

- [FitBit](#fitbit)


&nbsp;

> # EEG


## Muse 2

| **Category** | EEG |
| --- | --- |
| **Measures** | Brain activity (through electrical signals) |
| **Summary** | Intended for real-time biofeedback during meditation, the Muse 2 records brain activity using EEG, as well as heart rate and breath data. It has seven electrodes (see [this labeled image](https://www.frontiersin.org/files/Articles/634147/fnins-15-634147-HTML/image_m/fnins-15-634147-g001.jpg) - it's for the original Muse, not the Muse 2, but the electrode placement is similar). Though its commercial purpose is for meditation, it's been used in research, as it is inexpensive but still effective enough to produce good data. Because of the location of the sensors, you may notice interference due to blinks. |
| **Components** |- Headset <br> - BLED112 Bluetooth dongle (needed for Windows or Mac) - this is a small dongle that plugs into the USB port of your laptop. Be careful not to lose the dongle! Remember to remove it from your laptop and return to the box after use. |
| **Setup Instructions** | See this [BCI workshop](https://github.com/NeuroTechX/bci-workshop/blob/master/INSTRUCTIONS.md) for setup instructions and starter code. Also see [this guide](https://github.com/synaptech-uw/docs/tree/master/Muse/muse_python).<br>When you are around other people also using the Muse, make sure you are connecting to the correct device - take note of its MAC address. |
| **Additional Resources** | [MuseLSL Starter Code](https://github.com/NeuroTEC-UW/Starter-Code-MuseLSL) [Muse 2](https://choosemuse.com/muse-2/)<br>[Research using Muse](https://choosemuse.com/muse-research/)<br>[Using Muse: Rapid Mobile Assessment of Brain Performance](https://www.frontiersin.org/articles/10.3389/fnins.2021.634147/full) |

##
&nbsp;

## OpenBCI EEG Cap

| **Category** | EEG |
| --- | --- |
| **Measures** | Brain activity (through electrical signals) |
| **Summary** | The Gelfree BCI Electrode Cap uses saline-based electrodes in a mesh cap to acquire EEG data. Recommended for people who already have some experience with BCIs. |
| **Components** |- streamlined, comfortable cap with adjustable chinstrap<br>- labelled Ag-AgCl electrodes/cables<br>- measuring utensils for saline conductive solution<br>- saline retaining Hydro-link conductive inserts<br>- cotton swabs for scalp preparation<br>- towel for mess-free clean-up<br>***Note** - this list is from the product page, check the actual box in case contents are different.* |
| **Setup Instructions** | [Gelfree Electrode Cap Guide: OpenBCI Documentation](https://docs.openbci.com/AddOns/Headwear/GelfreeElectrodeCap/) |
| **Additional Resources** | [Gelfree BCI Electrode Cap Kit Product Page](https://shop.openbci.com/collections/frontpage/products/gelfree-bci-cap-kit?variant=40785117249694)[Research that uses OpenBCI hardware (including some with electrode cap)](https://docs.openbci.com/citations/)|

##
&nbsp;


## Unicorn Naked BCI

| **Category** | EEG |
| --- | --- |
| **Measures** | Brain activity (through electrical signals) |
| **Summary** | The Unicorn Naked BCI is a flexible, do-it-yourself kit for building an EEG headset and BCI applications.Recommended for people who already have some experience with BCIs. |
| **Components** |- Unicorn Naked BCI amplifier<br>- 50x Unicorn Sticky Electrodes<br>- 8x Unicorn Hybrid EEG Electrodes (can be used wet or dry)<br>- Unicorn Bluetooth Dongle<br>- Unicorn Charging Cable<br>- 1x Unicorn Suite Hybrid Black software environment (Recorder, C API, .NET API and Dev Tools applications)|
| **Setup Instructions** | No setup instruction aviliable. [Unicorn github repo](https://github.com/unicorn-bi/) |
| **Additional Resources** | [Unicorn Naked BCI for Open Source Enthusiasts: Unicorn Brain Interface](https://www.unicorn-bi.com/naked-bci/)|

##
&nbsp;

> # Neuromodulation

## TENS 3000

| **Category** | Nerve Stimulation |
| --- | --- |
| **Result** | Stimulates nerves using transcutaneously applied current(patches on the skin) |
| **Summary** | The TENS(Transcutaneous Electrical Nerve Stimulation) 3000 is a nerve stimulation device that has traditionally been used as a non-invasive, drug-free method of treating pain. |
| **Components** |- Case<br>- TENS Unit<br>- Batteries<br>- Electrode Wires + 4 Electrodes|
| **Setup Instructions** | **IMPORTANT: Read the instructions and warnings carefully!** Do not place the electrodes anywhere the current could pass through your heart or brain (for example, do not place them on opposite sides of your body). Do not apply TENS over neck region(carotid arteries), heart region, or over brain area. TENS is not recommended for people with known heart disease or implanted electronic device without physical evaluation of risk.<br>1. Straight connector of wire connects to electrode patch. Bent end of wire connects to TENS unit.<br>2. For pain management, put area of pain in between all electrodes used. [video instruction](https://www.youtube.com/watch?v=h-fcSPozMxQ) ![](/tens_spec_sheet.png)<br>Also see the operating manual linked in additional resources. |
| **Additional Resources** | [https://www.tenspros.com/assets/images/manuals/TENS-3000-dt3002-Manual.pdf](https://www.tenspros.com/assets/images/manuals/TENS-3000-dt3002-Manual.pdf)[https://www.youtube.com/watch?v=EB3d57MXtG8](https://www.youtube.com/watch?v=EB3d57MXtG8) |

##
&nbsp;

> # VR/AR

## Oculus Quest 2

| **Category** | VR |
| --- | --- |
| **Input** | Accelerometer, gyroscope |
| **Summary** | The Oculus Quest 2 is a VR headset from Meta with two touch controllers. |
| **Components** |- VR Headset<br>- Two Touch Controllers<br>- Charging Cable<br>- Two AA Batteries<br>- Power Adapter<br>- Glasses Spacer|
| **Setup Instructions** | [Get Started Developing for the Oculus Quest Platform](https://developer.oculus.com/quest/) |
| **Additional Resources** | [Oculus Quest 2 Product Page](https://www.oculus.com/quest-2/) |

##

&nbsp;

> # Other

## FitBit

| **Category** | Health tracker |
| --- | --- |
| **Measures** | Activity;Fitness;Heart rate;Nutrition;Sleep |
| **Summary** | The Fitbit is a health tracker worn on the wrist, and collects data from user inputs and sensors. The data can be accessed with the Fitbit web API. |
| **Components** | - Fitbit<br>- Charger |
| **Setup Instructions** | [FitBit developer guide](https://dev.fitbit.com/build/reference/web-api/developer-guide/getting-started/) |
| **Additional Resources** | [Documentation](https://dev.fitbit.com/build/reference/web-api/)|
