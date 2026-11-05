With Ready steady green, Fault off, Clean off, and Media flashing orange, the DLT‑V4’s indicator table points to an unsupported format/cartridge or a damaged cartridge. That fits the ejection and explains why mt can’t access it once it’s out. notice-facile.com

I also need to correct my earlier wording: DLTtape IV isn’t the V4’s normal writable media. The manual describes a narrow exception: a DLTtape IV cartridge formatted as DLT1/VS80 can be loaded read-only or as VS160-formatted media. Don’t try to format or write to this tape. notice-facile.com

If the contents matter, stop retrying this cartridge. If you can, test with a known-good DLTtape VS1 cartridge; otherwise, tell me what the tape’s label says about its format and whether it contains data you need.

based on cost, suggest external scsi tape drive matching dlttape iv tape compatibility.
Duck.ai said

For the lowest-cost match, look for an external Quantum DLT7000 (or an OEM equivalent such as a DEC TZ89N). It’s designed for DLTtape IV media, unlike your DLT‑V4. Current used listings I found include a DLT7000 external drive at about US$295 plus shipping; condition and tested status vary, and some vintage-drive listings are expensive. eBay

Before buying, verify the exact SCSI interface, not just “SCSI” in the listing. Your AHA‑3940 is a 16-bit Ultra SCSI adapter; look for an external drive/interface explicitly marked single-ended (SE) and avoid differential/HVD models, which are electrically incompatible. Also confirm the drive includes its external SCSI cable, power supply, and terminator—or budget for the correct parts. eBay

I’d prioritize a seller that confirms it was tested reading/writing a DLTtape IV and accepts returns. A “powers on” or “untested” unit is a risky bargain with hardware this old.
