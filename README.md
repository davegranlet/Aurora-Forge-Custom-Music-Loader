**Readability note:** I ran this document through an “explain like I am five” chatbot to improve readability, explainability, and usability. The chatbot helped present the material; it did not originate Aurora Forge, DataCtrlLink, their functionality, or the underlying development work.

# Aurora Forge Custom Music Loader

Aurora Forge Custom Music Loader is the custom-music addon separated from Secure DataCtrlLink. DataCtrlLink remains the shared game loader; this repository owns only the music feature.

## Current status

**Experimental — public source separation in progress.**

The music functionality existed and worked before AI involvement. This source was separated from the developer's existing project so the secure core loader no longer needs to own the custom-music feature.

Publication does not weaken DataCtrlLink's exact-game-build checks. A packaged addon must be accepted through an explicit fail-closed loader policy. It must never depend on unrestricted scanning and execution of arbitrary native files.

No WWE game files, captured packages or banks, Oodle libraries, prior addon binaries, rollback copies, or research dumps are included.

The canonical provenance statement is [the development and provenance FAQ](docs/DEVELOPMENT-AND-PROVENANCE-FAQ.md).

