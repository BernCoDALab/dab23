---
title: "Open Chronology: Towards FAIR and Transparent Chronology Building"
authors:
- name: "Eythan Levy"
  affiliation: "University of Bern"
  email: "eythan.levy@gmail.com"
format: "Standard presentation"
session: "S3: Practical Applications"
---

This paper discusses the opportunity and means to build archaeological chronologies in a FAIR and transparent way. Several current research projects, such as PeriodO (<https://perio.do>) and Chronontology (<https://chronontology.dainst.org>), aim at documenting chronologies according to FAIR principles. They offer linked gazetteers of chronological periods, covering a wide array of geographical and chronological horizons. Their fundamental work offer, for the first time, global databases of machine-readable archaeological chronologies. Yet, to the best of our knowledge, such projects archive final chronologies (i.e., sets of dates associates to labels), but do not address the process through which these chronologies were established. Each regional chronology is the outcome of a complex research process, involving different types of data (stratigraphic, ceramic, historical, radiometric, etc.). These source data are then weaved together to produce the final chronology, using complex cross-dating arguments. We argue that in order to be fully FAIR and transparent, the reasoning that led to a given chronology must also be documented in a formal and machine-readable way. This paper discusses how the recent ChronoLog software (Levy et al. 2021a; <https://chrono.ulb.be>) can be used to that effect. ChronoLog allows users to build chronological models including diverse types of chronological units (e.g., reigns, strata, ceramic types, cultural phases), with both exact and approximate dates. It also allows users to encode a wide set of chronological synchronisms connecting these units, in order to form a wide chronological network. ChronoLog automatically performs a coherence check on the data, and then computes the resulting chronology by automating the cross-dating process (see Levy et al. 2021b). ChronoLog also allows the tagging of chronological data, in order to decide which types of data should be taken into account. For example, one could build a chronology based only on historical and stratigraphic data, and another chronology that also takes radiometric data into account. We believe that ChronoLog, used in conjunction with current gazetteers, could offer an efficient way for documenting the chronological reasoning behind standard chronologies. It could also be used for testing alternative hypotheses when building a chronology, and thus produce several variant chronologies for a given region. Our paper discusses the current possibilities offered by ChronoLog to this effect, the challenges involved, and perspectives for future developments.

## References

* E. Levy, G. Geeraerts, F. Pluquet, E. Piasetzky and A. Fantalkin, 2021a: "Chronological Networks in Archaeology: a Formalised Scheme." Journal of Archaeological Science 127, pp. 1-27.
* E. Levy, E. Piasetzky and A. Fantalkin, 2021b: "Archaeological Cross-dating: A Formalized Scheme." Archaeological and Anthropological Sciences 13, pp. 1-30.
