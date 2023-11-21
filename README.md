# gpx 🗺️

GPX files of various routes

## About

This repository contains GPX files of various routes. I initially created this repository to store the GPX files of routes that I had to painfully create by hand for friends. I figured that I would save them in a public repository so that others could benefit from them as well.

## Usage

The main site that I use to edit, upload, create, and export GPX files is [gpx.studio](https://gpx.studio).

You can open any GPX file committed to this repository with software that can read/write XML files.

Many GPX files contain metadata about the route when you open them with a text editor. Here is an example:

> If you open the [`united_states/utah/grand_canyon.gpx`](united_states/utah/grand_canyon.gpx) file, you will see the following metadata

```xml
<metadata>
    <name>Lees Ferry to Diamond Creek</name>
    <desc>Handmade GPX route of Lees Ferry to Diamond Creek</desc>
    <author>
        <name>gpx.studio + Grant Birkinbine</name>
        <link href="https://gpx.studio"></link>
    </author>
</metadata>
```

This metadata is useful for understanding the route as `grand_canyon.gpx` doesn't tell you exactly what the route is. The metadata tells you that the route is from `Lees Ferry` to `Diamond Creek` and that it was created by `gpx.studio + Grant Birkinbine`.
