# eprobotkeysnoedit_alx
Βασικός Προγραμματισμός Ρομπότ - Fork της εφαρμογής του Φωτόδενδρου

Στο φωτόδενδρο, υπάρχει μια πολύ ωραία εφαρμογή βασικού προγραμματισμού με βελάκια για μαθητές Δημοτικού μικρών τάξεων.

Με δεδομένο ότι η άδεια της εφαρμογής επιτρέπει remixes, αποφάσισα να κάνω μια σειρά από αλλαγές / προσθήκες / μετατροπές που θα ήθελα να έχει η εφαρμογή βασικού προγραμματισμού που χρησιμοποιώ στις τάξεις όπου διδάσκω.

## Αλλαγές που υλοποιήθηκαν σε σχέση με την αρχική έκδοση

(0) Ανοίγοντας η εφαρμογή / σελίδα, υπάρχει ως προεπιλογή το δάπεδο (mat) με την αλφαβήτα αντί του κενού. Να μην χρειάζεται δηλαδή να αλλάξουν οι μαθητές χειροκίνητα το δάπεδο (mat) ώστε να κερδίσουμε χρόνο και να μειώσουμε τον διδακτικό θόρυβο.

(1) H περιοχή όπου τοποθετούνται οι οδηγίες – βελάκια που δίνουν οι μαθητές στην πασχαλίτσα είναι κάτα κάποιο τρόπο “οριοθετημένη”, δηλαδή να υπάρχουν σαφώς ορισμένα τετραγωνάκια μέσα στο οποία στοιβάζονται τα βελάκια. 

(2) Όταν οι μαθητές κάνουν κλικ σε ένα από τα 4 βελάκια (μπρος, πίσω, δεξιά ή αριστερά) αυτό να μπαίνει μέσα στο κατάλληλο τετραγωνάκι θέσης και να εμφανίζεται και ένας αύξων αριθμός εντολής, ώστε να καταλαβαίνουν με μια ματιά με ποιά σειρά θα εκτελεστούν οι εντολές – βελάκια και σε ποιά θέση θα μπει η επόμενη εντολή – βελάκι.

(3) Προσθήκη challenges για το βασικό δάπεδο mat. Ο στόχος κάθε challenge, είναι να πάει η πασχαλίτσα σε ένα γράμμα της αλφαβήτας. Ο στόχος δίνεται στο URL ως argument. Πχ για παιχνίδι με στόχο να φτάσει η πασχαλίτσα στο γράμμα Π το url είναι το [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Π](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Π). Αντίστοιχα για το γράμμα Ξ, [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ξ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ξ) κ.ο.κ. Αν ο μαθητής φτιάξει σωστές οδηγίες και καταλήξει στο επιθυμητό γράμμα, βλέπει ένα μικρό "χαρούμενο" animation από την πασχαλίτσα, σε διαφορετική περίπτωση υπάρχει ένα "λυπημένο" animation. 

(4) Αφαίρεση του κουμπιού pause και ενσωμάτωση του κουμπιού διαγραφή ενός (delete1) και προσθήκη συνάρτησης στο αρχείο [activity.js](activity.js) υλοποιεί τη διαγραφή της τελευταίας οδηγίας-βελάκι προς την πασχαλίτσα.

Η εφαρμογή είναι διαθέσιμη [εδώ](https://ale3andro.github.io/eprobotkeysnoedit_alx/)

Λίστα συνδέσμων με τα challenges της πασχαλίτσας:

Στόχος να φτάσει στο γράμμα Α | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Α](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Α)

Στόχος να φτάσει στο γράμμα Β | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Β](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Β)

Στόχος να φτάσει στο γράμμα Γ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Γ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Γ)

Στόχος να φτάσει στο γράμμα Δ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Δ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Δ)

Στόχος να φτάσει στο γράμμα Ε | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ε](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ε)

Στόχος να φτάσει στο γράμμα Ζ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ζ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ζ)

Στόχος να φτάσει στο γράμμα Η | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Η](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Η)

Στόχος να φτάσει στο γράμμα Θ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Θ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Θ)

Στόχος να φτάσει στο γράμμα Ι | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ι](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ι)

Στόχος να φτάσει στο γράμμα Κ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Κ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Κ)

Στόχος να φτάσει στο γράμμα Λ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Λ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Λ)

Στόχος να φτάσει στο γράμμα Μ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Μ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Μ)

Στόχος να φτάσει στο γράμμα Ν | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ν](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ν)

Στόχος να φτάσει στο γράμμα Ξ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ξ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ξ)

Στόχος να φτάσει στο γράμμα Ο | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ο](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ο)

Στόχος να φτάσει στο γράμμα Π | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Π](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Π)

Στόχος να φτάσει στο γράμμα Ρ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ρ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ρ)

Στόχος να φτάσει στο γράμμα Σ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Σ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Σ)

Στόχος να φτάσει στο γράμμα Τ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Τ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Τ)

Στόχος να φτάσει στο γράμμα Υ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Υ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Υ)

Στόχος να φτάσει στο γράμμα Φ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Φ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Φ)

Στόχος να φτάσει στο γράμμα Χ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Χ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Χ)

Στόχος να φτάσει στο γράμμα Ψ | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ψ](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ψ)

Στόχος να φτάσει στο γράμμα Ω | [https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ω](https://ale3andro.github.io/eprobotkeysnoedit_alx/?letter=Ω)

