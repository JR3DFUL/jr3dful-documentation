<table>
  <tr>
    <td width="150">
      <img src="../vck_assets/vc_to_uv.png" alt="Vertex Color To UV Thumbnail" width="150">
    </td>
    <td style="vertical-align: middle;">
      <h1>Vertex Color To UV</h1>
      <p><em>Stores Vertex Color data into one or two UV maps.</em></p>
    </td>
  </tr>
</table>

<p style="text-align:center;">
  <img src="../vck_assets/gifs/vc_to_uv.gif" alt="Vertex Color To UV animation">
</p>

### Modifier Parameters {: data-toc-skip }
- **`VC UV 1 Name`**: Sets the name of the first UV map to store color data in.
- **`VC UV 2 Name`**: Sets the name of the second UV map to store color data in.

!!! note "Channel Packing"
    By default, the **RG** channels are sent to the first UV map (`VCUV1`) and the **BA** channels are sent to the second (`VCUV2`).