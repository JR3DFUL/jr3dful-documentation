<table>
  <tr>
    <td width="150">
      <img src="../vck_assets/vc_to_vertex_group.png" alt="Vertex Color To Vertex Group Thumbnail" width="150">
    </td>
    <td style="vertical-align: middle;">
      <h1>Vertex Color To Vertex Group</h1>
      <p><em>Converts Vertex Color data into a weight-painted Vertex Group.</em></p>
    </td>
  </tr>
</table>

<p style="text-align:center;">
  <img src="../vck_assets/gifs/vc_to_vertex_group.gif" alt="Vertex Color To Vertex Group animation">
</p>

### Modifier Parameters {: data-toc-skip }
- **`Vertex Group`**: The Vertex Group to write the weight data to.

!!! info "Mix & Mask Parameters"
    Refer to the [Mix & Mask](./vc_mix_and_mask.md) page for a full description of these settings.

!!! note "Weight Painting"
    A primary use for this modifier is to create complex weight maps non-destructively. By generating procedural vertex colors with other modifiers in the kit, you can create intricate weight patterns that would be difficult to paint by hand.

    Note that Vertex Groups store a single float value (0.0 to 1.0) for weight. To convert, the incoming Vertex Color is first desaturated to a grayscale value which is then used as the weight.


!!! danger "Existing Vertex Group Required"
    The name provided must match your target Vertex Group **exactly**. If the name doesn't match or the group doesn't exist, a new data Attribute will be created instead of writing to the Vertex Group. It is highly recommended to create your target Vertex Group before using this modifier.