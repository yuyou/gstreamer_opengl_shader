# gstreamer opengl shader samples

```
gst-launch-1.0 gltestsrc is-live=true ! glshader vertex="\"`cat vertex.gstreamer`\"" fragment="\"`cat fragment.gstreamer`\"" ! glimagesink sync=false
```
