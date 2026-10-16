# SwordLab (Fabric 1.21.11, Mojang mappings)

Client-side test modules for validating a server anti-cheat: Trigger Bot, Silent Aim Assist, Auto Jump Reset.
Open the glass GUI with Right Shift (rebindable). Left-click a module to toggle, right-click to expand settings.

Build (Java 21):  ./gradlew build   ->  build/libs/swordlab-1.0.0.jar  -> drop into .minecraft/mods
No Gradle wrapper is bundled: copy gradlew, gradlew.bat and gradle/ from the official Fabric example mod
(or run `gradle wrapper`), and take the exact loader/fabric_version/loom values from https://fabricmc.net/develop/
