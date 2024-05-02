# Table of contents

---

cerca markdown lint nel marketplace vscode

---

1. [**Lezione 1**](./01_05-03-24_so.md)<br>
    1. [Esame](#esame)<br>
    2. [Sistemi Operativi](01_05-03-24_so.md#sistemi-operativi)<br>
        1. [Cos'e' un Sistema Operativo](01_05-03-24_so.md#cose-un-sistema-operativo)
        2. [Interfaccia Hardware <-> SO e Astrazioni](01_05-03-24_so.md#interfaccia-hardware---so-e-astrazioni)<br>
        3. [Gestione delle risorse](01_05-03-24_so.md#gestione-delle-risorse)<br>
        4. [Evoluzione dei SO](01_05-03-24_so.md#evoluzione-dei-sistemi-operativi)<br>
    3. [Hardware](01_05-03-24_so.md#hardware)<br>
        1. [CPU](01_05-03-24_so.md#cpu---il-processore)<br><br>
    
2. [**Lezione 2**](./02_07-03-24_so.md)<br>
    1. [Ciclo di fetch-decode-execute](02_07-03-24_so.md#ciclo-di-fetch---decode---execute)<br>
    2. [Syscalls](02_07-03-24_so.md#syscall)<br>
    3. [Interrupts](02_07-03-24_so.md#interrupt-hardware)<br>
    4. [Processori](02_07-03-24_so.md#processori)<br>
        1. [Multithreading](02_07-03-24_so.md#multi-threading)<br>
        2. [Multicore](02_07-03-24_so.md#multi-core)<br>
        3. [GPU](02_07-03-24_so.md#gpu)<br>
    5. [Memorie](02_07-03-24_so.md#memorie)<br>
        1. [Registri](02_07-03-24_so.md#1---registri)
        2. [Cache](02_07-03-24_so.md#2---cache-della-cpu)
        3. [Memoria Centrale](02_07-03-24_so.md#3---memoria-centrale)
        4. [Disco Elettronico](02_07-03-24_so.md#4---disco-elettronico)
        5. [Disco Elettromagnetico](02_07-03-24_so.md#5---disco-elettromagnetico)
        6. [Notazione memoria](02_07-03-24_so.md#notazione)
    6. [Dispositivi Input-Output](02_07-03-24_so.md#dispositivi-di-io)  <br><br>

  
3. [**Lezione 3**](03_12-03-24_so.md#3-lezione----sistemi-operativi)
    1. [Dispositivi di I/O](03_12-03-24_so.md##dispositivi-di-io)
        1. [Esempio: richiesta di lettura/scrittura su disco](03_12-03-24_so.md##esempio-richiesta-di-letturascrittura-su-disco)
            1. [DMA](03_12-03-24_so.md##dma)
            2. [Bus](03_12-03-24_so.md##bus)
    2. [Progettazione di sistemi operativi](03_12-03-24_so.md##progettazione-di-sistemi-operativi)
        1. [Mainframe/server](03_12-03-24_so.md##mainframeserver)
        2. [Personal computer](03_12-03-24_so.md#personal-computers)
        3. [Palmari / Smartphones](03_12-03-24_so.md#palmarismartphone)
        4. [Sistemi embedded](03_12-03-24_so.md#sistemi-integratiembedded)
        5. [Real-Time](03_12-03-24_so.md#realtime)
    3. [Strutture di sistemi operativi](03_12-03-24_so.md#strutture-di-sistemi-operativi)
        1. [Struttura monolitica](03_12-03-24_so.md#struttura-monolitica)
        2. [Struttura a strati/livelli](03_12-03-24_so.md#struttura-a-strati--a-livelli)
        3. [Microkernel](03_12-03-24_so.md#microkernel)
        4. [Struttura a moduli](03_12-03-24_so.md#struttura-a-moduli)
        5. [Macchine Virtuali](03_12-03-24_so.md#macchine-virtuali)
            1. [Simulazione](03_12-03-24_so.md#simulazione)
            2. [Para-virtualizzazione](03_12-03-24_so.md#para-virtualizzazione)<br><br>

4. [**Lezione 4**](04_14-03-24_so.md#4-lezione----sistemi-operativi)
    1. [Processi](04_14-03-24_so.md#processi)
        1. [PCB - Process Control Block](04_14-03-24_so.md#pcb-process-control-block)
    2. [Modello dei processi](04_14-03-24_so.md#modello-dei-processi)
        1. [Creazione e terminazione dei processi](04_14-03-24_so.md#creazione-e-terminazione-dei-processi)
            1. [Creazione](04_14-03-24_so.md#creazione)
            2. [Terminazione (volontaria o involontaria)](04_14-03-24_so.md#terminazione)
    3. [Stato di un processo](04_14-03-24_so.md#stato-di-un-processo)
        1. [Prelazione](04_14-03-24_so.md#prelazione)<br><br>

5. [**Lezione 5**](05_19-03-24_so.md#5-lezione----sistemi-operativi)
    1. [Stato dei processi](05_19-03-24_so.md#stato-dei-processi)
        1. [Coda dei processi pronti](05_19-03-24_so.md#coda-dei-processi-pronti)
    2. [Thread](05_19-03-24_so.md#thread)
        1. [Web Browser](05_19-03-24_so.md#web-browser)
        2. [Word Processor](05_19-03-24_so.md#word-processor)
        3. [Web Server](05_19-03-24_so.md#web-server)
    3. [Thread pt.2](05_19-03-24_so.md#thread-pt2)
        1. [Operazioni legate ai threads](05_19-03-24_so.md#operazioni-legate-ai-threads)
    4. [Programmazione multicore](05_19-03-24_so.md#programmazione-multicore)
        1. [Thread a livello utente](05_19-03-24_so.md#thread-a-livello-utente)
            1. [Modello a thread kernel (1-a-1)](05_19-03-24_so.md#modello-a-thread-kernel-1-a-1)
            2. [Modello dei thread livello utente (1-a-molti)](05_19-03-24_so.md#modello-dei-thread-livello-utente-1-a-molti)<br><br>

6. [**Lezione 6**](06_21-03-24_so.md#6-lezione----sistemi-operativi)
    1. [Threads](06_21-03-24_so.md#threads)
    2. [Modello ibrido (molti-a-molti)](06_21-03-24_so.md#modello-ibrido-molti-a-molti)
    3. [Thread nei sistemi operativi](06_21-03-24_so.md#thread-nei-sistemi-operativi)
    4. [Comunicazione tra processi](06_21-03-24_so.md#comunicazione-tra-processi)
        1. [Race condition](06_21-03-24_so.md#race-condition)
        2. [Condizioni critiche e soluzioni](06_21-03-24_so.md#condizioni-critiche-e-soluzioni)<br><br>

7. [**Lezione 7**]()<br><br>

8. [**Lezione 8**](08_04-04-24_so.md#8-lezione----sistemi-operativi)
    1. [Recap lezione precedente](08_04-04-24_so.md#recap-lezione-precedente)
    2. [Mutex e Thread utente](08_04-04-24_so.md#mutex-e-thread-utente)
    3. [Futex](08_04-04-24_so.md#futex)
    4. [Monitor (alternativa ai semafori)](08_04-04-24_so.md#monitor-alternativa-ai-semafori)
    5. [Meccanismo di sincronizzazione : Variabili condizione](08_04-04-24_so.md#meccanismo-di-sincronizzazione--variabili-condizione)
    6. [Scambio messaggi tra processi](08_04-04-24_so.md#scambio-messaggi-tra-processi)
    7. [Problema dei 5 filosofi](08_04-04-24_so.md#problema-dei-5-filosofi)
        1. [Soluzione dei semafori](08_04-04-24_so.md#soluzione-dei-semafori)
        2. [Soluzione con i monitor](08_04-04-24_so.md#soluzione-con-i-monitor)<br><br>

9. [**Lezione 9**](09_09-04-24_so.md#9-lezione----sistemi-operativi)
    1. [Recap](09_09-04-24_so.md#recap)
    2. [Problema dei Lettori-Scrittori](09_09-04-24_so.md#problema-dei-lettori-scrittori)
        1. [Soluzione 1: Semafori](09_09-04-24_so.md#soluzione-1-semafori)
        2. [Soluzione 2 : Monitor](09_09-04-24_so.md#soluzione-2--monitor)
            1. [Modifica per equita' tra scrittura e lettura](09_09-04-24_so.md#modifica-per-equita-tra-scrittura-e-lettura)
            2. [Modifica per favorire gli scrittori](09_09-04-24_so.md#modifica-per-favorire-gli-scrittori)
    3. [Scheduling](09_09-04-24_so.md#scheduling)
        1. [Categorizzazione:  Processi CPU-bounded vs IO bounded](09_09-04-24_so.md#categorizzazione--processi-cpu-bounded-vs-io-bounded)
            1. [Cpu-bounded](09_09-04-24_so.md#cpu-bounded)
            2. [IO Bounded](09_09-04-24_so.md#io-bounded)
        2. [Context Switch](09_09-04-24_so.md#context-switch)
    4. [Obbiettivi e metriche degli Algoritmi di Scheduling](09_09-04-24_so.md#obbiettivi-e-metriche-degli-algoritmi-di-scheduling)
        1. [Obbiettivi comuni](09_09-04-24_so.md#obbiettivi-comuni)
            1. [Equita' e Bilanciamento nell'uso delle risorse](09_09-04-24_so.md#equita-e-bilanciamento-nelluso-delle-risorse)
        2. [Sistemi batch](09_09-04-24_so.md#sistemi-batch)
        3. [Sistemi interattivi](09_09-04-24_so.md#sistemi-interattivi)
        4. [Sistemi real-time](09_09-04-24_so.md#sistemi-real-time)
    5. [Scheduling nei sistemi batch](09_09-04-24_so.md#scheduling-nei-sistemi-batch)<br><br>

10. [**Lezione 10**](10_11-04-24_so.md#10-lezione----sistemi-operativi)
    1. [Recap](10_11-04-24_so.md##recap)
    2. [Shortest Job First -- Scheduling per Brevita'](10_11-04-24_so.md##shortest-job-first----scheduling-per-brevita)
    3. [Shortest Remaining Time Next](10_11-04-24_so.md##shortest-remaining-time-next)
    4. [Scheduling Round-Robin](10_11-04-24_so.md##scheduling-round-robin)
        1. [Sistemi interattivi e priorita'](10_11-04-24_so.md##sistemi-interattivi-e-priorita)
    5. [Aging](10_11-04-24_so.md##aging)
    6. [Scheduling a code multiple](10_11-04-24_so.md##scheduling-a-code-multiple)
        1. [Quanti di tempo e priorita'](10_11-04-24_so.md##quanti-di-tempo-e-priorita)
        2. [Turni e percentuali -- garanzia di tempo in CPU](10_11-04-24_so.md#turni-e-percentuali----garanzia-di-tempo-in-cpu)<br><br>

11. [**Lezione 11**](11_16-04-24_so.md#11-lezione----sistemi-operativi)
    1. [Shortest Process Next (SPN)](11_16-04-24_so.md#shortest-process-next-spn)
    2. [Scheduling nei sistemi interattivi](11_16-04-24_so.md#scheduling-nei-sistemi-interattivi)
        1. [Scheduling Garantito](11_16-04-24_so.md#scheduling-garantito)
        2. [Scheduling a lotteria](11_16-04-24_so.md#scheduling-a-lotteria)
        3. [Scheduling Fair-Share](11_16-04-24_so.md#scheduling-fair-share)
    3. [Scheduling dei thread](11_16-04-24_so.md#scheduling-dei-thread)
    4. [Scheduling su Sistemi Multiprocessore](11_16-04-24_so.md#scheduling-su-sistemi-multiprocessore)
        1. [Multielaborazione asimmetrica](11_16-04-24_so.md#multielaborazione-asimmetrica)
        2. [Multielaborazione simmetrica](11_16-04-24_so.md#multielaborazione-simmetrica)
        3. [Migrazione spontanea](11_16-04-24_so.md#migrazione-spontanea)
    5. [Cosa usano i sistemi operativi moderni?](11_16-04-24_so.md#cosa-usano-i-sistemi-operativi-moderni)
        1. [Windows](11_16-04-24_so.md#windows)
        2. [Linux](11_16-04-24_so.md#linux)
            1. [Coda dei processi pronti:](11_16-04-24_so.md#coda-dei-processi-pronti)
            2. [Incremento](11_16-04-24_so.md#incremento)
            3. [Overflow](11_16-04-24_so.md#overflow)
            4. [Priorita'](11_16-04-24_so.md#priorita)
        3. [MacOS](11_16-04-24_so.md#macos)<br><br>

12. [**Lezione 12**](12_18-04-24_so.md#12-lezione----sistemi-operativi)
    1. [Memoria](12_18-04-24_so.md#memoria)
        1. [Memoria centrale e processi](12_18-04-24_so.md#memoria-centrale-e-processi)
        2. [Modello 2](12_18-04-24_so.md#modello-2)
        3. [Modello 3](12_18-04-24_so.md#modello-3)
    2. [Sistema Multiprogrammato -- Multiprogrammazione senza astrazione](12_18-04-24_so.md#sistema-multiprogrammato----multiprogrammazione-senza-astrazione)
        1. [Rilocazione](12_18-04-24_so.md#rilocazione)
        2. [Protezione della memoria](12_18-04-24_so.md#protezione-della-memoria)
        3. [Spazio degli indirizzi](12_18-04-24_so.md#spazio-degli-indirizzi)
    3. [Swapping](12_18-04-24_so.md#swapping)
        1. [Frammentazione esterna e interna](12_18-04-24_so.md#frammentazione-esterna-e-interna)
    4. [Gestione dell'allocazione](12_18-04-24_so.md#gestione-dellallocazione)
        1. [Bitmap](12_18-04-24_so.md#bitmap)
        2. [Lista dinamica dei blocchi liberi e occupati](12_18-04-24_so.md#lista-dinamica-dei-blocchi-liberi-e-occupati)
        3. [Ordinata per indirizzo](12_18-04-24_so.md#ordinata-per-indirizzo)
            1. [First fit](12_18-04-24_so.md#first-fit)
            2. [Next fit](12_18-04-24_so.md#next-fit)
            3. [Best fit](12_18-04-24_so.md#best-fit)
            4. [Worst fit](12_18-04-24_so.md#worst-fit)<br><br>

13. [**Lezione 13**](13_23-04-24_so.md#13-lezione----sistemi-operativi)
    1. [Memoria virtuale](13_23-04-24_so.md#memoria-virtuale)
        1. [Spazio di indirizzamento virtuale](13_23-04-24_so.md#spazio-di-indirizzamento-virtuale)
        2. [Page fault / miss](13_23-04-24_so.md#page-fault--miss)
    2. [Paginazione](13_23-04-24_so.md#paginazione)
    3. [Una voce della tabella delle pagine](13_23-04-24_so.md#una-voce-della-tabella-delle-pagine)
        1. [Numero del frame](13_23-04-24_so.md#numero-del-frame)
        2. [bit presente/assente](13_23-04-24_so.md#bit-presenteassente)
        3. [Protezione (lettura e scrittura)](13_23-04-24_so.md#protezione-lettura-e-scrittura)
        4. [Bit modificato (Dirty Bit)](13_23-04-24_so.md#bit-modificato-dirty-bit)
        5. [Bit referenziato](13_23-04-24_so.md#bit-referenziato)
        6. [Bit per disabilitare la cache](13_23-04-24_so.md#bit-per-disabilitare-la-cache)
        7. [Bit di validita' o allocazione](13_23-04-24_so.md#bit-di-validita-o-allocazione)<br><br>

14. [**Lezione 14**](14_30-04-24_so.md#14-lezione----sistemi-operativi)
    1. [Recap -- Tabella delle pagine](14_30-04-24_so.md#recap----tabella-delle-pagine)
        1. [Bit di Referenziamento](14_30-04-24_so.md#bit-di-referenziamento)
        2. [Bit per disabilitare la cache](14_30-04-24_so.md#bit-per-disabilitare-la-cache)
        3. [Bit di validita' o allocazione](14_30-04-24_so.md#bit-di-validita-o-allocazione)
    2. [Tabella dei frames](14_30-04-24_so.md#tabella-dei-frames)
        1. [Progettazione di una tabella delle pagine](14_30-04-24_so.md#progettazione-di-una-tabella-delle-pagine)
        2. [Memoria associativa  / TLB -- translation lookup buffer](14_30-04-24_so.md#memoria-associativa---tlb----translation-lookup-buffer)
            1. [Come evitiamo l'azzeramento della TLB al context switch?](14_30-04-24_so.md#come-evitiamo-lazzeramento-della-tlb-al-context-switch)
        3. [Effective Access Time (EAT)](14_30-04-24_so.md#effective-access-time-eat)
    3. [Tabella delle pagine multilivello](14_30-04-24_so.md#tabella-delle-pagine-multilivello)