English| [简体中文](./README_cn.md)

# hobot_model

## Compile into deb installation package

```
fakeroot dpkg-deb --build hobot-models-basic .
```

## Modify deb installation package version number

Modify the `Version` field in the `hobot-models-basic/DEBIAN/control` file.

## Add/Delete/Modify model files

Update files under the `hobot-models-basic/opt/hobot/model/x5/basic/` path.

