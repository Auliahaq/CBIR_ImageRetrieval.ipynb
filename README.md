# Content-Based Image Retrieval (CBIR)

Proyek ini mengimplementasikan sistem **Content-Based Image Retrieval (CBIR)**
untuk mencari citra yang paling mirip berdasarkan fitur visual.

## Contoh Hasil Retrieval
<img width="1602" height="472" alt="apel_result" src="https://github.com/user-attachments/assets/d603ee6d-bd6f-4d1c-b22b-2927daa2e2a7" />

## Metode
- Fitur warna (HSV + statistik)
- Fitur tekstur (GLCM)
- Kombinasi warna dan tekstur
- Pengukuran kemiripan: Euclidean Distance

## Evaluasi
- Metrik: Macro Precision@5 (P@5)
- Perbandingan performa antar fitur
- Visualisasi hasil Top-5 retrieval

## Tools
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab
