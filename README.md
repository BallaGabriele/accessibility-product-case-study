# Designing Accessibility Around User Choice

**From accessibility research to configurable product behavior**

A case study examining how accessibility principles and user needs can be translated into product requirements, interface decisions, and testable software behavior.

**Project:** Ultravocal 4.0 and an earlier, separate application prototype  
**My role:** Research, accessibility strategy, product design, implementation coordination, and testing  
**Methods:** Research-informed design, requirements definition, AI-assisted implementation, and founder-led evaluation

[Explore Ultravocal](https://ultravocal.app) · [View the case study](portfolio/accessibility-case-study.pdf)

---

## The challenge

Accessibility settings often require people to understand technical terminology, identify with predefined categories, or navigate multiple controls before finding what works for them.

But people's access needs are not always fixed. They can change depending on context, energy, environment, and the demands of a particular task.

**The question guiding this work was: How can an interface adapt to a person's needs without asking them to fit into a predefined model of accessibility?**

I explored this question through two approaches:

- **Earlier application prototype:** Accessibility organized around functional settings, including sensory, cognitive, and communication-related options.
- **Ultravocal 4.0:** A preference-first approach that invites people to choose how information is presented, with presets such as Calm, Focus, Detailed, and Low Energy, alongside individual controls.

These are examples from two separate applications, not sequential releases of the same product.

## My contribution

My work focused on connecting accessibility considerations to concrete product decisions.

I developed the personalization approach, structured configurable preferences, defined expected behaviors, coordinated AI-assisted implementation, and conducted founder-led functional and usability checks.

The work involved four connected activities:

| Activity | My contribution |
|---|---|
| **Research and design** | Examined accessibility principles and identified opportunities to reduce cognitive and interaction barriers. |
| **Requirements definition** | Translated broad needs into specific preferences, interaction rules, and expected behaviors. |
| **Implementation coordination** | Directed and reviewed AI-assisted development of the accessibility settings. |
| **Testing and evaluation** | Tested selected user journeys, identified issues, and documented questions requiring further validation. |

My focus was not simply on adding accessibility features. It was on creating a system where users could make meaningful choices about their experience.

## From accessibility needs to product behavior

A central decision was to avoid treating any single preset as universally accessible.

Instead, Ultravocal 4.0 defines preferences across several dimensions, including:

- Information density and reading depth
- Text size, contrast, and visual complexity
- Motion and transitions
- Communication and language preferences
- Notifications, reminders, and information visibility

These decisions informed a TypeScript `AccessibilityPreferences` structure that makes supported options explicit.

The implementation also includes logic for changing an individual setting while preserving other preferences and switching the selected preset to `Custom`.

**What this demonstrates:** A traceable connection between accessibility considerations, structured development requirements, and configurable interface behavior.

[Explore the implementation decisions](docs/implementation-decisions.md)

## Evidence and limitations

This work was informed primarily by accessibility principles, research-informed design hypotheses, and my own iterative testing.

The repository documents design decisions and selected implementation evidence. It does not establish that every defined setting has been independently verified across the application.

Further research with disabled participants is necessary to understand whether the categories, presets, and controls are meaningful, discoverable, and effective in practice.

In particular, future validation should examine how people with different or changing access needs understand their options, navigate between settings, and experience the resulting interface.

[Read the testing and limitations](docs/testing-and-limitations.md)

---

## Why this matters

Accessibility work should not end when a concern is documented.

It requires a process for turning observations into specific requirements, evaluating whether changes address the underlying problem, and returning to the people affected to understand what still needs improvement.

This case study documents one part of that process: **moving from research-informed accessibility considerations to concrete, testable product decisions.**

The next step is participatory validation that gives disabled people meaningful influence over how those decisions evolve.

## Explore the work

| Document | What it covers |
|---|---|
| [Design evolution](docs/design-evolution.md) | How two interface approaches framed accessibility and user choice |
| [Accessibility requirements](docs/accessibility-requirements.md) | Translating access considerations into expected behavior |
| [Implementation decisions](docs/implementation-decisions.md) | Preference
