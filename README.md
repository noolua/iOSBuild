#iOSBuild



Usage: ./iOS-build [lua openssl curl uv x264 xvid ffmpeg isofs]


FAQ:
  ld: file not found: /usr/lib/system/host/libdyld.dylib for architecture i386
    # sudo mkdir -p /usr/lib/system/host
    # sudo ln sudo ln -s /usr/lib/system/libdyld.dylib /usr/lib/system/host/libdyld.dylib
