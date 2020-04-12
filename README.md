# DebotnetUpdater
Get the latest build of Debotnet once a day

# Usage 
You can use this console application to download/update (to) the latest (stable) release of Debotnet.

<details><summary><b>Show instructions</b></summary>

1. Run `DebotnetUpdater.exe`
2. Latest build will be automatically downloaded, extracted to directory `Debotnet` and started.
3. After finishing, an `update.txt` file is created with current date
4. Next time you run `DebotnetUpdater.exe`it will check whether the date has changed. If it's already been downloaded for the day, it launches Debotnet without downloading again.
