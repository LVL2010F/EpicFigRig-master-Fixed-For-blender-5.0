# EpicFigRig-master-Fixed-For-blender-5.0
This is a fixed version for EpicFigRig-master that didn't work in blender 5.0 now it should work*.

IMPORTANT: uninstall the old version of EpicFigRig-master before installing the new one

*You may encounter the problem that the hands are not parented, to fix that you will need to

1. Go to Object Mode.

2. Select the loose Hand object by clicking on it.

3. Hold Shift and click on the Armature (the bone rig).

4. Switch to Pose Mode (you can use Ctrl + Tab or the top-left dropdown).

5. Click directly on the Hand Bone (the specific bone that is supposed to control that hand, likely named something like Hand.L or Hand.R). It should highlight to show it is the active selection.

6. Press Ctrl + P to bring up the parenting menu.

7. Select Bone from the list.

Repeat this process for the other hand. Test the arm—the hand should now follow the IK/FK movements perfectly.
