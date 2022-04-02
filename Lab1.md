 
    var1 = "Hello\tWorld!
    print(var1)
    
    >>>Hello  World!
 
'r' przed łańcychem znaków ignoruje znak ucieczki
    var2 = r"Hello\tWorld!"
    print(var2)
    
    >>>Hello\tWorld!
    
'f' przed łańcychem znaków pozwala na formatowanie(wywołanie funkcji format())
    var_ = "World"
    var3 = f"Hello {var_}!"
    print(var3)
    
     >>>Hello  World!
