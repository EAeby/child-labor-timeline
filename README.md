# The History of Child Labor Law: Interactive Timeline

A Den meeting presentation for the Scout requirement: *"Choose a federal law and create a timeline of the history of the law. Include the involvement of the 3 branches of government."*

**Open it here:** https://eaeby.github.io/child-labor-timeline/

A short YouTube video plays while a timeline from 1900 to 1950 fills in below it. Each milestone pops up as the video reaches it, colored by the branch of government that acted:

- **Blue:** Legislative (Congress)
- **Gold:** Executive (President)
- **Purple:** Judicial (Supreme Court)
- **Teal:** Citizens and events

Dots with a dashed ring are **bonus facts** the video doesn't cover, mostly Supreme Court decisions. When "Pause at bonus facts" is checked, the video pauses at each one so you can explain it, and you press play to continue. The video stops at 2:06, before its present-day section, and the side card shows a recap of all three branches.

## Presenting

| Key | Action |
| --- | --- |
| **F** | Full screen (use this, not YouTube's full screen, so the timeline stays visible) |
| **Space** | Play / pause |
| **← / →** | Jump to the previous / next milestone |
| Click a dot | Jump the video to that milestone |
| **D** | Show the current video time (for adjusting timestamps) |

You need an internet connection, since the video streams from YouTube.

## Editing

Milestone times, text, and the stop point are in the **EDIT HERE** section near the top of the script in `index.html`. `t` is the number of seconds into the video.

## Running offline from a copy

YouTube often won't play when `index.html` is opened directly as a file. With [Node.js](https://nodejs.org) installed, double-click `start.bat` (or run `node server.js`) and open http://localhost:5173.
