# Penggunaan Decision Tree untuk Prediksi Kemenangan pada Game Mobile Legends: Bang Bang

## Deskripsi Proyek
Proyek ini mengimplementasikan algoritma Decision Tree Classifier untuk memprediksi hasil pertandingan Mobile Legends: Bang Bang (Menang/Kalah) berdasarkan 12 fitur statistik permainan, seperti rasio KDA, gold earned, turret destroyed, dan komposisi tim. Model dilatih pada data statistik pertandingan dan mencapai akurasi 100% pada data pelatihan. Proyek ini juga dilengkapi GUI untuk memvisualisasikan alur keputusan Decision Tree secara interaktif.

## Tujuan
- Menganalisis faktor-faktor yang mempengaruhi kemenangan dalam game MLBB.
- Memprediksi hasil pertandingan berdasarkan statistik permainan dan komposisi tim.
- Mendemonstrasikan penerapan machine learning dalam dunia gaming dan e-sports.
- Menyediakan tools analisis untuk membantu pemain/tim meningkatkan strategi bermain.

## Tools & Library
- Python
- Scikit-learn (Decision Tree Classifier)
- Pandas, NumPy (manipulasi data)
- Matplotlib (visualisasi tree)
- Tkinter (GUI)

## Tahapan Proyek
1. **Pengumpulan Data** - Dataset statistik pertandingan MLBB (12 fitur)
2. **Preprocessing** - Konversi fitur ke representasi boolean (True/False)
3. **Pembangunan Model** - Decision Tree Classifier dengan struktur binary (cabang kiri=False, kanan=True)
4. **Traversal Tree** - Prediksi top-down dari root node ke leaf node
5. **Evaluasi** - Accuracy, precision, recall, F1-score, confusion matrix
6. **Visualisasi** - Plot Decision Tree + GUI interaktif

## Hasil
| Metrik | Kalah | Menang |
|---|---|---|
| Precision | 1,00 | 1,00 |
| Recall | 1,00 | 1,00 |
| F1-Score | 1,00 | 1,00 |
| Support | 8 | 22 |
| **Accuracy** | **1,00** | |

- **Root node:** `turret_damage <= 4256.5` → fitur paling berpengaruh.
- **Fitur utama:** KDA ratio, gold earned, turret destroyed, komposisi tim, Lord Skill.

## File Terkait
- Script Python: (./code/decision_tree.py)
- Dataset MLBB: (./data/dataset_mlbb.csv)

## Author
**Fauziah Roikhana Wardah** (dan tim)
- Program Studi S1 Sains Data, Universitas Negeri Surabaya
