Droixbench is a collection of 24 reproducible crashes in open-source Android apps.

To replay the event sequences leading to the crash, follow the steps below:
1. Follow the setup instructions (creating account) in the "README.txt".
2. Run the "monkey_playbacks.py" in this folder with monkeyrunner. 



Each subdirectory represents a defect that causes crash in an buggy APK. The contents of each subdirectory includes:
1. A buggy APK that contains a given defect
2. A script file with specific UI event sequences to reproduce the crash
