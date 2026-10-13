# downloads
Installers for compute.is products - MetaReporter, ANPRReporter, PeopleReporter. Source is not published; see compute.is for licence terms.

## Milestone XProtect plugins

| Plugin | What it is |
|---|---|
| [ANPRMib 1.1.0](https://github.com/QTinman/downloads/releases/tag/anprmib-v1.1.0) | ANPR Monitor: number plates from camera metadata, with images and a shared watchlist |
| [MetaCounter 2.1.0](https://github.com/QTinman/downloads/releases/tag/metacounter-v2.1.0) | People and vehicle counting from Hanwha WiseAI cameras, with dashboards and email reports |
| [PCMib 2.0.0](https://github.com/QTinman/downloads/releases/tag/pcmib-v2.0.0) | People Count Monitor: live in / out / occupancy from ONVIF cameras |
| [QueueMib 1.0.0](https://github.com/QTinman/downloads/releases/tag/queuemib-v1.0.0) | Queue monitoring from Dahua cameras: people waiting, longest wait, queue alarms |
| [ZoneWatch 1.0.0](https://github.com/QTinman/downloads/releases/tag/zonewatch-v1.0.0) | ZoneWatch: camera zones with a Smart Client wall that shows the cameras with activity |
| [TPMib 0.1.0](https://github.com/QTinman/downloads/releases/tag/tpmib-v0.1.0) | Time Profile for Milestone: camera alarms pass only while their own adjustable schedule is armed, so work that overruns does not flood the guards |

Run the installer on the Event Server machine and on every Management Client and Smart Client machine. It stops and restarts the Event Server; settings and licences in `%ProgramData%` are kept.

A 30-day trial starts from the Licence tab in the Management Client (TPMib needs no licence). Licences are requested from support@compute.is.
