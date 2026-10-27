# Designing Accessibility Around User Choice

**From accessibility research to configurable product behavior**

This case study examines how interface personalization might support different
cognitive, sensory, communication, and information-processing needs. It brings
together work described for Ultravocal 4.0, an early-stage, privacy-conscious
legal navigation application, and an earlier prototype from a separate
application.

The repository is a portfolio and documentation project, not a functional
application or SDK. The material currently available here is limited to the
project brief: source code, screenshots, research records, testing records, and
the PDF case study have not yet been supplied. Missing evidence is identified
throughout rather than reconstructed or presented as fact.

## The design question

How can digital interfaces accommodate different access needs without
requiring people to disclose a diagnosis or conform to a single definition of
accessibility?

## The approach

The project brief describes an earlier, separate application prototype that
organized accessibility around categories of needs and functions. It describes
Ultravocal 4.0 as exploring preference-first personalization. These are
different applications, not successive releases of one codebase. The underlying
screens and implementation evidence are not present in this repository yet.

The intended case study follows the path from an accessibility consideration,
to a product requirement, to a configurable interface behavior. It treats
personalization as a design hypothesis to examine—not proof that the product is
effective or accessible.

## What I contributed

The responsibilities described for this work are:

- Research-informed accessibility strategy
- Product and interaction design decisions
- Translation of access needs into requirements
- Development instructions and implementation coordination
- Founder-led usability and functional testing
- Documentation of limitations and future research questions

Software implementation involved AI assistance where applicable. This
portfolio does not claim that I independently engineered the entire
application. The source material needed to substantiate individual decisions
and implementation details remains to be added.

## From needs to behavior

**Accessibility considerations → Product requirements → Configurable
interface behavior**

For example, the brief identifies information depth as a preference area. A
possible requirement is to let people choose how much explanatory detail to
see; the expected behavior and whether it is implemented must be checked
against the product source before this can be presented as an authentic
Ultravocal example. The [requirements table](docs/accessibility-requirements.md)
marks these items as proposed or unverified.

## Selected implementation evidence

The requested `AccessibilityPreferences` type and its update logic are not
included in the supplied repository materials. No code excerpt is shown here
until the original source can be reviewed. The
[implementation decisions](docs/implementation-decisions.md) page explains
what evidence is needed; the
[example file](examples/accessibility-preferences.example.ts) is visibly a
placeholder, not application code.

## Testing and limitations

No test records were supplied, so this repository cannot report completed
founder-led checks or product validation. The project brief distinguishes
founder-led testing from participatory research and calls for future testing
with disabled people and assistive-technology validation. The
[testing and limitations](docs/testing-and-limitations.md) page separates
those future questions from documented findings.

Ultravocal 4.0 is described as an early-stage product. The presence of
accessibility settings alone would not demonstrate that they work across the
interface or meet people's needs.

## Explore the case study

- [Design evolution](docs/design-evolution.md)
- [Accessibility requirements](docs/accessibility-requirements.md)
- [Implementation decisions](docs/implementation-decisions.md)
- [Research methodology](docs/research-methodology.md)
- [Testing and limitations](docs/testing-and-limitations.md)
- [PDF portfolio case study — not yet supplied](portfolio/README.md)
- [Ultravocal](https://ultravocal.app)

Screenshots and code excerpts have not yet been supplied. Placeholder
instructions are available for the
[earlier prototype](assets/earlier-prototype/README.md),
[Ultravocal 4.0](assets/ultravocal-4/README.md), and
[code excerpts](assets/code-excerpts/README.md).
