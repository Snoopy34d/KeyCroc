# KeyCroc - Code Red

# My first attempt at a script after locking my first KeyCroc when the arming password stopped responding and I did a factory reset. Locked out.

# This is a simple payload to copy your current config.txt file to config.old
# Deletes the config.txt file
# Renames config-CODE-RED.txt to config.txt, thus replacing your original.

# This will allow you to potentially recover your KeyCroc should you forget your arming pass or some other problem occurs.
# The new config.txt file has debug on, SSH and no arming pass - thus hopefully allowing you access again.

# Place the config.CODE-RED.txt file in the same folder as config.txt
# Place the CODE-RED.txt payload file into the payloads folder

# Pray you never need them :)
# But if you do, __code-red in notepad and you can see the updates as they occur.
