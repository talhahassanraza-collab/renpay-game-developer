# Android rewarded ads

Only implement ads when requested. Keep AdMob app ID and ad unit ID distinct; never reuse a different project's IDs. Verify the integration method for the installed Ren'Py and Android SDK versions, including dependencies, manifest configuration and target API.

- Use Google's official test ad unit or correctly registered test devices during development. Never click production ads to test. Switch to the owner's production unit only for the intended release after appropriate testing; document the actual compiled setting, not merely a separate informational config file.
- Request and refresh consent as required by applicable regions using Google's current UMP guidance. Provide a privacy-options entry when required and an accurate public privacy policy. A published message or policy alone does not verify real-device behavior or legal compliance.
- Reward only when the SDK reports a reward earned; dismissal, load failure, offline state or consent failure alone must never grant one. Protect against duplicate grants and save/rollback issues. A reward threshold can be reached before the creative ends; do not infer a bug simply from an early close. Test actual reward, no-reward dismissal, duplicate callbacks, failed load, offline, retry, app pause/resume and consent behavior on a device, and report what was actually tested.
- Keep ads optional, disclose the reward and ensure unavailable ads do not block ordinary game progress. Do not promise ad availability or earnings.
- AdMob full app readiness may depend on linking a supported store, account setup and review. Confirm the current supported-store list, requirements and status; a download page on an unsupported store does not automatically satisfy review. Test ads do not generate production revenue.

References: https://developers.google.com/admob/android/rewarded ; https://developers.google.com/admob/android/privacy ; https://support.google.com/admob/answer/10564477 ; https://support.google.com/admob/answer/10230311
