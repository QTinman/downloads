# downloads
Installers for compute.is products - MetaReporter, ANPRReporter, PeopleReporter. Source is not published; see compute.is for licence terms.

## Milestone XProtect plugins

| Installer | What it is |
|---|---|
| [ANPRMib-Setup-1.0.0.exe](ANPRMib-Setup-1.0.0.exe) | ANPR Monitor: number plates from camera metadata, with images and a shared watchlist |
| [MetaCounter-Setup-1.0.0.exe](MetaCounter-Setup-1.0.0.exe) | People and vehicle counting from Hanwha WiseAI cameras, with dashboards and email reports |
| [PCMib-Setup-1.0.0.exe](PCMib-Setup-1.0.0.exe) | People Count Monitor: live in / out / occupancy from ONVIF cameras |
| [QueueMib-Setup-1.0.0.exe](QueueMib-Setup-1.0.0.exe) | Queue monitoring from Dahua cameras: people waiting, longest wait, queue alarms |
| [ZoneWatch-Setup-1.0.0.exe](ZoneWatch-Setup-1.0.0.exe) | ZoneWatch: camera zones with a Smart Client wall that shows the cameras with activity |
| [TPMib-Setup-0.1.0.exe](TPMib-Setup-0.1.0.exe) | Time Profile for Milestone: camera alarms pass only while their own adjustable schedule is armed, so work that overruns does not flood the guards |

Run the installer on the Event Server machine and on every Management Client and Smart Client machine. It stops and restarts the Event Server; settings and licences in `%ProgramData%` are kept.

Licences are requested from support@compute.is.
