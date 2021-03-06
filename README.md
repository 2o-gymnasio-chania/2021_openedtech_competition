# 2ο Γυμνάσιο Χανίων - 3oς Πανελλήνιος Διαγωνισμός Ανοιχτών Τεχνολογιών

<p align="center">
  <img src="schediasi/yliko/feedBot_afisa.jpg" width="450" title="hover text">
</p>

## Αναλυτική περιγραφή ιδέας
Η ομάδα του σχολείου μας συγκέντρωσε συνολικά 12 [προτάσεις και ιδέες](schediasi/idees/idees.pdf) για τη συμμετοχή στον 3ο Πανελλήνιο Διαγωνισμό Ανοιχτών Τεχνολογιών στην Εκπαίδευση. Η ιδέα που επιλέχθηκε αφορά την σχεδίαση και κατασκευή του **feedBot**, ενός ρομπότ που θα προσφέρει τροφή και νερό στα ζώα. Θα μπορούσε να λειτουργήσει για κατοικίδια ζώα σε εσωτερικό χώρο κάποιου σπιτιού, αλλά και σε δημόσιο χώρο για τις ανάγκες των αδέσποτων. Το ρομπότ θα εγκαθίσταται σε ένα, εύκολα προσβάσιμο για τα ζώα, χώρο και θα εξασφαλίζει την παροχή της προβλεπόμενης ή απαραίτητης ποσότητας τροφής και νερού για να εξυπηρετούνται τα ζώα που θα το πλησιάσουν και θα το χρησιμοποιήσουν. Κάποια αρχικά σχέδια για το πως φανταζεται η ομάδα το ρομπότ feedBot είναι διαθέσιμα στο αποθετήριο της ομάδας, στη διεύθυνση:
- [https://github.com/2o-gymnasio-chania/2021_openedtech_competition/tree/main/schediasi/yliko](https://github.com/2o-gymnasio-chania/2021_openedtech_competition/tree/main/schediasi/yliko)

Στην περίπτωση της εγκατάστασής του σε εσωτερικό χώρο, για την εξυπηρέτηση κάποιου ή κάποιων κατοικίδιων, η παροχή νερού και τροφής θα είναι χρονοπρογραμματισμένη σύμφωνα με τις με τις ανάγκες των ζώων, ανάλογα με το είδος τους, τον αριθμό τους ή σύμφωνα με προδιαγραφές που θα ορίσει ο ιδιοκτήτης των κατοικίδιων. Στην περίπτωσή της εγκατάστασής του σε δημόσιο χώρο, το καθήκον του ρομπότ θα αλλάζει ώστε να διατηρεί τo δοχείo του νερού γεμάτο, σε όλη τη διάρκεια του εικοσιτετράωρου. Το δοχείο της τροφής θα τροφοδοτείται με την ανάλογη ποσότητα κάθε φορά που κάποιο ζώο θα το πλησιάσει αρκετά. Όταν τα αποθέματα τροφής ή νερού είναι μικρότερα από τα όρια ασφαλείας που έχουν οριστεί, το ρομπότ θα προειδοποιεί για την ανανέωση των αποθεμάτων. Επίσης, θα ανιχνεύεται και θα καταγράφεται ο αριθμός των ζώων που εξυπηρετήθηκαν, ώστε να υπάρχει η δυνατότητα για στατιστική επεξεργασία της διαδικασίας.

Η συλλογή και επεξεργασία των δεδομένων σύμφωνα με κανόνες για τη συχνότητα και την ποσότητα τροφής και νερού, η παρακολούθηση των αποθεμάτων και η καταγραφή της δραστηριότητας του ρομπότ συνθέτουν την **τεχνητή νοημοσύνη** του. Η Ιδέα αυτή αποτελεί έναν πολύ εύκολο τρόπο για να ελέγχεται κάθε πότε δόθηκε φαγητό και νερό, σε τις ποσότητες, και φυσικά το καλύτερο από όλα είναι ότι θα υπάρχει φροντίδα για τα κατοικίδια ακόμη και αν δεν είμαστε σπίτι.

Το ρομπότ θα αποτελείται από τα παρακάτω τμήματα:
1. ένα δοχείο για την αποθήκευση της τροφής,
2. ένα δοχείο για το τάισμα των ζώων,
3. μια βαλβίδα για τον έλεγχο της μεταφοράς τροφής από το δοχείο αποθήκευσης στο δοχείο ταΐσματος,
4. έναν ηλεκτρικό κινητήρα για τον έλεγχο της βαλβίδας τροφής,
5. μια δεξαμενή για την αποθήκευση του νερού,
6. ένα δοχείο για το πότισμα των ζώων,
7. μια βαλβίδα για τον έλεγχο της μεταφοράς νερού από τη δεξαμενή στο δοχείο ποτίσματος,
8. έναν ηλεκτρικό κινητήρα για τον έλεγχο της βαλβίδας νερού,
9. έναν αισθητήρα για τον καθορισμό του αποθέματος στο δοχείο αποθήκευσης τροφής,
10. έναν αισθητήρα για τον καθορισμό της ποσότητας της τροφής στο δοχείο ταΐσματος,
11. έναν αισθητήρα για τον εντοπισμό του ζώου σε κοντινή απόσταση από το δοχείο ταΐσματος,
11. έναν αισθητήρα για τον καθορισμό της στάθμης του νερού στη δεξαμενή,
12. έναν αισθητήρα για τον καθορισμό της στάθμης του νερού στο δοχείο ποτίσματος,
13. ένα ρομποτικό ελεγκτή Arduino για τον έλεγχο και τον προγραμματισμό του ρομπότ,
14. υλικά κατασκευής και συναρμολόγησης.

Τα ηλεκτρονικά εξαρτήματα και το λογισμικό προγραμματισμού του που θα χρησιμοποιηθούν στο ρομπότ είναι ανοιχτής τεχνολογίας.

## Λίστα προτεινόμενου εξοπλισμού
- 4 Πλαστικά δοχεία (20€)
- 2 ηλεκτρικοί κινητήρες με τα κυκλώματα οδήγησής τους (2*30€) για τον έλεγχο των βαλβίδων, [https://www.sparkfun.com/products/14450](https://www.sparkfun.com/products/14450) - [https://www.sparkfun.com/products/12367](https://www.sparkfun.com/products/12367)
- 5 αισθητήρες υπολογισμού θέσης (5*15=65€), https://www.sparkfun.com/products/15171
- 1 ρομποτικό ελεγκτή Arduino (30€), https://www.sparkfun.com/products/11021
- υλικά κατασκευής και συναρμολόγησης του ρομπότ (30€)

## Ενδεικτικό κόστος
Εντός των παρενθέσεων στη λίστα προτεινόμενου εξοπλισμού αναφέρεται το ενδεικτικό κόστος για το κάθε εξάρτημα του ρομπότ. Συνολικά, μια πρώτη εκτίμηση του κόστους είναι **200€**.

