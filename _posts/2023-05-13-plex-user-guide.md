---
title: Plex User Guide
author: andrew
date: 2023-05-13 20:00:00 -0500
categories: [Plex]
tags: [plex, user, homelab, media, new, guide, graphics, movies, tv, shows, tv shows, music, libraries, overseerr, requests, quality]
pin: true
image: https://www.smarthomebeginner.com/images/2020/02/best-media-server-for-plex-ft.jpg
---

- [Plex User Guide](#plex-user-guide)
  - [What's Plex?](#whats-plex)
    - [So what is Plex anyway?](#so-what-is-plex-anyway)
    - [Is Plex Free?](#is-plex-free)
    - [Is Plex legal?](#is-plex-legal)
  - [Getting Started](#getting-started)
  - [Playback Quality](#playback-quality)
  - [Libraries](#libraries)
  - [Navigation](#navigation)
      - [Recommended](#recommended)
      - [Library](#library)
      - [Collections](#collections)
      - [Playlists](#playlists)
    - [Playback](#playback)
- [Overseerr User Guide](#overseerr-user-guide)
  - [Link to Overseerr](#link-to-overseerr)
  - [Requests](#requests)
    - [Making Requests](#making-requests)
      - [Requesting Movies](#requesting-movies)
      - [Requesting TV Series](#requesting-tv-series)
    - [Checking Requests](#checking-requests)
  - [Issues](#issues)
  - [Email Settings](#email-settings)

# Plex User Guide

This guide is meant to walk you through what Plex is, what it can do, and a few first steps that are suggested before you stream or request any media. 

> Please keep in mind that I operate this Plex server as a hobby, and I have multiple friends and family members that use the server. The best way to get support is to reach out to me directly or on the 'Plex Users' group chat.
{: .prompt-info }

## What's Plex?

### So what is Plex anyway?

You can think of Plex as a streaming service like Netflix or Hulu that is operated by someone you know instead of a huge company. What this means is that they have complete control over what content is available, and can often obtain shows and movies that you're looking for (even if they aren't available on other streaming platforms).

### Is Plex Free?

Server owners typically provide access to close friends and family only and don't charge for it.

Many server operators do pay a monthly or yearly fee for some additional features known as Plex Pass from the company that makes the Plex software. This helps to support ongoing efforts to make the Plex software better.

Additionally, Plex servers are a significant investment for the owner. The server hardware and storage devices are expensive to obtain and operate.

As a viewer, you can connect to and watch content on Plex servers for free through the Plex.tv website. However, viewing on the website often requires that the server transcode the media for you (more on that later). By using a Plex player that's specific to your hardware and platform, you'll get a better playback experience.

### Is Plex legal?

Plex is just a collection of software encompassing servers and clients. Plex itself is perfectly legal.

You can use Plex to stream content anywhere without worrying about copyright notices or the need to use a VPN or other means to hide your traffic.

## Getting Started

If you're here, you were probably invited to join my Plex server. The first step is to send me the email address you will use to create your free Plex account. If you've already done this: excellent, continue reading!

Shortly after you'll receive an email inviting you to join my server. Click the link in the email to accept the invitation and create your account at Plex. Once logged in, you may be asked to "Sync Watch State." I recommend enabling this feature, as it tracks your watch progress and allows you to start watching on one device and pick up on another. It also adds a "Continue Watching" section to your Home screen.

Please don't share the account you create with others. If you know someone who you think would enjoy having access to this server, have them contact me. In most cases I'll be happy to add them with their own account. 

> Additionally, if you decide to purchase a Plex Pass (unlocks some paid features within your Plex players), the people you add to your "Plex Home" will not have access to my libraries.
{: .prompt-warning }

Now's the time to connect your playback devices to your new account. Depending on what you're using, you may need download and install the Plex app your device, or one may have come pre-installed. (This includes the App Store on iOS devices, the Google Play Store on Android devices, and other similar stores and libraries on other platforms like Roku.)

Upon first use for most of these platforms, you will either have to log in with your username and password, or link the device with your account when prompted. To link your account, your Smart TV or streaming device will show you a code made of 4 letters or numbers. Simply visit [plex.tv/link](https://www.plex.tv/link/) and enter the code (you may have to sign in first if you're not already). This linking process saves you from having to enter your username and password on your TV which can be frustrating.

Once you've entered the code, your streaming device should sign in automatically after a few moments.

You can visit the [Plex downloads page](https://www.plex.tv/media-server-downloads/#plex-app) to see a list of platforms on which the Plex player is available and be directed on how to install it for your device.

For convenience, Plex provides an online web client you can use to watch content at [app.plex.tv](https://app.plex.tv/). This makes it easy to catch up on your favorite shows while traveling or away from your preferred devices. However, using the web client should be avoided when possible as it is inefficient and puts unnecessary strain on the Plex server hardware.

## Playback Quality

> You will have to set your Video Settings on **each** device that you will be using to watch Plex.
{: .prompt-info }

Plex playback quality is dynamic and tries to adjust to the capabilities of your player and to the available internet bandwidth. However, out of the box, the quality settings in most Plex players are very conservative.

To increase the quality of your playback experience, locate the Settings in your Plex app, and navigate to the Video Settings section. Typically, you should try to set **Local Quality** to *Original* and set **Remote Quality** to *Maximum*. If you then find playback stutters or pauses frequently, reduce the quality setting until you achieve smooth playback. This will ensure that media is played on your device at the highest quality possible and can help reduce strain on the Plex server.

> See [this post](https://docs.shaffer.network/posts/plex-video-settings/) for device-specific instructions on how to set up your Video Settings!
{: .prompt-warning }

## Libraries

Plex servers are organized with Libraries in order to accomplish a number of things. Foremost, this helps viewers locate the content they're looking for. Broad categories like TV Shows and Movies also enable the Plex server to obtain the correct information to fill in the details about content such as the synopsis, actors and other information about the media. Libraries are often further separated into subjects like Reality TV, Kid's TV or Documentaries to facilitate finding what you want to watch.

On my server, you will have been granted access to my Movies (which includes 4K versions), TV Shows (also includes 4K content), Stand-Up (for stand-up specials), and potentially one or two more. I may eventually add a separate library for Anime, if the need arises.

> **Note:** The Plex creators recently added a new Library that appears for all users called *"Movies & TV On Plex"*. Users should know that the ad-supported content in this special library is not provided by the owner of the Plex server and is available through a deal between Plex software and a number of movie studios. Plex server owners have no control over the content of this library. **In most Plex players, you can find an option to Unpin this library from your list so it doesn't appear.**
{: .prompt-warning }

## Navigation

Depending on what device or platform you're using Plex from, the interface can vary slightly, but typically you will find a list of the Libraries on the server located on the left side of the display. Clicking or tapping the name of a Library will change the content view on the bulk of the page to that Library. Along the top of the main view you can switch between the Recommended, Library, Collections, or Playlists tabs.

#### Recommended

This is a view of content the server selects automatically that contains a "Continue Watching" section and a mix of items in this library that are new or popular.

#### Library

This view shows the full contents of the Library. This will be in alphabetical order by default, but you can use filters and sorting to change how the list is presented.

#### Collections

Collections are a way to organize films and group them together.

The first few sections of the Collections page are mostly organizational: Newly Released, Seasonal films, IMDb Top 250, etc. The next section are streaming service original movies/series that I have available. The next section is for production companies, and the next is for award winners (Oscar winners, Golden Globe winners, etc.). The final two sections are for Directors/Writers and Actors (these will be deceased actors and you may find them featured on your Home page when a new collection is added).

The rest of the Collections tab is for movie series, i.e. Iron Man (includes Iron Man, Iron Man 2, and Iron Man 3), TV Series that had movie adaptations, i.e. Downton Abbey (these will show you the Movies and TV Shows in the collection, regardless of which Library you are currently browsing), and other collections. 

> Please note that if a movie is in a "film series" collection, they will typically be hidden from the rest of the library while browsing alphabetically. This means that **some movies may seem like they're missing** because the title of the collection doesn't match the title of the movies. For example, the films *Unbreakable*, *Split*, and *Glass* are in a collection titled, "Eastrail 177," and the films *Shaun of the Dead*, *Hot Fuzz*, and *The World's End* are in a collection titled, "The Cornetto Trilogy."
{: .prompt-tip }

#### Playlists

Playlists are curated lists of films and TV episodes with an emphasis on their ordering. For example, you may have a Playlist for Marvel's Infinity Saga and Multiverse Saga, as well as an "MCU Ultimate Watchlist" Playlist. The "MCU Ultimate Watchlist" contains all of the MCU films (and television series!) in their suggested watch order. There are other playlists available for crossover series, such as *The Vampire Diaries*, *The Originals*, and *Legacies*.

### Playback

Playback works very similar to how it does on other streaming services.

On streaming devices, if you push the play button on a title, playback should begin immediately. If you press select/OK/enter, you'll be taken to the information page about a title. For movies this will include a summary and other information. For a TV show, this will go to a list of seasons. And from there you can select a season to view the list of individual episodes.

On a desktop client, when the mouse is over the title image, a Play button will be visible - if you click that, playback should begin. If you click elsewhere, the process will be similar to selecting on a streaming device.

# Overseerr User Guide

## [Link to Overseerr](https://request.shaffer.network)

Once you've navigated to Overseerr, you will use the "Sign in with Plex" option *unless otherwise instructed*. Once signed in, you can add Overseerr to your home screen if you're accessing it from a mobile device. See the instructions below for more information.
- [How to Add a Website to the Home Screen on iPhone and Android (How-To Geek)](https://www.howtogeek.com/196087/how-to-add-websites-to-the-home-screen-on-any-smartphone-or-tablet/)

## Requests

Overseerr is used primarily as a way for you to request media to be added to Plex. All requests must be approved before they begin downloading, and TV requests may take a little longer as they typically have to be downloaded one season at a time.

> Please be aware that requests made using Overseerr are visible to **all other users** of Overseerr.
{: .prompt-warning }

### Making Requests

You can search for new movies and series using the search bar at the top of the screen. You can also browse popular movies/series using the tabs on the left of the screen or in the various sections of the home screen. 

> There are icons in the upper-right corners of some posters. These correspond to the item's status; a green checkmark means it's already available, a green dash means that it's partially available (i.e., some seasons of a show are available, but not all), and a purple clock means that it's been requested, but not downloaded (or released) yet.
{: .prompt-tip }

Once approved, movie requests should begin downloading automatically, but TV requests still need to be downloaded manually, which can increase the time before they are available.

#### Requesting Movies

Once you've found an item you'd like to request, you can either click/tap the Request button on the poster, or click/tap the poster itself for more information on the title (cast, crew, similar titles, runtime, etc.). Once you click/tap Request, a pop-up will display asking you to confirm this request. 

#### Requesting TV Series

Once you've found an item you'd like to request, you can either click/tap the Request button on the poster, or click/tap the poster itself for more information on the title (cast, crew, similar titles, season/episode info, etc.). Once you click/tap Request, a pop-up will display asking you to confirm this request and which seasons you'd like to request. 

When you request a *current* series (one that is still airing), the server will **automatically download new episodes as they become available**.

> If you'd like a specific season to be downloaded, i.e. the most recent season, please select only that season. Otherwise, select all seasons. I'm an obsessive completist, so I will eventually get around to downloading the entire series if it's requested, but I'll start with a specific season if that's what you request.
{: .prompt-info }

### Checking Requests

You can view active requests by clicking/tapping on Requests in the sidebar. Here you will find some additional information on your active requests and the requests of others. Here's what each of the "Status" items mean:
- Requested: The item was requested but it hasn't begun downloading yet.
- Pending: The item is still awaiting approval before it can begin downloading.
- Processing: The item is currently downloading or is in the queue to be downloaded once other downloads have completed.
- Available: The item has been downloaded and added to Plex successfully.
- Partially Available: A portion of item requested was downloaded. This is usually because multiple seasons were requested and only some of them are available so far, but it also appears on new series that are currently airing.  

## Issues

One of the other features of Overseerr is that it allows you to file issues with media items. This allows you to let me know that there is something wrong with a movie or TV series that needs addressing. To file an issue, please follow these steps:
1. Search for the problem item (i.e., the movie or show that's not playing properly).
2. Click the yellow "Report an Issue" button (it may look like a yellow warning sign on some devices).
3. If it is a TV series, please select which season is affected or leave the dropdown set to "All Seasons."
4. Select whether the issue is with the Video, Audio, Subtitle, or Other.
5. Add a description of what is wrong. 

Examples: 
- Issue > Audio > "The audio for season one episode two is in the wrong language."
- Issue > Video > "This is the wrong movie."
- Issue > Subtitle > "The S02E03 subtitles aren't synced up correctly."
- Issue > Other > "The player closed unexpectedly after I hit play."

## Email Settings

By default, Overseerr will notify you by email when your request becomes available and when an issue you reported is resolved. To change these settings, go to Settings > Notifications and you can disable/enable whichever notifications fit your preferences. 
