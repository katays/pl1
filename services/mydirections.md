# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?departure_time=now&mode=bicycling&origin=place_id:ChIJ5ejd3SXL1IkRirF5IsDyZe0&destination=place_id:ChIJfwMDtPHL1IkRKQvpyXpKHH4&waypoints=place_id:ChIJvVikcQLL1IkRafuhKhOaN98&waypoints=place_id:ChIJlQx0rVXK1IkRW1YiBCI5e74 &key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ5ejd3SXL1IkRirF5IsDyZe0",
         "types" : [ "establishment", "natural_feature" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJvVikcQLL1IkRafuhKhOaN98",
         "types" : [ "establishment", "natural_feature" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJfwMDtPHL1IkRKQvpyXpKHH4",
         "types" : [
            "establishment",
            "natural_feature",
            "point_of_interest",
            "tourist_attraction"
         ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 43.6630792,
               "lng" : -79.3089777
            },
            "southwest" : {
               "lat" : 43.63688339999999,
               "lng" : -79.36778699999999
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "2.8 km",
                  "value" : 2824
               },
               "duration" : {
                  "text" : "10 mins",
                  "value" : 577
               },
               "end_address" : "Cherry Beach, Ontario, Canada",
               "end_location" : {
                  "lat" : 43.63688339999999,
                  "lng" : -79.34484689999999
               },
               "start_address" : "Sugar Beach, Old Toronto, ON, Canada",
               "start_location" : {
                  "lat" : 43.6438203,
                  "lng" : -79.36744689999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "66 m",
                        "value" : 66
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 43.6443599,
                        "lng" : -79.36778699999999
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e on \u003cb\u003eDockside Dr\u003c/b\u003e toward \u003cb\u003eQueens Quay E\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{dkiGpmlcNCBCBIFu@^c@R"
                     },
                     "start_location" : {
                        "lat" : 43.6438203,
                        "lng" : -79.36744689999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 524
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 122
                     },
                     "end_location" : {
                        "lat" : 43.6464299,
                        "lng" : -79.3619377
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eQueens Quay E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ghkiGtolcNSy@Mi@YeAYmAeAcEI[COQo@Om@g@oBKc@[kAe@kBQw@UcAI[Qq@GQCICKGM"
                     },
                     "start_location" : {
                        "lat" : 43.6443599,
                        "lng" : -79.36778699999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 43.6463158,
                        "lng" : -79.36183419999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMerchants' Wharf\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "eukiGbkkcNTU"
                     },
                     "start_location" : {
                        "lat" : 43.6464299,
                        "lng" : -79.3619377
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 732
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 132
                     },
                     "end_location" : {
                        "lat" : 43.64795580000001,
                        "lng" : -79.35471
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMartin Goodman Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWaterfront Trail\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Martin Goodman Trail\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "otkiGljkcNK]CGEGEESKUKwAi@y@[CACCIGKGIKAACECGEKKYQw@c@gBWkAUaAGc@Ki@Qy@[wAQs@Ow@Me@EYAGAKAM?O?K?M@IBYBYFa@DUFSFSJQLSLST[LSXi@JOHOJYHS?C?C@C?A?EEK"
                     },
                     "start_location" : {
                        "lat" : 43.6463158,
                        "lng" : -79.36183419999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.4 km",
                        "value" : 1418
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 299
                     },
                     "end_location" : {
                        "lat" : 43.6374147,
                        "lng" : -79.34490170000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCherry St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w~kiG|}icNFIDGBEBGBCBEHGDELQLIJI^YDCVSFEVSNKNKNM`Aw@bBoARCXQ\\UZS\\[tAeA`@m@^YNMVSbGqENO~AmAd@]t@k@HGd@_@VUVWTYJIPSPSZ[HKtA{AZ]Z]x@}@FGVYf@k@zBiCNKBCDCDEDETWTWjCwCfBkB"
                     },
                     "start_location" : {
                        "lat" : 43.64795580000001,
                        "lng" : -79.35471
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "48 m",
                        "value" : 48
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 7
                     },
                     "end_location" : {
                        "lat" : 43.6370309,
                        "lng" : -79.3450053
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "y|iiGr`hcNBFBBBDBBB@B@@ABABABA@AHABAB@D@JD"
                     },
                     "start_location" : {
                        "lat" : 43.6374147,
                        "lng" : -79.34490170000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "21 m",
                        "value" : 21
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 43.63688339999999,
                        "lng" : -79.34484689999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mziiGhahcNTYFE"
                     },
                     "start_location" : {
                        "lat" : 43.6370309,
                        "lng" : -79.3450053
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "5.3 km",
                  "value" : 5336
               },
               "duration" : {
                  "text" : "16 mins",
                  "value" : 945
               },
               "end_address" : "1675 Lake Shore Blvd E, Toronto, ON M4L 3W6, Canada",
               "end_location" : {
                  "lat" : 43.6630735,
                  "lng" : -79.3092714
               },
               "start_address" : "Cherry Beach, Ontario, Canada",
               "start_location" : {
                  "lat" : 43.63688339999999,
                  "lng" : -79.34484689999999
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "21 m",
                        "value" : 21
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 43.6370309,
                        "lng" : -79.3450053
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e toward \u003cb\u003eMartin Goodman Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "oyiiGh`hcNGDUX"
                     },
                     "start_location" : {
                        "lat" : 43.63688339999999,
                        "lng" : -79.34484689999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 111
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 43.6373811,
                        "lng" : -79.3441945
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eCherry St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mziiGhahcNKEEACAC@I@A@C@C@C@A@CACACCCECCCGIQEICG?G?G?I@MBIBKBMBMFO"
                     },
                     "start_location" : {
                        "lat" : 43.6370309,
                        "lng" : -79.3450053
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 299
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 55
                     },
                     "end_location" : {
                        "lat" : 43.6392621,
                        "lng" : -79.3420486
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCherry St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s|iiGd|gcNIOCMAGAKAI?IAG?I?G?G?IAM?ECIEMGGIK]][Ye@e@a@a@gAcAm@i@o@c@CBA@A?A@AB?@CDA@A@C?C?"
                     },
                     "start_location" : {
                        "lat" : 43.6373811,
                        "lng" : -79.3441945
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 km",
                        "value" : 1580
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 278
                     },
                     "end_location" : {
                        "lat" : 43.648127,
                        "lng" : -79.3284584
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMartin Goodman Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "khjiGxngcNAACAEGKIEECCAA?CAA?EAE?E?E?I@E?G?E@GAE?GCGAICGAGCICECE?EAC?C?C?C?CAGO]GQEGAEACAEAC?CAEAG?GAGAO?EAE?GAE?GAGAG?EAEAE?ACGCICGCKMWIQYi@O[QWMMc@o@OQYa@_@g@c@i@o@y@OSY]_@e@_@g@W[MOGIKQCKGMIUKOCCEECAECMGe@YOKMMGGKKIMIKCGESCSCM?G?G@IDKFMBG@G@G?E@S?W?QAYCOGOo@_A}@cAIKECCCGAGAQAwADO@E?EAEAQEk@M]IICCACACCCGIQGKEIEGIIKKEGEIEIIQO[CGAGAI?GAEAEAGEGGMIQIOO]KUKUEKO[Ua@ACWe@k@cAGKMOIKCCCECICIAG?O?K?A?EAEEICEIKMOIKEOGUCMCIKOMQGKCGCG?CAEKYEIMQGGKKEIEGGI{@mB"
                     },
                     "start_location" : {
                        "lat" : 43.6392621,
                        "lng" : -79.3420486
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7 m",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.6481871,
                        "lng" : -79.3284967
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eWaterfront Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y_liGzydcNKF"
                     },
                     "start_location" : {
                        "lat" : 43.648127,
                        "lng" : -79.3284584
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 773
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 138
                     },
                     "end_location" : {
                        "lat" : 43.6523656,
                        "lng" : -79.32292950000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eUnwin Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "e`liGbzdcNi@iBe@eBEGCGEECCCAECEAE?C?C?E?GDeExCEDGBE?E@GAEEEEEIEKeIyVg@yAeA{C"
                     },
                     "start_location" : {
                        "lat" : 43.6481871,
                        "lng" : -79.3284967
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 208
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 34
                     },
                     "end_location" : {
                        "lat" : 43.6539847,
                        "lng" : -79.32423539999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLeslie St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "izliGhwccNqDrCqA~@]V_@X"
                     },
                     "start_location" : {
                        "lat" : 43.6523656,
                        "lng" : -79.32292950000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "9 m",
                        "value" : 9
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 43.6540216,
                        "lng" : -79.3241374
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eS Service Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kdmiGn_dcNGS"
                     },
                     "start_location" : {
                        "lat" : 43.6539847,
                        "lng" : -79.32423539999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 446
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 78
                     },
                     "end_location" : {
                        "lat" : 43.6575092,
                        "lng" : -79.3268168
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMartin Goodman Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sdmiGz~ccNMHgAz@yAfAC@_BnASNSNs@h@gAz@[VWREBC@A@C?C?C@EAGHGDC?C@I?MDo@b@eAx@IF"
                     },
                     "start_location" : {
                        "lat" : 43.6540216,
                        "lng" : -79.3241374
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2 m",
                        "value" : 2
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 43.6575181,
                        "lng" : -79.3267953
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mzmiGrodcNAC"
                     },
                     "start_location" : {
                        "lat" : 43.6575092,
                        "lng" : -79.3268168
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.5 km",
                        "value" : 1499
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 263
                     },
                     "end_location" : {
                        "lat" : 43.6616299,
                        "lng" : -79.31250319999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ozmiGnodcNMFEBKBKBI?K?E?K@IBGBMHKJEFGHINELGLINIJQLQHA?G@EAGAAACACCEGCAGEGAE?C@EACACACEAGAGAIAGCCCGAGCCCGGg@C_@EUKc@Ke@EMAKAIAU?[AO?GAE?CGQGWCKAOG]M}@OcAAEGi@E[SkAWyAAGAGEIO]EMEIAGGUGc@O}@WeBWgBU}AMaAESQkAUiBM_AE_@M}@OeAMcAGc@CUCQ?KAQ?S?KAG?AEIISGSEGIk@E[E]McAMgAK_AMgACOAG?GBMFMPYN]J[DQBQBW@O?K?YAUCQ?ACMGSCQEOAO?O?KBMDQFIPGJIFEBE?GCECCEC"
                     },
                     "start_location" : {
                        "lat" : 43.6575181,
                        "lng" : -79.3267953
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "70 m",
                        "value" : 70
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 43.6615283,
                        "lng" : -79.31170209999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMartin Goodman Trail\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "etniGbvacNGSAGAKAGB[L_@@EDUFW"
                     },
                     "start_location" : {
                        "lat" : 43.6616299,
                        "lng" : -79.31250319999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 251
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 43.6625975,
                        "lng" : -79.3089777
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eMartin Goodman Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qsniGbqacNEMUe@Ug@Qg@Ee@AQIc@i@sBUeAQi@Uk@Wo@"
                     },
                     "start_location" : {
                        "lat" : 43.6615283,
                        "lng" : -79.31170209999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "58 m",
                        "value" : 58
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 43.6630792,
                        "lng" : -79.3092475
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gzniGb`acNw@^g@T"
                     },
                     "start_location" : {
                        "lat" : 43.6625975,
                        "lng" : -79.3089777
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2 m",
                        "value" : 2
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 0
                     },
                     "end_location" : {
                        "lat" : 43.6630735,
                        "lng" : -79.3092714
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "g}niGxaacN@B"
                     },
                     "start_location" : {
                        "lat" : 43.6630792,
                        "lng" : -79.3092475
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "{dkiGpmlcNQNyAr@a@cBcCsJe@mByDuOWu@TUK]IOYQmBu@kAi@[[IS]qA{@sD]eBkAoFe@_CCu@HkALw@Ng@|@uA|@}ATu@@KEKFIHMTYRWXSdAw@fAy@dDgCRCXQx@i@rBaB`@m@^Yf@a@xKmI|BiBxEgFxBaCjE{ENM|DmEfBkBBFFHFDD?LGLCHBJDTYFEGDUXKEICSFMBOOWk@?O@WNq@FOIOEUEg@?c@ASIWkAkAgAgAuBmBo@c@CBC@GLKBKKWUCQ@w@Ia@M]AQ?GQe@Qc@ESIaAGk@Oe@aAoBsAgBmCmDiB_Ce@k@S[KYUe@SOs@a@]YSSSYQ}@?OFUJUBO@cAEi@w@oAqAwAOCiBBa@AeBa@OO]o@UUKQc@_AE_@Qc@o@uAw@_BmAyB_@e@GSAWAYIOW[O[Kc@e@w@IYQc@UY_@g@{@mBKFoAoESYUGG?MDkE~CMBM?KKyJiZeA{CqDrCoBvA_@XGSuAdAqEhDkDlCc@ZQ?ONG@WDo@b@oA`AACMFQFUBQ?UDULQR_@t@SZQLSHM?QIIIOGSAGGCOK]EKCGGg@Iu@WiAGYC_@Cy@Sy@g@oDc@wCa@sB]}@Oy@g@cDaA{G{@uGs@kFIeAAi@]y@c@iDk@_FAOJ[`@w@Pm@HeAEcAUcAA_@BYL[\\QJKCMIGI[CSB[L_@F[FWEMk@mAQg@Ee@Ku@_AyDg@uAWo@w@^g@T@B"
         },
         "summary" : "Martin Goodman Trail and Cherry St",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : [ 0 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
