# Echo Music v5.2.3

- Moved ListenBrainz settings to the Account page, making the integration fully accessible and functional.
- Fixed ListenBrainz scrobbling by replacing fragile transition triggers with robust playback state tracking, extracting metadata directly from the ExoPlayer instance for newly streamed tracks, and appending app version headers to submission payloads.
- Added Discord Integration to the settings menu.
- Fixed Discord Rich Presence not syncing by implementing automated token extraction via WebView.
- Improved Discord Rich Presence to automatically update on song change, playback state changes, and setting modifications.