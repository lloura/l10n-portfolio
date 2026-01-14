## [Complete and standardize Brazilian Portuguese (pt_BR) translation #1025](https://github.com/Jeffser/Alpaca/pull/1025)

This commit finalizes the Brazilian Portuguese (pt_BR) translation with 100% coverage.

The main goal was to ensure high consistency and professional terminology across the entire application interface, providing a clear, natural, and user-friendly experience for Brazilian Portuguese speakers.

---

### Key Standardization Summary

This section outlines the most significant adjustments made to professionalize and standardize the interface:


1. **Critical Verbs (Standardized for UI/Formality):**
   - `Delete` standardized to **"Excluir"** (formal UI term, replacing the informal “deletar”).
   - `Run` standardized to **"Executar"** (technical standard, replacing the informal “rodar”).
   - `Regenerate` consistently translated as **"Gerar Novamente"** (to avoid the contextually awkward “regenerar”).
   - `Pull` (for models/files) translated as **"Baixar"** (Download).
   - `Load` translated as **"Carregar"**.
   - `Manage` translated as **"Gerenciar"**.


2. **Contextual Nouns & Distinctions:**
   - **"Background" distinction:** used **"em segundo plano"** for software processes, and **"Fundo"** / **"Plano de Fundo"** for images.
   - **`Parent Model` / `Child`** adapted to **"Modelo Pai"** / **"Modelo Filho"**.
   - **`Dialog`** adapted to **"Diálogo"** or **"Caixa de Diálogo"** for technical accuracy.
   - **`Quick Ask`** adapted to **"Pergunta Rápida"**.
   - **`Live Chat`** adapted to **"Chat Ao Vivo"**.
   - **`Text-to-speech`** adapted to **"Síntese de Fala"**.


1. **Technical Terms (Kept Untranslated for Accuracy):**
   - **`Embedding`** retained to avoid misleading literal translations.
   - **`Template`** retained to prevent conflict with the already translated **"Modelo"** (used for LLMs).
   - **`Prompt`**, **`Token`**, **`Tag`**, **`Runtime`**, **`Script`**, and **`Socket`** kept as common, widely understood technical anglicisms.

---

### Full Glossary of Implemented Changes

The following glossary lists all verbs, nouns, and contextual phrases standardized or adapted in the pt_BR translation:


**Verbs:** 

`Add` → **Adicionar**, `Attach` → **Anexar**, `Cancel` → **Cancelar**, `Change` → **Alterar**, `Close` → **Fechar**, `Dictate` → **Ditar**, `Eval` → **Avaliação/Avaliar**, `Filter` → **Filtrar**, `Fix` → **Correção/Corrigir**, `Get` → **Obter**, `Hide` → **Ocultar**, `Improve` → **Melhorar**, `Override` → **Sobrescrever**, `Refresh` → **Atualizar**, `Reload` → **Recarregar**, `Remove` → **Remover**, `Render` → **Renderizar**, `Search` → **Pesquisar**, `Show` → **Exibir**, `Tweak` → **Ajustar**, `Update` → **Atualizar**.


**Nouns & Terms:** 

`Activity` → **Atividade**, `Attachments` → **Anexos**, `Chat` → **Conversa**, `Context` → **Contexto**, 
`Description` → **Descrição**, `Directory` → **Diretório**, `Feature` → **Funcionalidade**, `Entry` → **Entrada**, `Arguments` → **Argumentos**, `Files` → **Arquivos**, `Folder` → **Pasta**, `Image Recognition` → **Reconhecimento de Imagem**, `Inference` → **Inferência**, `Instance` → **Instância**, `Languages` → **Idiomas**, `Manager` → **Gerenciador**, `Missing` → **Ausente**, `Notebook` → **Caderno**, `Parameter` → **Parâmetro**, `Selector` → **Seletor**, `Sidebar` → **Barra Lateral**, `Tool` → **Ferramenta**, `Welcome` → **Boas-Vindas**, `Clipboard` → **Área de Transferência**, `Custom` → **Personalizado**, `Default` → **Padrão**, `Multilingual` → **Multilíngue**, `Profile Picture` → **Foto de Perfil**, `Quantization` → **Quantização**, `Web Browser` → **Navegador Web**, `Search Engine` → **Motor de Busca**.


**Phrases & Contextual Expressions:** 

`Are you sure you want to` → **Tem certeza que deseja**,
`Could not retrieve` → **Não foi possível recuperar**,
`It looks a bit empty in here` → **Está um pouco vazio por aqui**, 
`To get started` → **Para começar**.

---


### Maintenance

- Removed all unused 'fuzzy' and commented lines (`#~`) to improve maintainability and readability. 
  Total line count reduced from **6537** to **6126**.
