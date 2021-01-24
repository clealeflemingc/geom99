**Weel 1 - DirectionsAPI Example (JSON Return)**
#From Zion National Park, Utah
#To Las Vegas, Nevada
#via bicycle

##URL
https://maps.googleapis.com/maps/api/directions/json?origin=Zion+National+Park&destination=Las+Vegas&mode=bicycling&key=AIzaSyBOUj57MCaYkCLM6j954ePfTXqgS5Td0ew

##Valid Response from JSON
<!--
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ2fhEiNDqyoAR9VY2qhU6Lnw",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ0X31pIK3voARo3mz1ebVzDo",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 37.2265992,
               "lng" : -112.9884458
            },
            "southwest" : {
               "lat" : 36.16937619999999,
               "lng" : -115.1399596
            }
         },
         "copyrights" : "Map data ©2021 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "181 mi",
                  "value" : 290509
               },
               "duration" : {
                  "text" : "15 hours 11 mins",
                  "value" : 54668
               },
               "end_address" : "Las Vegas, NV, USA",
               "end_location" : {
                  "lat" : 36.1697502,
                  "lng" : -115.1399596
               },
               "start_address" : "Zion National Park, Utah, USA",
               "start_location" : {
                  "lat" : 37.2017725,
                  "lng" : -112.9884458
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "20.3 mi",
                        "value" : 32645
                     },
                     "duration" : {
                        "text" : "1 hour 47 mins",
                        "value" : 6405
                     },
                     "end_location" : {
                        "lat" : 37.2108566,
                        "lng" : -113.2721849
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003eUT-9 W\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eToll road\u003c/div\u003e",
                     "polyline" : {
                        "points" : "a~`bFx`spTJDXJh@TFBB@f@LTHRJB?n@d@ZZJPLRBFPd@DHL\\JVLR^b@`@Zt@b@x@h@~@j@JDRLr@^d@XZRn@^NJRJPJDBFDRH\\R`@RPJd@Zf@^TPB@TLVJF@LBTB`@BfAJdALL@x@LJD^Fv@LDBj@HXHZDD@XDrAP\\H~@LB@v@Pl@RNDXNVLb@XpB|An@h@HF|@t@@?fA|@b@d@NPZ`@BFRZN\\@DVr@JZJd@Jf@Jv@Fr@NhBRxBX`DT~BBRF\\JXFLLPLNNHJHNJPFLH`Bx@bAd@bAf@`Bt@~E|BLFfBv@bBt@z@`@ZPZNb@VHDXPb@ZPNRRZZPTTZ@Bl@~@T^V`@LRVd@NPNR\\^PLNLVLVL`@PNFPHVL\\R\\Tp@f@r@f@h@`@bAt@fBrAvCzBxB`Bh@`@PNZVVTTRh@f@VTzAtAtApAtBpBRR|@z@zBjBhEpD^VNJPJ@?RH`@N\\F\\Dh@DfAFX@|@DlAA^Ar@GFA~AW^GLAJATAPAR?ZA^?J@F?lAHT@`@DfALPBr@Jv@Jh@J|@Vl@X@?^TPHl@b@tDpClBvAHHVRLNJLJPT\\b@bAl@rAVf@\\j@JNRTJJPN\\RPJB@PFzDhAZNVNTRJJJNHNDLDH?@DLDP?FBN@R@b@@P@xABhC?H?^?RATADANGZIXITGLKPOT[\\STUP_@Xi@`@[Tq@h@EDIFQR?@MNINUf@]hAABK^GVGVIh@E^AN?@?V@V@XBPD\\Lj@Nj@L^DJHXXr@@BP^Td@Rb@HPDJ`AnBVd@?@d@r@j@t@RTNNJLnAtAZ^DFNZFNHR?@BJDRBTBT?H@D?R?R?LAJAPIf@ABCNKT?@GPKRQ^ABUb@Sd@KPGRCFIXADCFEVALANAJ?JAT?V?@@VBpA@ZFtAB~@?N?RAPARATEZCRKf@QhAIf@CZCT?LAR?J@\\@l@BtC@hA@pBJtJD`FF`IPpRBtDD~E@`BDhC@nA@hA?nA?hAE~CG`BCn@GbBIjAIfAMpAKlAAJMbAAFYrBId@Kj@UlAS~@_@vAK^CHYdAc@nAYz@o@|Ag@nAqAjCi@~@a@p@m@|@uAnBe@l@_BrBa@d@u@~@kCbDg@h@WXY\\[`@qBfCaD|D]`@g@l@mBbC]b@q@z@]d@MPU^OXKPQ^EJEHO\\KXKZOd@Mb@IVIZKh@ERG^AFStAI|@Ex@GhB?lABfAdAhSd@vI@ZJrBBbA?LB|@?z@@lA?dB?BEtBCx@An@KnBQfCANKjAKbAm@|Fk@zEOzASlBe@dEGj@_@nDCT_@rDIpACt@Cv@A|@@~A@Z@\\Fx@F|@B\\BJD\\BPHh@P|@^`B^nAN`@BJJXzBrGPd@~BzGtB~Ft@xBn@tB`@fBRjAJr@Fx@Dx@B~@?rAAz@GtAIx@Kv@ETMv@WfAW|@a@fAqAjCcFfJA@}C|FoBfDSd@e@`Ai@pAU~@Kf@O`AIb@AFUtACRGTg@fCK^M^CFSd@O^Yf@Wd@U\\EDQXA@CDUTEDEDONEDUTEDGDUPYREBCBSJGBYNEBKFMDe@PiBb@[HG@ODKBE@[HEB[FGBWFIDYLEBA?WNEBGBWN_@ROHIFEBWRC@A@UVEDCBORED[`@U^QV?@EFOZEFIPCHCHM\\CFSh@]rAGZAHI`@AHGZGz@ABCf@CXS~GCtAMpAAHALCRAHKn@SdAOr@Mh@UdAk@`DWzBSbCWbEK|AAHAHEVAHG^?@CHI\\[xAo@|BOh@Of@Of@y@vCOf@cAlDm@xBOf@cB`GaAfD_AlCg@dA?@MV[l@ABOR]j@QTu@`A}@|@SRKJyBtBeFfFIJQRGHSRGHk@p@EDABQVEH]h@}AxBQTGHW`@QTEFA@wBvCEFqB|BUT_Az@URSP]Ze@^OLk@b@oA`Ag@`@_@VqAbAuAhAg@`@w@l@o@h@]ZEBMNMLGHQRKJMPIJORA?ADOPU\\GJ?@IJKRA@OXCFA@U`@?@Q\\e@~@O`@[v@KZCJCJIVMl@GXGXG\\Ib@E\\Eb@Eb@Ef@?@Cx@Cj@?`@At@?zA?j@@b@@d@HbG@P?X?b@A`@Ah@Ad@Cd@Cd@Ed@E\\Mn@ShAEVEPKj@Kh@{@tEWvAUlAQhAIj@Gd@?DGd@Gj@Ef@I`AGhAIdBEt@G`AC\\E^E^EZGl@CLCRIh@Mp@QbAG`@Kj@A@a@zBm@hDa@`CKj@ERERERGTIb@Oh@Mh@Oh@Qj@Od@A??@GRGNA@M^Uj@Qd@Qd@ABSd@Ob@A@Sd@CHe@jAgAnCSd@Qf@oBdFe@lAu@lBe@jACFSd@Qd@Sd@gAnCqBdFSd@Qf@oBlF[z@Un@[bAUv@On@Qt@Id@Kr@Kt@CPMjAGn@?JC`@AZAj@Aj@?^?X?x@Bp@?@@j@Bv@@`@Bj@FpANzD@NJdCFjBHpB@RJ|CBz@BhABbA@`A@n@?T@V@dA?R@d@?F?l@@pB?fG?`D?zDAl@An@?\\IjGA|@C~@EfAGxACb@?FEl@Cj@SpD?FM~BIvAUfEOdCQlDKtBMzBg@dJa@rHSzDGpAs@|MWlFYpFa@rHg@jIGnAEt@WlEk@rKQpDMzBOdCa@xH]jGe@dJEj@u@jNCl@AJGtAYjFKtBGdAIbAEd@ANGt@In@Kx@Kj@Mv@I^If@Ib@eA~E}@jEId@yAdHaArEKh@Kh@YrAMh@_ArEGX[|AYpAWbAI\\ADSl@Od@Uh@Qb@MVOZKRW`@]h@a@h@_@d@_@`@WVg@d@gB`B]ZsBhBqChC]ZaHjGm@j@mD`D}BtBk@f@_@Zw@j@g@Ze@XWJi@TUH]Na@L]H}@P{AZI@gATa@Hg@H_ARqAVcB\\_AP{AZe@HeB\\aCd@c@HcATODm@Tk@Vc@TCBe@^YXKLIHY^?@U`@OZEHIRGPIRUr@I`@GZCPEZGp@Ab@Af@?\\?TBp@Bp@Fj@Jp@Nt@Tr@Vn@FHTb@Zf@`@d@f@b@b@X^TTJXJRH@?^Hn@J`@Bl@Bj@?^?RAPCp@Oh@Mx@QZGj@GZAh@AZBj@Df@HZHp@V\\NRJRL^Z\\\\BD`@f@dAvAl@z@BBr@~@r@`AfChDbBxBxAnBbAvAj@x@PTPVRTTR^VTJVHd@JL@L?TA~@C^At@CvAG^CfCKf@ANAX?\\?V@R@VB`@HJBPDZHTJ\\PXPZTPNXVRRRTj@z@^t@HRJVPd@J`@H\\Jj@BT@ND`@@N@D@b@@h@@jA@j@ApB?F?l@?j@?r@@pB@lD?J@nA?r@?nD"
                     },
                     "start_location" : {
                        "lat" : 37.2017725,
                        "lng" : -112.9884458
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.6 mi",
                        "value" : 2648
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 493
                     },
                     "end_location" : {
                        "lat" : 37.1881175,
                        "lng" : -113.2789898
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eUT-9 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eN State St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{vbbFbnjrTnB@T?`B?zEGpC?tA?z@AvE?pDAtE?bDAf@?`BBh@Bh@F\\DZD\\FfAXjDlAtEfBhG~BdC`ArJpDrCbA~An@`Bl@bBn@dA\\fBj@jEtATXDDB@BBzEtBhC`AD@D?H@ZBdAb@^RZN^Tx@f@FV"
                     },
                     "start_location" : {
                        "lat" : 37.2108566,
                        "lng" : -113.2721849
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 282
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 79
                     },
                     "end_location" : {
                        "lat" : 37.18814020000001,
                        "lng" : -113.2821623
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE 800 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wh~aFtxkrTCLAJ?P?`@?rD?j@?l@?J?`@@v@?vD"
                     },
                     "start_location" : {
                        "lat" : 37.1881175,
                        "lng" : -113.2789898
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 267
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 76
                     },
                     "end_location" : {
                        "lat" : 37.1857425,
                        "lng" : -113.2821843
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN 325 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{h~aFnllrTfA@fA?zF@b@?n@?"
                     },
                     "start_location" : {
                        "lat" : 37.18814020000001,
                        "lng" : -113.2821623
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "443 ft",
                        "value" : 135
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 37.1853512,
                        "lng" : -113.2835394
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e600 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{y}aFrllrTBbB@^BZBVFPBHFHHJHJVX"
                     },
                     "start_location" : {
                        "lat" : 37.1857425,
                        "lng" : -113.2821843
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 425
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 96
                     },
                     "end_location" : {
                        "lat" : 37.1856757,
                        "lng" : -113.2882471
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003e600 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mw}aFbulrTWh@KZENGVCRCVCPAX?fCAl@?l@?j@?\\?tB?`F?@?b@?z@"
                     },
                     "start_location" : {
                        "lat" : 37.1853512,
                        "lng" : -113.2835394
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 846
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 121
                     },
                     "end_location" : {
                        "lat" : 37.1780736,
                        "lng" : -113.2881144
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN Main St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "oy}aFprmrTR@fAARAtB?z@An@?rD?dB?b@A|BAvC?dHGlEGvAC"
                     },
                     "start_location" : {
                        "lat" : 37.1856757,
                        "lng" : -113.2882471
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 877
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 163
                     },
                     "end_location" : {
                        "lat" : 37.1780059,
                        "lng" : -113.2980151
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW 100 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}i|aFtqmrT?xJ@zDD|D?bC?tF?dB?pABhDAxAAhB@fA?j@@tD"
                     },
                     "start_location" : {
                        "lat" : 37.1780736,
                        "lng" : -113.2881144
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 165
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 37.176526,
                        "lng" : -113.2980368
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN 520 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qi|aFroorTb@?jB@jB?j@@"
                     },
                     "start_location" : {
                        "lat" : 37.1780059,
                        "lng" : -113.2980151
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.1 mi",
                        "value" : 13052
                     },
                     "duration" : {
                        "text" : "41 mins",
                        "value" : 2445
                     },
                     "end_location" : {
                        "lat" : 37.16044249999999,
                        "lng" : -113.4355128
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW State St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by O'Reilly Auto Parts (on the left in 0.3&nbsp;mi)\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "i`|aFvoorT@bB?fB?p@@zA?~C?bB?R?~B?@@dA?D?dA?L?nA?p@?~C?rB@x@@`K?|C?hAG`@?D?F?~@?pC?`A?f@?V?|B@hA?pCHN@dC?~C@dC?zA?j@@nG?tC@fC?|B?dB@zC?j@?l@?nC@fE?~A?nE@|@?fC@rD@dC?pJ?fD@v@?dE@x@?hF?z@@T?p@?^?dB@xA?j@@~@B`ADl@@\\F~@Fv@JbA@BJz@N`AJl@VnA@FRz@Jf@VbAn@nCjA`FVfA@F`@bBv@dDZpALj@Lf@T~@R|@BJH\\H\\BHJd@Nr@DTLf@PdAJp@@HHn@DXNtAH~ADh@@f@@XBz@@dA?dAAvAAhA?f@Az@C~C?n@@|@@l@Bx@Bf@Dp@F|@RjBNbANhAn@dEzAfK~@rGbBnLV~An@nEh@rDjAfIb@xCn@jEvB|NH`@\\bCZnB?BHf@RtA@D`@tCl@~Dn@rEH`@LbAJt@`ApGrAvITdBr@pEp@xEJh@Fb@NbAPfA?@PlAFZRpANfAV~ATxAL`ABLDZJr@Fb@Hf@@@TtA@BAVNj@FVPp@HV?@^dA^dA^|@~@nBTb@\\p@Vb@pCdEv@nA\\f@n@`A\\f@JTXj@Vl@Rj@Tr@XpAP~@DXBZFt@Bh@?@Bp@?f@@XAh@Cn@Ah@G~@E\\G`@Ib@Kh@]rAMb@CHOZIT_@v@s@xAcBbDKT[f@_@h@W\\GHORA@ONOLc@\\s@d@i@\\w@f@y@h@mAv@iAv@mAx@eA|@c@b@]`@SXKJORMTMRi@~@g@bAWl@Ul@IXA?[fAQt@Mp@Mn@Kp@G`@Gh@C\\ARCh@C`@Ev@?t@?j@FhIBfDHtG@R?d@HR@xAHdIBjB@jABjCBdB?JBj@Bv@Bv@FhALzAHlA@@LnAR`BLz@N`APdA\\fBd@vBNj@f@hBVx@FRZ~@Rl@LZRf@b@dATh@f@fA|@fBf@|@b@t@d@x@rCvExAdCb@t@n@jAZj@Td@j@nAf@rAt@zBFTHVZjAZvANt@V|AZjCLfAt@pHr@bHJz@XzC^pDd@nET`C"
                     },
                     "start_location" : {
                        "lat" : 37.176526,
                        "lng" : -113.2980368
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.6 mi",
                        "value" : 5758
                     },
                     "duration" : {
                        "text" : "17 mins",
                        "value" : 1043
                     },
                     "end_location" : {
                        "lat" : 37.1313768,
                        "lng" : -113.4853909
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003e6300 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTelegraph St\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Telegraph St\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w{xaF|jjsTfAFl@BJ@v@B|@Fj@HTFXHTFZLRH\\NRLB@PLf@^b@^NPf@j@h@x@^t@JTRh@JZL`@HZH\\Jj@Hn@Ht@H`ALvADT@DD^F`@Jb@FVHVJ`@Rh@N^BHNXFLNTNXNRPTBD\\`@j@n@NL~@`A^`@LLRTl@v@BBzB|CzAdC?@dBvCv@pAV^\\f@@@\\`@b@d@b@d@XTZXj@`@`@XZPZNNHPHD@FBPFl@Pz@VTF|@\\PHVN`@VHFXVTTJJLPJJNVPVLVJT@?DLLVl@|Af@nAd@jAHPJRFLHLNTDF`@j@|@dAt@|@t@|@rBdCGBpAxAJJLP^`@fAtA^j@d@x@Vl@\\~@Z~AT~@`@xAf@nBXdAt@nCrA|Ep@`CZhANl@hA`E@@dAvDDPZhAV~@Rj@FPFPN\\N\\Zf@p@hAf@r@n@bAVj@Tf@Pl@Nh@Pt@Pr@^zAFVHZJd@Lj@H^BLJh@Fl@F~@@TNdCTrD@XFbAFt@Jp@Lf@FTFNPf@Vh@Tb@fAvA\\d@f@n@R`@Xl@P`@JZNl@Rx@T`BNfAb@fDF`@Hf@Nj@Pf@?@Tj@Vd@PXLLJN\\^dBtApA`AfA|@v@p@r@r@n@v@`@h@JNb@p@Tb@HPHRLXL\\DF\\dATr@L`@Lj@H`@FVJp@Fd@BND\\Fh@F|@Dx@FzCHnC@Z"
                     },
                     "start_location" : {
                        "lat" : 37.16044249999999,
                        "lng" : -113.4355128
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 mi",
                        "value" : 958
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 194
                     },
                     "end_location" : {
                        "lat" : 37.1240133,
                        "lng" : -113.4850877
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eWashington Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cfsaFtbtsT^?b@UNGp@?D@tBTp@Gf@[@?l@SLSJOXg@FMTe@Ha@@EL[TYTWTa@LMZQHCPINAFATCFAPCXKFCNIT?RHVJPL^RVLH@D@XDB?T@HEHIFKHGHAh@A\\@@?NBJDZf@j@\\j@Vd@ZRVT`@LLTLB@t@l@\\\\VTHD"
                     },
                     "start_location" : {
                        "lat" : 37.1313768,
                        "lng" : -113.4853909
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 mi",
                        "value" : 4211
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 760
                     },
                     "end_location" : {
                        "lat" : 37.1112154,
                        "lng" : -113.5209982
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVirgin River Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "axqaFx`tsTe@h@CL?J@LBJFJ@@LFt@N@?ZHNJLJHTDPBXAXAHi@fBQ`@EHIHK^CT?n@Ov@Mr@E`@A?e@~BGv@Uz@CHAD[lBChAEZShBIhC?V@dBA^?HFnA?@RxBf@tAPj@FNPh@\\f@BFJLd@d@NNNPFNBJDLXhAN`@DJHPz@fAn@z@|AzANPrAtAH@D?FADCFCFCHOTs@BCBA@?@ABAJ?F@JDPHHDBBVXf@h@HFDDB?DFFDFLRb@@@n@j@bBxAXVz@r@F@H@HBDD@?HHj@n@b@^\\Xp@n@VTBDFLJ^FNFL@BJLXPZNRJD@RJZRLJJHPNBB@?\\k@BABCBAFA@?D@RP?@VR@D?@?DADADQXGL?B?FBDBBBB^HHFFDLHJHFBH@J?J?NAH@RF\\R`@VPNJRJNBBTP@?bA`@^Lf@LFDFDFLFNJ^Pf@Zr@HNJRJPBLBPBR@R@JHRDR@F@X?P@RBTBVB^?V?B?RCVE^Gn@AFAPA`@?`@A^@P?JDn@Dl@@LAHGPCJGN?DCXAl@@VBVH\\@BTv@L^Vh@NTPZDHBFHd@Fb@@@Jl@NdABX@V@VAZ?BCn@@`A@T?FBFDHDFTPLJBD@B@DBRFj@Dd@JxABj@@HADAFCBEBYFG@CBEFEJGTCTAL?RFZLh@\\pANp@J\\?@^nALZDNBNX`AN`@@BP\\j@n@N^HXJ^D^DRGVKNo@^QLAH?J@LHl@P~@BRJz@FZHb@H`@HZ@LBL@L?JAr@AP?HUdA"
                     },
                     "start_location" : {
                        "lat" : 37.1240133,
                        "lng" : -113.4850877
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 200
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 37.1099184,
                        "lng" : -113.5225434
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN 3050 E\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "choaFfa{sT`@Vt@x@|@rAJLNVx@hAV\\"
                     },
                     "start_location" : {
                        "lat" : 37.1112154,
                        "lng" : -113.5209982
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 650
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 37.1058673,
                        "lng" : -113.527821
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eE Riverside Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "_`oaFzj{sTbB`CX`@dAzAvF`I~DxFrAlBxAtB"
                     },
                     "start_location" : {
                        "lat" : 37.1099184,
                        "lng" : -113.5225434
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 290
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 63
                     },
                     "end_location" : {
                        "lat" : 37.1036519,
                        "lng" : -113.5284864
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eS Waterfront Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ufnaFzk|sTj@u@HAJAxBArA?HBNJJJt@bAp@|@\\b@"
                     },
                     "start_location" : {
                        "lat" : 37.1058673,
                        "lng" : -113.527821
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.6 mi",
                        "value" : 4133
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 756
                     },
                     "end_location" : {
                        "lat" : 37.0867955,
                        "lng" : -113.5570972
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yxmaF`p|sTJKHE@CVM^OTIRE@AL?P@D?XDB?b@FXDx@PfAZf@Rn@^l@^tA~@n@j@JRXp@Tr@NXfA`Bd@r@x@hAZd@NRjAbBjA`B^h@X^\\b@P\\Vb@DHl@|@RXTRVRNJNJDBRLHFDDLLDJ@FDR?L@N@\\Bv@Bz@F|@Lh@?@\\r@f@x@b@^RJ\\NP@`@GTARCb@BlATh@J`@Jf@Pd@L^?\\Gb@El@B`D\\b@JTLLHJDTJZDh@BfANrEj@ZDp@Jh@R`@TVRXZVZPXR\\JZFZDl@HdCHr@JV@@VP`@?VOh@i@RQTUVI\\El@Gf@BVJLLN|@Jt@D\\BHFvAJnCDdABf@Fr@PhBD|@A`@G`@M\\UZ[PWF]BUFMJ_@r@Yz@Sd@S`@OT[ZA@[^MRIREd@CdB?jA@l@Bx@HdBL~ABt@?j@EvC@^?pBCnBAPB\\Jn@Pj@|@vBHRTn@H`@Dj@DpDCNEFMDa@NKJGTBNTd@r@|@L^DX?H?`@?h@BPNb@DLBZ?JB\\?BGj@Ij@"
                     },
                     "start_location" : {
                        "lat" : 37.1036519,
                        "lng" : -113.5284864
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "367 ft",
                        "value" : 112
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 37.0877028,
                        "lng" : -113.5570164
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003e1050 S Cir\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "oojaFzbbtTIYUQQCS@YFMBe@J_@D"
                     },
                     "start_location" : {
                        "lat" : 37.0867955,
                        "lng" : -113.5570972
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "59 ft",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 37.0877401,
                        "lng" : -113.5568241
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e1050 S Cir\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cujaFjbbtTGg@"
                     },
                     "start_location" : {
                        "lat" : 37.0877028,
                        "lng" : -113.5570164
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 228
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 55
                     },
                     "end_location" : {
                        "lat" : 37.0857795,
                        "lng" : -113.5560932
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRiver Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kujaFbabtTPAXG^Id@Kx@Y\\KZK`D_A"
                     },
                     "start_location" : {
                        "lat" : 37.0877401,
                        "lng" : -113.5568241
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 mi",
                        "value" : 2682
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 490
                     },
                     "end_location" : {
                        "lat" : 37.07437609999999,
                        "lng" : -113.5684247
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cijaFp|atTB\\?HCHELGNGLCJAJ?TB\\@HD`@Dj@@FDb@N`BPvBFn@Ff@F`ACr@Ap@?`@JvALrBDf@?BBRBLBFDFNHXLTFRLFFDFHPH^Pp@Pf@BFRb@PR\\f@^^\\VB@dAf@`@HRBvBJvA@^@H@ZDPJHDHH\\b@LXFNF\\Jp@XtANp@DP?L?DAFEPM^IZCZ?HF\\Nb@D\\B^Bf@?BF\\FTTd@Rf@@L@T@^Bh@?J@HDXBNHRHPTVj@h@ZXt@n@ZXJNDPFd@Nl@N\\@@LVPRPPXLTLJHZ`@N^H^FZARGd@@PBPDHFJHFPBP@HCLILMXQFERKfAEl@CNGRMVQPQTe@Vm@Jg@Fe@Bk@?a@@q@@CDu@?ADSHQFETCVA\\GJ?FDDJHf@F`@Jj@BTFRBJFJHH@BPHJBHBVBLALALENIHKBCHMFM@?BO@[?ABk@BQBYBI@[Cq@?E@OVoC"
                     },
                     "start_location" : {
                        "lat" : 37.0857795,
                        "lng" : -113.5560932
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 451
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 37.0725516,
                        "lng" : -113.56563
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e at \u003cb\u003eLarkspur Rd\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "{ahaFridtTBUBI`@Qf@YNILKFCHMBI@C?GCIS]O_@AQA[Qe@OWCGMc@CU?QHSTUJGNIVIVIDEFIN]HMFEb@IBADCNKNKFCJ@f@RRHN@"
                     },
                     "start_location" : {
                        "lat" : 37.07437609999999,
                        "lng" : -113.5684247
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "308 ft",
                        "value" : 94
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 37.0721601,
                        "lng" : -113.564737
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mvgaFdxctT@MFITWBEFIDWB[BYBMNU"
                     },
                     "start_location" : {
                        "lat" : 37.0725516,
                        "lng" : -113.56563
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 329
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 67
                     },
                     "end_location" : {
                        "lat" : 37.07076929999999,
                        "lng" : -113.5619137
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_tgaFrrctTCOAE@M@QF]BKJYFODGFENEf@GBABCBE@EHYBO@]Ag@Cc@@K@SBMVo@\\u@Xe@HQJKHIFAXE"
                     },
                     "start_location" : {
                        "lat" : 37.0721601,
                        "lng" : -113.564737
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 274
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 55
                     },
                     "end_location" : {
                        "lat" : 37.0701666,
                        "lng" : -113.5591736
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ikgaF|`ctTGk@Ko@Mg@AE?G@EBIDOTe@FQBM@Q?W?]@KDUBIDCDC?K@GJYFWBIHQj@y@BS"
                     },
                     "start_location" : {
                        "lat" : 37.07076929999999,
                        "lng" : -113.5619137
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "390 ft",
                        "value" : 119
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 37.0692986,
                        "lng" : -113.5599406
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eHillrise Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qggaFxobtT^RRLLFJHj@j@DFRTXZ"
                     },
                     "start_location" : {
                        "lat" : 37.0701666,
                        "lng" : -113.5591736
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "443 ft",
                        "value" : 135
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 37.0684155,
                        "lng" : -113.5589494
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eFort Pierce Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cbgaFrtbtTNSLQJIJIPM@?LINKPKLKJMHQ?APm@"
                     },
                     "start_location" : {
                        "lat" : 37.0692986,
                        "lng" : -113.5599406
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 mi",
                        "value" : 1975
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 423
                     },
                     "end_location" : {
                        "lat" : 37.0521074,
                        "lng" : -113.5591787
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBloomington Hills Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "s|faFlnbtT`@JPBxAJD@XBB?b@Jb@Pl@Tl@VfA`@ZHD@\\FZBp@BD@\\?fABd@?`ABB?b@?T@LA~A?p@QrA_AXE^?ZJPJPLHH\\^XXl@^`Bh@fA\\dAj@jAl@tAv@bAj@^PZNf@Hj@DlA?tAM|@g@`Aq@n@_A@Aj@iAPg@ZaAXq@PWJQ`@[d@SnDFzFE`@?bCCL?jDE"
                     },
                     "start_location" : {
                        "lat" : 37.0684155,
                        "lng" : -113.5589494
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 346
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 37.0519309,
                        "lng" : -113.5553315
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBrigham Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uvcaFzobtT?sD?m@?_A?yB?q@?sA?E?sA?C@[?E@OBKBI@I@ARm@"
                     },
                     "start_location" : {
                        "lat" : 37.0521074,
                        "lng" : -113.5591787
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.7 mi",
                        "value" : 6017
                     },
                     "duration" : {
                        "text" : "20 mins",
                        "value" : 1183
                     },
                     "end_location" : {
                        "lat" : 37.0001854,
                        "lng" : -113.5602441
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAz Strip Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eS River Rd\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow S River Rd\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Arizona\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qucaFxwatTTJXHHBn@Hx@?r@Cj@Cp@CzCKdCEdACtCK`@CtBGd@Ap@Cx@CZA\\?LAD?hCGj@AH?D?~@Al@A`A@L@jAF|BXrAZbAVtAh@|Ap@@?bB`A|ChB`@TrIrF^VvBnA|FnDvIfGb@VvAz@pBl@VF`@LrA^hB^zAVfARzFnAfE|@bC^|@NnAJ`BBdBAhBA`ACjBGdACpAChAE`ACpACTAd@?v@?b@BL?T@^Dl@DlANh@LLBb@HVFjCj@b@H`@Jd@HdAT`AVPDPDj@JXDZFD@`ATRD\\DXD`@BP@P?H?XAfA?bAArCCbHGbDEfAAd@C\\A\\GXGZINEb@Q^OVOTQNMHGrCyBlCqBzAkApB{Ab@]^Wb@YBAZQd@Ub@Q\\OHCn@SHCNE^Ib@KTCBAf@IXEXCZCZA^AhBCdBAt@?xACfHGvEEjBChAA@?B?LAb@?@?@?z@A"
                     },
                     "start_location" : {
                        "lat" : 37.0519309,
                        "lng" : -113.5553315
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1525
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 244
                     },
                     "end_location" : {
                        "lat" : 36.9924759,
                        "lng" : -113.5714191
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eMount Trumbull Loop\u003c/b\u003e",
                     "polyline" : {
                        "points" : "ery`FnvbtTx@?N?tBEzCT~@TPDn@PjAb@jAn@\\TjAx@z@|@pDbGp@vAf@zBXtAVrBLfC?dB?rE@bKHz@Pt@Rp@l@|Az@|@n@f@FDj@XLB^H@?lB\\"
                     },
                     "start_location" : {
                        "lat" : 37.0001854,
                        "lng" : -113.5602441
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "59 ft",
                        "value" : 18
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 36.9923666,
                        "lng" : -113.5715613
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBLM 1009\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "_bx`Fj|dtTTZ"
                     },
                     "start_location" : {
                        "lat" : 36.9924759,
                        "lng" : -113.5714191
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.7 mi",
                        "value" : 4422
                     },
                     "duration" : {
                        "text" : "15 mins",
                        "value" : 871
                     },
                     "end_location" : {
                        "lat" : 36.9811361,
                        "lng" : -113.6046845
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "iax`Ff}dtTWdAg@`AqB~De@lB]dAiA|BYl@m@tAOVcAfBm@x@CFY^W^WZSb@ADKb@Gr@Et@C^E`@?HC\\OTSRA@a@Vi@VOLSNW\\GLc@zA[lAo@tBS^k@dA}@|Ai@hCKb@EzD_@tCCVEl@u@bGm@xEM`AMzCEhAm@hICf@?F@ZHf@Vb@DFPTj@v@v@|@d@l@RTTh@Dz@Zd@P`@N\\HLHJRLn@\\LF`@b@t@jAt@|AJNTNHFd@d@NTX\\XXZRd@Vv@`@d@Xf@\\n@h@b@ZHDj@d@j@\\XN|@h@f@^^Zh@RJFx@f@^V`@Rf@N\\R`@\\TVLLn@n@dAd@THXHZHv@L`APZDxAX|@N\\Dd@B|@DVNHPHLNTPHLDF@~@@d@?^LRV@HJ^Xj@Tl@Pn@JVb@|@Vn@Nh@@DF`@@^ANO`@@\\JJFFn@Tv@TTJnAd@fAf@\\Jp@?D?|@Dl@Bb@Cl@Px@Nl@ZPJnAz@LF|At@rA~@f@h@"
                     },
                     "start_location" : {
                        "lat" : 36.9923666,
                        "lng" : -113.5715613
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 mi",
                        "value" : 3752
                     },
                     "duration" : {
                        "text" : "11 mins",
                        "value" : 663
                     },
                     "end_location" : {
                        "lat" : 36.97930729999999,
                        "lng" : -113.6443487
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "c{u`FflktT?@BX?^Ih@Kd@KZ_@z@IPc@|@Wp@CFM^Kp@QbA[zAOn@Kd@?BIf@G`@Sn@?@S|@ERK`@Mn@Mf@CP?LCLGDM@SJONKTMLONOZI^ENOn@Gd@Cj@IVCFQd@Sn@Kv@CLAL?XHd@L~@DTANI\\O\\CLENCTE`@Cb@I\\C\\?dAFjBRdBHxAJdC@RNjEFxALrDDtALtDD`ADTbBrIVrAd@|BVtA|@pE|@rE|@rEd@zBxBxL`AhFv@jCPh@hBvBTdCd@zENvAzAnOXvC_@jBq@fDmAzFAHT`GXxH"
                     },
                     "start_location" : {
                        "lat" : 36.9811361,
                        "lng" : -113.6046845
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 565
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 104
                     },
                     "end_location" : {
                        "lat" : 36.9840733,
                        "lng" : -113.6465077
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBlack Rock Road\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uou`FddstT_@BYBSDYHg@H[JODa@NcA\\a@N_@Pa@Na@P_@NMFSHa@N_@P]LC@a@P_@N_A^C@a@N_@Na@PcBp@[L"
                     },
                     "start_location" : {
                        "lat" : 36.97930729999999,
                        "lng" : -113.6443487
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 580
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 111
                     },
                     "end_location" : {
                        "lat" : 36.9814439,
                        "lng" : -113.6517277
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto the \u003cb\u003eI-15 S\u003c/b\u003e ramp to \u003cb\u003eLas Vegas\u003c/b\u003e",
                     "maneuver" : "ramp-left",
                     "polyline" : {
                        "points" : "mmv`FtqstTNf@BFDFFHHHJFPHNHNH@?PHPJJFJDB@FDHDJF@?JFJFFDBBJFFFHHHJHH@BHJDFFLDJDHDHBJBFDLDRHZ@FDVNv@Hd@TpALr@Hf@`@bDVhBVjA"
                     },
                     "start_location" : {
                        "lat" : 36.9840733,
                        "lng" : -113.6465077
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "18.2 mi",
                        "value" : 29270
                     },
                     "duration" : {
                        "text" : "1 hour 17 mins",
                        "value" : 4621
                     },
                     "end_location" : {
                        "lat" : 36.8933268,
                        "lng" : -113.9242837
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-15 S\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "_}u`FhrttTt@zHDZPfCDd@F|@Dd@Bp@?LBb@Bb@Dh@@^B\\@ZB\\?NJrBFfCBt@FbD@vA@T?V@jB@hCAdDApAAr@Av@EfCCtAGvBMdFG`CCj@GtCKxD?BE|AE|AAd@CpAAt@?h@@^?F@f@Bh@BZBXFh@Fb@BPHb@DVH`@J\\HVLd@N^JVLZJRJRJPNT\\h@^d@NRRRTTLLNLHHp@j@xAtAFDpAlAhAdAd@h@`@f@\\b@^l@T`@HNVl@FPJXFRLb@DPBJLd@H^FXF^BRJr@Dd@H`AVnC@HRxBJdAb@jEh@bD^`BFXNt@FT\\lAJ\\Nf@Rj@DNn@fBFJl@|Al@vA`A|B^|@@BZp@Tl@Rl@Ph@Tr@VdAHd@Hh@Fb@Hp@Hz@Dr@?@@X?N@b@?pAAbAEp@Er@En@M`AE\\Kn@YdB}@rFKj@G\\c@jCSrAGd@Mt@OpAMxAIbAGhACz@E`AEjBA`C?dA@|DA`B?fB?z@@vB?jB?n@?jCBjNBrBJ~G@jA@lA@bB?hA@|@?l@Bj@Bx@@JDf@Ff@BZBJJt@Pr@Jb@b@~ATj@Rd@T`@LTHL?@`@n@b@n@@Bf@p@V^@Bf@t@zArBPXJPNRNVHL@@LTNVFN^v@LXHTTl@Pl@HZBL@BFVDNF`@Fd@BNFj@?@BT@PBh@@p@?J@x@?RAV?PE|@C\\?BGp@QrA[nB]zBId@CRUzASpAEVKt@W|ACPCXEXE^AHC^C^Cl@?BAd@?j@@hA@ZFjAHx@Jx@BLHj@@D^xB^~B@HH`@XhBLz@Fp@DZBVFZN~@Jt@@FFj@Hj@BXB`@Dl@@X@\\?\\?^An@Cr@A\\K|AUbD?BIxAEj@AHIlACl@Ej@AVARIxAGxBCx@ExAAHKtEIhDAt@CxAAJClACxACrA?DExAAn@GbCCv@?`@IpDAl@IrDChBIzCEfBCpAC`BCxA?rABdA?DBt@Fr@Ft@LdAPfANv@Rx@J`@Nh@@BHRJ^Xn@Vn@b@x@Zh@Zf@p@z@LPNNh@j@n@j@b@\\v@l@PL|@p@\\Vz@n@^VFFpA`A^Xx@l@\\XzAfAXT~@r@rB|Aj@b@h@`@DBTN`Ar@\\Xj@b@`@\\rApAp@v@t@|@PVh@v@^n@p@nAp@vAZt@Vp@Zz@f@dBDNFVHXFXFZFXDVDTFXHn@F^@JBNLfAZlDJbAPjBThBVdBDXDXFXDXDX@FDRDVDXDXDZDXDXDZ?B@FDd@BZ@N?J@Z@T?B@V?T?N?R?PAZCdAKzAIdACXCXCXG~@Ej@CZCZCZ?@CVCVCf@Eh@Ep@CZAXEnAAX?ZAZAV?X?h@AJ?b@?p@?X?Z?X?V?Z?Z?t@?@?r@?Z?n@?jB?t@?v@?Z?X?j@@|@?D?x@?B?t@?f@?b@@^@t@Bp@Fx@BRDj@F`@Hl@Ll@Jd@H\\Nh@Nh@Rh@Xv@`@|@l@nA\\v@~@tBt@rBf@|Af@pB~BbKfAxEFVFV^~AH`@ZtAPr@Rz@FVNr@`@bBFVFXFXFVFXDLBHFZFVFVNp@HXFXFZFXPn@Nn@FVBLBJHV@BFTFVHVHXHTJXHVHTJVLZHRFL@DJTDHDJLVJTLTJRLTLTJRLTLRNRLRLRHLDDLRNRLPNRNPNPRV\\`@^b@nAxABBX\\RTvA`B|@fA|GbIHHFFFFFFFFDD?@DDBBBDBDDDBBBDDDFHDD@@BBFHHHFHFHBB\\`@PRRTFHFFNPNPNPNPDFFHNPNPPVLPNRFL@@FHDJLTNXLVJTJTHTHTHVJZFXBHDLFVFZFXF\\Lj@Nr@TjANt@ThAFXFXHV?BFVFN@DHXBFDNJVHRJXJTJRJT`@t@\\f@d@j@hAnAhAlANPbAfAzA~ADDTV~@bA^b@^d@f@p@j@`Ad@`AZt@HVHVFVHVDTX~AVdBJ|@DZDXD^Hl@D^Hl@DZD^Hn@Hp@DZRhBThB^|C`@bDHn@DXHh@Jf@Lj@FV?@HVFVHVJZHRJVLZJR^t@`@p@l@x@j@p@t@r@TPZT\\T@@VNVLRJRHPHTHRHVHRFVFd@JRDTBF@PDj@DT@d@@J?\\@vAAlAArA?`@@\\@XBZDf@HD@RFf@Nb@PVNHDRLFB^ThAv@f@\\^VXPHFZTn@b@n@^t@h@j@`@|@n@XVZXTRn@v@r@|@BBj@z@~A~Bh@v@^d@RTNPNNPPn@j@BB^V?@`@ZTNBB^TVNh@Xj@XTJXHL@JBd@?L?HAXETCl@C^An@An@Cj@?v@AhCGD?XAXCZCVAj@C`A?n@@f@A~@AT@\\?l@BT@b@FH@hAR\\Jp@RPHz@^RHPJD@BBVJhB|@RHDBd@Tj@V`Ad@r@\\JD\\Pb@RRJZN^Pf@XPJRLB@\\Tb@Zp@p@RT\\f@Vd@h@dA@@HRHVHVBJDJ?DDPFV?@DT@BDX@JBJB\\@@@TBZ@^Bn@?X?V?B?NAJ?J?J?FAT?B?XAp@A^Ap@?`@An@A`@Av@Ap@?VAV?RAbBCnAAd@AZ?VAT?F?NAL?\\Cl@?@AZAXC^CXEZEXEZETA@GXCLEJADCJEHELKTIRA@GNA?ADGJEFEHGJORKNABKJCDGFGJEDMNe@j@u@z@SVED?@IHORMRMREJEHEFGLABIP?@GPABGNCFCHGRGRGVGXCL?@CJAFCPABCPEZKt@Il@EX?@ERAJKl@ETI\\K\\Qj@ITMVKTMRMTA@KLA@ILA@CBOPEFKHA@MLQLMHEDQLEBMFA?OHA??@YJEB[LUFQHA?i@PWJODA@MDC@UJGBKDC@OFQJSLQLQLSPOLOPOPEFIJMRMPKVMTKVIRABITIVGXCFCPA@CRABCPAHEXCRE\\C|@?j@@|@@TBd@BRFd@Lr@XlA@BNl@`@`Bd@`BDT\\rAj@vB`@pAFTHTFPBHBFFNJT@@FL?@NXNXZb@JL@BNPTVXZ@@JLBBPPPRNNBBRV@@BBFHFHDDJJLRBBFHLPDFDFHL@@?@HN@?HPBDNXHPTl@P`@J^FVFTHXFX@DBPFZD\\Hl@BZBV?HDl@@`@@Z?V?\\?F?^?L?t@An@?^?\\?r@Ap@?t@At@?v@Ax@?p@?B?Z?J?HAt@?z@?t@@d@?h@?@?H@`@@J?V?F@J?D@`@Dp@Bj@?FBVBb@Fr@Fp@B`@BPD^VjBJn@Jr@FXF\\FVFXDVFXFVHZH\\Pj@HZHXHVHXFRHTL\\Ph@L\\`@~@JVNZVj@LVVj@r@vAXj@Vd@NZZl@j@jAv@|Af@`Af@`Ad@bAXj@Zj@Xl@Xh@Xj@r@xAf@`A\\r@@@FJJT?@Zj@bBjD@?Rb@z@bBrBdE|AzC`AlBf@bAtEhJrFvKhBtD`@x@bApBf@bALT`C|E`AnBlA`Cr@vAXj@f@`AXj@^t@DJ~@hBh@dAd@`A~@hB`AnBpAjCb@x@LXv@|Al@jAP^z@bBXj@lAbCfBnD~@hBt@zA\\p@PXhA`CbHlNzAxCnB|Dn@jA|@nBP`@BDLZVn@Pf@L\\Rh@J\\Rl@J\\@BJ`@Rp@`@~A`@dBLt@HZV|AXlBNpAFn@Jt@@PHnABR@P@PDb@B^?DFz@F~@Dz@@DD`A?@Bt@Bl@H`BLfCHlA?@Bj@VvEBp@Dr@HvADr@Bp@JbB@^HjA@d@"
                     },
                     "start_location" : {
                        "lat" : 36.9814439,
                        "lng" : -113.6517277
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 516
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 36.8925366,
                        "lng" : -113.929961
                     },
                     "html_instructions" : "Take exit \u003cb\u003e8\u003c/b\u003e toward \u003cb\u003eBeaver Dam\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLittlefield\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "ivd`FvyivTAh@Bh@B~@Bb@DzB@j@@l@@X?R@\\@P@V@VBZ?HDh@Dj@Fn@@DDd@@BDd@?@Jn@NjAFVLr@d@fC"
                     },
                     "start_location" : {
                        "lat" : 36.8933268,
                        "lng" : -113.9242837
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "9.3 mi",
                        "value" : 14995
                     },
                     "duration" : {
                        "text" : "49 mins",
                        "value" : 2964
                     },
                     "end_location" : {
                        "lat" : 36.8168284,
                        "lng" : -114.0501371
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHwy 91\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Nevada\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kqd`Ff}jvT~Ak@`@O`@Mn@UVI~Bw@|@O^Eh@Gj@Et@Af@@^BV@H@XDt@Lh@L`@LPH`@PTJTNPJ`@X\\XNLd@d@@@b@h@V\\NRZf@T^PZN\\P`@Ld@J^HXFXBJDRJj@Jr@Jp@@DFf@Nx@Z`BLj@Pr@Tz@Rn@DNL\\f@vATf@\\x@\\p@BBNXT^Zh@R\\Zh@nAtBtC|ExDpGdAfBT`@l@bArBjDdAfBV`@nEtHlEnHnErHzBtDjClEpDfGvAbClArBvE|HRZFJ^h@h@t@^h@l@x@`@d@n@v@NN`@d@PRh@h@v@v@jCbCjCbCTTjE`EhBbBdExDb@b@tAnAt@r@xArAx@t@nBjB|DrDpFbFRRpEdEpFdFzBrB~@z@pChCjCdCJHl@j@x@v@~BtBdFxEtBnBTTt@r@l@h@p@j@\\X~@x@^ZtBhBh@d@Z\\dA`AbBjBr@v@JLPVh@x@JTJVN^Z`ATn@L\\HPT^LTHHHJPRTR\\XZXNJLJXNZLlAh@j@T~@^t@ZND`A^LDRH`@P`A`@TJJDn@XVLNLTRVZNTFJJTJVJVN`@FTBJBHHb@RdANn@@BLf@H\\L\\N`@Pb@Tb@LXDHTf@FNJXNh@FTVv@HPJRTb@LVRVRXXX`@\\@@l@d@rBfBz@v@FHPPd@h@BBn@v@xAlB\\b@`@b@BDTXFHf@l@BBXZ@@LLLJ@@\\TB@ZRPJXN\\LZJTFTFXB^BVBl@BT?L?Z?VARA@A^C@?^Cv@GRATAT?H?F?H@H@VBPDB?XFRHXJTHRLTJVRRNNNVTTTDFLPRVLTFJT^Td@NVHRHNlA|B`@r@DFLZHRR^dAhBJRRb@NX^l@Vf@\\h@JRV`@NXHNDDPPX^FHFHLHRNPJVJZNPFXHZDB@VBD@VBJ?X@T@b@CVALAd@Er@Gb@EBAPAXAT?B?J@P@D?L@L@FBF@VFB?RHVHTJZPB@NHNJDBPLDDHFPP@@RTRVJNFHXd@PZJTN`@FTLb@Jb@Hh@BV@L@DDf@?BBf@?R@\\?\\AX?HA`@CVAJAFAHE^?@G\\EVENMd@Of@KVIROXKPGLKNCBSZCDKNILUb@U`@EHOXUb@Ub@A?ADIPKRO\\CDABKXCFIRWx@o@pBMb@CJKZOl@Mj@K^EZCNEd@AREp@ATAP?JAX?f@?J@N@\\Bj@JbB@^HxAHvAHdBLxBB^Bv@F`ADj@?@Fh@Fj@?DFd@@HL|@P`AzAdHR~@j@dCJh@bApEXrAf@zB`@fBdC`Lx@lDdAbFJb@fCfLDNjAhFt@fDhAjFLh@Lh@Jh@DPFTt@fDXrAbAnEJh@pAxFt@jDbAnEPt@b@pBdAxELn@tAjG`@jBf@|BPz@R`AVrA\\hBP~@`A~FLv@t@hE`@dC^~BJh@^~Bd@rCH^PjA`@zBbAbG@F^|Bj@jDX~AT~ANz@BNJr@\\jBLt@"
                     },
                     "start_location" : {
                        "lat" : 36.8925366,
                        "lng" : -113.929961
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 mi",
                        "value" : 1483
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 199
                     },
                     "end_location" : {
                        "lat" : 36.8098345,
                        "lng" : -114.0639753
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eHillside Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "exu_FjlbwTHb@RbATtAbAdGH^FX@@HZLb@Pb@P`@bAtBzA|ChBtDTb@HNJRhDjGtAhCT`@LRx@|APZjAvB~AvC^p@`AlBNVNVl@dAJRHL\\j@JPR^`@r@Vf@LTFPFPBJBH@J?D@l@?RAHAJC\\AV"
                     },
                     "start_location" : {
                        "lat" : 36.8168284,
                        "lng" : -114.0501371
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 191
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 36.8081998,
                        "lng" : -114.0646312
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSandhill Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mlt_FzbewThAPt@Rt@VXJl@VVLPFHBRD"
                     },
                     "start_location" : {
                        "lat" : 36.8098345,
                        "lng" : -114.0639753
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "305 ft",
                        "value" : 93
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 36.80812110000001,
                        "lng" : -114.0654966
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eE Old Mill Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gbt_F|fewTI`@CNADAXA@ANAV@P@HBFBBDBTD"
                     },
                     "start_location" : {
                        "lat" : 36.8081998,
                        "lng" : -114.0646312
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "207 ft",
                        "value" : 63
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 36.8082822,
                        "lng" : -114.0660019
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eE Old Mill Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wat_FjlewTGHGFIJGFKDEHADBJBHLP"
                     },
                     "start_location" : {
                        "lat" : 36.80812110000001,
                        "lng" : -114.0654966
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 284
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 50
                     },
                     "end_location" : {
                        "lat" : 36.8091077,
                        "lng" : -114.0689702
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE Old Mill Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wbt_FnoewTMLOTSd@In@g@`Ei@vDKh@Kr@"
                     },
                     "start_location" : {
                        "lat" : 36.8082822,
                        "lng" : -114.0660019
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 550
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 78
                     },
                     "end_location" : {
                        "lat" : 36.8043997,
                        "lng" : -114.0699856
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}gt_F`bfwTNBJGB?@?F@LBJ@D@lB^x@NH@n@Bl@AX?PBRHb@`@JJTXPPj@XNBL@X?X@VFD?TDv@C\\?N@J?JENKD@DAHA`@C^@FBHDPF"
                     },
                     "start_location" : {
                        "lat" : 36.8091077,
                        "lng" : -114.0689702
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 324
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 86
                     },
                     "end_location" : {
                        "lat" : 36.8025634,
                        "lng" : -114.0723547
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ojs_FlhfwTDQJBJDFBNNDDBDPPBFFFPTDFL\\@@Nf@Lf@L`@\\vAFVHN@FRTTNJHLFRH^N?TRA"
                     },
                     "start_location" : {
                        "lat" : 36.8043997,
                        "lng" : -114.0699856
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 mi",
                        "value" : 1206
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 191
                     },
                     "end_location" : {
                        "lat" : 36.7968512,
                        "lng" : -114.0795889
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eW 1st S St\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "__s_FdwfwTLDfDrAPHTHRFRBL@R?V?J@J@ZDR@Z?PBH@n@NPHXJZFNBdALT?rC?ZAtC@`AC`@AJAL@JBDBBF@N?tG?fB?r@Ch@?TGlAAt@@dA@zC?rC?J?hD?\\"
                     },
                     "start_location" : {
                        "lat" : 36.8025634,
                        "lng" : -114.0723547
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "240 ft",
                        "value" : 73
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 36.7974357,
                        "lng" : -114.0798661
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eHafen Ln\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "i{q_FldhwTg@?Q?EBu@r@"
                     },
                     "start_location" : {
                        "lat" : 36.7968512,
                        "lng" : -114.0795889
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1239
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 215
                     },
                     "end_location" : {
                        "lat" : 36.7966107,
                        "lng" : -114.0935424
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHafen Ln\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "__r_FdfhwTf@~@Xh@^hARx@FVFh@DrA@zI@rDAlDD~E?T@xB@zB?T@fB?dA?N?XAVATAPATAP?FAH?N?d@@z@?b@@xA?P?J?J@N@V@^@b@Bb@@X@X?L@N?T?rA@xA?vA"
                     },
                     "start_location" : {
                        "lat" : 36.7974357,
                        "lng" : -114.0798661
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 400
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 133
                     },
                     "end_location" : {
                        "lat" : 36.793017,
                        "lng" : -114.0935475
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRiverside Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "yyq_Fr{jwTdF@xB?lB?Z?bF?"
                     },
                     "start_location" : {
                        "lat" : 36.7966107,
                        "lng" : -114.0935424
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "46 ft",
                        "value" : 14
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 36.7930156,
                        "lng" : -114.0937042
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eJensen Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kcq_Ft{jwT?\\"
                     },
                     "start_location" : {
                        "lat" : 36.793017,
                        "lng" : -114.0935475
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.0 mi",
                        "value" : 3187
                     },
                     "duration" : {
                        "text" : "9 mins",
                        "value" : 556
                     },
                     "end_location" : {
                        "lat" : 36.7739485,
                        "lng" : -114.1177033
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kcq_Fr|jwT@?N?NCbB@|ADV@fBJnBJp@DR@lDPvBJr@Bn@Fj@HXHVHjAh@@?TRr@l@LPd@p@jAxBBDx@fBx@dBn@nATd@Zt@tApChA|BtAnC@DpAlCJTFLjCrFFHh@hARb@Tb@P^fBrDVj@p@vAf@fAVb@LTXl@vA|Cb@t@bBjD@Dh@fA~@lB?@~@hBp@rArApCJVFJtAnC@BN`@Zx@RVb@~@|AzCvBnELT|@jBTd@Vh@N\\JPXt@Rb@@BNVFJr@xAr@xAR^r@vAFZ@JP^L`@Nv@"
                     },
                     "start_location" : {
                        "lat" : 36.7930156,
                        "lng" : -114.0937042
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13 ft",
                        "value" : 4
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 36.77391009999999,
                        "lng" : -114.1176932
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBunkerville Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "elm_FrrowTFA"
                     },
                     "start_location" : {
                        "lat" : 36.7739485,
                        "lng" : -114.1177033
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1268
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 212
                     },
                     "end_location" : {
                        "lat" : 36.7674629,
                        "lng" : -114.1292957
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e at \u003cb\u003eE Virgin St\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "}km_FprowTRE@?@?HNNZl@tAFLTb@Td@Td@dBnD@BTb@Tb@Nh@R`@Zr@LRNRt@|AXn@h@fAHNJRTb@JPbAtBXl@fAzBJTh@fAb@~@lAzCbAxCZp@h@lAP`@Tp@Ph@Vt@LVP\\Pd@jAxCRd@"
                     },
                     "start_location" : {
                        "lat" : 36.77391009999999,
                        "lng" : -114.1176932
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "23 ft",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 36.7674015,
                        "lng" : -114.1292648
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN 2nd W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "scl_Fb{qwTJG"
                     },
                     "start_location" : {
                        "lat" : 36.7674629,
                        "lng" : -114.1292957
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.8 mi",
                        "value" : 12513
                     },
                     "duration" : {
                        "text" : "42 mins",
                        "value" : 2543
                     },
                     "end_location" : {
                        "lat" : 36.7581247,
                        "lng" : -114.2352608
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eNV-170 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRiverside Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gcl_FzzqwTbAnCBF\\~@FPPh@Tv@b@fBn@vCjA`FLf@Jb@Pn@h@zBh@|BLh@XpA@@Lf@Lj@Lb@Nj@ZdANd@d@zA`DzH^z@z@pBr@fBr@bBd@vA^v@Rd@f@pAP^h@pAFLJTf@nAd@jARd@Rd@nA|Ct@jBTj@N\\f@jA@DRd@v@jB@DrB`Fv@jBBDx@pBN^@DlAtCz@nBf@jA~@~BhAtCN^BD^~@DJRd@d@jARd@N^pAzCj@vAf@jAlAtCRd@f@hAd@hApBbFx@pB?@jAtCRb@?@Rd@Pd@Rb@?@f@lAd@fA?@JTXr@LVRd@DJ?@Xn@^~@?@JVNZJR?@LV@DZt@l@zADJ@@^|@DJ?@lBrEDJ@@JVd@jADJ@@p@bBDH@BdAhCDH@B^|@BH@@HTh@lABH@BtBbFPd@LVBHLZtB`FzElLJVBHTh@z@pBJVBFh@pAJV|@xBBDJVVj@L\\FLN^N\\DLVj@n@|AXr@JVBFTj@JVRd@BDBFJVVl@LZBFBDJVvBhFBFJVVn@P`@BFJVdC`Gh@xABFJVVt@JVDNj@hBLd@@DBHVbA@BBHTbA@BBH\\tA`@hB@DBHFXXrAn@nC`B~Gb@fBRz@h@zBPt@|A~GVfAbDfNj@`CZrAzBpJdDnNHZBJZrALf@Lh@Lh@H^hA`FFRhAxEZrAXnA@@ZrAJf@Lh@Lh@Lf@Lh@Ll@Ld@Lf@Lh@f@zBLh@ZpAZrALf@ZrALh@ZpALh@Lf@ZrA@DJ`@lBjIv@dDBHLj@Ln@F^Dd@@H@PBXB^@b@?R@|@E~@C\\E`@EZGZQx@Oj@CF[z@g@dAe@r@A@g@n@e@f@w@n@]X]XSNIF]VOLMHQL_@R]PgAp@]T}BvA}@j@_Aj@}A`Ag@Ze@X_@PIFi@P_@JQFG@YJ]Na@To@\\UNURa@^i@j@UXKNILo@fAmBrCgAbB_@j@i@v@Yb@cAbBaAxAUZQPEDUTQLKHYPSFYJk@J[Dc@@C?[AGAc@CA?m@Iu@KkAQiBWUEcNsBq@I[AO?M?U@E?]DSFMFC@a@Ny@`@c@R_@RaAb@_@RaAd@k@VSLa@P_Ad@a@P_@PaAd@eGtCaBv@A@}Ax@u@`@_@T[Tc@\\q@j@g@h@A?Y\\SRY`@s@`AaCfDgA~A{BbDo@~@Y`@]f@yDpF_@h@g@l@i@h@[X"
                     },
                     "start_location" : {
                        "lat" : 36.7674015,
                        "lng" : -114.1292648
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12.3 mi",
                        "value" : 19779
                     },
                     "duration" : {
                        "text" : "1 hour 6 mins",
                        "value" : 3940
                     },
                     "end_location" : {
                        "lat" : 36.7325154,
                        "lng" : -114.4356795
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gij_FjqfxT@ZB`@Db@@RAP?BCFGFGDKBa@N[Fm@V]^m@x@gEbGQ\\eBrCY`AqAfESp@K\\uAdE_A~CQl@aAxCi@`BmA`Ek@hBa@nAAD_BhFGTM\\Sx@CZEPIpA?PC~@HbBTrABLX|@FPd@`At@bAz@t@PPv@^xA^hAJ`@@x@@~BFrAFt@DZ@~@NJF`@Tr@p@v@x@pA`Ad@`@v@Zn@Vx@ZlBn@x@XnBr@\\Vr@d@pA`BBDfAzA@Dr@xAXz@Rj@Jb@VdAFj@RdBFvB@n@CxBQ`BIh@]hB}@xDcAnEoCrLS|@cDpNw@dD_DhNwFtViB~HkBfIi@zBELo@vCu@fDI^y@lDoAjF]~AgA|EGZg@`CWnBALWzECxDAbCAdCC~E?xAAxA?r@ApAClG?xAClGCjG?lACpDAxAAj@?tDC|FAfBG`JC~EArDA~EIrRCfJElNKrY?j@GnNOt`@IlVAx@IxVEfJA~EIfQG~LA|BItVBtBBv@?N\\vDBRRtA^`CHj@Hj@f@hD^`Cp@nEVfBp@vE?@|A`KBTrCnRhE|YzDbXrA~Il@xD~BvLbDlP~@|Eb@|BDRtExU~CbPxBdLpElUlDnQjDnQxEdVZbBz@pEjA~FnArGt@zDnBxJtAfHzAzH^hBfCnMNx@x@`Ez@jEr@nDb@|BDLb@|Ad@tA`ApB~@lBZp@lEzIjD~GrC|FjBrD@@pCzF|DdItAnCTb@~IrQ`@t@`B~CHPTb@rApCBFdBjDTb@jD~GRd@FHlB|D\\t@j@jAP`@f@hA"
                     },
                     "start_location" : {
                        "lat" : 36.7581247,
                        "lng" : -114.2352608
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 521
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 36.7362588,
                        "lng" : -114.4364748
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCarp Elgin Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gie_F~umyTOPOJYDE@Q@K@gALa@FW@c@FQBQDCBEBON]Z[ZCB?@mBfBWTCDML[ZMLUPMDQCMIKQs@qBe@mA"
                     },
                     "start_location" : {
                        "lat" : 36.7325154,
                        "lng" : -114.4356795
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 mi",
                        "value" : 1302
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 241
                     },
                     "end_location" : {
                        "lat" : 36.7452524,
                        "lng" : -114.4448671
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "s`f_F|zmyTeCbA_@NOFy@Zk@Nc@TKH[Ta@d@oBdDA@eBxBA@e@XcA\\uCn@eAz@aD`Gg@rAe@r@W\\eChC{AtAIH_Al@gAd@o@Vo@b@e@^c@T_@LSVKTCX@RJ`@"
                     },
                     "start_location" : {
                        "lat" : 36.7362588,
                        "lng" : -114.4364748
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "5.6 mi",
                        "value" : 8956
                     },
                     "duration" : {
                        "text" : "26 mins",
                        "value" : 1544
                     },
                     "end_location" : {
                        "lat" : 36.6938408,
                        "lng" : -114.5043723
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eKern River Pipeline Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "yxg_FlooyTTn@r@pBd@dAHR\\f@v@fADFvAnBhAlBXl@~@hBx@jB`@x@X\\`BlDNTNXpBzD`@n@h@p@FFd@l@l@fAdAjAV\\Xd@b@bAJZPl@F^NZr@pADFx@lA^j@bAjBdApBn@dA`AfB|@bBXd@Zj@n@|@\\`@^h@BN@RP`@X`@|@zAvBtDLRt@pAnDhG~A~CbBdD`A|AVd@t@pArAxBhCrEJPnBrDjAtB|DzGf@|@BBT^j@|@Xd@p@nAl@hAhBfDn@hA|@zAv@lA`@n@DHd@r@v@vAn@pALVd@|@\\j@rC~ElBdDbDxFlAzBvAbCzAhCjB~CbChEJN?@lAtBvA`CxA~BhCjE@?Tb@|B`EtAfCb@t@zAjC~@hB^p@fBbD`BbDFJjB~CzBvDvBtDNX@?xAfC?@rDvGn@hAbA`Bt@lA`AvA?@rApBn@`A`@t@Xj@^v@BHXh@fBdDzFbKbAhBDFpBfDRZdAfBjAnB|@|ALTFLvAtCdAhBzA~B|BzDHPlBnDnA~BlAtBxAjCbAfBxAjCDFH@F@FABAHARMTOFGtAqAv@w@PQb@{@f@o@TW\\MTMXMh@a@RW\\]~@_AHOTc@LWLe@Rq@d@u@lBqC\\e@`@WVS@?XWTi@x@eBr@}AHYV}@T{@d@gA`AmBDKd@y@Va@b@QNARCH?JAPCZI"
                     },
                     "start_location" : {
                        "lat" : 36.7452524,
                        "lng" : -114.4448671
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 212
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 36.6928359,
                        "lng" : -114.5023877
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ow}~Ehc{yTp@}B`AoCd@e@Re@H[NU"
                     },
                     "start_location" : {
                        "lat" : 36.6938408,
                        "lng" : -114.5043723
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 231
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 36.6912188,
                        "lng" : -114.5039775
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto the ramp to \u003cb\u003eI-15 S\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "gq}~E|vzyTRVz@|@VV^\\n@l@XXFHJJ`AfADDBBB?L@"
                     },
                     "start_location" : {
                        "lat" : 36.6928359,
                        "lng" : -114.5023877
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 mi",
                        "value" : 2119
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 304
                     },
                     "end_location" : {
                        "lat" : 36.6749429,
                        "lng" : -114.5159186
                     },
                     "html_instructions" : "Merge onto \u003cb\u003eI-15 S\u003c/b\u003e",
                     "maneuver" : "merge",
                     "polyline" : {
                        "points" : "cg}~Ez`{yT~@hApG`Il@p@b@h@bBhBBBVVtAvAjAhAxArA^Zd@`@p@j@h@b@fAx@DD\\VRNHF\\VNLzAbAl@b@JFRL\\T^TJFRL^RZRbAh@\\R@?~@h@HDTL\\PdAh@\\Nr@^JDtAj@LFbA`@VJFBbA^pAf@PHbA^dDpA@?`A^lAd@v@XbBp@FBx@Z@@lAh@RJf@VTJf@Vx@f@RLhAt@fAx@"
                     },
                     "start_location" : {
                        "lat" : 36.6912188,
                        "lng" : -114.5039775
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 687
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 83
                     },
                     "end_location" : {
                        "lat" : 36.6716226,
                        "lng" : -114.522207
                     },
                     "html_instructions" : "Take exit \u003cb\u003e93\u003c/b\u003e for \u003cb\u003eNevada 169\u003c/b\u003e toward \u003cb\u003eLogandale\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOverton\u003c/b\u003e",
                     "maneuver" : "ramp-right",
                     "polyline" : {
                        "points" : "kaz~Enk}yT@L@B?@x@r@PNJJNNTV^`@X`@^f@BBRXBDTZXd@@@T^Xh@RZHNHRLVFLN^Tf@@@Vp@JZL\\BFL^Pn@BFTx@R|@VlAVzAFb@Hh@?@PpA"
                     },
                     "start_location" : {
                        "lat" : 36.6749429,
                        "lng" : -114.5159186
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 674
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 196
                     },
                     "end_location" : {
                        "lat" : 36.6660145,
                        "lng" : -114.5193774
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eNV-169 S\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eN Moapa Valley Blvd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "sly~Exr~yTdAo@FE^S^SXQDCVOFC^S^U^Sv@_@NE`A_@~@[fBm@dBk@lEyA`A]jC{@"
                     },
                     "start_location" : {
                        "lat" : 36.6716226,
                        "lng" : -114.522207
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.5 mi",
                        "value" : 5633
                     },
                     "duration" : {
                        "text" : "22 mins",
                        "value" : 1310
                     },
                     "end_location" : {
                        "lat" : 36.6629322,
                        "lng" : -114.5617922
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qix~Eba~yTRxABPNbATtANdAr@tANXJt@F~BM|Ag@LIBo@j@?@mCrCWXu@x@WX[r@UP]X{@n@c@ZM^Sh@_@HYDGD]XSPBd@LF`@P@?V\\?@`@DZDhAg@VMt@G|@NTBrAPdANb@Dh@H|@Vx@VHBpAXv@XdBl@B@VXX\\VVThC?FXTZT@?b@@fA@lB@`@?~@@F?jBF`@BVb@fB]NCn@b@`@Fv@JLHXTB@RAJAPi@F_ACC]e@Cc@Eo@Nc@FOR?b@AV?HE\\U@?n@b@h@b@\\XB@^ANAPH`Ab@Bh@?BAj@Ax@KhAAPAfA?`@KvASf@@b@SbEAHQb@@h@ChAEt@IvAADmA@Uj@CVCj@Cl@Zh@D`@@JKZIR@R@Xj@^HDMl@CXKdCC\\ALKvAKxAOr@Df@Cb@U|CBlB?@If@Ij@CNK|@?FEj@El@Cj@KvACj@ALCjAAv@G^Ih@ETMnBEj@Cj@K~AH`@FTERKh@WpAm@tIIfCEHQ`@AvAGp@KvAKvAKbBE^S`C?@m@|@aB`C_AtAYt@i@zAGfAI~@DVr@vEf@jDRrAYhACHgAzCc@jAyAbEc@jA]bAyB~GcA|C"
                     },
                     "start_location" : {
                        "lat" : 36.6660145,
                        "lng" : -114.5193774
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 834
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 149
                     },
                     "end_location" : {
                        "lat" : 36.6559401,
                        "lng" : -114.5592959
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLewis Ranch Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ivw~EdjfzTtAC`GIzAG\\?b@ADAlACp@Gh@O`@QBAVONO`@c@Xc@T[RSLMZSf@[HELGvAs@FERKj@[LG`Ai@BAd@Or@Qf@GXA`@A"
                     },
                     "start_location" : {
                        "lat" : 36.6629322,
                        "lng" : -114.5617922
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 199
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 29
                     },
                     "end_location" : {
                        "lat" : 36.6546787,
                        "lng" : -114.5577367
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "sjv~ErzezT\\Uf@e@b@w@p@kAl@y@p@}@"
                     },
                     "start_location" : {
                        "lat" : 36.6559401,
                        "lng" : -114.5592959
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 579
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 105
                     },
                     "end_location" : {
                        "lat" : 36.650521,
                        "lng" : -114.5573408
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wbv~EzpezTd@Nb@F\\IVEHEdAe@rAw@DGv@_Aj@_ARYt@kA\\Y\\KFAb@Jb@^`@j@v@xAb@r@@BPV`@\\f@@"
                     },
                     "start_location" : {
                        "lat" : 36.6546787,
                        "lng" : -114.5577367
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 884
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 141
                     },
                     "end_location" : {
                        "lat" : 36.6448307,
                        "lng" : -114.5507111
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "whu~EjnezT~C_Jx@aBT_@\\c@nAcB`BsAdC}BrBmBp@o@hCaC~A_Bt@u@d@g@JILENEJ?H@"
                     },
                     "start_location" : {
                        "lat" : 36.650521,
                        "lng" : -114.5573408
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.6 mi",
                        "value" : 13820
                     },
                     "duration" : {
                        "text" : "56 mins",
                        "value" : 3386
                     },
                     "end_location" : {
                        "lat" : 36.5421742,
                        "lng" : -114.5994735
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMoapa Ride About\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eet~E|ddzTF@H?HCDCRO^i@|@}@t@y@|BqHrCgJDKFMLMLGREb@EfCAF?xAGDABC@A@CBGn@sCZyAHUDGDCD?dCCt@G\\AV@HCzAa@b@MJEBCn@{@NUDAB?H?V@V@h@BL@VBLDPFt@^^Lj@R\\H`@Hv@NTJrAr@NFTDN?JAjB[JEFCFAFAT?T@PB|@Hz@JH@Z?R?N@l@BF@F@x@VNB^BtAFfAGf@AjCGZCHAbDm@LCR?T?bAIzAJN@\\Jt@h@^^d@CZH`@FTDf@D`@DRFTJHBZt@b@r@TVvA|@TNfA~@tAlAPR`@b@^\\VT~@|@ZXrCjCDHR`@JTP`@NTLRTf@z@hADBTJTF`@DhAJf@Pv@ZDBvBnA|@h@TDNB\\Hl@D\\CJEb@Y|@s@NKZQ@APGHERAP@RBVJt@f@vClB^Nj@D`@@N?HBFDFDFBD@H?DCFEPOBCL]Rg@@?BMBS?KGa@Gg@CUAK@IBKDIFELI^G`@Bf@Rl@d@FLj@|@rApCHZDj@FvABTNpATtA\\dAXj@X`@@?^V`A`@ZBF@TBZ?VCTCVIJGNGVG@?LAN@b@Nz@`@bC`BDDtClD^\\bC|BxD~Cj@^^RPPJJn@x@PRt@x@d@t@Xj@L^Jd@Jd@JTLRfAp@`@\\nCbClB`BvCxCx@`@dB|@jCp@jC~B\\\\bEdB?@lCfCpBlBbA`AtCxA\\RxGfAd@?V@x@?hAXlBn@lBPv@DXBLFLJ@@bCtCt@j@n@d@j@VFBbCv@bAnB`AhBv@lAnAtALPjC|AZRjAXl@B~AAj@AzBLvCEvDg@~@Qt@Y\\IRCfAM|DIvCER?N@dAJfAML?JDPJNNx@zAR^bB~CJTf@lAj@n@N`B?@z@vAt@tArAfCzApAPNvDlA^Lp@Vf@RlBjA~@\\d@PZTt@r@|@x@hDF`BdAf@\\|AtBtBrChAr@dBfAzCrAlAh@TBpD\\hBNbAWbC^nD~@dCzArAz@hFbDh@`ArBpDpDtDlDpBhAn@pBpBtBjEZp@pAvD\\R~@l@tE`Cl@ItASbDTL@bBfApBv@`A`@`@N^NjEv@h@JdGlAr@XxJ|D|C~@f@NnER@?hDdA`AZ~BvAhBfAvDrBfAxAhAh@r@p@hBfBbEvDn@dAFhB@FChCPjAD^lAT@?"
                     },
                     "start_location" : {
                        "lat" : 36.6448307,
                        "lng" : -114.5507111
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 mi",
                        "value" : 706
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 187
                     },
                     "end_location" : {
                        "lat" : 36.5411638,
                        "lng" : -114.5918141
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "qc`~EtumzTDO`@cBXqANq@FUPwARwBNkB@INkBR_BBMTmAVaBDe@BU?U?c@EyA?GOeCCk@IwAAMAm@"
                     },
                     "start_location" : {
                        "lat" : 36.5421742,
                        "lng" : -114.5994735
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7.1 mi",
                        "value" : 11405
                     },
                     "duration" : {
                        "text" : "30 mins",
                        "value" : 1783
                     },
                     "end_location" : {
                        "lat" : 36.5059045,
                        "lng" : -114.690592
                     },
                     "html_instructions" : "Sharp \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-sharp-right",
                     "polyline" : {
                        "points" : "g}_~ExelzTRd@?@Pb@Rd@Pd@Rd@d@jAPd@x@pBb@jApBbFd@lALX|@|BrCpHRd@zA~Dd@jARd@\\|@Zp@@BP`@HRFPJZXn@Rd@b@jAjB~ETl@xA`EPd@Pf@L\\BFRb@Rd@Tb@Rd@b@~@DFV^RXDDX^X\\X\\X\\HJPPX\\LLh@j@bDjDrAvALL|AdBpAvADDh@^t@h@j@ZlAr@XNRHh@Rd@P~@^lCz@^HVFz@ZrAr@~Av@B@fJ~D^PfAf@|BdAdAh@zAr@LFzAf@\\J`@JB@^DH@f@@~@Ct@BfAJj@Np@PlBp@rAd@|@X\\Jx@Vn@Xl@Vt@n@VN\\Rv@d@hAh@D@VT\\XTR`@b@RR|@bAp@r@BDl@p@`@h@X\\DFj@~@Tr@Xv@Lh@Rj@RZJP\\\\JHJHRLBBb@LtAb@lCdAF@|BbA@?\\Pb@T~@b@\\RXPf@PJDPN@?j@Xb@`@FJVb@Vl@^r@DFTRb@Z@@v@f@XFNF\\J\\@f@XVLf@`@d@^t@HB@h@NZh@RB`@F@?b@Cf@CbACB?^Ab@Ct@GbASVIZIHCl@GLB\\HD@ZTX`@FHZl@Tf@Vd@DFHN`@ZT`@HNpAfDP|@?N?j@Ct@?v@?lADl@Pp@Pd@h@pEF|@Hn@N`@TZd@pAGr@EbAALGd@EZGRERe@zBQ~@Ml@Md@]|AUrA?l@@j@?lA?v@BnD?b@?v@AtACbBClBAhAC`A?RKbAADEd@CRCVKl@Gf@G`@Kr@ABCf@Cd@QrAIj@Mv@Cl@A~@@h@BRBJ@b@Ad@GVKd@Qj@Qh@Od@GPENO`@YtAU|AQ~AYdCW|ASpAu@xGKdAYjDKzACj@W|Bc@bDm@vDGZ[pCAFAx@@|@Dv@Dn@A`@ATI~@?@Oz@G`@?`@?@@\\Az@?pD?rD?~L?dJ?vH?n@?nK?rD?p`@?hc@?TAhE?~E?vDBbU?hJ@fS"
                     },
                     "start_location" : {
                        "lat" : 36.5411638,
                        "lng" : -114.5918141
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "3.9 mi",
                        "value" : 6307
                     },
                     "duration" : {
                        "text" : "19 mins",
                        "value" : 1152
                     },
                     "end_location" : {
                        "lat" : 36.4579821,
                        "lng" : -114.7282032
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eOld Spanish Trail Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{`y}Edo_{Tn@p@zF`EjYhSh@`@z@n@nE|CbBlA`CfBhDbCjGlEHFxEbDzF|DnB|AjBzAdA`AtEjDfEtCfCbBtCpBvDtCbBpAfD`C`@\\z@r@jA`A`@NVHXJVLXP`@ZVRlAbAtCzBfAt@rE~C~@p@vEhDnHfFdD~BhBtA`BjAlBfAz@j@\\^VVfBvAFDnB|AZZ`@`@TRh@b@dAp@hAp@l@d@hBtA`@Z^XrCfBbFhDRNtDnCd@\\xCzBdD~B~AnAjA~@bBxAx@p@`C`ArC`BnBtApB|AVR~CxBJHpExCnBdBrBdBRN`BvAfBpAtCpC"
                     },
                     "start_location" : {
                        "lat" : 36.5059045,
                        "lng" : -114.690592
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 mi",
                        "value" : 431
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 94
                     },
                     "end_location" : {
                        "lat" : 36.458973,
                        "lng" : -114.732855
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eValley of Fire Hwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kuo}Efzf{T_DzWEXETId@Op@"
                     },
                     "start_location" : {
                        "lat" : 36.4579821,
                        "lng" : -114.7282032
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 216
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 36.4594224,
                        "lng" : -114.7351973
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "q{o}Ejwg{T?Ne@|Ds@dG"
                     },
                     "start_location" : {
                        "lat" : 36.458973,
                        "lng" : -114.732855
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "5.1 mi",
                        "value" : 8210
                     },
                     "duration" : {
                        "text" : "24 mins",
                        "value" : 1419
                     },
                     "end_location" : {
                        "lat" : 36.4709615,
                        "lng" : -114.8201993
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eS R 40\u003c/b\u003e",
                     "polyline" : {
                        "points" : "k~o}E~eh{Te@|Dq@dGeBhOuAxLy@fHCNcCfTi@vEmBrP[bCe@jDm@dEs@tGuGzk@kAdKa@lDIj@_@lDY`COvACRq@lF?@Mh@s@dDKf@iAfEOl@[pAWhACHUrAI^Mr@Oz@EXk@hD_A~FIn@mAtFoAvFEV}@vDu@dDQt@c@nByAbHq@fDMh@_@jBwCxMAJyBfJsAvFeAlECLq@tCMh@gC|KMh@yBrJg@zBSx@eDjL_A~Ca@vAI`@WrAo@hDi@rCCR}@`G]~BIh@[~BIxA?@ErA?hA?~@?@?d@?rAAJAj@EtA?@EfBp@|AJTLZl@rAFNJTf@hATh@DJbBdE|DtITd@DLn@l@x@t@^P^TrA\\RCF?THTTX\\FJLVXh@Rd@\\vAXnA?@^pANl@N`@p@rB@@bAjCrA`DN\\BF@BBLDZDj@@r@?h@DlB"
                     },
                     "start_location" : {
                        "lat" : 36.4594224,
                        "lng" : -114.7351973
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 mi",
                        "value" : 737
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 138
                     },
                     "end_location" : {
                        "lat" : 36.4755117,
                        "lng" : -114.8241556
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ofr}Efyx{TaAb@a@P_@Pa@PSLIFONA@IH]XEDC@g@b@]VEBIDGGCGAAGKGGGEA?GKKWCGIEO?S?MDQPKB]Eq@?aARa@FYFg@`@YnAu@dDe@nBi@~D"
                     },
                     "start_location" : {
                        "lat" : 36.4709615,
                        "lng" : -114.8201993
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "8.0 mi",
                        "value" : 12823
                     },
                     "duration" : {
                        "text" : "38 mins",
                        "value" : 2263
                     },
                     "end_location" : {
                        "lat" : 36.3834305,
                        "lng" : -114.8957094
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eLas Vegas Blvd N\u003c/b\u003e",
                     "polyline" : {
                        "points" : "}bs}E~qy{TIbCA`@Aj@?f@@t@@t@Bz@Dp@Fz@Hp@`@dCXjADNb@|Ap@fBv@xAv@nANT|D~F~BfDlDbF\\h@nIzL~FtIl@n@zGnHHHvF`G^`@lGzGjBrBhAjApMhNd@h@bAhAhDrDrDxDdBlBtBzB|B`Cl@p@r@r@rBhBLJhA|@hBnAdAn@pAr@f@V\\P\\Pt@\\~@b@xAn@dBp@HDfBv@dAb@h@T\\NPHdDvAhHzC`@NlL`FXLFBdFxB`@PlLbF`@PlL`FlLbF`Ab@`@NbDvAjInD`@NhInDbBr@fFxBnOvG`@PdDvAzXrL^P`Ab@tRjI|ZvMbCdAnNdG`@PrRjIbBr@^PbGfCvMxF`IjDnEjBRHlAh@pAl@LDv@ZjAf@hAj@xBhA^RbT`L^R`LbG^RbL`G~UfMdJ|E`Bx@^R~BnA^RpAp@nCvAj@^~@n@x@d@l@T^NPHNJLPHTFZD`@?D?VCZK`@i@hAS`@m@hA[`@[V]R_@La@HC?i@Fa@HQFOJKLINCNAV?Z@R@PDLFPJPRVX\\"
                     },
                     "start_location" : {
                        "lat" : 36.4755117,
                        "lng" : -114.8241556
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "138 ft",
                        "value" : 42
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 84
                     },
                     "end_location" : {
                        "lat" : 36.3831612,
                        "lng" : -114.8960448
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eApex Great Basin Way\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mca}Edqg|T`@h@DFLN"
                     },
                     "start_location" : {
                        "lat" : 36.3834305,
                        "lng" : -114.8957094
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "19.5 mi",
                        "value" : 31461
                     },
                     "duration" : {
                        "text" : "1 hour 33 mins",
                        "value" : 5562
                     },
                     "end_location" : {
                        "lat" : 36.1906347,
                        "lng" : -115.134085
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eHwy 91\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eLas Vegas Blvd N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Las Vegas Blvd N\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePass by Church's Chicken (on the right in 17.3&nbsp;mi)\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "waa}Efsg|T~@oAVYPYLWJYP[DGJOVY\\[PKTM\\[FGRYBEN]Rq@d@_BJS@CLQHGBCRITINAP?RBPDNFLJJLJLPLRHtA\\d@Pj@Vj@XfKpFpGfDdRxJ^Rj^hR`CnA|HbEjCrAdAd@B@v@X|@X@@bAV`BXVDb@Hr@Hj@Ft@HdAHf@FTBx@Hn@Hp@Ll@Pf@Px@Zv@b@JFPLXPz@l@v@l@JFZVfAv@RNz@n@bAt@jA|@n@f@p@f@TP|@n@~@r@`ExCn@d@r@h@dBpAjBrARNr@h@~AjA|C|BjCpBpA~@tAdAdAt@nA~@jAz@dAv@\\VjDdC|AjAbBlAhBrA|@r@HD`At@j@b@^VpEfDrA`AFFtAbAnA~@nA|@TPhCjBvB|Ap@f@vAfAbAr@p@f@d@\\z@n@rA`AfBrA~AlAhA~@b@^l@j@r@n@fAfAv@x@d@h@bAjAn@z@X^PT~@rAn@~@V`@fAfB`@x@^p@`@v@Zp@Vj@f@fAbAhCPb@d@tA|ApEHVzAlEfA~CJZlAlD|@lCt@xBTn@HT~@lCz@zB?@f@nA`@`AXr@Zv@h@jATf@f@hAZp@d@dAv@~AXl@l@lA|@bBp@pAn@fA\\n@`@r@PZr@fAt@nANTrArBb@r@p@~@HLlAdBx@fA`ArAx@dAj@t@TVlA~An@v@JLxAjBhB`Cv@bAHJHJDFz@bA^h@VZb@h@\\`@f@j@^^f@f@FFh@d@\\V^\\VP`@Xf@Zd@\\l@`@tBbAl@Vv@ZpA`@~@Vt@Ph@JZFt@Jr@Hh@FP@N@R@Z@f@Bh@@r@@R?H?Z?RAhAAhA?vAAbACpAFV@Z?T?T@d@@L?R@b@BbADz@HtAN`ANj@Hp@Lr@Lr@PjBb@dBh@`AZ`@NFBdBp@zBdA|Ax@~@h@LHNJ|@j@^V\\VFFz@n@dA|@`Ax@v@t@j@h@lApA`AfAFFX^FHPRRX\\d@JLLP`ArAZb@pBjCz@lAjA|AjA~AX^n@z@lBhCRV^f@jA|AlA`B|@jAzApBh@p@V^NRt@`AbB|B~@nAtBpC~F`IjAzA@@vAlBLNnCvDDFx@fAj@t@X^T\\Z^X^HJNRn@|@lA|AX^r@~@~@nAZd@V^FHXf@x@rAr@rAh@dAlAdC`AlBjAbCzAzCr@xAp@rA`ApB|@jBlAfCbApBVf@xAxCfBrDtBhE~@lBh@fAb@~@|BrElAfCLTdHxNPZjA`C~AdDjBxDjBxD\\p@jCnFpB~DhBvDh@dARb@FJLVx@dBbArBb@|@^v@`AlBtArCrBjEfAzBzHzOpDtHJPNZTd@DHx@~A~@pBx@~A~CvGtApCxD|HxApCh@hATb@|DbIbDtGlB~D~DdI|DfIfFfKlGrMfFjKTb@bG|LrAnCHNnIbQTb@nHhOfHzNfJ~QfEvIdAxB^t@`AnBNXj@lAt@~AxBnEpB`EpCvFxA|CNXhBjDfBxDNZHPhAxBd@fA@NBNBNDNDJFNZj@Zn@tAvC^r@n@dAh@~@LTN\\z@dBf@dAn@nAZp@nB|DFJd@fAbC~E@BPZDJDJh@fAN\\zAvCNVl@lAv@bBPXhCtFfAxB@BHLf@bALXVf@pAjCt@zAnAdCrAnCBFt@|AzBpEBFPZh@fAx@bB~BxEp@zAj@jAl@pAjBtDh@bAvCdGTb@Vh@rC|Fh@jA|CfGXl@`BfDl@tAd@~@T`@n@pA|A|CbCzEj@jA`@x@dBlDh@x@hAjCdBhDl@pAxAvCv@zAb@z@DJrBhE\\n@Xl@Xl@bDzGj@hAjA~Bn@rA|@fBP\\Rb@P\\Xl@|@jBZp@DHn@pAZn@dC`FjA`CbAtBj@jAf@`AZp@NXfAzBp@rAh@fA~@lBtArCbArB\\p@l@jAFNl@nA`@v@dAvBdAtBx@fBBDRb@p@tAh@hAl@dAdBnDv@|AJTP^n@pAj@fA^v@N\\^v@r@rA\\t@\\p@`AnBl@jAp@vA`AnBh@dAf@bAzA~C^t@r@zA`@t@Xh@`AtBd@~@`@v@d@`ArAnCp@rAfAxBR`@bArBd@bAR`@hAdCRb@`BhDnA`Cd@~@LVx@~AfAlBdAdBb@t@BFl@bA|BtD`BdCtAhBZRf@p@TXRXf@p@JLPThAxALPTX@V@BNNTTBDx@~@^`@V^PRr@n@d@j@HJHDB@F@r@v@ZXbCzB\\\\fA`APRBBbAx@\\ZHFRNNL`A|@LP^b@NRLRFJFJR`@PZV^VXLJLJNJRHdAP"
                     },
                     "start_location" : {
                        "lat" : 36.3831612,
                        "lng" : -114.8960448
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "95 ft",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 36.1903761,
                        "lng" : -115.1340795
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eLas Vegas Blvd N\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "mn{{E`cv}TJCT@N?"
                     },
                     "start_location" : {
                        "lat" : 36.1906347,
                        "lng" : -115.134085
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 mi",
                        "value" : 1773
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 481
                     },
                     "end_location" : {
                        "lat" : 36.1749444,
                        "lng" : -115.1371677
                     },
                     "html_instructions" : "Continue straight to stay on \u003cb\u003eLas Vegas Blvd N\u003c/b\u003e",
                     "maneuver" : "straight",
                     "polyline" : {
                        "points" : "{l{{E~bv}TT?fB?hD?nA@RDvC?RMP?Z@tBAtA?bB?lA?pCAtCA`C?h@AX?fACVAJ?TNdBFD@`BPVDd@JtCp@pAZjBd@fB`@rA^t@TB?ZLLDl@Xb@NfAb@d@TNH`Bz@j@ZB@XR^TlAt@pAt@"
                     },
                     "start_location" : {
                        "lat" : 36.1903761,
                        "lng" : -115.1340795
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 mi",
                        "value" : 235
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 73
                     },
                     "end_location" : {
                        "lat" : 36.1740319,
                        "lng" : -115.1348184
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eE Bonanza Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "klx{Ehvv}TJ[f@{AJ[nAqD@CJ[Ja@Dg@De@"
                     },
                     "start_location" : {
                        "lat" : 36.1749444,
                        "lng" : -115.1371677
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 279
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 51
                     },
                     "end_location" : {
                        "lat" : 36.1717922,
                        "lng" : -115.1362104
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eN 7th St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ufx{Ergv}T`Bv@XNFDFBd@TRLJDVN@@DBVLFDPJXNDB^Tr@^f@X"
                     },
                     "start_location" : {
                        "lat" : 36.1740319,
                        "lng" : -115.1348184
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "377 ft",
                        "value" : 115
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 36.1722826,
                        "lng" : -115.1373432
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eE Mesquite Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "uxw{Ehpv}TaB`F"
                     },
                     "start_location" : {
                        "lat" : 36.1717922,
                        "lng" : -115.1362104
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 mi",
                        "value" : 360
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 90
                     },
                     "end_location" : {
                        "lat" : 36.16937619999999,
                        "lng" : -115.1391167
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eN 6th St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "w{w{Ejwv}TzBlAnBbAr@^bAd@nB`AbAj@j@\\"
                     },
                     "start_location" : {
                        "lat" : 36.1722826,
                        "lng" : -115.1373432
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "282 ft",
                        "value" : 86
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 93
                     },
                     "end_location" : {
                        "lat" : 36.1697502,
                        "lng" : -115.1399596
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eWalk your bicycle\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "siw{Enbw}TiAfD"
                     },
                     "start_location" : {
                        "lat" : 36.16937619999999,
                        "lng" : -115.1391167
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "a~`bFx`spTtu@b^dZ|h@te@pY~d@``@~l@~T|d@dXdLtVkLhVfPf\\mCzoBcObjA_j@`v@eAr}ApIrxAlBxb@wXfo@yLfSaZbl@{XnoAq`@hf@wg@lu@gRhhBiXlr@wH`u@gTnxGkTvsA{t@dt@kl@`RlHb^llAbb@lJrg@dMxHna@Et{@xXv\\lMlFpUrJfJCxYzRGhWQ~AnV@f^jHpLDvc@F|m@V|}BdO~z@zl@n`FtZx_B{a@xe@sBbmA|\\~fAlM|p@lPdWtNp`@j`@ff@pz@l_Bzh@d`B~Rdh@zTmKfThJo@zYnE|j@tPvJ`[~W`Nff@rJzq@pDn\\zo@`i@nu@|v@pd@rTzJhAsA~Uy@jt@}@tVlJlP~SlX~U`p@xLyKpIjB|Mka@fPe]nfAfJ|]}MdEmUfq@gBnoBtq@zn@bEjy@}Npr@sGpY|ErQl{@}Lzl@mS`lAp[j_@xy@tj@pS|Fw@lRgJv[rCxdAlYx|AyJni@kP~LbGbH~GtnCdi@rxAZh~CvRhdA^j}AgBrrAb_@dg@d`@dj@pFre@yA~gAjb@n~Atc@vk@ba@`w@rd@rlA``Afg@dd@Bj^`UXbp@cNpYmVvYpKzu@df@p}BxmBd{DnNfeBrMdGxPz@jPfa@`mAvtBn}A`{AvjAffAnj@hr@vf@fb@p_@nR}Ozn@tz@zoEp~@j|CrIxMlDnVnd@bVfKrApNjMXfqAGlL`N~Nrb@dBbRxSjl@jmA|Zho@du@|mBjiA|sCpwA~vDbt@lgD{`AbbAwn@b@ux@rt@eb@jbA?d]d[hIpZnUiLldAsd@trDsA~aIlzArqIzqAttDfNz^{KhFmNBi\\|\\kRxQxTpb@dc@tv@x~@f`Bz|Br~Dr\\bl@`MwK`\\ig@jOcB`[l\\`a@nVzj@tXnOv^pKmBjViI|CpNyOjVdB`Dpm@|NdRyAeJn~AmKroAoJt^nQq@pK}H|c@{V`XeQ`RgOff@ef@nYdAli@dBla@v^jp@rIbmBnzAdcAb\\`YvAf\\b_@~i@dYby@fo@vlB~u@rBlJjCcQv@g\\pd@jkAna@nf@p~@h[jbAbu@j]zFlHrs@wTxbCXhcFdgCthBh}A~hAzv@lj@|D|d@}Jl{@u]zzCyItc@ev@rhDqF~h@zNvd@rWte@oL`JaNfXtHb_@r~B`jCvzChqAh_GnmCvc@rVsH|LlIMz|Axj@tdC`wA|aAdx@`i@xqA~m@x`Azf@bYzk@`Dbo@zf@juBfgDtuHzsOxoEv{Ih]f^fr@nGbr@fOfOaGlGlD`NdQiAfD"
         },
         "summary" : "Las Vegas Blvd N",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : []
      }
   ],
   "status" : "OK"
}
-->
