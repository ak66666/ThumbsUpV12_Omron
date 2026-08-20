# ThumbsUp! v12 RP2040-based ProMicro 3x12 chord keyboard for Omron and mouse switches.
                           
Steno/chord keyboard (number key instead of a bar)
2-key Thumb Cluster
Cirque ProGlide trackpad/touchpad


Omron mouse switches or 6x6 two-pin switches.

* RP2040 ProMicro x2
* TRS (3-wire) audio cable to connect the halves.
* USB-C connectors.

Silicone O-rings are used for the key paddles suspension: CS2.4mm, OD 11mm (12mm works too).
Cross section 2-2.5 mm works well.
OD less than 11mm result in much heavier keys. 
OD more than 12mm is a bit too loose.


# Rev.6

Made the thumb keys reverseable - their hinges were separated from the top keys/trackpad cover.
That little two-key hinge could be placed closer to the front edge, in somewhat return to the rev.0/rev.1 layout.
Otherwise it is the same as rev.5

Reversed keys are more comfortable when the board is below elbows level, but placed on the desk thumb keys are hard to reach.
So, not sure if it much better than rev.5.

![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.6/IMG_20260819_211209259_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.6/IMG_20260819_211225304_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.6/IMG_20260819_211230658.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.6/IMG_20260819_211301243.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.6/IMG_20260819_211314177_HDR.jpg)


# Rev.5

Re-worked the cross-board connections: 
Replaced the mix of pin headers/sockets and stand-offs with individual stand-off for each key, plus one in a corner.
This way the boards should stay flat, no twisting due to minor height mismatch and the connectors pulled upwards unevenly.
Hopefully that will equalize the key reactions, uniform the feel.

Split the top board in two parts - to move the thumb keys higher and a bit closer to the index finger column. 
If it was left as a single detail - it would be C-shaped board with a thin profile, could be easily broken, and, probably, harder to manufacture and deliver.

Moved the MCU, connectors to make room for the stand-offs, re-laid the tracks where affected.

![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214554678.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214603801.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214622668.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214647605.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214702145.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214757023_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/reversible_thumbs/Photos/rev.5/IMG_20260805_214823374_HDR.jpg)



# Rev.4

Moved the keys as in rev.1, as the rev.3 inherited the spacing from rev.2 and was a bit uncomfortable.

# Rev.3

Approx. 15g activation with Omron switches, reduced from the previous revisions.
Cirque ProGlide trackpad support - on both or one of the sides.
Handiness pin added.

![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.3/IMG_20260313_220132165_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.3/IMG_20260313_220141291_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.3/IMG_20260313_220251222_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.3/IMG_20260313_220259396.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.3/IMG_20260313_220304919_HDR.jpg)

# Rev.2

![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.2/IMG_20260209_195204672.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.2/IMG_20260209_195228750_HDR.jpg)

# Rev.1

![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/IMG_20260121_164555308.jpg)
![PCB Render](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/PCB_KICAD_render.png)
 
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/IMG_20260121_164613377.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/IMG_20260120_003025359_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/IMG_20251226_151121177_HDR.jpg)
![Main view](https://github.com/ak66666/ThumbsUpV12_Omron/blob/main/Photos/rev.1/IMG_20260121_164555308)

Other pictures and videos in Photos folder.

# Firmware

TX-Bolt interface as the only connectivity option for now:
https://github.com/ak66666/qmk_firmware/tree/thumbsup_20240523/keyboards/thumbsup/rev12_rp2040_split_steno
