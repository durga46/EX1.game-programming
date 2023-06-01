# Ex No :01

# <p align="center">  Effects in a material such as emissive, roughness and metallic properties</p>

## Aim:
To implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.

## Software Required:
Unreal Engine.

## Procedure:
Open the Material Editor: In Unreal Engine, go to the Content Browser and navigate to the folder where you want to create your material. Right-click and choose "Create Basic Asset" > "Material" to create a new material. Double-click the material to open it in the Material Editor.

### Setting up emissive effect: 

a. Texture-based emissive effect: Drag and drop an emissive texture into the Material Editor. Connect the emissive texture to the Emissive Color input of the Material node. You can adjust the intensity of the emissive effect using a scalar parameter or a constant value multiplied with the emissive color.

b. Color-based emissive effect: If you want a solid color emissive effect, use a constant vector node to define the emissive color. Connect the constant vector node to the Emissive Color input of the Material node.

### Adding roughness properties: 

a. Texture-based roughness: Drag and drop a roughness texture into the Material Editor. Connect the roughness texture to the Roughness input of the Material node.

b. Constant roughness: If you want a constant roughness value, use a constant scalar node and connect it to the Roughness input of the Material node.

### Incorporating metallic properties: 

a. Texture-based metallic: Drag and drop a metallic texture into the Material Editor. Connect the metallic texture to the Metallic input of the Material node.

b. Constant metallic: Use a constant scalar node to set a constant metallic value and connect it to the Metallic input of the Material node.

Applying the material: Once you've set up the desired properties in the Material Editor, you can apply the material to objects in your scene. Create a Material Instance from the base material by right-clicking the material in the Content Browser and selecting "Create Material Instance." Assign the material instance to the desired mesh or object in the scene.

Adjusting parameters: To provide flexibility and variation, you can expose parameters in the material instance. Right-click on a node in the Material Editor, select "Convert to Parameter," and provide a name. This allows you to tweak the emissive color, roughness, or metallic properties directly in the material instance, without modifying the base material.

Remember to save your materials and material instances in the Content Browser for easy reusability.

By following these steps, you can implement emissive, roughness, and metallic properties in Unreal Engine and achieve a variety of effects for your materials.

## Output:
![WhatsApp Image 2023-06-01 at 9 36 09 AM](https://github.com/durga46/EX1.game-programming/assets/75235704/f463c951-c057-4019-9615-dc2342281bf2)


## Result:

Thus a Implementing various effects in a material such as emissive, roughness and metallic properties done successfully in Unreal Engine





