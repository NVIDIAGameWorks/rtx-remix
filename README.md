# RTX-Remix

NVIDIA RTX Remix, built on NVIDIA Omniverse, is an end-to-end platform for remastering DirectX 8 and 9 games with fixed function pipelines. NVIDIA RTX Remix enables experienced modders to remaster classic games by upgrading textures with AI, allowing easy replacement of game assets with high fidelity assets built with physically accurate materials, and injecting RTX path tracing, DLSS and Reflex technologies.

RTX Remix consists of two components: an application for creating lights and adding remastered assets into a game scene, and a runtime for capturing classic game scenes, injecting the remastered assets back into the game at playback, and relighting the game with path tracing. The RTX Remix runtime is open source–read about it [here.](https://www.nvidia.com/en-us/geforce/news/rtx-remix-runtime-open-source-download/#:~:text=The%20RTX%20Remix%20runtime%20is,modded%20game%20assets%20at%20runtime.)

The runtime itself consists of multiple components, each with its own git repo. This combined repo references those components via submodules, at the specific commits that make up the current stable [release](https://github.com/NVIDIAGameWorks/rtx-remix/releases).


## Contributions

All contributions should be directed towards the individual component repos (below), this repo is just tying it all together in one place.

Contributions accepted to any of the submodules will eventually make it into a public release for modders everywhere to experience.

* [dxvk-remix](https://github.com/NVIDIAGameWorks/dxvk-remix/)
* [toolkit-remix](https://github.com/NVIDIAGameWorks/toolkit-remix/)

### Related Repositories

* [ComfyUI RTX Remix Nodes](https://github.com/NVIDIAGameWorks/ComfyUI-RTX-Remix)

## Important Links

* [Download RTX Remix Application](https://www.nvidia.com/en-us/geforce/rtx-remix/)
* [RTX Remix Runtime Releases](https://github.com/NVIDIAGameWorks/rtx-remix/releases)
* [RTX Remix Release Notes](https://docs.omniverse.nvidia.com/kit/docs/rtx_remix/latest/docs/remix-releasenotes.html)
* RTX Remix [Documentation](https://docs.omniverse.nvidia.com/kit/docs/rtx_remix/latest/)
* RTX Remix Runtime [User Guide](https://github.com/NVIDIAGameWorks/rtx-remix/wiki/runtime-user-guide)
* [RTX Remix Tutorials](https://www.youtube.com/playlist?list=PL4w6jm6S2lzvgJ97T1_VbLGBR_l6zzOUm)
* [Development Roadmap](https://github.com/NVIDIAGameWorks/rtx-remix/wiki/roadmap)


## Forums, Support & Community Resources

Looking to contribute to the RTX Remix community or learn more about Remix? Join the [RTX Remix Discord Community](https://discord.gg/j6sh7JD3v9) where you can collaborate with other modders, showcase your projects, and get insight from members of the community as well as NVIDIA engineers. If you have issues to report or feedback to provide on RTX Remix, please always use the [Issues tab](https://github.com/NVIDIAGameWorks/rtx-remix/issues) of our GitHub.

If you are a modder, we encourage you to check out [ModDB’s community resources](https://www.moddb.com/rtx/) for RTX Remix. The ModDB community maintains an up to date compatibility table, which also includes config files that can easily get any compatible game working with RTX Remix out of the box. You can even download and submit captures for any game you like for the community to use in their own RTX Remix projects.

