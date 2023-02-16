getgenv().Shhhh = {
  Options = {
      Key = "keyhere", -- // replace with ur key ofc
      Version = "Latest", -- // "Latest" for latest version
      Intro = false, -- // starts a small intro
  },
  Panic = {
      Enabled = false,
      Key = "K", -- // turns everything OFF/ON
  },
  Universal = {
    Enabled = false, -- // turn this off if you're gonna play DA HOOD
    TeamCheck = true, -- // turn this off if the game is free for all
    VisibleCheck = true,
    Use_HitChance = true,
    Visible = true, --  // Visible / Show Fov
    Predict = false,
    Prediction = 0.115,
    Size = 150, -- // Fov Size
    HitChance = 100,
    HitPart = "Random", -- // Head, HumanoidRootPart, Random
  },
  Silent = {
      Enabled = true,
      Mode = "FOV", -- // FOV or Target
      Enable_KeyBind = true,
      KeyBind = "p",
      Notification = true,
      Predict = true,
      Prediction = 0.135,
      HitChance = 300,
      AirShot_HitChance = 300,
      HitParts = 'HumanoidRootPart',
      NearestCursorHitpart = true,
      HitPart_Mode = "Nearest Point", -- "Nearest Part", "Nearest Point"
  },
  AimAssist = {
      Enabled = true,
      Hold_KeyBind = false,
      KeyBind = 'Q',
      ThirdPerson = true,
      FirstPerson = true,
      Predict = true,
      Prediction = 0.115,
      Smooth = true,
      SmoothValue = 0.014,
      AirShot_SmoothValue = 0.050,
      HitPart = "HumanoidRootPart",
      Use_AirShotHitPart = false,
      AirShotHitPart = "Head",
      NearestCursorHitpart = true,
  },
  Shake = {
      Enabled = true,
      X = 5,
      Y = 5,
      Z = 5,
  },
  Fov = {
      Silent = {
          Visible = true, -- circle visible
          Filled = true,
          Size = 35,
          Transparency = 0.14,
          Thickness = 1,
          Shape = 'Circle',
          Set = {0, 0},
          Color = Color3.fromRGB(0, 0, 0),
      },
      AimAssist = {
          Visible = true, -- circle visible
          Use_Fov = false,
          Disable_Outside_Fov = false,
          Filled = false,
          Size = 50,
          Transparency = 1,
          Thickness = 1,
          Shape = 'Circle',
          Set = {0, 0},
          Color = Color3.fromRGB(0, 0, 0),
      },
  },
  Checks = {
      Wall = true,
      Knocked = true,
      Grabbed = true,
      Airshot = true,
      Crew_Check = false,
      NoGroundShots = true,
  },
  Resolver = {
      Enabled = true,
      Anti_Aim_Viwer = true,
  },
  TriggerBot = {
      Enabled = false,
      Delay = 0.1,
  },
  Animation = { -- once u click the keybinds it makes u use the Animation
      Lay = true, LayKey = Enum.KeyCode.T,
      Greet = true, GreetKey = Enum.KeyCode.G,
      Speed = false, SpeedKey = Enum.KeyCode.N,
      Sturdy = false, SturdyKey = Enum.KeyCode.H,
      Griddy = false, GriddyKey = Enum.KeyCode.G,
  },
  Mod = {
      Enabled = false,
      Mode = "Key",
      Key = "L", -- // crashes u when u click the button
      Message = "lol...",
      Kick_if_Mod_Joined = true,
  },
  Macro = {
      Enabled = true,
      Hold_Key = false,
      KeyBind = Enum.KeyCode.X,
      AntiMacroFling = true, -- // not here yet
      BypassMacroAbuse = true,
      Mode = 'First Person', -- // use "Normal" or "First Person"
  },
  Memory = {
      Enable = false,
      Start = 971,
      End = 984,
      Speed = 1,
  },
  GunFov = {
      Enable = false,
      DoubleBarrel = 10,
      Revolver = 44,
      Rifle = 20,
      Shotgun = 20,
      Smg = 23,
      TacticalShotgun = 24,
      Silencer = 17,
      AK47 = 8,
      AR = 15,
  },
  AutoPrediction = { -- the numbers are pings ( this is for silent + Current sets not recommended )
      Enabled = false,
      p20_30 = 0.1000,
      p30_40 = 0.1100,
      p40_50 = 0.1190,
      p50_60 = 0.1230,
      p60_70 = 0.1250,
      p70_80 = 0.1290,
      p80_90  = 0.1295,
      p90_100 = 0.1300,
      p100_110 = 0.1315,
      p110_120 = 0.1344,
      p120_130 = 0.1411,
      p130_140 = 0.1500,
      p140_150 = 0.1555,
      p150_160 = 0.1574,
      p160_170 = 0.1663,
      p170_180 = 0.1672,
      p180_190 = 0.1848,
      p190_200 = 0.1865,
  },
  Chat = {
      Enabled = false, -- // example : $pred 0.12
      HitChance = "$hc",
      Silent_Prediction = "$pred",
      Fov_Size = "$fov",
      AimAssist_Fov_Size = "!fov",
      AimAssist_Smoothness = "!smooth",
      AimAssist_Prediction = "!pred",
      Revolver_Fov = "rfov",
      DoubleBarrel_Fov = "dfov",
      Shotgun_Fov = "sfov",
      TacticalShotgun_Fov = "tfov",
  },
  Range = {
      Enabled = false, -- enable prediction for prediction commands and fov for fov commands (you can enable both)
      Fov = true,
      Prediction = false,
      Close_Detection = 16, -- uses studs
      Mid_Detection = 42, -- uses studs
      Far_Detection = math.huge, -- uses studs (leave it at math.huge)
      Close_Fov = 55,
      Close_Prediction = 0.12,
      Mid_Fov = 35,
      Mid_Prediction = 0.125,
      Far_Fov = 10,
      Far_Prediction = 0.13,
  },
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/xfarzad/Shhhh/main/BETA", true))()
