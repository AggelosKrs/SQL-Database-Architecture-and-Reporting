CREATE TABLE ΕΠΙΛΕΓΕΙ (
	/*Παρατηρούμε ότι το μέγεθος των δεδομένων δεν ορίζετε στην sqlite*/
    "ΚωδικόςΧρήστη" INTEGER NOT NULL,
    "ΚωδικόςΡύθμισης" INTEGER NOT NULL,
    "Ενεργή" INTEGER,
    "Σχόλιο" TEXT,
    /* Ορίζουμε ΕΝΑ Primary Key που αποτελείται από δύο στήλες */
    PRIMARY KEY ("ΚωδικόςΧρήστη", "ΚωδικόςΡύθμισης"),
    /* Ορίζουμε τα Foreign Keys χωρίς κόμμα πριν το REFERENCES */
    FOREIGN KEY ("ΚωδικόςΧρήστη") REFERENCES ΧΡΗΣΤΗΣ ("ΚωδικόςΧρήστη"),
    FOREIGN KEY ("ΚωδικόςΡύθμισης") REFERENCES ΡΥΘΜΙΣΗ ("ΚωδικόςΡύθμισης")
);

