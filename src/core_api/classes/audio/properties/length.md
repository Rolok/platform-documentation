# length

###### [Classes](/core_api/raw_source) > [Audio](/core_api/classes/audio/AudioOverview)

### Description

Returns the length (in seconds) of the [Audio](/core_api/classes/audio/AudioOverview).

### Notes
!!! info
    This audio property is a read-only float.

### Syntax

`.length`

### Example

```lua
-- audioExample.lua --
-- drag the audio "Ambience Suburbs Night Crickets 01 SFX" into the hierarchy --

local cricketsSFX = game:FindObjectByName("Ambience Suburbs Night Crickets 01 SFX")
cricketsSFX:Play()
print("This sound effect will play for " .. tostring(cricketsSFX.length) .. " seconds.")
-- will print 10000.0 seconds in the Event Log window --

```

### See Also

* [Classes.Audio](/core_api/classes/audio/AudioOverview)