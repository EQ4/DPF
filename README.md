# DPF - DISTRHO Plugin Framework

DPF is designed to make development of new plugins an easy and enjoyable task.<br/>
It allows developers to create plugins with custom UIs using a simple C++ API.<br/>
The framework facilitates exporting various different plugin formats from the same code-base.<br/>

DPF can build for LADSPA, DSSI, LV2 and VST formats.<br/>
LADSPA, DSSI and VST implementations are complete, LV2 at ~95% completion.<br/>
A JACK/Standalone mode is also available, allowing you to quickly test plugins.<br/>

Plugin DSP and UI communication is done via key-value string pairs.<br/>
You send messages from the UI to the DSP side, which is automatically saved in the host when required.<br/>

Getting time information from the host is possible.<br/>
It uses the same format as the JACK Transport API, making porting some code easier.<br/>


List of plugins made with DPF:<br/>
 - [DISTRHO Mini-Series](https://github.com/DISTRHO/Mini-Series)
 - [DISTRHO MVerb](https://github.com/DISTRHO/MVerb)
 - [DISTRHO Nekobi](https://github.com/DISTRHO/Nekobi)
 - [DISTRHO ProM](https://github.com/DISTRHO/ProM)
 - [DISTRHO ndc Plugs](https://github.com/DISTRHO/ndc-Plugs)
 - [Juice Plugins](https://github.com/DISTRHO/JuicePlugins) (work in progress)
 - [ZamAudio Suite](https://github.com/zamaudio/zam-plugins)


Plugin examples are available [here](https://github.com/DISTRHO/plugin-examples).<br/>
OpenGL UI examples are available [here](https://github.com/DISTRHO/gl-examples).


Online documentation is available at [https://distrho.github.io/DPF/](https://distrho.github.io/DPF/).
