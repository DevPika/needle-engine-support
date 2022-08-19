# Features Overview

Needle Engine provides

## Fast Iteration

## Shader Graph

## Crossplatform: VR, AR, Mobile, Desktop
Needle Engine runs everywhere web technology does - and is built with VR and AR in mind.

## Lightmaps

![20220819-152731_Needle_Website_-_Google_Chrome-needle](https://user-images.githubusercontent.com/5083203/185631598-cd8b930b-bcc8-49c0-884b-11d091fd7185.png)

Needle Engine utilizes the [Unity Editor Lightmapper ⇡](https://docs.unity3d.com/Manual/progressive-lightmapper.html) to easily bake static light for your 3d content.

> **Note**: There is no technical limitation on which lightmapper to use so you could also use a third party lightmapper like [Bakery ⇡](https://assetstore.unity.com/packages/tools/level-design/bakery-gpu-lightmapper-122218) for the job.

## Multiplayer and Networking
Networking is built into the core runtime. Needle Engine deployments to Glitch come with a tiny server that allows you to deploy a multiplayer 3d environment in seconds. Needle Engine comes with some networked components that make it easy to get started. Synchronizing variables and state is super easy!

## Animation
Needle Engine animations are super powerful. From just playing a single animation to orchestrating and blending multiple complex and dynamic animations - we got you covered. 
### AnimatorController
The powerful AnimationController in Unity lets you setup animations and define conditions for when and how to blend between them.
### Timeline
![timeline-needle](https://user-images.githubusercontent.com/5083203/185631460-e53ebfd7-047e-4e47-9519-1a4006e60266.png)

Needle Engine has core support for all of Unity's Timeline tracks to build complex dynamic animations and audio-visual experiences.  
The supported tracks include: AnimationTracks, AudioTracks, ActivationTracks, ControlTracks, SignalTracks. 

> **Note**: Sub-Timelines are currently not supported
> **Note**: Yes it is even possible to export your custom timeline tracks!

## Physics