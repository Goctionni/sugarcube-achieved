# sugarcube-achieved

Download the html file and open in twine to find the code.

[Try it out at](https://goctionni.github.io/sugarcube-achieved/Achieved.html)

## Macros:

* `<<achieve "achiement name">>` - sets given achievement to completed
* `<<achievement "achievement name">>` - outputs an achievement
* `<<achievements>>` - Outputs list with all achievements

## How it works:

Define your achievements in `setup.Achievements`, provide a title, description, image and optional hidden and trigger attributes.

If you give add the trigger attribute, you dont need to use the `<<achieve>>` macro, as that will happen automatically.
