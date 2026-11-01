# Testing and release

## Functional verification

Use the project's installed Ren'Py SDK and current official commands. Run lint and available automated tests; test affected story branches and inspect relevant screens. Check start/new game, main menu, pause, settings, save/load/delete confirmation, existing saves, dialogue, choices, tasks, inventory, money, day transitions, audio and return paths. Separate source tests, packaged build tests and actual device tests in reports.

Check Windows and Android input, scaling, font sizes, safe areas, touch targets, performance, pause/resume, save persistence and first launch. Confirm an ad-unavailable or offline state does not prevent normal play. Prevent test windows from being left running and avoid touching unrelated processes.

## Package and preserve

Respect the user's build instructions; do not rebuild a release they asked to leave alone. Confirm SDK/toolchain compatibility, version, version code, app ID, icons and installed signing configuration before packaging. Preserve Android signing keys, passwords and recovery material securely; never publish them, source-control them, or generate replacements for an existing app without considering update compatibility. Check package integrity and signature, exclude secrets and unrelated saves, and keep a clear release directory. Independently test the exact build to be distributed when feasible.

For Android, distinguish APK distribution from Google Play App Bundle requirements. Check the current target API, app size, Play policies and store requirements in official documentation. A successful build does not prove device compatibility or store approval.

## Store preparation

Prepare accurate title, description, categories, screenshots from the actual build, cover, banner, supported platforms, installation instructions, content disclosures and privacy policy where applicable. Confirm image sizes against the store's current requirements. Avoid claims about untested features or approval. Select correct platform labels and pricing based on the owner's wishes. Upload only intended release artifacts; do not include private files.

Itch.io allows multiple platform downloads on one page. Public visibility and search indexing are different; check whether downloads and search listing are enabled and consult https://itch.io/docs/creators/getting-indexed for current review details. Publishing or changing visibility requires user authorization. Afterward verify the saved state and report the direct link. Do not claim search placement or ad earnings are guaranteed.

References: https://www.renpy.org/doc/html/ ; https://www.renpy.org/doc/html/android.html ; https://www.renpy.org/doc/html/build.html ; https://support.google.com/googleplay/android-developer/answer/11926878 ; https://itch.io/docs/creators/getting-indexed
