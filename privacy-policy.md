# Solray Studio Privacy Policy

Effective 28 October 2026. This policy covers Solray Studio 3.0.1 for Windows.

## Who makes Solray Studio

Solray Studio is a free app made by Code du Soleil. In this policy, "we" and "us" mean Code du Soleil, and "Solray" means the app. You can reach us at codedusoleil@gmail.com.

## The short version

Solray works on your computer and nowhere else. It has no accounts, no ads and no analytics, and it never sends what you play, record, open, type or make over the internet. Solray gives us no information about you, and we collect, sell and share none. It downloads only one thing, and only when you ask it to: the training engine, when you press Install in Settings > Models (below).

## What Solray uses on your computer

- Your audio input: a microphone, an audio interface or another recording device you pick. Sessions, the Tuner, Challenges, Voices and the delay measurement in Settings listen to it while they are on screen; Sessions records from it when you press Record, and Voices when you record a take of your voice. What Solray hears is analysed in memory and then let go; only your recordings are kept, and only on your computer.
- Your MIDI keyboard, when one is connected: the notes you play light up and sound in the Visualizer. They are not stored.
- The files you open: audio files you import, separate, transcribe or convert, MIDI files, videos and Guitar Pro scores, session folders, voice files, and the models you import in Settings. Solray reads them where they are. It copies them only into a session you save, a song into the folder its stems are written to, a voice file into the Voices folder, and an imported model into its own folder (below).
- What you type: names for sessions, tracks and voices, the words of a spoken take of your voice, and the text you have Solray read aloud in Voices. The text read aloud is not kept: only the speech made from it, and only when you export it.
- The names of your audio and MIDI devices, graphics cards and processor, to list them and to choose where Stems and Voices run. They stay on your computer.

## What Solray keeps on your computer

- Sessions you save, with their recordings: in Documents\Solray Studio\Sessions, unless you save them somewhere else.
- Songs you export go where you choose, by default Music\Solray Studio. MIDI files you export go where you choose, by default Documents\Solray Studio\MIDIs. Videos you export go where you choose, by default Documents\Solray Studio\Videos.
- Stems go to the folder you pick, by default Music\Solray Studio, with a copy of the song they were separated from.
- Your last transcription in Tabs, with the location of the track it came from.
- Your last project in Videos: the locations of its video, recording and score, how they are lined up, and how the tab is drawn.
- The models you import in Settings > Models: a separation model in %LOCALAPPDATA%\Solray Studio\Stems models, a lead and backing vocals model in %LOCALAPPDATA%\Solray Studio\Lead vocal models, a reverb removal model in %LOCALAPPDATA%\Solray Studio\Reverb removal models, and the voice models in %LOCALAPPDATA%\Solray Studio\Voice models (where the training engine also puts the conversion base it makes). Remove them in Settings > Models, or delete those folders.
- The training engine, when you install it: in %LOCALAPPDATA%\Solray Studio\Training engine (Python, PyTorch and the packages it needs, and the pretrained weights a training starts from). Remove it in Settings > Models, or delete that folder.
- Voices you save in Voices: in Documents\Solray Studio\Voices, one folder per voice, holding its recordings, the words of its spoken takes and the language they are in, the results of Solray's checks of each take (levels, pitch range, noise), and, once you train it, its model (in its Model folder) and what the training worked with (in its Training folder: the recordings cut into pieces and what was heard in them; Free training files deletes it).
- What Voices makes goes where you choose when you export it: by default into the voice's own folder, Conversions for vocals re-sung and Speech for text read aloud. Deleting the voice deletes those with it.
- Your settings: the tuning, sound and volume, the audio devices you picked (by their names), the folders you used, your recent sessions, the audio delays you measured, how long separations took on your devices, and the options you chose last. These, your last transcription and your last video project are kept in %APPDATA%\com.codedusoleil\Solray Studio.

When Solray is installed from the Microsoft Store, Windows keeps the folders under %LOCALAPPDATA% and %APPDATA% above inside Solray's own package folder, %LOCALAPPDATA%\Packages\CodeduSoleil.SolrayStudio_5s0nx0cn6trmg.

None of this is sent anywhere. Solray keeps it until you delete it, which you can do at any time. Uninstalling Solray removes the app but leaves your sessions, voices, exports and stems where they are; delete those folders to remove them too. Uninstalling the Microsoft Store version also removes its package folder, with the imported models, the training engine and your settings; uninstalling any other version leaves those too.

## Voices

A recording of someone's voice is personal information about them. By saving a voice, you acknowledge that it is your own voice, or that you have the right to copy it as the person whose voice it is agreed to it. Solray uses the recordings only on your computer, to have Solray sing or speak in that voice when you ask it to. Training a voice runs on your computer, on its graphics card: its recordings never leave it. Copy and train only your own voice, or the voice of someone who has agreed to it.

A voice never leaves your computer unless you export it into a file yourself (Export voice…), to take it to another computer. That file holds its recordings and its trained model, so keep it as safe as the voice. A voice file you import from someone else is kept like your own, and the same care applies. Delete a voice in the Voices section, or delete its folder.

## What Solray downloads

Only the training engine, and only when you press Install (or Repair) in Settings > Models. It downloads uv and Python from github.com, PyTorch with NVIDIA's CUDA from download.pytorch.org, the trainer's other packages from pypi.org, and the pretrained weights from huggingface.co, and checks every file against the one it expects. When Python cannot be downloaded, it uses a Python 3.11 already installed on your computer instead. Files you give it with Import files… are copied from the folder you pick, and only the training engine's own files are taken from it: a file there is read only when it is the size of one of them, to compare its contents, and nothing else is kept or sent. As with any download, those sites see your IP address and the files asked for; Solray sends them nothing else, nothing about you, your voice or your files. Nothing is downloaded at any other time, and a training never connects to anything.

## What can leave your computer

Solray itself sends nothing. Two things outside Solray can:

- Microsoft components. Solray runs its Stems, Tabs and Voices models with ONNX Runtime and DirectML, which are made by Microsoft. Like other parts of Windows, they can record usage events in Windows' own diagnostic data, which Windows sends to Microsoft as far as your choices in Settings > Privacy & security > Diagnostics & feedback allow. These events describe how the components run, not your music, your voice or your files. Microsoft's Privacy Statement covers them: https://privacy.microsoft.com/privacystatement
- The Microsoft Store, if you got Solray from it, and Windows' own error reporting. Microsoft runs both, under the same Privacy Statement.

## Your controls

- Windows decides which apps may use your microphone: Settings > Privacy & security > Microphone.
- Solray opens your audio input while a section that listens is on screen (it starts on Sessions), and closes it soon after you move to one that does not. You pick the input on the toolbar of any section that listens.
- Everything Solray keeps is in the places listed above, and you can delete what you like.

## Security

What Solray keeps is ordinary files in your Windows user folders, protected by your Windows account like your other files. Anyone who can sign in as you can open them, so protect your account, and the voice files you export, accordingly.

## Children

Solray collects no personal information from anyone, children included.

## Changes

If Solray starts handling information differently, this policy will change first, with a new effective date at the top. The current version is always in the app, in Settings > About & licences.

## Contact

Questions about this policy or your privacy: codedusoleil@gmail.com
