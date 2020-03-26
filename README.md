# Shapeshift 2.0.0
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
