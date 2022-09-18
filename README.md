# Game Archiving Showcase

This is a showcase to demonstrate, what set of descriptive and technical metadata is necessary to archive a piece of software. The graph.ttl file contains metadata in Records in Contexts (RiC) and PREMIS format to describe the content, context (provenance) and technical environment needed to assess and run a simple computer game. The goal is to store enough information in the preservation system to be able to configure and run an emulator. The challenge is that emulators do change over time and are not stored together with the archived object. Thus the metadata must be generic enough to be used with different emulators on different platforms.

The example was developed for the iPres2022 conference with the goal of keeping computer games from an archived CD-ROM playable.

Based on the metadata, the next step is to show how an emulator can be configured and started in an automated way.