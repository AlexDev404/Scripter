# Introduction
## FAQ
What languages are supported?: C# and C++. We are planning to add Go, JS, Rust, and Lua.
What Fortnite versions are supported?: Every version except for alpha and higher than s16.
How big are scripts?: They will most likely never go over 2MB.
Is it open source?: Not yet, but we plan to when we have every goal implemented.
Discord Server:

# Scripts
What are scripts?
They aren't actual "scripts". By scripts, we mean DLL files. With our Scripter.dll you are able to modify Fortnite in other programming languages easily, for example, C#. They are easy to set up and easy for other users to use.

# Installing a script
Download the .script file. Create a new folder in the folder where your game's binaries are located called "Scripts"
. Now drag the .script file in and inject Scripter.dll.

## How installing works
The .script file is really just a zip renamed. It contains a JSON file that contains information about the script. It extracts it to your local AppData in a folder called "Scripts".
## Deleting a script
It is not as simple as you would think. First, delete the .script file in your Scripts folder in your Win64. Then press Win + R and type %localappdata%/Scripts/ and delete the folder with the script name. You are finished and it should no longer get loaded.
## Using the Script Builder
You will already need your DLL file. Run ScriptBuilder.exe and enter the DLL path, then enter the language (C#, C++, CSharp, Cpp, JS, Javascript, etc.). Then enter the description for the script, and what it does. It will create a new file where ScriptBuilder.exe is located and it will be the script file.

# Making a script
It is pretty similar for every language. Every language has a scripter file that imports the functions.
