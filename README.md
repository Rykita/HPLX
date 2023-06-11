# HPLX
A 64-bit fork off Amnesia64 which is a fork of Amnesia TDD by Frictional Games (We are not affiliated!) which serves to improve existing functionality and performance of HPL2,
HPLX is a "for fun" exercise project and I give no guarantees regarding it's functionality, although I do my best to keep it as stable and documented as possible.

## Key changes (FROM AMNESIA64):
- Can be compiled in both 32-bit and 64-bit modes using VS2019 with latest build tools.
- Single solution file for all projects (main game, HPL2, dependencies and editors). No need to compile the engine separately.
- Produces self-contained .exe files without dependency on 3rd party dlls (this prevents cluttering user's game folder with 64-bit dlls).
- Some libraries were changed, most notably:
	- SDL2 was upgraded from 2.0.4 to 2.0.12
	- alut was replaced with freealut
	- Newton Dynamics was upgraded from 2.08 to 2.32 (I simply couldn't find the source code for 2.08)
	- Fbx support is removed.

## Planned changes (FOR HPLX):
- Jolt Physics replaces Newton Physics.
- No 60 FPS limit.
- Move project over to Premake
