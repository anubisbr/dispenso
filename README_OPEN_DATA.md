Open Data — products_br.db (Derivada)
====================================

Este pacote contém uma cópia derivada dos dados do OpenFoodFacts filtrada para produtos do Brasil (`products_br.db`) destinada a ser publicada para cumprir a obrigação de compartilhamento da licença ODbL quando o app distribui esse DB no bundle.

O que inclui
- `products_br.db` — arquivo SQLite derivado (não incluído neste repositório por padrão).
- `products_br.db.sha256` — checksum SHA256 do ficheiro.
- `LICENSE_ODbL.txt` — referência à licença ODbL v1.0.
- `README_OPEN_DATA.md` — este ficheiro com instruções.

Instruções rápidas
------------------
1. Coloque aqui o arquivo `products_br.db` gerado (ex.: copiar para esta pasta).  
2. Gere um checksum SHA256:  
   ```bash
   shasum -a 256 \"products_br.db\" > products_br.db.sha256
   ```  
3. Faça upload deste ficheiro (e do .sha256) como assets de uma Release no GitHub ou em um URL público (S3, etc.).  
4. No app, atualize o link na tela de Licença para apontar para o Release/URL.

Notas legais
-----------
- Atribuição obrigatória: “Dados: OpenFoodFacts — https://world.openfoodfacts.org — ODbL v1.0.”  
- Ao redistribuir o DB derivado, disponibilize a cópia derivada sob ODbL e inclua atribuição.

