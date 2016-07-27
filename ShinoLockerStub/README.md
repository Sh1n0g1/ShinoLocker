#ShinoLockerStub

    +-------------------------------------------------------------+
    |   _____ _     _             _                _              |
    |  / ____| |   (_)           | |              | |             |
    | | (___ | |__  _ _ __   ___ | |     ___   ___| | _____ _ __  |
    |  S___ H| '_ I| | '_ N / _ L| |    / _ C / __| |/ / _ | '__| |
    |  ____) | | | | | | | | (_) | |___| (_) | (__|   |  __| |    |
    | |_____/|_| |_|_|_| |_|O___/|______O___/ K___|_|E_R___|_|    |
    +-------------------------------------------------------v.1.0-+
    
    Usage: ShinoLockerStub <E|D> <KEY> <IV> <FILEPATH>
    <E|D>                D to decrypt, E to encrypt.
    <KEY>                AES key (Base64)
    <IV>                 AES IV  (Base64)
    <FILEPATH>           File to encrypt/decrypt
    
    All parameters are mandatory and the order is stricted.
    
    Example:
    ShinoLockerStub E VEFLRVNISVRFU0hJR0FXQQ== UkFUQUtFU0hJVEVTSElHQQ== C:\file.txt
