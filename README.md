#programma in cui viene chiesto all'utente di decidere Username e password di un sito,dopo aver deciso le credenziali, il programma chiede all'utente di effettuare un tentativo di login inserendo username e password. se le info inserite sono corrette il programma stampa "benvenuto" altrimenti il programma stampa un messaggio d'errore
nomeUtente = input("inserisci un nomeUtente:")
password = input ("inserisci una password:")
loginnomeUtente = input("reinserisci il nomeUtente")
loginpassword = input ("reinserisci la password")
if loginnomeUtente == nomeUtente and loginpassword == password :
    print ("Benvenuto")
else :
    print ("error")
