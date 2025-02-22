=== Podlove Podcast Publisher ===
Contributors: eteubert
Donate link: https://opencollective.com/podlove
Tags: podlove, podcast, publishing, rss, feed, audio, mp3, m4a, player, webplayer, iTunes, radio
Requires at least: 4.9.6
Tested up to: 5.9
Requires PHP: 7.0
Stable tag: 3.8.0
License: MIT

The one and only next generation podcast publishing system. Seriously. It's magical and sparkles a lot.

== Description ==

We built the Podlove Podcast Publisher because existing solutions are stuck in the past, complex and unwieldy. The Publisher helps you save time, worry less and provides a cutting edge listening experience for your audience.

Official Site: [publisher.podlove.org](http://publisher.podlove.org/)

= Video Tutorial: Getting started with Podlove Publisher =

[youtube http://www.youtube.com/watch?v=Hmrm-jUe6u4]

= Compatible Feeds =

The Publisher makes it easy to create highly expressive, efficient and super compatible podcast feeds with fine grained control over client behavior (e.g. GUID control to replace faulty episodes and for clients to reload) supporting all important meta data.

= Multi-Format Publishing =

The Publisher also makes multi-format publishing - embracing all modern and legacy audio and video codecs - a snap. By adopting simple file name conventions, the plugin allows the podcaster to provide individual feeds for certain use cases or audiences without adding work for the podcaster during the publishing process.

= Optimized Web Player =

The Publisher also comes with integrated with the Podlove Web Player plugin (which you do not need to install separately) and fully support its advanced options including multiple audio (MP4 AAC, MP3, Vorbis, Opus) and video (MP4 H.264, WebM, Theora) format support for web browsers. This Web Player is fully HTML5 compatible (but provides Flash fallback for ancient environments) and is ready for all touch based clients too.

= Chapter Support =

The Publisher also makes it easy to publish chapter information in the player to make access to structured episodes even easier. Full support for linking directly to any part of your podcast on the web with instant playback included.

= Flexible Templates =

To round it all up, a flexible template system enables you to published Podcasts in a defined fashion and change the style at any time without having to touch your individual postings later on.

And this is just the beginning. We have a rich roadmap that will bring even more interesting features: integration with helpful services, much improved timeline metadata support (show notes) and much more.

= Further Reading =

* [Podlove Publisher](http://publisher.podlove.org/)
* [Podlove Project](http://podlove.org/)
* [Podlove Community](https://community.podlove.org/)
* [Documentation](http://docs.podlove.org/)
* [Bug Tracker](https://github.com/podlove/podlove-publisher/issues)
* [Donate](http://podlove.org/donations/)

Development of the plugin is an open process. The current version is available [on GitHub](https://github.com/podlove/podlove-publisher) Feel free to contribute and to fix errors or send improvements via GitHub.

Requires PHP 5.4+

== Frequently Asked Questions ==

### Is Podlove Podcast Publisher free?

Yes! The core features of Podlove Podcast Publisher are and always will be free. [Paid Professional Support](https://publisher.podlove.org/support/) is available but not necessary to run the plugin.

### Are there Download Statistics?

Yes! Podcast Downloads can be tracked and analyzed. You can easily see how many people downloaded you podcast episodes, which clients they used, if they prefer to subscribe to the feed or listen on your website using the web player—and much more.

### Are there Privacy / GDPR considerations?

Podlove Publisher is GDPR compliant and provides prewritten text snippets for your privacy page. See https://docs.podlove.org/podlove-publisher/guides/dsgvo-gdpr.html

### Where can I host my podcast files?

Any storage where you have control over the file naming is compatible with Podlove Podcast Publisher. You can manage files using a simple FTP/sFTP or use services like Amazon S3.

### Where can I ask questions and get support?

Free support where questions are answered by the community is available in the [Podlove Community Forum](http://community.podlove.org/). There is a German community in the [Sendegate](https://sendegate.de/).

### How can I help the project?

The continued success of Open Source project relies on the community. There are many ways you can help:
Episode title in API now follows the same rules as in RSS feed. There's a new field 'title_clean' for accessing the specifically set plain episode title, but that might be null in some cases, so it's better to default the 'title' attribute to the usual rules.
- If you enjoy the plugin, please [leave a review](https://wordpress.org/support/plugin/podlove-podcasting-plugin-for-wordpress/reviews/#new-post).
- You can answer questions of other fellow podcasters in the [Podlove Community](https://community.podlove.org/).

---

This product includes GeoLite2 data created by MaxMind, available from http://www.maxmind.com.

== Installation ==

1. Download the Podlove Publisher Plugin to your desktop.
1. If downloaded as a zip archive, extract the Plugin folder to your desktop.
1. With your FTP program, upload the Plugin folder to the wp-content/plugins folder in your WordPress directory online.
1. Go to Plugins screen and find the newly uploaded Plugin in the list.
1. Click Activate Plugin to activate it.

== Screenshots ==
1. Custom episode post type separates media from your blog content.
2. Download analytics provide you with all the data you ever wanted.
3. The Publisher automatically checks the health of your media files.
4. The mighty template engine gives you full control over the episode presentation.
5. Includes the Podlove Subscribe Button, the easiest way for listeners to subscribe to your podcast.
6. Includes the Podlove Web Player. One more thing: you can manage and present all contributors easily.

== Changelog ==

= 2022-09-04 =

- feat: New UI module for episode description related information

= 2022-07-25 =

- update webvtt parser to support closing voice tags and a missing trailing newline

= 2022-07-08 =

- feat(api): include season_id in episode

= 2022-07-01 =

- feat(api): add routes to handle episode contributions and social services
- feat(api): episode duration and slug enhancements

= 2022-06-19 =

- fix(core): incompatibility with matomo plugin by vendor-prefixing the device detector library
- fix(shows): display episode summary in show feeds instead of the show summary

= 2022-03-23 =

We're working on bringing the whole JavaScript codebase onto a modern foundation. You will discover the Chapter Marks and Transcripts sections have a new look, as they are the first components we upgraded. They should be functionally equivalent to before.

In the long run, this new foundation will allow us to build better interfaces on top of recent web technology.

----

Changes for previous versions can be found in the [`changelog.txt`](https://github.com/podlove/podlove-publisher/blob/master/changelog.txt).
