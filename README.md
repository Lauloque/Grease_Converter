<h1 tabindex="-1" class="heading-element" dir="auto">
    <a target="_blank" rel="noopener noreferrer" href="Prez/icon.png">
        <img src="Prez/icon.png" alt="icon" style="height: 1em; vertical-align: middle;">
    </a>
    Grease Converter
</h1>

[![GitHub license](https://img.shields.io/github/license/Lauloque/bl_addon_template?style=for-the-badge&labelColor=rgb(63,64,64))](https://github.com/Lauloque/bl_addon_template/blob/master/LICENSE) ![Minimum Supported Blender Version](https://img.shields.io/badge/Blender-4.2LTS+-green?style=for-the-badge&logo=blender&logoColor=white&labelColor=rgb(64,64,64)) [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H818FHX)

Grease Converter is a Blender Add-on [forked from Blender Studio's Grease Pencil Converter](https://projects.blender.org/studio/blender-studio-tools/src/commit/2c8e10a4811fbbaf75b9a32489ed4cd3c6451aca/scripts-blender/addons/grease_converter) that can convert annotations to grease pencil objects and vise versa.

After the add-on is installed you have 2 new operators available.

- **grease_converter.convert_to_grease_pencil**:
  
  - Located in the 3DView Side Panel (N)-> View -> Annotations Panel
  - Converts active annotation to Grease Pencil Object and link it in the active Scene.
    ![drawing](https://studio.blender.org/tools/assets/convert_to_grease_pencil.uVvhXE5m.jpg)

- **grease_converter.convert_to_annotation**:
  
  - Located in the 3DView Header -> Object -> Convert
  
  - Active objects needs to be grease pencil object. Will convert it to Annotation Grease Pencil Object. Uses Tint Color and Stroke Thickness attribute found in the Adjustments Panel for final annotation color and stroke thickness. (Annotations are a simple version of GreasePencil and only support **one* color and stoke thickness per layer)
    
    ![drawing](https://studio.blender.org/tools/assets/adjustments_panel.BW2zas1n.jpg)
  
  - > **Note**: If the grease pencil object has it's transforms not applied or a parent you will be prompted with a warning as these are not taken in to account yet

## Installation

You can download the extension either from:

- Blender's GUI (Preferences > Get Extensions)
- The [Blender Extension Platform](https://extensions.blender.org/add-ons/bl_addon_template/) (to be published!)
- [This repository's releases page](https://github.com/<OWNER>/<REPO>/releases).

The installation process is well explained by Blender's official extensions platform documentation:

[About — Blender Extensions](https://extensions.blender.org/about/)
