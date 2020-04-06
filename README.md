![Shapeshift](https://i.imgur.com/dWWExrI.png)
Shapeshift is a 3D Map Model Maker made for and with P3D (http://p3d.lizardking.co/)
This is a repository for Source MFA Releases and Executable Releases.

Visit the [Everything You Need To Know!](https://github.com/VoyVivika/shapeshift/wiki/Everything-You-Need-To-Know!) Page on the Wiki.

Note: To make use of the MFA file you have to copy and paste the "P3D perspective projection engine" group from your P3D mfa into the shapeshift mfa where designated.
If you're looking for the previous iteration of Shapeshift you'll find it here https://github.com/VoyVivika/shapeshift1 (Clickteam Fusion 2.5+ Required for Shapeshift 1.x)

Note: Shapeshift 2.x is currently not capable of importing Shapeshift 1.x or T-Mesh Data.

Skybox is "Sky Box - Sunny Day" by The Chayed/Chayed Creates/KIIRA from OpenGameArt.org

Changes over original
- Points Detached from Tris/Quads (Allows much easier editing of geometry by manipulating global points instead of per-polygon points)
- Better Mouse Control
- 123 Importable Textures over original 50
- (Source MFA) Clickteam Fusion 2.5+ DLC No Longer Required

Features Excluded from 1.x
- Lighting (for now this should be handled within your own application unless there is demand)

# P3D
P3D is an extensionless 3D engine for Clickteam Fusion 2.5 by Lizard King containing most of the basics for making a 3D game. The engine is heavily reliant on Fusion 2.5's Pixel Shaders support via DirectX 9. Fusion's Shader support is not whole hearted and thus lacks crutial features for allowing this engine to run better than it does. It's suggested to use Sprites instead of large amounts of polygons due to the strain they put on the Engine, particularly on low end machines. Find more info about P3D here http://p3d.lizardking.co/

# TL;DR License Info
Shapeshift is Licensed under the MIT License which basically permits you to use the source for whatever you'd like but you are not granted rights to the Copyright and you are required to include the license, not required to use the same license, but required to include it. Bear in mind P3D is not included with the Source and uses it's own strict license about distributing it's source (hense the choice for a permissive license), using it's Source maintains that you abide by it's license, if you wish to share the source for your own derivative of Shapeshift you'll have to make sure you remove P3D's group if you've pasted it in there to begin with.
