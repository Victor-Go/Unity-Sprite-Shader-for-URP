# Introduction
This is the shader graph used **under** the *Universal Render Pipeline (URP)* to enable Sprite to cast shadows.

# How To Use

- Select the Sprite Renderer you want to cast the shadow.
- Switch to **Debug** mode from inspector menu.
- Switch **Cast Shadow** to **On**.
- (Optional) You may also want to check **Receive Shadows**.
- Create a material using the **Sprite Shadow.shadergraph**.
- Assign the material to Sprite Renderer.

# Notice
If you are not able to cast shadows, select the **Univeral Render Pipeline Asset** that you are currently using. Then check both *Lighting/Main Light/Cast Shadows* and *Lighting/Additional Lights/Cast Shadows*.