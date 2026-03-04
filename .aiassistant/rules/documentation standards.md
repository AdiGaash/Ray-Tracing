---
apply: always
---

## Documentation Standards
- **XML Documentation:** Every public class and method must have a `<summary>` tag.
- **Parameters & Returns:** Methods must include `<param>` for all arguments and `<returns>` for non-void types.
- **Shader Comments:** Use `//` for HLSL logic and specify the **GPU precision** (half vs float) used for variables to optimize for the RTX 3090/4060 Ti.
- **Teaching Style:** Documentation should explain *why* a pattern is used (e.g., "Used a ScriptableObject here to decouple data from the MonoBehaviour").