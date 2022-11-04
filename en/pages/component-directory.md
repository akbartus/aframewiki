# Component Directory

## Origin
This is the modern, community-maintained alternative to the out-of-date A-Frame Registry.

The historical standard has been to publish and search for component on A-Frame. This adds some overhead, though, and only searching on NPM can mean missing a lot of possible projects. A-Frame doesn't require a complex build process, either, so installing with NPM may not always be the best fit--the community can get a speed boost to our pages by all using the same cached CDNs, actually.

The focus here is not on the original author's repo, but on the most up-to-date fork available of a repo. If two forks are both viable with unique features, they can both be listed separately.

## Notes for editors

- Listings should be alphabetized. Where the name begins with "A-" or "a-" or "aframe-", it should be ignore for alphabetizing purposes, and removed from the listing title. "-component" should also be removed from the listing title.

- You may find it easier to edit the table in an external markdown editor such as Typora. Just copy/paste the whole article across, make your edits, and copy/paste back.

- Please avoid pasting raw links into the table as they mess with formatting (the markdown renderer refuses to split them, so everything gets pushed off to the right). To be clear: share links using this markdown code: `[link text](https://link.com)`, which will look like this: [link text](https://link.com).


## Notable collections of components

[A-Frame's built-in components](https://aframe.io/docs/1.3.0/components/animation.html) 

[A-Frame Extras set of additional components](https://github.com/n5ro/aframe-extras)

[Superframe components]( https://supermedium.com/superframe/)

Other community components mentioned in the [A-Frame docs](https://aframe.io/docs/1.3.0/introduction/#off-you-go) include:

> [environment](https://github.com/supermedium/aframe-environment-component), [state](https://npmjs.com/package/aframe-state-component), [particle systems](https://github.com/IdeaSpaceVR/aframe-particle-system-component), [physics](https://github.com/n5ro/aframe-physics-system), [multiuser](https://github.com/networked-aframe/networked-aframe), [oceans](https://github.com/n5ro/aframe-extras/tree/master/src/primitives), [teleportation](https://github.com/fernandojsg/aframe-teleport-controls), [super hands](https://github.com/wmurphyrd/aframe-super-hands-component), and [augmented reality](https://github.com/jeromeetienne/AR.js#augmented-reality-for-the-web-in-less-than-10-lines-of-html).

## Directory of individual components

Note, this directory does not include A-Frame built-in components - for which you can refer to the [A-Frame documentation](https://aframe.io/docs/1.3.0/components/animation.html).

This table is always a work in progress. Currently all of the following collections have been folded in:

- Original A-Frame registry
- A-Frame extras
- Superframe

If you find something that isn't here add it! If you build something, add it! Old components can also be added, just list the version number; someone could find a valuable starting point and fork and revive it.

| Component| Description | Link   | Example | Status | Confirmed w/ A-Frame Version | See also |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------- |
| 3dtiles | A-Frame component to stream and render 3DTiles | [Repo](https://github.com/nytimes/aframe-loader-3dtiles-component) | [Examples](https://nytimes.github.io/aframe-loader-3dtiles-component/)| Maintained| 1.3.0 | |
| 6dof-object-control | 6DoF Controls for in-scene entities | [Repo](https://github.com/diarmidmackenzie/6dof-object-control) | None | Maintained | 1.3.0 | |
| aabb-collider | An axis-aligned bounding box component for A-Frame. | [Repo](https://github.com/supermedium/superframe/tree/master/components/aabb-collider/) | [Example](https://supermedium.com/superframe/components/aabb-collider/) | Unknown | Unknown| |
| aobake | aframevr component for auto baking ambient occlusion to the vertex colors| [Repo](https://github.com/supereggbert/aframe-aobake-component) | [Example](https://supereggbert.github.io/aframe-aobake-component/dist/examples/index.html) | Unknown | 1.3.0| |
| alongpath| A-Frame Component that allows entities to follow predefined paths | [Repo](https://github.com/protyze/aframe-alongpath-component) | [Similar concept](https://scroll-along-path.glitch.me/) | Unknown| 0.6 | curve |
| animation-mixer | Animation mixer for JSON and glTF models. | [Repo](https://github.com/c-frame/aframe-extras/tree/master/src/loaders) | [Example](https://rexraptor08.github.io/animation-controls/) | Maintained| 1.3.0 | |
| animation-timeline | A timeline component to use with the A-Frame animation component. | [Repo](https://github.com/supermedium/superframe/tree/master/components/animation-timeline/) | [Example](https://supermedium.com/superframe/components/animation-timeline/) | Unknown| Unknown| |
| atlas-uvs| An A-Frame component to set UVs onto a plane geometry given a gridded texture atlas. | [Repo](https://github.com/supermedium/superframe/tree/master/components/atlas-uvs/) | [Example](https://supermedium.com/superframe/components/atlas-uvs/) | Unknown| Unknown| spritesheet|
| atoll-terrain| a circle of high-resolution terrain near the origin, surrounded by a low-resolution sea or plain that stretches to the horizon| [Repo](https://github.com/DougReeder/aframe-atoll-terrain) | [Example](https://dougreeder.github.io/aframe-atoll-terrain/example.html) | Slow updates| 1.2.0| mountain, a-hexmap, environment, a-ocean, water|
| audio-analyser | Audio visualizations in A-Frame using Web Audio (AnalyserNode) | [Repo](https://github.com/ryota-mitarai/aframe-audio-analyser) | [Example](https://github.com/ryota-mitarai/aframe-audio-analyser/tree/master/examples) | Unknown | 1.2.0 | |
| BabiaXR | Data visualization with A-Frame | [Repo](https://gitlab.com/babiaxr/aframe-babia-components) | [Examples](https://babiaxr.gitlab.io/aframe-babia-components/) | Maintained | 1.3.0
| blend-transforms | Position an object with a weighted blend of two different objects' position, scale & rotation. | [Repo](https://github.com/diarmidmackenzie/screen-display) | [Examples](https://github.com/diarmidmackenzie/screen-display/#usage-guidelines) | Actively Maintained | 1.3.0 | |
| blink-controls | Feature-rich extension of aframe-teleport-controls| [Repo](https://github.com/jure/aframe-blink-controls) | [Examples](https://jure.github.io/aframe-blink-controls/) | Maintained | 1.3.0 | teleport-controls |
| broadcast| Multi-user in A-Frame using raw websockets | [Repo](https://github.com/supermedium/superframe/tree/master/components/broadcast/) | [Example](https://supermedium.com/superframe/components/broadcast/) | Unknown| Unknown| networked-aframe |
| broadcast| Multi-user in A-Frame using raw websockets | [Repo](https://github.com/etiennepinchon/aframe-bubble) | [Example](http://stemkoski.github.io/Three.js/Bubble.html) | Abandoned| 0.6.1| [Stemkoski Examples](http://stemkoski.github.io/Three.js/) |
| button-controls | Especially useful for apps designed to be usable with Google Cardboard V2, Gear VR without a separate Controller, mobile and desktop | [Repo](https://github.com/DougReeder/aframe-button-controls) | [Example](https://dougreeder.github.io/aframe-button-controls/example.html) [Elfland Glider](https://dougreeder.github.io/elfland-glider/) | slow updates | 1.1.0 | gamepad-controls |
| camera-fade-in | Component for fading the camera | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/camera-fade.js) | [Example](https://stemkoski.github.io/A-Frame-Examples/fade-in.html) | Unknown | Unknown| |
| camera-recorder | A component to film and record A-Frame scenes with a controlled camera (pans, dollies, tilts). | [Repo](https://github.com/supermedium/superframe/tree/master/components/camera-recorder/) | [Example](https://supermedium.com/superframe/components/camera-recorder/) | Unknown| Unknown| |
| charts | Make 3d charts in A-Frame | [Repo](https://github.com/adrixp/aframe-charts-component) | [Examples](https://adrixp.github.io/aframe-charts-component/) | Unknown | 1.0.4 | [data-vis](/data-vis)https://aframe.wiki/en/data-vis) |
| checkpoint | Target for checkpoint-controls. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | checkpoint-controls |
| checkpoint-controls | Move to checkpoints created with the `checkpoint` component. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 0.9+ | checkpoint |
| chromakey-material | A chromakey material for green screening in A-Frame. | [Repo](https://github.com/nikolaiwarner/aframe-chromakey-material) | None | Maintained	| 1.3.0 | checkpoint |
| console | console.log/warn/error in VR. Dynamic resizing, customizable. | [Repo](https://github.com/kylebakerio/a-console) | [example](https://canvas-log.glitch.me/) | Maintained	| 1.3.0 ||
| crawling-cursor | An A-Frame component to move cursor along objects' surface. | [Repo](https://github.com/jujunjun110/aframe-crawling-cursor) | [Example](https://jujunjun110.github.io/aframe-crawling-cursor/basic/) | Unknown| 0.7 | |
| cross-section | A-Frame Cross-Section Component. | [Repo](https://github.com/akbartus/AFrame-Cross-Section-Component) | [Example](https://cross-section-component.glitch.me/) | Unknown| 1.3.0 | |
| csg-meshs | A component for A-Frame that allows runtime Constructive Solid Geometry. | [Repo](https://github.com/SebastianBaltes/aframe-csg-meshs) | [Example](https://sebastianbaltes.github.io/aframe-csg-meshs/examples/index.html) | Unknown | 0.7 | |
| cursor-teleport | An A-Frame component for navigating scenes on non-VR devices | [Repo](https://github.com/mwbeene/aframe-cursor-teleport) | [Example](https://mwbeene.github.io/aframe-cursor-teleport/examples/basic/index.html) | Maintained| 1.2.0 | |
| curve | A component for drawing curves and defining curved paths | [Repo](https://github.com/kylebakerio/aframe-curve-component) | [Example](https://follow-path.glitch.me/) | Minimum Maintenance | 1.3.0 | alongpath |
| daylight-system | A component for accurately positioning the sun according to time/date/lat/lon | [Repo](https://github.com/EX3D/aframe-daylight-system) | see repo | Unknown | 1.1.0 | environment-component, aframe-simple-sun-sky |
| debug-cursor | A component to pretty-log cursor events. | [Repo](https://github.com/supermedium/superframe/tree/master/components/debug-cursor/) | [Example](https://supermedium.com/superframe/components/debug-cursor/) | Unknown| Unknown| |
| dial | A clickable analog timer or gauge display | [Repo](https://github.com/DougReeder/aframe-dial) | [Example](https://dougreeder.github.io/aframe-dial/example.html) | slow updates | 1.2.0 | |
| dust | A cloud of particles which respawn in front of the user | [Repo](https://github.com/DougReeder/aframe-dust-component) | [Example](https://dougreeder.github.io/aframe-dust-component/example.html) | slow updates | 1.1.0 | particle-system, mesh-particles |
| e2e-testing| End-to-end testing for A-Frame using Playwright | [Repo](https://github.com/diarmidmackenzie/aframe-e2e-testing) | See examples in repo | Actively maintained | 1.3.0 | |
| fix-fog| Improves ([fixes](https://fern.solutions/dev-logs/aframe-adventures-02/)) A-Frame's Fog component | [Repo](https://github.com/mrxz/fern-aframe-components/tree/main/fix-fog) | [Example](https://aframe-components.fern.solutions/fix-fog) | Actively maintained | 1.3.0 | |
| entity-generator | Generate a number of entities in A-Frame given a mixin. | [Repo](https://github.com/supermedium/superframe/tree/master/components/entity-generator/) | [Example](https://supermedium.com/superframe/components/entity-generator/) | Unknown| Unknown| |
| environment| Infinite environments for your A-Frame VR scene in just one file. | [Repo](https://github.com/supermedium/aframe-environment-component) | [Example](https://supermedium.com/aframe-environment-component/) | Working| 1.3.0 | shader-buildings, aframe-atoll-terrain, aframe-simple-sun-sky |
| environment-map | Generate environment maps from aframe-environment-component for proper PBR reflections on metallic materials | [Repo](https://github.com/msfeldstein/aframe-environment-map-component) | N/A | Unknown| 1.0.1 | environment, hdr-environment-map |
| enviropacks| High resolution environments, textures, and lighting from a CDN | [GitLab](https://gitlab.com/zach-geek/aframe-enviropacks) | [Example](https://glitch.com/edit/#!/aframe-enviropacks?path=index.html) | Occasionally maintained | 1.3.0 | |
| event-set| Component to set properties in response to events.| [Repo](https://github.com/supermedium/superframe/tree/master/components/event-set/) | [Example](https://supermedium.com/superframe/components/event-set/) | Working| 1.3.0 | |
| exokit-avatars| Full body IK (inverse kinematic) avatars| [Repo](https://github.com/msub2/aframe-exokit-avatars) | [Example](https://msub2.github.io/aframe-exokit-avatars/examples/) | Working| 1.3.0 | |
| extended-wasd-controls| WASD-controls, but with keys to handle flying as well | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/extended-wasd-controls.js) | [Example](https://stemkoski.github.io/A-Frame-Examples/extended-wasd-controls.html) | unknown | 1.3.0 | wasd-controls, movement-controls |
| extra-stats| Improved `stats` component| [Repo](https://github.com/mrxz/fern-aframe-components/tree/main/extra-stats) | [Example](https://aframe-components.fern.solutions/extra-stats/) | Maintained| 1.3.0 | |
| fbx-model| Loader for FBX format. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/loaders) | None | Unknown| 0.9+ | |
| firebase | Multi-user in A-Frame using Firebase | [Repo](https://github.com/supermedium/superframe/tree/master/components/firebase/) | [Example](https://supermedium.com/superframe/components/firebase/) | Unknown| Unknown| networked-aframe |
| forcegraph | A 3D Force-Directed Graph component for A-Frame. | [Repo](https://github.com/vasturiano/aframe-forcegraph-component) | None | Maintained | Unknown - probably 1.2.0 or 1.3.0 | |
| fps-counter| A simple FPS counter component to measure performance in VR for A-Frame. | [Repo](https://github.com/supermedium/superframe/tree/master/components/fps-counter/) | [Example](https://supermedium.com/superframe/components/fps-counter/) | Unknown| Unknown| vr-super-stats |
| fractal | Component for graphing "audio responsive points" | [Repo](https://github.com/Tino-F/aframe-fractal-component) | [Examples](https://github.com/Tino-F/aframe-fractal-component/tree/master/examples/) | Unknown| 0.8.2| |
| gaze | Look control that interprets gaze data as input. | [Repo](https://github.com/jsimonson2013/aframe-gaze-component) | None | Unknown| Unknown| |
| gamepad-controls | Gamepad-based rotation and movement. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 0.9+ | movement-controls |
| geometry-merger | An A-Frame component to merge geometries to reduce draw calls. | [Repo](https://github.com/supermedium/superframe/tree/master/components/geometry-merger/) | [Example](https://supermedium.com/superframe/components/geometry-merger/) | [Broken](https://github.com/supermedium/superframe/issues/304) | Unknown| instanced-mesh |
| geothree | World-scale maps using geo-three and support for multiple map providers (Mapbox, Bing, HereMaps, etc) | [Repo](https://github.com/arvind-iyer/aframe-geothree#readme) | [example](https://aframe-geothree-example.glitch.me/) | Unknown | 1.2.0 | mapbox |
| gltf-part| A component to extract parts from a GLTF model into their own A-Frame entities. | [Repo](https://github.com/supermedium/superframe/tree/master/components/gltf-part/) | [Example](https://supermedium.com/superframe/components/gltf-part/) | Unknown| Unknown| |
| grab | When used on one or both hands, lets the player pick up objects with `vive-controls`. Requires `sphere-collider`. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | sphere=-collider |
| grid | Square grid primitive for scene debugging. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/primitives) | None | Unknown| Unknown| |
| haptics (supermedium) | An old controller haptics (vibrations) component for A-Frame from the WebVR days | [Repo](https://github.com/supermedium/superframe/tree/master/components/haptics/) | [Example](https://supermedium.com/superframe/components/haptics/) | Unknown | 0.7.0 | |
| haptics | A controller haptics (vibrations) component for A-Frame that was built for a WebXR game | [Repo](https://github.com/kylebakerio/A-Haptics) | see repo | Maintained| 1.3.0| |
| hand-tracking-controls | A variety of components for using hand-tracking without controlers | [Repo](https://github.com/gftruj/aframe-hand-tracking-controls-extras/tree/master/components) | [examples](https://github.com/gftruj/aframe-hand-tracking-controls-extras/tree/master/examples) | unknown | 1.3.0| |
| handy-work | hand controls with gesture recognition | [Repo](https://github.com/AdaRoseCannon/handy-work) | [example](https://aframe-xr-starterkit.glitch.me/) | Maintained| 1.3.0| |
| hexmap | Hexagon map loaded from a JSON file, using [von-grid](https://github.com/vonWolfehaus/von-grid). | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/primitives) | None | Unknown| 0.9+ | |
| highlight| Highlight parts of objects that are occluded | [Repo](https://github.com/mrxz/fern-aframe-components/tree/main/highlight) | [Example](https://aframe-components.fern.solutions/highlight/) | Maintained | 1.3.0 | |
| hologram-shader | An A-Frame shader for creating stylized holograms from images and videos | [Repo](https://github.com/TravisBarryDick/aframe-hologram-shader) | [Example](https://travisbarrydick.github.io/aframe-hologram-shader/dist/index.html) | Unknown| 1.2.0 ||
| hdr-environment-map | Adds support for equirectangular hdr maps to A-Frame | [Repo](https://github.com/mwbeene/aframe-hdr-environment-map) | [Example](https://mwbeene.github.io/aframe-hdr-environment-map/) | Maintained| 1.3.0 ||
| html-mesh | Element for displaying HTML based on THREE.js HTMLMesh | [Repo](https://github.com/AdaRoseCannon/aframe-htmlmesh) | [Example](https://ada.is/aframe-htmlmesh/) | Maintained| 1.3.0 | web2vr, websurfaces |
| instanced-mesh | Instancing support for A-Frame (allows rendering of multiple instances of a mesh with a single draw call) | [Repo](https://github.com/diarmidmackenzie/instanced-mesh) | [Example](https://github.com/diarmidmackenzie/instanced-mesh#examples) | Actively Maintained | 1.3.0 | |
| interactive-book | make pdfs into interactive books | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/interactive-book.js) | [Example](https://stemkoski.github.io/A-Frame-Examples/quest-book.html) | Unkown | 1.3.0 | |
| jump-ability | Allows player to jump using keyboard or gamepad, when physics is enabled. *Not VR-friendly*. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | |
| keyboard | Component that renders a fully functional 3D keyboard, that works on mobile, desktop browers, and VR headsets. | [Repo](https://github.com/WandererOU/aframe-keyboard) | [Example](https://wandererou.github.io/aframe-keyboard/examples/basic/index.html) | Unknown | 1.0.4 | super-keyboard |
| keyboard-controls | WASD + arrow controls for movement, and more. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 1.3.0 | movement-controls |
| layout | Position and layout child entities in 3D space for A-Frame | [Repo](https://github.com/supermedium/superframe/tree/master/components/layout/) | [Example](https://supermedium.com/superframe/components/layout/) | Unknown| Unknown| |
| leap-hands | Leap Motion components for A-Frame VR | [Repo](https://github.com/openleap/aframe-leap-hands) | None | Unknown| Unknown| |
| lensflare | A component to add a configurable lens-flare (and optional light) to an entity that wraps THREE.JS Lensflares. | [Repo](https://github.com/mokargas/aframe-lensflare-component) | None | Unknown| 0.5| |
| lines | Multiple 1-pixel-wide lines (very efficient) | [Repo](https://github.com/DougReeder/aframe-lines) | [Example](https://dougreeder.github.io/aframe-lines/example.html) [Barrier Mage](https://dougreeder.github.io/barrier-mage/) | slow updates | 1.1.0 | built-in line |
| liquid-portal-shader | Shader to create an attractive portal with complex edges | [Repo](https://github.com/TravisBarryDick/aframe-liquid-portal-shader) | [Example](https://travisbarrydick.github.io/aframe-liquid-portal-shader/dist/index.html) | Unknown | 1.2.0? | |
| locomotion | A collection of A-Frame components, systems and primitives that enable all sorts of locomotion in VR. It's built to be modular, flexible and easy to use. | [Repo](https://github.com/mrxz/aframe-locomotion) | [Examples](https://aframe-locomotion.fern.solutions/examples/) | Maintained | 1.3.0 | movement-controls |
| lod | A-Frame LOD implementation | [Repo](https://github.com/ChillyCider/aframe-lod) | [Example](https://mflux.github.io/aframe-lod/) | Unknown | 0.9.1| |
| log | In-VR console logs for A-Frame. | [Repo](https://github.com/supermedium/superframe/tree/master/components/log/) | [Example](https://supermedium.com/superframe/components/log/) | Unknown| Unknown| a-console |
| log-all-events | log every event emitted on an entity | [Repo](https://github.com/kylebakerio/log-all-events) | [Example](https://log-all-events.glitch.me/) | Maintained | 1.3.0 | a-console |
| look-at | Rotate an entity to face towards another entity in A-Frame | [Repo](https://github.com/supermedium/superframe/tree/master/components/look-at/) | [Example](https://supermedium.com/superframe/components/look-at/), [stemkoski](https://stemkoski.github.io/A-Frame-Examples/sprites.html) | Unknown | Unknown | |
| mapbox| A Mapbox component for A-Frame | [Repo](https://github.com/mattrei/aframe-mapbox-component) | [Example](https://mattrei.github.io/aframe-mapbox-component/) | Unknown| 1.0.4 | geothree |
| maze | generates mazes | [Repo](https://github.com/mitchallen/aframe-maze-component) | [Example](https://mitchallen.bitbucket.io/) | Unknown | 0.7.1 || 
| mesh-smooth| Apply to models that looks "blocky", to have Three.js compute vertex normals on the fly for a "smoother" look. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | |
| mesh-particles| aframe component for mesh particles | [Repo](https://github.com/harlyq/aframe-mesh-particles-component), [stemkoski](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-mesh-particles-component.js) | [Example](https://harlyq.github.io/aframe-mesh-particles-component/), [stemkoski](https://stemkoski.github.io/A-Frame-Examples/particles.html) | Unknown| 1.3.0 | |
| metronome| A simple component that fires events at specified intervals. Useful for musical looping applications. | [Repo](https://github.com/rserota/aframe-metronome-component) | No known examples. | Unknown| Unknown| |
| mirror | Reflecting mirrors for A-Frame scenes | [Repo](https://github.com/diarmidmackenzie/aframe-multi-camera) | [Example](https://diarmidmackenzie.github.io/aframe-multi-camera/examples/mirror-example.html) | Actively Maintained | 1.3.0 | [mirror](https://github.com/juunini/aframe-mirror) |
| motion-capture | A-Frame motion capture components | [Repo](https://github.com/dmarcos/aframe-motion-capture-components) | None | Unknown| Unknown| |
| mountain | Mountain terrain in A-Frame using randomly-generated height maps | [Repo](https://github.com/supermedium/superframe/tree/master/components/mountain/) | [Example](https://supermedium.com/superframe/components/mountain/) | Unknown| Unknown| atoll-terrain |
| movement-controls | Collection of locomotion controls, which can switch between input devices as they become active. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 1.3.0 | locomotion |
| music-player | a full interactive music player | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/music-player.js) | None | Unknown | 1.3.0 |  |
| nav-agent| Adds behaviors to an entity allowing it to navigate to any reachable destination along the nav mesh. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/pathfinding) | None | Unknown| 1.1.0. [Issues wit 1.2.0+](https://github.com/n5ro/aframe-extras/issues/369) | |
| nav-mesh | Assigns model from the current entity as a [navigation mesh](https://en.wikipedia.org/wiki/Navigation_mesh) for the pathfinding system. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/pathfinding) | None | Unknown| 1.1.0. [Issues wit 1.2.0+](https://github.com/n5ro/aframe-extras/issues/369) | |
| networked-aframe | A web framework for building multi-user virtual reality experiences. Components: networked-scene networked networked-audio-source networked-video-source networked-hand-controls. Supports websockets with socket.io for data only (wseasyrtc adapter), WebRTC audio, video and datachannels (easyrtc adapter), SFU with janus-gateway (janus adapter). | [Repo](https://github.com/networked-aframe/networked-aframe) | [Example](https://naf-examples.glitch.me) | Maintained| 1.3.0 | broadcast, firebase |
| normal-material | Applies a MeshNormalMaterial to the entity, such that face colors are determined by their orientation. Helpful for debugging geometry. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | |
| object-model | Loader for THREE.ObjectLoader-compatible models. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/loaders) | None | Unknown| Unknown| |
| ocean | Flat-shaded, animated ocean primitive and component.| [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/primitives) | None | Unknown| 1.1.0. [Issues with 1.2.0+](https://github.com/n5ro/aframe-extras/issues/362) | |
| orbit-controls | Orbit controls component for A-Frame. | [Repo](https://github.com/supermedium/superframe/tree/master/components/orbit-controls/) | [Example](https://supermedium.com/superframe/components/orbit-controls/) | Unknown| Unknown| |
| outline | Two-pass Outline effect component for A-Frame | [Repo](https://github.com/takahirox/aframe-outline) | [Example](https://rawgit.com/takahirox/aframe-outline/v1.1.1/index.html) | Unknown| 0.7.1 | |
| parametric-curve | Draw Parametric curves | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-parametric-curve.js) | [Example](https://stemkoski.github.io/A-Frame-Examples/curves-tubes.html), [Following Path]([Example](https://stemkoski.github.io/A-Frame-Examples/parametric-path-follow.html)) | Maintained | 1.3.0 | curve, [follow-parametric-curve](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-curve-follow.js) |
| particle-system | Particle systems for A-Frame. | [Repo](https://github.com/IdeaSpaceVR/aframe-particle-system-component) | [Example](https://ideaspacevr.github.io/aframe-particle-system-component/) | Maintained | 1.3.0 | dust |
| physics-system | Physics system for A-Frame VR, which can use either Cannon.js or Ammo.js | [Repo](https://github.com/c-frame/aframe-physics-system) | [examples](https://c-frame.github.io/aframe-physics-system/examples/) | Maintained | 1.3.0 | [original fork](https://github.com/n5r0/aframe-physics-system) |
| player-move | teleportation + smooth locomotion | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/player-move.js) | [examples](https://stemkoski.github.io/A-Frame-Examples/quest-extras.html) | Maintained | 1.3.0 | movement-controls |
| point | A Point component for A-Frame. | [Repo](https://github.com/naugtur/aframe-point-component) | [Example](http://naugtur.pl/aframe-point-component/)| Unknown| Unknown| |
| polygon-wireframe | A component to display wireframes composed of polygons, rather than triangles. | [Repo](https://github.com/diarmidmackenzie/aframe-examples/) | [Example](https://diarmidmackenzie.github.io/aframe-examples/component-usage/polygon-wireframe.html)| Unknown| Unknown| |
| portals | A component for creating portal doors | [Repo](https://github.com/ryota-mitarai/aframe-portals) | [Example](https://github.com/ryota-mitarai/aframe-portals/blob/master/examples/index.html)| Unknown| 1.2.0| |
| proxy-event| A component to declaratively proxy events for A-Frame. | [Repo](https://github.com/supermedium/superframe/tree/master/components/proxy-event/) | [Example](https://supermedium.com/superframe/components/proxy-event/) | Unknown| Unknown| |
| randomizer | Randomize color, position, rotation, and scale in A-Frame | [Repo](https://github.com/supermedium/superframe/tree/master/components/randomizer/) | [Example](https://supermedium.com/superframe/components/randomizer/) | Unknown| Unknown| |
| raycaster-extras | A prettier raycaster implementation that lights up, has nice fade, and draws a cursor on targets | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/raycaster-extras.js) | [Example](https://stemkoski.github.io/A-Frame-Examples/quest-extras.html) | Maintained | 1.3.0| |
| raycaster-thresholds | Set distance thresholds for raycasting to lines and points to different values from the (not very useful) defaults of 1m. | [Repo](https://github.com/diarmidmackenzie/aframe-examples/blob/main/components/raycaster-thresholds.jshttps://github.com/diarmidmackenzie/aframe-examples/blob/main/components/raycaster-thresholds.js) | [Example](https://diarmidmackenzie.github.io/aframe-examples/component-usage/raycaster-thresholds.html) | Maintained | 1.3.0| |
| raytrace | An A-Frame component for placing raytraced surfaces in a scene. | [Repo](https://github.com/omgitsraven/aframe-raytrace-component) | [Example](https://omgitsraven.github.io/aframe-raytrace-component/examples/basic/) | Unknown| Unknown| |
| refraction-system | THREE.CubeRefractionMapping implementation | [Repo](https://github.com/gftruj/aframe-refraction-system) | [example](https://cdn.jsdelivr.net/gh/gftruj/aframe-refraction-system@eef3e0ee/example/index.html) | Unknown | 0.8.0 | a-cubemap |
| render-order | A component that enables sorting and manually defining render order for transparent objects. | [Repo](https://github.com/supermedium/superframe/tree/master/components/render-order/) | No examples | Unknown| Unknown| |
| resonance-audio | Make spatial audio that resonates according to room dimensions. | [Repo](https://github.com/mkungla/aframe-resonance-audio-component) | [Example](https://mkungla.github.io/aframe-resonance-audio-component/) | Maintained| 1.3.0| |
| room | An A-Frame component for quickly creating rooms connected by doors. | [Repo](https://github.com/omgitsraven/aframe-room-component) | [Example](https://omgitsraven.github.io/aframe-room-component/examples/basic/) | Maintained| 1.3.0| |
| screen-display | Position an A-Frame object at a fixed position on-screen | [Repo](https://github.com/diarmidmackenzie/screen-display) | [Examples](https://github.com/diarmidmackenzie/screen-display/#usage-guidelines) | Actively Maintained | 1.3.0 | |
| screen-fade| Allows fade transitions in both desktop and VR mode | [Repo](https://github.com/mrxz/fern-aframe-components/tree/main/screen-fade) | [Example](https://aframe-components.fern.solutions/screen-fade/) | Maintained | 1.3.0 | |
| secondary-camera | Component that enables support for multiple active cameras, including in-scene CCTV-style monitors. | [Repo](https://github.com/diarmidmackenzie/aframe-multi-camera) | [Examples](https://github.com/diarmidmackenzie/aframe-multi-camera#examples) | Actively Maintained | 1.3.0 | |
| shader-buildings | Add a city's worth full of low-poly buildings, cheap! | [Repo](https://github.com/DougReeder/aframe-shader-buildings) | [Example](https://dougreeder.github.io/aframe-shader-buildings/example.html) | slow updates| 1.1.0| enviropacks, environment|
| simple-sun-sky | sky primitive using a simple (and fast) gradient away from the sun. | [Repo](https://github.com/DougReeder/aframe-simple-sun-sky) | [Example](https://dougreeder.github.io/aframe-simple-sun-sky/example.html) | slow updates | 1.1.0 | sun-sky, aframe-daylight-system, environment, a-super-sky, a-starry-sky |
| shake2show | Using shake.js to display toggle UI modal | [Repo](https://github.com/rdub80/aframe-shake2show-component) | None | Unknown| Unknown| |
| slice9 | A Slice9 ([9-slice-scaling](http://www.centigrade.de/blog/en/article/modern-user-interface-design-tools-part-2-graphical-approach-of-gui-design-tools/)) component for A-Frame. | [Repo](https://github.com/fernandojsg/aframe-slice9-component) | None | Unknown| Unknown| |
| speech-command | Speech Command component for A-Frame. | [Repo](https://github.com/lmalave/aframe-speech-command-component) | [Example](https://lmalave.github.io/aframe-speech-command-component/examples/index.html) | Unknown| Unknown| |
| spe-particles | Wrapper around the Shader Particle Engine for A-Frame | [Repo](https://github.com/harlyq/aframe-spe-particles-component) | [Example](https://harlyq.github.io/aframe-spe-particles-component/) | Unknown| 0.8| |
| sphere-collider | Detects collisions with specified objects. Required for `grab`. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/misc) | None | Unknown| 0.9+ | grab |
| spritesheet| Animated spritesheet support for A-Frame | [Repo](https://github.com/EkoLabs/aframe-spritesheet-component) | See repo. No live example | Not maintained| Unknown| atlas-uvs|
| spritesheet-animation | Animated spritesheet support for A-Frame | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-spritesheet-animation.js) | [example](https://stemkoski.github.io/A-Frame-Examples/spritesheet.html) | unknown | Unknown | atlas-uvs, spritesheet |
| sprite-particles| aframe particle system component using texture billboards | [Repo](https://github.com/harlyq/aframe-sprite-particles-component) | See repo. No live example | Not maintained| 0.9| particle-system|
| sprite-particles (stemkoski) | aframe particle system component using texture billboards | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-sprite-particles-component.js) | [example](https://stemkoski.github.io/A-Frame-Examples/particles.html) | Not maintained| 1.3.0 | particle-system |
| spe-particles (stemkoski) | aframe particle system component using texture billboards | [Repo](https://github.com/stemkoski/A-Frame-Examples/blob/master/js/aframe-sprite-particles-component.js) | [example](https://stemkoski.github.io/A-Frame-Examples/particles.html) | Not maintained| 1.3.0 | particle-system |
| state | State management for A-Frame using single global state modified through actions. State flows down to application via declarative binding. | [Repo](https://github.com/supermedium/superframe/tree/master/components/state/) | [Example](https://supermedium.com/superframe/components/state/) | Unknown| Unknown| |
| stereo | Stereoscopic component for A-Frame VR. | [Repo](https://github.com/oscarmarinmiro/aframe-stereo-component) | [Example](http://oscarmarinmiro.github.io/aframe-stereo-component/) | Appears to be maintained | Unknown| |
| stock-ticker | View stock ticker | [Repo](https://github.com/ryota-mitarai/aframe-stock-ticker) | [Example](https://github.com/ryota-mitarai/aframe-stock-ticker/tree/master/examples/crypto-chart) | unknown | 1.2.0| |
| sun-sky | Gradient sky with adjustable sun in A-Frame| [Repo](https://github.com/supermedium/superframe/tree/master/components/sun-sky/) | [Example](https://supermedium.com/superframe/components/sun-sky/) | Unknown| Unknown| a-super-sky, aframe-simple-sun-sky |
| super-hands | All-in-one natural hand controller interaction component for A-Frame. | [Repo](https://github.com/wmurphyrd/aframe-super-hands-component) | [Example](https://wmurphyrd.github.io/aframe-super-hands-component/examples/) | Somewhat maintained | 1.3.0 | |
| super-keyboard | Customizable keyboard and text entry for in-vr | [Kyle's fork](https://github.com/supermedium/aframe-super-keyboard) | [Example](https://supermedium.com/aframe-super-keyboard) | Kyle's fork is maintained, [Original Repo](https://github.com/supermedium/aframe-super-keyboard) not so much. | 1.3.0 | |
| super-sky| Fancy, lightweight, drop-in day-night sky component for A-Frame. | [Repo](https://github.com/kylebakerio/a-super-sky)| [Example](https://a-super-sky-demo.glitch.me/) | Maintained | 1.2.0 | sun-sky |
| surface-scatter| Position objects randomly over an objects surface | [Repo](https://github.com/AdaRoseCannon/aframe-surface-scatter/)| [Example](https://ada.is/aframe-surface-scatter/) | Maintained | 1.3.0 | |
| starry-sky| A Realistic Starry Skybox for A-Frame | [Repo](https://github.com/Dante83/A-Starry-Sky)| [Example](https://code-panda.com/pages/projects/v_1_0_0/a_starry_sky_christmas_star_example) | Maintained | 1.3.0 | a-super-sky, aframe-simple-sun-sky |
| teleport-controls | A-Frame teleport controls component | [Repo](https://github.com/fernandojsg/aframe-teleport-controls) | [Example](https://fernandojsg.com/aframe-teleport-controls/) | Unknown| Unknown| blink-controls |
| template | Encapsulate groups of entities, use templating engines, and do string interpolations in A-Frame | [Repo](https://github.com/supermedium/superframe/tree/master/components/template/) | [Example](https://supermedium.com/superframe/components/template/) | Unknown| Unknown| |
| text-geometry | Geometry-based text for A-Frame | [Repo](https://github.com/supermedium/superframe/tree/master/components/text-geometry/) | [Example](https://supermedium.com/superframe/components/text-geometry/) | Unknown| Unknown| |
| thumb-controls | An A-Frame component that provides and normalizes directional events for thumbpads and thumbsticks. | [Repo](https://github.com/supermedium/superframe/tree/master/components/thumb-controls/) | [Example](https://supermedium.com/superframe/components/thumb-controls/) | Unknown| Unknown| |
| tooltip | A-Frame tooltip component | [Repo](https://github.com/fernandojsg/aframe-tooltip-component) | [Example](https://fernandojsg.com/aframe-tooltip-component/) | Unknown| 0.5 | |
| touch-controls | Touch screen (or Cardboard button) to move forward. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 0.9+ | movement-controls |
| trackpad-controls | Trackpad-based movement. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/controls) | None | Unknown| 0.9+ | movement-controls |
| trail | Simple geometrical trail component | [Repo](https://github.com/EricEisaman/aframe-trail-component) | See repo. No live example | Unknown | 1.3.0 | |
| troika-text | An A-Frame component for rendering 3D text using troika-three-text that reads font files directly (ttf, otf, woff) | [Repo](https://github.com/lojjic/aframe-troika-text) | None | Maintained| 1.3.0 | a-text |
| tube | Tube following a custom path, primitive and component. | [Repo](https://github.com/n5ro/aframe-extras/tree/master/src/primitives) | None | Unknown| Unknown| |
| ui-widgets | UI Widgets for A-Frame. | [Repo](https://github.com/caseyyee/aframe-ui-widgets) | [Example](https://caseyyee.github.io/aframe-ui-widgets/examples/) | Unknown| Unknown| |
| videoplayer | A video player made with A-Frame | [Repo](https://github.com/etiennepinchon/aframe-videoplayer) | [Example](https://etiennepinchon.github.io/aframe-videoplayer/) | Unmaintained | 0.5.0 | [youtube-player](https://github.com/akbartus/Youtube-WebVR-Experiments) |
| vimeo | Stream Vimeo videos into WebVR. | [Repo](https://github.com/vimeo/aframe-vimeo-component) | None | Unmaintained | 0.8.0 | |
| viewpoint-renderer | On-screen rotating cube to use to pick a viewpoint on a 3D scene | [Repo](https://github.com/diarmidmackenzie/aframe-multi-camera#viewpoint-selector) | [Example](https://diarmidmackenzie.github.io/aframe-multi-camera/examples/viewpoint-selector-basic.html) | Actively maintained | 1.3.0 | |
| vr-super-stats | Rendering performance stats, visible while in VR | [Repo](https://github.com/kylebakerio/vr-super-stats) | https://vr-super-stats.glitch.me/| Unknown| 1.3.0 | fps-counter|
| water | High quality (but GPU intensive) ocean water component. | [Repo](https://github.com/Dante83/a-water) | [Example](https://code-panda.com/pages/projects/a_ocean/v_0_1_0) | Maintained| 1.3.0| ocean |
| water | gpu-cheap water, cell-shaded effect | [Repo](https://github.com/kylebakerio/ada-water) | [Example](https://ada-water.glitch.me/) | Maintained | 1.3.0 | water, ocean |
| web2vr | GUI and display lib, use html & css | [Repo](https://github.com/kikoano/web2vr) | [Example](https://glitch.com/edit/#!/web2vr-demo?path=index.html%3A5%3A47) | Unknown| 1.3.0| html-mesh, websurfaces |
| web-portals | create portals to other websites | [Repo](https://github.com/ryota-mitarai/aframe-web-portals) | [Example](https://codesandbox.io/s/aframe-web-portals-example-27guc) | Unknown| 1.2.0 | portals |
| websurfaces | interactive canvas rendering of html within VR | [Repo](https://github.com/ryota-mitarai/aframe-websurfaces) | [Example](https://codesandbox.io/s/aframe-websurfaces-example-l44vc?file=/index.html) | Unknown | 1.2.0 | html-mesh, web2vr |

## Components Not Included in List

There are a few components included in the collections referenced above that I haven't included. Here's a list of components that I looked at but didn't include, together with the reasons why.

| Component | List | Reason for non-inclusion |
| ---------------------------------------- | ---------------- | ------------------------------------------------------------ |
| animation | A-Frame Registry | Superseded by A-Frame built-in animation component|
| auto-detect-controllers | A-Frame Registry | Superseded by A-Frame built-in tracked-controls component |
| controller-cursor | A-Frame Registry | Superseded by A-Frame built-in cursor component |
| json-model | A-Frame Registry | Claims to be part of aframe-extras, but I can't see it in there. |
| gear-vr-controls | A-Frame Registry | Superseded by A-Frame built-in gearvr-controls component |
| lerp | A-Frame Registry | Superseded by A-Frame built-in animation component|
| line | A-Frame Registry | GitHub repo no longer exists. |
| rain | A-Frame Registry | Unmaintained, and doesn't seem to add anything over what's available in aframe-particle-system (which is maintained) |
| stats-in-vr | A-Frame Registry | Superseded by [vr-super-stats](https://github.com/kylebakerio/vr-super-stats) |
| collada-model-legacy | A-Frame Extras | Removed from A-Frame in 0.09.0 - Collada models no longer recommended. |
| gltf-model-legacy | A-Frame Extras | GLTF 1.0 support. Recommended to use GLTF 2.0 wherever possible. |
| kinematic-body| A-Frame Extras | Deprecated |
| cube-env-map| A-Frame Extras | Cubemaps are now supported natively in A-Frame via the a-cubemap element. |