<table>
  <tr>
    <td width="150">
      <img src="../vck_assets/vc_preview.png" alt="Vertex Color Preview Thumbnail" width="150">
    </td>
    <td style="vertical-align: middle;">
      <h1>Vertex Color Preview</h1>
      <p><em>Previews the selected Vertex Color channels in the 3D viewport.</em></p>
    </td>
  </tr>
</table>

<p style="text-align:center;">
  <img src="../vck_assets/gifs/vc_preview.gif" alt="Vertex Color Preview animation">
</p>

### Modifier Parameters {: data-toc-skip }
- **`Unlit Material`**: Toggles an unlit material to view the colors without scene lighting influence.
- **<span style="color: #E53935;">R</span> Channel**: Toggles the visibility of the Red channel.
- **<span style="color: #1E88E5;">B</span> Channel**: Toggles the visibility of the Blue channel.
- **<span style="color: #43A047;">G</span> Channel**: Toggles the visibility of the Green channel.
- **<span style="color: #9E9E9E;">A</span> Channel**: Toggles the visibility of the Alpha channel.

!!! danger "Warning"
    This modifier temporarily overrides the mesh's materials for preview purposes. If left enabled on export or applied to the mesh, this override will be baked into the final result. **Disable or remove it** to restore your original materials.