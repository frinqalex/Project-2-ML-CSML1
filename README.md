 Pneumonia Detection using CNN
 
Acest proiect utilizează Rețele Neuronale Convoluționale (CNN) pentru a detecta automat pneumonia din radiografiile toracice. Modelul a fost dezvoltat iterativ, ajungând la o performanță ridicată prin tehnici avansate de Deep Learning.

📊 Performanță Model
Acuratețe Validare: ~91.8%

Loss (Eroare): 0.22

Stabilitate: Ridicată, utilizând mecanisme de control automat (Callbacks).

🚀 Caracteristici Tehnice
Arhitectură Profundă: 3 straturi de convoluție (32, 64, 128 filtre) pentru extracția detaliată a trăsăturilor.

Augmentarea Datelor: Rotire, zoom și translație pentru a preveni memorarea datelor (Overfitting).

Echilibrarea Claselor: Utilizarea class_weight pentru a gestiona setul de date medical neechilibrat.

Control Inteligent:

EarlyStopping: Oprește antrenarea în punctul de eficiență maximă.

ReduceLROnPlateau: Ajustează viteza de învățare pentru o precizie fină la final.

📁 Structura Dataset-ului
Dataset-ul utilizat este cel creat de Kermany et al., organizat în:

train/: Imagini pentru antrenare (80% utilizate pentru învățare, 20% pentru validare).

test/: Imagini separate pentru evaluarea finală.

Categorii: NORMAL și PNEUMONIA.

🛠️ Tehnologii Utilizate
Python 3

TensorFlow / Keras (Deep Learning Framework)

Matplotlib / Seaborn (Vizualizare date)

Google Colab (Mediu de dezvoltare GPU)

📈 Vizualizarea Rezultatelor
Modelul generează automat un grafic al evoluției acurateței și erorii. Se poate observa o convergență stabilă, demonstrând capacitatea modelului de a generaliza pe date noi, nu doar de a le memora pe cele de antrenament.

📝 Concluzii
Proiectul demonstrează că o abordare iterativă de rafinare a modelului poate duce la rezultate medicale robuste. Deși nu este o variantă finală, sistemul servește drept un punct de plecare solid pentru un instrument de asistență în triajul radiologic.

📚 Bibliografie
Kermany, D., et al. (2018) – „Labeled Optical Coherence Tomography and Chest X-Ray Images for Classification”.

Suport de curs CSML1 - Machine learning - Conf. univ. dr. Elena Pelican	 – Universitatea Ovidius din Constanța
