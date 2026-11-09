# Hassan Kazmi

I build hardware and software prototypes, with the goal of taking ideas through circuit design, firmware, CAD, and the interface people use. I study electrical engineering at Toronto Metropolitan University and want to develop products across robotics, electronics, and software.

[Explore my product portfolio](https://github.com/hxssank/recruiter-portfolio) · [Engineering coursework](https://github.com/hxssank/electrical-engineering-coursework)

## Engineering to read first

- [Shaggy's audio and cache walkthrough](https://github.com/hxssank/shaggy/blob/main/ENGINEERING.md) follows a bank from SD validation to synchronized playback, including what remains after an interrupted copy.
- [Spark's power calculation](https://github.com/hxssank/spark/blob/main/ENGINEERING.md) derives current, voltage sag, resistive loss, and usable energy from explicit assumptions.
- [Pager's thickness budget](https://github.com/hxssank/pager/blob/main/ENGINEERING.md) accounts for the full 17.4 mm stack and shows why a different display would break it.
- [Mazal's import walkthrough](https://github.com/hxssank/mazal/blob/main/ENGINEERING.md) separates original evidence, reviewed rows, and ledger writes, then explains retry and stale-edit protection.

## Hardware, firmware, and robotics

| Project | What I am building | Current stage |
| --- | --- | --- |
| [Shaggy](https://github.com/hxssank/shaggy) | Pico 2 audio player with Hall-sensor controls, SD music libraries, flash caching, and a KiCad carrier board | Firmware and host tools with automated tests; device timing and audio need hardware checks |
| [Spark](https://github.com/hxssank/spark) | Compact power-bank designs connecting parametric CAD, a bench boost PCB, and an assembly-review UI | Circuit and packaging studies; complete USB-PD charging and protection remain open |
| [Alfred](https://github.com/hxssank/recruiter-portfolio/tree/main/projects/alfred) | Humanoid robotics development using ToddlerBot, with communication, motor-validation, and recording fixes | Attributed patches and simulation regressions; no demonstrated household robot |
| [Pager](https://github.com/hxssank/pager) | Pocket Linux computer concept with a thumb keyboard, trackball, and enclosure CAD | Packaging model and geometry tests; parts selection and physical fit remain open |

## Software products

| Project | What it does | Engineering focus |
| --- | --- | --- |
| [Mazal](https://github.com/hxssank/mazal) | Local finance desktop app with document review, a ledger, planning, and encrypted backups | React, SQLite, Python calculations, and Swift desktop integration |
| [Cant Pin Me](https://github.com/hxssank/cant-pin-me) | Workout planner with 60 exercises, history, muscle summaries, and 3D movement demos | Local persistence, anatomy assets, and inverse kinematics |
| [Drip](https://github.com/hxssank/drip) | Wardrobe planner with photos, outfit rotation, laundry tracking, and closet editing | Validated state changes, IndexedDB, and a procedural 3D preview |
| [Mazal Academy](https://github.com/hxssank/mazal-academy) | Interactive lessons, quizzes, and financial calculation labs | Testable numerical models and transactional browser progress |

## How I approach a product

I use these projects to learn how a product's parts constrain each other. Spark's current estimate affects its thermal requirements. Pager's component dimensions determine whether the enclosure can close. Mazal's persistence rules determine when its interface can say an import succeeded.

The engineering notes trace the source, work through examples, compare design choices, and define the next measurement or test. They distinguish implemented behavior from proposed changes. ToddlerBot, anatomy models, and other upstream work retain their attribution.

My next steps include physical fit and thermal testing, complete charging and protection circuits, and longer robotics validation. I am also learning Azure, Microsoft Graph, and platform engineering for the services that future products may need.
