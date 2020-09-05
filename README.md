# lr-hkbus

lr-hkbus is a Lightroom keyword list for categorizing Hong Kong transport images.

This keyword list provides an easier way for Hong Kong transport enthusiasts to categorize their images in Adobe Lightroom, supporting franchised bus, non-franchised bus/coach, green/red public minibus and more.

## User Guide

You can import lr-hkbus.txt to Lightroom to import all keywords for your future photo categorization.

Most images will have 1-2 keywords per vehicle, which will be the registration no./fleet no. and the route (if applicable). This means you can add more than 2 keywords if you have more than one vehicle in the image.

### Routes

All keywords for routes are stored under the keyword `"ByRoute"`. Types of routes that currently supported are shown belo:

* `AEL_Shuttle`: Airport Express Complimentary Shuttle Bus
* `CUHK`: Bus service in CUHK
  * Not including "light bus", i.e NR834
* `DB`: Discovery Bay Residential Routes
  * All routes only run in DB are listed under the keyword `DB00R`
* `GMBHK`, `GMBKN`, `GMBNT`: Green minibus routes in Hong Kong Island, Kowloon and N.T. respectively
  * All GMB routes have a prefix ("HK_", "KR_", "NR_")
* `Hire`: Contract Hire Service
* `HR`, `KR`, `NR`: Residential Routes in Hong Kong Island, Kowloon and N.T. respectively
  * Due to the enormous number of NR routes, all NR routes are then sub-classified to `NR0xx` to `NR9xx`
  * All keywords uses the offical route no. (HR, KR and NR) except 61R^, 62R^, 88R^ and 89R^
* `LRT`: Light Rail routes
* `RMBHK`, `RMBKN`, `RMBNT`: Red minibus routes in Hong Kong Island, Kowloon and N.T. respectively
  * All RMB routes are coded as "XXXYYY", with XXX and YYY representing the two destinations by a three-character code. Please refer to *Guides for contribution* for further information.
* `Rt_AES`^: Airport routes (A-), North Lantau external routes (E-, X-) and North Lantau shuttle routes (S-, X-)
  * Excluded: "Disneyland Resort" recreation routes (R-)
* `Rt_CHT`^: Cross-harbour routes (1xx, 3xx, 6xx, 9xx)
* `Rt_CTBnf`: All CTB non-franchised routes
  * Excluding residential routes
* `Rt_HKI`^: Hong Kong Island routes
* `Rt_KLN`^: Kowloon routes
* `Rt_NTE`^: New Territories East routes (7-9, 27-29, 79)
  * Included: 63R, 64P (2nd gen), 65K (before 2009), All Shatin Racecourse routes except 802/811, All MTR feeder bus in Tai Po
* `Rt_NTW`^: New Territories West routes (3-6, 23-26)
  * Included: "Disneyland Resort" recreation routes (R-), All MTR Bus routes, B1-B3 series,Y41)
* `Rt_Other`: Routes that not categorized
* `Training`: Training bus
* `Tram`: Hongkong Tramway, by destination

Keywords in types with ^ are destination-required.

Please refer to *Guides for contribution* for further information.

### Companies / Organizations

Most vehicle in this keyword list are represented by registration no., with the following exceptions:

* `CMB`
  * Fleet no. is used
* `Ferry`
  * All ferries use the name of the vessel
* `LRT` in `MTR/KCR/Tram`
  * Fleet no. is used, with "LR#" prefix
* `MTRB` in `MTR/KCR/Tram`
  * Fleet no. is used, with "M#" prefix
* `Tram` in `MTR/KCR/Tram`
  * Fleet no. is used, with "#" prefix
* `NWFB/CTB/CLP`
  * Fleet no. is used, with "#" prefix except DA, LA and VA
  
## Guides for Contribution

(TBC)

### Incomplete fleet

This is for upcoming fleets not using "forseeable" naming in the list. Mostly are KMB's new fleet since the list uses registration no. instead of fleet no.

*Please update README.MD after updating any of the following fleet.*

* KMB
  * 3AVBML
  * E6M (up to E6M71 / WW3308)
  * E6X (up to E6X134 / WW4136)
  * V6B (up to V6B156 / WV2953)