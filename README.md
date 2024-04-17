## Tahapan development prototype:
- Mengumpulkan data: kami mencari sample data dokumen e-book mata pelajaran dan modul ajar melalui google dan PMM (Platform Merdeka Mengajar)
Link:
https://guru.kemdikbud.go.id/perangkat-ajar/toolkits/2pWBRgeWxj
https://buku.kemdikbud.go.id/katalog/ilmu-pengetahuan-alam-dan-sosial-untuk-sdmi-kelas-vi

- Mencari referensi sebagai acuan: tugas "Build a Chatbot to Analyze PDF Documents Using LLM" dan "Chat with multiple PDFs using Gemini Google GenAI"

  Link:
  https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lORC1HUFhYME5TOEVOL2xhYnMvQnVpbGRfYV9DaGF0Ym90X3dpdGhfRmxhc2tfYW5kX1B5dGhvbi5tZCIsInRvb2xfdHlwZSI6Imluc3RydWN0aW9uYWwtbGFiIiwiYWRtaW4iOmZhbHNlLCJpYXQiOjE3MDk3NDg3NzZ9.swnkTB9mWw45lyAC5-5s_bBs2C9RKh9CYZsJHatTlZk

  https://medium.com/@17nagh/chat-with-multiple-pdfs-using-gemini-google-genai-feda4a21bf7f

- Membuat api key di Google AI Studio https://aistudio.google.com/app/apikey

- Membuat file dotenv(.env) untuk menaruh google api key

- Membuat file requirement.txt yang berisi semua requirement yang dibutuhkan

- Selanjutnya kami menyusun kode untuk file app.py.

- Membuat directory "pdf" yang berisi file pdf sebagai context

- Mengupload sample file pdf ke directory "pdf" 

- Setelah membuat file app.py, kode sudah bisa dijalankan dengan menuliskan python -m streamlit run app.py


