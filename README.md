# MIPS-Video-Game
My MIPS final project for CS0447 Computer Organization and Assembly Language.

# What is it?
This is my favorite project that I've done for a class so far at Pitt. Basically using some starter files and libraries that the teacher gave us we had to code the `JVA7_proj1.asm` to make a simple adventure game. The premise is to collect 3 keys and get to the treasure to beat the game. The player is able to throw bombs and use a sword in order to defeat blobs and clear the path to victory. The cool thing is that this is all coded in assembly language which is super low level so that means that it takes multiple lines in assembly to do the same thing that is possible in a higher level language.
Here is a screenshot of the gameplay in 64x64 resolution:
![Screenshot](https://user-images.githubusercontent.com/35745239/157386665-bbe81a68-181a-43e2-8caf-d17fbc2cdcda.png)

# How to play?
In order to play you have to download an application called MARS. This is a MIPS cpu emulator that allows us to compile and run MIPS assembly code without having a MIPS cpu built into your computer.

1. Clone this repository to your computer.
2. If you do happen to have JDK 11 or newer installed, you can run MARS. Otherwise, you can install the OpenJDK from [this link](https://adoptopenjdk.net/index.html). Pick OpenJDK 11 or 16 with HotSpot VM.
3. Download MARS from this link [MARS](https://jarrettbillingsley.github.io/teaching/classes/cs0447/software/Mars_2211_0822.jar)
4. Running MARS:
First, try just double-clicking the jar file. If it works, great! If you’re on a Mac and it complains about being from an “unlicensed developer,” right click > Open, and choose to open it anyway. (That works with anything, not just jar files.)

Mac users: the newest versions of macOS have introduced a bunch of strange incompatibilities with Java and I don’t know what’s going on. Even if you manage to get MARS running by double-clicking it, you will often be unable to load/save any files in the file dialog. Running it from the command line as described below usually solves the problem.

If it doesn’t, go into your terminal/command line, and do the following:
    1. cd to the directory where you have the JAR file.
    2. run this: `java -jar Mars_2211_0822.jar`
    try typing java -jar Mars and then hit the Tab key. It will complete the filename for you.
    
4. Open MARS and then open JVA7_proj1.asm.
5. Press the compile button (it looks like a pair of tools)
6. Then press the run button (the green play button)
7. Naviagate to Tools > Keypad and LED Display Simulator
8. Press the CONNECT TO MIPS button
9. You should now see this
![Screenshot](https://user-images.githubusercontent.com/35745239/157386130-fbda8efd-ce3a-4340-9de6-a870f09d3a41.png)
10. Use the arrow keys to move. Use Z for your sword, X to throw bombs and C to use keys.
