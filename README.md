# TheTwoTowers_ActionQueue

# CMUD tool setting for TheTwoTowers MUD
# Action QUeue tool

# Purpose:
# Creates a first in last out stack list, used for queueing up commands to be issued to the MUD

# Problem Solved:
# In order to avoid spamming a full list of desired inputs to the MUD all at once, a queue list
# is needed to only pop the next command upon sensing a 'que' trigger from the MUD terminal.

# Solution:
# Create a stack list called: @ActionQueue

# Create 'que' command list that triggers MUD response text when terminal is caught up
# and time synced to the MUD engine.

# Upon 'ActionNext', a set of conditional triggers will sense the 'trigger' text and then
# pop/execute the next command only when the terminal is caught up with the MUD engine
