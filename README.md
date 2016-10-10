Openway Alfresco SDK Parent
===========================

Si tratta della specializzazione per Openway del SDK Maven fornito da Alfresco.
Questo progetto ha lo scopo principale di centralizzare la gestione delle dipendenze comuni a tutti i progetti nonchè delle procedure di compilazione e gestione di un progetto.


Linee guida
-----------
*	Nell'includere dipendenze nel tag **dependencyManagement** tenere ben in considerazione che questo pom fungerà da parent sia per moduli Alfresco sia per moduli Share; questo significa che le dipendenze da includere devono essere solo quelle comuni ai due applicativi
*	Stesso principio sia per la sezione **pluginManagement** e più in generale per la sezione **build**