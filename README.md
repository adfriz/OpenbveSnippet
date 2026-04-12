# OpenBVE Development Snippets

[English](#english) | [Bahasa Indonesia](#bahasa-indonesia)


## English

A collection of Visual Studio Code snippets designed to speed up object and route development for **OpenBVE**. Supports `.csv` (Object & Route), `.b3d`, and `.animated` formats.

### Key Features
- **Comprehensive**: Covers basic to advanced commands (MeshBuilder, Vertex, Face, Track, Signals, etc.).
- **Smart Placeholders**: Quickly fill in coordinates, colors, and textures without manual typing.
- **Doc-Aligned**: Descriptions are based on the official [OpenBVE Hugo Documentation](https://openbve-project.net/documentation_hugo/en/).
- **4x Blocks**: Insert 4 vertices or 4 faces at once with automatically sequenced numbering.
- **Valid JSON**: Pre-validated and ready to use in VS Code.

### How to Install

#### Method 1: Global Snippets (For All Projects)
Best if you want the snippets to be always available.
1. Open VS Code.
2. Go to **File > Preferences > Configure User Snippets**.
3. Select **New Global Snippets file...** for each format:
   - Name it `openbve-csv.code-snippets`, then paste the content of `OpenbveCSV.code-snippet`.
   - Name it `openbve-route.code-snippets`, then paste the content of `OpenbveRoute.code-snippet`.
   - Repeat for B3D and Animated formats.
4. **Tip**: You can also merge all snippet contents into a single global file.

#### Method 2: .vscode Folder (Per Project)
The fastest way if you don't want to copy-paste.
1. Create a folder named `.vscode` in your project root.
2. Copy all `.code-snippet` files from this repo into that folder.
3. Snippets will be automatically detected by VS Code.

### Reference Lists
- [CSV Object Prefix List](CSV_Prefix_List.md)
- [CSV Route Prefix List](Route_Prefix_List.md)
- [B3D Prefix List](B3D_Prefix_List.md)
- [Animated Prefix List](ANIMATED_Prefix_List.md)

### Usage Tips
- **4x Commands**: Use prefixes like `vexx` (4 Vertex) or `aff` (4 Face) for faster building. Press `TAB` to move between fields.
- **Smart Scoping**: Add `"scope": "csv"` inside your global snippet file to restrict them to CSV files only.
- **Language Association**: Add this to your `settings.json` so VS Code recognizes OpenBVE formats:
  ```json
  "files.associations": {
    "*.csv": "csv",
    "*.b3d": "plaintext",
    "*.animated": "plaintext"
  }
  ```


## Bahasa Indonesia

Kumpulan snippet Visual Studio Code untuk mempercepat pembuatan objek dan route di **OpenBVE**. Mendukung format `.csv` (Object & Route), `.b3d`, dan `.animated`.

### Fitur Utama
- **Lengkap**: Mencakup perintah dasar hingga lanjut (MeshBuilder, Vertex, Face, Track, Sinyal, dll).
- **Placeholder Pintar**: Memudahkan pengisian koordinat, warna, dan tekstur tanpa perlu ngetik manual.
- **Sesuai Dokumentasi**: Deskripsi perintah diambil langsung dari dokumentasi resmi [OpenBVE Hugo](https://openbve-project.net/documentation_hugo/en/).
- **Blok 4x**: Masukkan 4 vertex atau 4 face sekaligus dengan penomoran otomatis yang sudah urut.
- **Valid JSON**: Struktur file sudah benar dan siap digunakan di VS Code.

### Cara Pasang

#### Cara 1: Global Snippets (Untuk Semua Project)
Cocok kalau kamu ingin snippet ini selalu aktif di VS Code.
1. Buka VS Code.
2. Pilih menu **File > Preferences > Configure User Snippets**.
3. Pilih **New Global Snippets file...** untuk setiap format:
   - Buat nama `openbve-csv.code-snippets`, lalu copy isi dari `OpenbveCSV.code-snippet`.
   - Buat nama `openbve-route.code-snippets`, lalu copy isi dari `OpenbveRoute.code-snippet`.
   - Lakukan hal yang sama untuk format B3D dan Animated.
4. **Tip**: Kamu juga bisa menggabungkan semuanya ke dalam satu file global saja.

#### Cara 2: Folder .vscode (Per Project)
Cara paling cepat kalau kamu tidak mau repot copy-paste isi file.
1. Buat folder bernama `.vscode` di dalam folder project kamu.
2. Copy semua file `.code-snippet` dari repo ini ke dalam folder tersebut.
3. Snippet akan otomatis aktif saat kamu mengerjakan project di folder itu.

### Daftar Referensi
- [CSV Object Prefix List](CSV_Prefix_List.md)
- [CSV Route Prefix List](Route_Prefix_List.md)
- [B3D Prefix List](B3D_Prefix_List.md)
- [Animated Prefix List](ANIMATED_Prefix_List.md)

### Tips Penggunaan
- **Command 4x**: Pakai prefix seperti `vexx` (untuk 4 Vertex) atau `aff` (untuk 4 Face). Tekan `TAB` untuk pindah antar kolom.
- **Filter Bahasa (Scope)**: Tambahkan `"scope": "csv"` di dalam file snippet global agar hanya muncul di file CSV.
- **Asosiasi File**: Tambahkan setting ini di `settings.json` VS Code kamu:
  ```json
  "files.associations": {
    "*.csv": "csv",
    "*.b3d": "plaintext",
    "*.animated": "plaintext"
  }
  ```
