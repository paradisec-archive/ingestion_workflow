# PARADISEC Ingestion Workflow Model
_(Last updated December 2020)_

<p align="center">
  <img width="500" src="images/Reel-BW-gh-page.jpg" alt="PARADISEC-reel-to-reel">
  </p>
  
This document was last updated 22 December 2020. Previous iterations of our Operations Manual (prior to implementation of the Nabu catalogue) are available from the downloads section of our website [https://www.paradisec.org.au/](http://www.paradisec.org.au/downloads.html).

For questions or comments on this document please contact us at [admin@paradisec.org.au](mailto:admin@paradisec.org.au), or write to us at:<br><br>
**PARADISEC <br>
Sydney Conservatorium of Music, C41 <br>
University of Sydney, 2006 <br>
Ph: +61 2 9351 1279, Fax: +61 2 9351 1287**

***Role terms used in this document*** <br>
**Admin:** Sydney Director (2020: *Amanda Harris*) **Audio:** Audio Preservation Officer (2020: *Nick Fowler-Gilmore*) **PD:** Project Director (2020: *Nicholas Thieberger*) **SA:** Systems Admin (2020: *University of Sydney ICT*)


## Pre-ingestion (audio tapes)

### Assess collection (Admin and PD)
Assess whether material is suitable for accession (PD in consultation with steering committee). Suitability should consider the following conditions, though materials not meeting these criteria are not necessarily excluded from the collection:

***Rights*** <br>
Does the depositor assert ownership of the material?
* Are the rights in the material clearly specified?
* Content criteria (assess against policy)
  * is the material unique?
  * is the country and language of the material known, and in the core area (non-Australian)?
  * is there an alternative place for deposit of the recording?
  * is the content of the recording in a high-risk language?
  * is the format or recording medium at high-risk of obsolescence?
  * institutional affiliation – give preference to consortium members
  * ease of integration into our systems
    * is data in a format we can handle (i.e. cassette, 1/4 inch reels)?
    * if not, direct prospective depositor to suitable alternative facility
  * consistency and adequacy of any metadata
  
If collection assessed as suitable, create a collection record in Nabu Assess tape condition and prepare material for transportation accordingly

### Transportation

If the recordings are in bad condition (e.g. mould, rare formats, tape visibly damaged) send to Sydney (contact Admin). Transport any mouldy items in separate ziplock bags and do not pack with non-mouldy items

If in reasonable condition transport to nearest ingestion point, personal transport is preferable; transport in hand luggage if flying, if necessary use registered courier

* Packing – make sure end fastened on reel tape, pack tightly, wrap in bubble wrap
* Ensure against unnecessary shocks during transport
* Transport with inventory of contents

### Receipt of materials at ingestion point (Admin)
* Check inventory against contents and contact depositor if any discrepancy
* Enter date in ‘data received’ field of Nabu
* Assess whether mould-affected and if so implement appropriate procedure (put in ziplock bags and store in cleaning room)

### Metadata
Where possible get depositors to enter own metadata in Nabu:
* User signs up to Nabu, creating a login
* Admin or PD assigns edit access to user
  
Assign Persistent Identifier (PI) – if depositor already has a consistent naming system, use it, or else use numerical symbols for ‘item ID’, e.g. 001

Where depositor cannot enter own metadata, enter records manually or batch import records from a spreadsheet

* **For batch import of new records:** ensure all metadata is inserted into the PARADISEC basic metadata import spreadsheet located at http://www.paradisec.org.au/downloads.html (only those fields listed in the spreadsheet can be imported, and no changes should be made to fields or
headings in the spreadsheet, metadata should only be added to existing fields)
  * Open Nabu and click on the Dashboard tab
  * Click on ‘Upload metadata file’ button
  * Browse to location of file
  * Click on ‘Add Collection from Spreadsheet XLS file’
  
* **For manual entry of new records:**
  * Create item records (Admin) by adding item IDs and descriptions into the Collection screen
  * Enter all metadata available into appropriate fields of catalogue, ensuring that all compulsory fields (marked with a red asterisk) have been filled

Label all tapes and tape cases to show PI, ensuring that no written information is covered up

Sort all tapes in numerical order in filing cabinet, or in dirty room if mould-affected

When tapes returned, note date in ‘tracking’ field of Item, Archive Information and tick ‘Tapes returned to depositor’ checkbox

### Photograph tape covers and casings to capture all handwritten metadata
* Image files should be named with the same PI as the audio files
* Archival copies of images should be in tiff (.tif) format, jpeg (.jpg) copies can be archived as additional access copies
* The whole image should be captured, but in some cases it might be desirable to zoom in to the text to make sure it is fully legible in an additional image
* Even blank surfaces should be photographed to ensure that no metadata has been overlooked
* Include a ruler in the captured image to indicate scale
* See the Appendix at the end of this document on guidelines for image capture and also the Austehc image capture guidelines in the 2011 PARADISEC Operations Manual for more details

### Prepare tapes for ingestion (Audio)
* Assess tape condition – treat mouldy items according to the below procedure *(wear a mask and latex gloves as protective gear)*
* Dehumidify in vacuum oven if necessary, with separate batches for mould-affected items
* If necessary, advice regarding duration of treatment and temperature can be found at [NFSA](http://nfsa.gov.au/) and also within the IASA [TC-04 Guidelines](www.iasaweb.org/tc04/audio-preservation)
* If mouldy remove any visible growths first with cotton bud or pad and solution of isopropyl and cetramide
* If sticky shed is present no special prior treatment is needed
* Clean and prepare for ingestion

**Reel-to-reel** <br>
* Repair or replace lead tape and damaged splices if necessary
* Clean using slow spool and specialist equipment (cotton pads and isopropyl/cetramide solution); also clean flange (spool) separately
* Perform a second slow spool to repack tape

**Cassette and DAT** <br>
* Replace splices if necessary (cassette)
* Fast forward and rewind to minimise print-through (cassette) and to repack tape (cassette and DAT)
* If mouldy, bag up separately, to avoid cross-contamination, shelve in PARADISEC's *Dirty Room* and minimise time in *Ingestion Room*, replay on designated *dirty* cassette machine

**Information on devices and servicing**

|  Format  |  Device  |  Date last tested  |
|  :---  |  :--- |  :--- |
|  Cassette  | TASCAM 122 Mk II | July 2014  |
|  Mouldy cassette  | Yamaha KX-W32  | July 2014  |
|  Reel-to-reel 15 ips  | Studer A810  | July 2014  |
|  Reel-to-reel 7 1/2 ips | Studer A810  | July 2014  |
|  Reel-to-reel 3 3/4 ips | Studer A810  | July 2014  |
|  Reel-to-reel 7/8 ips  | No suitable in-house machine | as of October 2015  |
|  Minidisk  |  Processed at Melbourne | n/a   |
|  \*.wav files | Procesed at Melbourne, ANU or APAC  |  2015  |
|  DAT  |  Sony PCM 7040  |  July 2014  |
|  CD  |  CD inspector on Audiocube 3  | n/a |


## Ingestion process

### Wavelab ingestion processes - Sydney Lab (Audio)

* Avoid internet browsing and any activity over the network during digitisation (these activities can cause interference, which may result in digital clips and unwanted errors in the signal), avoid using or turn off mobile phones or other mobile devices, including close wi-fi transmitters, and as a precaution, close any programs other than WaveLab during recording of audio. 

* Reel-to-reel tapes go through Audio1 workstation (where StuderA810 is connected), cassette tapes go through either Audio1 or Audio2 workstations (both fitted with Tascam 122MKII’s cassette tape machines). Other sources, such as vinyl records, are to be connected separately as required and may, depending on how the device is connected, go through either Audio1 or Audio2 ingest stations.

* Open the ‘record’ dialogue box (the button with the red circle at the bottom of the screen) and type in the name and path of the file that you will create. The destination folder will, on either audio machine, be ‘D:/WAV96 ingest’ (shortcut on desktop) followed by the name of the audio file ‘CollID-ItemID.wav’. Relevant subparts of an item are indicated ‘-A’, ‘-B’ for example, and are inserted after the PI and before the extension.

* If digitization is being done from a copy tape (rather than an original), then ‘copy’ needs to be added into the third part of the filename (e.g. ‘AC1-001-A_copy’). This is so that we can avoid having to overwrite DOIs if a later file is produced from the original; the subsequent file can then be added, rather than replacing the ‘copy’ file, and it can be appropriately named (e.g. ‘AC1-001-A_original’).

* If further work will be required on a file, such as splitting it into two separate channels, then the file should take a name that is distinct from the files that will ultimately be produced, to preclude any confusion. For instance, if the files to be archived will eventually be named AW1-001-A.wav and -B.wav and they are two sides of a single ingested recording that will require splitting, then name the file that comprises each of them as AW1-001_ The underscore as opposed to a dash will prevent the file from being erroneously archived. (Using Rif64 file format in Dobbin, we can now overcome our 2GB limit and so splitting of large files is not usually necessary).

* It is a good idea to run the signal for a few seconds and adjust the level on the source selector so that it maxes out at about -100 dB on the record dialogue (the white stickers on the source selector are a rough approximation of good gain levels for the selected source). After a good level is established, return the tape to the beginning and commence recording, leaving at least 5 seconds of silence before the signal begins.

* Adjust the azimuth - this is the angle at which the tape meets the head, and we want to adjust it so we can get the sharpest (closest to original position of record head) possible signal. You will need to have the cover off the tape deck. In the monitoring window, enable Phase scope in WaveLab - you will see a graph in the bottom-right, with clusters of moving points showing as the tape plays; ideally, these should line up along one of the axes. [Cassettes] Take the small flat screwdriver, and tweak the screw on the bottom-left of the cassette playback head slot (not the right screw), while the tape is playing. Use only very small movements – you don’t want to unscrew the screw and lose it in the machine. Listen carefully – you should hear the recording start to become sharper, as well as see the points start to line up more on the graph. Adjust the screw back after use. [R2R] Adjust the azimuth as it plays - use the allen key to turn the screw behind the heads. You should hear the recording get sharper, and see the moving points start to form a straight line in the graph in the monitoring window.

* pay attention to the recording and note any analogue errors, such as pops, hisses, buzzing, microphone bumps. These should be noted in the ‘ingest notes’ in the catalogue. More generally, note the overall quality of the recording — whether it is at all muffled, distorted or good and clean. This information should also go into ‘ingest notes’.

* analyse the file in Wavelab (shortcut: control-Y) (takes about 2 minutes for normal length file) — this generates temporary error markers wherever recording faults are apparent

  * check any errors: if they are analogue errors, make a note of them in ‘ingest notes’; if they are digital errors, re-ingest – file size, waveform, length sample rate might need to be checked and adjusted in Wavelab. Where more serious corruption has occurred, check the most recent backup (there should be one somewhere). Keep regressing in stages until you find a version of the file’s history that is not corrupted. If no such file exists, contact the depositor to establish if the file had been corrupted prior to being received.

* Enter additional metadata into Nabu
  * Enter dates digitised
  * Enter name of operator in Operator field
  * If recorded tape ID mentions date created, tape ID, recordist, or any other info not already in database, fill in relevant fields (check with admin as necessary, if unsure, leave blank)

* if necessary, normalise the file. This should not normally be necessary where premonitoring has taken place and the tapes are in good enough condition to yield a good quality sound level.

* after ingestion finished, trim silence at beginning and end of file, leaving margin of 5 seconds’ silence
* in the case of stereo reel-to-reel tapes that comprise two simultaneous mono recordings, split the 2 channels

* name the files appropriately (for the time being, leave the raw, unedited files (the ones with underscored names instead of dashed ones) in this folder until a later backup can be made)

* check that mandatory metadata fields (PI, title, date created, country, collector) are in Nabu catalogue, if not, add them. If you are unsure of what information to enter into the catalogue, liaise with Admin

* Before adding files to Nabu, all mac users must ensure they delete any hidden files (they start with a . e.g. ‘.DS_Store’) so they do not cause errors, and also delete them immediately from the ‘Processing Area\forDobbin’ folder if they appear in there during the process of copying files across. To do this all Mac users must switch on viewing of invisible or hidden files. Instructions can be found here: [http://www.macworld.co.uk/how-to/macsoftware/how-show-hidden-files-in-mac-os-x-finder-funter-3520878/](http://www.macworld.co.uk/how-to/macsoftware/how-show-hidden-files-in-mac-os-x-finder-funter-3520878/)

* place files in **parapd00470.srv.sydney.edu.au\Processing Area\forDobbin**, this will trigger Nabu to create matching .imp and .id3 xml export files (see below section *Dobbin Processes for BWF generation* for details). Otherwise, if more work will be undertaken at a later time, files should be placed on the server in **parapd00470.srv.sydney.edu.au\Processing Area\waitingArea**.


### Dobbin processes for BWF generation (Audio)

* NABU monitors ‘forDobbin’ directory for .wav files, and when it finds one, it writes out the metadata for the corresponding item – if the item is marked ‘Ready for metadata export’ in the Item’s Admin panel. The exported metadata files are:
  * **parapd00470.srv.sydney.edu.au\Processing Area\xml\[PID].imp.xml**
  * **parapd00470.srv.sydney.edu.au\Processing Area\id3\[PID].id3.v2_3.xml**

* XMLcheck monitors ‘forDobbin’ directory, and if a .wav file exists, it then also checks to see whether both the corresponding .imp.xml and .idv2_xml files exist. If both xml files are in the right directories, it moves the .wav file into the directory ‘processed\fromDobbin’.

* Dobbin monitors ‘forDobbin’ for .wav files. When it finds a .wav file, it begins processing it. To do this it requires the .imp.xml file and the .idv2_xml files to be in the correct locations. Dobbin outputs a sealed BWF file with a .wav suffix and a derivative .mp3 file. Dobbin also produces a .qua file for each of these. These .qua files are generated only after the files have been successfully written to the output directory, which is ‘processed\fromDobbin’.

* BWFhashgenerator monitors the ‘processed\fromDobbin’ directory for .wav files. If it finds one, along with a corresponding .mp3, .wav.qua and .mpqua, then it generates a hashsum for the wav and mp3, and writes them out to a file named [file]-checksum-PDSC_ADMIN.txt, which will contain the checksums for both wav and mp3 It then writes both .wav and .mp3, as well as the checksum .txt file, to ‘toNabu’, from which NABU harvests archive files.

* this process commences once the wav file is in the folder ‘parapd00470.srv.sydney.edu.au\Processing Area\forDobbin’ and the necessary metadata has been entered into the catalogue (see above). Wrapping includes the necessary metadata and digitally seals the file to prevent it being altered

* a backup of the file is kept in ‘parapd00470.srv.sydney.edu.au\Processing Area\processed\forDobbin’. This folder is used as a backup of the raw .wav files before they are processed in Dobbin and uploaded to the archive as bwfs and mp3s. Once we have received a report from Cron <deploy@paradisec> stating the file was SUCCESSFUL in its upload to our catalogue and the file appears in Nabu in its proper format, with relevant matching metadata. Then we can delete our original raw .wav backup copy. If this file generates an ERROR message, then we can refer back to our original .wav backup copy and reprocess.

* A script searches ‘forDobbin’ for any newly added wav files and harvests the file name, size and the audio properties and places a reference to them in the catalogue entry for that item

### Ingestion of photographic slides

### Digital text

## University of Melbourne ingestion unit

## Restore from archive proces (SA)

## Appendix: Notes on image capture equipment






