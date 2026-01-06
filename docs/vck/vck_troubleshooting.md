# Troubleshooting

Common solutions for issues you may encounter while using the Vertex Color Kit.

---
## Workflow & Setup

### "The modifiers aren't doing anything!"
Since Vertex Colors aren't visible in the viewport by default, it can be difficult to see the effect of the modifiers.

!!! tip "Solution"
    It is highly recommended to add and pin the **[`VC Preview`](./vc_preview.md)** modifier to your stack first before adding any others. This allows you to see the changes from other modifiers in real-time.

### "I have too many modifiers!"
Working with many geometry node modifiers can make the default modifier stack difficult to navigate.

!!! tip "Solution"
    For managing large and complex modifier stacks, we recommend using the [Modifier List](https://extensions.blender.org/add-ons/modifier-list-fork/) addon for Blender. It provides a more compact and organized view of your modifiers.

---
## Visibility Issues

### "I can't see my vertex colors in Solid Shading mode!"
To view Vertex Colors in the 'Solid' viewport shading mode, you need to change how objects are colored by default.

!!! tip "Solution"
    1.  In the top-right of the 3D Viewport, click the dropdown arrow for **Viewport Shading**.
    2.  Under the **Color** options, change the mode from `Material` to **`Attribute`**.

    Your mesh will now display the active Vertex Color layer instead of its material color.

### "I can't see my mesh!"
A key feature of the Vertex Color Kit is that the Alpha channel is treated just like the RGB channels. If a modifier clears the Alpha channel to zero, your mesh may become invisible.

!!! tip "Solution"
    In the **[`VC Preview`](./vc_preview.md)** modifier, toggle the visibility of the **`A Channel`** off to prevent the mesh from vanishing.

### "I can't see the vertex color alpha channel in Solid Shading mode!"
Blender's 'Solid' viewport shading mode does not support displaying attribute alpha.

!!! tip "Solution"
    Switch to **Material Preview** or **Rendered** shading modes to see the alpha channel's effect.

    Alternatively, for a quick preview, add a **[`VC Swizzle`](./vc_swizzle.md)** modifier to the bottom of the stack to visualize the Alpha channel in the R, G, or B channels. Remember to disable it when you're done to avoid overwriting your color data.

---
## Material Issues

### "My materials are gone!"
This typically happens if the `VC Preview` modifier is still active on your object.

!!! tip "Solution"
    The **[`VC Preview`](./vc_preview.md)** modifier temporarily overrides the mesh's materials for preview purposes. To restore your original materials, simply **disable or remove** the modifier from your stack. Always remove it before exporting to prevent the material override from being baked into the final result.