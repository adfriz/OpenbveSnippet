# OpenBVE Development Snippets

[English](#english) | [Bahasa Indonesia](#bahasa-indonesia)


## English

A collection of Visual Studio Code snippets and Notepad++ auto-completion files designed to speed up object and route development for **OpenBVE**. Supports `.csv` (Object & Route), `.b3d`, and `.animated` formats.

### Key Features
- **Comprehensive**: Covers basic to advanced commands (MeshBuilder, Vertex, Face, Track, Signals, etc.).
- **Smart Placeholders**: Quickly fill in coordinates, colors, and textures without manual typing. Includes dropdowns for specific choices (e.g., BlendMode, WrapMode).
- **Doc-Aligned**: Descriptions and parameters are strictly based on the official [OpenBVE Hugo Documentation](https://openbve-project.net/documentation_hugo/en/).
- **4x Blocks**: Insert 4 vertices, 4 faces, or 4 texture coordinates at once with automatically sequenced numbering (VS Code).
- **Notepad++ Support**: Includes XML files for Notepad++ Auto-Completion, providing parameter hints and command suggestions.
- **Valid JSON**: Pre-validated and ready to use in VS Code.

### How to Install

#### Method 1: Global Snippets (VS Code - For All Projects)
Best if you want the snippets to be always available across all your workspaces.
1. Open VS Code.
2. Go to **File > Preferences > Configure User Snippets** (or **Code > Settings > Configure User Snippets** on macOS).
3. Select **New Global Snippets file...** and create the following files:
   - Name it `openbve-csv.code-snippets` and paste the CSV Object snippet content.
   - Name it `openbve-route.code-snippets` and paste the Route snippet content.
   - Name it `openbve-b3d.code-snippets` and paste the B3D Object snippet content.
   - Name it `openbve-animated.code-snippets` and paste the Animated Object snippet content.
4. **Tip**: You can also merge all snippet contents into a single global file if you prefer.

#### Method 2: .vscode Folder (VS Code - Per Project)
The fastest way if you want to share these snippets with your team or keep them isolated to a specific project.
1. Create a folder named `.vscode` in your project root directory.
2. Copy all `.code-snippets` files from this repo into that folder.
3. Snippets will be automatically detected by VS Code when you open the project.

#### Method 3: Notepad++ Auto-Completion
If you prefer using Notepad++, you can use the provided XML files for auto-completion and parameter hints.
1. Copy the `.xml` files (`openbve_csv.xml`, `openbve_b3d.xml`, `openbve_route.xml`) from this repo.
2. Paste them into the `autoCompletion` folder in your Notepad++ directory (e.g., `C:\Program Files\Notepad++\autoCompletion\` or `%APPDATA%\Notepad++\autoCompletion\`).
3. Open Notepad++ and go to **Settings > Preferences > Auto-Completion**.
4. Check **"Enable auto-completion on each input"**.
5. **Important**: Ensure the Language in Notepad++ is set correctly for the hints to appear:
   - For `.csv` files (Object & Route): Set Language to **CSV** (or create a User-Defined Language named `CSV`).
   - For `.b3d` files: Set Language to **User** (or your specific User-Defined Language name).
6. Restart Notepad++ to apply the changes.

### Reference Lists
Detailed lists of all available prefixes, commands, and their descriptions:
- [CSV Object Prefix List](openbve-csv-object-prefixes.md)
- [CSV Route Prefix List](openbve-route-prefixes.md)
- [B3D Object Prefix List](openbve-b3d-object-prefixes.md)
- [Animated Object Prefix List](openbve-animated-prefixes.md)

**Notepad++ Auto-Completion Files:**
- `openbve_csv.xml` - CSV Object commands
- `openbve_b3d.xml` - B3D Object commands
- `openbve_route.xml` - Route CSV commands

### Usage Tips
- **4x Commands (VS Code)**: Use prefixes like `vexx` (4 Vertex), `aff` (4 Face), or `stcc` (4 Texture Coordinates) for faster building. Press `TAB` to jump between fields.
- **Smart Scoping (VS Code)**: If you use a merged global snippet file, you can add `"scope": "csv"` (or `"plaintext"`) inside specific snippets to restrict where they appear.
- **Language Association (VS Code)**: Add this to your `settings.json` so VS Code recognizes OpenBVE formats and applies syntax highlighting correctly:
  ```json
  "files.associations": {
    "*.csv": "csv",
    "*.b3d": "plaintext",
    "*.animated": "plaintext"
  }
  ```


## Bahasa Indonesia

Kumpulan snippet Visual Studio Code dan file auto-completion Notepad++ untuk mempercepat pembuatan objek dan route di **OpenBVE**. Mendukung format `.csv` (Object & Route), `.b3d`, dan `.animated`.

### Fitur Utama
- **Lengkap**: Mencakup perintah dasar hingga lanjut (MeshBuilder, Vertex, Face, Track, Sinyal, dll).
- **Placeholder Pintar**: Memudahkan pengisian koordinat, warna, dan tekstur tanpa perlu ngetik manual. Sudah termasuk *dropdown* untuk pilihan spesifik (misal: BlendMode, WrapMode).
- **Sesuai Dokumentasi**: Deskripsi dan parameter perintah diambil langsung dari dokumentasi resmi [OpenBVE Hugo](https://openbve-project.net/documentation_hugo/en/).
- **Blok 4x**: Masukkan 4 vertex, 4 face, atau 4 texture coordinates sekaligus dengan penomoran otomatis yang sudah urut (khusus VS Code).
- **Dukungan Notepad++**: Tersedia file XML untuk Auto-Completion Notepad++, lengkap dengan saran command dan hint parameter.
- **Valid JSON**: Struktur file sudah benar dan siap digunakan di VS Code.

### Cara Pasang

#### Cara 1: Global Snippets (VS Code - Untuk Semua Project)
Cocok kalau kamu ingin snippet ini selalu aktif di VS Code untuk semua workspace.
1. Buka VS Code.
2. Pilih menu **File > Preferences > Configure User Snippets** (atau **Code > Settings > Configure User Snippets** di macOS).
3. Pilih **New Global Snippets file...** dan buat file-file berikut:
   - Buat nama `openbve-csv.code-snippets`, lalu paste isi snippet CSV Object.
   - Buat nama `openbve-route.code-snippets`, lalu paste isi snippet Route.
   - Buat nama `openbve-b3d.code-snippets`, lalu paste isi snippet B3D Object.
   - Buat nama `openbve-animated.code-snippets`, lalu paste isi snippet Animated Object.
4. **Tip**: Kamu juga bisa menggabungkan semuanya ke dalam satu file global saja kalau mau.

#### Cara 2: Folder .vscode (VS Code - Per Project)
Cara paling cepat kalau kamu tidak mau repot copy-paste isi file, atau ingin snippet ini khusus untuk project tertentu.
1. Buat folder bernama `.vscode` di dalam folder root project kamu.
2. Copy semua file `.code-snippets` dari repo ini ke dalam folder tersebut.
3. Snippet akan otomatis aktif saat kamu mengerjakan project di folder itu.

#### Cara 3: Auto-Completion Notepad++
Kalau kamu lebih suka pakai Notepad++, kamu bisa pakai file XML yang disediakan untuk auto-completion dan hint parameter.
1. Copy file `.xml` (`openbve_csv.xml`, `openbve_b3d.xml`, `openbve_route.xml`) dari repo ini.
2. Paste ke dalam folder `autoCompletion` di direktori Notepad++ kamu (biasanya di `C:\Program Files\Notepad++\autoCompletion\` atau `%APPDATA%\Notepad++\autoCompletion\`).
3. Buka Notepad++, lalu masuk ke **Settings > Preferences > Auto-Completion**.
4. Centang **"Enable auto-completion on each input"**.
5. **Penting**: Pastikan *Language* di Notepad++ sudah diatur dengan benar agar hint muncul:
   - Untuk file `.csv` (Object & Route): Set Language ke **CSV** (atau buat User-Defined Language bernama `CSV`).
   - Untuk file `.b3d`: Set Language ke **User** (atau nama User-Defined Language yang kamu pakai).
6. Restart Notepad++ agar perubahan diterapkan.

### Daftar Referensi
Daftar lengkap prefix, command, dan deskripsinya:
- [CSV Object Prefix List](openbve-csv-object-prefixes.md)
- [CSV Route Prefix List](openbve-route-prefixes.md)
- [B3D Object Prefix List](openbve-b3d-object-prefixes.md)
- [Animated Object Prefix List](openbve-animated-prefixes.md)

**File Auto-Completion Notepad++:**
- `openbve_csv.xml` - Command CSV Object
- `openbve_b3d.xml` - Command B3D Object
- `openbve_route.xml` - Command Route CSV

### Tips Penggunaan
- **Command 4x (VS Code)**: Pakai prefix seperti `vexx` (untuk 4 Vertex), `aff` (untuk 4 Face), atau `stcc` (untuk 4 Texture Coordinates). Tekan `TAB` untuk pindah antar kolom.
- **Filter Bahasa / Scope (VS Code)**: Kalau kamu pakai satu file global yang digabung, kamu bisa menambahkan `"scope": "csv"` atau `"plaintext"` di dalam snippet tertentu agar hanya muncul di format file yang diinginkan.
- **Asosiasi File (VS Code)**: Tambahkan setting ini di `settings.json` VS Code kamu biar format OpenBVE dikenali dengan benar:
  ```json
  "files.associations": {
    "*.csv": "csv",
    "*.b3d": "plaintext",
    "*.animated": "plaintext"
  }
  ```