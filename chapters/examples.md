---
layout: page
header:
   image_fullwidth: ""
permalink: "/examples/"
show_meta: false
---

# Διαδραστικά Παραδείγματα

Σε αυτό το τμήμα μελετάμε μέσα από απλά παραδείγματα τη διάδραση του χρήστη με τον υπολογιστή. Εστιάζουμε την προσοχή μας σε ιδιότητες του διαδικτύου και ειδικά στα συστήματα εισόδου και εξόδου. Τα παραδείγματα έχουν αναπτυχθεί σε γλώσσες προγραμματισμού html, css, javascript καθώς και εξωτερικές βιβλιοθήκες.

# Κεφάλαιο: Αρχέτυπα

### Παράδειγμα εισόδου χρησιμοποιώντας  το ποντίκι

Παράδειγμα διαδραστικού κώδικα που χρησιμοποιεί το ποντίκι ως συσκευή εισόδου. Ο χρήστης μπορεί να χρησιμοποιήσει το ποντίκι για να σχεδιάσει στη λευκή επιφάνεια (canvas). 

<p data-height="350" data-theme-id="17517" data-slug-hash="MwxdgM" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/MwxdgM/'>html canvas draw</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τρποποποιήστε το παράδειγμα έτσι ώστε όταν δίνεται ως είσοδος ένα συγκεκριμένο πλήκτρο από το πληκτρολόγιο (π.χ. Space), να εκτελείται η λειτουργία reset / clear στo canvas (επαναφορά στη λευκή επιφάνεια). 

### Παράδειγμα εισόδου μέσω της συσκευής Ποντίκι

Παράδειγμα διαδραστικού κώδικα που χρησιμοποιεί το ποντίκι ως συσκευή εισόδου και δίνει ως έξοδο το ανάλογο αποτέλεσμα στην οθόνη. Για να αλλάξει η τιμή εισόδου πρέπει ο χρήστης να κυλίσει δεξιά ή αριστερά το πορτοκαλί "κουμπί ώστε να αλλάξει η τιμή εισόδου".

<p data-height="350" data-theme-id="17517" data-slug-hash="ZGVrjJ" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/ZGVrjJ/'>ZGVrjJ</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Αλλάξτε το χρώμα του αριθμού εξόδου, κάθε φορά που κινείται η μπάρα εισόδου. 

### Παράδειγμα αναπαραγωγής βίντεο χρησιμοποιώντας το ποντίκι

Παράδειγμα διαδραστικού κώδικα που χρησιμοποιεί το ποντίκι ως συσκευή εισόδου. Το βίντεο χρησιμοποιεί για την έναρξη και την παύση του το σύστημα αναπαραγωγής της υπηρεσίας Youtube 

<p data-height="350" data-theme-id="17517" data-slug-hash="yNWZwm" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/yNWZwm/'>video example</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Δημιουργείστε δικό σας σύστημα αναπαραγωγής με κουμπιά Start (εκκίνηση) και Pause (Διακοπή) τα οποία να εκτελούν τις αντίστοιχες λειτουργίες στο υπάρχον Βίντεο. Για εκκίνηση του βίντεο μπορεί να χρησιμοποιηθεί το εξής παράδειγμα κώδικα Javascript:
$(document).ready(function() {
  $('#yourNewDiv').on('click', function(ev) {
    $("#video")[0].src += "&autoplay=1";
    ev.preventDefault();
  });
});

### Παράδειγμα διαδραστικού παιχνιδιού 

Μετακίνηση αντικειμένου μέσω πληκτρολογίου (html Canvas)

<p data-height="350" data-theme-id="17517" data-slug-hash="dorEYW" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/dorEYW/'>html canvas game</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Τροποποιήστε το παράδειγμα έτσι ώστε όταν το αυτοκίνητο κινείται όπισθεν να έχει μικρότερη (τη μισή) ταχύτητα από το όταν κινείται έμπροσθεν. 

Άσκηση 2: Δημιουργείστε περιμετρικά όρια  έτσι ώστε το αυτοκίνητο να μη βγαίνει ποτέ έξω από την πίστα.

# Κεφάλαιο: Εργαλεία 

### Παράδειγμα CSS Media Queries

Παράδειγμα κώδικα με σκοπό να γίνει κατανοητή η χρήση των CSS media queries. Αλλάζοντας το μέγεθος του παραθύρου του περιηγητή (browser) σας αλλάζει το χρώμα της επιφάνειας του παραδείγματος. 

<p data-height="350" data-theme-id="17517" data-slug-hash="vOoyJG" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/vOoyJG/'>media queries example</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Πειραματιστείτε με το παράδειγμα προσθέτοντας περισσότερα CSS media queries και αλλάζοντας το χρώμα του παραθούρου. Στη συνέχεια δοκιμάστε να εφαρμόσετε CSS media queries στο μέγεθος της γραμματοσειράς ώστε να απεικονίζεται σωστά σε όλα τα μεγέθη παραθύρων.

### Παράδειγμα Μενού 1

Διαδραστικό παράδειγμα dropdown μενού χωρίς τη χρήση Javascript.

<p data-height="350" data-theme-id="17517" data-slug-hash="dorrVa" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/dorrVa/'>Simple Dropdown menu</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το παράδειγμα με τη βοήθεια των CSS3 Media Queries έτσι ώστε το μενού να γίνει responsive, λειτουργώντας κατάλληλα στα βασικά μεγέθη οθόνης.

### Παράδειγμα Μενού 2

Παράδειγμα slide μενού χωρίς ενσωματωμένες λειτουργίες.

<p data-height="350" data-theme-id="17517" data-slug-hash="LVwxER" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/LVwxER/'>Slide Menu</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το παράδειγμα αφαιρώντας τον κώδικα που δημιουργεί το μενού στη δεξιά πλευρά της σελίδας. Στη συνέχεια, πειραματιστείτε με τον preprocessor SCSS παρατηρώντας τις ομοιότητες και τις διαφορές με το κανονικό CSS.

### Παράδειγμα Μενού 3

Διαδραστικό παράδειγμα responsive μενού σε One page template χρησιμοποιώντας τη βιβιοθήκη Τwitter Βootstrap 3.0 . Στο παράδειγμα εμφανίζεται το μενού έπειτα από κύλιση του ποντικιού και υποστηρίζεται η λειτουργία αυτόματης μεταφοράς (scroll) στην ενότητα/κεφάλαιο που θα επιλέξει ο χρήστης μέσω του μενού. 

<p data-height="350" data-theme-id="17517" data-slug-hash="yNdPrJ" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/yNdPrJ/'>responsive menu</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Δημιουργείστε ένα επιπλέον στοιχείο στο μενού και κατόπιν φτιάξτε μια αντίστοιχη ενότητα/κεφάλαιο στο τέλος της σελίδας. Εφαρμόστε την λειτουργία scroll-to συνδέοντας το μενού με την καινούρια ενότητα/κεφάλαιο.

Άσκηση 2: Δημιουργείστε κουμπί στο τέλος της σελίδας. Κάθε φορά που το επιλέγει ο χρήστης να εκτελείται μεταφορά (scroll) στην πρώτη/αρχική ενότητα/κεφάλαιο.

### Παράδειγμα Μενού 4

Διαδραστικό παράδειγμα πολύπλοκου κυκλικού μενού. Με την επιλογή του κουμπιού "open" από το χρήστη, εμφανίζονται μια σειρά από πιθανές επιλογές.

<p data-height="350" data-theme-id="17517" data-slug-hash="eNwepm" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/eNwepm/'>Circular Navigation example</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το μενού κατάλληλα ώστε κατά την επιλογή του κουμπιού open να εμφανίζονται 4 και όχι 12 επιλογές.

### Παράδειγμα Μενού 5

Παράδειγμα εναλλακτικού μενού χωρίς τη χρήση Javascript. Για τη δημιουργία της διάδρασης έχει χρησιμοποιηθεί ο CSS preprocessor SCSS.

<p data-height="350" data-theme-id="17517" data-slug-hash="vOommL" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/vOommL/'>Pure CSS Circle Menu</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το παράδειγμα ενσωματώνοντας στο υπάρχον μενού περιεχόμενο της επιλογής σας. Αντί για CSS, χρησιμοποιήστε τον Preprocessor SCSS.

### Παράδειγμα Μενού 6

Παράδειγμα εναλλακτικού μενού χωρίς ενσωματωμένες λειτουργίες.

<p data-height="350" data-theme-id="17517" data-slug-hash="zGVpNR" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/zGVpNR/'>tablet menu</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Ενσωματώστε το παραπάνω μενού στο παράδειγμα "Παράδειγμα Μενού 2" αφού πρώτα αφαιρέσετε το υπάρχον μενού. Στη συνέχεια ενσωματώστε τις προϋπάρχουσες λειτου ργίες στο καινούριο μενού. Προεραιτικά χρησιμοποιήστε στο μενού τοποθέτηση fixed (position:fixed;) ώστε να φαίνεται πάντα κατά την κύλιση ή τη μεταφορά στις διάφορες ενότητες.

# Κεφάλαιο: Μοντέλα

### Παράδειγμα εφαρμογής φίλτρου σε εικόνα 

Παράδειγμα διαδραστικού κώδικα στον οποίο όταν εκτελείται από το χρήστη η λειτουργία hover (κίνηση του ποντικιού πάνω από την εικόνα στο συγκεκριμένο παράδειγμα) εφαρμόζεται το φίλτρο του αποχρωματισμού της εικόνας. 

<p data-height="350" data-theme-id="17517" data-slug-hash="VLJWMQ" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/VLJWMQ/'>image filter 1</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το παράδειγμα χρησιμοποιώντας φίλτρα εικόνας και συνδυασμούς αυτών. Παραδείγματα φίλτρων βρίσκονται ως σχόλια στην ενότητα με τον CSS κώδικα του παραδείγματος.

### Παράδειγμα αριθμομηχανής

Παράδειγμα οπτικής και λειτουργικής εξομοίωσης αριθμομηχανής. 

<p data-height="350" data-theme-id="17517" data-slug-hash="vOqewJ" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/vOqewJ/'>Apple's Calculator fork</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Τροποποιήστε το παράδειγμα έτσι ώστε κάθε φορά που επιλέγεται το σύμβολο/τελεστής "=" να τυπώνεται το αποτέλεσμα σε όποιο μέρος της σελίδας επιθυμείτε. Το επόμενο αποτέλεσμα πρέπει να τυπώνεται σε νέα σειρά.

### Παράδειγμα Διαδραστικού χάρτη 

Έυρεση τοποθεσίας χρήστη χρησιμοποιώντας το Google Maps API (https://developers.google.com/maps/?hl=en).

<p data-height="350" data-theme-id="17517" data-slug-hash="WvmOXo" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/WvmOXo/'>google maps user's Geolocation</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση: Τροποποιήστε το παράδειγμα δημιουργώντας/οπτικοποιώντας χρωμματική περίμετρο γύρω από το σημείο εντοπισμού.

### Παράδειγμα Διαδραστικού χάρτη 

Εύρεση τοποθεσίας μέσω της χρήσης φόρμας εισόδου και του Google Maps API (https://developers.google.com/maps/?hl=en).

<p data-height="350" data-theme-id="17517" data-slug-hash="XbGgZq" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/XbGgZq/'>google maps api place search</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Κάθε φορά που δίνεται ως είσοδος μια τοποθεσία αλλάζει το κέντρο του χάρτη. Τροποποιήστε το παράδειγμα έτσι ώστε κάθε φορά που αλλάζει το κέντρο του χάρτη, να φαίνεται μεγαλύτερο κομμάτι της εκάστοτε περιοχής (μείωση της τιμής zoom)

Άσκηση 2: Τροποποιήστε του προεπιλεγμένου (default) marker που χρησιμοποιείται για την εύρεση του σημείου που αναζητήσατε με ένα marker της επιλογής σας.

Άσκηση 3: Δοκιμάστε παραδείγματα απο το documentation του Google Maps API (https://developers.google.com/maps/?hl=en).

# Κεφάλαιο: Σύνθεση

### Παράδειγμα σύνθεσης διαδραστικών εικόνων

Διαδραστικό παράδειγμα εικόνων χρησιμοποιώντας την τεχνική parallax. Στο συγκεκριμένο παράδειγμα η τεχνική αυτή δημιουργεί την αίσθηση του 3d περιβαλλντος. Ο χρήστης μπορεί να περιηγηθεί στη σύνθεση χρησιμοποιώντας το ποντίκι.

<p data-height="350" data-theme-id="17517" data-slug-hash="yNmMLO" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/yNmMLO/'>GTA 5 CSS3 Parallax</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Τροποποιήστε το παράδειγμα αλλάζοντας τις υπάρχουσες εικόνες, δημιουργώντας τη δική σας θεματική σύνθεση. 

### Παράδειγμα διαδραστικού γραφήματος

Διαδραστικό παράδειγμα γραφήματος χρησιμοποιώντας τη βιβλιοθήκη d3.js/dimple.js (http://dimplejs.org/)

<p data-height="350" data-theme-id="17517" data-slug-hash="pJYmOJ" data-default-tab="result" data-user="sckarolos" class='codepen'>See the Pen <a href='http://codepen.io/sckarolos/pen/pJYmOJ/'>d3 bar chart example</a> by sckarolos (<a href='http://codepen.io/sckarolos'>@sckarolos</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

Άσκηση 1: Δημιουργείστε ένα αρχείο της επιλογής σας (πχ.: .csv,.tsv,.json κτλ) και προσθέστε στην κατάλληλη μορφή τα δεδομένα που οπτικοποιεί το παράδειγμα (πίνακας data στην ενότητα Javascript).

Άσκηση 2: Ανεβάστε το αρχείο σε μια υπηρεσία που επιτρέπει τη δωρεάν αποθήκευση αρχείων (π.χ.: Github, Dropbox).  

Άσκηση 3: Τροποποιήστε το παράδειγμα κατάλληλα ώστε να γίνεται φόρτωση και προσπέλαση των δεδομένων από το αρχείο που δημιουργήσατε.

Άσκηση 4: Προσθέστε περισσότερα δεδομένα στο αρχείο και δοκιμάστε παραδείγματα απο το documentation της βιβλιοθήκης (http://dimplejs.org/).



{% include license.html %}
