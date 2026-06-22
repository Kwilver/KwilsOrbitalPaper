# Kwil's Orbital Paper

A quick Paper fork that changes collision code to be more like vanilla minecraft + carpet optimizations. This allowed the Orbital Cannon to work on the Smore SMP, a Paper server, which you can see in action below:
https://www.youtube.com/watch?v=7EQN6Fve_2A
https://www.youtube.com/watch?v=Sluyg8qNnOE
https://www.youtube.com/watch?v=LG69S7Lf3E4

This fork is not affiliated with, endorsed by, or supported by PaperMC. It is based on Paper and keeps Paper's original licensing and credits.

# How to build jar
Requirements:
- Git
- Java/JDK 25 or newer, or a Java setup compatible with Paper's Gradle toolchain
- Internet connection

1. Clone the repo: git clone -b ver/1.21.11 https://github.com/Kwilver/KwilsOrbitalPaper.git
2. cd KwilsOrbitalPaper
3. .\gradlew.bat applyPatches
4. .\gradlew.bat createPaperclipJar
5. The jar will be in paper-server/build/libs

**1.21.11 IS THE ONLY SUPPORTED VERSION!** If you can't figure it out, please don't flood mine and Joy's dms and go talk to ChatGPT or something.

DISCLAIMER:
Based on PaperMC: https://github.com/PaperMC/Paper. Do not report issues to Paper unless they also occur in Paper. This version will also likely become outdated quickly.
