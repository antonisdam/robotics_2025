# robotics_2025
Για τον διαγωνισμο ρομποτικής

## Έξυπνη τουαλέτα με προσβασιμότητα για όλους 
Το συγκεκριμένο project αποτελεί ένα σύστημα έξυπνης τουαλέτας που ενσωματώνει τρεις βασικούς αυτοματισμούς, σχεδιασμένους για να διευκολύνουν την καθαριότητα και την προσβασιμότητα.
Ο πρώτος αυτοματισμός περιλαμβάνει έναν μηχανισμό αυτόματου καθαρισμού του πατώματος. Χρησιμοποιώντας servo που κινεί μια βούρτσα, ώστε να διατηρείται ο χώρος καθαρός χωρίς ανθρώπινη παρέμβαση. Ο δεύτερος αφορά την ανύψωση και την κάθοδο ενός σκαλοπατιού μπροστά από την τουαλέτα και τον νιπτήρα ανάλογα με το ύψος του παιδιού για καλύτερη προσβασιμότητα. Τέλος, ο τρίτος αυτοματισμός περιλαμβάνει την τοποθέτηση μιας αυτόματης μπάρας στήριξης για ΑμεΑ, η οποία ενεργοποιείται μέσω αισθητήρα πίεσης κατά την είσοδο του παιδιού με αναπηρικό καροτσάκι.
Το project προάγει την  κοινωνική ευαισθησία ενώ παράλληλα  βελτιώνει  την εργασία του προσωπικού καθαριότητας και ενισχύει την προσβασιμότητα σε όλους τους μαθητές.

## Eκπαιδευτικοί στόχοι
Οι εκπαιδευτικοί στόχοι του συγκεκριμένου project συνδέονται με την ενίσχυση δεξιοτήτων STEM, την καλλιέργεια της δημιουργικότητας, και την κατανόηση των εφαρμογών της τεχνολογίας στην επίλυση πραγματικών προβλημάτων. Αναλυτικά, οι στόχοι είναι:

- Κατανόηση των βασικών αρχών αυτοματισμού: Οι μαθητές μαθαίνουν πώς λειτουργούν τα συστήματα αυτοματισμού με τη χρήση αισθητήρων, servos, και μικροεπεξεργαστών, όπως το micro:bit.
- Καλλιέργεια δημιουργικής σκέψης: Ενθαρρύνονται να σχεδιάσουν και να υλοποιήσουν καινοτόμες λύσεις, όπως το ανυψωτικό σκαλοπάτι και η μπάρα υποστήριξης.
- Ανάπτυξη δεξιοτήτων συνεργασίας:Η ομαδική εργασία για τη σχεδίαση, κατασκευή και υλοποίηση του συστήματος προάγει την επικοινωνία και τη συνεργασία.
- Εξοικείωση με τη χρήση αισθητήρων: Μαθαίνουν πώς λειτουργούν οι αισθητήρες πίεσης, υπερήχων και υγρασίας, καθώς και πώς ενσωματώνονται σε ένα ολοκληρωμένο σύστημα.
- Ενίσχυση των δεξιοτήτων προγραμματισμού: Οι μαθητές γράφουν και δοκιμάζουν κώδικα για να ελέγχουν τη λειτουργία των αισθητήρων, αποκτώντας πρακτική εμπειρία στον προγραμματισμό.
- Ενίσχυση της αναλυτικής σκέψης: Κατά τη διάρκεια του project, οι μαθητές μαθαίνουν να εντοπίζουν προβλήματα και να προτείνουν λύσεις.

 ## Αυτοματισμοί 
 
**Αυτοματισμός 1: Αυτόματος Καθαρισμός Πατώματος με Servo-Σκούπα**
 Ένα servo μοτέρ χρησιμοποιείται για την κίνηση μιας σκούπας δεξιά-αριστερά στο πάτωμα. Η σκούπα είναι τοποθετημένη σε ειδική βάση πάνω στο servo μοτέρ και ενεργοποιείται με αισθητήρα υγρασίας. Στην περίπτωση που εντοπιστεί υγρασία το σύστημα ενεργοποιείται για να καθαρίσει την περιοχή.

Οφέλη:
- Εξασφαλίζει ένα καθαρό περιβάλλον.
- Μειώνει τον φόρτο εργασίας της καθαρίστριας. Οι καθαρίστριες απαλλάσσονται από την ανάγκη συνεχούς καθαρισμού και μπορούν να εστιάσουν σε άλλες εργασίες.
- Βελτιώνει την υγιεινή, περιορίζοντας τη συγκέντρωση μικροβίων.
 
**Αυτοματισμός 2: Ανυψωτικό Σκαλοπάτι για Τουαλέτα και Νιπτήρα**
Τοποθετείται ένα γραμμικό servo κάτω από το σκαλοπάτι της τουαλέτας και του νιπτήρα. Ο μηχανισμός ενεργοποιείται μέσω ενός αισθητήρα υπερήχων που μετρά το ύψος του παιδιού. Εάν το ύψος είναι κάτω από ένα προκαθορισμένο όριο, το σκαλοπάτι ανυψώνεται  διευκολύνοντας το παιδί να φτάσει στην τουαλέτα ή στον νιπτήρα.

Οφέλη:
- Εξασφαλίζει ότι παιδιά κάθε ύψους μπορούν να χρησιμοποιήσουν την τουαλέτα και τον νιπτήρα με ασφάλεια και άνεση.
- Μειώνει τις πιθανότητες ατυχημάτων

**Αυτοματισμός 3: Μπάρα Υποστήριξης για Παιδιά ΑΜΕΑ**

**Λόγο έλλειψης χρόνου ο αυτοματισμός δεν ολοκληρώθηκε**

Στην είσοδο της τουαλέτας τοποθετείται ένας αισθητήρας πίεσης φτιαγμένος από δύο φύλλα αλουμινόχαρτου  που κλείνουν το κύκλωμα μόλις περάσει αναπηρικό καροτσάκι. Με την ανίχνευση της παρουσίας παιδιού σε καροτσάκι  μια  μπάρα υποστήριξης τοποθετημένη στο εσωτερικό της τουαλέτας ανυψώνεται αυτόματα με τη χρήση servo. Η μπάρα  επιστρέφει στην αρχική της θέση όταν το παιδί αποχωρήσει.

Οφέλη:
- Παρέχει ασφάλεια και υποστήριξη σε παιδιά με κινητικές δυσκολίες.
- Διευκολύνει τη χρήση της τουαλέτας από μαθητές με αναπηρίες, ενισχύοντας τη την ισότητα.
- Αυξάνει τη λειτουργικότητα της τουαλέτας .
 
## Σχέδια Μαθήματος για Κάθε Αυτοματισμό

**Μάθημα 1: Αυτόματος Καθαρισμός Πατώματος**
Στόχος: Κατανόηση της λειτουργίας αισθητήρα υγρασίας και servo motor.
Δραστηριότητες:
- Παρουσίαση με εικόνες και video τη χρήση του αισθητήρα.
- Σύνδεση αισθητήρα με Micro:bit και ενεργοποίηση του servo.
- Δοκιμές με νερό για ενεργοποίηση της βούρτσας.
- [Φύλλο Εργασίας 1](https://docs.google.com/document/d/1sdm02BVbbSUkw0g358ng9q4rigJcJjF-XVRmAKxGHl4/edit?usp=sharing)


**Μάθημα 2: Ανυψωτικό Σκαλοπάτι**
Στόχος: Εκμάθηση του αισθητήρα υπερήχων και της σύγκρισης τιμών απόστασης. 
Δραστηριότητες:
- Πείραμα: Μέτρηση ύψους μαθητών και ενεργοποίηση servo για σήκωμα σκαλοπατιού.
- Κωδικοποίηση if-statement για έλεγχο του ύψους.
- Δημιουργία απλής κατασκευής σκαλοπατιού.
- [Φύλλο Εργασίας 2](https://docs.google.com/document/d/1rjaHLJnZv_5QUCWn3PeGsJs3TdBJoqHylcG96Wnh_wM/edit?usp=sharing)

**Μάθημα 3: Μπάρα Στήριξης για ΑμεΑ**
Στόχος: Ευαισθητοποίηση σε θέματα προσβασιμότητας και χρήση αισθητήρα πίεσης. 
Δραστηριότητες:
- Προσομοίωση με καρότσι πάνω σε αυτοσχέδιο αισθητήρα.
- Ενεργοποίηση servo που κινεί μια μπάρα.
- Συζήτηση για τη σημασία της ισότητας.
- [Φύλλο Εργασίας 3 ](https://docs.google.com/document/d/1VSQmmJ9eTIaiGch-Cbgj9wBI72LoqiuTXY4eb6kqSHQ/edit?usp=sharing)

  
## Quiz Αξιολόγησης 

-[Ερωτήσεις  για το Project "Έξυπνη Τουαλέτα"!!!](https://wordwall.net/el/resource/86442013/%ce%b5%cf%81%cf%89%cf%84%ce%ae%cf%83%ce%b5%ce%b9%cf%82-%ce%b3%ce%b9%ce%b1-%cf%84%ce%bf-project-%ce%ad%ce%be%cf%85%cf%80%ce%bd%ce%b7-%cf%84%ce%bf%cf%85%ce%b1%ce%bb%ce%ad%cf%84%ce%b1)

-[΄Εξυπνη Τουαλέτα quiz 2](https://wordwall.net/el/resource/86512048/%ce%b5%ce%be%cf%85%cf%80%ce%bd%ce%b7-%cf%84%ce%bf%cf%85%ce%b1%ce%bb%ce%ad%cf%84%ce%b1-quiz-2)

## Συμπέρασμα
Το project αυτό ενσωματώνει καινοτόμες λύσεις για την αναβάθμιση των σχολικών τουαλετών,  συνδυάζοντας  αυτοματισμούς για να αντιμετωπίσει πρακτικά προβλήματα. Εστιάζει στη διευκόλυνση των μαθητών και στη μείωση του φόρτου εργασίας των καθαριστριών, δημιουργώντας ένα καθαρό και  ασφαλές περιβάλλον.

### Παρουσίαση Youtube
[![IMAGE ALT TEXT](https://img.youtube.com/vi/Md59bIz-bwM/1.jpg)](https://www.youtube.com/watch?v=Md59bIz-bwM "My video")
 
### Φωτογραφικό Υλικό
<img src="images/1.jpg" alt="Screenshot" width="300" height="200">
<img src="images/2.jpg" alt="Screenshot" width="300" height="200">
<img src="images/3.jpg" alt="Screenshot" width="300" height="200">
<img src="images/4.jpg" alt="Screenshot" width="300" height="200">
<img src="images/5.jpg" alt="Screenshot" width="300" height="200">
<img src="images/6.jpg" alt="Screenshot" width="300" height="200">
<img src="images/7.jpg" alt="Screenshot" width="300" height="200">
<img src="images/8.jpg" alt="Screenshot" width="300" height="200">
<img src="images/9.jpg" alt="Screenshot" width="300" height="200">
<img src="images/10.jpg" alt="Screenshot" width="300" height="200">
<img src="images/11.jpg" alt="Screenshot" width="300" height="200">
<img src="images/12.jpg" alt="Screenshot" width="300" height="200">
<img src="images/13.jpg" alt="Screenshot" width="300" height="200">
<img src="images/14.jpg" alt="Screenshot" width="300" height="200">
<img src="images/15.jpg" alt="Screenshot" width="300" height="200">
<img src="images/16.jpg" alt="Screenshot" width="300" height="200">
<img src="images/17.jpg" alt="Screenshot" width="300" height="200">
<img src="images/18.jpg" alt="Screenshot" width="300" height="200">





## Βασικός εξοπλισμός:
- Micro:bit: 19,90€
- Καλώδια σύνδεσης (Jumper wires x 3): 1,80 x3 =5,4€
- Κιτ μπαταριών: 2€
- Αισθητήρας απόστασης (Ultrasonic): 2€
- Αισθητήρας υγρασίας: 2€
- Servo motors (x2): 5€
- Linear servo ή linear actuator (x2): 8,50€
- Keyestudio Micro:bit Sensor Shield v2 10€

Σύνολο: 55€

