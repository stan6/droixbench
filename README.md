Droixbench is a collection of 24 reproducible crashes in open-source Android apps.

To replay the event sequences leading to the crash, follow the steps below:
1. Follow the setup instructions (creating account) in the "README.txt".
2. Run the "monkey_playback.py" in this folder with monkeyrunner.  
```monkeyrunner monkey_playback.py <testscript> <package-name>```
For example, 
```$HOME/Android/Sdk/tools/bin/monkeyrunner monkey_playback.py $HOME/droix/droixbench/Transistor1.1.5/transistor-21 org.y20k.transistor```

*Note that the replay script could be replayed only in emulator create in Android Studio: Nexus 5X, API24, x84-64. As the resolution may be different in other emulator, the script will need to be re-recorded for other emulator. 


Each subdirectory represents a defect that causes crash in an buggy APK. The contents of each subdirectory includes:
1. A buggy APK that contains a given defect
2. A script file with specific UI event sequences to reproduce the crash
