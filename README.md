# ai-hub

A minimalist browser startpage designed to launch your core AI stack instantly. 

Fetches your local weather and time, holds links to major models, and stays out of the way.

## the play

The best way to use this is to set it as the default homepage on a dedicated browser or profile. When you launch that profile, you use the "Open All" or "Open Featured" buttons to instantly put your entire AI toolkit on standby in the background, ready whenever you need to context-switch between models.

## nuances

- **Popups:** Browsers natively block scripts from opening multiple tabs at once. The first time you use the launch buttons, you will need to click the blocked-popup icon in your address bar and select "Always allow."
- **No "Nuke Tabs" Button:** There is no master switch to close all opened AIs. Modern browser security (COOP) severs the connection between tabs the moment sites like ChatGPT or Claude perform their initial authentication redirects. Once that redirect happens, JavaScript fundamentally loses the permission to close them.

## extending

The dashboard is built to be easily modifiable. To add or swap out models, just edit the `allUrls` array in the `index.html` file. 

Open to suggestions and pull requests if a new major model drops or if you have a clean UI refinement.
