# TrailCraft

**Build your own Trailmakers map in 3D. Shape the ground and place objects on it. Then export the map so you can play it in Trailmakers.**

TrailCraft is in playtesting. This means we are still testing it with players. If something goes wrong, or you have an idea, please use one of the feedback links at the bottom of this page, or you can DM me on discord (lulufur / LuluFluffy).

> ```
> TrailCraft is proprietary software supplied for personal, non-commercial
> playtesting under the playtest licence included in the download. Reverse engineering,
> redistribution, resale and modification of the app are prohibited, subject
> to mandatory legal rights and third-party licences. You can create and
> export user created content, modify and share files created solely
> from the app's exported contents, and share screenshots
> and recordings of normal use.
> ```
>
> [Read the playtest licence](LICENCE.txt)

<p align="center">
  <a href="https://github.com/LuluFur/TrailCraft-Playtest-2/releases/download/v0.2.0/TrailCraft-test.zip"><strong>⬇ Download TrailCraft Playtest 2 (Windows)</strong></a>
</p>

## Start a new map

Maps that you made in earlier versions of TrailCraft do not work in this playtest. Please start a new map. You can also bring in a save from Trailmappers.

## Install on Windows

1. Click the download button above. This downloads a ZIP file. 
2. Open File Explorer and find the ZIP file. Right-click it and choose **Extract All**. This unpacks the files into a normal folder.
3. Open the new folder. Double-click **TrailCraft.exe** to start TrailCraft.
4. Windows may show a message that it protected your PC. If it does, choose **More info**, then choose **Run anyway**. TrailCraft is not signed yet. A signature tells Windows who made a program.

TrailCraft looks for Trailmakers in your Steam library. Your Steam library is the set of folders where Steam installs your games. If TrailCraft cannot find the game, choose **Pick Trailmakers folder...**. Then select the folder that contains `Trailmakers.exe`. Usually, this is the folder:

`C:\Program Files (x86)\Steam\steamapps\common\Trailmakers`
TrailCraft remembers this folder.

## Known bug

When you build or repair a vehicle, Trailmakers may pick the Test Zone floor as the place to do it, instead of your terrain. I know about this. It comes from how the game works.

## What you can do

### Shape the ground

- Add terrain. Raise or lower the ground, smooth it, and paint it with different ground types.
- The paint buttons show the real ground textures, so you can see what each one looks like.
- When you raise or lower the ground, the props on it move up or down with it.
- A setting in the Terrain panel makes the edge of your terrain meet the Test Zone floor.

### Draw roads

- Draw roads that follow the shape of the ground. Roads lean into their turns.
- When two roads cross, they make a junction.
- Choose the line down the middle of the road: dashed, single solid, double solid, or none. The white lines on the road edges always stay.
- Add pavements for people to walk on. They have a 10 cm kerb, which is the step up from the road. You can also add parking bays along a road.
- TrailCraft adds a strip of dirt beside a road. This strip is called a hard shoulder.

### Place and manage props

- Search for props by name or by category. Then drag them into the map.
- Move, turn and resize props. Make a copy of one prop, or move a group of props together.
- Choose **Local** to make each selected prop move, turn and resize along its own axes. Axes are the directions that the prop moves along.
- Paint many props at once with the Asset Brush.
- Place trees, rocks and plants by ground texture.
- In the Asset Brush, each prop has a **Ground patch** switch. When it is on, the brush paints dirt under the props it places. For trees, it starts switched on.
- Add your own 3D models from `.obj` files.

## What you need

You need a Windows 10 or Windows 11 PC. Linux also works but needs extra steps, DM me on discord.

You also need Trailmakers, installed through Steam.

TrailCraft uses props from your own copy of Trailmakers. Props are the trees, rocks and other objects from the game. The download does not contain any game files.

## Make and play a map

When you start TrailCraft, it makes pictures for the prop list.

To draw a road, click the **Spline** button on the toolbar. Then click on the ground to place the line of the road.

When your map is ready, save it. Then choose **Export**. TrailCraft puts your map in the `mods` folder, inside the folder where Trailmakers is installed. Start Trailmakers and load your map as a local mod.

## Send feedback

- [Report a bug or suggest a feature in the TrailCraft Discord](https://discord.gg/RV7Vts4jdC)

You can also DM me on discord (lulufur / LuluFluffy). :D

When you report a bug, please say what happened and the steps you took. A screenshot helps.

If you can, also send the build value from the TrailCraft log. The log is a file where TrailCraft writes down what it does:

- **Windows:** Open File Explorer. Paste `%LOCALAPPDATA%\TrailCraft` into the address bar at the top and press Enter. Then open `trailcraft.log`.
- **Linux:** Open `~/trailcraft-prefix/drive_c/users/steamuser/AppData/Local/TrailCraft/trailcraft.log`.

In the log, find the last line that contains `app.start`. Copy the value after `build_sha=` and paste it into your report. You can also attach the whole log file instead. The log can contain your map names and some details about your computer's graphics.


Thank you for helping test TrailCraft!
