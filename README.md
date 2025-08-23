# Anàlisi Servei Radiodiagnòstic
Per fer aquest projecte m'he basat en la meva experiència com a tècnica en radiodiagnòstic. 

# Objectius
- Analitzar les proves radiològiques més realitzades i demandades.
- Identificar els dies i les hores amb més activitat.
- Estudiar el temps d'espera segons la modalitat de la prova radiològica.
- Examinar els perfils de pacients segons l'edat i el sexe.

# Estructura
He estructurat el projecte d'una manera ordenada i pràctica per trobar ràpidament les dades que volguem estudiar:
```
analisi_radiologia/
├── data/                    # Carpeta on guardarem les dades
├── notebooks/               # Carpeta dels notebooks amb l'anàlisi
├── README.md                # Descripció del projecte
├── requirements.txt         # Text dels paquets de Python que s'han d’instal·lar
└── .gitignore               # Evita que pujem arxius innecessaris
```
      
## Introducció per posar en marxa el projecte
1. Primer haurem de descarregar el repositori del GitHub al nostre ordinador i tot seguit canviarem el directori a la carpeta que hem clonat per poder començar a treballar.
```bash
git clone https://github.com/andreatussaz/analisi_radiologia.git
cd analisi_radiologia
```

2. Instal·larem les llibreries per poder executar el projecte dins de la carpeta requirements.txt.
```bash
pip install -r requirements.txt
```

3. Obrim el notebook on podrem executar el codi.
```bash
jupyter notebook notebooks/01_analisi_exploratoria.ipynb
```
