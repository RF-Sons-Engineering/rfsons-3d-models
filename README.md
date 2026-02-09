# RF Sons 3D Models

Shared 3D models from RF Sons Engineering projects.

## View Models Online

Click to view in browser (no download needed):

### Demo Models
- [Test Box (100×50×20mm)](https://3dviewer.net/#model=https://raw.githubusercontent.com/RF-Sons-Engineering/rfsons-3d-models/main/models/demo/test_box.step)

## How to Use

### View a Model
Click the link above, or construct a URL:
```
https://3dviewer.net/#model=https://raw.githubusercontent.com/RF-Sons-Engineering/rfsons-3d-models/main/YOUR_FILE.step
```

### Supported Formats
- STEP (.step, .stp)
- IGES (.iges, .igs)
- glTF/GLB (.gltf, .glb)
- OBJ (.obj)
- STL (.stl)
- 3DM (Rhino)
- FBX (.fbx)

## Folder Structure
```
models/
├── demo/           # Demo/test models
├── projects/       # Project-specific models
└── components/     # Reusable components
```

## Adding Models

```bash
# Clone
git clone https://github.com/RF-Sons-Engineering/rfsons-3d-models.git
cd rfsons-3d-models

# Add your model
cp /path/to/model.step models/folder/

# Push
git add .
git commit -m "Add model description"
git push origin main
```

---
*Maintained by RF Sons Engineering*
