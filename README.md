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

## 📦 Usage   
python doc_to_bhili.py --file `new.pdf` --lang `hi`  
python doc_to_bhili.py --file `new.docx` --lang `hi`    
python doc_to_bhili.py --file `new.pdf` --lang `en`    
python doc_to_bhili.py --file `new.pdf` --lang `en`     



