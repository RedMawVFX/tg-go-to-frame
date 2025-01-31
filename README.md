# tg-go-to-frame
&#9888; This Python script is now part of the <b>redmaw-tg-toolkit</b> repository, and will no longer be developed as a stand-alone script in this repository.

Click [here](https://github.com/RedMawVFX/redmaw-tg-toolkit) for the redmaw-tg-toolkit repository.<br> 
Click [here](https://github.com/RedMawVFX/redmaw-tg-toolkit/tree/main/scripts/tg-go-to-frame) to go directly to the <i>tg-go-to-frame</i> folder in the redmaw-tg-toolkit.
<hr>

Sets the current frame in the Terragen project.

![tg_go_to_frame UI](images/tg_goto_frame_GUI.jpg)

### Requirements
Terragen 4 Professional v4.6.31 (or later) <br>
https://planetside.co.uk/

### Installation
Install Terragen 4 Professional v4.6.31 or greater on your computer.

In this repository you’ll find two Python scripts, which are identical except for their file extensions.  The file ending in .PY will open a command window when run, while the file ending in .PYW will not.  I recommend using the file with the .PYW extension when the script is run or called from an external file or controller device like a Tourbox.

### Usage
When run, the UI presents a single Entry widget called “<b>Go to frame</b>” which accepts integer values. The default value is the current frame, and this value can be retrieved at any time by pressing the <b>Escape key</b>.   The current frame and timeline will automatically update as characters are entered.  The <b>Up Arrow</b> and <b>Down Arrow</b> will advance the current frame forward or backwards respectively by one frame.  Scrolling the <b>middle mouse button</b> will advance the “Go to frame” value, but you must click another key, such as the <b>Enter</b> key, to set the current frame and update the timeline.

### Reference
terragen-rpc <br>
https://github.com/planetside-software/terragen-rpc

Online documentation for Terragen RPC <br>
https://planetside.co.uk/docs/terragen-rpc/

Blog posts on using Terragen RPC <br>
https://planetside.co.uk/blog/hello-rpc-part-1-scripting-for-terragen/ <br>
https://planetside.co.uk/blog/hello-rpc-part-2-error-handling/ <br>
https://planetside.co.uk/blog/script-it-yourself-kelvin-sunlight-colour-with-terragen-rpc/

