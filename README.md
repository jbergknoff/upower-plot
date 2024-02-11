# upower-plot

This is a tool for visualizing upower battery charge history. The initial revision is very lightly modified from code which ChatGPT gave, which was only slightly broken, based on the prompt

```
write a webpage that accepts upower battery readings via an `input type=file` and makes an explorable plot of them
```

I did this because the graphs given by `gnome-power-statistics` are very hard to read and can't be zoomed.

## TODO

* [x] Make the plot zoom in on the appropriate region.
* [x] Any way to set default directory to `/var/lib/upower`? Apparently not
* [x] Make it possible to load multiple files.
