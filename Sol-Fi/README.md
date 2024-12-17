# Sol-Fi

For this project, it is important to mention that the dichroic filter has a disc shape.

* **SunlightCollector+Dichroic01.FCStd**: The main structure (_FullBase_) can hold up to two LC and dichroic filters for multiplexing. In the single-channel configuration use the one on the left with no dichroic filter. The _FibreFixer_ can be screwed on the output of the sunlight collector and fits into the _FibreHolder_, which in turn fits into the _FullBase_.
* **dmd-dichroic.FCStd**: The _DichroicHolder_ part can be fixed to the DMD board and the optical engine using screws. The left pole has a hole for the plastic optical fibre which captures light from the sunlight collector. The _7degBase_ part sets a fixed inclination to the _DichroicHolder_ part. The _Dichroic-Holder02 (Mirror #1)_ can be fixed at the front of the  _DichroicHolder_ part and can hold the dichroic filter in the dual channels configuration.
* **lenspcx02.FCStd**: _Base_ part is the main holder and it should fix the output of the sunlight collector and the fibre that receives the light coming from that output. To achieve this it uses two instances of the _MainSCHolder_ part and the _FibreFixer_ part to hold the output of the sunlight collector and the _FibresHolder_ part to hold a bunch of fibre pieces surrounding the fibre that captures the light and conveys it to the DMD. This allows heat disipation.
* 
