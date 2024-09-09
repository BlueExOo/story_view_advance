## [0.1.0+1] - 9 Sep 2024.
- changes in versions and domain name
## [0.1.0] - 7 Sep 2024.
- added callback to receive videoPlayController
- Bump dependencies to latest
- Added medium to Indicator Height
- Exposed loading and error widget API on both story image and story video
- Exposed outerPaddings API
- onStoryShow callback now returns both storyItem and it's index
- Test `publish.yml` workflow
- Replace `PaintingBinding` with `ui`
- API to change indicator colors.
- Ability to hide progress indicators
- Upgraded rxdart to latest version
- Remove unnecessary null assertions
Fixed null errors.
Merged #84 - Fix Error if playerController has not been loaded and is null
Upgraded rxdart to latest version
Merged PR #74. Provision Key to store values. More here https://github.com/blackmann/story_view/pull/74
Upgraded video_player to latest version
Upgraded flutter_cache_manager to latest version
`fontSize` has been replaced with `textStyle`. Minor breaking change.
Update dependencies.
Fix issue #40 and #41. Refactor interaction events to use controller.
Vertical gesture support. Code clean up with minor breaking changes. Promoted the use of story controller.
Fix issue with video stories not pausing while loading.
Duration API in shorthand methods. Roundness of inline gifs fixed.
Fix swipe down pause issue on fullscreen stories.
Fix hardcoded `imageFit` for StoryImage.
Bumped rxdart version.
Video media support.
Animated Gifs support.
Ability to wait for images to load before stories proceed.
Comes with controller to manually control playback.
Improvement for issue #1 fix.
Fix issue #1: onTap pause error for last page
Pub library health complain on description length. Fixed.

Initial release
