# Affidabilità-Creditizia-per-il-Rilascio-della-Carta-di-Credito.
Previsione dell'affidabilità creditizia per il rilascio della carta di credito

Sei stato assunto dalla Pro National Bank come data scientist, e il tuo primo incarico consiste nel realizzare un modello in grado di stimare l'affidabilità creditizia dei clienti, al fine di aiutare il team dedicato a comprendere se accettare o meno la richiesta per il rilascio della carta di credito.

Dati forniti
Ti vengono consegnati i dati anonimizzati di clienti che hanno già ottenuto la carta di credito e ne pagano regolarmente le rate. I dati sono disponibili in un file CSV che puoi scaricare da questo indirizzo:

credit_scoring.csv

Il file credit_scoring.csv contiene le informazioni dei correntisti che hanno richiesto l’apertura di una linea di credito.

Colonne del dataset:

ID: numero identificativo del cliente

CODE_GENDER: sesso del cliente

FLAGOWNCAR: indicatore del possesso di un'automobile

FLAGOWNREALTY: indicatore del possesso di una casa

CNT_CHILDREN: numero di figli

AMTINCOMETOTAL: reddito annuale

NAMEINCOMETYPE: tipo di reddito

NAMEEDUCATIONTYPE: livello di educazione

NAMEFAMILYSTATUS: stato civile

NAMEHOUSINGTYPE: tipo di abitazione

DAYS_BIRTH: numero di giorni trascorsi dalla nascita

DAYS_EMPLOYED: numero di giorni trascorsi dalla data di assunzione (se positivo, indica il numero di giorni da quando è disoccupato)

FLAG_MOBIL: indicatore della presenza di un numero di cellulare

FLAGWORKPHONE: indicatore della presenza di un numero di telefono di lavoro

FLAG_PHONE: indicatore della presenza di un numero di telefono

FLAG_EMAIL: indicatore della presenza di un indirizzo email

OCCUPATION_TYPE: tipo di occupazione

CNTFAMMEMBERS: numero di familiari

TARGET: variabile che vale 1 se il cliente ha una elevata affidabilità creditizia (pagamento costante delle rate), 0 altrimenti.

Obiettivo
Devi realizzare un modello che preveda il target dato, ovvero la variabile TARGET che indica se il cliente ha una buona affidabilità creditizia.

Punto bonus
Se ad un cliente viene negata la carta di credito, il team deve essere in grado di fornirgli una motivazione. Questo significa che il tuo modello deve fornire delle indicazioni facilmente interpretabili.
