# wkhtmltopdf Examples — Ready Commands & Usage

Here are practical examples of using **wkhtmltopdf** to convert HTML to PDF on Windows, Linux, and macOS.

---

## 🧾 Basic Example
```bash
wkhtmltopdf https://example.com output.pdf
🧱 Convert Local File
bash
Copy code
wkhtmltopdf index.html myfile.pdf
🖼️ Add Header and Footer
bash
Copy code
wkhtmltopdf --header-center "Report" --footer-right "[page]" page.html report.pdf
📄 Multiple Pages
bash
Copy code
wkhtmltopdf page1.html page2.html combined.pdf
🔒 Password-Protected PDF
bash
Copy code
wkhtmltopdf --password 12345 page.html secure.pdf
📘 More Resources
Download: https://wkhtmltopdf.com/download/

Docs: https://wkhtmltopdf.com/docs/

Support: https://wkhtmltopdf.com/support/

yaml
Copy code

---






