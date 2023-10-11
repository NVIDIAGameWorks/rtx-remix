---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

**Describe the bug**
- A clear and concise description of what the bug is.
- Which Remix version (include branch and commit info for dxvk and bridge if not a stable build)
- Which GPU
- Which GPU driver version
- Which game build (and whether it is from Steam/GOG/Other)

**Attach files!**
- NvRemixBridge.log
- d3d9.log
- The game specific log will be named gamename_d3d9.log
- Used rtx.conf
- For crashes also attach dump files: {.dmp} for CPU side crashes and {.nv-gpudmp and shaderDebugInfo folder} for GPU side crashes. Automatic GPU dumps can be enabled by setting "dxvk.enableAftermath = True" in dxvk.conf. Zip these files before uploading them.
  Note, the dumps may contain personally identifiable information.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
- A clear and concise description of what you expected to happen.

**Screenshots**
- If applicable, add screenshots to help explain your problem.
- If it is a visual issue where the raytraced version is wrong/different in comparison to the rasterized version, attach a screenshot of the rasterized version for reference. You can view the rasterized version by disabling raytracing (available in debug and debugOptimized builds).
