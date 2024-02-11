# upower-plot

This is a web-based tool for visualizing [UPower](https://upower.freedesktop.org/) battery charge history (typically stored in `/var/lib/upower/history-charge-*.dat`). The initial revision is very lightly modified from code which ChatGPT gave, which was only slightly broken, based on the prompt

```
write a webpage that accepts upower battery readings via an `input type=file` and makes an explorable plot of them
```

I made this because I was having a hard time inspecting the plots produced by `gnome-power-statistics`.

## TODO

* [x] Make the plot zoom in on the appropriate region.
* [x] Any way to set default directory to `/var/lib/upower`? Apparently not
* [x] Make it possible to load multiple files.
