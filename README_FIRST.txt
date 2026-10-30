VILLAGER WARDEN — FABRIC 1.21.11

WHAT THIS MOD DOES
- Keeps the Warden's original model, size, animations and behaviour.
- Replaces its texture with the vanilla Villager texture.
- Client-side only. Install it in the client mods folder.

BUILD THE JAR ONLINE WITH GITHUB ACTIONS
1. Extract this ZIP.
2. Sign in to https://github.com/ and create a new repository at https://github.com/new
3. In the new repository, use Add file > Upload files. Upload the CONTENTS of this folder.
   IMPORTANT: Include the hidden .github folder. It contains the automatic build workflow.
   If Windows hides it, turn on File Explorer > View > Show > Hidden items.
4. Commit the uploaded files to the main branch.
5. Open the repository's Actions tab.
6. Select "Build Villager Warden Mod" and click "Run workflow".
7. Open the finished run. Under Artifacts, download "villager-warden-1.21.11".
8. Extract that downloaded ZIP. It contains villager-warden-1.0.0.jar.
9. Put the JAR in %appdata%\\.minecraft\\mods and launch Minecraft 1.21.11 with Fabric.

If GitHub's upload page does not show Upload files, open the repository page and choose
Add file > Upload files, or use the blue "uploading an existing file" link on the empty
repository's Quick setup page.

NOTE
This is a source project with an automatic GitHub build workflow, not a precompiled JAR.
The workflow has been configured for Minecraft 1.21.11, Java 21, Fabric Loader 0.18.6,
Yarn 1.21.11+build.1 and Fabric Loom 1.15.5. The build itself still needs to run on GitHub.
