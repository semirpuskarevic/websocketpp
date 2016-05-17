project('websocketpp', 'cpp',
        'version': '0.7.0'
       )

inc = include_directories('websocketpp')
boost_dep = dependency('boost', modules : 'system')
websocket_dep = declare_dependency(include_directories : inc, dependencies :boost_dep )

