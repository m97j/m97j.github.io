---
title: ✅ nanite
date: 2024-10-06
authors:
  - admin
tags:
  - nanite
  - unreal5
---

Understanding Nanite and Its Principles
The basic principle of Nanite involves importing assets used in the engine and clustering a certain portion of triangles into units called clusters, which are then analyzed and decomposed.

During rendering, these clusters transition to various Levels of Detail (LOD) based on the camera view and are displayed in real-time in the viewport.

At this time, only the visible areas are rendered through occlusion culling based on the camera's perspective.

Therefore, Nanite only consumes memory for the areas being streamed by the camera.

However, it's important to note that when processing cluster culling in Nanite, if the distances between surfaces are excessively close and overlap a lot, overdraw can occur.

This typically happens when multiple geometries are stacked near the top surface, causing the engine to render both surfaces because it cannot accurately distinguish which is on top.

Rendering all parts in this manner can lead to optimization issues.

Through this process, no matter how high the polygon model is used, we no longer need to create LODs, and there is no loss in quality.

Additionally, high polygons can be used directly without using normal map textures to express details.

Nanite is especially useful when you want to express a high level of detail.

It can even be more cost-effective and provide higher quality and smaller size than creating low polygons and using LODs.