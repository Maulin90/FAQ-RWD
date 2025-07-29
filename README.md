# FAQ-RWD
# 💬 FAQ RWD Project - Powered by Flowise

Project ini adalah sistem FAQ (Frequently Asked Questions) berbasis AI untuk menjawab pertanyaan seputar **Responsif Web Design (RWD)**. Sistem ini dibangun menggunakan **Flowise**, sebuah platform visual no-code untuk menyusun alur LLM (seperti OpenAI GPT).

---

## ⚙️ Persiapan Wajib (Wajib Ikuti Sebelum Menjalankan)

### ✅ 1. Install Node.js versi 20 (WAJIB)


Flowise hanya berjalan stabil di Node.js versi **20.x.x**  
🚫 Jangan gunakan Node.js versi 22 (akan error saat install `faiss-node` dan lainnya)

📥 Download Node.js 20 dari:  
https://nodejs.org/en/download

Lalu cek versi:

```bash
node -v
# Harusnya keluar: v20.x.x

### ✅ 2. Cara Install Flowise For Development Bisa lihat dokumentasi flowise di web

Clone repository Flowise

```bash
git clone https://github.com/FlowiseAI/Flowise.git
cd Flowise

### ✅ 3. Sesudah flowise berjalan masukkan model yang sudah di upload di repo ini
