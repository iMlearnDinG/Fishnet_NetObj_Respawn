# Fishnet_Networking_Player_Respawn

A simple setup to respawn a network objected when it despawns due to an impact threshold.

**PlayerCollisionHandler.cs**

Attach this to your player prefab and edit the impact threshold.

**PlayerRespawnManager**

Attach this to a root gameobject which has a NetworkObject attached.

Assign your player prefab and respawn points.

**PlayerControls.cs**

Basic wsad, sprint, jump movements.

**IndependentCameraControl.cs**

Attach this to your main camera in the scene for camera controls.
