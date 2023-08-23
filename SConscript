
# This script declares to SCons how to compile the example.
# It has to be called from a SConstruct file.
# The 'env' object is passed from there and contains further specification like directory and debug/release flags.
#
# Note: If you're creating a new example and copied this file, adjust the desired name of the executable in the 'target' parameter of env.Program.


Import('env')     # import Environment object from calling SConstruct

# create the main executable
env.Program(target = 'muscle_precice', source = "src/muscle_with_prestretch_precice.cpp")
env.Program(target = 'tendon_precice', source = "src/tendon_precice.cpp")

