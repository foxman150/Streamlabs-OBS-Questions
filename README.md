# Streamlabs OBS General Questions

- Roadmap > [found on Trello](https://trello.com/b/oTl4KiBW/streamlabs-obs-roadmap)
- Report Issues > Please submit all issues on the tracker http://tracker.streamlabs.com
- Backups > Always make backups during beta testing! Settings > Overlays > Export

## How do I report any issues

You can submit issue you have our [Streamlabs OBS Tracker](http://tracker.streamlabs.com/)
Also please `Upload cache to Developers` found in General Settings and include the filename of the cache, that got copied to your clipboard by doing so, in the issue. Preferably also attach your Discord name+discriminator so developers can contact you.

## How do I submit a suggestion

You can submit ideas or suggestions to the [Streamlabs OBS Tracker](http://tracker.streamlabs.com/) as well.
However do make sure the suggestion is not already made before, and if using the tracker set serverity to **Feature** or **Tweak** depending on what the suggestion is.

You can also post the suggestion in #suggestions channel on the [Streamlabs OBS Discord](http://discord.gg/stream).

## How do i submit a suggestion not related to SLOBS

You can submit suggestions and ideas at: http://ideas.streamlabs.com

## Do I still need to the Stream Labels application

No, you do not have to use the Stream Labels standalone application anymore as this has been fully integrated into Streamlabs OBS. To use them please remove any old `Text (GDI)` sources you have to read the textfiles, and replace them with `Stream Label` widgets.

## Does Streamdeck work with Streamlabs OBS

Currently Streamlabs OBS does not natively support Streamdeck but Streamlabs and Elgato are working together since the start to bring native support for the Streamdeck but no ETA is available yet for when this will be.

A work around at the moment is to set hotkeys in Streamlabs OBS and let the streamdeck 'press' these hotkeys.

## Is Streamlabs Chatbot integrated into Streamlabs OBS

No, the chatbot is currently not integrated. You still need to run it as seperate application.

## Is there NDI support

No, currently there is no NDI support but it is being planned to be added. No ETA on this yet though!

## Are OBS Studio Plugins supported

No, at this moment external plugins are disabled so they can currently not be used.

## How do I enable Face Masks

You can enable `Face Mask` as a filter to your webcam video capture source.

## How do I connect Face Mask to my alerts

This feature is not implemented yet, as currently the face mask plugin is still being optimized.

## Can I select and then move or transform multiple sources

At this moment you are unable to select multiple sources to either move or transform at the same time. However you can kind of group them by putting all related sources into a special scene, and then resuse this scene as source in other scenes. Then you can move and transform this scene-source as a group.

An example would be a `WEBCAM` scene, containing a `Webcam Video Capture Device`, a `Webcam Frame Image`, a `Webcam Background Image`, and maybe a `Top Donator Label` under the webcam. Build the scene, centered on the source, preferably unscaled (so images need to match native resolution of the webcam). Then in every scene you want to use the webcam add `WEBCAM` scene as source. Making an edit, you only need to edit `WEBCAM`. Also souces are literally used once, you can do the same for alerts!

[Video Guide](https://youtu.be/-2gUay7AiCY)
