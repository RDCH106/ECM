# ECM
ECM (Error Code Modeler) lets you prepare CD image files (such as BIN, CDI, NRG, CCD, or similar) so that they'll compress far better in programs such as [WinRAR](http://rarlab.com).

Here's how to use it:

1. Run the CD image file (i.e. filename.bin) through ECM to create an ECM file (i.e. filename.bin.ecm).
2. Compress the ECM file (i.e. filename.bin.ecm) using your favorite compression program.
3. Back up, transmit via Internet, or whatever you normally do with CD images!
4. When you want to burn the CD again, extract the original CD image from the ECM file.

How much space does it actually save?
--------------------------------------

The space saved depends on the number of sectors with unnecessary EDC/ECC data in them, which will depend on the specific type of CD. Here are some examples:

|                Test CD              |  Format |  Size (RAR)  | Size (ECM, then RAR) | Improvement |
| ------------------------------------| :------:| :----------: | :------------------: | :---------: |
| Metal Gear Solid (PSX) Disc 1       | BIN/CUE |  466,852,244 |       381,033,267    |     18.4%   |
| Panzer Dragoon Saga (Saturn) Disc 1 | BIN/CUE |  432,909,436 |       366,889,519    |     15.3%   |
| Tokyo Xtreme Racer 2 (Dreamcast)    |   CDI   |  474,346,319 |       389,917,790    |     17.8%   |


Obligatory disclaimer
---------------------

ECM is not intended as a tool to aid in acts of copyright infringement


* Original Author: Neill Corlett
* Original homepage Project: http://www.neillcorlett.com/ecm/
* Wayback Machine Copy: https://web.archive.org/web/20140328062622/http://www.neillcorlett.com/ecm/
