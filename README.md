# Line-follower-Robot-Omada_1-Embedded-Systems
'Ατομα που εργάστηκαν:
  -Λαπαρίδης Ανέστης
  -Φαμπιάν Τίλα
  -Λουκοβίτης Αθανάσιος
  -Ζαφείρης Γκέχος

1. ΕΙΣΑΓΩΓΗ
Παρουσιάζεται ένα αυτόνομο όχημα ακολουθίας γραμμής (line follower), το οποίο χρησιμοποιεί αισθητήρες για να ανιχνεύει και να ακολουθεί 
μια προκαθορισμένη διαδρομή σε μια επιφάνεια. 

2. ΑΛΓΟΡΙΘΜΟΣ
Περιγραφή Λειτουργίας:
Η λειτουργία του ρομπότ στηρίζεται σε πέντε αισθητήρες που ανιχνεύουν την παρουσία της γραμμής.
Οι αισθητήρες είναι τοποθετημένοι στο κάτω μέρος του ρομπότ και παρέχουν δεδομένα σχετικά με τη θέση της γραμμής ψηφιακά (0 ή 1).
Γίνεται χρήση PDI ελεγκτή.

Λειτουργία Αλγορίθμου:
Εισαγωγή Δεδομένων: Διαβάζονται οι τιμές από τους αισθητήρες.
Ανάλυση Δεδομένων: Αξιολογούνται οι τιμές για να καθοριστεί η θέση της γραμμής σε σχέση με το ρομπότ.
Εκτέλεση Κινήσεων: Ανάλογα με τις τιμές των αισθητήρων εκτελούνται οι αντίστοιχες κινήσεις:
  1)Εμπρός (move)
  2)Αριστερή στροφή (turn_l)
  3)Δεξιά στροφή (turn_r)
  4)Σταμάτημα (stop)

3. ΚΑΤΑΣΚΕΥΗ
Περιγραφή:
Το ρομπότ αποτελείται από το σασί, τους κινητήρες και τα ηλεκτρονικά εξαρτήματα.
Το σασί είναι κατασκευασμένο από ανθεκτικό υλικό και διαθέτει αρκετό χώρο για την τοποθέτηση των εξαρτημάτων.

Διαστάσεις:
Μήκος: 23cm
Πλάτος: 16cm
Υψος: 6.5cm

Κινητήρες:
Χρησιμοποιούνται δύο DC κινητήρες για την κίνηση του ρομπότ, οι οποίοι είναι ελεγχόμενοι μέσω PWM (Pulse Width Modulation).

Ηλεκτρονικά:
Χρησιμοποιήθηκε ο μικροελεγκτής Maker Pi RP2040. Οι αισθητήρες γραμμής είναι τοποθετημένοι στο μπροστινό μέρος του ρομπότ.

4. ΑΠΟΤΕΛΕΣΜΑΤΑ
Αξιολόγηση:
  Το ρομπότ λειτουργεί ικανοποιητικά, ακολουθώντας με ακρίβεια τη γραμμή και προσαρμόζοντας την ταχύτητά του ανάλογα με τις συνθήκες. Ανταποκρίθηκε πλήρως στις απαιτήσεις του μαθήματος, παρουσιάζοντας καλή απόδοση κατά   τις δοκιμές.

Βελτιώσεις:
  Προτείνεται η προσθήκη περισσότερων αισθητήρων και η βελτίωση της λογικής κίνησης για μεγαλύτερη ακρίβεια στις στροφές και αύξηση της ταχύτητας.

5. LESSONS LEARNED(ΠΑΘΗΜΑΤΑ-ΜΑΘΗΜΑΤΑ)
Απο την εργασία κατανοήσαμε τη σημασία της σωστής σχεδίασης και υλοποίησης ενός ρομποτικού συστήματος, συμπεριλαμβανομένης της επιλογής κατάλληλων αισθητήρων και κινητήρων.
Επίσης, κατανοήσαμε τη σημασία της διαρκούς βελτίωσης και προσαρμογής του συστήματος με βάση τις ανάγκες και τις αλλαγές του περιβάλλοντος.
Τέλος, διαπιστώσαμε πως η ανάπτυξη ενός έργου που περιλαμβάνει ευαίσθητα εξαρτήματα πρέπει να γίνεται σε ένα ελεγχόμενο και ασφαλές περιβάλλον, προς αποφυγή ατυχημάτων και καταστροφής του υλικού.
