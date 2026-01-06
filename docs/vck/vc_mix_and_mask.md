<table>
  <tr>
    <td width="150">
      <img src="../vck_assets/vc_mix_and_mask.png" alt="Mix & Mask Parameters Thumbnail" width="150">
    </td>
    <td style="vertical-align: middle;">
      <h1>Mix & Mask Parameters</h1>
      <p><em>These settings are present on nearly all Vertex Colors Kit Modifiers.</em></p>
    </td>
  </tr>
</table>

### Mix
Color Mix Settings

-   **`Blend Mode`**: Changes how colors are mixed.
    -   **Mix:** A standard linear blend, or 'lerp', between the two colors.
    -   **Darken:** Takes the darkest value of each color channel.
    -   **Multiply:** Multiplies the color values.
    -   **Color Burn:** A darker, more saturated result than Multiply.
    -   **Lighten:** Takes the lightest value of each color channel.
    -   **Screen:** A lighter result than Add.
    -   **Color Dodge:** A brighter, more saturated result than Screen.
    -   **Add:** Adds the color values together.
    -   **Overlay:** A combination of Multiply and Screen.
    -   **Soft Light:** Softer version of Overlay.
    -   **Linear Light:** A combination of Color Dodge and Color Burn.
    -   **Difference:** Subtracts the top layer from the bottom layer.
    -   **Exclusion:** Similar to Difference, but with lower contrast.
    -   **Subtract:** Subtracts the color values.
    -   **Divide:** Divides the color values.
    -   **Hue:** Uses the hue of the top layer and the saturation and value of the bottom layer.
    -   **Saturation:** Uses the saturation of the top layer and the hue and value of the bottom layer.
    -   **Color:** Uses the hue and saturation of the top layer and the value of the bottom layer.
    -   **Value:** Uses the value of the top layer and the hue and saturation of the bottom layer.
-   **`Blend Factor`**: Controls the strength of the blend.
-   **`Switch Blend Order`**: Swaps the input colors, altering the blend result.

### Mask
Attribute and Channel Mask Settings

-   **`Attribute Mask`**: Uses a custom attribute to mask the effect.
-   **`Invert Mask`**: Inverts the influence of the attribute mask.
-   **<span style="color: #E53935;">R</span> Channel**: Adjusts the influence of the Red channel.
-   **<span style="color: #43A047;">G</span> Channel**: Adjusts the influence of the Green channel.
-   **<span style="color: #1E88E5;">B</span> Channel**: Adjusts the influence of the Blue channel.
-   **<span style="color: #9E9E9E;">A</span> Channel**: Adjusts the influence of the Alpha channel.