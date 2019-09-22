# Server-in-C
Programming with C through Ubuntu with an Axis network camera - Malmö University

Malmö    University,    
Faculty    of    Technology    and    Society,   

Department    of    Computer    Science

Assignment    1

Client-­‐server system


In    this    assignment,    you    should    learn    about    distributed    architectures.    
In    particular,    you    will    constructa    client-­‐server    basedsystem,    where    a    
camera    operates    as    a    server,    which    sends    images    to    a    client    running    
on    your    desktop    computer.    


In    this    assignment    you    should    build    a    client-­‐server    system,    
which    includes    one    server    application    running    on    the    axis    camera    
and    one    client    application    running    on    your    desktop    computer    (Ubuntu    system).    
The    main    functionality    of    your    system    is    that    the    server    should    capture    
and    sendimages    that    should    bedisplayed    by    the    client.    


Yourserver    application    should    be    an    ACAP    application    that    you    should    
install    and    run    on    one    of    the    six    cameras    used    in    this    assignment.    
Your    server    application    should,    at    least,    be    able    to:

•Manageconnections    with    multiple    clients;    on    request    from    the    clients.        

•Capture    imagesfrom    an    image    stream.

•Send    images    to    the    connected    clients,where    it    should    be    able    
to    send    images    with    differentresolutions    andfrequenciesto    different    clients.    
The    clients    determine the    resolutions    and    frequencies.    


Yourclientapplication,    which    should    run    on    your    desktop    computer,    
should,    at    least,    be    able    to:

•Manage    a    connection    with    yourserver.

•Allow    the    user    to    specify    the    IP    address    and    port    of    
the    server    (i.e.,    thecamera).

•Allow    the    user    to    specifythe    resolution    of    the    captured    images    
and    the    frequency(frame    rate)with    which    the    server    should    send    
imagesto    the    client.•Display    the    images    communicated    by    the    server,    
where    the    most    recent    image    should    always    be    shown.
Hence,    the    
stream    of    received    images    should    bedisplayed    as    a    streaming    movie.
Your    are    allowed    to    develop    yourclient    in    any    programming    language    
you    prefer,    and    which    you    are    able    to    install    into your    
Ubuntu    system.    The    recommended    programming    languagefor    the    client    is Java.


