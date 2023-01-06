PaperUnsigned
================
Paper Unsigned is a fork of Paper with the set goal of keeping chat unsigned. more to be added later.


Paper-Negative-Explosions (Received from Nico314159)
------
In vanilla, a creeper with a negative `ExplosionRadius` value will deal knockback, but not damage. This is useful for mapmaking as it gives you the ability to manipulate player motion without unwanted side effects. (See [Delta](https://github.com/BigPapi13/Delta) for an example of this.)

Unfortunately, Spigot and Paper makes it so negative radius creepers do nothing at all. As such, I have created this fork so that mapmakers can enjoy the performance benefits of Paper without having to give up useful vanilla functionality.

I will try my best to keep this fully in-sync with regular PaperMC. DM me on Discord at Nicoder#6884 if you have any issues.


Compiling
------
Compiling this fork of Paper works identically to compiling Paper normally. All you need is JDK 17 and an internet connection.

Clone this repo, run `./gradlew applyPatches`, then `./gradlew createReobfBundlerJar` from your terminal. You can find the compiled jar in the project root's `build/libs` directory.

To get a full list of tasks, run `./gradlew tasks`.


Credit
------
All credit goes to the original authors of PaperMC and https://github.com/Nico314159/Paper-Negative-Explosions
