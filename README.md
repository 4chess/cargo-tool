# cargo-tool
When compiling from windows, it saves time (and clicks and typing) just staying on the desktop. 

This batch file for example can be placed on your desktop. Once you run cargo new it makes the directories you need right on the desktop. Copy this batch file into the main app directory (where your cargo.toml is) and that way the build commands work. Any item marked with a * before the description,  for example,  *cargo build [Build the project] indicates that it runs cargo clean automatically before running the command (in this case cargo build). Automatic cleaning before running some of the commands prevents compiler errors based on having artifacts left over that cause conflicts. As such, this is actually a useful tool, i use it every day.
