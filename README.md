# catalogue.fresthomes.com

Frest Homes price catalogue for first leads. Pages are AES-GCM encrypted at build time; the browser decrypts with the catalogue code (PBKDF2-SHA256 300k). Codes rotate monthly (`catalogue/data/codes.json`, two valid at a time). Request form → FormSubmit → auto-reply with the current code. No server, no accounts. Generator in Drive `WEB/gates/`.
