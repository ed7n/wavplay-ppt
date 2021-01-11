# WavPlay-PPT

—Digital audio playback for PowerPoint.

*This project is on hold.*

## Downloads

* [[**Latest Release**](https://github.com/ed7n/wavplay-ppt/raw/master/release/WavPlay-PPT.zip)] — Update 2 Revision 0, 01/08/2018.

## Usage

Place audio files alongside the presentation file and rename them to 1, 2, etc.

## About

WavPlay-PPT is the PowerPoint version of WavPlay. It has been altered into
multiple forms to support the following audio codecs/containers:

* AIFF  (Audio Interchange File Format)
* FLAC  (Free Lossless Audio Codec)
* M4A   (MPEG-4 Part 14 container format, usually has AAC)
* MP3   (MPEG-1/2 Audio Layer III)
* OGA   (Ogg container format, usually has Vorbis)
* Opus
* WMA   (Windows Media Audio)

WavPlay is also available for Rainmeter (within EDENrm) and Java under the same
name.

### DirectShow Decoders

##### In Layman's Terms

Some versions of PowerPoint do not natively support third-party audio codecs
such as FLAC, Vorbis (OGA) and Opus. To mitigate over this limitation, install
their respective DirectShow Decoders. These can be obtained in one go by
downloading and installing
[[**K-Lite Codec Pack Basic**](http://codecguide.com/download_k-lite_codec_pack_basic.htm)].

This makes not only PowerPoint but also Windows compatible to almost any media
format out there within technical limits. Proceed below if you must.

##### Technically Speaking

PowerPoint supports the use of DirectShow filters to expand its media playback
capabilities. The same can be done to other applications that uses the
DirectShow multimedia framework, like MPC-HC. Think of them as plugins or
extensions to Windows.

This has led to concerns on affected PC behaviors due to conflicts between
multiple filters. This has been forgotten since the introduction of Media
Foundation, a new multimedia framework in Windows Vista and later. Additionally,
most games supply their own filters in the form of DLL files that usually sits
adjacent to their executable(s). A common example is Bink video.

Otherwise, codec packs reduce all these hassles by getting multiple filters done
right; installing individual filters is generally not recommended for the above
reasons.

Despite the mentioned advantage, I would still suggest to do so only if
required. Microsoft already started to add support for third-party codecs in
later versions of Windows and, presumably, Office.

## About WavPlay

WavPlay is any program that plays `wav` audio files.

### History

This project is formerly titled as WavPlayer.

It was first made for Rainmeter as one of the four "applications" in the
All-in-ONE skin suite (now EDENrm) when the pseudo-platform launched back in
January 2014. It sported the following features:

* Looping
* Track selection

The PowerPoint version was made shortly after and added the ability to pause as
this was not possible in Rainmeter. Its first release contained at least ten
slides, one for each track number. Later releases crammed the entire player
into one slide.

Overtime, more plugins were introduced to Rainmeter which led to the maturity of
WavPlay. New features added into this release include:

* Custom filename
* AutoPlay (sequential playback based on global silence detection)
* Track skip

The Java version was finished long after the former two. It is the only one that
can play up to 99 tracks sequentially without silence detection but no track
skip.

## Trademarks

PowerPoint is a trademark of Microsoft Corporation.
