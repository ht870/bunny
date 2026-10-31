Spatial AR Bunny v0.4

Deploy index.html at the root of a Render Static Site.
Build command: leave empty
Publish directory: .
Open the HTTPS Render URL in Chrome on an ARCore-compatible Android device.
Tap Start Real AR, scan a lit floor, then tap the camera view to anchor bunny.
This intentionally has no camera overlay fallback: world anchoring requires WebXR immersive-ar hit-test.
Depth sensing is requested as an optional feature; real-object occlusion is NOT implemented in this prototype. The bunny model is a placeholder, not photorealistic.
Requires internet to load Three.js from CDN.
