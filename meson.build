project('EasyLogging++', 'cpp')
inc = include_directories('src')
lib = static_library('elpp', 'src/easylogging++.cc', include_directories : inc, cpp_args : '-DELPP_NO_DEFAULT_LOG_FILE')
elpp_dep = declare_dependency(include_directories : inc, link_with : lib)
