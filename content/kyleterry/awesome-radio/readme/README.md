# Awesome Radio Overview

Awesome radio stuff

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/kyleterry/awesome-radio/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 kyleterry/awesome-radio](https://github.com/kyleterry/awesome-radio) · ⭐ 191 · 🏷️ Miscellaneous

[ [Daily](/content/kyleterry/awesome-radio/README.md) / [Weekly](/content/kyleterry/awesome-radio/week/README.md) / Overview ]

---

# Awesome Radio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome radio resources. Inspired by awesome-\*.

I recently pulled out my CB radio and installed it in my truck. This inspired me
to create an open source repository of all the radio related resources I found
helpful and my notes on the subject.

This project is aimed at hackers who enjoy all aspects of radio communication.
While a lot of this technology isn't usable by citizens and is heavily regulated
by the FCC, just knowing anything about it is special. I've been interested in
learning the ins and outs of radio, as well as hearing stories, new and old.

## General

### Links

*   [Radio (wikipedia)](http://en.wikipedia.org/wiki/Radio)
*   [Radio Spectrum (wikipedia)](http://en.wikipedia.org/wiki/Radio_spectrum)
*   [Skywave (skip) (wikipedia)](http://en.wikipedia.org/wiki/Skywave)
*   [Mystery signal from a
    helicopter](http://www.windytan.com/2014/02/mystery-signal-from-helicopter.html)
*   [Portable SDR](http://hackaday.io/project/1538-PortableSDR)
*   [N0NBH's Solar-Terrestrial Data](http://www.hamqsl.com/solar2.html) - Current
    solar-terrestrial data, with explanation of their influence on HF propagation
    and propagation forecast.

## CB

Citizens band radio, or CB, is a two way radio spectrum dedicated to open use by
anyone for almost any purpose. In the US and many other countries, it
does not require a license to operate. CB consists of 40 channels between 26.965
MHz and 27.405 MHz with channel 09 being dedicated to emergencies.

CB is more popular among truckers and radio enthusiasts, but its usefulness
does not stop there. It's great for long distance travel on popular trucking
routes. You can tune to channel 19 (an unofficial trucker's channel) and get
real time traffic updates, alternate routes and accident warnings.

Given a good antenna that's properly tuned, a typical range to expect out of
your CB is about 2 - 5 miles (3.2 - 8 kilometers).

### General Use

I've found a lot of my information on Jeep and trucker forums. From my own
experience, it seems about half the CB transmission I hear include a handle of
some kind. I also hear a lot of swearing, so I wouldn't sweat accidentally
letting a "fuck" or a "shit" go.

CB is public. Very public. That seems like a "no shit" kind of thing, but with
the current generation pretty much only using cell phones, it's easy to forget
that using something as "primitive" as a CB radio is essentially [broadcast to
the world](http://en.wikipedia.org/wiki/Citizens_band_radio#Working_skip).

Truckers tend to use channel 19. This is a good channel to monitor for traffic
conditions.

Channel 9 is for emergencies only. No general chatter on this channel. If you
are broke down, or your car catches fire, besides calling 911, this is a good
channel to transmit on for help.

Around Portland, I hear a lot of chatter on channels 6, 17 and 28. These are
good channels for entertaining conversation.

### SWR

[SWR](http://en.wikipedia.org/wiki/Standing_wave_ratio), or Standing Wave Ratio
is a measurement of efficiency when connecting your antenna to your radio.

Optimum ratio is 1:1, although you'll probably end up with 1.3:1 or so. Anything
higher than 2:1 should be considered a no-no since it can damage your radio and
give poor transmission. Read up on [how to tune
SWR](http://www.rightchannelradios.com/tuning-cb-antenna-adjusting-swr).

### Installing a mobile CB

Installing your CB right is key to A) not damaging your radio hardware and B)
getting good range and quality on both the receiving and transmitting ends.

Following the advice in the following articles will ensure you have a quality
setup.

### Links

*   [Right Channel Radios](http://www.rightchannelradios.com/) - Good online shop
    for parts, radios, antennas and mounts.
*   [CB Slang](http://www.cbslang.com/) - mostly humorous, but kinda helpful.
*   [CB Slang (wikipedia)](http://en.wikipedia.org/wiki/List_of_CB_slang)
*   [CB Talk and etiquette](http://www.jeepforum.com/forum/f8/cb-radio-etiquette-jeep-trail-1169815/)
*   [Skip](http://cbradiomagazine.com/Articles/How%20to%20Shoot%20Skip.htm)
*   [Silly CB Handles](http://www.somethingawful.com/news/cb-handles/)
*   [CB FAQ](http://www.advancedspecialties.net/cb-radio-faq.htm)
*   [Frequency Table](http://www.radioreference.com/apps/db/?aid=7731)

## SDR (Software Defined Radio)

Software Defined Radio is a way to define components that are typically
hardware, such as filters and amplifiers, as software. It has been around for a
while, but with the cost of digital electronics needed to run SDR becoming
increasingly cheaper, we are seeing a rise in hacker folk playing and building
with SDR.

I would like contributors for this section.

### Links

*   [Gqrx](http://gqrx.dk/)
*   [sdrsharp on .NET](http://sdrsharp.com)

### Hardware

*   **Recommended starter hardware** On the low end,
    [RTL-SDR](http://sdr.osmocom.org/trac/wiki/rtl-sdr) is a super-cheap usb
    dongle, around which a thriving community has been founded.
*   On the other side of the cost spectrum, [pervices](http://www.pervices.com/)
    makes some really high-throughput, PCIe devices for when you need to log all
    the traffic ever. The software and community support for this is less good,
    though (for which you can blame @outofculture).
*   You can also browse through the [big
    list](https://gnuradio.org/redmine/projects/gnuradio/wiki/Hardware) of all
    compatible hardware.
*   Antennas are their own body of options and tradeoffs, about which I know
    nothing.

### Software

Depending on the hardware you're using, it may ship with some demo software to
play around with. This is great for just getting a chance to see some waves and
start to get an idea of what's possible. Otherwise, [GNU
Radio](https://gnuradio.org/redmine/) is going to where you'll spend your time.
It's mainly just a library, but it also has a supporting gui for combining
processing blocks that then outputs python. Once you're more comfortable, you
can also just use GNURadio to do any device tuning, setup and i/o, and then use
numpy for the signal manipulation math.

Just visualizing and manually inspecting a signal is a valuable part of learning
how to work with them. [Baudline](http://www.baudline.com/) is a janky old
thing, but it's the best there is. Be forewarned that learning the UI won't come
easily to anyone.

## Amateur Radio (a.k.a Ham Radio)

The hobby of Amateur Radio has a long and proud tradition. The very first radio
amateurs were true pioneers of radio technology. Amateurs 'invented' and refined
much of the early radio technology and were the first to transmit music, radio
plays, and information to the handful of people who had the new fangled radio
receivers.

After World War II the hobby of amateur radio flourished. Radio clubs sprang up
in schools all over the world and kids went home each night to build some new
contraption, or have a chat with someone over the wireless. These young people
became the mainstay of the technical professions and developed much of the
modern technology we use today.
([WIA](http://www.wia.org.au/licenses/foundation/about/))

[What is Ham Radio?](http://www.arrl.org/what-is-ham-radio)

### Links

*   American Radio Relay League - [ARRL](http://www.arrl.org/)
*   The Wireless Institute of Australia [WIA](http://www.wia.org.au/)
*   Radio Society of Great Britain - [RSGB](http://rsgb.org/)
*   Pakistan Amateur Radio Society - [PARS](http://www.pakhams.com/)
*   [The International Amateur Radio Union](http://www.iaru.org/)
*   [Japanese asteroid mission](http://www.arrl.org/news/amateur-radio-transponder-will-accompany-japanese-asteroid-mission-into-deep-space)
*   [Slow-scan Television](https://en.wikipedia.org/wiki/Slow-scan_television)

I would like contributors for this section.

### Amateur Radio License

*   In the [US](http://www.arrl.org/getting-licensed) there are three license
    classes—Technician, General and Extra.
*   [The Foundation Licence](http://www.wia.org.au/licenses/foundation/about/) in
    Australia.
*   \[Foundation Licence]
    (<http://rsgb.org/main/clubs-training/for-students/foundation/>) in the UK.
*   In
    [Pakistan](http://www.pakhams.com/index.php?option=com_content\&view=article\&id=75\&Itemid=92)
    first you apply for SWL (Short Wave Listener) membership and then you are
    eligible to [apply for the HAM
    License](http://www.pta.gov.pk/index.php?option=com_content\&view=article\&id=466%3Aamateur-wireless-license\&catid=138%3Aguidelines\&Itemid=349).

## Public Health and Safety

Police and fire in the United States typically communicate over trunked radio.
This makes it hard to scan using normal reciever without trunk tracking
abilities. See more in the [trunking](#trunking) section.

### Trunking

While not strictly specific to public health and safety, it is usually the first
thing that comes to mind when talking about trunked radio.

Trunked radio is a form of digital-two-way communication where multiple
organizations can share a small spectrum of real frequencies without hearing
another organizations conversations. A user can choose a logical channel or
group and the base station will find an empty frequency to transmit on.

### Links

*   [Project 25](http://www.project25.org/)
*   [Project 25 wikipedia](http://en.wikipedia.org/wiki/Project_25)
*   [Trunked Radio wikipedia](http://en.wikipedia.org/wiki/Trunked_radio_system)

