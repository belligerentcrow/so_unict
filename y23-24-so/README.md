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
        2. [Turni e percentuali -- garanzia di tempo in CPU](10_11-04-24_so.md#turni-e-percentuali----garanzia-di-tempo-in-cpu)