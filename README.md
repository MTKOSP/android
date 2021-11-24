### About MTKOSP ###

MediaTeK Open Source Project is an Android Custom ROM, Based On AOSP & Fueled by Lineage.
Providing to users a clean, bloat free and a very good experience with Minimal Customization!
We also just focus on MTK devices and providing them a pure OSS experience.

### Initializing & sync Repo ###

#### Initialize repo
```
$ repo init -u git://github.com/MTKOSP/android.git -b mtkosp-2.0
```

#### Sync 
```
$ repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

### Building the ROM ###

```
$ . build/envsetup.sh && export LC_ALL=C && lunch mtkosp_($device_codename)-userdebug && brunch mtkosp_($device_codename)-userdebug
```

### Contribute toward our Project ###

To submit changes/patches, please send a pull request on GitHub. We will review and merge.
