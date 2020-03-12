# domoticz-blebox-builds

Builds/releases from master branch at https://github.com/gadgetmobile/domoticz-blebox-support


## Who is this for?

If you are a Domoticz user and you have purchased BleBox devices, I'd highly recommend switching to Home Assistant as soon as you can.

(More info on BleBox support in Home Assistant: https://github.com/gadgetmobile/home-assistant-blebox)

However, if you want decent BleBox device support and you're for some reason REALLY stuck with Domoticz ...

... I've pre-built some special Domoticz packages for you.

(If you want to build the version yourself, go here: https://github.com/gadgetmobile/domoticz-blebox-support)


## How do I use this?

1. Download the archive from https://github.com/gadgetmobile/domoticz-blebox-builds/releases
2. Unzip
3. You'll have a tgz archive (much like the kind Domoticz releases and uses for updates)
4. Replace your installed files and restart Domoticz (?)
5. Probably disable official updates
6. BleBox support should now work really well for 11 devices (completely new hardware setup strategy!)


## Issues

- Domoticz updates still uses official URLS (so you may want to avoid updates until new releases appear here)
- May fall behind official version (but rebases/merges with offical version are usually pretty trivial)
- Using Domoticz at all is an issue


## Why isn't this in the official version?

One of the Domoticz maintainers rejected the changes without giving competent, convincing arguments.

(All of my PRs were suddenly closed without a reason).

He also asked me to do things that would likely hurt Domoticz users.

I consider that too unethical and unprofessional for my standards and values.

Switch to Home Assistant as soon as you can, because it has:

- more competent developers
- much, much higher level of care and quality
- faster releases
- more stability
- modern development tools
- higher appreciation for contributors
- much better documentation
- project isn't dead


## Support / Contributions

I don't plan on supporting this much, though free to report issues in case I've made a mistake on my side somewhere.
