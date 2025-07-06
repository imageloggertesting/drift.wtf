```
local drift = {
    SilentAim = {
        Enabled = true,
        AntiCurve = true,
        HitPartMode = "ClosestPoint",
        HitPart = "Head",
        HealthCheck = true,
        KnifeCheck = true,
        WallCheck = true,
        HitChance = {
            X = 100,
            Y = 100,
            Z = 100
        },
        Prediction = {
            Enabled = false,
            X = 0.24434,
            Y = 0.24434,
            Z = 0.24434
        },
        FOV = {
            Enabled = false,
            Radius = 500,
            OutlineColor = Color3.fromRGB(0, 0, 0),
            Rainbow = {
                Enabled = false,
                Speed = 1
            },
            Thickness = 1,
            Transparency = 1
        }
    },
    Camlock = {
        Enabled = true,
        ToggleKey = Enum.KeyCode.E,
        Smoothing = {
            Enabled = true,
            X = 1.5,
            Y = 2,
            Z = 1.6
        },
        HitPartMode = "ClosestPart",
        HitPart = "Head",
        HealthCheck = true,
        KnifeCheck = true,
        WallCheck = false,
        Prediction = {
            Enabled = false,
            X = 0.24434,
            Y = 0.24434,
            Z = 0.24434
        }
    },
    TriggerBot = {
        Enabled = false,
        ToggleKey = Enum.KeyCode.Q,
        Delay = 0.1,
        Prediction = {
            Enabled = false,
            X = 0.1,
            Y = 0.1,
            Z = 0.1
        },
        WallCheck = true,
        HealthCheck = true,
        KnifeCheck = true,
        HitPartMode = "ClosestPart",
        HitPart = "Head",
        FOV = {
            Enabled = true,
            Radius = 50,
            OutlineColor = Color3.fromRGB(255, 0, 0)
        }
    },
    WalkSpeed = {
        Enabled = true,
        ToggleKey = Enum.KeyCode.P,
        FastSpeed = 375,
        SlowSpeed = 40
    },
    JumpPower = {
        Enabled = false,
        ToggleKey = Enum.KeyCode.V,
        FastPower = 145,
        SlowPower = 50
    },
    Zoom = {
        Enabled = true,
        ToggleKey = Enum.KeyCode.Z
    },
    SpreadMod = {
        BulletSpread = {
            Enabled = true,
            Amount = 70
        }
    },
    Indicators = {
        Enabled = false
    },
    MaxDistance = 10000
}
```
