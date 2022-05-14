# Lesson: Interaction Design

### First and Last Name: Ioanna Ninou
### University Registration Number: dpsd19085
### GitHub Personal Profile: https://github.com/IoannaNi/IoannaNi.git
### Augmented Reality Personal Repository: https://ioannani.github.io/Augmented-Reality/

# Introduction

# Summary


# 1nd Deliverable
Αρχικά, έκανα εγκατάσταση στον υπολογιστή μου την εφαρμογή "GitHub"(απο το διαδύκτιο) και την "Python"(απο το Microsoft Store). Αφου έγινε η εγκατάσταση, η εφαρμογή GitHub συνχρόνισε τα αρχεία που βρίσκονταν ο φάκελος Augmented-Reality> index.html όπου και επεξεργάστηκα με την βοήθεια της εφαρμογής  "Visual Studio 2017". Ύστερα,στην γραμμή αναζήτησης, αναζήτησα το "Windows PowerShell", ελέγχω αν υπάρχει το πρόγραμμα στους συγκεκριμένους φακέλους, ώστε να μπορεί να τρέξει το πρόγραμμα σε ένα τοπικό server. Αφού προηγήθηκαν τα παραπάνω βήματα, αναζήτησα στο "Google" (στις παρακάτω πηγές) να βρω τις κατάλληλες εντολές για τα σχήματα(κύβος-υπήρχε , σφαίρα και κύλινδρος) και τα τοποθέτησα στον κώδικα. Παρομοίως, για τα χρώματα των σχημάτων, για το χιόνι και για τις φωνιτικές εντολές "START"(για να χιονίζει) και "STOP"(για να σταματήσει να χιονίζει). Τέλος, μπήκα στην εφαρμογή "GitHub" και πάτησα "Commit to main" για να ανεβάσω τον κώδικά μου.

# 2nd Deliverable
<h2>Περιληπτικά:</h2>

Αφού έψαξα και μελέτησα από το διαδίκτυο πως θα δημιουργήσω τα δικά μου pattern με το Dpsd μου. Έφτιαξα το δικό μου pattern κατέβασα την δική μου φωτογραφία και έπειτα εκτέλεσα τα κατάλληλα βήματα για να εκτελεστεί.
Ας σημειωθεί το γεγονός ότι στον προσωπικό υπολογιστή δεν μπορούσε να  πραγματοποιήθει και έτσι επέλεξα να πάω στο εργαστήριο του πανεπιστημίου, όπου και πέτυχε, χωρίς να κάνω κάποιες ιδιαίτερες αλλαγές.
Το ίδιο έγινε και με τα patterns του  υδρογόνου και του οξυγόνου. Έφτιαξα στο blender δύο σφαίρες για το υδρογόνο και του οξυγόνου αντίστοιχα. Τέλος τα αποθήκευσα σε αρχείο gltf και με τις κατάλληλες συμβουλές από διαδίκτυο και συμφοιτητές από τα σχόλια στο github βρήκα τις κατάλληλες εντολές και εκτελέστηκαν. Στα παρακάτω λινκς βρίσκονται όλα αυτά που βρήκα.


<h2>Αναλυτικά:</h2>

-Για το πρώτο σκέλος, αρχικά εφτιαξά το μαρκερ μου με το dpsd μου στην ιστοσελιδα του AR.Js. Το αποθήκευσα σε .png και .patt αρχείο και το ανέβασα στον φάκελο assets marker bases στο GitHub. Ύστερα έφτιαξα στον κώδικα το περιεχόμενο που θα εμφανίζεται με το που δει το μαρκερ,  δλδ το το ονοματεπώνυμό μου με την εντολή ( <a-text value=" NINOU ") .... Την θέση που θα πάει το κείμενο και την καταλληλη περιστροφή και τέλος το χρώμα του ( position="0.5 0.9 0.8" rotation="-90 0 0" color="#F31A78"></a-text>).
Επέλεξα και κατέβασα απο το διαδίκτυο μια φωτογραφία και την εισήγαγα με την εξής εντολή: <a-image src="./assets/PINK.png" </a-image> ...  έκανα κάποιες επεξεργασίες όπως τις διαστάσεις που θα έχει, την  θέση που θα πάει η εικόνα και την κατάλληλη περιστροφή (width="1"  height="1" rotation="90 -180 0" position="0 0 0"> ). 
Για να βεβαιωθώ οτι δουλεύει χρησιμοποίησα την μάρκα του "hiro" και μέτα εβαλα το δικό μου marker.
- Για το δεύτερο σκέλος, έκανα τα ιδια βήματα με το πρώτο με την μόνη διαφορά το animation. Για το animation ακολούθησα την εξής πορεία: έφτιαξα στο BLENDER τρία 3D σχήματα που αντιστοιχουν στο υδρογόνο, οξυγόνο και στο νερό. Η καινούργια εντολή που χρησιμοποίησα ήταν: ( <a-entity position="0 1 0" rotation="0 90 0" scale="0.3 0.3 0.3" gltf-model="#cardO_Model"         animation__rotate = "property: rotation; dur: 5000; easing: linear; dir: normal; from:0 0 0; to: 360 0 0; loop: true;" ></a-entity>), οπου η εντολή gltf-model="#cardO_Model"  εισάγει το σχέδιο και animation__rotate = "property:....... κάνει την κίνηση του animation. 
- Για το τρίτο σκέλος, ως και το δυσκολότερο έπειτα απο την έρευνα μου στο διαδίκτυο βρίκα τον κώδικα και εκανα τις κατάλληλες αλλαγές, όπως να καλεί τα σωστά ονοματά των μαρκών και των animations, για να μπορει να κάει τις κατάλληλες πράξεις για τον υπολογισμό της απόστασης και την εμφάνισει του νερού. 
 



# 3rd Deliverable 


# Conclusions


# Sources
https://aframe.io/docs/1.3.0/primitives/a-cylinder.html
https://www.w3schools.com/colors/colors_picker.asp
https://www.npmjs.com/package/aframe-particle-system-component?fbclid=IwAR29byyScaq9VeemROUoqlyEo1IgXibOoHF4263zTlIQrlOsq6tDzfc1bUc

Πως να βάλω το δικο μου μαρκερ
https://medium.com/arjs/how-to-create-your-own-marker-44becbec1105

 AR.js
https://ar-js-org.github.io/AR.js/three.js/examples/marker-training/examples/generator.html?fbclid=IwAR1Tt-xJdxudhhN9QcGTMJCXoq0Z0ANwpf3yueMcPnKdaG6aEM85z0j83t4

Η φωτογραφία PINK
https://www.google.com/search?q=pink+aesthetic+image&sxsrf=ALiCzsZ5GB5iXSLorS5UetqY7B5LzIL7Mw:1652210711092&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiVj53E1NX3AhXESvEDHR-sDgkQ_AUoAXoECAEQAw&biw=1536&bih=722&dpr=1.25#imgrc=0v4_B1G7CCu1aM

#gltf-model#
https://aframe.io/docs/1.3.0/components/gltf-model.html#sidebar~
https://threejs.org/docs/#examples/en/loaders/GLTFLoader
https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564

#animation
https://www.youtube.com/watch?v=_C2ClFO3FAY

#apostasi#
https://stackoverflow.com/questions/61239107/how-to-get-marker-position-x-y-ar-js
