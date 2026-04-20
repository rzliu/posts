+++
date = '2026-04-20T10:49:06-04:00'
draft = false
title = 'Video Edit Quicktime Player'
+++

# Editing Video with QuickTime Player on Mac

QuickTime Player is the free video player that ships with every Mac. Most people only use it to watch clips, but it also includes a surprisingly capable set of built-in editing tools — enough to handle trimming, splitting, rearranging, rotating, and exporting video without ever opening iMovie or Final Cut Pro. This guide walks through everything QuickTime Player can do as an editor, when it's the right tool, and when you should reach for something more powerful.

## When QuickTime Player Is the Right Tool

QuickTime Player is ideal for lightweight, non-destructive editing tasks where you need results fast:

- Trimming the beginning or end off a clip
- Cutting out a middle section (e.g., removing a mistake from a screen recording)
- Splitting a long recording into multiple clips
- Combining several clips into one continuous video
- Rotating or flipping footage shot in the wrong orientation
- Quick screen, camera, or audio recordings
- Exporting to a smaller resolution for sharing

It is **not** the right tool for color grading, transitions, titles, multi-track audio mixing, effects, or frame-accurate editing. For those, use iMovie (free) or Final Cut Pro (paid).

## Opening a Video

There are several ways to open a video in QuickTime Player:

- Double-click any compatible file (`.mov`, `.mp4`, `.m4v`) if QuickTime Player is your default player
- Right-click a file in Finder → **Open With** → **QuickTime Player**
- Launch QuickTime Player, then choose **File → Open File...** (⌘O)
- Drag a video file onto the QuickTime Player icon in the Dock

Supported formats include most common video types, though some `.mkv` and older codecs may not play without conversion.

## Trimming a Clip

Trimming lets you shorten a video by removing footage from the beginning and/or end. This is the most common QuickTime edit.

1. With the video open, choose **Edit → Trim** (⌘T)
2. A yellow trim bar appears at the bottom of the window
3. Drag the left yellow handle inward to cut off the beginning
4. Drag the right yellow handle inward to cut off the end
5. Click **Play** to preview the trimmed selection
6. Click **Trim** to apply

After trimming, the removed sections are discarded. The trimmed video can then be saved or exported as a new file.

> **Tip:** Hold ⌥ (Option) while dragging a handle for finer, slower adjustments.

## Splitting a Clip

Splitting divides a single video into multiple independent segments, which is useful when you want to remove a middle section, rearrange parts, or delete just one portion of a longer recording.

1. Move the playhead (the vertical red line) to the point where you want to split
2. Choose **Edit → Split Clip** (⌘Y)
3. The video breaks into two segments, each shown as a thumbnail in a clip strip at the bottom of the window
4. Repeat at additional points to create more splits

Once a video is split, each segment can be selected individually and moved, deleted, or edited on its own.

## Cutting Out a Middle Section

To remove an unwanted section from the middle of a video:

1. Move the playhead to the **start** of the unwanted section and press ⌘Y to split
2. Move the playhead to the **end** of the unwanted section and press ⌘Y again
3. Click the middle segment to select it (it will be outlined in yellow)
4. Press **Delete** (or choose **Edit → Delete**)
5. The surrounding segments automatically join back together

## Rearranging Clips

After splitting a video (or combining multiple clips, described below), you can reorder segments by dragging:

1. Click and hold a segment thumbnail in the clip strip
2. Drag it left or right to a new position
3. Release to drop it into place

The video plays back in the new order immediately.

## Combining Multiple Clips

QuickTime Player can join multiple videos into one. There are two ways to do this:

### Method 1: Drag and Drop

1. Open the first video in QuickTime Player
2. Drag additional video files from Finder directly into the QuickTime Player window
3. Each dropped file is appended as a new segment at the end of the clip strip
4. Drag the segments to reorder them as needed

### Method 2: Add Clip to End

1. With the first video open, choose **Edit → Add Clip to End...**
2. Select the video you want to append and click **Choose Media**
3. Repeat for additional clips

### Method 3: Insert Clip After Selection

To insert a clip somewhere in the middle instead of at the end:

1. Split the video at the point where you want to insert
2. Click the segment **before** the insertion point to select it
3. Choose **Edit → Insert Clip After Selection...**
4. Choose the clip to insert

## Rotating and Flipping Video

If a clip was recorded in the wrong orientation (a common issue with iPhone footage), QuickTime Player can fix it:

- **Edit → Rotate Left** rotates 90° counterclockwise
- **Edit → Rotate Right** rotates 90° clockwise
- **Edit → Flip Horizontal** mirrors the video left-to-right
- **Edit → Flip Vertical** mirrors the video top-to-bottom

These operations apply to the entire video, or to a specific segment if one is selected in the clip strip.

## Recording New Video

QuickTime Player isn't just for editing existing files — it can record new ones too.

### Screen Recording

In older versions of macOS, **File → New Screen Recording** opens QuickTime's built-in screen recorder. In macOS Mojave (10.14) and later, this menu item launches the system screen-capture tool (⇧⌘5), which is the recommended approach.

### Movie Recording (Webcam)

**File → New Movie Recording** opens a window using your built-in or connected camera. Click the red record button to start. You can pick a different camera or microphone from the arrow next to the record button, and choose recording quality (Maximum, High, Medium) from the same menu.

### Audio-Only Recording

**File → New Audio Recording** captures audio from your Mac's microphone or any connected audio input.

### Recording from an iPhone or iPad

With a Lightning or USB-C cable connecting your iOS device:

1. Choose **File → New Movie Recording**
2. Click the arrow next to the record button
3. Select your iPhone or iPad as the camera source
4. The device's screen appears in the window, ready to record

This is useful for capturing iOS app demos or gameplay.

## Saving and Exporting

### Saving

Once your edits are complete, use **File → Save** (⌘S) to save changes. If the file was opened from an existing location, it will save over that file (after confirmation). If it's a new combined or recorded video, you'll be prompted to choose a name and location.

### Exporting at Different Resolutions

To export a compressed or resized version, choose **File → Export As** and pick a preset:

- **4K** (if the source is 4K)
- **1080p**
- **720p**
- **480p**
- **Audio Only** (extracts the audio as an `.m4a` file)

Lower resolutions produce smaller files that are faster to upload or share. The export uses H.264 or HEVC encoding depending on the preset and your Mac's capabilities.

### Exporting for Web

**File → Export As → Web** produces a smaller, web-optimized `.mp4` suitable for uploading to most platforms.

## Useful Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| ⌘O | Open file |
| ⌘W | Close window |
| ⌘S | Save |
| ⌘T | Trim |
| ⌘Y | Split clip |
| ⌘Z | Undo |
| ⇧⌘Z | Redo |
| Space | Play / Pause |
| → | Step forward one frame |
| ← | Step back one frame |
| ⌥→ | Skip forward |
| ⌥← | Skip back |
| L | Fast-forward (press again to speed up) |
| J | Rewind (press again to speed up) |
| K | Pause |

## Limitations to Know About

Before committing to QuickTime Player for a project, be aware of these constraints:

- **No transitions.** Cuts are always hard cuts — no fades, dissolves, or wipes.
- **No titles, text, or overlays.** You can't add captions, watermarks, or graphics.
- **No color correction or filters.** What you shoot is what you get.
- **One audio track.** You can't mix in music or separate dialogue from a soundtrack.
- **Limited precision.** Trimming and splitting work to roughly the nearest frame, but there's no scrub wheel or timecode readout for frame-accurate work.
- **No speed changes.** You cannot slow down or speed up clips.
- **Limited format support.** Files in formats QuickTime doesn't recognize (such as many `.mkv` files) won't open.

## Workflow Tips

A few practical habits make QuickTime editing smoother:

- **Work on a copy.** QuickTime can overwrite the original file when you save. Duplicate the source file first (⌘D in Finder) before editing.
- **Use Undo freely.** ⌘Z reverses trims, splits, deletions, and rotations without any quality loss, since edits are non-destructive until you save.
- **Split first, delete second.** When removing middle sections, make both splits before deleting anything. It's easier to see what you're keeping.
- **Export rather than save for important files.** Export As creates a new file and leaves the original untouched, which is safer than overwriting during a save.
- **Combine, then trim.** When merging clips, join them first and trim afterward — that way you only need one final export.

## When to Move to iMovie or Final Cut Pro

If you find yourself needing any of the following, it's time to upgrade:

- Any transitions between clips
- Titles, lower-thirds, or end credits
- Background music or additional audio tracks
- Color adjustment or filters
- Speed ramping, slow motion, or reverse playback
- Picture-in-picture or split-screen effects
- Precise frame-by-frame editing with a proper timeline

**iMovie** is free from the App Store and handles all of the above. **Final Cut Pro** is a paid professional tool for more serious work. For quick cuts and simple edits, though, QuickTime Player remains the fastest, lightest way to get the job done on a Mac.

