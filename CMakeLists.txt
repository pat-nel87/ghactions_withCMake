cmake_minimum_required(VERSION 3.20)

# The first line of top-level CMakeLists file should always be cmake_minimum_required
# allows project to specify a required version of cmake; also allows backwards compatibility 

project(Hello)

# the next line should be the project command
# specifies project name and may specify other options ie. language/version etc.

add_executable(Hello Hello.c)

# add_executable adds an executable to the project using the given source file
