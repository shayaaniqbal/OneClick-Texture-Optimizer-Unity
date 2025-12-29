# 🎨 OneClick Texture Optimizer

**Automate your Unity texture import settings in seconds!** 🚀

Stop manually configuring hundreds of textures. **OneClick Texture Optimizer** is a powerful Unity Editor tool that lets you bulk-override texture compression settings for specific platforms, with smart handling for transparency!

---

## 🔥 Features

-   **📁 Bulk Processing**: Target entire folders and process all containing textures at once.
-   **📱 Platform Specific**: Define dedicated settings for **Android**, **iOS**, **Standalone**, or **WebGL**.
-   **🧠 Smart Alpha Detection**: Automatically applies different compression formats for:
    -   Textures **with** Alpha (Transparency)
    -   Textures **without** Alpha (Opaque)
-   **📏 Resolution Control**: Force max texture sizes from **32px** up to **8192px**.
-   **⚡ Friendly Formats**: Select from a clean, organized list of texture formats (ASTC, ETC, DXT, etc.) with readable names.
-   **🎛️ Quality Control**: Fine-tune compression quality with a simple slider.

---

## 🛠️ Installation

1.  Download the package.
2.  Import it into your Unity project (`.unitypackage`).
3.  The tool adds a new menu item: `Tools > Texture Overrider`.

---

## 🚀 How To Use

1.  Open the tool via **Tools > Texture Overrider**.
2.  **Target Folder**: Drag & drop the folder containing your textures into the slot.
3.  **Target Platform**: Select the platform you are optimizing for (e.g., Android, iOS).
4.  **Max Size**: Choose your desired maximum resolution.
5.  **Formats**:
    -   Select a format for textures **WITH** Alpha (e.g., `ASTC 6x6` or `RGBA Compressed ETC2 8 bits`).
    -   Select a format for textures **WITHOUT** Alpha (e.g., `RGB Compressed ETC2 4 bits`).
6.  **Apply**: Hit **Apply Overrides** and watch the magic happen! ✨

---

## 💡 Why use this?

Optimizing build size and runtime memory often requires setting platform-specific overrides. Doing this manually for every texture is a nightmare.

This tool solves the common problem:
> *"I want all my opaque background textures to use **RGB ETC2 4-bit**, but all my transparent UI icons to use **RGBA ETC2 8-bit**, and I want them all max 2048px on Android."*

**OneClick Texture Optimizer** does exactly that in one click.

---

## 👨‍💻 Tech Stack

*   **Unity Editor API** (`AssetDatabase`, `TextureImporter`)
*   **C#**

---

## 📄 License

Free to use in personal and commercial projects. Happy coding! 🎮
