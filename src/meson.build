piwik_sources = [
    'Cookies.cpp',
    'Cookies.h',
    'CURLHttpRequest.cpp',
    'CURLHttpRequest.h',
    'CustomVar.cpp',
    'CustomVar.h',
    'EcommerceItem.cpp',
    'HttpRequestQueue.cpp',
    'HttpRequestQueue.h',
    'ICriticalSection.h',
    'IHttpRequest.h',
    'IPiwikTracker.h',
    'IThread.h',
    'PiwikCreator.cpp',
    'PiwikCreator.h',
    'PiwikTracker.cpp',
    'PiwikTracker.h',
    # 'PosixCriticalSection.cpp',
    # 'PosixCriticalSection.h',
    # 'PosixThread.cpp',
    # 'PosixThread.h',
    # 'stdafx.cpp',
    # 'stdafx.h',
    'targetver.h',
    # 'tempapp.cpp',
    'Utils.cpp',
    'Utils.h',
    # 'WindowsCriticalSection.cpp',
    # 'WindowsCriticalSection.h',
    # 'WindowsThread.cpp',
    # 'WindowsThread.h',
]

piwik_lib = static_library(
    'piwik', 
    piwik_sources,
    dependencies: [
        dependency('libcurl')
    ]
)

