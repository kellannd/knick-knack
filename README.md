# Project

Demo Video:

### Chosen Locations
The two locations I chose for this project were Koh Tao, Thailand (specifically Than Sadet-Ko Pha-ngan National Park) and Greece. I went to Koh Tao in January 2024 and was able to see a sea turtle while snorkling, which was one of the best parts of the trip for me as I have never seen a wild sea turtle that close. I went to Greece in the May 2025 with a goal of seeing as many temples and ancient ruins as possible, so I incorporated a temple along with some statues I saw while I was there.

# Design
All credit for components and tutorials are under the [Assets and Tutorials Section](#assets-and-tutorials).

For both models, I used a scripts that gets the current weather (using the [OpenWeather](https://openweathermap.org/api) API) and time at the location.

## Koh Tao, Thailand Knick-Knack
I combined a mixture of blender created and assets taken from free online resources. The turtle was a component from Poly Pizza that I scripted to bob up and down in the water. The sand and starfish came from the same component from CG Trader that I modified to create a smaller starfish to allow for more room on the sand. On the sea floor I also put a crab and shell to account for some other little things I saw while snorkling. The water component is a water asset from the Unity Asset Store that I modified to make transparent. On the back of the component, I included a photo of the actual sea turtle and, when the box is flipped over, a photo of a starfish seen while snorkling will apear.

### Screenshots
<img src="/screenshots/th_ss.png" height="500"/><br>
<b>Screenshot from Unity</b>


## Athens, Greece Knick-Knack
I got the temple component from Poly Pizza and reused the water component to add water to the fountain inside of the partheon. I got the statues from a pack of ancient Greek city components to put in front of the partheon. I got the pottery from CG trader. I used the Rock Textures Asset from the Unity Asset store for the materials on most of the components. On the back of the component, I included a photo of the Partheon in Athens and when the box is flipped over, there is a photo of some of the iconic white dome churches in Santorini.

### Screenshots
<img src="/screenshots/gr_ss.png" height="500"/><br>
<b>Screenshot from Unity</b>

# Process
This project was made in Unity, utilizing Vuforia for the AR functionality. Blender was used to create and modify components to use in the project.

# Challenges
The biggest challenge I ran into during this project was transfering components made in Blender to Unity. I created one component that I was unable to use because I lacked compatable hardware. For other components, I was unable to export materials that I created in Blender to use in Unity. I know that there are ways to "bake" your materials to the components, but even following multiple tutorials, was unsuccessful doing this.

# Assets and Tutorials
### Assets
#### CG Trader
Lowpoly pottery collection group of vases Free low-poly 3D model by adam127 https://www.cgtrader.com/free-3d-models/household/kitchenware/lowpoly-pottery-collection

Cartoon Low Poly Starfish Illustration Free low-poly 3D model by antonmoek https://www.cgtrader.com/free-3d-models/exterior/other/cartoon-low-poly-starfish-illustration

#### Poly Pizza
Turtle by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via Poly Pizza (https://poly.pizza/m/fklSEvGm1Q8)

Crab by Poly by Google [CC-BY](https://creativecommons.org/licenses/by/3.0/) via Poly Pizza (https://poly.pizza/m/2DgM36qZW2u)

Greek Temple by Alexandre Thomas (Ashtom) [CC-BY](https://creativecommons.org/licenses/by/3.0/) via Poly Pizza (https://poly.pizza/m/cdMQnl19MB9)

#### TurboSquid
Ancient Greek City Pack 33 GameReady Assets by PackDev https://www.turbosquid.com/3d-models/ancient-greek-city-pack-33-gameready-assets-1187678?dd_referrer=

#### Unity Asset Store
Rock Textures - 4k by Texture Haven https://assetstore.unity.com/packages/2d/textures-materials/rock-textures-4k-179128

URP Stylized Water Shader - Proto Series by BitGem https://assetstore.unity.com/packages/vfx/shaders/urp-stylized-water-shader-proto-series-187485

### Tutorials
#### Blender Tutorials
<img src="/screenshots/blender_shell_mat.png" width="300"/><br>
I created this [shell object](/blender/shell.blend) for my project. I also created a material/shader to go with the component, but was not able to export the material to use in Unity.
Tutorial: https://www.youtube.com/watch?v=ic9gbO7Pk3c

<img src="/screenshots/water_unused.png" width="300"/><br>
I created this [water component](/blender/water.blend) originally to be used in my project. However, upon completing the component, I realized that I did not have a compatable GPU to render the component (Cycles in Unity needs an AMD GPU, CPU alone was not enough to render).
Tutorial: https://www.youtube.com/watch?v=sxWJqMJdL04

I used this tutorial to create the water component that I used in the project. I modified the material to be translucent.
Tutorial: https://www.youtube.com/watch?v=LBp1-yHCBYo (using URP Stylized Water Shader from Unity Asset Store)

#### Unity Tutorials
Tutorial referenced to make turtle bob in water: https://www.youtube.com/watch?v=nnDFXmoNBOo
