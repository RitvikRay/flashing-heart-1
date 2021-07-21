# Flashing Heart

## Step 1

Drag the icon blocks from the basic section and put it in a forever loop.
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## Step 2

Drag another icon block and put it in the forever loop. Now click on the heart and make it a small heart from the options.
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showIcon(IconNames.SmallHeart)
})
```
## Step 3
Try it on your microbit!<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
