# health_tizen

Get live health data from Tizen.

## Getting Started

This plugin requires Tizen 5.5+.

Make the following changes to `tizen/tizen-manifest.xml`
```
<manifest api-version="5.5" ...>
    <privileges>
        <privilege>http://tizen.org/privilege/healthinfo</privilege>
    </privileges>
    <feature name="http://tizen.org/feature/sensor.heart_rate_monitor">true</feature>
</manifest>
```