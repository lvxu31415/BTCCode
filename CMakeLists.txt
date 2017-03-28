project(TORRENT) 
set(APP_SRC 
    main.c
    bitfield.c
    bterror.c
    data.c
    log.c
    message.c
    parse_metafile.c
    peer.c
    policy.c
    sha1.c
    signal_hander.c
    torrent.c
    tracker.c)  
add_executable(torrent ${APP_SRC}) 
