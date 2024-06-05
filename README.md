# rag-TAP

Run python populate_database.py
Run python test_rag.py

# Instaling

Windows powershell - wsl --install
curl https://ollama.ai/install.sh | sh
ollama pull nomic-embed-text
ollama pull mistral
ollama serve


# Vector DB

1 vector por pdf
varios chunks por PDF

Versão mais naive é ter tudo na mesma BD
Senão ter vairias DB cada uma com 1 PDF e depois fazer um filtro das melhores 5
