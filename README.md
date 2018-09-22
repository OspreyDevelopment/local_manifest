# local_manifests for this repos
There it is some changes to use a stable source to build AOSP or LOS-Based ROMs on moto msm8916 devices (mostly surnia, but there's osprey, harpia and more). If you got some change or suggestion or fix for your device, feel free to pull request idk.

## How can i add this to my common repo sync?
by just ctrl+c and ctrl+v this:
```
curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/ospreydevelopment/local_manifest/master/local_manifest.xml
```
