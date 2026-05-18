### Server https://discord.gg/g4bJDKUanD
# Allow List

### Roblox has introduced a [Fast Flag Allowlist](https://devforum.roblox.com/t/allowlist-for-local-client-configuration-via-fast-flags/3966569) to enhance platform security and stability. This system limits the number of locally configurable Fast Flags to those explicitly listed, preventing misuse and ensuring a more stable experience for all users. The allowlist is subject to change based on platform needs and community feedback. To use Fast Flags that are not in the allowlist, you must use a Fast Flag injector.

# Injectors

##### **VELOSTRAP AHK:** Requires Auto Hotkey v2 | Open Source | Might be Sketchy **use at your own risk** | Download this Injector in The Velostrap Discord server at https://discord.gg/QJhNQ3gDM





##### **DAVESTRAP OLD:** Original Injector that's well known and trusted | New Dumper Was Added So it Works Flawlessly After The Patch | Download at https://github.com/davelovestars/oldinjector-version-working/blob/main/fastflag\_injector\_gui\_enhanced.exe





##### **DAVESTRAP NEW:** New and improved Injector | advanced | Uses all the new features and also works Flawlessly | Download at               https://github.com/davelovestars/fflag-injector-new-version/releases





##### **(4anti) FASTFLAG MANAGER:** Clean and rich ui | a bit more advanced and complicated | Buggy | Good features and customization | Download at  https://github.com/4anti/Roblox-Fastflag-Manager/releases/tag/v3.3.5

# Rendering

### Vulkcan

```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferVulkan": "True"
}
```

### DirectX10

```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "True"
}
```

### DirectX11

```json
{
    "FFlagDebugGraphicsPreferD3D11": "True"
}
```

### OpenGL

```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferOpenGL": "True"
}
```

### Metal (MacOS Only)

```json
{
    "FFlagDebugGraphicsPreferMetal": "True"
}
```

# Lighting

### Voxel Lighting (Phase 1)
>recommended for fps
```json
{
    "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```

### Shadowmap Lighting (Phase 2)

```json
{
    "FFlagDebugForceFutureIsBrightPhase2": "True"
}
```

### Future Lighting (Phase 3)

```json
{
    "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```
### Unified Lighting

```json
{
    "FFlagRnderUnifiedLighting12": "True",
    "FFlagUnifedLightingBetaFeature": "True"
}
```

### Unified Lighting Blendzone

```json
{
    "FIntUnifiedLightingBlendZone": "500"
}
```

# Graphics

### Resolution
>144p = 37 | 
>240p = 77 | 
>360p = 230 | 
>480p = 410 | 
>720p = 922 | 
>1080p = 2074 | 
>1440p = 3686 | 
>2160p (4k) = 8294 | 
>4320p (8k) = 33178
```json
{
    "DFIntDebugDynamicRenderKiloPixels": "1"
}
```

### Disable PostFX
>the name ofc
```json
{
    "FFlagDisablePostFx": "True"
}
```

### Shiny Surfaces (semi-shaders)
>Makes things shiny | got some good knife inspects with this
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverridge": "6"
}
```

### Textures
>1-5 is blurry | 6+ removes textures

```json
{
    "FIntDebugTextureManagerSkipMips": "1"
}
```

### Force MSAA
>ONLY values 1, 2, 4, 8 | Higher = Cleaner, less pixelated lines

```json
{
    "FIntDebugForcMSAASamples": "4"
}
```

### Force Graphics Quality Level
>Turn ingame slider up for high render distance and level 1 graphics

```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### Pause Voxelizers
>Can make games dark but +fps

```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### Grey Sky
>Only in games with default skybox

```json
{
    "FFlagDebugSkyGray": "True"
}
```

### GpuLightCulling
>idek

```json
{
    "FFlagDebugForceFSMCPULightCulling": "True"
}
```

### Terrain Texture Quality
>4 less quality | 16 32 64 for higher quality

```json
{
    "FIntTerrainArraySliceSize": "4"
}
```

### No Avatar Textures

```json
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```

### Remove Grass

```json
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
}
```

### Render Distance From Camera
> Distance from camera not charactor/person

```json
{
  "FIntCameraFarZPlane": "100"
}
```

# Quality Of Life

### Disable Notifications
>Basically Do Not Disturb

```json
{
    "FFlagToastNotificationsProtocolEnabled2": "False"
}
```

### Disable VC
>Pretty useless ig

```json
{
    "DFFlagVoiceChat4": "False"
}
```

### Hide GUI
>Replace "ID" with any group ID that you are in | Ctrl + Shift + B	Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc) | Ctrl + Shift + C	Toggles game-defined ScreenGuis | Ctrl + Shift + G	Toggles Roblox CoreGuis | Ctrl + Shift + N	Toggles player names, and other BillboardGuis that show up above a player

```json
{
    "DFIntCanHideGuiGroupId": "ID"
}
```

### Webview
>Click the Beta Badge of the 13+ badge to open the webview browser.

```json
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://udm14.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://udm14.com/"
}
```

###
