Effects
=======

**GUID** *32-digit hexadecimal*: Refer to [GUID](GUID.md) documentation.

**Type** *enum* (`Effect`)

**ID** *uint16*: Must be a unique identifier.

General data
------------

**Blast** *uint16*: ID of effect.

**Lifetime** *float*: Duration of the effect.

**Lifetime_Spread** *float*: Variation on the duration of the effect, measured in seconds. A random value is chosen between the specified spread value, and the negative of that spread value. Default value is 4 seconds.

**Gore** *bool*: Effect is hidden when gore is disabled.

**Static** *bool*: Disable randomized audio pitch change.

**Randomize_Rotation** *bool*: Rolls the effect around the hit axis. Defaults to true.

**Spawn_On_Dedicated_Server** *bool*: Spawn effect on server.

**Relevant_Distance** *float*: How far away players can be before an asset effect should not be sent to them, measured in meters. Players within this radius will be sent the effect in multiplayer.

**Preload** *bool*: Total number of the effect to pre-instantiate in the effect pool to reduce hitching when first used.

Splatters
---------

**Splatter** *int*: Total number of splatter textures in Unity.

**Splatters** *int*: Total number of splatters to spawn.

**Splatter_Lifetime** *float*: Duration of the splatter.

**Splatter_Lifetime_Spread** *float*: Variation on the duration of each individual splatter after effect spawn. A random value is chosen between the specified spread value, and the negative of that spread value. Default is 1 second.

**Splatter_Liquid** *bool*: Splatters are visible regardless of effect graphics settings being disabled, and slightly changes the direction of each splatter.

**Splatter_Temperature** *enum* (`Acid`, `Burning`, `Warm`): Temperature status effect caused when standing in the effect.

**Splatter_Preload** *bool*: Total number of the splatter effects to pre-instantiate in the effect pool to reduce hitching when first used.
