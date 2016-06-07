# PodsIgnoresMultiplePostInstall
Project to demonstrate bug in Pods 0.39 and possibly 1.X where post_install code being silently ignored if declared multiple times

Run pod install and you will see output only from the last declared post_install.
