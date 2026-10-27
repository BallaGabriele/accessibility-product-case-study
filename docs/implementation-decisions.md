# Implementation decisions

## Evidence boundary

The project brief names an `AccessibilityPreferences` TypeScript type and
individual preference update behavior, but the corresponding Ultravocal 4.0
source code was not included in this repository. Accordingly, this page does
not reproduce or infer code. The described type and behavior remain
unverified until the original source is supplied and reviewed.

## Example A: `AccessibilityPreferences`

### Accessibility consideration

People may need to choose among supported interface preferences without being
assigned a single accessibility profile.

### Product decision described in the brief

The brief asks for a preference structure covering preset, text size, motion,
information depth, communication, language, and other preferences. The
specific supported values, defaults, and optionality cannot be established
without the source.

### Relevant code and expected behavior

No code excerpt is available. A reviewed excerpt should show the actual type
definition, then explain each option in plain language. Defining a preference
in TypeScript would establish a shape for data, not prove that the interface
applies that preference correctly.

### Verification status

Not verified: source, behavior, and test evidence were not supplied.

## Example B: preference update behavior

### Accessibility consideration

Changing one setting should not silently reset unrelated choices or force a
person to keep a preset that no longer describes their selections.

### Product decision described in the brief

The brief requests an update example in which changing an individual
preference can move the preset to Custom while preserving other settings. The
implementation has not been supplied, so this is not reported as confirmed
product behavior.

### Relevant code and expected behavior

No update logic is reproduced. Once reviewed source is available, the excerpt
should demonstrate how the changed field and preset status are handled, and
how all other fields are preserved. The expected behavior should be checked in
the actual interface, not inferred from a type or isolated function.

### Verification status

Not verified: source, behavior, and test evidence were not supplied.

## Evidence to add

Add narrowly scoped excerpts from reviewed Ultravocal 4.0 source, identify
their original file and context, and omit secrets, authentication logic, and
unrelated proprietary code. Record which behavior was checked, how it was
checked, and what remains unknown. See the [example placeholder](../examples/accessibility-preferences.example.ts).
