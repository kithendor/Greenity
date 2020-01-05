# Greenity - Πράσινη πόλη

##  Περιγραφή

Υλοποίηση συσκευών σε μια έξυπνη πόλη – μακέτα που θα βοηθήσουν στην εξοικονόμηση νερού, στην προστασία του περιβάλλοντος, στην διαχείριση σκουπιδιών και θα διαθέτουν ανανεώσιμες πηγές ενέργειας. Οι συσκευές θα μπορούν να τοποθετηθούν και σε σπίτια αλλά και σε δημόσιους χώρους.

### Έξυπνοι κάδοι
Οι κάδοι θα έχουν σκοπό την εξοικονόμηση χώρου, την μείωση των δρομολογίων των απορριμματοφόρων, την καθαριότητα γύρω από τον κάδο. Πιο συγκεκριμένα ο κάδος θα διαθέτει τις εξής λειτουργίες
1. θα έχει μια μεγάλη δεξαμενή μέσα στο έδαφος ώστε να εξοικονομεί χώρο.
2. Με αισθητήρα θα ανοίγει αυτόματα το καπάκι του.
3. Μετά από συγκεκριμένα «ανοίγματα», μια πλατφόρμα θα συμπιέζει τα σκουπίδια εξοικονομώντας χώρο μέσα στην δεξαμενή του κάδου.
4. Θα υπάρχουν ενδείξεις που θα δείχνουν κατά πόσο έχει γεμίσει ο κάδος ώστε να γνωρίζει και ο άνθρωπος που θέλει να πετάξει τα σκουπίδια όσο και οι οδοκαθαριστές. Με αυτό τον τρόπο θα αποφεύγονται περιττά δρομολόγια σε κάδους που δεν έχουν γεμίσει,
5. Στην περίπτωση που ο κάδος γεμίσει το καπάκι θα κλειδώνει για να μην γίνει υπερχείλιση σκουπιδιών.
6. Με δυο κουμπιά θα σηκώνεται, ή θα κατεβαίνει, η δεξαμενή για να αδειάζει στο απορριμματοφόρο.

### Δεξαμενή νερού
Μια δεξαμενή που θα γεμίζει με νερό βροχής, αφού το έχει φιλτράρει πρώτα. Η δεξαμενή θα βρίσκεται μέσα στο έδαφος. Τε νερό θα αξιοποιείται κυρίως σε ποτίσματα σε δημόσιους χώρους και όχι μόνο. Πιο συγκεκριμένα η δεξαμενή:
1.	Θα ελέγχει την στάθμη του νερού
2.	Θα μπορεί να αντλήσει το νερό από την δεξαμενή έτσι ώστε
a.	Να ποτίσει δημόσια πάρκα
i.	Τα πάρκα θα ποτίζονται μόνο όταν έχουν ανάγκη για νερό
b.	Να χρησιμοποιηθεί σε δημόσιες τουαλέτες
c.	να χρησιμοποιηθεί σε δημόσια κτήρια ακόμα και σπίτια

### Αυτόματα φώτα
αυτόματα φώτα τα οποία θα βρίσκονται τόσο μέσα στην πόλη όσο και στους κεντρικούς αυτοκινητόδρομους:
1.	θα ανάβουν ανάλογα με την φωτεινότητα του ήλιου
2.	τα φώτα σε μεγάλους αυτοκινητόδρομο θα ενεργοποιούνται μόνο όταν πλησιάζει αμάξι.
3.	Θα αντλούν ενέργεια από το φως του ήλιου την ημέρα

### Ειδοποίηση φωτιάς
Στο κοντινό δάσος της περιοχής θα υπάρχουν ειδικά αισθητήρια τα οποία θα εκτιμούν την επικινδυνότητα εκδήλωσης πυρκαγιάς. Επίσης σε περίπτωση που πιάσει φωτιά θα ειδοποιείται αυτόματα η πυροσβεστική και θα γνωρίζει ακριβός σε ποιο σημείο να μεταβεί.
1.	Αισθητήρες που θα εκτιμούν την επικινδυνότητα
2.	Αισθητήρες που θα αντιλαμβάνονται φωτιά και καπνό
3.	Θα ειδοποιεί κατευθείαν με ενδείξεις και σειρήνες

## Εξοπλισμός και ενδεικτικό κόστος


| Κατασκευή            | Εξαρτήματα         | Τιμή  | Τεμάχια | Σύνολο |
|----------------------|--------------------|-------|---------|--------|
| Βασική               | Arduino            | 9,80  | 1       | 9,80   |
|                      | Καλώδια            | 5,00  | 1       | 5,00   |
|                      | Breadboard         | 4,00  | 1       | 1,00   |
| Αυτόματα φώτα        | led                | 0,04  | 20      | 0,80   |
|                      | ldr                | 0,15  | 1       | 0,15   |
|                      | led                | 0,04  | 10      | 0,40   |
|                      | ir                 | 2,11  | 3       | 6,33   |
| Έξυπνος Κάδος        | led                | 0,04  | 3       | 0,12   |
|                      | ir                 | 2,11  | 1       | 2,11   |
|                      | servo              | 3,99  | 3       | 11,97  |
|                      | button             | 0,40  | 2       | 0,80   |
|                      | ultrasonic         | 2,00  | 1       | 2,00   |
| Δεξαμενή νερού       | αντλία             | 2,49  | 2       | 4,98   |
|                      | αισθητήρας βροχής  | 2,00  | 1       | 2,00   |
|                      | αισθητήρας χώματος | 2,48  | 2       | 4,96   |
|                      | button             | 0,40  | 2       | 0,80   |
| Ειδοποίηση Φωτιάς    | mq2                | 3,50  | 1       | 3,50   |
|                      | led                | 0,04  | 5       | 0,20   |
|                      | lm35               | 1,50  | 1       | 1,50   |
|                      | ldr                | 0,15  | 1       | 0,15   |
|                      | flame              | 2,00  | 1       | 2,00   |
| Σύνολο               |                    |       |         | 60,57  |


