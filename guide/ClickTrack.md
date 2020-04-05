# How to Generate a Click Track

A [click track](https://en.wikipedia.org/wiki/Click_track) is an audio track that contains
metronomic beats that correspond to a piece of music. It helps ensure that you can
synchronize the performances when combining them into the final collaborative virtual video.

This guide shows you how to create basic click tracks with no tempo changes as well
as more advanced click tracks that contain tempo changes.


## Basic Click Track

While several software applications feature click track generation, this
guide explains how to create one with a free, open source audio editor called [Audacity](https://en.wikipedia.org/wiki/Audacity_(audio_editor)).


### Step 1 - Install and Open Audacity

If you do not already have it installed, [download](https://www.audacityteam.org/download/) it for the operating system
that you use and install it.

After you open Audacity, a new audio track editor window that contains menu options at the top should appear. From the
menu, select the **Generate** menu item and then the **Rhythm Track** sub-menu item as shown below.

![Step 1](https://github.com/violaaas/music/blob/master/guide/screenshots/Audacity_clicktrack_step1.png)

### Step 2 - Configure the Click Track

From your menu selection in the previous step, a new dialog window should appear which contains the parameters of your
click track which should resemble the following:

![Step 2](https://github.com/violaaas/music/blob/master/guide/screenshots/Audacity_clicktrack_step2.png)

Update the "Tempo (bpm) and "Beats per bar" settings to match the piece of music being performed.
For example, if your meter is 3/4 and metronome marking is 72, you'll want to set the "Tempo (bpm)" setting to 72 and the
"Beats per bar" to 3.

Update the "Number of bars" setting to the number of bars in the piece of music being performed, and add two extra
bars to give your performance the chance to prepare.  For example, if the piece is 80 measures long, generate an 82
measure click track. Make sure to communicate the preparation measures to the performers, either in your Recording Plan, or directly.

If you want the click track to provide a different pitch for downbeats, update the "MIDI pitch of strong beat" setting
to a number different than the "MIDI pitch of weak beat". Each number corresponds to a specific half step in a chromatic scale
in increasing order: the higher the number, the higher the pitch.

You can click the "Preview" button to listen to a short sample of the current settings before you generate the full
click track. Click the "OK" button to generate the full click track.

### Step 3 - Review the Click Track

After clicking the "OK" button, the dialog box should close and you should show a graphic representation of the audio
within an "Audio Track" as follows. You can click the play button at the top to listen to the current click track.

![Step 3](https://github.com/violaaas/music/blob/master/guide/screenshots/Audacity_clicktrack_step3.png)

If you discover you made a mistake in the settings you chose, you can close the click track audio file by opening the "File" menu 
and selecting the "Close" item. When prompted as to whether you want to save changes to the project, click "No". Otherwise, 
if you're ready to save the click track, proceed

### Step 4 - Save the Click Track

Select the File menu and Export menu choice. From there, select "Export as WAV" as shown below. Choose a filename and
directory to save it to.

![Step 4](https://github.com/violaaas/music/blob/master/guide/screenshots/Audacity_clicktrack_step4.png)

### Step 5 - Share the Click Track

To share the click track, you need to make it available online. If you are not certain what service to use or how to
upload files from your computer to a sharing service, read one of the following tutorials:

* [Upload Files to Google Drive](https://support.google.com/drive/answer/2424368?co=GENIE.Platform%3DDesktop&hl=en)
* [Upload Files to Dropbox](https://help.dropbox.com/files-folders/share/add-files)


## Advanced Click Track

This guide assumes that you have read the [Basic Click Track](#Basic-Click-Track) section and can generate a simple
click track.

If the piece of music requires tempo changes such as accelerandos, ritards, or other markings, you need to customize the click track. 
Although Audacity does not include a feature that generates a click track with multiple tempos, you can generate one click track
for each tempo in sequence by following the steps below:

### Step 1- Count the Number of Beats in Each Tempo

Suppose the piece of music consists of the following tempo markings in order:

* "quarter note = 120" in 4/4 time for 32 measures and 1 quarter note pickup
* "half note = 48" in 2/4 time for 16 measures
* "quarter note = 176" in 3/4 time for 24 measures



### Generate Click Tracks for Each Tempo

Note: the quarter note pickup can be included in the two additional measures that we add to the beginning. Otherwise, you must
manually remove three beats from the start of the click track.

From the example above, the first segment of the click track is 34 measures long since we add two measures to allow time for
the performers to get ready to play. Use the directions explained in the [Basic Guide: Step 2 - Configure the Click Track](#Step-2-Configure-the-Click-Track) to generate a click track with 120bpm and 4 beats per measure for 34 measures.

Then, select the end of the recording by pressing your "End" key or using the "Skip to End" button as shown below.

![Skip to End Button](https://github.com/violaaas/music/blob/master/guide/screenshots/Audacity_clicktrack_end.png)

Repeat the steps to generate a click track with 48bpm with 2 beats per measure for 16 measures. Select the end of the recording
again, and repeat the steps to generate a click track with  176bpm with 3 beats per measure for 24 measures.

At this point, you have generated a click track with multiple tempos that you can save and share.