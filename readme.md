# NebulaWare
## A collection of small programs provided by Nebula R&D

This collection was originally hosted at http://Nebula-RnD.com/freeware. It's been copied here and modified for this FOSS4MV environment.

### Hosted software

#### ComparativeAQL
* MV BASIC program that enables D3 AQL statements to compare the value of one field with another as part of the selection process. This is not native functionality in D3 and is considered a feature only found in other MV platforms.

#### ConvertBase
* This program will convert any base to any other base. Assume bases are from 2 to 36. That's binary through octal, decimal, and beyond.

#### D3DecatalogPlus (formerly NebulaDecatalog)
* MV BASIC program to decatalog programs without disturbing MD items that do not point to the file containing the object code. Small but significant enhancement over default Decatalog behavior.

#### D3GetList
* MV BASIC program that replaces the GET-LIST command in D3 v9.0 and 9.1. Addresses issues not yet patched by TigerLogic.

#### FindBadCharacters
* MV BASIC program that accepts a file name, then scans every item ID and data item for invalid data that might cause problems with screen rendering, printing, or data transmissions.

#### MergeSplit
* Merge Include items into the base module. Edit and debug in a single item. Then effortlessly split the item back up into its origina items. Backup is maintained "just in case".

#### NotifyAdmin
* Rather than sending a message directly from an application when something important happens, it might be better to use a phantom to send the message, especially when the process that needs to send the message is a file trigger. Sending a message sometimes pauses a process, especially when sending to multiple recipients. You don't want this kind of pause to occur in an intense transaction processing loop, or with Web Services or other internet transactions. This code can be used as a base for a little notification module.

#### SaveRestoreAT
* Save/Restore entire accounts using AccuTerm. Save R83 and restore to D3. Save mvBase and restore to QM. Save AP/Pro and restore to Reality. Any platform combination is possible, any the code includes hooks for various combinations, but only R83 to D3 has been tested and used in a live project. See README with source for more info.

#### Snapshot (formerly NebulaSave)
* Developers will often write a lot of code and then shutdown and go off to other things. This ensures that a snapshot is taken at the time of shutdown, in case the system gets corrupted or in case a back-step is required to code. The automated process removes the requirement to remember to save, manage devices, and manually enter required accounts. [OS:Windows]

