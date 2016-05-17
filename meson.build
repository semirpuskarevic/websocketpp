project('websocketpp', 'cpp',
        version: '0.7.0'
       )

inc = include_directories('.')
boost_dep = dependency('boost', modules : 'system')
websocketpp_dep = declare_dependency(include_directories : inc, dependencies :boost_dep )

