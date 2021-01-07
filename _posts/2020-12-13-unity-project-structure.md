---
title: Approach to Unity Folder Structure
date: "2020-12-20T22:12:05.284Z"
description: "How I like to keep my projects tidy."
---

Below is an example of my project structure inside Assets (where I keep everything).
It was generated using tree on my Argon Assault project. I find this keeps my project easy to navigate through.

```
├───Assets
│   ├───Asset Packs
│   │   ├───Autarca
│   │   │   └───AlienShipsPack
│   │   │       ├───Materials
│   │   │       ├───Meshes
│   │   │       ├───Prefabs
│   │   │       └───Textures
│   │   ├───Particles
│   │   ├───Rock Textures
│   │   ├───Samples
│   │   │   └───Terrain Tools
│   │   │       └───0.1.0-preview
│   │   │           └───Terrain Assets
│   │   │               ├───BrushTextures
│   │   │               ├───TerrainBrushes
│   │   │               ├───TerrainLayers
│   │   │               └───TerrainTextures
│   │   ├───SampleScenes
│   │   │   ├───AudioMixers
│   │   │   ├───Materials
│   │   │   ├───Menu
│   │   │   │   ├───Prefabs
│   │   │   │   ├───Scripts
│   │   │   │   └───Sprites
│   │   │   ├───Models
│   │   │   │   └───Materials
│   │   │   ├───Navmesh
│   │   │   ├───Prefabs
│   │   │   ├───Scenes
│   │   │   │   └───CharacterThirdPersonAI
│   │   │   ├───Scripts
│   │   │   ├───Shaders
│   │   │   └───Textures
│   │   ├───SkyBox Volume 2
│   │   │   ├───DeepSpaceBlue
│   │   │   ├───DeepSpaceBlueWithPlanet
│   │   │   ├───DeepSpaceGreen
│   │   │   ├───DeepSpaceGreenWithPlanet
│   │   │   ├───DeepSpaceRed
│   │   │   ├───DeepsSpaceRedWithPlanet
│   │   │   └───Stars01
│   │   ├───Standard Assets
│   │   │   ├───2D
│   │   │   │   ├───Animations
│   │   │   │   ├───Animator
│   │   │   │   ├───Materials
│   │   │   │   ├───PhysicsMaterials
│   │   │   │   ├───Prefabs
│   │   │   │   ├───Scripts
│   │   │   │   └───Sprites
│   │   │   ├───Cameras
│   │   │   │   ├───Prefabs
│   │   │   │   └───Scripts
│   │   │   ├───Characters
│   │   │   │   ├───FirstPersonCharacter
│   │   │   │   │   ├───Audio
│   │   │   │   │   ├───Prefabs
│   │   │   │   │   └───Scripts
│   │   │   │   ├───RollerBall
│   │   │   │   │   ├───Materials
│   │   │   │   │   ├───Models
│   │   │   │   │   ├───Prefabs
│   │   │   │   │   ├───Scripts
│   │   │   │   │   └───Textures
│   │   │   │   └───ThirdPersonCharacter
│   │   │   │       ├───Animation
│   │   │   │       ├───Animator
│   │   │   │       ├───Materials
│   │   │   │       ├───Models
│   │   │   │       ├───Prefabs
│   │   │   │       ├───Scripts
│   │   │   │       └───Textures
│   │   │   ├───CrossPlatformInput
│   │   │   │   ├───Prefabs
│   │   │   │   ├───Scripts
│   │   │   │   │   └───PlatformSpecific
│   │   │   │   └───Sprites
│   │   │   ├───Editor
│   │   │   │   ├───CrossPlatformInput
│   │   │   │   └───Water
│   │   │   │       └───Water4
│   │   │   ├───Effects
│   │   │   │   ├───GlassRefraction
│   │   │   │   │   ├───Materials
│   │   │   │   │   ├───Shaders
│   │   │   │   │   └───Textures
│   │   │   │   ├───ImageEffects
│   │   │   │   ├───LightCookies
│   │   │   │   │   └───Textures
│   │   │   │   ├───LightFlares
│   │   │   │   │   ├───Flares
│   │   │   │   │   ├───Materials
│   │   │   │   │   └───Textures
│   │   │   │   ├───Projectors
│   │   │   │   │   ├───Materials
│   │   │   │   │   ├───Prefabs
│   │   │   │   │   ├───Shaders
│   │   │   │   │   └───Textures
│   │   │   │   ├───TessellationShaders
│   │   │   │   │   ├───Materials
│   │   │   │   │   ├───Models
│   │   │   │   │   ├───Scenes
│   │   │   │   │   ├───Shaders
│   │   │   │   │   └───Textures
│   │   │   │   └───ToonShading
│   │   │   │       ├───Materials
│   │   │   │       ├───Shaders
│   │   │   │       └───Textures
│   │   │   ├───Environment
│   │   │   │   ├───SpeedTree
│   │   │   │   │   ├───Broadleaf
│   │   │   │   │   │   ├───Broadleaf_Desktop Materials
│   │   │   │   │   │   │   ├───LOD0
│   │   │   │   │   │   │   ├───LOD1
│   │   │   │   │   │   │   └───LOD2
│   │   │   │   │   │   └───Broadleaf_Mobile Materials
│   │   │   │   │   │       ├───LOD0
│   │   │   │   │   │       ├───LOD1
│   │   │   │   │   │       └───LOD2
│   │   │   │   │   ├───Conifer
│   │   │   │   │   │   └───Conifer_Desktop Materials
│   │   │   │   │   │       ├───LOD0
│   │   │   │   │   │       ├───LOD1
│   │   │   │   │   │       └───LOD2
│   │   │   │   │   └───Palm
│   │   │   │   │       └───Palm_Desktop Materials
│   │   │   │   │           ├───LOD0
│   │   │   │   │           ├───LOD1
│   │   │   │   │           └───LOD2
│   │   │   │   ├───TerrainAssets
│   │   │   │   │   ├───BillboardTextures
│   │   │   │   │   └───SurfaceTextures
│   │   │   │   ├───Water
│   │   │   │   │   ├───Water
│   │   │   │   │   │   ├───Materials
│   │   │   │   │   │   ├───Models
│   │   │   │   │   │   ├───Prefabs
│   │   │   │   │   │   ├───Scripts
│   │   │   │   │   │   ├───Shaders
│   │   │   │   │   │   └───Textures
│   │   │   │   │   └───Water4
│   │   │   │   │       ├───Materials
│   │   │   │   │       ├───Models
│   │   │   │   │       ├───Prefabs
│   │   │   │   │       ├───Shaders
│   │   │   │   │       └───Textures
│   │   │   │   └───Water (Basic)
│   │   │   │       ├───Materials
│   │   │   │       ├───Models
│   │   │   │       ├───Prefabs
│   │   │   │       ├───Scripts
│   │   │   │       ├───Shaders
│   │   │   │       └───Textures
│   │   │   ├───Fonts
│   │   │   │   └───OpenSans
│   │   │   ├───ParticleSystems
│   │   │   │   ├───Materials
│   │   │   │   ├───Prefabs
│   │   │   │   ├───Scripts
│   │   │   │   ├───Shaders
│   │   │   │   └───Textures
│   │   │   ├───PhysicsMaterials
│   │   │   ├───Prototyping
│   │   │   │   ├───Materials
│   │   │   │   ├───Models
│   │   │   │   ├───Prefabs
│   │   │   │   ├───Shaders
│   │   │   │   └───Textures
│   │   │   ├───Utility
│   │   │   │   └───Prefabs
│   │   │   └───Vehicles
│   │   │       ├───Aircraft
│   │   │       │   ├───Animation
│   │   │       │   ├───Audio
│   │   │       │   ├───Materials
│   │   │       │   ├───Models
│   │   │       │   ├───Prefabs
│   │   │       │   ├───Scripts
│   │   │       │   └───Textures
│   │   │       └───Car
│   │   │           ├───Audio
│   │   │           ├───Materials
│   │   │           ├───Models
│   │   │           ├───Prefabs
│   │   │           ├───Scripts
│   │   │           ├───Shaders
│   │   │           └───Textures
│   │   └───StarSparrow
│   │       ├───Materials
│   │       ├───Meshes
│   │       ├───Prefabs
│   │       │   └───Examples
│   │       └───Textures
│   │           └───2K_Textures
│   ├───Audio
│   ├───Environment
│   ├───Materials
│   ├───Prefabs
│   ├───Scenes
│   │   └───Level 1
│   └───Scripts
├───Library
│   ├───APIUpdater
│   ├───Artifacts
│   ├───PackageCache
│   │   ├───com.unity.collab-proxy@1.2.16
│   │   │   ├───Documentation~
│   │   │   ├───Editor
│   │   │   │   ├───Collab
│   │   │   │   │   ├───Presenters
│   │   │   │   │   └───Views
│   │   │   │   └───Resources
│   │   │   │       └───Styles
│   │   │   └───Tests
│   │   │       └───Editor
│   │   ├───com.unity.ext.nunit@1.0.5
│   │   │   ├───Documentation~
│   │   │   └───net35
│   │   │       └───unity-custom
│   │   ├───com.unity.ide.rider@1.1.4
│   │   │   ├───Documentation~
│   │   │   └───Rider
│   │   │       └───Editor
│   │   │           ├───PostProcessors
│   │   │           ├───ProjectGeneration
│   │   │           ├───UnitTesting
│   │   │           └───Util
│   │   ├───com.unity.ide.vscode@1.2.3
│   │   │   ├───Documentation~
│   │   │   └───Editor
│   │   │       └───ProjectGeneration
│   │   ├───com.unity.test-framework@1.1.19
│   │   │   ├───Documentation~
│   │   │   │   └───images
│   │   │   ├───UnityEditor.TestRunner
│   │   │   │   ├───Api
│   │   │   │   ├───CommandLineParser
│   │   │   │   ├───CommandLineTest
│   │   │   │   ├───GUI
│   │   │   │   │   ├───TestListBuilder
│   │   │   │   │   ├───TestListTreeView
│   │   │   │   │   └───Views
│   │   │   │   ├───NUnitExtension
│   │   │   │   │   └───Attributes
│   │   │   │   ├───TestLaunchers
│   │   │   │   │   └───PlatformSetup
│   │   │   │   ├───TestRun
│   │   │   │   │   └───Tasks
│   │   │   │   ├───TestRunner
│   │   │   │   │   ├───Callbacks
│   │   │   │   │   ├───Messages
│   │   │   │   │   └───Utils
│   │   │   │   ├───TestSettings
│   │   │   │   └───UnityTestProtocol
│   │   │   └───UnityEngine.TestRunner
│   │   │       ├───Assertions
│   │   │       │   └───LogScope
│   │   │       ├───NUnitExtensions
│   │   │       │   ├───Attributes
│   │   │       │   ├───Commands
│   │   │       │   ├───Filters
│   │   │       │   └───Runner
│   │   │       ├───TestRunner
│   │   │       │   ├───Callbacks
│   │   │       │   ├───Messages
│   │   │       │   └───RemoteHelpers
│   │   │       └───Utils
│   │   │           ├───AssemblyProvider
│   │   │           └───MonoBehaviourTest
│   │   ├───com.unity.textmeshpro@2.1.1
│   │   │   ├───Documentation~
│   │   │   ├───Editor Resources
│   │   │   │   ├───Gizmos
│   │   │   │   ├───Shaders
│   │   │   │   └───Textures
│   │   │   ├───Package Resources
│   │   │   ├───Scripts
│   │   │   │   ├───Editor
│   │   │   │   └───Runtime
│   │   │   └───Tests
│   │   │       ├───Editor
│   │   │       └───Runtime
│   │   └───com.unity.timeline@1.2.17
│   │       ├───Documentation~
│   │       │   └───images
│   │       ├───Editor
│   │       │   ├───Actions
│   │       │   │   └───Menus
│   │       │   ├───Activation
│   │       │   ├───Analytics
│   │       │   ├───Animation
│   │       │   ├───Attributes
│   │       │   ├───Audio
│   │       │   ├───ControlTrack
│   │       │   ├───CustomEditors
│   │       │   ├───Extensions
│   │       │   ├───inspectors
│   │       │   │   ├───ClipInspector
│   │       │   │   └───CurvesOwner
│   │       │   ├───Items
│   │       │   ├───Manipulators
│   │       │   │   ├───AddDelete
│   │       │   │   ├───Cursors
│   │       │   │   ├───Move
│   │       │   │   ├───Sequence
│   │       │   │   ├───Trim
│   │       │   │   └───Utils
│   │       │   ├───Playables
│   │       │   ├───Properties
│   │       │   ├───Recording
│   │       │   ├───Signals
│   │       │   │   └───TreeView
│   │       │   ├───State
│   │       │   ├───StyleSheets
│   │       │   │   ├───Extensions
│   │       │   │   ├───Images
│   │       │   │   │   ├───DarkSkin
│   │       │   │   │   ├───Icons
│   │       │   │   │   ├───LightSkin
│   │       │   │   │   └───Shared
│   │       │   │   └───res
│   │       │   ├───treeview
│   │       │   │   ├───Drawers
│   │       │   │   │   └───Layers
│   │       │   │   ├───ItemGui
│   │       │   │   └───Snapping
│   │       │   ├───Utilities
│   │       │   └───Window
│   │       │       ├───Modes
│   │       │       └───ViewModel
│   │       └───Runtime
│   │           ├───Activation
│   │           ├───Animation
│   │           ├───AssetUpgrade
│   │           ├───Attributes
│   │           ├───Audio
│   │           ├───Control
│   │           ├───Evaluation
│   │           ├───Events
│   │           │   └───Signals
│   │           ├───Extensions
│   │           ├───Playables
│   │           ├───Properties
│   │           ├───Scripting
│   │           └───Utilities
│   ├───ScriptAssemblies
│   ├───ShaderCache
│   │   ├───0
│   │   ├───1
│   │   ├───2
│   │   ├───3
│   │   ├───4
│   │   ├───5
│   │   ├───6
│   │   ├───7
│   │   ├───8
│   │   ├───9
│   │   ├───a
│   │   ├───b
│   │   ├───c
│   │   ├───d
│   │   ├───e
│   │   └───f
│   ├───StateCache
│   │   ├───Hierarchy
│   │   ├───LayerSettings
│   │   └───SceneView
│   ├───TempArtifacts
│   │   ├───Extra
│   │   └───Primary
│   ├───TerrainTools
│   └───Timeline
├───Logs
├───obj
│   └───Debug
│       └───TempPE
├───Packages
└───ProjectSettings

```
