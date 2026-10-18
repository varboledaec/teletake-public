# TeleTake Privacy Policy

Publisher details and effective date are being finalized before the Google Play release.

This policy covers TeleTake for Android, package com.varboleda.teleprompt, version 0.2.2.

Privacy and support contact: info@easytechcommerce.com

## Your content

TeleTake lets you save scripts, read them with a teleprompter, record vertical video with the front camera and microphone, import a video you select, and generate captions after recording. Spanish or English speech recognition runs on your device after you prepare the included language model locally. It does not translate or transcribe live. Automatic captions and word timings may contain errors and should be reviewed.

The editor retains your original video while saving your edits separately. Edits can remove linked audio and video intervals, correct captions, change caption styles and adjust the video's appearance. You can export edited video, SRT or VTT captions, or save or share the original.

Scripts, titles, videos, take dates and durations, language choices, captions, corrections and teleprompter preferences are stored in the app's private storage. Edit projects also store cut positions, caption styles, appearance settings and a fingerprint used to identify the original file. Undo and redo histories each retain up to 30 edit states.

When you transcribe in the editor, TeleTake saves a separate local archive of the recognition result, including the original words and captions, timings, confidence values when available, language, model name and raw recognition output. Correcting a caption or removing a word does not erase that archive. The 30-state history limit does not limit these separate archives.

Recognition and editing process your content on the device. TeleTake does not send scripts, recordings or transcripts to a transcription service or a developer-operated server. This version has no accounts, ads, in-app purchases, developer-operated cloud synchronization or developer-operated analytics service. Android-controlled diagnostics and deliberate saving or sharing are described below. Local processing is not a promise about every service running on your device.

## Permissions

- Camera: to display the preview and record a take you start.
- Microphone: to record sound with your video.
- Internet: retained for a future approved tutorial video that you explicitly choose to download. No tutorial video URL is configured in this version; language-model setup does not use the internet.

Android requests camera and microphone permissions. You may deny or revoke them in Android settings; the features that require them will be unavailable. Importing and saving use Android's picker to select a file or destination. TeleTake does not request general access to your photo or video library, contacts or location.

## Included language models

TeleTake 0.2.2 includes the Vosk small Spanish 0.42 and US English 0.15 language models with the app. Before a language's first use, local preparation verifies and extracts its included files into private app storage. This requires free storage and time, but no model-provider connection, account or download. Recognition then processes the saved video's audio on your device.

An upgrade can reuse a valid model already prepared by an earlier version. Earlier versions, including 0.2.0, downloaded models from alphacephei.com, whose infrastructure received IP and technical request data. Version 0.2.1 removes that runtime request. This change does not delete any logs that the provider may have retained from earlier downloads; the developer has not verified or assumed control of those historical logs.

## Help and tutorial videos

The written English guides are included in the app and work offline. This version includes six written English guides. No tutorial videos or tutorial video URLs are configured. Opening Help or reading a guide does not download a video.

The app does not make background tutorial downloads or refresh a remote catalog. If a future release enables remote tutorials, the policy and app disclosures must identify the host and its data handling before that feature is distributed.

## Android usage and diagnostics

Android may handle technical playback and device diagnostics through its own system services. Depending on the device and your Android usage-and-diagnostics settings, Google or the device provider may receive system diagnostic information. These platform services are separate from a TeleTake-operated backend.

TeleTake uses AndroidX Media3 and native Android playback. Google states that integrating Jetpack libraries does not itself add user-data transfers to a backend or affect an app's Play Data Safety declaration. Passing playback metrics to an Android system service does not by itself establish that TeleTake sends your recordings, scripts or transcripts to a server.

TeleTake disables Media3's optional platform reporting for its compatible-preview player and video exporters where that API is available. This is not a switch for every Android, codec or device diagnostic. Review the controls available in your device's settings; TeleTake does not provide or promise a global diagnostic opt-out.

## Saving and sharing

Exports are prepared in local cache and delivered to another app or location when you choose Save or Share and select a destination through Android. If you choose a cloud provider or social network, that provider may transfer and retain the file under its own terms. TeleTake does not publish videos automatically.

The destination receives the file's content and any metadata it contains. Exporting the original preserves that file; TeleTake does not promise to remove all metadata. After a copy is delivered, TeleTake cannot delete it from the receiving app, folder or service.

## Retention and deletion

Scripts, takes, edit projects and transcription archives remain in private storage until you delete the relevant data or clear the app's data. Removing a section from an edit changes the edited result; it does not erase that section from the original, earlier edit states, recognition archives or previous exports. Resetting only an edit project also leaves its separate recognition archives intact.

A successful take deletion removes compatible-preview cache files owned by that take, the app's original video, its library entry and saved captions, and the take's edit project, edit history and recognition archives. TeleTake also attempts to remove associated temporary exports. If deletion reports an error, some private files may remain; Android's Clear storage/Clear data option removes the app's remaining private data. Deleting a script removes it from the app's library. None of these actions removes copies already saved or shared elsewhere.

Compatible edit previews are temporary local video copies. TeleTake cleans abandoned preview files on startup after an interrupted process; active previews are protected until the editor closes.

Android may clear temporary cache files, and you can clear the cache in Android's storage settings. Clearing TeleTake's app data or uninstalling it removes its private files, preferences, prepared model files and cache. Save copies you want to keep first. The app disables automatic Android app backup and excludes its data from Android device-transfer rules. Copies saved outside TeleTake depend on your chosen system or service.

## Protection

Private files use Android's app storage isolation. Included model archives are checked for integrity before local preparation. This is not a promise of separate app-level encryption of every file and does not give TeleTake control over modified devices, external copies or receiving apps. TeleTake does not sell your personal data.

## Contact and this website

For privacy questions or support, contact info@easytechcommerce.com. If you choose to email support, your email provider delivers the address, message and any attachments you send. These communications are used to handle your request. Send only the information needed; you do not need to send private recordings or scripts. Ask through the same contact if you want your support correspondence removed, subject to applicable legal requirements. The developer cannot access or remotely erase content stored only on your phone.

The public policy and support pages are hosted on GitHub Pages. Visiting them, including by choosing Privacy policy online in TeleTake, sends a normal web request to GitHub. GitHub may process your IP address and technical request information under its Privacy Statement: https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement . These pages do not embed analytics, advertising or third-party media. Opening them is separate from the app's offline recording, editing and speech-recognition processing.

## Policy updates

The current policy is available at https://varboledaec.github.io/teletake-public/privacy.html and a copy is included under Settings → Privacy in the app. Updates will show a new effective date. Material changes in app data handling will be reflected in the app, this policy and the store disclosures.
