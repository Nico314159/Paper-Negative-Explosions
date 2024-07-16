# ℹ️ If you think you need this, you probably don't. 

# [Player motion](https://github.com/MulverineX/player_motion) no longer relies on negative radius creepers, and thus is now compatible with all server softwares, including Spigot & Paper.


Paper-Negative-Explosions
-----------

In vanilla, a creeper with a negative `ExplosionRadius` value will deal knockback, but not damage. This is useful for mapmaking as it gives you the ability to manipulate player motion without unwanted side effects. ~~(See [Delta](https://github.com/BigPapi13/Delta) for an example of this.)~~

Unfortunately, Spigot and Paper makes it so negative radius creepers do nothing at all. As such, I have created this fork so that mapmakers can enjoy the performance benefits of Paper without having to give up useful vanilla functionality.

**Important:** This is *not* a plugin, it is a replacement for the paper.jar file. So it is unfortunately not usable if your server host doesn't let you change the .jar directly.

~~I will try my best to keep this fully in-sync with regular PaperMC. DM me on Discord if you have any issues.~~

### **This pack is no longer being maintained. Existing versions are still available through the [tags page](https://github.com/Nico314159/Paper-Negative-Explosions/tags) if you need them for any reason.**

Compiling
------
Compiling this fork of Paper works identically to compiling Paper normally. All you need is JDK 17 and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createReobfBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.

Credit
------
All credit goes to the original authors of PaperMC.
