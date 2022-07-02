These are my local manifests for cedric & deen

How to use ?


```
mkdir .repo/local_manifests
curl https://raw.githubusercontent.com/GiovanYCringe/local_manifests/main/$DEVICE/$MANIFEST_NAME > .repo/local_manifests/manifest.xml
```
be sure to replace $DEVICE and $MANIFEST_NAME with a device codename and manifest name, that are available

Example:
```
mkdir .repo/local_manifests && curl https://raw.githubusercontent.com/GiovanYCringe/local_manifests/main/deen/A11Magnu-R.xml > .repo/local_manifests/manifest.xml
```

after that do `repo sync --force-sync --no-tags --no-clone-bundle -c`
