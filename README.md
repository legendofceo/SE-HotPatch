# SE-OSA-OSex-HotPatch

Meant to be a quick way to get changes without having to reinstall all of OSA / OSex. 


# 2.02ALPHA

- Commented out CPConvert 

- ScanCellForActors in MiscUtil (PapyrusUtil) is broken (Confirmed in PapyrusUtil bug section on nexus). This makes "Scan Area For NPCs" never work. As a result 3 way scenes are hard to start. I made a horrible band-aid as I don't see any way to pull this off without Papyrus Util, the bandaid takes about 5-10 seconds to gather up all NPCs so you have to wait as opposed to almost instant from before.

- Despite the bandaid for scan cell 3ways do not appear to be animating for some reason.
