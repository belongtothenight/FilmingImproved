# FilmingImproved

[howto video](https://www.youtube.com/watch?v=_JZ7bnk3oiM)

## Develop Goals

1. Improve spectator mode recording camera movement.
   1. W/S/A/D/space/shift keys can be toggled to be continuous mode. (no need to keep pressing, re-press to cancel action).
   2. Moving speed adjustment.
   3. space/shift action with smoothed reaction.
   4. Auto-select cinematic camera mode.
   5. Group every setting here to an options/stats page.
   6. (optional) Screen rotation.
2. Create an auto-recording path generator.
   1. Auto-control camera with a pre-generated path to record. The user specifies the length of the recording, the direction of the path, and the height variation.
   2. Path generation prevents the camera from going inside blocks and makes sure the scene is beautiful.
3. Separate recording path generating and rendering.
   1. Store recording path in the first stage.
   2. Modify the recording path in the second stage.
   3. Render recording using recording path.
4. Optimize in-game resource loading mechanism.
   1. Make sure chunks are not loaded if the camera doesn't see them.
   2. Pre-load chunks before the camera reach.
