# Iron Meridian

## Run locally
- Install dependencies with `npm install`
- Start the development server with `npm run dev`
- Create a production build with `npm run build`

## Campaign persistence
Campaign state is autosaved in this browser's local storage. The title screen offers **Continue Campaign** when a valid save exists. Saved state includes faction, health/loadout, squad vehicle, upgrade tree, salvage, objective completion, pinned objective, and last synced player coordinates. Clearing browser site data or using another browser/device will not carry this save over.

Google sign-in/cloud saves are not enabled in this source package. They require an OAuth/Firebase project, authorized redirect domains, and secure backend rules; no credentials are included in the uploaded project.

## Current scope
This update preserves the existing tactical valley game and adds campaign persistence plus a remote-clinic respawn that does not reset objectives. The requested fully enterable multi-floor mega-city, four independently simulated squad companions, and country-scale campaign are larger gameplay systems and are not represented as finished features in this update. Mission framing remains fictional and non-instructional.
