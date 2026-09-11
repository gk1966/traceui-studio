# TraceUI — Production & Education Studio

**Version 3.1** · single-file web application · runs entirely in the browser

A browser-based studio that turns a project idea into an explicit, reviewable specification and a
single production brief for generative-AI tools. It is built around one idea: the decisions stay
visible. The application organises the project, points out what is still missing, and produces
deliverables and AI instructions without hiding the choices that produced them.

## Two workspaces

**Education.** Lessons, learning scenarios, websites, quizzes, presentations, worksheets,
simulations, games, infographics and LMS material. This workspace starts from the learning
objective and works outward: audience and prior knowledge, teaching strategy, activities, what the
learner will be able to do, assessment methods, and an alignment matrix that maps each activity to
the evidence it produces.

**Professional design.** Websites, digital products, UI/UX flows, accessible SVG, technical
specifications and a controlled handoff to generative tools. This workspace covers project context
and primary task, components and interaction states, visual system, technical parameters,
accessibility requirements and acceptance checks for the final artefacts.

## What it does

- **Six interface languages** — Greek, English, French, German, Spanish, Italian — with the
  language of the generated material chosen **independently** of the interface language.
- **Step-by-step structure.** Each step states what to supply, what it is for, and what to check
  before continuing. Nothing is generated from an empty specification.
- **Human review gates.** The application asks for a human check at defined points and lets an
  approved version be frozen before the next step. Automated output is never treated as approved
  output.
- **Accessibility as requirements, not a slogan.** Contrast, alternative text, captions and
  transcripts, motion and timing control, accessible authentication and status messages that do
  not rely on colour alone enter the brief as specific, checkable statements.
- **Deliverables and acceptance checks.** The brief is accompanied by the checks a reviewer should
  apply to whatever comes back, so the output is reviewed against the specification rather than
  against a first impression.
- **Export and import.** Projects can be exported and reopened; the generated brief can be copied
  or downloaded.

## Privacy and requirements

The application is a single HTML file. It runs entirely on the client: **no server, no account, no
installation, no analytics, and no network requests of any kind.** Projects are held in your
browser's local storage and never leave the machine unless you export or copy them. Any modern
browser will run it — open the file and it works, online or offline.

## How to use

1. Download `TraceUI_v3.1_Standalone.html`.
2. Open it in a browser (double-click is enough).
3. Choose the interface language and the language of the material you want to produce.
4. Choose a workspace, work through the steps, and review the result against the acceptance checks
   before you use it.

`index.html` is a short landing page describing the application; the studio itself is the
standalone file above.

---

## Ελληνικά

Το **TraceUI** είναι μια εφαρμογή ενός αρχείου που μετατρέπει μια ιδέα έργου σε σαφή, ελέγξιμη
προδιαγραφή και σε ένα ενιαίο prompt παραγωγής για εργαλεία τεχνητής νοημοσύνης, χωρίς να κρύβει
τις αποφάσεις που την παρήγαγαν.

Έχει δύο χώρους εργασίας. Ο **εκπαιδευτικός** ξεκινά από τον μαθησιακό σκοπό και προχωρά σε κοινό,
διδακτική στρατηγική, δραστηριότητες, μεθόδους αξιολόγησης και έναν πίνακα αντιστοίχισης που
συνδέει κάθε δραστηριότητα με το τεκμήριο που παράγει. Ο **επαγγελματικός** καλύπτει ιστοσελίδες,
ψηφιακά προϊόντα, ροές UI/UX, προσβάσιμα SVG, τεχνικές παραμέτρους και ελεγχόμενη παράδοση σε AI.

Η διεπαφή είναι διαθέσιμη σε έξι γλώσσες και η γλώσσα του παραγόμενου υλικού επιλέγεται
**ανεξάρτητα** από τη γλώσσα της εφαρμογής. Σε κάθε βήμα δηλώνεται τι πρέπει να ελεγχθεί πριν τη
συνέχεια, και η εγκεκριμένη έκδοση μπορεί να παγώσει πριν το επόμενο βήμα.

Η προσβασιμότητα μπαίνει ως συγκεκριμένες, ελέγξιμες απαιτήσεις — αντίθεση, εναλλακτικά κείμενα,
υπότιτλοι και απομαγνητοφωνήσεις, έλεγχος κίνησης και χρόνου, μηνύματα κατάστασης που δεν
στηρίζονται μόνο στο χρώμα.

Η εφαρμογή τρέχει **αποκλειστικά τοπικά**: χωρίς διακομιστή, χωρίς λογαριασμό, χωρίς εγκατάσταση,
χωρίς analytics και χωρίς καμία δικτυακή κλήση. Τα έργα μένουν στον φυλλομετρητή σας εκτός αν τα
εξαγάγετε.

---

## Author

**Georgios Korakakis** — Department of Graphic Design and Visual Communication, School of Applied
Arts and Culture, University of West Attica, Egaleo, Athens, Greece.
ORCID: [0009-0005-0042-6348](https://orcid.org/0009-0005-0042-6348)

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0). See `LICENSE`.

## Citation

If you use this application in teaching or research, please cite it using the metadata in
`CITATION.cff`, or the archived record and its DOI.
