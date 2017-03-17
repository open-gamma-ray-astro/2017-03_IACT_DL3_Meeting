# IACT DL3 meeting, March 2017, MPIK Heidelberg

## Basic information

* When?
  * Start: **Monday, March 20 at 2:30 pm**
  * End: Friday, March 24 at noon
* Where? 
  * [MPIK Heidelberg](https://www.mpi-hd.mpg.de/mpi/en/start/)
  *  Conference room  in the library building #12 (see [MPIK site map](https://www.mpi-hd.mpg.de/mpi/en/contact/access-and-site-map/), up the stairs, to the right)

* Contacts:
  * [Christoph Deil](https://github.com/cdeil) and [Catherine Boisson](https://github.com/cboisson)
* Remote participation: probably not, please come to the meeting.
* We will do a call the week before to prepare the meeting.
  * **"IACT DL3" call on Tuesday, March 14 at 11 am on CTA eZuce.**
  * Connection info (no password, guests allowed) is [here](planning_call_connection_info.txt).

## About

This is a meeting on the data level 3 (DL3) data model and formats for imaging atmospheric Cherenkov (IACT) telescopes.

* The topic is data level 3 (DL3), i.e. the interface between pipeline and science tools. See ["Open high-level data formats and software for gamma-ray
astronomy" (2016)](http://adsabs.harvard.edu/abs/2016arXiv161001884D) for an introduction / overview / status / next steps on DL3.
* The main focus is on [CTA](https://www.cta-observatory.org/)! Participation by existing IACTS (e.g. H.E.S.S., MAGIC, VERITAS, FACT), or similar telescopes (e.g. HAWC, neutrinos) is encouraged, their experience especially with instrument response functions (IRFs) is an important input for the discussions.
* This is a follow-up on the workshop from last year (see [2016-04_IACT_DL3_Meeting](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting)).
* The meeting will be announced on the [open-gamma-ray-astro](https://lists.nasa.gov/mailman/listinfo/open-gamma-ray-astro) mailing list and cta-data, and forwarding to analysis mailing lists of existing IACTs is welcome.
* This is a CTA meeting, but everyone interested in the topic is welcome to join (at last year's meeting, we had the same policy, but in the end all participants were CTA members).

Goals of the meeting are:

* Get an overview and update from the CTA side on the aspects that influence DL3, such as planned observing modes to support, IRF precision requirements and status and plans for IRF production.
* Make progress on the DL3 specifications at [gamma-astro-data-formats](http://gamma-astro-data-formats.readthedocs.io/).
* We have been stuck a bit since last year with major questions concerning
  the data model and formats, e.g. on how to organise the data and link the pieces. Other major points are listed in [2016arXiv161001884D](http://adsabs.harvard.edu/abs/2016arXiv161001884D).
  We would like to make some real progress on those key DL3 issues, and try
  to develop something that can support CTA well and then prototype it in the coming year.
* By the end of the week, have a document summarising the information that determines the CTA DL3, and one or more concrete options to do it outlined, with action items what to investigate next (in 2017) to make progress listed.

The following things are not topics at this workshop:
* CTA pipeline or science tool software development. DL3 is the interface between these softwares, and participation and feedback by people working on those codes is highly encouraged. But the focus here is on the DL3 specs, work on the codes to implement or prototype can then continue after the meeting.
* Lower-level data, e.g. air shower images.
* Higher-level data, e.g. sky images or spectra.

## Agenda

### Monday afternoon

We will start with presentations on Monday 2:30 pm.
A telcon connection will be provided (CTA eZuce, "IACT DL3", no password)

* Tarek Hassan: DL3 FITS in Magic (5 min)
* Christoph Deil: DL3 FITS in HESS (5 min)
* Jim Hinton or Alison Mitchell: overview of proposed CTA observation modes and IRF requirements
* Tarek Hassan: proposal for point-like IRF format in DL3
* TBC: status DL3 from the science tool side (Gammapy & ctools)?
* Tarek & Christoph: thoughts on CTA DL3
* Open discussions on DL3 (with focus what to do this week and in the coming months for CTA)

###

The rest of the week is reserved for discussions & document or spec writing.

## Participants

* Catherine Boisson
* Tarek Hassan
* Jose-Luis Contreras
* Bruno Khelifi
* Christoph Deil
* (some others for the presentations / discussion Monday afternoon)
