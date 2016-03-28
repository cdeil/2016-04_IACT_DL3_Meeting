# IACT DL3 meeting in Meudon in April 2016

## Contact

If you have any questions or suggestions, or would like to attend, please
contact [Catherine Boisson](http://www.iau.org/administration/membership/individual/7665/) and
[Christoph Deil](https://github.com/cdeil).

## When?

* Face-to-face meeting
    * Start: 10 am on Wednesday, April 6, 2016
    * End: noon on Friday, April 8, 2016
* Pre-meeting planning telcon:
    * Purpose: plan the f2f meeting
    * March 29, 2016 at 6 pm CEST
    * Agenda and notes at [pre-meeting-telcon.md](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting/blob/master/pre-meeting-telcon.md).
* Post-meeting follow-up telcon:
    * Purpose: short reports on action items and activities after the meeting; keep people in contact.
    * Date / time: tbd (will be scheduled at the f2f meeting)
    * Agenda and notes at [post-meeting-telcon.md](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting/blob/master/post-meeting-telcon.md).

## Where?

Observatoire de Paris, site de Meudon, 
Place J. Janssen, 92190 - Meudon

The meeting will be held in the conference room, downstairs of Builging 9, the "big dom". See the [access map](https://www.obspm.fr/acces-au-site-de-meudon.html?lang=en)

Practical informations:
A list of a few convenient hotels in Paris can be found [here](http://lesia.obspm.fr/List-of-some-convenient-hotels.html)
The selected hotels are close to Gare Montparnasse serving Meudon SNCF train Meudon and Bellevue stations or close to RER C stop (regional line) serving Meudon Val Fleury RER station.

There are also a few options to book a room in Meudon within walking distance via [airbnb](https://www.airbnb.com/s/Meudon--France).

From the train stations in Meudon, the Observatory is about 20 minutes walk uphill, whatever the station.  From the SNCF station "Bellevue" (in Meudon) to the Observatory you may catch the 9:20 am bus, TIM, going up to the Observatory. Your next chance is one hour later... 

Taxi in Meudon
"Central taxis", 24h/24h, 7d/7d  : 0146309012  or  0673385301

## No remote participation

There will be no possibility of remote participation for this meeting.

Apologies if you would have liked to join the discussion but can't come!

We have the experience that audio or video remote participation is usually distracting and slowing down the face-to-face discussion.

Note that all presentation slides will be openly available in this repository and we also plan to write minutes for the discussion sessions, to provide a good basis for future online collaboration or meetings on the topic.

## Introduction

This two-day face-to-face meeting will bring together people
from existing IACTs (imaging atmospheric Cherenkov telescopes) such as H.E.S.S.,
VERITAS, MAGIC, ASTRI, FACT, ... as well as the next-generation Cherenkov telescope
array (CTA) interested in data level 3 (DL3). 

The ["Cherenkov Telescope Array Data Management" proceeding from ICRC 2015](http://adsabs.harvard.edu/abs/2015arXiv150901012L) explains what DL3 is:

> ... high-level observatory products comprised of selected gamma-like events,
instrument response tables, and housekeeping data (DL3). DL3 data will have a
total volume of about 2% of the DL0 data volume and guaranteed access will be
provided in the CTA archive to basic users (e.g. Guest Observers and Archive
Users).

Very roughly DL3 is what most users will download and analyse with science tools,
similar to how Fermi-LAT data is distributed.

Most of the existing IACTs have started efforts to export their event data and
instrument response functions (IRFs) at the DL3 level to FITS formats and
there are some open-source science tools able to analyse it.

But so far no DL3 data model and data format specifications have been produced,
making collaboration difficult!

There are some efforts to write documents within CTA. For the effort on IRFs
see the
["The Instrument Response Function Format for the Cherenkov Telescope Array" proceeding from ICRC 2015](http://adsabs.harvard.edu/abs/2015arXiv150807437W).
In fall 2015 a few people from H.E.S.S. started writing down an open spec of the
formats they use at [gamma-astro-data-formats](http://gamma-astro-data-formats.readthedocs.org/en/latest/). These formats are (mostly, except for recent extensions) supported by Gammapy and Gammalib/ctools and are similar to the ones used by VERITAS.

## Goals

The main goal of this meeting is to work on the DL3 data model and data formats.

* Start with summary presentations on DL3 in the various IACTs and codes that produce or consume DL3 data and IRFs.
* Gather use cases and see which ones are possible / not possible with the existing formats.
* Extend existing formats or create new ones that cover more (all?) use cases.
* Write down open specs (so that they are visible by all, not just CTA members, e.g. at [gamma-astro-data-formats](http://gamma-astro-data-formats.readthedocs.org/en/latest/)) that can form the basis for prototyping for the next months for data producers (mainly existing IACTs and simulated CTA data) and consumers (mainly science tool codes).

Finding a good data model and format and getting community adoption will be an
ongoing task for the coming years. This meeting is just an attempt to speed up
the process. The goal is not to "produce and decide on final formats".

## Agenda

### Wednesday

Start: 10 am

We'll start the meeting with a series of short presentations, to make sure everyone's aware of the status of existing efforts.

Confirmed:

* Catherine Boisson - Welcome, logistics
* Tarek Hassan - Proposed DL3 IRF format and prototype code ([flexIRF](https://github.com/cta-observatory/flexIRF))
* Christoph Deil - 10 min - open-gamma-ray-astro [mailing list](https://lists.nasa.gov/mailman/listinfo/open-gamma-ray-astro), [Github org](https://github.com/open-gamma-ray-astro) and [gamma-astro-data-format](http://gamma-astro-data-formats.readthedocs.org/en/latest/) specs.
* Jürgen Knödlseder - DL3 in [Gammalib](http://cta.irap.omp.eu/gammalib/) and  [ctools](http://cta.irap.omp.eu/ctools/)
* Christoph Deil - 10 min - DL3 in [Gammapy](https://gammapy.readthedocs.org/en/latest/)
* Gernot Maier - Status report DL3 in VERITAS
* tbd (please volunteer!) -- Status report DL3 in HESS
* tbd (please volunteer!) -- Status report DL3 in MAGIC
* tbd (please volunteer!) -- Status report DL3 in FACT
* Imma Donnarumma - DL3 IRF concept and implementation status in the framework of the MINI-ARRAY pipeline
* Jaime Rosado and José Luis Contreras - Thoughts on DL3

Ideas:

* Wanted: short presentations of use cases or "I think we should do this for DL3 ..."
* (if you'd like to give a presentation, please let uns know!)

* Open plenary discussion session
* Plan work for Thursday together on the board:
  * Identify topics for working groups
  * How much time to allocate for each?
  * Everyone puts their name to what they are most interested in.
  * Schedule parallel sessions.
  * Identify 

## Thursday

Start: 9 am

The 

* Split out into small working groups on sub-topics?
* Summary from the sub-groups and discussion.

## Friday morning

Start 9 am

* Identify action items: who does what after the meeting?

## Participants

(alphabetical order by first name)

* [Catherine Boisson](https://github.com/cboisson)
* [Christoph Deil](https://github.com/cdeil)
* [Daniela Dorner](https://github.com/dadorner)
* [Gernot Maier](https://github.com/GernotMaier)
* Immacolata Donnarumma
* Jaime Rosado
* José Luis Contreras
* [Julien Lefaucheur](https://github.com/jjlk)
* [Jürgen Knödlseder](https://github.com/jknodlseder)
* [Kai Brügge](https://github.com/mackaiver)
* [Tarek Hassan](https://github.com/TarekHC)
* (if your name isn't here yet, but you'd like to attend, please let us know!)

## How to contribute to this repository?

The main work product from this meeting will be presentation slides presented on Wednesday, as well as notes and documents written collaboratively during the meeting.

We are using this Github repository to gather presentations and notes for this
meeting: https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting

Please help us gather notes, especially summaries of the parallel sessions, and
identified action items for the coming months (for us, and for people that
couldn't come to the meeting).

To contribute, please make a Github account (it only takes a minute and is free)
and make pull requests, adding files to the following folders:

* [notes](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting/notes) - Add notes as Markdown ``.md`` files. Use the [notes/template.md](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting/blob/master/notes/template.md) file as a starting point if you like.
* If you want to do collaborative note taking, a Google doc with URL shared via
email or Twitter is a good option (and copy & paste the content over to this repo after).
* [presentations](https://github.com/open-gamma-ray-astro/2016-04_IACT_DL3_Meeting/presentations) - Add your presentation in PDF format if you want to present slides.
Or just write down what you want to present in a Markdown file if you prefer.

If you have any questions, ask [Christoph Deil](https://github.com/cdeil) or
other participants that are familiar with Markdown and Github. If you don't want
to use Github, just email files or notes to me and I'll add them to the repo.
