# Hindi/English → Bhili (DOCX/PDF to DOCX)

This project converts **English or Hindi `.docx` or `.pdf` files into Bhili `.docx` files** using the **Adivaani Translation API**, while preserving the original **paragraph/block layout** as much as possible.

It was designed for low-resource language processing, especially for **Bhili**.

---

## ✨ Features

✔️ Input: **English or Hindi**  
✔️ Output: **Bhili (.docx)**  
✔️ Supported formats: **.docx, .pdf**  
✔️ Preserves **paragraph + table + block layout**  
✔️ Uses **Adivaani API** for translation  
✔️ Automatically detects file type  
✔️ Verifies block count before rebuilding DOCX  

---

## 📂 Input → Output

| Input File | Language | Output File |
|------|------|------|
| `input.docx` | English/Hindi | `bhili.docx` |
| `input.pdf` | English/Hindi | `bhili.docx` |

---

## 📦 Installation

Create virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows
